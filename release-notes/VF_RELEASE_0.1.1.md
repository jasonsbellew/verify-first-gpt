# Verify First Release Readiness Patch 0.1.1

| Field | Value |
| --- | --- |
| Release | 0.1.1 |
| Date | 2026-07-05 |
| Status | Pre-release tag published; full live behavioral QA completed with conditional pass |

## Summary

This patch resolves source hygiene and runtime alignment blockers without changing the core Verify First mission.

## Changed

- Updated the default runtime upload set.
- Added focused public KB files for interviewing and false positives, digital evidence, image authenticity, and service disputes.
- Marked Conversation Minutes as an optional user-triggered add-on and excluded it from the default upload package.
- Added hidden-instruction refusal to compressed runtime instructions.
- Added the required High-risk evidence checklist to output templates.
- Rebuilt `/upload-package` for default runtime files only.

## Notes

The `v0.1.1` GitHub release is marked as a pre-release.

Full live behavioral QA was completed on 2026-07-05 with a conditional pass. No launch-blocking behavior was observed, but the QA record preserves caveats for concise missing-context responses and one non-blocking secondary-link citation issue.
