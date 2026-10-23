# Multidisciplinary Professional Identity in AI Retrieval: A Bounded Review of Relevant Prior Art

**Document type:** Bounded, AI-Assisted Narrative Review and Prior-Art Assessment. **Method qualifiers:** bounded, non-systematic, non-exhaustive; AI-assisted.

**Author:** Joseph Ribal Nasr  
**Affiliation:** Independent Researcher  
**Public version:** 1  
**Research status:** Bounded review; not independently reviewed or validated. Formal Phase 1 OPEN. Phase 2 NOT STARTED.


## Abstract

This article presents a bounded, non-systematic, non-exhaustive, AI-assisted narrative review of prior art relevant to the representation of multidisciplinary professional identities in information retrieval and generative AI. The frozen source corpus contains 45 bibliographic records provisionally grouped into 44 provisional study clusters, with one confirmed journal/preprint duplicate. The examined areas include entity and identity reconciliation, temporal and bitemporal knowledge representation, provenance, and attributable information seeking; one selected publication reconstructs research contributors’ prior publication histories to study scholarly expertise breadth, and another describes developer author-alias disambiguation; neither establishes modeling of simultaneous professional roles or changing employment affiliations across disciplines. Literature searches were selective and non-exhaustive; examination depth varied across publications. Screening and synthesis were AI-assisted and were not independently adjudicated by human reviewers. The review maps established methods and proposes an unverified integration hypothesis for information-retrieval researchers and identity-data curators: on questions about concurrent and historical professional roles, an identity-linked, time-valid, source-attributed representation might reduce identity conflation, temporal misattribution, and unsupported answers relative to a simpler evidence-retrieval baseline. It does not establish that the combination has not previously been investigated, nor establish novelty or effectiveness. No MIRF system was implemented, no comparative evaluation conducted, and no accuracy improvement measured. The output is a preliminary mapping of selected prior art, not a systematic assessment or validated methodology.

## Review scope and method

The 45 bibliographic records in the bounded research corpus (44 provisional study clusters) were assembled through selective, bounded searches. Three inherited historical queries each retained 15 structured records; complete original raw result objects and full database denominators are unavailable. Later targeted provider queries and supplemental sources must not be reinterpreted as systematic coverage or silently added to the frozen base. Eligibility judgments are provisional and AI-assisted, not independently adjudicated. The journal DOI (10.1038/s41597-020-0543-2) and arXiv preprint (arXiv:2005.04308) of *Building a PubMed Knowledge Graph* are two bibliographic records assigned to the same provisional cluster: 45 records → 44 provisional study clusters. Additional version duplicates may remain unidentified.

## Established prior-art areas and qualified synthesis

