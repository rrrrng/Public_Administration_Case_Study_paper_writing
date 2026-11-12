# Notes: PA Skill Project Management

## Project Context

目标项目：`PA-example-paper-writing`

项目性质：中文公共管理/社会科学案例研究论文写作 skill，目标风格为《公共管理学报》式案例研究论文。

## Current Skill Architecture

现有主流程为 Phase 0-6：

1. Phase 0：材料摄入与案例档案。
2. Phase 1：范文匹配、体例锁定与研究设计。
3. Phase 2：编码分析与证据链矩阵。
4. Phase 3：概念界定与理论绑定。
5. Phase 4：案例呈现与案例分析。
6. Phase 5：机制模型、机制图与理论提升。
7. Phase 6：全文生成、引文核验与投稿自检。

## Completed Improvements

### 1. Codex Project Guidance

- Added `AGENTS.md`.
- Synchronized core guidance with `CLAUDE.md`.

### 2. Introduction Writing Module

- Added `references/introduction-writing-module.md`.
- Connected it to `SKILL.md`, `references/writing-guide.md`, `references/cn-exemplar-benchmark.md`, and `references/checklists.md`.
- Core principle: 引言不只是介绍主题，更应该构造问题。

### 3. Paper Project Decomposition Module

- Added `references/paper-project-decomposition.md`.
- Added `templates/paper-project-brief-template.md`.
- Connected it to Phase 0 in `SKILL.md`, `references/full-stack-workflow.md`, `references/checklists.md`, `templates/README.md`, and `templates/completion-summary-template.md`.
- Core project rule: 先锁定主交付物，再组织路径、材料和版本。

## Current Git Status Summary

Observed modified files related to recent improvements:

- `AGENTS.md`
- `CLAUDE.md`
- `SKILL.md`
- `references/checklists.md`
- `references/cn-exemplar-benchmark.md`
- `references/full-stack-workflow.md`
- `references/writing-guide.md`
- `references/introduction-writing-module.md`
- `references/paper-project-decomposition.md`
- `templates/README.md`
- `templates/completion-summary-template.md`
- `templates/mechanism-diagram-brief.md`
- `templates/paper-project-brief-template.md`
- `references/mechanism-diagram-generation.md`
- `references/image-api-configuration.md`

Observed pre-existing or user-side changes that should not be reverted without explicit instruction:

- Deleted old PDF exemplar files under `templates/公共管理学报/`.
- Added converted CN markdown exemplars under `templates/CN/`.
- Added `templates/image/`.
- Added or changed `config/`.
- Existing `.gitignore` state.

## Risks

1. `SKILL.md` is growing large and mixes core workflow with detailed policy. Some details may eventually need to move into references for better progressive disclosure.
2. New mandatory Phase 0 project brief improves scope control but may slow down simple writing requests unless the assistant summarizes it compactly.
3. Frontmatter in `SKILL.md` has changed from older flat metadata style to nested `metadata`; confirm target runtime accepts this structure before packaging.
4. Chinese filenames may display as `????` in some shell contexts, though UTF-8 reads are correct when explicitly requested.
5. Existing uncommitted changes include unrelated exemplar conversion/deletion work; commit hygiene requires separating logical commits.

## Recommended Next Actions

1. Run skill validation or package validation if available.
2. Review `SKILL.md` for progressive disclosure: move detailed image API text or long phase details into references if needed.
3. Test a Phase 0 dry run using `paper-project-brief-template.md`.
4. Test an introduction rewrite using `introduction-writing-module.md`.
5. Decide whether to commit all current changes together or split into logical commits.

