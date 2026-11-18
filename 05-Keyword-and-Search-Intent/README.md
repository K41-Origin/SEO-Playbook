# Domain 05 — Keyword & Search Intent

## Domain Purpose

Domain 05 documents how SEO practitioners research the language people use in search, interpret the needs behind queries, and turn that evidence into a defensible keyword strategy.

The focus is **search demand and query-level research**: discovering candidate queries, understanding what they mean in context, evaluating available keyword data, grouping related queries, and deciding which opportunities deserve attention.

Keyword research is not a list-exporting contest. A large spreadsheet full of volume estimates is not a strategy. The useful work is connecting query evidence to audience needs, business relevance, competition, and the pages that can genuinely satisfy those needs.

## Scope and Ownership

### What Domain 05 owns

- Keyword research as an SEO research discipline and its workflow.
- Seed keyword discovery and the collection of language used by audiences.
- Keyword expansion, modifiers, variants, and query patterns.
- Keyword data sources, metrics, estimation limits, and interpretation.
- Search intent concepts, taxonomies, and classification uncertainty.
- SERP observation as evidence for interpreting query intent.
- Keyword clustering and query grouping for research purposes.
- Opportunity assessment and keyword prioritization.
- Keyword-to-page mapping as a research deliverable and the handoff to content planning.

### What Domain 05 does not own

| Related domain | Canonical ownership | Boundary with Domain 05 |
|---|---|---|
| [01 — SEO Fundamentals](../01-SEO-Fundamentals/README.md) | SEO purpose, disciplines, visibility, and business value | Domain 01 explains why SEO matters; Domain 05 researches query demand and intent that may support those objectives. |
| [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md) | Search-engine architecture, query processing, retrieval, and serving | Domain 02 explains how search systems process queries; Domain 05 studies queries as SEO research objects. Do not duplicate tokenization, query rewriting, or retrieval mechanics. |
| [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md) | Ranking systems, relevance, ranking signals, and ranking evaluation | Domain 03 explains how systems assess and rank results; Domain 05 interprets likely user intent and market/query opportunity. Intent research is not a ranking-factor manual. |
| [04 — Information Retrieval](../04-Information-Retrieval/README.md) | IR theory, retrieval models, semantic/neural retrieval, and formal IR evaluation | Domain 04 owns retrieval theory. Domain 05 may use its terminology where necessary but does not re-teach retrieval models or IR metrics. |
| [06 — SERP & Search Features](../06-SERP-and-Search-Features/README.md) *(planned)* | SERP components, result formats, and search features | Domain 05 may inspect visible SERPs to infer intent and result expectations. Domain 06 will own the taxonomy and mechanics of SERP features themselves. |
| [07 — On-Page SEO](../07-On-Page-SEO/README.md) *(planned)* | Page-level optimization and implementation | Domain 05 identifies query targets and intent; Domain 07 owns on-page implementation. |
| [08 — Content SEO](../08-Content-SEO/README.md) *(planned)* | Content planning, production, optimization, and maintenance | Domain 05 produces research and query-to-page recommendations. Domain 08 owns editorial strategy and content execution. |
| [09 — Semantic SEO](../09-Semantic-SEO/README.md) *(planned)* | Entities, semantic relationships, topical coverage, and semantic content architecture | Keyword clustering in Domain 05 groups queries for research and targeting; semantic entity/topic modeling belongs to Domain 09. Similar words do not make the concepts interchangeable. |
| [13 — International & Local SEO](../13-International-and-Local-SEO/README.md) *(planned)* | International and local search strategy | Domain 05 covers general query research. Locale-specific demand, language-market adaptation, and local strategy belong to Domain 13 when developed. |
| [14 — SEO Analytics](../14-SEO-Analytics/README.md) *(planned)* | Site-owner performance measurement and reporting | Domain 05 may use Search Console query data as research evidence; Domain 14 owns ongoing organic performance analysis and reporting. |

Planned domain paths above are ownership references only. Their files do not exist yet and are not working navigation destinations.

### Canonical boundary rules

1. **Query research is not query processing.** Domain 05 studies the queries people use and the demand they express. Domain 02 documents how a search engine processes a submitted query.
2. **Intent inference is not ranking-system disclosure.** Search intent labels are analytical models. They do not reveal a search engine's internal classification or guarantee a particular ranking outcome.
3. **SERP inspection is evidence, not SERP-feature documentation.** Domain 05 uses result patterns to validate intent; Domain 06 will explain the features and result components.
4. **Keyword clusters are not semantic topic maps.** Query grouping supports research and page targeting. Entity relationships and topical architecture belong to Domain 09.
5. **Keyword-to-page mapping is a handoff, not content production.** Domain 05 documents which query groups may fit which pages. Editorial briefs, content creation, and page optimization belong to Domains 08 and 07.
6. **Keyword metrics are not performance guarantees.** Search volume, competition, CPC, trend indices, and third-party difficulty scores are source-dependent estimates or proxies. They must not be treated as exact demand, organic ranking difficulty, or expected traffic.
7. **Search Console query data is observed site performance, not a complete market-demand dataset.** It describes reported performance for a property under Search Console's definitions and limitations; it does not replace broader keyword discovery.

