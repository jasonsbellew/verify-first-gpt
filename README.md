# Verify First GPT

This repository manages the Verify First Custom GPT source stack.

GitHub is the source of truth for this project.

GPT URL: https://chatgpt.com/g/g-6a40dea0af9481919dc57f979fb9f57a-verify-first

`/source-active` contains public source files, default runtime knowledge files, and optional public add-ons.

`/paste-only` contains compressed GPT Instructions intended for the GPT Builder Instructions field. Paste these instructions into the builder; do not upload them as knowledge.

`/upload-package` mirrors the upload-ready public files once they are built:

- `/upload-package/public-runtime` for GPT knowledge uploads.
- `/upload-package/paste-only` for the GPT Builder Instructions field.

`/tests` contains release QA prompts and expected behavior.

Private strategy and user-specific context must not be added to public runtime files.

## Current Release

Release `0.1.0` creates the first public-ready Verify First source stack for claim verification, source discipline, confidence labeling, uncertainty handling, and decision support.

Patch `0.1.1` prepares the stack for public-launch readiness by rebuilding the default upload set, adding focused public runtime KB files, marking Conversation Minutes optional, and tightening hidden-instruction and High-risk output rules.

## Builder Setup

Use `docs/GPT_BUILDER_FIELDS.md` for the GPT profile, description, conversation starters, instructions placement, and knowledge upload list.
