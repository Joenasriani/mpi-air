# MPI-AIR — public version 1

**Multidisciplinary Professional Identity in AI Retrieval: A Bounded Review of Relevant Prior Art**  
**Author:** Joseph Ribal Nasr (Independent Researcher)  
**Type:** Bounded, AI-Assisted Narrative Review and Prior-Art Assessment (non-systematic, non-exhaustive)

## Deposit files

- `mpi-air-narrative-review.pdf` — primary readable manuscript, public version 1 (9 pages).
- `mpi-air-narrative-review.md` — manuscript source, public version 1.
- `evidence-table.csv` — 45 bibliographic records mapped to 44 provisional study clusters; 9 narrow passage-checked records and 36 title/abstract-level publication classifications.
- `search-and-limitations.md` — bounded search, provisional screening, duplicates, and scientific limitations.
- `README.md` — this file.
- `LICENSE` — full Creative Commons Attribution 4.0 International legal text for original material included in this deposit; third-party works remain subject to their own rights.

**Scope:** Prior-art mapping and an untested integration hypothesis, not a constructed solution or measured performance improvement. No independent human review. Scientific novelty NOT ESTABLISHED; solution effectiveness UNTESTED. Formal Phase 1 OPEN; Phase 2 NOT STARTED.

References to outside publications and links do not imply those works have been relicensed. The author should verify their public-deposit and licensing decision before manually depositing these files. Any future study or corrections belong in a new dated version.

## Suggested Zenodo description (author-provided; copy into Zenodo metadata)

I'm an independent researcher looking at a practical problem: when someone works across several fields — holding concurrent roles, changing affiliations, publishing under different name variants over time — AI retrieval systems tend to either merge them incorrectly or lose track of which role applied when.

This review is my attempt to find out whether the technical pieces needed to handle that already exist. I searched the literature with AI assistance and assembled 45 records, grouped into 44 provisional clusters. Nine of those I read closely enough to check specific claims against the original text; the other 36 I classified from titles and abstracts only. One confirmed duplicate was identified and merged at the cluster level.

What I found is that the individual components are well established: identity resolution and alias matching, temporal and bitemporal representation, provenance tracking, author disambiguation, and evidence-grounded retrieval all have substantial prior work. What I could not find is a study that combines them specifically for people with multidisciplinary careers. That may be a genuine gap, or it may be that my search was not wide enough to find it — I can't tell from this corpus alone.

So this is not a claim that the combination works. It's a map of what exists, plus a stated hypothesis that integrating these components could improve retrieval accuracy for multidisciplinary professional identities. I have not built or tested any system, and I have measured nothing.

The search was bounded and non-exhaustive, I used AI assistance for screening and synthesis, and no independent reviewer checked my decisions. Treat it as a starting point for a testable research question, not as a validated method. The remaining questions are set out in the paper as a research agenda.