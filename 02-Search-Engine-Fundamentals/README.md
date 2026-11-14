# 02 — Search Engine Fundamentals

> Understand the system behind search. No algorithm folklore, no SEO implementation detours.

## Domain Purpose

Search Engine Fundamentals explains how search engines operate as systems: how they discover information, acquire and process documents, organize searchable collections, handle queries, retrieve candidate documents, and deliver results.

The domain covers search engines in general, with **web search engines as the primary context** and **Google Search as the main implementation reference**. Other engines—such as Microsoft Bing—are used for comparison where their documented approaches add useful context.

Google is the primary reference, not a universal blueprint. A mechanism documented for Google must not be presented as a rule followed by every search engine. Public documentation also does not expose every internal implementation detail.

Google describes its Search process through crawling, indexing, and serving. This domain expands that high-level view into system components and processing stages while keeping Google-specific statements attributed to Google. ([Google Search Central](https://developers.google.com/search/docs/fundamentals/how-search-works); [Microsoft Bing](https://support.microsoft.com/en-us/bing/how-bing-delivers-search-results))

## Scope

This domain focuses on:

- The purpose, types, and high-level architecture of search engines.
- Web discovery and crawling as system processes.
- Document acquisition, rendering, parsing, and preparation.
- Index construction, organization, and maintenance at a system level.
- Query handling and retrieval as stages in the search pipeline.
- Result generation and delivery.
- The infrastructure, scale, and operational constraints behind search systems.

The emphasis is on **what the system does, how its major components fit together, and how information moves through it**. Detailed mathematical models, ranking logic, query intent analysis, and SEO implementation belong elsewhere.

## Knowledge Structure

| ID | Topic | Scope |
|---|---|---|
| [02.1](02.1-Introduction-to-Search-Engines.md) | **Introduction to Search Engines** | What search engines are, what problems they solve, their core functions, and the distinction between web search and other search systems. |
| [02.2](02.2-Search-Engine-Architecture.md) | **Search Engine Architecture** | The major components of a search engine, their responsibilities, and how information flows between them. |
| [02.3](02.3-Web-Discovery.md) | **Web Discovery** | How search systems identify URLs and other discoverable resources that may enter their processing pipeline. |
| [02.4](02.4-Web-Crawling.md) | **Web Crawling** | How crawlers request resources, handle responses, revisit known URLs, and manage crawl activity. |
| [02.5](02.5-Document-Processing-and-Rendering.md) | **Document Processing & Rendering** | How acquired resources are rendered, parsed, and transformed into information that downstream systems can process. |
| [02.6](02.6-Search-Indexing.md) | **Search Indexing** | How processed information is organized, stored, updated, and made available for search. |
| 02.7 | **Query Processing** | How a search system receives and prepares a query for retrieval, without taking over keyword research or search-intent analysis. |
| 02.8 | **Search Retrieval** | How a system uses a query to locate candidate information from its searchable collections. |
| 02.9 | **Search Result Generation & Serving** | How retrieved candidates move through result assembly and delivery to the search experience. Ranking algorithms and SERP presentation are covered elsewhere. |
| 02.10 | **Search Engine Infrastructure** | The distributed computing, storage, networking, and operational foundations required to run search at scale. |
| 02.11 | **Search Engine Types & Models** | How search engines differ by scope, corpus, retrieval model, and service design, with web search as the main reference context. |
| 02.12 | **Search Engine Limitations** | System-level constraints, incomplete coverage, freshness trade-offs, uncertainty, and reasons search results cannot represent the entire web perfectly. |

This is the domain's topic architecture. Individual topic documents should explain their assigned subject in depth rather than repeating the whole search pipeline.

## Search Pipeline: Working Model

Use this as a conceptual map, not a claim that every search engine implements identical components or a strictly linear pipeline:

1. **Discovery** identifies resources that may be processed.
2. **Crawling** retrieves accessible resources.
3. **Document processing** extracts and prepares information.
4. **Indexing** organizes information into searchable structures.
5. **Query processing** prepares the user's request.
6. **Retrieval** locates candidate information.
7. **Result generation and serving** assembles and delivers the response.

Real systems may run these processes asynchronously, distribute them across services, repeat stages, or use additional components. Google's public explanation groups its process into crawling, indexing, and serving; the finer-grained stages above are this domain's explanatory structure, not a disclosure of Google's complete internal architecture. ([Google Search Central](https://developers.google.com/search/docs/fundamentals/how-search-works))

## Scope Boundaries

Domain 02 owns the **search engine as a system**. It introduces the role of algorithms, information retrieval, queries, and result presentation only as needed to explain the system pipeline.

| Domain | Its canonical focus | Boundary with Domain 02 |
|---|---|---|
| **03 — Search Engine Algorithms** | Algorithms, ranking systems, signals, and evaluation mechanisms. | Domain 02 identifies where algorithmic decisions fit in the system; Domain 03 explains the algorithms and ranking behavior. |
| **04 — Information Retrieval** | IR theory, retrieval models, indexing theory, scoring methods, and deeper retrieval techniques. | Domain 02 explains the operational role of indexing and retrieval; Domain 04 explains their theoretical and methodological foundations. |
| **05 — Keyword & Search Intent** | Search queries, keywords, query classification, and searcher intent from the SEO perspective. | Domain 02 explains query handling inside a search system; Domain 05 studies queries and intent as SEO subjects. |
| **06 — SERP & Search Features** | SERP composition, result formats, and search features. | Domain 02 covers result generation and delivery; Domain 06 covers what users see on the results page. |
| **10 — Technical SEO** | Website-side technical conditions and optimization affecting search accessibility and processing. | Domain 02 explains crawler and processing behavior; Domain 10 covers the website-side implications and optimization. |

### Boundary Rules

- **Discovery vs. crawling:** discovery identifies a resource; crawling requests and retrieves it. They are related, not interchangeable.
- **Processing vs. indexing:** processing extracts and prepares information; indexing organizes information for later search.
- **Retrieval vs. ranking:** retrieval identifies candidate information; ranking systems determine ordering and relative prominence. Detailed ranking belongs in Domain 03, while retrieval theory belongs in Domain 04.
- **Query processing vs. search intent:** Domain 02 covers the system's handling of an input query. Domain 05 covers what the query expresses and how SEOs interpret it.
- **Serving vs. SERP features:** Domain 02 covers delivering a search response. Domain 06 covers the structure and features of its presentation.
- **Crawler behavior vs. technical SEO:** Domain 02 explains how crawling works. Domain 10 explains how site architecture, directives, responses, and implementation affect crawler access.

These boundaries are editorial ownership rules. They do not imply that real search systems have perfectly isolated stages or components.

## Research & Documentation Principles

Every topic in this domain must follow the repository-wide rules in [AGENTS.md](../AGENTS.md), with these domain-specific requirements:

1. **Start with general principles.** Explain the system-level concept before using a vendor's implementation as an example.
2. **Prioritize Google, attribute precisely.** Use Google's official documentation as the primary reference for Google Search behavior. Say "Google documents" when describing Google's published explanation; do not imply that it reveals undisclosed internals.
3. **Compare other engines carefully.** Use the relevant engine's official documentation for its own behavior. Do not assume that Bing, Google, or another provider implements the same pipeline in the same way.
4. **Keep the domain boundaries intact.** Explain algorithms, IR theory, query intent, SERP features, and SEO implementation only to the depth required by the system-level topic. Link to their canonical domains when those documents exist.
5. **Separate evidence from the model.** Label conceptual diagrams, generalized architectures, and editorial abstractions as such. Distinguish documented implementation details from general principles and reasoned interpretation.
6. **Acknowledge what is not public.** Search engines are complex proprietary systems. Do not invent internal components, data flows, infrastructure details, or exact processing rules when public evidence does not establish them.
7. **Explain mechanisms and constraints.** Definitions alone are not enough. Show how components interact, what inputs and outputs they handle, and where limitations or exceptions apply.
8. **Use traceable sources.** Cite substantive claims inline and include a matching References section in every substantive topic document.

## References

- Google. ([In-Depth Guide to How Google Search Works](https://developers.google.com/search/docs/fundamentals/how-search-works)). Google Search Central. Accessed 2026-11-14.
- Microsoft. ([How Bing Delivers Search Results](https://support.microsoft.com/en-us/bing/how-bing-delivers-search-results)). Microsoft Support; last updated March 2025. Accessed 2026-11-14.


## Content Navigation

| ID | Topic |
|---|---|
| [02.1](02.1-Introduction-to-Search-Engines.md) | Introduction to Search Engines |
| [02.2](02.2-Search-Engine-Architecture.md) | Search Engine Architecture |
| [02.3](02.3-Web-Discovery.md) | Web Discovery |
| [02.4](02.4-Web-Crawling.md) | Web Crawling |
| [02.5](02.5-Document-Processing-and-Rendering.md) | Document Processing & Rendering |
| [02.6](02.6-Search-Indexing.md) | Search Indexing |
