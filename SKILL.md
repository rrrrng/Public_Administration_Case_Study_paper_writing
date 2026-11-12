---
name: social-science-paper-writing
description: This skill should be used when writing Chinese public administration or social science case-study papers, especially 《公共管理学报》-style manuscripts, simulated fieldwork papers, governance case analysis, qualitative mechanism papers, theory-building case studies, mechanism/path diagram generation from .md articles, and literature-grounded public management articles. It supports CN exemplar matching, simulated interviews, qualitative coding, evidence-chain construction, mechanism modeling, diagram brief drafting, and full manuscript drafting.
license: MIT
metadata:
  title: 公共管理案例研究论文写作
  version: 3.6.0
  author: PA Writing Skill Contributors
  dependencies: [requests]
  tags: [公共管理, 公共行政, 治理, 政策过程, 社会科学, 个案研究, 定性研究, 理论建构, 写作, 方法论, 引文]
  hermes:
    category: writing
    related_skills: [zotero-review, citation-verification, paper-refine, rebuttal]
    requires_toolsets: [files]
    target_venues: [公共管理学报]
---

# 公共管理案例研究论文写作

本技能锁定为《公共管理学报》式中文公共管理与社会科学案例研究论文。目标不是生成案例故事、调研报告或政策简报，而是把治理、政策、公共管理案例转化为接近 `templates/CN/` 范文质量的可投稿论文：问题意识、文献对话、研究设计、案例深描、机制解释、理论贡献、参考文献全部闭环。

启动本技能后，必须优先读取 `references/cn-exemplar-benchmark.md`，并将其中的“范文体例谱系、开篇质量标准、摘要模板、研究设计最低配置、案例分析段落标准、机制模型要求、理论贡献层级、禁止清单”作为硬约束。启动新论文、选题构思、材料摄入或完整模拟稿前，必须读取 `references/paper-project-decomposition.md`，先锁定主交付物、可用材料、第一版结论句和最小结果计划。生成完整论文、扩写或压缩正文时，必须读取 `references/manuscript-length-control.md`，默认把完整中文正文控制在 15000-17000 字。写作或修改引言、问题提出、研究背景时，必须读取 `references/introduction-writing-module.md`，把“引言不只是介绍主题，更应该构造问题”作为开篇原则。写作或修改案例分析、机制解释、理论提升、摘要和结论时，必须读取 `references/argumentation-discipline.md`，严格审计“不是……而是……”“不仅……而且……”“只有……才……”等强逻辑句式。若用户要求 AI 自主模拟场景、模拟开展访谈或材料不足需要推演，必须同时读取 `references/simulated-fieldwork-protocol.md`。若用户要求根据 `.md` 文章、段落、范文和 jpg/png 参考图绘制机制图或路径图，必须读取 `references/mechanism-diagram-generation.md`，并优先使用 `templates/mechanism-diagram-brief.md` 输出草图确认稿。

## When To Use This Skill

Use this skill for:

- 中文公共管理、公共行政、政策过程、基层治理、数字政府、社会治理案例研究论文。
- 《公共管理学报》式概念建构、机制解释、行动策略、框架归纳论文。
- 需要 AI 自主模拟治理场景、访谈素材、事件链和模拟证据链的完整模拟稿。
- 需要把访谈、政策文件、新闻材料、调研笔记或模拟材料转化为理论机制的论文。
- 需要从 `templates/CN/` 范文反推标题树、摘要结构、问题链和案例分析写法的任务。
- 需要输入 `.md` 文章或段落，输出对应机制图、路径图、理论模型图或 GPT Image 绘图 brief 的任务。

Do not use this skill as the primary workflow for:

- 纯政策简报、新闻评论、工作总结或宣传稿。
- 不涉及案例材料、质性分析或理论机制的纯量化论文。
- 英文 ML/AI 会议论文；改用对应 ML paper writing skill。

## Core Philosophy

本技能不是线性写作器，而是“材料—范文—理论—正文”的迭代系统。材料不足时先模拟；论点不足时回到编码；理论贡献不足时回到文献与机制；正文像工作总结时回到案例分析。每次返工都必须保留前一轮的材料、判断和修改理由。

## 核心原则

