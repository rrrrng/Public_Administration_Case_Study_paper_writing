# CLAUDE.md

This file provides guidance when working on the `social-science-paper-writing` skill package.

## Purpose

This skill generates publication-ready public administration case study papers in the style of 《公共管理学报》. It is not for generic case stories, policy reports, or narrative summaries.

The target quality benchmark is the Chinese exemplar corpus in `templates/CN/`. Treat those articles as the highest-priority style and structure reference.

## Current Design

The skill uses a full-stack paper workflow:

1. Paper project brief, material intake, and case dossier.
2. CN exemplar matching and article-structure lock.
3. Qualitative coding and claim-evidence matrix.
4. Concept definition and theory-case binding.
5. Case presentation and case analysis.
6. Mechanism model, mechanism/path diagram brief, and theoretical contribution.
7. Full manuscript generation, citation verification, and submission checklist.

## Key Rules

- Do not force a fixed 6-section or 7-section structure. Match the article type to `templates/CN/` exemplars.
- Ensure every finished manuscript covers seven functions: problem statement, literature/theory dialogue, research design, case presentation, case analysis, mechanism/theory contribution, and conclusion/discussion.
- Before expanding a new paper, lock the main deliverable type: phenomenon, difference, mechanism, or framework. Use a first-pass conclusion sentence and minimum viable result to control scope.
- For complete Chinese manuscripts, use `references/manuscript-length-control.md`; default body length is 15000-17000 Chinese characters, excluding references, appendices, and material inventories.
- Build `case-dossier`, `material-inventory`, and `claim-evidence-matrix` before drafting the full paper.
- For case analysis, mechanism explanation, theoretical contribution, abstracts, and conclusions, use `references/argumentation-discipline.md`; before writing dialectical logic paragraphs with strong patterns such as “不是……而是……”, “并非……而是……”, “不仅……而且……”, and “只有……才……”, answer what manuscript problem the paragraph targets, what part of the expected result it solves, and whether the argument remains complete without it.
- For mechanism/path diagram requests, build a reviewable diagram brief and draft diagram first; generate the image only after the user confirms the draft.
- Do not use “冲突触发/材料碰撞/机制判断/理论落点” as manuscript headings. These may be internal reasoning steps only.
- Never fabricate citations, interviews, policy files, statistics, or case evidence. Mark unverifiable citations as `[引文待核实]`.
- Do not simulate interviews or fieldwork. When material is insufficient, narrow the scope, downgrade the claim, or mark `[材料待补]`.

## Important Files

- `SKILL.md`: Main workflow and locked behavior.
- `references/paper-project-decomposition.md`: Project-management workflow for locking the deliverable type, usable materials, first-pass conclusion sentence, minimum viable result, and next-paper backlog.
- `references/manuscript-length-control.md`: Length budget and revision order for 15000-17000-character full manuscripts.
- `references/argumentation-discipline.md`: Constraints for high-risk contrastive, additive, and exclusive argument patterns.
- `references/writing-guide.md`: Writing rules distilled from CN-style case papers.
- `references/checklists.md`: Submission and quality checklist.
- `references/full-stack-workflow.md`: End-to-end workflow.
- `references/qualitative-analysis-workflow.md`: Coding and process-tracing guide.
- `references/mechanism-diagram-generation.md`: Workflow for turning `.md` articles/paragraphs and reference images into mechanism diagram briefs and GPT Image prompts.
- `references/image-api-configuration.md`: Local configuration rules for the independent image-generation endpoint, key, model, and size.
- `references/citation-verification-cn.md`: Chinese citation verification rules.
- `templates/CN/`: Chinese exemplar corpus.
- `templates/paper-project-brief-template.md`: Paper project brief template.
- `templates/case-dossier-template.md`: Case dossier template.
- `templates/material-inventory-template.md`: Material inventory template.
- `templates/claim-evidence-matrix.md`: Claim-evidence matrix template.
- `templates/mechanism-models.md`: Mechanism diagram templates.
- `templates/mechanism-diagram-brief.md`: Draft diagram, node table, caption, and image-generation prompt template.
- `config/image-generation.example.json`: Committable example image API configuration. Keep real keys in `config/image-generation.local.json` or environment variables only.

## Maintenance Notes

- Keep all files UTF-8 encoded.
- Avoid reintroducing old fixed-structure rules.
- If adding new templates, link them from `templates/README.md` and `SKILL.md`.
- Never commit real image API keys. `config/image-generation.local.json` is local-only and ignored.
