# Verify First GPT

**Status:** Public beta  
**Current release:** `0.1.1`  
**GPT:** [Open Verify First in ChatGPT](https://chatgpt.com/g/g-6a40dea0af9481919dc57f979fb9f57a-verify-first)  
**Website:** [Service Business Command](https://servicebusinesscommand.com/gpts/verify-first?utm_source=github&utm_medium=repository&utm_campaign=public_beta&utm_content=verify_first_readme)

Verify First is a source-discipline and claim-verification GPT stack. It helps users separate facts, assumptions, uncertainty, and unsupported claims before making or communicating a decision.

## Who it is for

- Operators validating claims before acting.
- Teams reviewing sources, evidence quality, and confidence.
- Business owners who need a repeatable verification workflow.
- Users who want explicit uncertainty and risk labeling.

## Main capabilities

- Claim verification and source discipline.
- Confidence and uncertainty labeling.
- Evidence hierarchy and contradiction handling.
- High-risk output boundaries.
- Structured decision support and release QA.

## Repository structure

- `source-active/` — public source files, default runtime knowledge, and optional public add-ons.
- `paste-only/` — compressed GPT Builder instructions; paste them into the Builder and do not upload them as knowledge.
- `upload-package/public-runtime/` — upload-ready public knowledge files.
- `upload-package/paste-only/` — upload-package copy of the Builder instructions.
- `tests/` — release QA prompts and expected behavior.
- `docs/GPT_BUILDER_FIELDS.md` — profile, description, starters, instructions placement, and upload list.

## How to explore it

1. Open the public GPT using the link above.
2. Review the source stack and Builder field guide.
3. Use the tests to understand expected behavior and boundaries.
4. Keep private strategy, credentials, personal data, and user-specific records out of the public runtime.

## Current status

Release `0.1.0` created the first public-ready source stack. Patch `0.1.1` rebuilt the default upload set, added focused runtime knowledge, made Conversation Minutes optional, and tightened hidden-instruction and high-risk-output rules. Live behavioral QA completed with a conditional pass; see `TEST_RESULTS.md`.

## Roadmap

- Resolve remaining conditional-pass findings.
- Expand public test coverage and examples.
- Improve source evaluation and contradiction handling.
- Align future integrations with the Service Business Command roadmap.

## License

No open-source license is currently included. Unless a license is added, normal copyright restrictions apply.