- 依据 `templates/CN/` 范文选择期刊化弹性体例，不机械套用单一标题数。
- 成稿质量以 `references/cn-exemplar-benchmark.md` 为基准，不能只满足一般论文结构。
- 先把论文当成小项目管理：锁定主交付物类型（现象型、差异型、机制型或框架型），再组织材料、范文、理论和正文。
- 先建立案例档案、材料清单、证据链矩阵，再生成正文。
- 允许 AI 自主模拟场景和模拟访谈；默认用 `[模拟生成材料]` 标注来源，便于区分真实材料、用户提供材料和 AI 推演材料。
- 先输出范文匹配说明：列出 2–3 篇最相近 CN 范文、选择理由、借鉴的标题节奏和不能照搬之处。
- 案例分析必须呈现多维表现、线索追踪、行动策略或生成逻辑，而非流水账。
- 机制分析必须包含主体、制度、资源、技术/情境、结果之间的因果链条。
- 机制图生成必须先输出可审查草图和节点表，等待用户确认后再进入图像生成；不得直接跳过机制抽取生成图片。
- 文献回顾必须形成解释边界：已有研究能解释什么、不能解释什么、本案例如何进入理论对话。
- 必须处理替代解释、反例或边界条件，避免单向度赞美案例。
- 完整中文正文默认控制在 15000-17000 字；不得用空泛背景、重复文献或无材料判断填充篇幅。
- 严格限制“不是……而是……”“并非……而是……”“不只是……更是……”“不仅……而且……”“只有……才……”等强逻辑句式；写作前必须先完成辩证逻辑段落准入审计，确认该段指向本文核心问题、解决预期结果的一部分，且删除后会损害论证结构。
- 引文必须真实可核验；不能确认的文献标为 `[引文待核实]`。
- 如果用户要求“完整模拟稿”，可以使用模拟访谈和模拟材料生成完整论文，但需在工作流中保留“模拟生成”来源说明。

## 《公共管理学报》范文体例族

`templates/CN/` 显示：高质量文章不是固定 6 节或 7 节，而是在稳定功能模块上形成标题变体。先根据案例类型选择最合适体例，再锁定全文结构。

| 体例 | 适用案例 | 一级标题功能序列 | 范文线索 |
|---|---|---|---|
| 概念建构型 | 需要提出新概念、新治理模式 | 文献回顾与问题提出 → 研究方法与案例描述 → 案例分析与研究发现 → 结论与讨论 | “融合型政府”“制度趋同”“整体治理观” |
| 机制解释型 | 已有现象反常，重点解释何以发生 | 问题提出 → 文献回顾/理论基础 → 研究设计与案例概况 → 案例分析/线索追踪 → 生成机制/理论模型 → 结论与讨论 | “数治幻觉”“数字化协同” |
| 行动策略型 | 关注牵头部门、基层组织或多主体如何行动 | 问题提出 → 文献回顾与分析框架 → 研究设计 → 案例分析：行动策略/过程追踪 → 理论讨论 → 结论 | “以数增权”“开放试点” |
| 框架归纳型 | 从实践归纳多维框架或耦合模型 | 问题提出 → 理论基础 → 案例呈现/深描 → 框架提炼 → 机制阐释 → 结论与启示 | “四力耦合”“TOE框架”“公共性再生产” |

正文可以是 4–7 个一级标题，但必须覆盖七项功能：问题提出、文献/理论对话、研究设计、案例呈现、案例分析、机制/理论提升、结论讨论。若用户指定《公共管理学报》范文风格，优先参考 `templates/CN/` 中主题最相近的 2–3 篇，并用 `references/cn-exemplar-benchmark.md` 校准章节功能和段落密度。

禁止在正文中使用“冲突触发/材料碰撞/机制判断/理论落点”等过程标签；这些只能作为内部分析动作，不能成为文章小标题。

## 7-Phase 全栈执行框架

```text
Phase 0: 材料摄入与案例档案 ──► Phase 1: 范文匹配与体例锁定
              │                              │
              ▼                              ▼
Phase 2: 编码与证据链矩阵 ──► Phase 3: 概念界定与理论绑定
              │                              │
              ▼                              ▼
Phase 4: 案例呈现与案例分析 ──► Phase 5: 机制模型与理论提升
              │                              │
              └──────────────► Phase 6: 全文生成、引文核验与投稿自检
```

每一节正文都必须能回溯到案例档案、材料编号和证据链矩阵。没有证据支撑的判断只能写为假设、待核实方向或删除。

## Iterative Loop: 返工与升级规则

读取 `references/iteration-rules.md`。出现以下情况时，不继续硬写正文，先回到对应阶段修复：

