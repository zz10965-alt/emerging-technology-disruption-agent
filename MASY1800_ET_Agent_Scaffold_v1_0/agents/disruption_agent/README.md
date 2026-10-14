# Emerging Technology Disruption Agent

**Tested candidate: 0.4-reviewed. Actual v0 and v1 outputs received and reviewed. Partial improvement with retained weaknesses; not universally validated decision support.**

Template-derived; common schemas/core/tools unchanged. Standard-library instructor workflow remains sufficient; the installed jsonschema package was additionally used for full-schema review, without changing course dependency declarations.

## Contents

- `responses/`: six untouched user-supplied ChatGPT JSONs, v0 and v1.
- `records/TEST_HANDOFF_original.md` and `RETEST_HANDOFF_original.md`: unchanged runtime provenance. V1 is three responses in ONE ChatGPT conversation, not independent fresh chats.
- `records/validation/`: preservation hashes, executed structural outcomes and final QA.
- `records/critical_review.md`: genuine v0 weaknesses; `retest_assessment.md`: actual v1 correction/partial/non-correction.
- `records/baselines/`: unchanged original v0 metadata, instructions and packets.
- `specialist_instructions.md`: actual tested 0.4 revision. No untested further fix silently substituted.
- `cases/`: same technology and supplied evidence, different revenue/value contexts; attributes hypothetical.
- `packets/`: original v0 and revised retest inputs; they are not output evidence.
- `evidence/`: checked NBER/SBA/NIST scope; HBS unavailable/excluded.
- `deliverables/`: final English course work products in Word/Markdown. Independent judgment/reflection require personal review. `records/agent_record.md` is the source for Word Agent Record.

## Findings and limits

V1 separates conditional primary High stress exposure from unknown realized potency and impact timing. Ancillary-service scope drift, generic counterarguments and incomplete ledger coverage remain. Shared-conversation carryover/settings/transcript limitations preclude claims of independent replication or causal proof of revision effectiveness. No real company data, interviews or pilot outcomes exist.

## Reproduce local structural checks

Use the existing isolated checkout, not a worktree unless explicitly requested. From the scaffold root:

```sh
python tools/check_frozen_core.py
python tools/validate_response.py agents/disruption_agent/responses/primary_v0.json
python tools/validate_response.py agents/disruption_agent/responses/contrast_1_v0.json
python tools/validate_response.py agents/disruption_agent/responses/contrast_2_v0.json
python tools/validate_response.py agents/disruption_agent/responses/primary_v1.json
python tools/validate_response.py agents/disruption_agent/responses/contrast_1_v1.json
python tools/validate_response.py agents/disruption_agent/responses/contrast_2_v1.json
```

The instructor validator checks basic structure; full-schema checks and substantive review are separately recorded. Passing either is not a market-validity claim. Exact case/prompt rebuild checks are in final QA.

## Submission

Use `submission/Assignment_2_Brightspace_Submission.zip` at repository root, with top-level Word documents and full Agent Package. See its manifest and checklist. Add identity/review personal drafts and obey the actual Brightspace item formats/deadline. Historical pending-retest notes/ZIPs are retained as history and superseded by the current actual-retest assessment. No Brightspace upload has been performed.
