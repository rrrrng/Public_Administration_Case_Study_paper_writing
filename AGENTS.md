# AGENTS.md

This repository is the `social-science-paper-writing` skill package for Chinese public administration and social science case-study papers, especially manuscripts in the style of 《公共管理学报》.

## Core Purpose

Use this package to turn public administration, governance, policy, interview, fieldwork, or other real case materials into publication-oriented Chinese case-study manuscripts. Do not treat it as a generic case story, policy memo, work summary, or promotional writing tool.

The highest-priority style and structure reference is the Chinese exemplar corpus in `templates/CN/`. The repository ships 11 Chinese exemplars and 185 English references; start by matching 2-3 CN exemplars.

## Required Workflow

Follow the package workflow in `SKILL.md`:

1. Paper project brief, material intake, and case dossier.
2. CN exemplar matching and article-structure lock.
3. Qualitative coding and claim-evidence matrix.
4. Concept definition and theory-case binding.
5. Case presentation and case analysis.
6. Mechanism model, mechanism/path diagram brief, and theoretical contribution.
7. Full manuscript generation, citation verification, and submission checklist.

Before drafting a full manuscript, build:

- `paper-project-brief`
- `case-dossier`
- `material-inventory`
- `claim-evidence-matrix`

Every substantive claim in the manuscript must be traceable to supplied material, public sources, or an explicit `[材料待补]` / pending-verification note.

## Key Rules

- Do not force a fixed 6-section or 7-section structure. Match the article type to the closest `templates/CN/` exemplars.
- Before expanding a new paper, lock one main deliverable type: phenomenon, difference, mechanism, or framework. If available evidence cannot support the promised type, downgrade the claim strength or narrow the scope.
- Ensure finished manuscripts cover seven functions: problem statement, literature/theory dialogue, research design, case presentation, case analysis, mechanism/theory contribution, and conclusion/discussion.
- For complete Chinese manuscripts, use `references/manuscript-length-control.md`; default body length is 15000-17000 Chinese characters, excluding references, appendices, and material inventories.
- First output exemplar matching: 2-3 closest CN exemplars, why they fit, what structural rhythm to borrow, and what must not be copied.
- For case analysis, mechanism explanation, theoretical contribution, abstracts, and conclusions, use `references/argumentation-discipline.md`; before writing dialectical logic paragraphs with strong patterns such as "不是……而是……", "并非……而是……", "不仅……而且……", and "只有……才……", answer what manuscript problem the paragraph targets, what part of the expected result it solves, and whether the argument remains complete without it.
- Do not use internal process labels such as "冲突触发", "材料碰撞", "机制判断", or "理论落点" as manuscript headings.
- Never fabricate citations, interviews, policy files, statistics, or case evidence.
- Mark unverifiable citations as `[引文待核实]`.
- Do not fabricate interviews, fieldwork records, policy documents, or statistics. When material is insufficient, narrow the scope, downgrade the claim, or mark `[材料待补]`.

## Mechanism Diagrams

For mechanism/path diagram requests:

1. Read `references/mechanism-diagram-generation.md`.
2. Use `templates/mechanism-diagram-brief.md` to produce a reviewable diagram brief, node table, caption, and draft diagram.
3. Wait for user confirmation before generating an image or image-generation prompt.

Keep image-generation API configuration separate from Codex/OpenAI configuration. Use `references/image-api-configuration.md` and never commit real keys. Local secrets belong in `config/image-generation.local.json` or environment variables only.

## Important Files

- `SKILL.md`: Main workflow and locked behavior.
- `CLAUDE.md`: Existing project guidance; keep it aligned with this file when changing repo-level instructions.
- `references/cn-exemplar-benchmark.md`: Required CN exemplar quality benchmark.
- `references/paper-project-decomposition.md`: Project-management workflow for deliverable type, usable material, first-pass conclusion sentence, minimum viable result, and next-paper backlog.
- `references/manuscript-length-control.md`: Length budget and revision order for 15000-17000-character full manuscripts.
- `references/argumentation-discipline.md`: Constraints for high-risk contrastive, additive, and exclusive argument patterns.
- `references/writing-guide.md`: Writing rules distilled from CN-style case papers.
- `references/full-stack-workflow.md`: End-to-end workflow.
- `references/qualitative-analysis-workflow.md`: Coding and process-tracing guide.
- `references/mechanism-diagram-generation.md`: Mechanism/path diagram workflow.
- `references/image-api-configuration.md`: Independent image API configuration rules.
- `references/citation-verification-cn.md`: Chinese citation verification rules.
- `templates/CN/`: Highest-priority Chinese exemplar corpus.
- `templates/paper-project-brief-template.md`: Paper project brief template.
- `templates/case-dossier-template.md`: Case dossier template.
- `templates/material-inventory-template.md`: Material inventory template.
- `templates/claim-evidence-matrix.md`: Claim-evidence matrix template.
- `templates/mechanism-models.md`: Mechanism model templates.
- `templates/mechanism-diagram-brief.md`: Draft diagram and image brief template.
- `config/image-generation.example.json`: Committable example config only.

## Maintenance Notes

- Keep files UTF-8 encoded.
- Preserve Chinese terminology exactly where it is part of the writing protocol.
- Avoid reintroducing old fixed-structure article rules.
- If adding templates, link them from `templates/README.md` and `SKILL.md`.
- Do not commit real API keys, local `.env` files, or `config/image-generation.local.json`.
- The exemplar corpus lives in `templates/CN/` and `templates/EN/`; `templates/image/` holds local-only figures.