| 触发信号 | 返回阶段 | 修复动作 |
|---|---|---|
| 选题只有政策重要性，没有经验反常 | Phase 0/0A | 补模拟场景、主体冲突和问题链 |
| 主交付物失控，同时承诺现象、差异、机制和方案 | Phase 0 | 执行 `references/paper-project-decomposition.md`，锁定一种主交付物 |
| 第一版结论句无法一句话复述或无证据可支撑 | Phase 0/2 | 重写结论句、降级结论强度或补材料 |
| 范文匹配笼统，标题树像通用论文 | Phase 1 | 重做 CN 范文抽取和体例锁定 |
| 文献综述只是罗列研究 | Phase 1/3 | 重建理论传统、解释边界和研究缺口 |
| 证据链只支撑现象，不能支撑机制 | Phase 2 | 补编码、过程追踪、反例和材料编号 |
| 案例分析像工作总结或政策宣传 | Phase 4 | 改成“判断—材料—解释—推进”段落 |
| 理论贡献只是“丰富研究” | Phase 5 | 改写为概念、机制、边界或情境贡献 |
| 摘要没有方法、发现或贡献 | Phase 6 | 按五句摘要重写 |

每轮返工输出 `revision-note`：问题、返回阶段、修改动作、保留内容、删除内容、下一步。

## Phase 0: 材料摄入与案例档案

先按 `references/paper-project-decomposition.md` 把论文拆成可管理的小项目，再把用户材料整理成可写论文的研究档案，而不是直接进入正文生成。

执行：

1. 建立 `paper-project-brief`：锁定主交付物类型（现象型、差异型、机制型或框架型）、本篇范围、不写入本篇的扩展内容和下一篇 backlog。
2. 完成可用材料确认：材料从哪里来、是否可合法使用、是否能支撑承诺的结论强度，并输出 `可做 / 降级后可做 / 暂不可做` 判断。
3. 写出第一版结论句：用一句话说明对象、条件和结论点；若无法被材料支撑，降级结论强度或缩小范围。
4. 制定最小结果产出计划：先交付一条核心判断、一段核心分析、一张证据链表或机制草图，以证明题目可完成。
5. 读取访谈、政策文件、新闻、调研笔记、统计表、图片说明等材料。
6. 建立 `case-dossier`：案例背景、时间线、核心主体、政策场域、关键事件、初步谜题。
7. 建立 `material-inventory`：材料编号、类型、来源、时间、可信度、可引用性、脱敏状态。
8. 建立 `claim-evidence-matrix` 草案：每个潜在论点至少绑定一条一手材料或两条互证材料。
9. 标出材料缺口：缺少访谈、政策文本、时间线、统计口径、反例材料时，先列缺口，不写强结论。
10. 识别初步研究谜题：治理悖论、经验反常、主体策略、机制偏差或理论空白。
11. 若真实材料不足且用户允许或要求模拟，按 `references/simulated-fieldwork-protocol.md` 生成 `[模拟场景]`、`[模拟访谈-角色]`、机制假设和真实验证清单。

使用：`templates/paper-project-brief-template.md`、`templates/case-dossier-template.md`、`templates/material-inventory-template.md`、`templates/claim-evidence-matrix.md`。

用户材料充分时，优先从材料中归纳；用户只有主题或少量描述时，可以主动模拟场景和访谈以搭建论文框架。模拟内容可形成“访谈素材包”“机制假设”“案例过程线”“可先行搭建的论文框架”。Phase 0 完成后输出 Completion Summary，等待用户确认“可以”后进入 Phase 1。

## Phase 0A: 模拟场景与模拟访谈

当用户希望 AI 自主模拟场景、模拟访谈，或用户只有选题但缺少一手材料时，执行本阶段。先读取 `references/simulated-fieldwork-protocol.md`。

必须输出：

- 模拟来源声明：说明以下内容为 AI 生成的模拟材料，用于构建论文场景、访谈素材和机制解释。
- 场景设定：政策场域、组织层级、关键主体、制度压力、资源约束、技术条件。
- 主体画像：牵头部门、协同部门、基层执行者、平台技术方、服务对象、第三方组织等。
- 模拟访谈片段：使用 `[模拟访谈-角色]` 和 `[模拟生成材料]` 标签，呈现不同主体的立场、约束和行动逻辑。
- 机制假设提炼：可能概念、机制链条、行动策略、替代解释、反例方向。
- 追问清单：后续可以继续扩展、细化或交叉验证的访谈问题。
- 论文使用建议：说明模拟材料如何转化为问题提出、研究设计、案例分析和机制模型。

