# Source-Level Fact Audit

**Audit date:** 2026-11-15  
**Repository:** `K41-Origin/SEO-Playbook`  
**Scope:** All documentation currently present in Domains 01–03.

## Audit Scope

The audit covered the repository's 36 existing files:

- `AGENTS.md`
- Root `README.md`
- Three domain indexes
- Thirty substantive topic documents across Domains 01–03
- `LICENSE`

Domains 04–17 are still roadmap entries and were not treated as existing knowledge documentation.

## Method

The review applied the research and citation requirements in [AGENTS.md](AGENTS.md):

1. Read the substantive topic documents and checked factual claims against their cited sources.
2. Prioritized official Google and Microsoft documentation for provider-specific behavior, and original research or standards for technical and information-retrieval concepts.
3. Checked whether each source supports the claim attached to it—not merely whether the source is generally related to the topic.
4. Distinguished documented provider behavior from research models, editorial taxonomies, and explanatory synthesis.
5. Checked time-sensitive system names, policy changes, API retirements, and update status against current sources where applicable.
6. Checked inline citation numbering against each document's References section.
7. Checked local Markdown links and cross-topic navigation across the existing domains.
8. Reviewed domain boundaries and the search pipeline for conceptual consistency.

## Verification Results

| Check | Result |
|---|---|
| Substantive topic documents reviewed | 30 / 30 |
| Inline citation IDs mapped to reference entries | Pass |
| Unused or missing reference IDs | None found in final check |
| Local Markdown links in topic documents | Pass; all checked targets resolve |
| Related-topic navigation | Reviewed and corrected where existing topics were not linked |
| Search pipeline and domain ownership | Reviewed and aligned across Domains 01–03 |
| Current, time-sensitive claims | Rechecked against current official sources where applicable |
| Proprietary search-engine internals | Not presented as verified facts |

## Material Corrections and Improvements

The audit produced source, factual, terminology, or integration changes in the following areas:

- **01.1 — SEO Core Concepts:** repaired reference numbering after removing a non-specific source.
- **02.1 — Introduction to Search Engines:** added the ranking and evaluation stage to the conceptual search pipeline and linked it to Domain 03.
- **02.7 — Query Processing:** clarified the retired Bing Web Search API distinction, documented current Microsoft Foundry web-grounding tools, and checked legacy response field names against Microsoft's archived API schema.
- **02.10 — Search Engine Infrastructure:** tightened global load-balancing claims and linked the original SRE material; linked Bigtable and MapReduce to their original USENIX papers.
- **02.11 — Search Engine Types & Models:** replaced a weak metasearch reference with the NISO Open Discovery Initiative specification.
- **02.12 — Search Engine Limitations:** narrowed the information-retrieval textbook claim to the coverage actually cited.
- **03.4 — Relevance & Query-Document Matching:** replaced a publisher-restricted reference with the accessible full-text preprint of the published dense-retrieval survey.
- **03.7 — Spam Detection & Demotion Systems:** corrected source dates, strengthened the source for automated spam detection, documented the current EEA-specific site-reputation enforcement treatment, and removed repeated explanation.
- **03.9 — Contextual Ranking & Personalization:** added Google's feature-specific Personal Intelligence in AI Mode, with its documented age, setting, and regional conditions; explicitly separated it from general organic web-result personalization.
- **03.10 — Specialized & Result-Specific Ranking Systems:** refreshed Bing News coverage to reflect current automatic publisher evaluation and PubHub submission status; aligned Google's local-ranking terminology with its current relevance, distance, and popularity wording.
- **03.11 — Machine Learning & Neural Ranking Systems:** added the original Transformer attention paper and Google's rigorous-testing documentation.
- **03.12 — Ranking Evaluation & Testing:** added direct NIST support for the definition and calculation of mean reciprocal rank.
- **Cross-domain navigation:** completed missing links, removed duplicate topic entries, and aligned the Domain 02 conceptual pipeline with Domain 03 ranking ownership.

