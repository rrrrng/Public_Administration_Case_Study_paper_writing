# 公共管理案例研究论文写作 Skill

面向中文公共管理、公共行政与社会科学案例研究论文的写作 Skill。它把真实的治理、政策、访谈和田野材料，转化为接近《公共管理学报》体例的可投稿论文。

当前版本：`3.7.0`　|　许可证：MIT

## 核心能力

- 锁定论文类型：现象型、差异型、机制型或框架型，控制选题漂移。
- 先建证据链：案例档案、材料清单、论点—证据矩阵先于正文。
- 匹配中文范文体例：从 `templates/CN/` 反推标题树、摘要结构和案例分析节奏。
- 覆盖完整流程：研究设计、案例呈现、机制解释、理论贡献、引文核验。
- 生成机制图草图：先出节点表和图注，确认后再生成图像。

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
目标期刊：《公共管理学报》。
先做项目简报和材料清单，再给我 2–3 篇范文匹配建议，不要直接写全文。
```

## 范文语料

仓库不附带第三方论文全文。请把你**有权使用**的 Markdown 范文放入 `templates/CN/` 或 `templates/EN/`；这些文件已被 `.gitignore` 排除，不会误提交。

## 许可证

本仓库的 Skill 指令、模板与文档采用 MIT License，详见 `LICENSE`。第三方论文与图片的版权归原作者和出版机构所有。
