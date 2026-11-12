# 公共管理案例研究论文写作 Skill

一个面向中文公共管理、公共行政与社会科学案例研究论文的写作 Skill。它把治理、政策、访谈、田野或模拟案例材料，转化为接近《公共管理学报》体例的可投稿论文：问题意识、文献对话、研究设计、案例深描、机制解释、理论贡献与参考文献形成闭环。

当前版本：`3.6.0`　|　许可证：MIT

## 这是什么

这不是通用的“论文润色”提示词，而是一套带阶段门禁的写作流程：

- **先锁定交付物**：现象型、差异型、机制型或框架型，避免选题漂移和结论过度承诺。
- **先建证据链**：案例档案、材料清单、论点—证据矩阵先于正文。
- **先匹配范文体例**：从中文范文反推标题树、摘要结构、问题链和案例分析节奏，不机械套用固定节数。
- **允许模拟但必须标注**：模拟场景、模拟访谈和推演材料使用 `[模拟生成材料]` 等标签，避免与真实材料混淆。
- **成稿有篇幅预算**：完整中文正文默认 15000–17000 字，附章节预算与压缩/扩写顺序。
- **机制图两阶段生成**：先出可审查草图、节点表和图注，用户确认后再生成图像。

## 适用与不适用

适用：

- 中文公共管理、公共行政、政策过程、基层治理、数字政府、社会治理案例研究。
- 《公共管理学报》式概念建构、机制解释、行动策略、框架归纳论文。
- 需要把访谈、政策文件、新闻材料、调研笔记或模拟材料转化为理论机制的论文。
- 需要从范文反推体例，或从 `.md` 文章、段落生成机制图/路径图的任务。

不适用：

- 纯政策简报、新闻评论、工作总结或宣传稿。
- 不涉及案例材料、质性分析或理论机制的纯量化论文。
- 英文 ML/AI 会议论文；请改用对应的 ML paper writing skill。

## 目录结构

```text
.
├── SKILL.md                  # 主流程与锁定行为（入口）
├── AGENTS.md                 # Codex 项目级指导
├── CLAUDE.md                 # Claude Code 项目级指导
├── references/               # 写作规则、体例基准、编码与引文流程
│   ├── cn-exemplar-benchmark.md
│   ├── paper-project-decomposition.md
│   ├── manuscript-length-control.md
│   ├── argumentation-discipline.md
│   ├── introduction-writing-module.md
│   ├── qualitative-analysis-workflow.md
│   ├── mechanism-diagram-generation.md
│   └── ...
├── templates/                # 项目简报、案例档案、证据矩阵、机制图模板
│   ├── CN/                   # 本地范文目录（不随仓库分发）
│   ├── EN/                   # 本地英文文献目录（不随仓库分发）
│   └── image/                # 本地参考图目录（不随仓库分发）
├── config/
│   └── image-generation.example.json
├── docs/dev/                 # 开发过程记录（历史归档）
└── PUBLISHING.md             # 发布到 GitHub 的操作说明
```

## 安装

### Codex

```powershell
git clone https://github.com/<your-name>/<repo>.git "$env:USERPROFILE\.codex\skills\social-science-paper-writing"
```

### Claude Code

```powershell
git clone https://github.com/<your-name>/<repo>.git "$env:USERPROFILE\.claude\skills\social-science-paper-writing"
```

也可以直接在本仓库根目录打开会话；`AGENTS.md` / `CLAUDE.md` 会作为项目级指导被读取。

## 快速开始

直接把选题和材料交给助手，例如：

```text
用这个 skill 写一篇公共管理案例研究论文。
主题：县域数字治理中的部门协同。
材料：3 份政策文件、2 次访谈纪要、1 份会议记录。
目标期刊：《公共管理学报》。
先做项目简报和材料清单，再给我 2–3 篇范文匹配建议，不要直接写全文。
```

推荐的使用顺序：

1. 项目简报与材料摄入（Phase 0）。
2. 范文匹配与体例锁定。
3. 质性编码与论点—证据矩阵。
4. 概念界定与理论绑定。
5. 案例呈现与案例分析。
6. 机制模型、机制图与理论贡献。
7. 全文生成、引文核验与投稿自检。

## 范文语料说明

本仓库**不包含**第三方论文全文。原因有两点：

1. 已发表论文的全文通常受版权保护，不适合随开源仓库分发。
2. 从数据库下载的 PDF 转换稿常带有机构名称、图书馆账号等下载水印，可能暴露使用者身份。

如需使用范文匹配功能，请自行将**你有权使用**的 Markdown 范文放入：

```text
templates/CN/     # 中文公共管理案例研究范文
templates/EN/     # 英文公共管理理论文献
```

这些目录下的 `*.md`、`*.pdf`、`*.png`、`*.jpg` 已被 `.gitignore` 排除，不会误提交到公开仓库。仓库自带的 `references/cn-exemplar-benchmark.md` 仍然提供完整的体例判断标准，即使没有本地语料也可以使用。

## 机制图与生图配置

默认生图端点为 OpenAI 官方接口，可在本地覆盖：

```powershell
Copy-Item config/image-generation.example.json config/image-generation.local.json
$env:IMAGE_API_KEY = "<your image API key>"
```

`config/image-generation.local.json` 已被 `.gitignore` 排除。不要把真实 key 写入任何可提交文件；如使用第三方 OpenAI-compatible 服务，请自行修改 `endpoint` 并确认其字段兼容性。

## 隐私与合规

本仓库已做如下处理：

- 移除了本地绝对路径、个人署名和特定服务账号信息。
- 未包含第三方论文全文、论文图片及含机构下载水印的转换稿。
- 未包含 API key、`.env` 或本地配置文件。
- Git 历史为重新初始化的单一提交，不包含原开发目录的历史记录。

提交前仍建议自查：

```powershell
rg -n "C:\\Users|D:\\Desktop|University Library user|Downloaded from|sk-[A-Za-z0-9]{10,}" .
```

## 许可证

本仓库中的 Skill 指令、模板与文档采用 MIT License，详见 `LICENSE`。

第三方论文、图片及其他外部材料的版权归原作者与出版机构所有，不因本仓库的 MIT 许可证而改变。使用者需自行确保所引入语料的授权与使用范围。

## 贡献

欢迎提交 Issue 或 Pull Request。新增模板时，请同步更新 `templates/README.md` 与 `SKILL.md` 的索引；不要提交真实密钥、受版权保护的全文或含个人/机构信息的材料。
