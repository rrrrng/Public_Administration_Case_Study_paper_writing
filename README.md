# 公共管理案例研究论文写作 Skill

让 AI 写出像中文期刊上的公共管理案例研究论文。

*Turn real governance and policy materials into Chinese case-study manuscripts that read like published journal articles.*

**语言 / Language**　｜　**简体中文**　｜　[English](#english)

## 中文

<details open>
<summary><b>简体中文简介</b>（点击展开 / 折叠）</summary>

面向中文公共管理、公共行政与社会科学案例研究论文的写作 Skill。把治理、政策、访谈和田野材料，转化为接近体例的成熟论文。

当前版本：`3.7.0`　|　许可证：MIT

### 它解决什么问题

多数 AI 写出来的案例论文，读起来像调研报告：背景铺得很长，案例讲成故事，结论停在「丰富了相关研究」。这个 Skill 把期刊论文的隐性规矩拆成可执行的步骤——先判定材料能支撑多强的结论，再选体例、做编码、搭证据链，最后才动笔。

### 核心能力

- 锁定案例论文类型：现象型、差异型、机制型或框架型。
- 证据链：案例档案、材料清单、论点—证据矩阵先于正文。
- 匹配中文范文体例：从 `templates/CN/` 反推标题树、摘要结构和案例分析节奏。
- 覆盖完整流程：研究设计、案例呈现、机制解释、理论贡献、引文核验。
- 七阶段推进：材料摄入 → 范文匹配 → 编码 → 理论绑定 → 案例呈现 → 机制模型 → 全文与自检。
- 质量控制：正文 15000–17000 字、摘要五句结构、证据 A/B/C/D 分级、句式审计、引文核验。

### 安装

Codex：

```powershell
git clone https://github.com/rrrrng/Public_Administration_Case_Study_paper_writing.git "$env:USERPROFILE\.codex\skills\social-science-paper-writing"
```

Claude Code：

```powershell
git clone https://github.com/rrrrng/Public_Administration_Case_Study_paper_writing.git "$env:USERPROFILE\.claude\skills\social-science-paper-writing"
```

也可以直接在本仓库根目录打开会话，`AGENTS.md` / `CLAUDE.md` 会作为项目级指导被读取。

### 使用

1. 提供真实的政策文件、访谈纪要、调研笔记或公开材料。
2. 先让助手输出项目简报、材料清单和证据矩阵。
3. 确认范文体例和写作范围后，再生成全文。

```text
用这个 skill 写一篇公共管理案例研究论文。
主题：县域数字治理中的部门协同。
材料：3 份政策文件、2 次访谈纪要、1 份会议记录。
先做项目简报和材料清单，再给我 2–3 篇范文匹配建议，不要直接写全文。
```

材料以你自己提供的为准：访谈纪要、田野记录、政策文件、统计数据都从你的材料里取。材料不足时会缩小研究范围、降低结论强度，或标注 `[材料待补]`。

### 范文语料

仓库已内置两套范文：`templates/CN/` 收录 11 篇中文期刊案例研究范文，`templates/EN/` 收录 185 篇英文公共管理文献，可直接用于体例匹配与理论锚定，用法见 `templates/README.md`。

你也可以把**有权使用**的 Markdown 范文放入 `templates/CN/` 或 `templates/EN/`。

### 目录结构

```text
SKILL.md            技能主文件：七阶段流程与硬约束
references/         质量基准、篇幅控制、句式纪律、编码与引文规则
templates/          15 个模板：案例档案、材料清单、证据矩阵、机制图 brief
templates/CN/       11 篇中文范文
templates/EN/       185 篇英文文献
config/             生图 API 配置示例（真实 key 走本地文件）
docs/               开发记录
```

### 许可证

本仓库的 Skill 指令、模板与文档采用 MIT License，详见 `LICENSE`。第三方论文与图片的版权归原作者和出版机构所有。

</details>

## English

<details>
<summary><b>English introduction</b> (click to expand)</summary>

A skill package for Codex and Claude Code that turns your governance, policy, interview and fieldwork materials into Chinese public-administration case-study manuscripts shaped like published journal articles.

Current version: `3.7.0`　|　License: MIT

### Why it exists

Most AI-drafted case papers read like field reports: long policy background, the case told as a story, and a conclusion that stops at "this enriches the existing literature." This skill breaks the unwritten rules of journal writing into executable steps — decide how strong a claim your materials can support, pick a genre, code the data, build the evidence chain, and only then write.

### What it does

- Locks a single deliverable type: descriptive, comparative, mechanism-explaining, or framework-building.
- Builds evidence before prose: case dossier, material inventory, claim–evidence matrix.
- Matches house style against 11 Chinese exemplars in `templates/CN/`, with theory anchors in 185 English papers in `templates/EN/`.
- Runs a seven-phase pipeline: material intake → exemplar matching → coding → theory binding → case analysis → mechanism model → full draft and self-check.
- Enforces measurable standards: a 15,000–17,000 character body, a five-sentence abstract, A/B/C/D evidence grading, rhetorical pattern audits, and citation verification.

### Install

Codex:

```powershell
git clone https://github.com/rrrrng/Public_Administration_Case_Study_paper_writing.git "$env:USERPROFILE\.codex\skills\social-science-paper-writing"
```

Claude Code:

```powershell
git clone https://github.com/rrrrng/Public_Administration_Case_Study_paper_writing.git "$env:USERPROFILE\.claude\skills\social-science-paper-writing"
```

You can also open a session in the repository root; `AGENTS.md` and `CLAUDE.md` are picked up as project-level instructions.

### Usage

1. Bring real policy documents, interview transcripts, field notes or public materials.
2. Ask for the project brief, material inventory and evidence matrix first.
3. Confirm the exemplar match and scope, then generate the full draft.

```text
Write a public administration case study with this skill.
Topic: inter-departmental collaboration in county-level digital governance.
Materials: 3 policy documents, 2 interview transcripts, 1 meeting record.
Start with the project brief and material inventory, then suggest 2-3 exemplar matches. Do not draft the full text yet.
```

Materials come from you: interview transcripts, field notes, policy documents and statistics are taken from what you provide. When the materials are thin, the skill narrows the research question, lowers the strength of the claims, or marks the gap as `[material pending]`.

### Exemplar corpus

Two corpora ship with the repository: `templates/CN/` holds 11 Chinese journal articles, and `templates/EN/` holds 185 English public administration papers. Both are used for genre matching and theoretical anchoring; see `templates/README.md`.

You can add your own licensed Markdown exemplars to either folder.

### Repository layout

```text
SKILL.md            main skill file: seven-phase workflow and hard constraints
references/         quality benchmarks, length control, sentence discipline, coding and citation rules
templates/          15 templates: case dossier, material inventory, evidence matrix, diagram brief
templates/CN/       11 Chinese exemplars
templates/EN/       185 English papers
config/             image API configuration example (real keys stay in a local file)
docs/               development notes
```

### License

The skill instructions, templates and documentation in this repository are released under the MIT License; see `LICENSE`. Copyright of the third-party papers and images remains with their original authors and publishers.

</details>

---

[↑ 回到中文](#中文)　｜　[English](#english)
