# Verify First Codex Instructions

## Project identity

Verify First is a public Custom GPT source stack for claim verification, source discipline, factual confidence, uncertainty labeling, and decision support.

It helps users slow down before accepting, repeating, buying, publishing, acting on, or building from claims that may be false, outdated, unsupported, exaggerated, misleading, or incomplete.

## Core operating doctrine

- Verify before amplifying.
- Separate facts, claims, evidence, assumptions, and conclusions.
- Prefer primary sources when available.
- Label confidence clearly.
- Distinguish current facts from outdated or time-sensitive claims.
- Identify missing evidence and what would change the conclusion.
- Do not overstate certainty.
- Do not invent citations, sources, quotes, statistics, studies, legal rules, medical claims, financial claims, or technical documentation.
- Do not hide uncertainty behind confident language.

## Public/private boundary

- Do not add Jason, Branching Out Tree Service, private business data, client data, financial data, employee data, or personal context.
- Public runtime files must be general-purpose and safe for public GPT use.
- Private strategy, internal QA notes, source-control history, and personal use cases must not become active public runtime knowledge.

## Source-stack rules

- Preserve stable active filenames unless explicitly instructed otherwise.
- Use internal version metadata and patch notes instead of filename churn.
- Keep active runtime files lean, non-duplicative, and upload-ready.
- Do not create source bloat.
- Do not create raw research dumps as active knowledge.
- Do not invent missing files, test results, source references, or repo history.

## Expected source hierarchy

When conflicts exist, follow:
1. Source Index / Authority Map
2. Governance / Verification Charter
3. Full GPT Instructions
4. Compressed GPT Instructions
5. Knowledge Base files
6. Workflow files
7. Output templates
8. Prompt library
9. Tests / examples

## Required checks before finalizing

- Verify source inventory.
- Verify upload order.
- Verify cross-references.
- Verify no private-context leakage.
- Verify no fake citation behavior.
- Verify confidence labels are used correctly.
- Verify time-sensitive claims trigger current-source discipline.
- Verify public-safe language.
- Verify compressed instructions align with full instructions.

## Deliverables for patch tasks

When asked to patch:
- Update active source files.
- Create or update CHANGELOG.md.
- Create or update TEST_RESULTS.md.
- Create /upload-package containing only upload-ready active files.
- Report changed files and rationale.
