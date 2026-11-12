# Templates / Examples

本目录服务于《公共管理学报》式公共管理案例研究论文生成。

## Core Templates

- `article-skeleton.md`：弹性体例文章骨架。
- `paper-project-brief-template.md`：论文项目简报模板，用于锁定主交付物、可用材料、第一版结论句、最小结果和扩展 backlog。
- `case-dossier-template.md`：案例档案模板。
- `material-inventory-template.md`：材料清单模板。
- `claim-evidence-matrix.md`：论点—证据链矩阵。
- `mechanism-models.md`：机制模型与 Mermaid 图模板。
- `mechanism-diagram-brief.md`：机制图草图确认、节点表、图注和 GPT Image 绘图 brief 模板。
- `theory-binding-matrix.md`：理论—案例绑定矩阵。
- `completion-summary-template.md`：Phase 0 总结模板。
- `exemplar-extraction-template.md`：CN 范文结构抽取模板。
- `revision-note-template.md`：迭代返工记录模板。

## Exemplar Corpus

仓库包含两套范文语料：

- `CN/`：11 篇中文公共管理案例研究范文，作为最高优先级体例参考。
- `EN/`：185 篇英文公共管理理论文献，用于理论锚点和写法参考。

用法：先从 `CN/` 选择 2–3 篇最相近范文，用 `exemplar-extraction-template.md` 抽取标题树、摘要、问题链和案例分析段落，再组织用户材料。

## Usage Rule

生成论文前，先使用 `paper-project-brief-template.md` 锁定主交付物、可用材料、第一版结论句、最小结果和扩展 backlog；再从 `CN/` 中选择 2–3 篇相近范文，使用 `exemplar-extraction-template.md` 提取体例、节奏、图表和论证方式，再使用模板组织用户材料。材料不足时缩小范围或标注待补，不得使用 AI 生成的访谈或田野材料。

生成机制图或路径图时，先使用 `mechanism-diagram-brief.md` 输出可审查草图、节点表、图题图注和范例迁移说明，等待用户确认后再生成图片或图像模型提示词。
