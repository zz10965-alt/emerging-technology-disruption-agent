# Emerging Technology Disruption Agent

**Current status: 0.4-reviewed; real v0 responses reviewed, behavioral retest pending. Do not submit as complete yet.**

Created from the unchanged instructor template. All original package/core/tool hashes remain intact. No new framework/API account is needed. Python standard-library course tools remain the required workflow. The optional full-schema check used the already-installed `jsonschema` package; it is not a change to course dependencies.

## Current evidence

- Student-supplied actual ChatGPT outputs: `responses/primary_v0.json`, `contrast_1_v0.json`, `contrast_2_v0.json`; raw handoff in `records/TEST_HANDOFF_original.md`. Bytes preserved, hashes recorded.
- All three independently pass course validation and full Draft 2020-12 schema checks. This is format evidence, not analytical success.
- `records/critical_review.md`: stable general findings, valid value-capture contrast, unsupported primary impact timing, cross-context evaluation-object drift and copied counterargument.
- `records/baselines/`: exact original v0 specialist/metadata/packets.
- `specialist_instructions.md`: revision 0.4 adds evidence gates and scope/uncertainty controls. Inputs/evidence are unchanged.
- `packets/retest_*_prompt.txt`: revised packets. Original `primary_prompt.txt`/contrast packets are retained as v0 history, not the current retest inputs.
- `records/retest_handoff.md`: exact external execution/save steps and acceptance criteria. No v1 outputs exist.
- `deliverables/`: English Markdown and Word review drafts, including primary output report, independent judgment, verification note, Craft Gained and team handoff; `records/agent_record.md` documents actual work and limitations.
- `evidence/`: checked NBER/SBA/NIST claims and actual access metadata. HBS remained 403 and is excluded. All organization data are declared hypothetical inputs.

## Commands and directories

Use the existing isolated checkout; do not create a worktree unless the student requests one. Run from `/workspace/emerging-technology-disruption-agent/MASY1800_ET_Agent_Scaffold_v1_0`.

```sh
python tools/check_frozen_core.py
python tools/validate_response.py agents/disruption_agent/responses/primary_v0.json
python tools/validate_response.py agents/disruption_agent/responses/contrast_1_v0.json
python tools/validate_response.py agents/disruption_agent/responses/contrast_2_v0.json
```

Rebuild any revised packet with the instructor `build_prompt.py`, e.g.:

```sh
python tools/build_prompt.py --agent agents/disruption_agent --case agents/disruption_agent/cases/primary.json --out agents/disruption_agent/packets/retest_primary_prompt.txt
```

Actual model execution uses separate normal ChatGPT. Return its untouched v1 outputs for validation and critical review. The current session has no callable separate ChatGPT runtime; never fill missing files with scripted or manually corrected responses and call that a retest.

## Submission

See `deliverables/00_Submission_Checklist.md`. Review drafts are available now; a completed final package requires genuine behavioral retest outcomes and student review/identity. The archive manifest identifies the source commit. The temporary retest ZIP is an execution aid, not a Brightspace submission.
