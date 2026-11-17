# 04 — Information Retrieval

> Understand how information is represented, searched, retrieved, and evaluated. The theory behind finding the right document—not another ranking-factor fan fiction.

## Domain Purpose

Information Retrieval (IR) studies the representation, organization, search, and evaluation of information so that relevant items can be found in response to an information need.

This domain documents the **general theory and methods of information retrieval**, using text and document retrieval as the primary context. It covers foundational representations, text processing, retrieval data structures, classical retrieval models, relevance feedback, semantic and neural retrieval, hybrid methods, and formal evaluation.

The goal is to understand the mechanisms and trade-offs behind retrieval—not to turn every model, benchmark, or paper into a production-search claim.

IR is broader than web search. Its methods apply to many information environments, including document collections, digital libraries, enterprise search, and passage retrieval. Web search provides an important application context, but a method described in an academic paper must not automatically be attributed to Google, Bing, or another production search engine.

## Scope

Domain 04 owns the **theoretical, methodological, and model-level foundations of information retrieval**.

It covers:

- How documents, passages, terms, and queries can be represented for retrieval.
- Text processing and term representation used by retrieval systems.
- Retrieval-oriented indexes and data structures.
- Classical Boolean, vector-space, and probabilistic retrieval models.
- Relevance feedback and query expansion as retrieval methods.
- Semantic, dense, neural, and hybrid retrieval approaches.
- Relevance judgments, test collections, evaluation methodology, and formal IR metrics.

Domain 04 does not own the operational architecture of a search engine, search-engine ranking systems, SEO keyword research, or site-owner performance measurement. Those subjects have canonical homes elsewhere and are connected below.

## Knowledge Structure

The domain is organized into four groups and twelve topics.

### Group A — Information Retrieval Foundations

| ID | Topic | Canonical scope |
|---|---|---|
| [04.1](04.1-Introduction-to-Information-Retrieval.md) | **Introduction to Information Retrieval** | The IR problem, information needs, queries, documents, relevance, retrieval tasks, and the distinction between retrieval and ranking. |
| [04.2](04.2-Information-Representation-and-Document-Modeling.md) | **Information Representation & Document Modeling** | Representing documents, passages, fields, metadata, and collections as retrievable information units. |
| 04.3 | **Text Processing & Term Representation** | Tokenization, normalization, linguistic processing, term selection, and transformations used to prepare text for retrieval models. |

### Group B — Indexing & Retrieval Models

| ID | Topic | Canonical scope |
|---|---|---|
| 04.4 | **Information Retrieval Indexing & Data Structures** | Retrieval-oriented index structures, dictionaries, postings, positional information, index construction, and compression. |
| 04.5 | **Boolean Retrieval Model** | Boolean operators, exact-match retrieval, query evaluation, and the strengths and limitations of Boolean retrieval. |
| 04.6 | **Vector Space Model & Term Weighting** | Document and query vectors, term weighting, TF-IDF, similarity functions, and ranked retrieval using vector-space representations. |
| 04.7 | **Probabilistic Information Retrieval Models** | Probability-based relevance estimation, the Binary Independence Model, BM25, and related probabilistic retrieval approaches. |

### Group C — Advanced & Modern Retrieval

| ID | Topic | Canonical scope |
|---|---|---|
| 04.8 | **Relevance Feedback & Query Expansion** | Explicit and implicit feedback, pseudo-relevance feedback, query reformulation, and expansion methods. |
| 04.9 | **Semantic & Neural Information Retrieval** | Semantic representations, embeddings, dense retrieval, neural retrievers, and learned query-document representations used to retrieve candidates. |
| 04.10 | **Hybrid & Advanced Retrieval Methods** | Combining lexical and semantic retrieval, sparse-dense methods, multi-vector approaches, fusion strategies, and advanced candidate-retrieval methods. |

### Group D — Information Retrieval Evaluation

| ID | Topic | Canonical scope |
|---|---|---|
| 04.11 | **Relevance Assessment & Evaluation Frameworks** | Relevance judgments, graded assessment, test collections, qrels, pooling, evaluation design, and methodological limitations. |
| 04.12 | **Information Retrieval Evaluation Metrics** | Formal definitions, interpretation, and limitations of precision, recall, precision at k, average precision, MAP, MRR, DCG, NDCG, and related metrics. |

Topic IDs define canonical ownership. Topics 04.1–04.2 are documented; topics 04.3–04.12 remain roadmap entries until their files are created and reviewed.

## Information Retrieval: Conceptual Model

Use this as a learning model, not a claim that every retrieval system implements one fixed pipeline:

1. **Represent information.** Define the retrievable units—documents, passages, fields, terms, and metadata.
2. **Process and represent text.** Transform raw text into representations suitable for matching or scoring.
3. **Build retrieval structures.** Organize collection representations into indexes or other data structures.
4. **Represent the query.** Convert an information need into a form that a retrieval method can process.
5. **Retrieve candidates.** Apply a retrieval model or method to identify potentially relevant items.
6. **Improve retrieval where appropriate.** Use feedback, expansion, semantic representations, or hybrid methods to improve candidate discovery.
7. **Assess and evaluate.** Compare retrieved results with relevance judgments using a suitable evaluation framework and metrics.