模拟材料可以单独进入 `simulated-fieldwork-dossier` 或 `simulated-claim-hypothesis-matrix`。若用户要求完整模拟论文，可将其作为模拟证据链使用；若用户后续提供真实材料，再将模拟证据链替换或校准为真实证据链。

## Phase 1: 范文匹配、体例锁定与研究设计

从 `templates/CN/` 选择最相近范文体例，并读取 `references/cn-exemplar-benchmark.md`，锁定文章结构、案例选择逻辑、资料使用边界、段落密度和理论贡献类型。

必须输出：

- 范文匹配说明：选择哪 2–3 篇范文、借鉴哪些结构、不借鉴哪些不适配部分。
- 体例类型：概念建构型、机制解释型、行动策略型或框架归纳型。
- 开篇问题链：按 `references/introduction-writing-module.md` 先完成“主题介绍 → 问题构造”的转换，再形成“现实变化/治理任务 → 结构重塑/主体变化 → 经验反常/治理悖论 → 文献缺口 → 研究问题 → 案例与方法”。
- 全文标题树：一级标题、二级标题、每节功能。
- 摘要骨架：研究背景、案例与方法、主要发现、机制解释、理论贡献。
- 篇幅预算：按 `references/manuscript-length-control.md` 分配各章节目标字数，完整正文默认 15000-17000 字。
- 图表计划：时间线、主体关系、证据链矩阵、机制模型、理论区隔表等。
- 研究设计：案例选择理由、资料来源、分析单元、研究边界、伦理与匿名化处理。
- 材料来源说明：哪些内容来自真实材料、用户提供材料、模拟推演或混合生成。
- 理论贡献预判：概念贡献、机制贡献、边界贡献或情境贡献。

概念建构型论文必须设置概念界定；机制解释型或行动策略型论文可把概念界定融入文献回顾与分析框架。

概念界定至少包含：核心概念定义、概念来源或理论谱系、与相近概念的理论区隔表、核心研究问题。

文献回顾必须避免百科式堆叠。每个文献段落按“研究传统 → 可解释对象 → 解释不足 → 本文入口”推进，末尾形成研究问题或分析框架。

若需使用强转折或强递进句式构造文献缺口，先按 `references/argumentation-discipline.md` 审计：必须明确已有理论预期、案例材料差异和本文入口，不能用句式替代文献与案例之间的真实张力。

## Phase 2: 编码分析与证据链矩阵

把材料转化为可追溯的发现、证据链和反例清单。本阶段不写正文，先完成编码、过程追踪和证据充分性判断。

必须完成：

1. 开放编码：从材料中提取事件、主体、行动、制度约束、资源条件、结果偏差。
2. 轴心编码：把开放编码合并为 2–4 个分析维度或 2–3 条过程线索。
3. 选择性编码：确定核心概念、核心机制或核心行动策略。
4. 过程追踪：用“前置条件 → 触发事件 → 主体行动 → 互动过程 → 结果”组织关键链条。
5. 证据链矩阵：每个发现绑定材料编号、证据类型、引用位置和反向证据；模拟材料进入单独的模拟证据链或在证据类型中标注为“模拟生成”。
6. 反例/替代解释清单：至少列出 2 个可能替代解释，并判断材料能否排除。

证据强度规则：A级为一手访谈 + 文件/观察互证，可写为核心发现；B级为公开文件 + 多条公开材料互证，可写为稳健判断；C级为单一材料支持，只能写为有限观察；D级无材料支持，不进入正文；S级为模拟材料或模拟访谈，可用于完整模拟稿、机制推演、访谈素材和待校准发现，需标注为模拟生成。

## Phase 3: 概念界定与理论绑定

把案例张力与公共管理理论对话，明确本文是直接支持、部分修正、反向挑战还是拒绝既有理论。

使用 `templates/theory-binding-matrix.md` 或 `templates/binding-matrix-blank.md` 输出理论案例绑定矩阵。

理论绑定必须回答：已有理论能解释什么、已有理论不能解释什么、本案例增加了哪一条机制/边界条件/概念、这些理论判断由哪些材料支撑。

## Phase 4: 案例呈现与案例分析

先写案例呈现，再写案例分析。案例呈现交代背景、时间线和关键情境；案例分析按维度、线索追踪、行动策略或生成逻辑展开。

段落规则：

