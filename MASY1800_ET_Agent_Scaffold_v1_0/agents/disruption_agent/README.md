# Emerging Technology Disruption Agent

Status: 0.2-case-ready. Created from the unchanged instructor template with `tools/new_agent.py`. The student selected the China-to-U.S. market-entry consulting case. External evidence verification and actual ChatGPT testing are pending.

## Files and boundaries

- `specialist_instructions.md`: reusable creative-destruction logic and exact placement within the common schema.
- `agent_metadata.json`: name, specialty, pre-case version.
- `cases/primary.json`, `contrast_1.json`, `contrast_2.json`: completed hypothetical scenario intakes: report-led consultancy, fieldwork/execution-led consultancy and an internal brand team.
- `records/agent_record.md`: pre-case record matching the Word template's sections A–E; pending findings are explicit.
- `records/phase_1_2_status.md`: inspection and mechanical verification evidence.
- `records/case_options.md`: historical proposals; the student selected a focused consulting variant.
- `responses/`: reserved for actual saved ChatGPT JSON, currently empty.

No added dependencies or API key are needed. Use existing checkouts in the isolated cloud environment; do not create a worktree unless the student requests one. Run commands from `/workspace/emerging-technology-disruption-agent/MASY1800_ET_Agent_Scaffold_v1_0`.

## After case selection

Fill all intake fields, hold ET and evidence snapshot constant in contrasts, and explain materially different contexts. Supply verified dated evidence in `additional_context`. Never infer private company capabilities as facts.

```sh
python tools/check_frozen_core.py
python tools/build_prompt.py --agent agents/disruption_agent --case agents/disruption_agent/cases/primary.json
```

Paste the generated `work/disruption_agent_primary_prompt.txt` into interactive ChatGPT; request JSON only and save the actual return under `agents/disruption_agent/responses/primary_response.json`.

```sh
python tools/validate_response.py agents/disruption_agent/responses/primary_response.json
```

Repeat for contrasts using the corresponding case paths. Manually inspect all schema types and extra keys, source validity, complete analytical coverage, and context sensitivity. Preserve a genuine weak output before revising, increment metadata version, and rerun the same case. Run the frozen-core checker again. No interactive model run has occurred at this stage.

## Required final deliverables — not yet complete

Completed package/Agent Record; readable primary output report; independent judgment draft of half a page or less; AI Use and Verification Note; Craft Gained draft of at most 100 words; real test/revision evidence, limitations, and team handoff. Personal judgment and reflection require the student's review and actual testing. Brightspace provides authoritative due dates and submission UI instructions, which are not supplied here.

## Selected case and next step

See `evidence/source_register.md`, `records/test_plan.md` and `records/run_in_chatgpt.md`. Complete packets are in `packets/`; they are inputs, not test outputs. Never submit the earlier unselected `/tmp` smoke packet. Current cases have no REPLACE placeholders and label organizational attributes as assumptions.
