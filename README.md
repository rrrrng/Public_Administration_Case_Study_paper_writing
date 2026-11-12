# 公共管理案例研究论文写作 Skill

面向中文公共管理、公共行政与社会科学案例研究论文的写作 Skill。把治理、政策、访谈和田野材料，转化为接近体例的成熟论文。

当前版本：`3.7.0`　|　许可证：MIT

## 核心能力

- 锁定案例论文类型：现象型、差异型、机制型或框架型。
- 证据链：案例档案、材料清单、论点—证据矩阵先于正文。
- 匹配中文范文体例：从 `templates/CN/` 反推标题树、摘要结构和案例分析节奏。
- 覆盖完整流程：研究设计、案例呈现、机制解释、理论贡献、引文核验。

## 安装

Codex：

```powershell
git clone https://github.com/rrrrng/Public_Administration_Case_Study_paper_writing.git "$env:USERPROFILE\.codex\skills\social-science-paper-writing"
```

Claude Code：

```powershell
git clone https://github.com/rrrrng/Public_Administration_Case_Study_paper_writing.git "$env:USERPROFILE\.claude\skills\social-science-paper-writing"
```

也可以直接在本仓库根目录打开会话，`AGENTS.md` / `CLAUDE.md` 会作为项目级指导被读取。

## 使用

1. 提供真实的政策文件、访谈纪要、调研笔记或公开材料。
2. 先让助手输出项目简报、材料清单和证据矩阵。
3. 确认范文体例和写作范围后，再生成全文。

```text
用这个 skill 写一篇公共管理案例研究论文。
主题：县域数字治理中的部门协同。
材料：3 份政策文件、2 次访谈纪要、1 份会议记录。
先做项目简报和材料清单，再给我 2–3 篇范文匹配建议，不要直接写全文。
```

## 范文语料
仓库已内置两套范文：`templates/CN/` 收录 11 篇中文期刊案例研究范文，`templates/EN/` 收录 185 篇英文公共管理文献，可直接用于体例匹配与理论锚定，用法见 `templates/README.md`。
你也可以把**有权使用**的 Markdown 范文放入 `templates/CN/` 或 `templates/EN/`。

## 许可证
本仓库的 Skill 指令、模板与文档采用 MIT License，详见 `LICENSE`。第三方论文与图片的版权归原作者和出版机构所有。