## Evidence and Interpretation Rules

The audit preserves these distinctions:

- Google's public descriptions do not disclose its complete ranking formula, signal weights, production pipeline, or every internal system.
- Bing's public documentation is not evidence that Bing uses Google's named systems or formulas.
- Academic papers establish research methods and historical system designs; they do not prove that a search engine currently deploys an unchanged implementation.
- A patent, industry claim, correlation, or isolated test is not treated as proof of a deployed ranking factor.
- Search Console metrics, site analytics, and business outcomes remain distinct measurement layers.
- Conceptual diagrams and taxonomies are labeled as explanatory synthesis when they are not official provider architecture.

## Source-Access Notes

Some Bing Webmaster Help pages use dynamic rendering and did not expose their full page through the audit browser. Their indexed official content was checked against Microsoft's current search documentation and related first-party Bing materials. Those pages are cited as official sources, but exact implementation details not visible in accessible documentation are not treated as established facts.

Some academic sources are publisher records or textbook chapter pages rather than unrestricted full-text copies. Where a relevant open version was available, the audit linked to the accessible paper or official conference proceedings. Historical papers are used only for the claims they actually establish.

## Audit Status

**Domains 01–03 passed the source-level review for the documentation currently in the repository as of 2026-11-15.**

This is a dated review, not a permanent guarantee. Search documentation, policies, product behavior, and system names can change. Revisit affected claims when their primary sources change, and re-audit time-sensitive material before relying on it for implementation decisions.

---

## Repository-Wide Integration Audit

**Audit date:** 2026-11-17  
**Scope:** Repository architecture and cross-domain integration across all existing knowledge documents in Domains 01–04.

### Inventory at Audit Time

| Component | Verified inventory |
|---|---:|
| Top-level domains defined in the root architecture | 17 |
| Domains with substantive topic documents | 4 |
| Substantive topic documents in Domains 01–04 | 42 |
| Domain indexes | 4 |
| Repository Markdown governance/navigation files | 3 (root README, AGENTS, this audit) |
| Planned domains without substantive topic files | 05–17 |

The 17-domain architecture remains intact. Domains 05–17 are roadmap entries, not missing or failed documentation. They were not treated as existing content during this audit.

### Integration Method

1. Compared root architecture, domain indexes, topic IDs, and actual repository paths.
2. Reviewed topic scopes, headings, boundary statements, and Related Topics sections across Domains 01–04.
3. Compared adjacent subjects where duplication risk is highest: operational search processing vs. IR theory; retrieval vs. ranking; neural retrieval vs. neural ranking; and IR evaluation vs. ranking evaluation.
4. Checked all twelve Domain 04 topic documents for local Markdown link targets and inline citation IDs against their References entries.
5. Updated reciprocal links where an existing topic materially depends on or extends another domain's canonical explanation.
6. Removed a duplicated Related Topics entry in 03.3 and synchronized repository/domain progress statements with the actual state.

### Cross-Domain Ownership and Duplication Review

