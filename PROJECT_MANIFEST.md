# Project Manifest

- Project name: Verify First
- Repo status: active public source stack built
- Public/private status: public repo; public-safe source target
- Source of truth: GitHub
- GPT URL: https://chatgpt.com/g/g-6a40dea0af9481919dc57f979fb9f57a-verify-first
- Current release status: v0.1.1 pre-release tag published
- Active runtime status: launch-readiness source stack built
- Upload package status: corrected for default public runtime; Source Index and full instructions remain source-control references, not Knowledge uploads
- Live QA status: test 11 fresh rerun passed after live GPT source-control Knowledge removal and stricter hidden-instruction refusal patch
- Live GPT Knowledge note: editor currently shows Source Index and Full GPT Instructions removed from Knowledge; live Knowledge upload parity with the full 9-file default upload package still needs a separate check if launch parity is required
- Next step: verify live GPT Knowledge upload parity against `/upload-package/public-runtime`, then rerun full behavioral QA if the live Knowledge set is changed.

## Source-Control Inventory

- `source-active/VF_OS_00_Public_Source_Index_Authority_Map.md` - source-control authority and upload map; excluded from `/upload-package/public-runtime`
- `source-active/VF_INST_01_Public_Full_GPT_Instructions.md` - full design instructions; excluded from `/upload-package/public-runtime`

## Default Runtime Upload Inventory

- `source-active/VF_GOV_01_Public_Verification_Charter.md`
- `source-active/VF_WF_01_Verification_Workflows.md`
- `source-active/VF_KB_01_Source_Discipline_And_Evidence_Types.md`
- `source-active/VF_KB_02_Public_Interviewing_False_Positives_Language.md`
- `source-active/VF_KB_03_Public_Digital_Evidence.md`
- `source-active/VF_KB_05_Public_Image_Authenticity.md`
- `source-active/VF_KB_04_Public_Service_Dispute.md`
- `source-active/VF_PROMPT_01_User_Prompt_Library.md`
- `source-active/VF_OUT_01_Output_Templates.md`

## Optional Add-On Inventory

- `source-active/VF_ADD_01_Public_Conversation_Minutes.md` - optional, user-triggered, excluded from default upload package

## Paste-Only Inventory

- `paste-only/VF_INST_02_Public_Compressed_GPT_Instructions.md`

## Test Inventory

- `tests/VF_TEST_01_Behavioral_Test_Pack.md`
