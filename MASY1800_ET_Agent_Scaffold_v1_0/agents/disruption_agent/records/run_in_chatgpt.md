# Interactive ChatGPT run and evidence handoff

Status: exact prompt packets prepared; no model responses exist. This Codex session has no callable interface to submit packets into a separate interactive ChatGPT conversation. The course permits handing the actual packets to the student; it does not permit fabricated responses or reported test success.

## Run sequence

1. Open `packets/primary_prompt.txt` in a fresh normal ChatGPT conversation. Paste its COMPLETE contents, or attach the text file and ask: "Execute the attached prompt packet. Return only the JSON object required by its schema. Do not invent evidence."
2. If browsing is available, have ChatGPT open the original candidate sources and verify them. Save its original-source references/excerpts and access dates. Do not confuse an AI-generated source summary with inspected evidence. If browsing is unavailable, preserve the output's qualifications/abstentions; it is not a verified final case report.
3. Save the exact returned JSON, without fixing its analysis, as `responses/primary_v0.json`. Preserve the transcript if the return is invalid or incomplete.
4. Run `packets/contrast_1_prompt.txt` and `packets/contrast_2_prompt.txt` in separate fresh conversations to reduce cross-case anchoring. Save exact returns as `responses/contrast_1_v0.json` and `responses/contrast_2_v0.json`.
5. Return the actual response files and any inspected source excerpts to Codex for validation and analytical review. Do not request invented outputs to fill empty folders.

If new general evidence is verified during one run, freeze the same evidence record for every case and rebuild/repeat the packets. Different evidence availability is a confound, not context sensitivity. Preserve earlier outputs as preliminary runs.

## Local checks after actual responses exist

Run from the scaffold root:

```sh
python tools/validate_response.py agents/disruption_agent/responses/primary_v0.json
python tools/validate_response.py agents/disruption_agent/responses/contrast_1_v0.json
python tools/validate_response.py agents/disruption_agent/responses/contrast_2_v0.json
python tools/check_frozen_core.py
```

The supplied validator performs basic checks only. Independently inspect all schema types, array item types and forbidden extra top-level fields; then review reasoning and source validity. Never describe a format pass as proof of factual or analytical quality.

## Review and revision

Review all seven specialist analyses and all three context levels. Identify one stable general conclusion and one changed contextual judgment, with reasons and evidence. Do not require a different potency merely to make the comparison look successful.

Preserve at least one actual weak/generic/unsupported/contradictory output. Record the exact passage, diagnosis, corrective instruction, version and date. Keep v0; revise the specialist, increment metadata, rebuild packets with the same case/evidence, and save a separate retest output. Do not edit the old response or change the case to hide failure. If no deficiency is found, document actual review honestly and use an informative stress case; do not manufacture a failure.

Only then complete the readable report, half-page independent-judgment draft, verification note, at-most-100-word personal Craft Gained draft, team handoff and final checklist. Personal judgment and reflection remain subject to the student's review. Obtain current Brightspace submission instructions from the course site; no deadline or UI sequence is invented here.

## Subsequent status update

The three v0 responses were later supplied by the student, preserved unchanged, validated and critically reviewed. The opening pre-run status is historical. Use `retest_handoff.md` and `packets/retest_*_prompt.txt` now; no v1 exists. See `critical_review.md` for the genuine deficiencies rather than assuming the original categories are correct.

## Final status after receipt of v1

The student later supplied three actual v1 responses and a handoff stating they were produced in ONE ChatGPT conversation, not three independent fresh chats. Originals are preserved in responses/ and RETEST_HANDOFF_original.md. All six received v0/v1 JSONs pass independent course/full-schema checks. See retest_assessment.md for observed fixes, partial improvements and residual defects. Earlier statements that no v1 existed are historical, not current status. Version 0.4 remains the tested candidate; no further untested instruction change was substituted.
