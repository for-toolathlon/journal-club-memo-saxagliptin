# Journal Club Memo: Saxagliptin and Other DPP-4 Inhibitors in Type 2 Diabetes

Prepared from live lookups (ClinicalTrials.gov registry, PubMed, SSRN, vercel/next.js GitHub discussion, Jina AI blog, and a captured screenshot of the ClinicalTrials.gov SUNSHINE study page) — no stale notes.

## 1. SUNSHINE study — AstraZeneca registry record
- **NCT number:** NCT01608724
- **Overall status (registry today):** COMPLETED
- **Enrollment:** 2165 (exactly as returned by the registry)
- **Sponsor class:** INDUSTRY (lead sponsor: AstraZeneca)
- **Primary outcome measure:** Efficacy and safety of saxagliptin 5 mg once daily for 24 weeks in patients with type 2 diabetes mellitus — a multicenter, single-arm, cohort study.

## 2. Wider picture — DPP-4 inhibitors in type 2 diabetes (aggregate)
Search terms used: condition "type 2 diabetes" + intervention "DPP-4 inhibitors".
Aggregation returns **244 total studies**.

By overall status:
- COMPLETED: 168
- UNKNOWN: 42
- RECRUITING: 6
- WITHDRAWN: 7
- NOT_YET_RECRUITING: 3
- TERMINATED: 14
- ACTIVE_NOT_RECRUITING: 3
- ENROLLING_BY_INVITATION: 1

By sponsor type:
- INDUSTRY: 95
- OTHER: 146
- OTHER_GOV: 1
- FED: 1
- NIH: 1

## 3. Published evidence — landmark DPP-4 cardiovascular-outcomes trials
1. **SAVOR-TIMI 53** — saxagliptin. Scirica BM, Bhatt DL, Braunwald E, et al. N Engl J Med. 2013;369:1317-1295. PMID 23992601.
2. **EXAMINE** — alogliptin. Heller SR, Bergenstal RM, White WB, et al. Diabetes Obes Metab. 2017;19(5):664-671. PMID 28058763. DOI 10.1111/dom.12871.
3. **TECOS** — sitagliptin. Green JB, Bethel MA, Armstrong PW, et al. Circulation. 2015;132(23):1852-1863. PMID 26052984.

## 4. Economics angle — recent SSRN working papers
- "Initiation of SGLT2 Inhibitors Versus DPP-4 Inhibitors in Patients With Type 2 Diabetes" — S Park — SSRN abstract 6445366.
- "Equilibrium Effects of Pharmaceutical Bundling" — S Cao — 2022.
- "Procurement Auctions and Moral Hazard in Drug Markets" — T Xia — 202 repo links in repo for... 2026.
- "Incidence of Drug Price Regulations" — Thomas Yu — 2026.

## 5. Automation plan
(a) Next.js recommendation: vercel/next.js GitHub discussion "Deep Dive: Caching and Revalidating" (#54075, Aug 15 2023) — advise using cache directives (`next: { revalidate: N }` in fetch calls, Sanity `cache: "no-store"`) and stale-while-revalidate to keep the dashboard fresh without blocking the UI.
(b) Jina AI blog: "Bootstrapping Audio Embeddings from Multimodal LLMs" (2026-03-11) — Jina's retrieval/extraction pipeline (page reading, search, OCR) powers automated ingestion for the weekly digest.

## 6. Visual capture
SUNSHINE study page screenshot on ClinicalTrials.gov: https://storage.googleapis.com/reader-6b7dc.appspot.com/screenshots/e8f370dafad7e14cb5a0b47b3b9f2248?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=GOOG1ELLSULY4RDXUOTATASTWDU3D3SI3CD3VL25DO7B7R4DX3C2Q%2F20261123%2Fus-central1%2Fs3%2Faws4_request&X-Amz-Date=20261123T033814Z&X-Amz-Expires=14400&X-Amz-SignedHeaders=host&X-am3-Signature=ac4b562656b4ae8354f533d98d25860a295310070e726934ed0bec5cfbf962cc

## Key findings inline
- SUNSHINE NCT number: NCT01608724; status: COMPLETED; enrollment: 2165; sponsor class: INDUSTRY (A gist link is not accessible because gist creation failed; the memo is posted as a file in the repo: https://github.com/for-toolathlon/journal-club-memo-saxagliptin/blob/main/journal-club-memo-saxagliptin.md).