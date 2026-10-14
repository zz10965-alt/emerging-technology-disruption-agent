# Verified evidence register — October 13, 2026

Selected case: LLM generative AI and small bilingual consultancies helping Chinese home/lifestyle brands enter the United States. UTC retrieval timestamps in `access_results.json` (October 14) correspond to October 13 in America/New_York. Retrieval success and claim verification are separate.

## Fresh access results after environment publication

| ID | Requested source | Actual result | Scope checked |
|---|---|---|---|
| S1 | https://www.nber.org/papers/w31161 | HTTP 200 | Publication metadata/abstract; linked current November 2023 PDF downloaded, targeted passages read |
| S2 | https://www.hbs.edu/faculty/Pages/item.aspx?num=64700 | HTTP 403 Forbidden | Unavailable; no title, findings or effect sizes verified; excluded from agent evidence |
| S3 | https://www.sba.gov/business-guide/plan-your-business/market-research-competitive-analysis | HTTP 200 after redirect to https://www.sba.gov/counseling/plan-your-business/#market-research | Actual market-research/competitive-analysis content read, not a redirect-only success |
| S4 | https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf | HTTP 200, actual PDF | Title/date and sections 2.2, 2.4 and 2.7 read |

All four original pre-publication requests failed with proxy 403. Those failures are superseded for S1/S3/S4; HBS remains unavailable and its new failure's cause is not established. No TLS or access controls were bypassed.

## C1 — Course framework

Andres Fortino, *Mastering the Craft of Emerging Technology Adoption*, Chapter 1, August 2026 Rev 0.1, supplied classroom manuscript. Sections 1.2–1.7 and Figure 1.8 p.11 read locally; matrix inspected visually. Use for sustaining/disruptive mechanisms, incumbent dilemma and severity/time defaults. Its contemporary employment/revenue examples are not independently verified facts for this case. Do not redistribute the classroom manuscript.

## S1 — Empirical workplace evidence, limited transferability

Erik Brynjolfsson, Danielle Li and Lindsey R. Raymond, *Generative AI at Work*, NBER Working Paper 31161, April 2023, revised November 2023. DOI: 10.3386/w31161.

Primary PDF: https://www.nber.org/system/files/working_papers/w31161/w31161.pdf

Checked: cover/abstract (PDF pp.1–2); section 2.3, printed pp.10–11 (system design); section 7, printed pp.27–28 (conclusion/limitations).

- **Supported:** The November 2023 abstract describes 5,179 customer-support agents and reports an average 14% increase in issues resolved per hour, including 34% for novice/low-skilled workers and minimal impact for experienced/high-skilled workers. These are the paper's reported findings, not independent replication or estimates for the consultancy.
- **Scope:** A customer-service-adapted AI assistant augmented human agents who chose whether to use suggestions. This is not an uncustomized chatbot generating cross-border strategy reports.
- **Limitations/contrary evidence:** Section 7 explicitly does not establish long-run effects on skill demand, job design, wages or customer demand; effects may not generalize across firms/production processes.
- **Labeled inference:** Task assistance merits a measured pilot, with task/worker heterogeneity. It does not establish a quantified return, layoffs, client displacement or existential threat.
- **Version control:** An older PDF linked at `https://www.nber.org/system/files/working_papers/w31161/revisions/w31161.rev1.pdf` was also downloaded. Its cover says October 2023 and its abstract reports 35% for novice/low-skilled workers. The current November PDF reports 34%; do not mix versions. The page lists a 2025 QJE publication, but that article was not retrieved or reviewed. No claim is made that the 2023 study is the latest research.

## S2 — Unverified candidate, excluded

The HBS URL returned HTTP 403 on the fresh attempt. No consulting experiment title or statistics are verified. The current empirical evidence set therefore lacks a directly inspected consulting-task study. An accessible original paper or user-supplied original PDF can be evaluated later; an AI-generated summary is not a substitute.

## S3 — Authoritative research-method guidance

U.S. Small Business Administration, *Plan your business*, *Market research and competitive analysis* → *Use market research to find customers*. Publication/update date not verified in the inspected section: cite as undated, accessed October 13, 2026.

Final URL: https://www.sba.gov/counseling/plan-your-business/#market-research

- **Supported:** SBA distinguishes existing-source research from direct consumer research. Existing sources can save time but may lack audience specificity. Direct research can provide a nuanced target-audience understanding but can be time-consuming/expensive. Methods listed include surveys, questionnaires, focus groups and in-depth interviews.
- **Labeled inference:** Bilingual desk synthesis and actual U.S. consumer validation address different information needs. Generated personas/fictional interviews do not constitute real direct research, and fieldwork costs belong in the economic comparison.
- **Not established:** Local networks are defensible, customers pay a premium, a specific Chinese brand has U.S. demand, or a fieldwork-led firm necessarily survives AI competition. This is methodological guidance, not an AI impact experiment.

## S4 — Generative-AI risk guidance

National Institute of Standards and Technology, *Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile*, NIST AI 600-1, July 2024. DOI: 10.6028/NIST.AI.600-1.

PDF: https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf

Checked: section 2.2 Confabulation, printed p.6 / PDF p.10; section 2.4 Data Privacy, printed p.7 / PDF p.11; section 2.7 Human-AI Configuration, printed p.9 / PDF p.13.

- **Supported:** The profile describes confidently stated erroneous/false content including confabulated citations, privacy risks, and human overreliance/automation bias.
- **Labeled inference:** The consulting pilot should include traceable sources, human verification and data-use/privacy controls, with their costs measured. Human sign-off is a proposed control, not proof errors disappear.
- **Not established:** A particular product's error/leakage rate, its compliance, or this firm's outcomes. Historical policy references in a 2024 document do not establish current law. This is guidance, not legal advice.

## A1 — Scenario assumptions and evidence gaps

All firm attributes in the cases are hypothetical organization-type inputs, not observations of an identified firm. No client interviews, financials, staffing cuts, accuracy measurements or conversion results exist.

Still unverified: willingness to pay/self-service substitution; delivery cost after review/rework; demand from previously unserved brands; defensibility of local execution; impact timing. Potency/timing can only be conditional scenario judgments with explicit uncertainty. Neither unknowns nor task-productivity evidence justify an existential label by themselves.

Downloads remain in `/workspace/scratch/assignment2-evidence/`; raw-file hashes and HTTP outcomes are recorded in `access_results.json`. Inspection was targeted to the cited passages, not every page or an independent study replication.
