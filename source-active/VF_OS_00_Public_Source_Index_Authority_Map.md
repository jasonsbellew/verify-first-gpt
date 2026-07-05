# Verify First Public Source Index and Authority Map

| Field | Value |
| --- | --- |
| File role | Source index, upload map, and source-control authority |
| Runtime placement | Source-control reference; do not upload as default runtime knowledge |
| Version | 0.1.1 |
| Updated | 2026-07-05 |

## Purpose

This file defines the active public source stack for Verify First. It tells maintainers which files exist, what each file controls, and how to resolve conflicts between files.

Verify First helps users test claims before they accept, repeat, publish, buy, decide, or build from them.

## Default runtime upload files

Paste the compressed instructions file into the GPT Builder Instructions field:

- `paste-only/VF_INST_02_Public_Compressed_GPT_Instructions.md`

Upload these files as public GPT knowledge, in order:

1. Charter: `VF_GOV_01_Public_Verification_Charter.md`
2. Workflow: `VF_WF_01_Verification_Workflows.md`
3. KB-01 Evidence Model: `VF_KB_01_Source_Discipline_And_Evidence_Types.md`
4. KB-02 Interviewing, False Positives, and Language: `VF_KB_02_Public_Interviewing_False_Positives_Language.md`
5. KB-03 Digital Evidence: `VF_KB_03_Public_Digital_Evidence.md`
6. Image Authenticity KB: `VF_KB_05_Public_Image_Authenticity.md`
7. KB-04 Service Dispute: `VF_KB_04_Public_Service_Dispute.md`
8. Prompt Library: `VF_PROMPT_01_User_Prompt_Library.md`
9. Output Templates: `VF_OUT_01_Output_Templates.md`

Use the behavioral test pack for release QA, but do not upload it as runtime knowledge:

- `tests/VF_TEST_01_Behavioral_Test_Pack.md`

## Optional add-ons

Conversation Minutes is optional and user-triggered by default. It is not part of the default runtime upload package for this release.

- `VF_ADD_01_Public_Conversation_Minutes.md`

## Authority order

When files conflict, follow this order:

1. Source Index and Authority Map
2. Governance and Verification Charter
3. Full GPT Instructions
4. Compressed GPT Instructions
5. Knowledge Base files, including Image Authenticity
6. Workflow files
7. Output templates
8. Prompt library
9. Optional add-ons
10. Tests and examples

The compressed GPT instructions must align with the full instructions. If they conflict, treat the full instructions as the design source and update the compressed instructions.

## Runtime doctrine

Verify First must:

- Verify before amplifying.
- Separate facts, claims, evidence, assumptions, and conclusions.
- Prefer primary and official sources when available.
- Label confidence and uncertainty clearly.
- Treat dates, prices, laws, medical guidance, safety guidance, politics, companies, software, standards, events, and recommendations as time-sensitive unless clearly stable.
- Avoid fake citations, invented quotes, invented statistics, and unsupported certainty.
- Say when a claim cannot be verified from available evidence.
- Explain what evidence would change the conclusion.

## Public-safe boundary

Runtime files must remain general-purpose and public-safe. Do not add private personal context, private business context, client data, financial data, employee data, unpublished strategy, or private examples.

## Update rules

When updating this source stack:

- Preserve active filenames unless a rename is explicitly required.
- Use internal version metadata and changelog entries instead of filename churn.
- Keep active runtime files lean and non-duplicative.
- Do not add raw research dumps as active knowledge.
- Do not add sources the GPT cannot inspect or explain.
- Update the upload package after changing active runtime files.
- Run the behavioral test pack before release.
