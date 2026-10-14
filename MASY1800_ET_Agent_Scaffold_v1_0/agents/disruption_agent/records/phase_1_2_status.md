# Phase 1–2 status and verification

## Inspection

Read the user-selected MD, all four supplied course documents, all distinct pasted-text variants, all scaffold documentation, core contracts, template files, four Python tools, example files, manifests and the Agent Record Word template. Chapter 1 Figure 1.8 was inspected visually. No AGENTS.md was found in the workspace.

The uploaded scaffold is under `MASY1800_ET_Agent_Scaffold_v1_0/`, with expected core, tools, template, examples and docs. Baseline commit: `4cd9f889302bb2d647199490ccc2898d489d3569`. The assignment branch was based on that upload. Earlier empty-repository observations have been superseded.

## Changes

Created `agents/disruption_agent/` using the supplied `new_agent.py`, then specialized its instructions/metadata and English documentation/Agent Record. No original tracked files, template, schema, tool or manifest were changed. Cases remain the copied REPLACE placeholders until student selection. Created an empty responses directory because the uploaded template lacks its directory marker.

## Actual checks

| Check | Actual outcome | Scope |
|---|---|---|
| GitHub read / fetch | Passed; main fetched | Repository access, not model execution |
| Python | 3.12.14 | Standard library; no pip install needed |
| `python tools/check_frozen_core.py`, before and after edits | FROZEN CORE INTACT | All seven listed core/tool hashes |
| `sha256sum -c PACKAGE_SHA256.txt` | Failed: three absent dotfiles | `.gitignore`, `agents/_template/responses/.gitkeep`, `work/.gitkeep` absent in the uploaded baseline; every existing manifest entry matches |
| Instructor toy response validator | VALIDATION PASSED | Existing example only, not this specialist |
| Prompt build with unselected copied intake | Passed; output in `/tmp/disruption_agent_unselected_prompt.txt` | Mechanical smoke only; exact common/specialist instructions included; NOT sent to ChatGPT |
| Original package hashes / copied case bytes | All present originals match; all three cases unchanged | Preservation check |
| Specialist primary/contrast runs | NOT RUN | Pending student case choice |
| Genuine weakness/revision/retest | NOT RUN | Requires actual model outputs |

The uploaded working copy is not byte-for-byte package-complete because the three dotfiles are absent. Do not change manifests or claim full package integrity. The student should retain the canonical Brightspace ZIP; its unchanged preservation cannot be confirmed from this checkout. Missing marker/ignore files do not prevent the standard-library prompt workflow; the original ZIP can supply their exact contents later.

## Remaining work and pause

Choose a proposal in `case_options.md`. Then fill real intake and evidence, build case packets with the supplied tool, execute them interactively in ChatGPT, save/validate actual returns, compare contexts, preserve and address a genuine weakness, and finish English deliverables. No external case claims have yet been verified, and no case report, independent judgment, personal reflection or final submission package is complete.

No dependency-install script or running service is required for this scaffold. Current mechanical validation does not establish specialist reasoning quality or fresh-task snapshot restoration. Local prompt-construction smoke packets must not be submitted as case outputs.

## Original archive reconciliation

The student subsequently supplied the canonical scaffold ZIP. Its 32 file entries were compared byte-for-byte with the working copy: all existing original files matched, and only the three previously reported hidden files were absent. Restored `.gitignore`, `work/.gitkeep`, and `agents/_template/responses/.gitkeep` directly from the unchanged ZIP, without reconstructing contents or modifying manifests. ZIP SHA-256: `3875e8924556b2801c572390fb2c90e5957aea452d33312a31084e1f3712e754`. The full package hash check and frozen-core checker now pass. Earlier missing-file results above remain as historical evidence and are resolved. No case selection or analytical testing has occurred.
