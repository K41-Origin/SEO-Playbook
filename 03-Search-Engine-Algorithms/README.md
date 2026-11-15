# 03 — Search Engine Algorithms

> Ranking is not one magic score. Understand the systems, evidence, and trade-offs behind result ordering.

## Domain Purpose

Search Engine Algorithms explains how search engines evaluate and order candidate results for a query. It covers ranking systems, ranking signals, relevance, link analysis, quality and spam systems, freshness, context, machine learning, evaluation, and system evolution.

The domain covers search engines generally, with **web search as the primary context, Google Search as the main implementation reference, and other engines such as Bing as comparative references**.

The goal is to understand ranking mechanisms—not to collect alleged ranking factors or turn every announced update into a separate SEO superstition.

Search engines are proprietary systems. Public documentation can establish what a provider says about its systems, but it rarely reveals the complete implementation, feature set, signal weights, or decision logic. This domain must never pretend otherwise.

## Scope

Domain 03 owns the **search-engine-side evaluation and ordering of candidate results**.

It covers:

- The concepts and architecture of search ranking systems.
- Ranking signals and how different signal categories may interact.
- Query-document relevance and link-based analysis.
- Quality, helpfulness, originality, spam, and freshness systems.
- Contextual and specialized ranking behavior.
- Machine-learning and neural approaches documented in ranking.
- How ranking systems are evaluated, tested, updated, and evolved.

It does not own website implementation, SEO execution, general information-retrieval theory, search-engine infrastructure, keyword research, or the user-visible design of the SERP. Those subjects have their own canonical domains and are connected below.

## Knowledge Structure

| ID | Topic | Canonical scope |
|---|---|---|
| [03.1](03.1-Introduction-to-Search-Ranking-Systems.md) | **Introduction to Search Ranking Systems** | What ranking systems do, why ranking is needed, and the distinctions between algorithms, systems, signals, models, factors, and updates. |
| [03.2](03.2-Ranking-Architecture-and-Multi-Stage-Ranking.md) | **Ranking Architecture & Multi-Stage Ranking** | Conceptual ranking stages, candidate evaluation, re-ranking, system interaction, and the limits of what public sources reveal about deployed architecture. |
| [03.3](03.3-Ranking-Signals-and-Signal-Interaction.md) | **Ranking Signals & Signal Interaction** | Signal categories, page-level and site-wide signals, signal interpretation, combinations, and the limits of public knowledge about weights. |
| [03.4](03.4-Relevance-and-Query-Document-Matching.md) | **Relevance & Query-Document Matching** | How ranking systems assess the relationship between a query and candidate documents, including lexical, semantic, passage-level, and contextual relevance. |
| [03.5](03.5-Link-Analysis-and-PageRank.md) | **Link Analysis & PageRank** | Web link graphs, link analysis, PageRank, link-derived evidence, manipulation risks, and the limits of public knowledge about modern implementations. |
| 03.6 | **Content Quality, Helpfulness & Originality Systems** | Search systems associated with content quality, helpfulness, originality, and reliable information. |
| [03.7](03.7-Spam-Detection-and-Demotion-Systems.md) | **Spam Detection & Demotion Systems** | Detection and treatment of search spam, manipulation, policy violations, signal neutralization, and ranking demotions. |
| [03.8](03.8-Freshness-and-Temporal-Ranking.md) | **Freshness & Temporal Ranking** | How time-sensitive relevance is handled, including freshness-related systems, query-dependent freshness needs, temporal evidence, and content age. |
| [03.9](03.9-Contextual-Ranking-and-Personalization.md) | **Contextual Ranking & Personalization** | How search systems use request context and individual-specific information, while distinguishing localization, personalization, and ordinary result variability. |
| [03.10](03.10-Specialized-and-Result-Specific-Ranking-Systems.md) | **Specialized & Result-Specific Ranking Systems** | Specialized ranking and result-set mechanisms for local results, editorial reviews, news, site diversity, and deduplication. |
| [03.11](03.11-Machine-Learning-and-Neural-Ranking-Systems.md) | **Machine Learning & Neural Ranking Systems** | Machine-learning and neural methods used in ranking and ranking-related retrieval, including documented systems such as RankBrain, BERT, neural matching, and passage ranking. |
| [03.12](03.12-Ranking-Evaluation-and-Testing.md) | **Ranking Evaluation & Testing** | How ranking systems are evaluated through offline measures, live experiments, human assessment, behavioral feedback, and quality guardrails. |
| 03.13 | **Ranking Updates & System Evolution** | Core updates, system changes, integration or retirement of named systems, historical developments, and how to interpret update announcements. |

This table defines canonical ownership. Individual topic documents should explain their assigned subject in depth and link to adjacent topics rather than reproducing their content.

## Ranking Model: Conceptual Flow

Use this as a learning model, not a literal diagram of Google's or Bing's undisclosed production architecture:

1. **Candidate retrieval** supplies documents that may be relevant to a query. The operational search pipeline is introduced in [Domain 02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md); deeper retrieval theory belongs to Domain 04.
2. **Relevance assessment** evaluates how well candidates address the query.
3. **Signal and system evaluation** considers relevant evidence about documents, sources, links, context, quality, freshness, and other documented dimensions.
4. **Specialized processing and re-ranking** may apply additional systems for particular query or result contexts.
5. **Result ordering** produces an ordered set for downstream result generation and serving.

Real systems may combine, parallelize, repeat, or otherwise organize these responsibilities differently. This sequence is an explanatory abstraction, not a claim about exact internal architecture. Google's public documentation describes multiple ranking systems and signal types, but does not disclose a complete universal scoring formula or every production stage. ([Google Search ranking systems guide](https://developers.google.com/search/docs/appearance/ranking-systems-guide); [How Google Search works](https://developers.google.com/search/docs/fundamentals/how-search-works))

## Canonical Ownership & Cross-Domain Integration

The same subject can affect several SEO disciplines without requiring the same explanation to be copied into every domain. **Domain 03 owns the search-engine ranking mechanism. Other domains own their own perspective and implementation.**

| Domain | Canonical ownership | Integration rule |
|---|---|---|
| **01 — SEO Fundamentals** | SEO definitions, visibility, ecosystem, objectives, and discipline overview. | Domain 01 introduces ranking as part of organic visibility. Domain 03 explains how ranking systems evaluate and order results. |
| **02 — Search Engine Fundamentals** | Search-engine architecture and operational pipeline. | Domain 02 identifies where ranking sits after retrieval; Domain 03 owns ranking mechanisms and behavior. |
| **04 — Information Retrieval** | IR theory, formal retrieval models, mathematical scoring, and foundational retrieval methods. | Domain 04 owns general theory and formal models; Domain 03 owns documented search-engine ranking systems and their applied behavior. |
| **05 — Keyword & Search Intent** | Keyword research, query meaning, classification, and searcher intent for SEO. | Domain 05 owns query and intent analysis; Domain 03 owns how ranking systems assess query-document relevance. |
| **06 — SERP & Search Features** | SERP composition, visible result formats, and search features. | Domain 03 explains algorithmic selection or ordering where documented; Domain 06 explains how results and features appear to users. |
| **07 — On-Page SEO** | Website-side page elements and their optimization. | Domain 07 owns implementation; Domain 03 explains only the documented ranking role of relevant signals. |
| **08 — Content SEO** | Content strategy, planning, production, and optimization. | Domain 08 owns creating and improving content; Domain 03 owns the search-engine systems associated with quality, helpfulness, and originality. |
| **09 — Semantic SEO** | Semantic content architecture, entities, topical relationships, and semantic optimization. | Domain 09 owns semantic SEO methods; Domain 03 owns documented semantic and neural ranking systems. |
| **10 — Technical SEO** | Website-side technical implementation and search accessibility. | Domain 10 owns implementation; Domain 03 explains only the ranking implications supported by evidence. |
| **11 — Internal Linking** | Internal link architecture and implementation. | Domain 11 owns internal linking strategy; Domain 03 owns link-analysis and PageRank mechanisms. |
| **12 — Off-Page SEO** | Backlinks, digital reputation, promotion, and off-site SEO practices. | Domain 12 owns off-page practice; Domain 03 owns link-based ranking and documented link-spam treatment. |
| **13 — International & Local SEO** | Website and business implementation for geographic and language markets. | Domain 13 owns localization and international SEO execution; Domain 03 owns documented geographic and contextual ranking mechanisms. |
| **14 — SEO Analytics** | SEO measurement, reporting, and business interpretation. | Domain 14 owns SEO performance measurement; Domain 03 owns search-engine ranking evaluation and experimentation. |
| **15 — Advanced SEO** | Advanced SEO applications and cross-disciplinary methods. | Domain 15 integrates established knowledge from specialist domains; it must link to canonical explanations rather than duplicate them. |
| **16 — AI & Search Evolution** | The broader impact of AI on search products, discovery, and the search ecosystem. | Domain 16 owns the wider AI-search landscape; Domain 03 owns machine-learning and neural methods specifically used in ranking. |
| **17 — k41-version** | Experiments, unconventional tactics, and original k41 investigations. | Domain 17 may test ranking-related hypotheses, but must link to Domain 03 for established mechanisms and label evidence maturity accurately. |

### Boundary Rules

- **Retrieval vs. ranking:** retrieval finds candidate documents; ranking evaluates and orders them. Domain 02 covers the pipeline role, Domain 04 covers retrieval theory, and Domain 03 covers ranking systems.
- **Relevance vs. search intent:** Domain 05 studies what a query means to a searcher and SEO; Domain 03 studies the engine-side assessment of query-document relevance.
- **Ranking systems vs. ranking signals:** a system is a mechanism or collection of mechanisms; a signal is evidence that may be used by a system. Do not use these terms interchangeably.
- **Ranking updates vs. ranking systems:** an update changes or improves systems; it is not necessarily a new system. Domain 03.13 owns update history, while each system's mechanism belongs to its canonical topic.
- **Ranking vs. SERP presentation:** Domain 03 owns algorithmic evaluation and ordering; Domain 06 owns user-visible result layouts and features.
- **Ranking relevance vs. SEO implementation:** Domain 03 explains documented search-engine behavior; implementation and optimization belong to the relevant SEO domain.
- **Ranking evaluation vs. SEO analytics:** Domain 03 covers how search systems assess their own ranking quality; Domain 14 covers how site owners measure SEO outcomes.