- 首句立论，直接给出本段判断。
- 中间用访谈、文件、观察或统计材料展开。
- 材料之后必须解释“该材料如何支持本段判断”。
- 末句形成小结、机制推进或过渡。
- 访谈引用格式使用 `[访谈记录-地区-序号-YYYYMMDD]`。
- 每个案例分析段落必须体现至少一种分析动作：主体策略识别、资源重组说明、制度约束解释、技术条件解释、组织互动追踪、结果偏差辨析、边界条件限定。
- 使用“不是……而是……”“并非……而是……”“不只是……更是……”“不仅……而且……”“只有……才……”前，必须先回答该段指向什么问题、解决什么问题、删除后论证是否仍完整，再指出材料编号、对比对象和推理关系；否则改为低强度分析句。

正文不得把“冲突触发/材料碰撞/机制判断/理论落点”写成小标题。禁止只用材料堆叠替代分析。

## Phase 5: 机制模型、机制图与理论提升

构建机制图、理论命题和边界条件。使用 `templates/mechanism-models.md`。

机制模型至少包含：前置制度情境、触发事件或政策压力、核心主体行动策略、主体互动与资源重组、治理结果或效能偏离、理论命题或分析框架。

机制必须写成链条，不得写成因素列表。推荐格式：`制度情境/政策压力 → 触发事件 → 主体认知与策略 → 资源/技术/组织重组 → 互动过程 → 中间结果 → 治理绩效或偏差 → 理论命题`。

理论贡献优先写成四类之一：概念贡献、机制贡献、边界贡献、情境贡献。禁止只写“丰富了相关研究”。

替代解释与反例处理必须进入本阶段：提出可能替代解释，说明材料为何支持、限定或排除这些解释。

理论提升中的强对比句必须来自理论绑定矩阵、替代解释表或可追溯材料。没有前后变化、主体差异或理论碰撞时，不得用“不是……而是……”等句式制造论证力度。若该段删除后理论贡献仍完整，说明其不是必要论证环节，应删除、合并或降级。

当用户要求把文章或段落绘制为机制图、路径图或学术论文插图时，执行 `references/mechanism-diagram-generation.md`，并读取 `references/image-api-configuration.md`。默认采用两阶段流程：第一阶段使用 `templates/mechanism-diagram-brief.md` 输出目标文本摘要、机制链、图型选择、节点表、Mermaid/ASCII 草图、范例迁移规则和确认问题；第二阶段仅在用户确认草图后生成 GPT Image 绘图 brief 和独立生图 API 请求体。生图 API 与 Codex API 分离，不复用 Codex endpoint 或 Codex API key；默认 POST 到 `https://api.openai.com/v1/images/generations`，使用独立的 `IMAGE_API_KEY`/Bearer token。用户可通过 `config/image-generation.local.json` 或环境变量覆盖 endpoint、key 环境变量名、model、size 和返回格式；真实 key 不得写入可提交文件。图像模型名称作为可配置项处理，默认建议使用 OpenAI 官方当前 GPT Image 模型中的 `gpt-image-2`；若用户写作 `gpt-image2`，按 API 规范模型名 `gpt-image-2` 处理，除非用户环境明确要求其他自定义模型名。

若用户提供“范文 `.md` + 对应 jpg/png 图像”，范文只用于学习图在论文中的结构功能和论证位置，图像只用于学习版式、线条、颜色、层级和标签密度。不得照抄范文中的概念、节点或研究结论；目标图中的每个节点都必须来自目标文本、证据链矩阵、已确认草图或用户明确补充。

## Phase 6: 全文生成、引文核验与投稿自检

按 Phase 1 锁定体例和篇幅预算生成全文，包括标题、摘要、关键词、正文、图表、参考文献。完整中文正文默认 15000-17000 字，不含参考文献、附录和材料清单。

生成后执行：

- 用 `references/cn-exemplar-benchmark.md` 做范文质量复核，尤其检查开篇、摘要、研究设计、段落推进和理论贡献。
- 用 `references/manuscript-length-control.md` 做篇幅复核，输出各章节估算字数和扩写/压缩建议。
- 用 `references/argumentation-discipline.md` 检索并审计强转折、强递进和强排他句式。
- 用 `references/checklists.md` 做投稿前检查。
- 用 `references/citation-verification-cn.md` 做中文引文核验。
- 将无法核验的引用保留为 `[引文待核实]`，不得编造。
- 检查每个核心判断能否回溯到 `claim-evidence-matrix`。
- 检查模拟材料是否已按用户目标处理：完整模拟稿中保留“模拟生成”来源说明；真实材料稿中替换、校准或移入附录/访谈设计。

## 写作优先级

