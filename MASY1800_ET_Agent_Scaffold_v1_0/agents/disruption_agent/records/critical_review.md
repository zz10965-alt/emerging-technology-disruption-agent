# Independent critical review of actual v0 responses

## Provenance and method

The student uploaded `Assignment_2_ChatGPT_Test_Results.zip` containing three JSON responses and a handoff note describing new ChatGPT runs. The JSON files and note are preserved byte-for-byte; the archive/file hashes are in `validation/v0_preservation_manifest.json`. Codex did not witness the external sessions and cannot independently establish model identity, settings or exact execution transcript. The supplied version is 0.3-evidence-checked, matching the retained baseline. No v0 content has been corrected in place.

Codex independently reran the instructor validator and Draft 2020-12 full-schema validation with the installed `jsonschema` package. All three passed both checks. This confirms structure, not analysis. See `validation/v0_validation_results.json` for actual command outcomes.

Source claims were compared with the already-downloaded original NBER November 2023 PDF, SBA page and NIST PDF used in the evidence register. The 14% customer-support result, method distinction and risk categories align with the inspected originals. The replies accurately disclaim direct consulting ROI, independent browser retrieval by the ChatGPT run, and HBS access. No new source retrieval or independent study replication is claimed in this review. The source register supplies more precise NBER revision metadata than the responses' generic '2023 working-paper revision'.

## Context comparison

| Dimension | Primary: report-led firm | Contrast 1: fieldwork-led firm | Contrast 2: internal brand |
|---|---|---|---|
| Paid value / revenue | Fixed-fee research packages | Fieldwork/project fees and execution retainers | Physical-product sales |
| v0 potency | High, conditional | Moderate, conditional | Low for product-sales model; potentially Moderate workflow change |
| v0 matrix | High × Mid-term | Moderate × Near-term for complementary task changes | Low × Near-term internal workflow changes |
| v0 action | Prepare/pilot | Pilot/partner | Absorb as sustaining update, with pilot |
| Independent reading | Core report exposure is plausible; magnitude and arrival evidence absent | Complementary task opportunity is plausible; its magnitude is not core-business threat severity | Narrow tool does not demonstrate product-model disruption; process opportunity must remain separate |

One appropriately stable finding is the limited technology/evidence scope: all three `general_et_finding` strings are exactly identical. All distinguish public-source drafting from validated fieldwork and decline to transfer customer-support productivity estimates into consulting ROI. Identical text alone is not proof of reasoning, but invariance is appropriate for the unchanged evidence snapshot.

One defensibly changed contextual judgment is value capture: selling reports exposes a paid deliverable to possible client self-service, whereas an internal brand does not sell those reports and may treat reduced research effort as an internal benefit. Fieldwork-led delivery requires actual consumer/partner work that the stipulated desk-research capability does not itself perform. These are scenario-based causal distinctions, not measured market outcomes.

The numerical/category ladder High → Moderate → Low is NOT independently validated. The outputs partly change the object being rated; do not use that ladder as the main proof of context sensitivity. All recommend roughly 8–12-week human-supervised pilots, so management actions differ less than their headline labels suggest.

## Genuine weaknesses, exact preserved evidence and correction

### W1 — Unsupported matrix timing and insufficient potency gate (material)

File: `responses/primary_v0.json`, `organization_specific_finding`:

> Business-Model Disruption Potency: High (conditional; low-to-moderate confidence).

> Severity/time placement: High × Mid-term, 2027-10-14 to 2029-10-13, conditional; near-term process exposure already plausible.

Same output, `contrary_evidence_or_limitations`:

> No direct verified experiment on small China-to-U.S. market-entry consultancies, no customer willingness-to-pay or service economics, and no primary customer interviews; the source snapshot cannot quantify pricing changes or displacement.

The first statement is a plausible *stress scenario*, but no evidence chain establishes material substitution, price erosion or those arrival dates. The intake defines time bins; it does not provide a forecast. Merely adding 'conditional' does not distinguish supported appraisal from an assumed adverse scenario. The reviewed position is to defer a supported real-world potency/matrix estimate, describe High as a conditional stress case if its materiality conditions hold, and justify a reversible learning pilot separately. It is not necessary to force a Moderate rating.

Revision: explicit evidence gates and separate supported assessment/stress scenario; impact timing undetermined when unsupported; distinguish pilot schedule from impact timing.

### W2 — Evaluation-object drift across contexts (material)

File: `responses/contrast_1_v0.json`, `organization_specific_finding`:

> Severity/time placement: Moderate × Near-term for complementary task changes through 2027-10-13; mid-term threat to core fieldwork fees remains unproven.

File: `responses/contrast_2_v0.json`, same field:

> Severity/time placement: Low × Near-term internal workflow changes through 2027-10-13; material threat to product business model not established.

The primary assesses a paid business-model threat; the contrasts partly assess process changes. A workflow benefit is not severity of business-model destruction. Low business exposure can be a bounded inference from the specified capability, but lack of evidence must not itself become Low.

Revision: keep each organization's own paid business model as the common assessment object; report process opportunity/control urgency separately. Do not force category differences.

### W3 — Copied counterargument misses the internal brand (moderate)

File: `responses/contrast_2_v0.json`, `contrary_evidence_or_limitations[0]`:

> Strong sustaining/complementary case: AI assistance may cheapen preparation while clients continue paying for judgment, accountability, access and verified customer insight; neither direct substitution nor a low-end disruption trajectory is observed.

This is a consultancy counterargument, reused for a brand whose income is product sales. Common evidence can stay stable; an organization's incumbent defense should not be copied without changing its referent.

Revision: tailor contrary evidence and missing data to product/channel economics for the internal brand; distinguish its suppliers' exposure from its own.

### W4 — Additional controls to assess, not fabricated failures

The primary's 20% cost/25% prospect thresholds are honestly called proposed rather than measured; that is a strength. They are nevertheless uncalibrated and need denominators/baselines before use. Contrast 1 proposes transcript synthesis, which should be separately authorized if it extends the stipulated public-source scope. Ledger entries do not consistently enumerate all required stakeholder/timing/uncertainty fields. The revision adds explicit coverage and scope checks; these are not claims of observed privacy harm or false empirical numbers.

## Revision and retest boundary

The exact original instructions/metadata and packets are preserved in `baselines/`. Version 0.4-reviewed adds controls for W1–W4 without changing core, tools, schema, input cases or evidence. Retest packets are `packets/retest_*_prompt.txt`.

A local rebuild can verify that controls are present and inputs unchanged; it cannot establish corrected model behavior. No separate interactive ChatGPT execution tool is available in this Codex session. Therefore no v1 response is authored or claimed, and behavioral retest remains PENDING until actual returned JSON arrives. A primary retest is essential for W1; both contrasts should also be rerun for W2/W3. This is an explicit blocker to a completed final submission, not a hidden successful test.