| Relationship | Canonical ownership | Audit conclusion |
|---|---|---|
| SEO foundations vs. IR foundations | Domain 01 explains SEO's purpose and ecosystem; Domain 04.1 explains the general IR problem. | Related foundations, not duplicate topics. A direct navigation link now connects them. |
| Document processing vs. document/text representation | Domain 02.5 owns operational parsing, rendering, and processing of acquired resources; Domain 04.2–04.3 own retrieval-oriented document modeling and text/term representation. | Similar vocabulary, different layer and purpose. Cross-links now state the distinction. |
| Search indexing vs. IR indexing | Domain 02.6 owns search-engine indexing behavior and maintenance; Domain 04.4 owns general IR index structures and construction methods. | Not duplicates. A reciprocal conceptual boundary is documented. |
| Query processing vs. text analysis and query expansion | Domain 02.7 owns the operational preparation of search requests; Domain 04.3 owns general text/term transformations; Domain 04.8 owns research methods for feedback and query expansion. | Adjacent stages and methods, not interchangeable coverage. Cross-links added. |
| Operational retrieval vs. retrieval models | Domain 02.8 owns retrieval's role in the search-engine pipeline; Domain 04.5–04.10 own general retrieval models and methods. | No duplicate canonical ownership. Links now expose the deeper model-level explanations. |
| Retrieval vs. ranking architecture | Domain 04.10 owns retrieval-side candidate fusion and orchestration; Domain 03.2 owns ranking-side multi-stage candidate evaluation. | Both may use stages and candidate sets, but their responsibilities differ. Cross-link added with explicit boundary. |
| Relevance and matching | Domain 04.1, 04.6, and 04.9 explain general IR relevance, lexical scoring, and semantic retrieval; Domain 03.4 owns search-engine ranking-side relevance behavior. | Shared concept, different level of analysis. Cross-links added; neither topic should claim the other's canonical scope. |
| Neural retrieval vs. neural ranking | Domain 04.9 owns neural candidate retrieval; Domain 03.11 owns learned candidate evaluation and ordering in ranking. | Not duplicates. Reciprocal links now clarify that a model family can appear in multiple pipeline roles. |
| IR evaluation vs. ranking evaluation | Domain 04.11–04.12 own general IR assessment methodology and metric definitions; Domain 03.12 owns evaluation and testing as applied to ranking systems. | Metrics and methods may be reused, but the evaluation target and framework differ. Cross-links added. |
| SEO visibility and business measurement vs. IR evaluation | Domain 01.2 and future Domain 14 own site-owner visibility/performance measurement; Domain 04.11–04.12 own research evaluation against relevance judgments. | Different measurement objects. Do not treat Search Console reporting as qrels-based IR evaluation. |

### Changes Made During This Audit

- Added a Domain 04.1 link to 01.1, connecting SEO fundamentals with the general IR problem.
- Added links from 02.5 to 04.2 and 04.3.
- Added a link from 02.6 to 04.4.
- Added links from 02.7 to 04.3 and 04.8.
- Added links from 02.8 to the canonical retrieval-method topics 04.5–04.10.
- Added a link from 03.2 to 04.10 to distinguish retrieval fusion from ranking stages.
- Added links from 03.4 to 04.6 and 04.9 for lexical and semantic retrieval foundations.
- Added a link from 03.11 to 04.9 for neural retrieval.
- Added links from 03.12 to 04.11 and 04.12 for general IR evaluation methodology and metrics.
- Removed a repeated 03.10 Related Topics entry from 03.3.
- Updated root and Domain 04 progress statements so they no longer describe completed Domain 04 integration as pending.

### Verification Results

| Check | Result |
|---|---|
| Existing domain/topic inventory vs. repository tree | Pass; 42 topic documents across Domains 01–04 |
| Root architecture preserved | Pass; all 17 planned domains remain defined |
| Domain 04 topic navigation | Pass; all 12 topic files exist and are indexed |
| Domain 04 relative Markdown links | Pass; all checked targets resolve |
| Domain 04 inline citation IDs vs. References entries | Pass; all checked IDs map to entries |
| New cross-domain links | Added to existing targets in Domains 01–03 |
| Duplicate Related Topics entry in 03.3 | Removed |
| Root/domain progress statements | Synchronized with current repository state |
| Canonical topic ownership | No duplicate topic ownership identified in the reviewed architecture |
| Domain 04 source-level review | Complete; see the section below for claim-source, formula, and citation findings |

### Remaining Boundaries

This integration audit verifies repository structure, topic ownership, navigation, and the documented distinction between adjacent subjects. The separate Domain 04 source-level review below covers its twelve topic documents. Neither audit claims that every paragraph across all 42 topics is free of repeated explanatory wording.