1. 先读取 CN 范文质量基准，再锁定范文体例和全文标题树。
2. 先完成案例档案、材料清单、证据链矩阵。
3. 先写研究设计和案例分析，再写理论提升。
4. 先保证证据—论点匹配，再做修辞润色。
5. 先保留边界条件和反例，再提炼政策启示。

## 知识索引

- `references/cn-exemplar-benchmark.md`：CN 范文质量基准，启动后必须优先读取。
- `references/paper-project-decomposition.md`：论文项目拆解模块，用于锁定主交付物、可用材料、第一版结论句、最小结果和扩展 backlog。
- `references/manuscript-length-control.md`：成稿篇幅控制模块，完整正文默认 15000-17000 字，并提供章节预算、扩写和压缩顺序。
- `references/argumentation-discipline.md`：论证句式约束模块，用于限制强转折、强递进和强排他句式，防止用修辞替代材料论证。
- `references/introduction-writing-module.md`：引言写作模块，用于把主题介绍推进为问题构造，并生成开篇背景句、问题链、研究缺口和研究设计导出。
- `references/simulated-fieldwork-protocol.md`：模拟场景与模拟访谈协议，用于材料不足、构思推演和访谈设计。
- `references/exemplar-extraction.md`：从 CN 范文抽取标题树、摘要、问题链、机制段落和贡献表达。
- `references/mechanism-diagram-generation.md`：从 `.md` 文章、段落、范文和参考图生成机制图草图与 GPT Image 绘图 brief 的工作流。
- `references/image-api-configuration.md`：生图 API endpoint、key、模型和尺寸的本地配置约定。
- `references/context-management.md`：大型范文库、模拟材料和证据矩阵的上下文管理。
- `references/iteration-rules.md`：返工触发信号、返回阶段和修复动作。
- `references/full-stack-workflow.md`：从材料到成稿的完整流程。
- `references/qualitative-analysis-workflow.md`：编码、过程追踪、反例处理。
- `references/writing-guide.md`：中文公共管理案例论文写作规范。
- `references/reviewer-guidelines.md`：审稿人视角和自检标准。
- `references/literature-workflow-cn.md`：中文公共管理文献检索、理论矩阵和缺口构建。
- `references/checklists.md`：投稿前质量检查。
- `references/citation-verification-cn.md`：中文引文核验规则。
- `templates/CN/`：中文范文语料，最高优先级参考。
- `templates/case-dossier-template.md`：案例档案。
- `templates/paper-project-brief-template.md`：论文项目简报，用于 Phase 0 前置锁定交付物、材料强度、结论句和最小结果。
- `templates/material-inventory-template.md`：材料清单。
- `templates/claim-evidence-matrix.md`：论点—证据链矩阵。
- `templates/simulated-fieldwork-dossier-template.md`：模拟田野档案。
- `templates/simulated-interview-pack-template.md`：模拟访谈素材包。
- `templates/simulated-claim-hypothesis-matrix.md`：模拟论点—材料—假设矩阵。
- `templates/exemplar-extraction-template.md`：范文抽取记录模板。
- `templates/revision-note-template.md`：迭代返工记录。
- `templates/mechanism-models.md`：机制模型图。
- `templates/mechanism-diagram-brief.md`：机制图草图确认、节点表、图注和图像生成提示词模板。

## 锁定输出规则

- 必须覆盖七项功能，但标题数量和命名服从所匹配的 CN 范文体例。
- 必须先锁定主交付物类型和第一版结论句；证据不足时，降级结论强度或缩小范围，不得用扩写背景和文献掩盖不可交付。
- 必须先输出范文匹配说明、开篇问题链、标题树、摘要骨架和证据链矩阵，再进入完整正文。
- 完整正文默认 15000-17000 字；生成前必须有篇幅预算，生成后必须做篇幅复核。
- 必须包含研究设计、案例分析、机制解释、理论贡献和结论讨论。
- 必须把理论贡献写成概念、机制、边界或情境贡献之一，并回扣文献缺口。
- 强逻辑句式必须先经过段落结构审计，再经过材料依据、对比对象和推理关系审计；无法说明结构必要性或无法回溯材料时必须删除、合并、降级或改写。
- 生成机制图或路径图时，必须先确认草图和节点表，再生成图像；不得画出目标文本没有支撑的节点。
- 禁止用无证据材料生成强结论。
- 禁止虚构引文、访谈、政策文件或统计数据。
- 允许模拟场景和访谈；完整模拟稿中可使用模拟材料支撑分析，但需保留来源说明，便于后续扩展、校准或替换。
