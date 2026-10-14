# Independent assessment of actual v1 retest

## Provenance and performed checks

The student supplied `Assignment_2_Retest_Results_v1.zip` with three model-generated responses and a handoff. The handoff explicitly states that all responses were produced in **one ChatGPT conversation from revised packet specifications**. These are three case outputs, not three independent fresh-chat tests. Codex did not witness the session or an API call; model identity/settings, exact submitted text and full transcript are not independently established. Repository inputs and evidence are unchanged; the handoff reports the shared source snapshot.

All files are preserved byte-for-byte. The uploaded-archive and individual-file hashes are in `validation/v1_preservation_manifest.json`. All three v1 files passed the instructor `tools/validate_response.py` and full Draft 2020-12 common-schema validation with the already-installed `jsonschema` library. Version metadata is 0.4-reviewed in every v1. The original v0 responses/handoff remain unchanged. Core/package hashes remain intact.

The source claims are consistent with the previously checked NBER November 2023 paper, SBA guidance and NIST sections recorded in `evidence/source_register.md`. No new browsing or source replication is asserted for the retest. HBS remains excluded.

## Outcome by revision criterion

| Criterion | Observed result | Independent judgment |
|---|---|---|
| Required schema and metadata | All three course/full-schema checks pass; version 0.4-reviewed | Pass for structure only |
| W1: supported appraisal versus stress scenario | Primary now says 'Present observed potency is Undetermined' and labels High as conditional stress exposure | Material improvement observed |
| W1: unsupported dated impact cell | Primary says 'No substantiated business-impact date: time cell UNDETERMINED'; time bins explicitly not forecasts | Fixed in this response; illustrative cell is not validated placement |
| W2: same business-model object across contexts | Own revenue mechanisms are identified, but contrast 1 still labels Moderate 'task/service exposure' and 'supporting reports'; contrast 2 retains a Low/near 'process-update cell' as illustration | Partial improvement, not a clean comparable category ladder |
| W3: organization-specific contrary reasoning | Internal-brand governance now distinguishes vendor fees from own product sales, but the separate contrary-evidence arrays remain exactly identical across cases | Partial at whole-response level; dedicated-field tailoring not fixed |
| Ledger completeness and scope | Entries name stakeholders/mechanisms/uncertainty; primary fieldwork is not claimed to be automated; not every required element is explicitly covered or marked not material | Improved, partial coverage; no claim of complete specialist compliance |
| Threshold calibration | Acceptance thresholds left to measured baseline, sample and owner; no fabricated 20%/25% empirical rule | Improved observed control discipline |
| Citation precision | November 2023 NBER revision named; 14% is customer-support evidence, not consultancy savings; HBS excluded | Improved; not independent verification by the ChatGPT run |

## Exact preserved passages

**Primary v1, `organization_specific_finding`:**

> Present observed potency is Undetermined—insufficient customer substitution, fees, cost and margin evidence.

> No substantiated business-impact date: time cell UNDETERMINED.

These directly address the v0's unsupported current High/mid-term interpretation. High remains an explicit stress scenario conditional on reliable substitutes displacing the paid report core. The reviewer accepts this calibration; no measured market forecast is inferred.

**Contrast 1 v1, same field:**

> Moderate conditional task/service exposure

> Moderate scenario severity for supporting reports; actual business-model severity and timing undetermined.

The response is more transparent, but still mixes an ancillary-service category with the organization-wide question. Treat its Moderate as a subsidiary scenario only, not a comparable organization-wide measurement.

**Contrast 2 v1, same field:**

> An illustrative Low/near process-update cell would suggest sustaining absorption, but this is NOT a dated measured market impact.

The qualification prevents a false forecast, yet process-update cells should not be used to score business-model threat. Low direct exposure is defensible only within the narrow internal-research capability, not as a finding about all AI threats to the brand.

**All v1 `contrary_evidence_or_limitations[0]`:**

> Sustaining/complementary alternative: firms may use AI to strengthen professionally verified deliverables without changing what clients purchase; AI-produced drafts may increase verification costs.

All three entire contrary-evidence arrays are exactly identical. The internal brand's separate governance paragraph is tailored, but a specific product/channel counter-case in this dedicated field is still missing. This is a preserved residual weakness, not silently corrected JSON.

## Cross-context findings

The general technology findings are exactly identical within v1, appropriately preserving the same narrow capability and source limits. They are rewritten from v0 but remain stable in meaning: assistance is plausible; task gains do not establish client substitution, niche ROI or an adoption date.

The defensibly changed contextual finding is **whose paid value is exposed**. Primary sells reports; contrast 1 sells fieldwork/execution with ancillary briefs; contrast 2 sells goods and uses research internally. Client self-service threatens a paid report differently from an internal cost center. This causal distinction, not the High/Moderate/Low ladder alone, is evidence of useful context sensitivity.

Management actions remain reversible pilots with different owners/measures; the revision improves calibration more than it creates wholly different actions. Pilots were proposed, not performed.

## Limits and final disposition

- Same-conversation generation permits carryover, anchoring and coordinated answers. Exact identical general findings may reflect instruction following or copying; they do not establish independent replication.
- No randomized comparison, repeated samples, known model settings or verified unchanged full-packet execution. Changes are observed improvements, not isolated causal proof that the instruction revision alone caused them.
- Hypothetical firms, no interviews, prices, margin data, real-world adoption outcomes or measured pilot results. No commercial-impact validation or complete ledger compliance established.
- Keep version 0.4-reviewed as the actual tested candidate; do not silently revise to a new untested version to remove remaining defects.

**Disposition:** complete the course submission evidence with a bounded, partially improved specialist and explicit remaining limitations. Do not claim all acceptance criteria passed or three independent fresh chats occurred. A future fresh-session check and dedicated-field/ledger refinement would strengthen reliability, but are recommendations rather than invented completed tests. The final readable report distinguishes actual v1 output from reviewer synthesis. Student review of personal drafts and Brightspace format/date requirements remains necessary.
