# Project Management Status

## Project

`PA-example-paper-writing` skill improvement and stabilization.

## Current Objective

把该 skill 从“完整论文写作流程”升级为更可控的“论文项目管理 + 写作生成”系统，减少选题漂移、材料不足、结论过度承诺和后期返工。

## Delivery Status

| Workstream | Status | Deliverable |
|---|---|---|
| Codex 初始化 | Done | `AGENTS.md` |
| 引言写作模块 | Done | `references/introduction-writing-module.md` |
| 论文项目拆解模块 | Done | `references/paper-project-decomposition.md` |
| 项目简报模板 | Done | `templates/paper-project-brief-template.md` |
| Phase 0 接入 | Done | `SKILL.md`, `full-stack-workflow.md`, `completion-summary-template.md` |
| 检查表更新 | Done | `references/checklists.md` |
| 项目管理文件 | Done | `task_plan.md`, `notes.md`, `project_management_status.md` |

## Scope Control

### In Scope

- 强制新论文先锁定主交付物类型。
- 强制材料可用性和结论强度匹配。
- 强制先写第一版结论句。
- 强制全文前产出最小结果。
- 把扩展想法放入 next-paper backlog。

### Out of Scope Unless Requested

- 回退旧 PDF 删除。
- 清理或重命名 `templates/CN/` 中的中文文件。
- 合并、压缩或重构大型 EN/CN 范文库。
- 创建 git commit。
- 发布或安装 skill。

## Milestones

| Milestone | Status | Acceptance Criteria |
|---|---|---|
| M1: Project brief introduced | Done | `paper-project-decomposition.md` and template exist; Phase 0 requires them |
| M2: Introduction workflow introduced | Done | Introduction module exists and is referenced by core writing files |
| M3: Quality checklist updated | Done | Checklist includes project brief and introduction items |
| M4: Project management snapshot | Done | Management files created and current risks documented |
| M5: Validation | Pending | Skill structure and references validated by script or manual review |
| M6: Trial run | Pending | One sample topic successfully passes project brief → minimum result |

## Risk Register

| Risk | Impact | Probability | Mitigation |
|---|---|---|---|
| `SKILL.md` becomes too large | Harder to maintain and load | Medium | Move more detail into references later |
| Mandatory project brief feels heavy | Slower simple requests | Medium | Allow compact one-screen brief for simple tasks |
| Evidence downgrade rule frustrates users wanting full mechanism papers | Scope negotiation needed | Medium | Keep downgrade as recommendation with explicit rationale |
| Existing unrelated git changes mix with current work | Commit and review confusion | High | Split commits or review paths before commit |
| Frontmatter compatibility uncertainty | Skill may not load in some runtimes | Medium | Run validator before packaging |

## Immediate Next Actions

1. Validate structure and referenced files.
2. Run one dry test:
   - Input: a rough public administration topic.
   - Expected output: project brief, first-pass conclusion sentence, minimum result plan.
3. Review whether `SKILL.md` should be shortened by moving mechanism-image API detail into references.
4. Decide commit strategy:
   - Commit A: baseline/unrelated exemplar conversion.
   - Commit B: Codex/AGENTS setup.
   - Commit C: introduction module.
   - Commit D: paper project decomposition module.
   - Commit E: project management files.

## Definition of Done

This improvement round is done when:

- Every new required module is referenced from `SKILL.md`.
- Every referenced file exists.
- Phase 0 requires `paper-project-brief`.
- The checklist can detect scope drift, weak materials, and missing minimum result.
- A dry run demonstrates that the skill refuses or downgrades over-promised papers when evidence is weak.

