# 发布到 GitHub 操作说明

本文假设你使用 Windows PowerShell。仓库已经完成脱敏和初始化，按下面步骤即可发布。

## 0. 前提

- 已注册 GitHub 账号：<https://github.com>
- 已安装 Git：终端执行 `git --version` 能看到版本号
- 已确认本目录不包含真实 API key、受版权保护的论文全文和个人身份信息

## 1. 创建远程仓库

1. 打开 <https://github.com/new>。
2. `Repository name` 建议填：

   ```text
   social-science-paper-writing
   ```

   也可以使用 `PA-example-paper-writing`，名称不影响功能。

3. 选择 `Public`。
4. **不要**勾选 `Add a README file`、`Add .gitignore`、`Choose a license`，否则首次推送会冲突。
5. 点击 `Create repository`。

## 2. 设置提交身份

公开仓库会显示提交者的姓名和邮箱。建议使用 GitHub 的 noreply 邮箱，避免暴露真实邮箱。

1. 打开 GitHub 的 `Settings` → `Emails`。
2. 勾选 `Keep my email addresses private`。
3. 复制形如 `12345678+username@users.noreply.github.com` 的地址。

在仓库根目录执行：

```powershell
git config user.name "你的GitHub用户名"
git config user.email "12345678+username@users.noreply.github.com"
```

当前仓库的首次提交使用了中性的项目身份。如果你希望这次提交显示在自己的 GitHub 账号下，执行：

```powershell
git commit --amend --reset-author --no-edit
```

如果不在意首次提交的署名，可以跳过这一步。

## 3. 关联远程仓库并推送

在 GitHub 新建仓库后，页面会给出仓库地址。把下面的 `<your-name>` 和 `<repo>` 替换成实际值：

```powershell
git remote add origin https://github.com/<your-name>/<repo>.git
git branch -M main
git push -u origin main
```

如果系统弹出登录窗口，选择 `Sign in with your browser` 完成 GitHub 授权即可。

## 4. 验证发布结果

```powershell
git remote -v
git log --oneline -1
git status
```

然后打开 `https://github.com/<your-name>/<repo>`，确认：

- 首页能正常渲染 `README.md`。
- `templates/CN/`、`templates/EN/` 中的语料文件数与 `README.md` 描述一致。
- 文件列表中没有 `config/image-generation.local.json`、`.env` 或 API key。
- 提交作者不是你的真实姓名/私人邮箱（如在意隐私）。

## 5. 后续更新

```powershell
git add .
git commit -m "docs: update writing rules"
git push
```

建议使用 Conventional Commits 风格：`feat:`、`fix:`、`docs:`、`chore:`。

## 6. 发布前安全检查

在仓库根目录执行：

```powershell
rg -n "C:\\Users|D:\\Desktop|University Library user|Downloaded from|sk-[A-Za-z0-9]{10,}" .
git ls-files | Select-String -Pattern "local.json|\.env"
```

理想结果是两条命令都没有输出。若第一条命中，请先删除或替换对应内容；若第二条命中，说明本地密钥配置被加入暂存区，执行：

```powershell
git rm --cached "config/image-generation.local.json"
```

然后重新提交。已经被推送过的敏感内容不会因为后续删除而从 Git 历史中消失，必要时需重写历史或删除仓库重建。

## 7. 关于范文语料

范文语料已随仓库分发。更新语料时，直接替换 `templates/CN/` 或 `templates/EN/` 中的 Markdown 文件，并同步修改 `README.md` 和 `templates/README.md` 中的数量说明。

## 8. 常见问题

**推送被拒绝（rejected / fetch first）**

远程仓库初始化了 README 或 LICENSE，与本地历史不一致。可以先拉取再合并：

```powershell
git pull --rebase origin main
git push -u origin main
```

**提示 `remote origin already exists`**

```powershell
git remote set-url origin https://github.com/<your-name>/<repo>.git
```

**网络超时**

确认代理或网络环境可用；也可以改用 SSH：

```powershell
git remote set-url origin git@github.com:<your-name>/<repo>.git
```

**想改仓库名或描述**

在 GitHub 仓库页面的 `Settings` 中修改，`README.md` 顶部的项目名也建议同步。