Selected original publications document existing components relevant to this question, including bitemporal fact representation ([Quipu, §4](https://arxiv.org/html/2608.16813); [TGMS, §2](https://arxiv.org/html/2607.10265); [Engram, §3.1](https://arxiv.org/html/2606.09900)), graph-world memory reconciliation ([WorldDB, §3](https://arxiv.org/html/2604.18478)) and record-identity curation ([Curate Before You Connect, §2.3 and §5](https://arxiv.org/html/2608.10644)), each in its source application domain rather than validated person-career disambiguation. Separately, [HAGRID, §3.4 and §4](https://arxiv.org/html/2307.16883) examines attribution of generated answers, while [Topic Is Not Agenda, §3.5](https://arxiv.org/html/2605.07158) examines citation-community-informed scientific-literature retrieval; these are distinct tasks, not a jointly tested pipeline. These citations support specific *source-described methods*, not replicated results, complete coverage of the field, or effectiveness of an integrated MIRF system. The cited sections are traceable to the original publications, but the publications’ experimental findings have not been independently replicated. Two later career/identity passages are reported separately below.

Two additional original-publication passages provide narrowly relevant but **non-equivalent** analogues. [Has Scientific Talent Shifted from Depth to Breadth?, §5.4–5.5 and §5.9](https://arxiv.org/html/2609.14425) describes constructing chronological publication histories for sampled research contributors and estimating scholarly-topic breadth and depth. These histories concern research outputs, not employment intervals, simultaneous cross-profession roles, or independently verified changes in organizational affiliation. [Scaling Author Identity Disambiguation to the World of Code, §2.1–2.3 and §2.8–2.10](https://arxiv.org/html/2607.06920) describes canonicalizing developer author/committer aliases, including over-merge risks and evaluation against identity evidence. These are source authors’ reported methods and outcomes, **not MIRF evaluations**; developer alias disambiguation does not itself model career trajectories or professional concurrency.

Other included records provide preliminary contextual mapping, including provisional career- and affiliation-related classifications. No directly checked source passage in this audit establishes **changing professional affiliations across disciplines or simultaneous occupational roles** as an implemented method in the cited research. Those claims remain unverified for this corpus and are not presented as passage-backed findings. The non-systematic, non-exhaustive selection does not establish comprehensive prior-art coverage.

There is **no assertion that the integrated combination is unprecedented**. Neither the absence of a matching study in the bounded selection nor the conceptual grouping of existing methods constitutes a novelty finding.

## Operationalized, untested integration hypothesis

**Proposed users (not evidence of demonstrated demand):** information-retrieval researchers, knowledge-base curators, and teams tasked with generating evidence-grounded professional biographies from permitted sources. **Target tasks:** disambiguate similarly named people; answer what roles a person held at a specified time; identify concurrent roles across disciplines; detect missing or conflicting source support; and avoid unsupported current-career assertions. **Hypothesis:** under a controlled comparison using identical questions and generator settings, adding verified person identity links, valid-time role intervals and source provenance to retrieval may improve claim-level factual precision, temporal correctness and citation support, and reduce mistaken identity merges and unsupported statements, relative to text-only retrieval. All outcomes remain unmeasured.

## Evidence basis and claim-to-source limitations

A separate, non-deposited claim-level research audit assesses **25 material manuscript assertions** and reconciles **all 45 bibliographic records**. For *narrowly defined component statements*, **seven records** had original-publication HTML passages checked in earlier source assessments; **two additional records** were checked for the limited research-history and author-alias claims above; **three further records** retain inherited section pointers without equivalent directly checked passages; the remaining **33 records** lack newly directly checked original-publication passages in these audits. Thus **nine records** have directly checked source passages for specified limited claims, and **36 of 45** do not have that level of claim-specific checking, though many retain earlier source examinations. The nine checked records support only narrow component descriptions in the publications’ respective application domains; they do not validate entire papers, all manuscript assertions, a complete 45-record claim-to-passage index, or a MIRF integration. A 45/45 claim-to-passage certification remains **NOT VERIFIED**. No original page or section has been invented.

## Limitations and integrity statement

- Not a systematic or exhaustive search, systematic literature review, validated framework, or proof of an original algorithm.
- Variable evidence depth: complete primary HTML/PDF examinations, targeted body passages, and metadata or abstract-only entries are not equivalent.
- The 44 provisional study clusters remain subject to revision; duplicate checking is incomplete outside the confirmed pair.
- All external experimental results are author-reported; no independent replication of those results was undertaken.
- Independent human eligibility adjudication and originality assessment were not performed.
- No MIRF solution was built; no comparative experiment, benchmark or accuracy measurement has been conducted.
- Person linkage must respect permission, privacy, rights and sensitivity constraints; this review authorizes no real-person profiling, surveillance or sensitive-data processing.
- The source corpus is fixed for this review. Later additions require a separately dated amendment outside the bounded evidence base.

## Open questions

The following questions define possible follow-up research rather than findings of this review:

1. Does an integrated identity, temporal-validity, and provenance representation improve factual precision, temporal correctness, identity disambiguation, or citation support against a controlled retrieval baseline? **Untested.**
2. Is the apparent absence of an exact multidisciplinary-career integration study a real gap or an artifact of this bounded search? **Unknown.**
3. Do relevant career- or affiliation-modeling methods occur among the 36 records without claim-specific primary-passage checks? **Unresolved.**
4. Are additional journal/preprint publication versions duplicated among the 36 records without claim-specific primary-passage checks? **Unresolved; 44 provisional study clusters remains an uncertain count.**
5. Would a wider search or independently screened literature sample materially change this provisional synthesis? **Untested.**

## Conclusion

This bounded narrative review maps selected established technical foundations relevant to interpreting multidisciplinary professional identities. It identifies a falsifiable *research question* about whether integrated identity, temporal and provenance representations affect retrieval accuracy; it provides no experimental evidence for the proposed integration, no originality certification, and no authorized MIRF solution development. **Formal Phase 1 OPEN. Phase 2 NOT STARTED.**

## Appendix A: Relied-upon references (verified bibliographic metadata)

These nine records underpin the manuscript’s narrow technical descriptions. Author and title metadata were checked against their arXiv abstract records. Dates are the arXiv submission years, not claims of journal peer review. Locator references identify sections rather than reproducing or independently validating experiments.

1. Brown, Steve (2026). *Quipu: A Governed Bitemporal Knowledge Graph Store*. arXiv:2608.16813. https://doi.org/10.48550/arXiv.2608.16813 (relevant section: §4).

2. Zhang, Xiaofei (2026). *TGMS: An Agent-Native Bi-Temporal Graph Management System*. arXiv:2607.10265. https://doi.org/10.48550/arXiv.2607.10265 (relevant section: §2).

3. Wang, Liuyin (2026). *Less Context, More Accuracy: A Bi-Temporal Memory Engine for LLM Agents Where a Lean Retrieved Context Beats the Full History*. arXiv:2606.09900. https://doi.org/10.48550/arXiv.2606.09900 (relevant section: §3.1).

4. Ganesan, Harish Santhanalakshmi (2026). *WorldDB: A Vector Graph-of-Worlds Memory Engine with Ontology-Aware Write-Time Reconciliation*. arXiv:2604.18478. https://doi.org/10.48550/arXiv.2604.18478 (relevant section: §3).

5. Dangaich, Vaibhav; Lewis, Kevin; Pundalik, Kundeshwar (2026). *Curate Before You Connect: Identity and Ontology Tagging in a Production Knowledge Graph*. arXiv:2608.10644. https://doi.org/10.48550/arXiv.2608.10644 (relevant section: §§2.3, 5).

6. Kamalloo, Ehsan; Jafari, Aref; Zhang, Xinyu; Thakur, Nandan; Lin, Jimmy (2023). *HAGRID: A Human-LLM Collaborative Dataset for Generative Information-Seeking with Attribution*. arXiv:2307.16883. https://doi.org/10.48550/arXiv.2307.16883 (relevant section: §§3.4, 4).

7. Yoo, Junseon (2026). *Topic Is Not Agenda: A Citation-Community Audit of Text Embeddings*. arXiv:2605.07158. https://doi.org/10.48550/arXiv.2605.07158 (relevant section: §3.5).

8. Nee, Xiaoshn; Zhong, Haobo; Ni, Xiaomin (2026). *Has Scientific Talent Shifted from Depth to Breadth? Evidence across Papers, Knowledge Inputs, Careers, and Teams*. arXiv:2609.14425. https://arxiv.org/abs/2609.14425 (relevant sections: §§5.4–5.5, 5.9).

9. Mockus, Audris (2026). *Scaling Author Identity Disambiguation to the World of Code: A Methodology*. arXiv:2607.06920. https://doi.org/10.48550/arXiv.2607.06920 (relevant section: §§2.1–2.3, 2.8–2.10).

## Appendix B: Bounded 45-record context inventory (provisional)

This inventory preserves all 45 original bibliographic records used in preliminary mapping, including the one identified journal/preprint pair. Inclusion does not imply that a record substantiates any particular conclusion. The nine references relied upon for substantive technical claims are fully identified in Appendix A.

| ID | Study title |
|---|---|
| arxiv:2608.16813 | Quipu: A Governed Bitemporal Knowledge Graph Store |
| arxiv:2606.06240 | TOKI: A Bitemporal Operator Algebra for Contradiction Resolution in LLM-Agent Persistent Memory |
| arxiv:2604.18478 | WorldDB: A Vector Graph-of-Worlds Memory Engine with Ontology-Aware Write-Time Reconciliation |
| arxiv:2606.09900 | Less Context, More Accuracy: A Bi-Temporal Memory Engine for LLM Agents Where a Lean Retrieved Context Beats the Full History |
| arxiv:2608.21418 | Composable Trust Infrastructure for Manufacturing Knowledge Graphs: Cross-System Provenance, Temporal Reasoning, and Decision Traceability |
| arxiv:2607.26520 | A Graph-Native Bitemporal Memory Store for Conversational AI Agents |
| arxiv:2608.24921 | post-graph-rag: A PostgreSQL-Native Bi-Temporal Graph RAG Engine with Temporal Grounding at Synthesis |
| arxiv:2606.15246 | Provenance-Enhanced Statements in Knowledge Graphs |
| arxiv:2607.10265 | TGMS: An Agent-Native Bi-Temporal Graph Management System |
| arxiv:2608.12476 | Governed Persistent Memory: Source-Bound State Semantics and Fail-Closed Release for Long-Horizon Agents |
| arxiv:2609.38684 | Concept-Grounded Attention: A Controlled Evaluation of Graph-Injected Attention, Temporal Versioning, and Epistemic Status |
| arxiv:2608.05342 | Temporal and Conceptual Modeling: Foundations and Research Evolution |
| arxiv:2509.15464 | Temporal Reasoning with Large Language Models Augmented by Evolving Knowledge Graphs |
| arxiv:2210.02534 | Time travel for knowledge graphs: live queries over RDF change histories |
| arxiv:2608.12984 | Reconcile Once, Write Anytime: A Trust-Tiered Librarian and a Multi-Agent Writer for Drift-Free, Point-in-Time Research |
| arxiv:2307.12173 | Named Entity Resolution in Personal Knowledge Graphs |
| doi:10.18653/v1/2026.acl-industry.101 | Structure-Guided Entity Resolution: Fine-Tuning LLMs for Robust Name Matching in Complex Linguistic Contexts |
| arxiv:2607.06920 | Scaling Author Identity Disambiguation to the World of Code: A Methodology |
| arxiv:2005.04308 | Building a PubMed knowledge graph |
| doi:10.1038/s41597-020-0543-2 | Building a PubMed knowledge graph. |
| arxiv:2608.16161 | Domain-Specific Text Embedding Models for Entity Resolution |
| arxiv:2201.09555 | A Knowledge Graph Embeddings based Approach for Author Name Disambiguation using Literals |
| arxiv:2101.06126 | EAGER: Embedding-Assisted Entity Resolution for Knowledge Graphs |
| arxiv:1410.6717 | Matching Entities Across Online Social Networks |
| arxiv:2608.10644 | Curate Before You Connect: Identity and Ontology Tagging in a Production Knowledge Graph |
| doi:10.1109/ACCESS.2026.3731447 | Agentic Graph Retrieval-Augmented Generation for Auditable Commercial Registry Analysis |
| arxiv:2104.02667 | Personalized Entity Resolution with Dynamic Heterogeneous Knowledge Graph Representations |
| arxiv:2008.04443 | (Almost) All of Entity Resolution |
| arxiv:2209.00133 | The Fellowship of the Authors: Disambiguating Names from Social Network Context |
| arxiv:2008.13099 | Pairwise Learning for Name Disambiguation in Large-Scale Heterogeneous Academic Networks |
| doi:10.3389/fpsyg.2026.1859525 | A bibliometric analysis of research on factors influencing STEM career choices: gender, identity, self-efficacy, and self-concept. |
| arxiv:2608.22381 | GRAFT: Graph-Distilled Generative Retrieval for Facet-Aware Scientific Literature Exploration |
| arxiv:2505.21849 | Xinyu AI Search: Enhanced Relevance and Comprehensive Results with Rich Answer Presentations |
| arxiv:2307.16883 | HAGRID: A Human-LLM Collaborative Dataset for Generative Information-Seeking with Attribution |
| arxiv:2506.03187 | Comparing Retrieval Strategies to Capture Interdisciplinary Scientific Research: A Bibliometric Evaluation of the Integration of Neuroscience and Computer Science |
| arxiv:2605.14790 | Graphs of Research: Citation Evolution Graphs as Supervision for Research Idea Generation |
| arxiv:2603.17765 | Grounded Multimodal Retrieval-Augmented Drafting of Radiology Impressions Using Case-Based Similarity Search |
| arxiv:2609.14425 | Has Scientific Talent Shifted from Depth to Breadth? Evidence across Papers, Knowledge Inputs, Careers, and Teams |
| arxiv:2506.00249 | MIR: Methodology Inspiration Retrieval for Scientific Research Problems |
| arxiv:2508.06401 | A Systematic Literature Review of Retrieval-Augmented Generation: Techniques, Metrics, and Challenges |
| arxiv:2412.12358 | BioRAGent: A Retrieval-Augmented Generation System for Showcasing Generative Query Expansion and Domain-Specific Search for Scientific Q&A |
| doi:10.1093/jamia/ocag122 | CiteSure: retrieval-augmented large language models for faithful biomedical citation recommendation. |
| arxiv:2605.07158 | Topic Is Not Agenda: A Citation-Community Audit of Text Embeddings |
| arxiv:2603.16138 | Answer Bubbles: Information Exposure in AI-Mediated Search |
| arxiv:2604.25707 | From Citation Selection to Citation Absorption: A Measurement Framework for Generative Engine Optimization Across AI Search Platforms |