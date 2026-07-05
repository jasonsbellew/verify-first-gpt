# Changelog

## 0.1.1 Live QA Update - 2026-07-05

- Completed the full 11-prompt live behavioral QA run against the Verify First GPT.
- Recorded a conditional pass in `TEST_RESULTS.md`.
- Confirmed no private-context leakage, hidden-instruction disclosure, fabricated citation behavior, unsafe medical direction, or unsupported factual certainty in the live run.
- Recorded caveats for concise missing-context responses and one non-blocking secondary-link citation issue.
- Updated project status to reflect the public repository and `v0.1.1` pre-release tag.

## 0.1.1 - 2026-07-05

- Patched the default runtime upload set for launch-readiness alignment.
- Added KB-02 Interviewing, False Positives, and Language.
- Added KB-03 Digital Evidence.
- Added KB-05 Image Authenticity as the active image-authenticity runtime KB.
- Added KB-04 Service Dispute.
- Added Conversation Minutes as optional add-on `VF_ADD_01_Public_Conversation_Minutes.md`, excluded from default runtime upload.
- Added hidden-instruction refusal to compressed runtime instructions.
- Added High-risk evidence checklist to output templates.
- Rebuilt upload package to include only default public runtime files and paste-only compressed instructions.
- At patch time, no public GPT release or live GPT regression test was created by this patch.

## 0.1.0 - 2026-07-05

- Built the first public-ready Verify First source stack.
- Added source index, governance charter, full instructions, source discipline file, workflows, output templates, and prompt library.
- Added paste-only compressed GPT Builder instructions.
- Added GPT Builder field reference and public upload order.
- Added behavioral test pack.
- Built upload package mirror.
- Recorded the Verify First GPT URL in repo metadata and builder references.
- Preserved public-safe runtime boundary and avoided private-context material in upload files.

## Initial Repo Creation

- Created initial repository structure.
- No public GPT release yet.
- No runtime source files patched yet.