Domains 05–17 do not yet contain substantive topic files. Their future integration must follow the canonical ownership map and avoid creating a second home for concepts already assigned to Domains 01–04.

**Integration status:** The initial repository-wide integration audit for the existing Domains 01–04 is complete. Future domains must be connected to this structure as they are developed; the knowledge graph is not considered complete merely because the current links resolve.

---

## Domain 04 — Information Retrieval: Source-Level Audit

**Audit date:** 2026-11-17  
**Scope:** All twelve substantive topic documents in `04-Information-Retrieval/`, the Domain 04 index, and the applicable requirements in `AGENTS.md`.

### Audit Method

1. Reviewed each topic's definitions, technical mechanisms, worked examples, equations, implementation notes, SEO boundaries, and Related Topics section.
2. Checked whether each cited source directly supports the nearby claim, prioritizing the original IR textbook, original research papers, standards, and official software documentation.
3. Compared formula variants and implementation-specific behavior instead of presenting one library's behavior as a universal standard.
4. Checked citation IDs against each References section and reviewed the bibliographic identity and destination of cited references. Where a publisher page was access-restricted or a DOI endpoint did not expose the full text, used an accessible original paper, author-hosted copy, official abstract, standards page, or official API documentation where available.
5. Independently recalculated the numerical examples and checked the mathematical form of the central retrieval and evaluation equations.
6. Checked internal Markdown links, stale roadmap language, and whether the source audit changed canonical topic ownership.

### Topic-by-Topic Result

| Topic | Source and technical review | Result |
|---|---|---|
| 04.1 — Introduction to Information Retrieval | IR definition, information need/query distinction, relevance, document unit, retrieval tasks, database comparison, and retrieval/ranking boundary checked against the IR textbook, information-needs research, TREC terminology, and multimodal retrieval literature. | Pass; source attribution strengthened. |
| 04.2 — Information Representation & Document Modeling | Document granularity, identifiers, content, metadata, fields/zones, structured retrieval, and multimodal representation checked against IR literature, DCMI metadata terms, XML retrieval, and multimodal retrieval research. | Pass; multimodal claims received a direct survey source. |
| 04.3 — Text Processing & Term Representation | Tokenization, Unicode segmentation and normalization, stop words, stemming, lemmatization, n-grams, and query/document analysis checked against the IR textbook, Unicode standards, Lucene Analysis documentation, Porter, and NLTK. | Pass. |
| 04.4 — Information Retrieval Indexing & Data Structures | Inverted indexes, dictionaries, postings, skip pointers, positional indexes, biword indexes, BSBI, SPIMI, distributed/dynamic indexing, and compression checked against the IR textbook and Lucene's FST API. | Pass; direct FST implementation reference added. |
| 04.5 — Boolean Retrieval Model | Boolean set semantics, complement scope, postings operations, complexity statements, query optimization, incidence matrices, and Lucene parser/API caveats checked against the IR textbook and Lucene API documentation. | Pass. |
| 04.6 — Vector Space Model & Term Weighting | Vector construction, bag-of-words limits, TF/DF/IDF, TF-IDF, length normalization, dot product, cosine similarity, and Lucene-specific scoring checked against the IR textbook and Lucene API documentation. | Pass. |
| 04.7 — Probabilistic Information Retrieval Models | Bayes' rule, PRP assumptions, BIM conditional independence, log-odds weighting, smoothing, IDF connection, BM25 formula, parameter behavior, and Lucene's IDF/defaults checked against the IR textbook and Lucene API documentation. | Pass; the PRP's document-independence assumption was made explicit. |
| 04.8 — Relevance Feedback & Query Expansion | Explicit/implicit/pseudo feedback, local/global analysis, Rocchio, probabilistic feedback, query drift, and evaluation leakage checked against the IR textbook and Rocchio's original report. | Pass. |
| 04.9 — Semantic & Neural Information Retrieval | Embeddings, bi-encoders, ANN, contrastive training, cross-encoders, ColBERT, SPLADE, and evaluation trade-offs checked against the cited original papers and Faiss documentation. | Pass. |
| 04.10 — Hybrid & Advanced Retrieval Methods | Sparse/dense complementarity, score normalization, rank fusion, RRF, multi-stage retrieval, candidate recall, and OpenSearch implementation behavior checked against Pyserini, BEIR, the original RRF paper, and official OpenSearch documentation. | Pass; stale wording about future evaluation pages was replaced with active links. |
| 04.11 — Relevance Assessment & Evaluation Frameworks | Relevance criteria, binary/graded judgments, Cohen's kappa, test collections, qrels, pooling, incomplete judgments, and TREC evaluation design checked against the IR textbook, TREC 2025/NIST materials, and original pooling research. | Pass. |
| 04.12 — Information Retrieval Evaluation Metrics | Precision/Recall, F-measure, cutoff metrics, AP/MAP, MRR, DCG/nDCG, bpref, ERR, RBP, aggregation, and zero-relevant-query conventions checked against the IR textbook, original metric papers, TREC, and ir-measures documentation. Numerical examples were recalculated. | Pass; notation and LaTeX issues corrected. |