Real systems may combine, repeat, parallelize, or omit parts of this conceptual sequence. Production search engines also include operational components such as crawling, document processing, query serving, ranking, and result delivery. Those system-level responsibilities are not redefined here.

## Canonical Ownership & Cross-Domain Integration

| Domain | Canonical ownership | Integration rule |
|---|---|---|
| **01 — SEO Fundamentals** | SEO definitions, visibility, ecosystem, objectives, and discipline overview. | Domain 01 introduces search visibility and the role of search systems; Domain 04 explains the general retrieval foundations behind finding information. |
| **02 — Search Engine Fundamentals** | Search-engine architecture and operational search pipeline. | Domain 02 owns how a search engine operationally processes documents and retrieves candidates. Domain 04 owns the underlying IR models, representations, and retrieval theory. |
| **03 — Search Engine Algorithms** | Search-engine ranking systems, ranking signals, relevance systems, and ranking evaluation. | Domain 03 owns engine-side evaluation and ordering. Domain 04 owns general retrieval models and formal IR evaluation theory. |
| **05 — Keyword & Search Intent** | Keyword research, query meaning, classification, and searcher intent from the SEO perspective. | Domain 05 interprets queries for SEO. Domain 04 studies query representation and matching as retrieval problems. |
| **06 — SERP & Search Features** | SERP composition, visible result formats, and search features. | Domain 04 explains retrieval methods that may supply candidates; Domain 06 owns the user-visible result experience. |
| **09 — Semantic SEO** | Semantic content architecture, entities, topical relationships, and semantic optimization. | Domain 09 owns semantic SEO strategy and implementation. Domain 04 owns semantic retrieval methods and their technical foundations. |
| **10 — Technical SEO** | Website-side technical implementation and search accessibility. | Domain 10 owns website implementation. Domain 04 does not prescribe SEO implementation based on a retrieval model. |
| **14 — SEO Analytics** | SEO measurement, reporting, and business interpretation. | Domain 14 owns site-owner organic performance measurement. Domain 04 owns evaluation of retrieval systems and research test collections. |
| **16 — AI & Search Evolution** | Broader impact of AI on search products, discovery, and the search ecosystem. | Domain 16 owns the wider AI-search landscape. Domain 04 owns the retrieval methods themselves. |
| **17 — k41-version** | Experiments, unconventional tactics, and original k41 investigations. | Domain 17 may test retrieval-related hypotheses, but must link to established IR methods and label experimental evidence accurately. |

### Boundary Rules

- **Operational indexing vs. IR indexing:** Domain 02.6 explains how search engines organize and maintain their production indexes. Domain 04.4 explains retrieval-oriented data structures and indexing theory. Related concepts do not make the documents duplicates.
- **Operational retrieval vs. retrieval theory:** Domain 02.8 explains the retrieval stage in a search-engine pipeline. Domain 04 explains the models, representations, and evaluation methods that underpin retrieval.
- **Retrieval vs. ranking:** retrieval identifies candidate items; ranking evaluates and orders candidates for a particular search context. Domain 04 owns general retrieval theory. Domain 03 owns search-engine ranking systems and their behavior. Some architectures combine retrieval and ranking-like scoring, so the distinction is functional rather than a claim that deployed components are always separate.
- **Document processing vs. text processing:** Domain 02.5 covers system-level processing and rendering of acquired resources. Domain 04.3 covers text transformations used to represent content for retrieval.
- **Relevance modeling vs. search-engine relevance systems:** Domain 04 explains relevance as an IR concept and how it is assessed in retrieval research. Domain 03.4 owns search-engine-side query-document relevance and ranking behavior.
- **Neural retrieval vs. neural ranking:** Domain 04.9 covers neural methods used to retrieve candidate items. Domain 03.11 covers machine-learning and neural methods used to evaluate or order candidates in ranking. A model may participate in more than one stage; document the function being discussed.
- **IR evaluation vs. ranking evaluation:** Domain 04.11–04.12 owns general IR evaluation methodology and metric theory. Domain 03.12 explains how evaluation and testing are applied to search-engine ranking systems.
- **IR evaluation vs. SEO analytics:** Domain 04 evaluates retrieval systems against defined tasks and relevance judgments. Domain 14 measures a website's observed organic search performance and business outcomes.

These are editorial ownership rules. They do not imply that real search systems have perfectly isolated stages or that a public paper reveals how a particular search engine implements its production stack.

## Research & Documentation Principles

Every topic must follow [AGENTS.md](../AGENTS.md). Domain 04 applies these additional rules:

