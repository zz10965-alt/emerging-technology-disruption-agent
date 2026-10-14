# Required behavioral retest — version 0.4-reviewed

The genuine v0 weaknesses and correction criteria are documented in `critical_review.md`. No `*_v1.json` output exists. Do not treat the local regression checks as a model retest.

## Execute

Use a fresh normal ChatGPT conversation for each of:

1. `packets/retest_primary_prompt.txt` → save exact return as `responses/primary_v1.json`.
2. `packets/retest_contrast_1_prompt.txt` → `responses/contrast_1_v1.json`.
3. `packets/retest_contrast_2_prompt.txt` → `responses/contrast_2_v1.json`.

Paste the complete packet and request JSON only. Keep the supplied evidence snapshot; do not browse for different evidence in just one case. If new external evidence is required, preserve it, freeze it consistently for all cases, and document that as a separate experiment. Do not supply the desired category or manually correct the returned answer. Record date, visible model name/settings if known, and any execution failure. Return all outputs to Codex for validation and review. User-supplied results will be recorded as such, not as a witnessed Codex API call.

## Acceptance criteria for actual responses

- All three pass the supplied validator and full common schema; version is 0.4-reviewed.
- Primary does not present the 2027–2029 bin as an evidenced impact forecast. It either justifies timing from supplied evidence or explicitly leaves it undetermined. A hypothetical stress cell is labeled as such.
- Potency separates supported appraisal from a conditional stress scenario and explains materiality conditions. No forced downgrade or forced contrast is required.
- Every context rates its own paid business model; process opportunity/control urgency is labeled separately.
- Internal-brand contrary reasoning addresses product/customer/channel economics rather than consultancy client fees.
- Ledger entries preserve both creation and displacement, attribution/assumptions, stakeholders, timing/unknowns and uncertainty. The pilot stays within stated data/capability boundaries.
- Thresholds are proposed/calibrated honestly; citations retain the November 2023 NBER boundary and exclude unread HBS evidence.
- Unsupported real-world claims remain qualified/abstained; no invented surveys, costs or interviews.

Run the supplied validator for each actual file and the integrity checker. Keep all v0 and v1 bytes unchanged. Record pass, partial improvement or persisting failure by criterion and exact passage. If a criterion fails, preserve it rather than editing the response into compliance. Update the report and Agent Record only with demonstrated outcomes.

## Final status after receipt of v1

The student later supplied three actual v1 responses and a handoff stating they were produced in ONE ChatGPT conversation, not three independent fresh chats. Originals are preserved in responses/ and RETEST_HANDOFF_original.md. All six received v0/v1 JSONs pass independent course/full-schema checks. See retest_assessment.md for observed fixes, partial improvements and residual defects. Earlier statements that no v1 existed are historical, not current status. Version 0.4 remains the tested candidate; no further untested instruction change was substituted.
