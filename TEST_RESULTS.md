# Test Results

## 0.1.1 Source-Stack Patch Checks

Status: passed

Date: 2026-07-05

## Scope

These are source-stack patch checks only. No live GPT regression tests have been run for this patch.

## Checks Run

- Source Index upload order matches `/upload-package/public-runtime`: passed.
- Default runtime upload package contains 9 public knowledge files: passed.
- Source files mirror upload-package files for default runtime and paste-only compressed instructions: passed.
- No duplicate prompt-library file remains active in the default runtime upload package: passed.
- No KB-05 collision remains: passed.
- Image Authenticity KB is included in the active default runtime upload set: passed.
- Conversation Minutes is optional and excluded from the default upload package: passed.
- Hidden-instruction refusal exists in compressed runtime instructions: passed.
- High-risk evidence checklist exists in output templates: passed.
- Active public runtime files contain no private Jason, Branching Out, client, financial, or personal context: passed.
- `/upload-package` excludes archive, test, changelog, audit, handoff, private-note, source-control reference, full-instructions, and optional add-on files: passed.

## Notes

No live GPT regression tests were run for the 0.1.1 patch.

## 0.1.0 Static Source Checks

Status: passed

Date: 2026-07-05

## Checks Run

- Active runtime inventory present: passed
- Paste-only compressed instructions present: passed
- Upload package mirrors active runtime files: passed
- Upload package mirrors paste-only instructions: passed
- Compressed instructions size check: passed at 4,939 bytes
- Runtime private-name scan: passed
- Placeholder scan: passed
- Non-ASCII scan: passed

## Notes

The static checks verify source-stack structure, package parity, and release hygiene. Live GPT behavior still needs to be tested after the files are uploaded in the GPT Builder.

## Live GPT Testing

Target GPT URL: https://chatgpt.com/g/g-6a40dea0af9481919dc57f979fb9f57a-verify-first

### Instruction Alignment

Pending builder upload.

### Knowledge File Behavior

Pending builder upload.

### Citation and Source Discipline

Pending builder upload.

### Confidence Labeling

Pending builder upload.

### Private Context Leakage

Pending builder upload.
