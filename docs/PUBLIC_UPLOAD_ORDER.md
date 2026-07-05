# Verify First Public Upload Order

| Field | Value |
| --- | --- |
| File role | Upload checklist |
| Runtime placement | Reference only; do not upload as runtime knowledge |
| Version | 0.1.1 |
| Updated | 2026-07-05 |

## Paste-only instructions

Paste this file into the GPT Builder Instructions field:

1. `paste-only/VF_INST_02_Public_Compressed_GPT_Instructions.md`

Do not upload the compressed instructions as knowledge.

## Default knowledge upload files

Upload these files as GPT knowledge, in order:

1. `source-active/VF_GOV_01_Public_Verification_Charter.md`
2. `source-active/VF_WF_01_Verification_Workflows.md`
3. `source-active/VF_KB_01_Source_Discipline_And_Evidence_Types.md`
4. `source-active/VF_KB_02_Public_Interviewing_False_Positives_Language.md`
5. `source-active/VF_KB_03_Public_Digital_Evidence.md`
6. `source-active/VF_KB_05_Public_Image_Authenticity.md`
7. `source-active/VF_KB_04_Public_Service_Dispute.md`
8. `source-active/VF_PROMPT_01_User_Prompt_Library.md`
9. `source-active/VF_OUT_01_Output_Templates.md`

`source-active/VF_OS_00_Public_Source_Index_Authority_Map.md` is the source-control authority and upload map. It is not uploaded as GPT knowledge for the default runtime package.

`source-active/VF_INST_01_Public_Full_GPT_Instructions.md` is the full design/source-control instruction file. It is not uploaded as GPT knowledge for the default runtime package; use the compressed paste-only instructions in the GPT Builder Instructions field.

`source-active/VF_ADD_01_Public_Conversation_Minutes.md` is optional and excluded from the default upload package.

## Test-only file

Use this file for live GPT testing after upload:

- `tests/VF_TEST_01_Behavioral_Test_Pack.md`

Do not upload the test pack as runtime knowledge.

## Upload package

For convenience, the same default runtime files are mirrored under:

- `upload-package/public-runtime`
- `upload-package/paste-only`

Only files from `upload-package/public-runtime` should be uploaded as GPT knowledge. The file in `upload-package/paste-only` is for the GPT Builder Instructions field. Do not include archive, changelog, test, audit, handoff, optional add-on, or source-control reference files in the default upload package.