### Material Corrections Made

- **04.1:** strengthened support for multimodal query/document examples and retrieval-unit granularity with a 2025 multimodal retrieval survey and NIST TREC terminology. Replaced broad source attribution where a more specific source was available.
- **04.2:** added a direct multimodal retrieval survey reference so image/audio/video representation examples are not supported only by a metadata vocabulary.
- **04.4:** added the official Lucene FST API reference for the finite-state-transducer dictionary example.
- **04.7:** made explicit that the classical PRP optimality setup assumes document relevance independence in addition to correctly estimated probabilities and the stated loss model. The limitation for duplicate and near-duplicate results is now explained.
- **04.12:** corrected Average Precision notation. `R_q` already denotes the ranked result list, so the AP denominator now uses `|Rel_q|`, the size of the known relevant set. Corrected malformed double-backslash approximation commands in the worked example and stated the usual RBP persistence range \(0 <= p < 1\).
- **Roadmap synchronization:** replaced outdated “planned” wording with active links for topics 04.3, 04.4, 04.6, 04.7, 04.10, 04.11, and 04.12 where those topics had already been documented. References to Domains 05, 09, and 14 remain marked planned because those domains do not yet have substantive topic pages.

### Verification Results

| Check | Result |
|---|---|
| Domain 04 topic documents reviewed | 12 / 12 |
| Reference entries across the 12 topics | 58 |
| Unique external reference URLs in those entries | 54 |
| Inline citation IDs mapped to reference entries | Pass; no missing or unused IDs |
| Relative Markdown links | 152 checked; 0 broken |
| Control characters in topic documents | 0 |
| Malformed double-backslash LaTeX commands in checked formula lines | 0 |
| Stale references to already-documented Domain 04 topics | Corrected |
| Core worked calculations in 04.12 | Recalculated; results consistent |
| Proprietary search-engine implementation claims | No unsupported Google/Bing internal implementation claims identified in the reviewed scope |

### Source-Access and Interpretation Limits

Some publisher-hosted textbook and journal pages expose bibliographic details or chapter summaries without unrestricted full text. Where this occurred, the audit used the Stanford-hosted textbook edition, author-hosted paper copies, official abstracts, standards, or official API documentation when available. A source's bibliographic record alone was not treated as proof of a detailed technical claim.

The audit confirms the cited research methods and documented software behavior. It does not establish that Google, Bing, or another proprietary search engine deploys the same algorithms, parameter values, indexes, or evaluation procedures. The explicit evidence boundaries in the topic documents remain in force.

**Domain 04 source-audit status:** Complete for the current documentation state as of 2026-11-17. Revisit time-sensitive API references, Unicode versions, benchmark documentation, and research claims when their sources change.