1. **Start with foundational literature and original research.** Use established IR textbooks for core concepts, then inspect the original papers, specifications, and benchmark documentation relevant to each method.
2. **Keep the task explicit.** Identify whether a source concerns document retrieval, passage retrieval, ad hoc search, question answering, recommendation, or another task. Do not treat their evaluation setups as interchangeable.
3. **Explain assumptions.** Retrieval models make assumptions about representation, term independence, relevance, language, collection statistics, or training data. State the assumptions that matter to the method being discussed.
4. **Separate model theory from deployment.** A method's mathematical definition or benchmark result does not prove that Google, Bing, or another production search engine uses it.
5. **Compare methods on fair terms.** When discussing performance, identify datasets, baselines, metrics, evaluation conditions, and computational trade-offs. Do not generalize one benchmark result into a universal winner.
6. **Treat relevance as a judgment, not an absolute label.** Explain the task, assessor instructions, relevance scale, and limitations where they affect evaluation.
7. **Keep retrieval and ranking distinct.** Explain a method according to its role—candidate generation, retrieval scoring, re-ranking, or final result ordering. Do not silently move concepts across Domain 03 and Domain 04.
8. **Avoid duplicate explanations.** Link to operational search architecture in Domain 02, ranking mechanisms in Domain 03, and SEO applications in their canonical domains.
9. **Cite claims at claim level.** Every substantive topic requires inline citations and a matching References section. A bibliography alone does not satisfy [AGENTS.md](../AGENTS.md).

## Key Reference Sources

These are starting points for research, not a frozen whitelist. Each topic must inspect and cite the specific source that supports its claims.

- Christopher D. Manning, Prabhakar Raghavan, and Hinrich Schütze. [Introduction to Information Retrieval](https://nlp.stanford.edu/IR-book/). Cambridge University Press, 2008. The online companion includes chapters on Boolean retrieval, inverted indexes, vector-space scoring, evaluation, relevance feedback, probabilistic retrieval, language models, and related topics.
- Stephen Robertson and Hugo Zaragoza. [The Probabilistic Relevance Framework: BM25 and Beyond](https://doi.org/10.1561/1500000019). *Foundations and Trends in Information Retrieval*, 3(4), 2009.
- Kalervo Järvelin and Jaana Kekäläinen. [Cumulated Gain-based Evaluation of IR Techniques](https://doi.org/10.1145/582415.582418). *ACM Transactions on Information Systems*, 20(4), 422–446, 2002.
- Vladimir Karpukhin et al. [Dense Passage Retrieval for Open-Domain Question Answering](https://aclanthology.org/2020.emnlp-main.550/). *Proceedings of EMNLP*, 2020.
- Nandan Thakur et al. [BEIR: A Heterogeneous Benchmark for Zero-shot Evaluation of Information Retrieval Models](https://arxiv.org/abs/2104.08663). 2021.

## Content Navigation

- [Repository README](../README.md)
- [AGENTS.md](../AGENTS.md)
- [Domain 02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md)
- [Domain 03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md)
- [04.1 — Introduction to Information Retrieval](04.1-Introduction-to-Information-Retrieval.md) — defines the IR problem, core terminology, relevance, and the scope of the discipline.
- [04.2 — Information Representation & Document Modeling](04.2-Information-Representation-and-Document-Modeling.md) — defines retrievable units, document granularity, metadata, fields, structure, and representation choices.
- 04.3 — Text Processing & Term Representation — planned.
- 04.4 — Information Retrieval Indexing & Data Structures — planned.
- 04.5 — Boolean Retrieval Model — planned.
- 04.6 — Vector Space Model & Term Weighting — planned.
- 04.7 — Probabilistic Information Retrieval Models — planned.
- 04.8 — Relevance Feedback & Query Expansion — planned.
- 04.9 — Semantic & Neural Information Retrieval — planned.
- 04.10 — Hybrid & Advanced Retrieval Methods — planned.
- 04.11 — Relevance Assessment & Evaluation Frameworks — planned.
- 04.12 — Information Retrieval Evaluation Metrics — planned.

---

*Domain 04 defines the canonical scope and roadmap for Information Retrieval. Its topic pages will be marked documented only after they are researched, sourced, integrated, and reviewed.*


## Development Status

| Area | Status | Current coverage |
|---|---|---|
| Domain architecture | Established | Scope, ownership boundaries, four topic groups, and the 12-topic roadmap are defined. |
| Topic 04.1 — Introduction to Information Retrieval | Documented | Foundational IR problem, terminology, relevance, system-level concepts, and SEO connections are documented with cited academic sources. |
| Topic 04.2 — Information Representation & Document Modeling | Documented | Document units, granularity, content, metadata, fields, structure, modeling approaches, and task-dependent trade-offs are documented with cited IR literature and metadata standards. |
| Topics 04.3–04.12 | Planned | Topic ownership and scope are defined; detailed documents have not yet been created. |
| Cross-domain integration | In progress | Parent navigation and links to existing Domain 02, 03, 05, 09, and 10 resources are established; integration will expand as related topic pages are developed. |