## Domain Structure

The domain is organized into three groups. The sequence moves from collecting query evidence, to interpreting intent, then turning the research into decisions.

### Group A — Keyword Research Foundations

| Topic | Title | Canonical scope |
|---|---|---|
| 05.1 | Introduction to Keyword Research | Defines keyword research, its purpose, outputs, workflow, and role in SEO strategy. Establishes the difference between a keyword, a query, a topic, and an information need without duplicating IR theory. |
| 05.2 | Seed Keyword & Audience-Language Discovery | Develops seed terms from products, services, audiences, customer language, existing site knowledge, and first-party evidence. |
| 05.3 | Keyword Expansion & Query Variations | Expands seeds into modifiers, long-tail queries, question patterns, lexical variants, and related formulations; explains source overlap and discovery bias. |
| 05.4 | Keyword Data Sources & Metrics | Evaluates Keyword Planner, Google Trends, Search Console, internal site search, third-party tools, and qualitative sources; defines volume, trend, competition, CPC, and difficulty caveats. |

### Group B — Search Intent & SERP Interpretation

| Topic | Title | Canonical scope |
|---|---|---|
| 05.5 | Search Intent Concepts & Taxonomies | Explains informational, navigational, transactional, and other useful intent models; covers mixed, layered, ambiguous, and changing intent. |
| 05.6 | SERP-Based Intent Analysis & Validation | Uses result types, page formats, result diversity, and query context as observable evidence to validate or challenge an intent hypothesis. Does not teach the mechanics of SERP features. |

### Group C — Keyword Strategy & Research Outputs

| Topic | Title | Canonical scope |
|---|---|---|
| 05.7 | Keyword Clustering & Query Grouping | Groups queries using intent, SERP overlap, lexical similarity, and task relevance; distinguishes practical keyword clusters from semantic entity/topic models. |
| 05.8 | Keyword Opportunity & Prioritization | Assesses relevance, demand, business value, intent fit, current visibility, effort, and uncertainty to prioritize research opportunities without reducing decisions to one arbitrary score. |
| 05.9 | Keyword-to-Page Mapping & Research Deliverables | Turns validated clusters into target-page assignments, identifies mapping conflicts and coverage gaps, and defines a clear handoff to content planning without owning content production. |

## Research Principles

- **Start with the audience, not a tool export.** Tools reveal patterns in their datasets; they do not define the full vocabulary or needs of a market.
- **Treat metrics as evidence with context.** Record source, market, language, network, date range, and methodology where available.
- **Do not confuse paid and organic metrics.** Advertising competition and CPC describe advertising-market conditions; they are not direct measurements of organic ranking difficulty.
- **Use intent as a hypothesis.** A query can express more than one reasonable need, and the dominant interpretation can vary by context, location, and time.
- **Inspect actual results when intent matters.** SERP patterns can provide useful evidence, but they are snapshots and can vary across users, locations, devices, and dates.
- **Do not worship volume.** A low-volume query with strong relevance and conversion potential may be more valuable than a high-volume query with weak fit.
- **Make uncertainty visible.** Estimated volume, third-party difficulty, inferred intent, and clustering thresholds all have limitations.
- **Keep one canonical explanation.** Cross-link to Domains 02–04 and future related domains instead of copying their technical material.

## Development Status

| Area | Status | Coverage |
|---|---|---|
| Domain architecture | Established | Scope, ownership boundaries, three topic groups, and nine-topic roadmap are defined. |
| Topic 05.1–05.9 | Planned | Topic pages have not yet been created. |
| Cross-domain integration | Initial boundaries defined | Existing relationships to Domains 01–04 are identified; reciprocal topic links will be added as pages are documented. |
| Source audit | Pending | Each substantive topic will receive claim-level citations and source verification before being marked complete. |

## Related Domains

- [01 — SEO Fundamentals](../01-SEO-Fundamentals/README.md)
- [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md)
- [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md)
- [04 — Information Retrieval](../04-Information-Retrieval/README.md)

## References

These sources establish key foundations and data-source behavior for the domain roadmap. Individual topic documents must add and cite the specific sources that support their substantive claims.

1. Broder, A. ([A Taxonomy of Web Search](https://doi.org/10.1145/792550.792552)). *ACM SIGIR Forum*, 36(2), 3–10, 2002. https://doi.org/10.1145/792550.792552.
2. Google Ads Help. ([Use Keyword Planner](https://support.google.com/google-ads/answer/7337243)). Accessed 2026-11-18.
3. Google Ads Help. ([About Keyword Planner forecasts](https://support.google.com/google-ads/answer/3022575)). Accessed 2026-11-18.
4. Google Trends Help. ([FAQ about Google Trends data](https://support.google.com/trends/answer/4365533)). Accessed 2026-11-18.
5. Google Search Console Help. ([Performance report: Search results](https://support.google.com/webmasters/answer/7576553)). Accessed 2026-11-18.