These are editorial boundaries. They do not imply that production systems have perfectly isolated components or that every ranking decision can be assigned to one publicly known signal.

## Evidence & Research Rules

Every topic must follow [AGENTS.md](../AGENTS.md). Domain 03 applies these additional rules:

1. **Start with primary evidence.** For Google ranking behavior, consult the current Google Search Central ranking systems guide and the most specific linked documentation. For Bing, use Microsoft's official documentation. Use academic papers and standards for general methods and theory.
2. **Attribute every engine-specific claim.** State which search engine the evidence describes. A Google implementation is not automatically a universal search-engine rule.
3. **Do not invent the formula.** Do not claim to know exact signal weights, thresholds, feature combinations, or production architecture unless reliable evidence actually establishes them.
4. **Separate systems, signals, and updates.** Preserve the difference between a named ranking system, a signal, a model, an algorithmic method, and an update to an existing system.
5. **Do not manufacture ranking factors.** Industry repetition, correlation studies, patents, leaked documents, and isolated experiments do not independently prove that a factor is currently used in production ranking.
6. **Treat patents carefully.** A patent documents a claimed invention or possible method. It does not prove that the method was implemented, remains active, or is used by a particular search engine.
7. **Track lifecycle accurately.** Label systems as currently documented, integrated into broader systems, retired, historical, or unclear. Recheck volatile claims against current official sources.
8. **Do not flatten specialized systems into universal ranking.** A system used for a particular search context must not be described as affecting every query or every result.
9. **Keep ML claims specific.** Do not infer that a technology is used in general ranking merely because a search engine uses it somewhere in Search. Document its stated scope and limitations.
10. **Distinguish public facts from interpretation.** Label conceptual models and reasoned interpretations. Explicitly state when internal behavior is not publicly disclosed.
11. **Avoid duplicate explanations.** Give each concept one canonical home. Other documents should summarize only what is needed for context and link to the owner.
12. **Keep citations close to claims.** Every substantive topic needs inline citations and a matching References section, as required by AGENTS.md.

## Key Reference Sources

These are starting points, not a substitute for topic-level research. Each topic must cite the specific sources that support its claims.

- Google. [A guide to Google Search ranking systems](https://developers.google.com/search/docs/appearance/ranking-systems-guide). Google Search Central. Accessed 2026-11-14.
- Google. [In-depth guide to how Google Search works](https://developers.google.com/search/docs/fundamentals/how-search-works). Google Search Central. Accessed 2026-11-14.
- Google. [Spam policies for Google web search](https://developers.google.com/search/docs/essentials/spam-policies). Google Search Central. Accessed 2026-11-14.
- Google. [Creating helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content). Google Search Central. Accessed 2026-11-14.
- Google. [Google Search documentation updates](https://developers.google.com/search/updates). Google Search Central. Accessed 2026-11-14.
- Google. [Google Search Status Dashboard — ranking updates](https://status.search.google.com/products/rGHU1u87FJnkP6W2GwMi/history). Google. Accessed 2026-11-14.
- Microsoft. [Bing Webmaster Guidelines](https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a). Microsoft Bing. Accessed 2026-11-14.

## Content Navigation

The links below point to documents that currently exist. Topic IDs define the agreed architecture; detailed topic pages are linked as they are documented.

- [Domain 01 — SEO Fundamentals](../01-SEO-Fundamentals/README.md)
- [Domain 02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md)
- [03.1 — Introduction to Search Ranking Systems](03.1-Introduction-to-Search-Ranking-Systems.md)
- [03.2 — Ranking Architecture & Multi-Stage Ranking](03.2-Ranking-Architecture-and-Multi-Stage-Ranking.md)
- [03.3 — Ranking Signals & Signal Interaction](03.3-Ranking-Signals-and-Signal-Interaction.md)
- [03.4 — Relevance & Query-Document Matching](03.4-Relevance-and-Query-Document-Matching.md)
- [03.5 — Link Analysis & PageRank](03.5-Link-Analysis-and-PageRank.md)
- [03.6 — Content Quality, Helpfulness & Originality Systems](03.6-Content-Quality-Helpfulness-and-Originality-Systems.md)
- [03.7 — Spam Detection & Demotion Systems](03.7-Spam-Detection-and-Demotion-Systems.md)
- [03.8 — Freshness & Temporal Ranking](03.8-Freshness-and-Temporal-Ranking.md)
- [03.9 — Contextual Ranking & Personalization](03.9-Contextual-Ranking-and-Personalization.md)
- [03.10 — Specialized & Result-Specific Ranking Systems](03.10-Specialized-and-Result-Specific-Ranking-Systems.md)
- [03.11 — Machine Learning & Neural Ranking Systems](03.11-Machine-Learning-and-Neural-Ranking-Systems.md)
- [Repository README](../README.md)
- [AGENTS.md](../AGENTS.md)
