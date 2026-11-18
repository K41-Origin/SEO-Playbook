# Domain 06 — SERP & Search Features

## Domain Purpose

Domain 06 documents how search engines present information on search engine results pages (SERPs) and related search interfaces.

Its canonical focus is **search presentation**: SERP structure, organic result components, enhanced result formats, specialized search features, interactive refinements, and AI-powered search experiences visible to users.

The goal is to understand what appears on the results page, how the documented presentation works, what conditions or eligibility rules apply, and what the visible interface does—and does not—tell us. A SERP feature is a presentation format, not a magic SEO badge or a ranking guarantee.

## Scope and Ownership

### What Domain 06 owns

- SERP anatomy, page structure, layout, and visible result composition.
- The presentation components of standard organic results, including title links, snippets, URLs, site names, favicons, breadcrumbs, and sitelinks.
- Enhanced search appearances and rich-result formats, including their documented eligibility and display limitations.
- Featured snippets and other direct-answer presentation formats, with careful distinctions between their underlying feature types.
- Knowledge panels and entity-oriented information presentations.
- Local, map-based, news, image, video, shopping, and product-related SERP features.
- Interactive SERP components that support query refinement or continued exploration.
- AI-powered SERP features and generative search interfaces, limited to their visible experience, result presentation, source attribution, and user interaction.
- Cross-engine comparison of SERP presentation where primary documentation or observable evidence supports it.
- Feature availability, display variability, lifecycle changes, deprecation, and documentation freshness.

### What Domain 06 does not own

| Related domain | Canonical ownership | Boundary with Domain 06 |
|---|---|---|
| [01 — SEO Fundamentals](../01-SEO-Fundamentals/README.md) | SEO purpose, disciplines, visibility, ecosystem, and business value | Domain 01 explains SEO's role and objectives. Domain 06 explains search-result presentation. |
| [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md) | Search-engine architecture, query processing, retrieval, result generation, and serving | Domain 02 owns the operational pipeline. Domain 06 describes the visible SERP and feature formats, not the private serving architecture. |
| [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md) | Ranking systems, ranking signals, relevance, specialized ranking, and ranking evaluation | Domain 03 owns candidate evaluation, ordering, and ranking-side selection. Domain 06 owns how result features are presented. A feature's appearance does not disclose its ranking mechanism. |
| [04 — Information Retrieval](../04-Information-Retrieval/README.md) | IR theory, representations, retrieval models, and formal evaluation | Domain 04 owns general retrieval theory. Domain 06 does not re-teach retrieval models or IR metrics. |
| [05 — Keyword & Search Intent](../05-Keyword-and-Search-Intent/README.md) | Keyword research, intent inference, SERP-based intent validation, clustering, prioritization, and keyword-to-page mapping | Domain 05 uses visible SERP patterns as evidence for query research. Domain 06 owns the feature taxonomy, presentation, and documented behavior being observed. |
| Domain 07 — On-Page SEO (planned) | Page-level optimization and implementation | Domain 06 may explain how page elements appear in search results; Domain 07 owns on-page changes intended to improve the source page. |
| Domain 08 — Content SEO (planned) | Content planning, production, optimization, and maintenance | Domain 06 explains result presentation, not editorial production or content optimization workflows. |
| Domain 09 — Semantic SEO (planned) | Entities, semantic relationships, topical coverage, and semantic content architecture | Domain 06 describes entity-oriented SERP presentations such as knowledge panels; Domain 09 owns semantic content and entity architecture. |
| Domain 10 — Technical SEO (planned) | Technical implementation, structured data implementation, crawling/indexing controls, and technical validation | Domain 06 explains supported search appearances, eligibility, and display behavior. Domain 10 owns implementation and validation of structured data and technical controls. |
| Domain 11 — Internal Linking (planned) | Internal link architecture and implementation | Domain 06 may describe sitelinks as a search presentation feature; Domain 11 owns the site's internal-linking strategy and implementation. |
| Domain 13 — International & Local SEO (planned) | International targeting and local SEO strategy/execution | Domain 06 describes local and geographic SERP presentations; Domain 13 owns local SEO and international strategy. |
| Domain 14 — SEO Analytics (planned) | Site-owner organic performance measurement and reporting | Domain 06 explains what is displayed. Domain 14 owns analysis of impressions, clicks, CTR, position, and business outcomes. |
| Domain 16 — AI & Search Evolution (planned) | AI-driven discovery, search-system evolution, and broader ecosystem implications | Domain 06 documents the visible AI search experience. Domain 16 owns broader technological evolution, system-level changes, and strategic implications. |
| Domain 17 — k41-version (experimental) | Original k41 experiments and unconventional SEO investigations | Domain 06 documents established features and evidence. Domain 17 may test hypotheses about feature behavior but must not replace canonical feature documentation. |

### Canonical Boundary Rules

1. **Presentation is not processing.** Domain 06 explains the user-visible result interface. Crawling, indexing, query processing, retrieval, and serving architecture remain in Domain 02.
2. **Presentation is not ranking.** Domain 06 does not explain why a document or feature was selected, how candidates were scored, or how result order was determined. Those mechanisms belong to Domain 03 where documented.
3. **SERP observation is not intent research.** Domain 05 owns the research method for inferring and validating search intent. Domain 06 owns the feature descriptions that make SERP observations interpretable.
4. **Feature documentation is not implementation guidance.** Domain 06 explains search appearance, feature eligibility, and display limitations. Technical implementation and validation belong to Domain 10; on-page changes belong to Domain 07.
5. **Structured data does not guarantee a rich result.** Valid markup or eligibility does not guarantee that a search engine will display a particular enhancement for a page or query.
6. **Feature labels are not interchangeable.** Featured snippets, direct answers, knowledge panels, rich results, and AI-generated responses must be distinguished by documented behavior and presentation—not grouped together because they occupy prominent SERP space.
7. **Local presentation is not local SEO strategy.** Local packs and map-based results belong here as presentation features; local optimization strategy belongs to Domain 13.
8. **AI presentation is not AI system architecture.** Domain 06.11 covers the visible AI-powered search experience. Generative response assembly and serving architecture belongs to Domain 02.9; broader AI/search evolution belongs to Domain 16.
9. **Search Console measurement is not feature documentation.** Domain 06 may explain feature-related reporting concepts only as needed to clarify presentation; ongoing site-performance measurement belongs to Domain 14.
10. **Availability is conditional and time-sensitive.** Search features vary by engine, market, language, device, query, policy, and product changes. Never imply universal availability or permanent support without evidence.

## Domain Structure

The domain is organized into three groups. The sequence moves from the structure of a results page, to specific search features, then to interactive and AI-powered search experiences.

### Group A — SERP Foundations & Organic Result Presentation

| Topic | Title | Canonical scope |
|---|---|---|
| 06.1 | Introduction to SERPs & SERP Anatomy | Defines SERPs and explains their overall structure, major regions, result composition, layout variation, and the distinction between standard results and specialized presentation modules. Establishes the vocabulary needed by the remaining Domain 06 topics without duplicating search processing or intent research. |
| [06.2](06.2-Organic-Search-Result-Elements-and-Presentation.md) | Organic Search Result Elements & Presentation | Documents the visible components of standard organic results, including title links, snippets, source attribution, visible URLs, site names, favicons, breadcrumbs, byline dates, sitelinks, and optional result enrichments. Focuses on provider-documented presentation behavior, not page implementation. |

### Group B — Search Features & Enhanced Results

| Topic | Title | Canonical scope |
|---|---|---|
| [06.3](06.3-Rich-Results-and-Structured-Data-Search-Appearance.md) | Rich Results & Structured Data Search Appearance | Explains structured data as a source of explicit page information, the distinction between Schema.org vocabulary and Google's supported Search features, rich-result eligibility, validation limits, display variability, and feature retirement. Does not teach markup implementation or promise display. |
| [06.4](06.4-Featured-Snippets-and-Direct-Answers.md) | Featured Snippets & Direct Answers | Documents selected page-excerpt presentations, placements, source attribution, query-specific selection caveats, snippet controls, and distinctions from rich results, knowledge panels, and AI answers. Does not become a featured-snippet optimization checklist. |
| 06.5 | Knowledge Panels & Entity-Based Search Features | Documents knowledge panels and other entity-oriented information presentations, including their visible components, source attribution, entity relationships, and display limitations. Semantic entity modeling remains in Domain 09. |
| 06.6 | Local & Map-Based SERP Features | Documents local packs, map results, location-oriented result modules, and business information displayed in search interfaces. Local SEO strategy and business-profile optimization remain in Domain 13. |
| 06.7 | News & Top Stories Search Features | Explains news-oriented SERP modules, Top Stories presentation, publisher/result components, temporal display characteristics, and documented availability. News ranking systems remain in Domain 03. |
| 06.8 | Image & Video Search Features | Documents image and video result formats, thumbnails, previews, carousels, visual metadata, and related search presentation. Media production and technical optimization remain in their canonical content and technical domains. |
| 06.9 | Shopping & Product Search Features | Explains product-oriented organic and commercial search appearances, product information modules, merchant/product result formats, and their presentation differences. Merchant implementation and commerce strategy remain outside this domain. |

### Group C — Interactive & AI-Powered Search Experiences

| Topic | Title | Canonical scope |
|---|---|---|
| 06.10 | Interactive SERP & Query Refinement Features | Documents interactive components such as People Also Ask, related searches, query suggestions, refinement controls, and other interface elements that help users continue or narrow a search. Does not duplicate keyword discovery or intent-classification workflows. |
| 06.11 | AI-Powered SERP Features & Search Experiences | Documents user-visible AI search experiences, including AI Overviews, AI Mode, generative answer layouts, source/citation presentation, links, and interaction patterns where officially documented. Search architecture belongs to Domain 02; broader AI and search evolution belongs to Domain 16. |

The roadmap defines canonical ownership, not a claim that every named feature is currently available in every market or search engine. Each topic must verify current feature status, terminology, eligibility, and source documentation before describing a feature as active.

## Documentation and Research Principles

- **Describe what users can actually see.** Use precise descriptions of visible components and distinguish direct observation from provider-documented behavior.
- **Separate provider facts from interpretation.** Attribute Google-specific or Bing-specific statements to the relevant provider. Do not generalize one engine's behavior to all search engines.
- **Treat feature availability as conditional.** Record the engine, market, language, device, query context, and observation date when these affect a claim.
- **Separate eligibility from display.** Structured data validity, feature eligibility, and actual appearance are different states. Never present one as a guarantee of another.
- **Distinguish similarly named features.** Explain differences between rich results, featured snippets, knowledge panels, direct answers, and AI-generated experiences.
- **Do not infer ranking internals from presentation.** A visible feature or its position does not reveal the full selection or ranking process.
- **Use current primary sources.** For Google Search features, start with the specific Google Search Central documentation and current Search Gallery. Use official Bing documentation for Bing-specific behavior. Check update notes and feature status for volatile claims.
- **Use screenshots carefully.** Record the search engine, query, locale, language, device, date, and relevant context. Screenshots are observations, not proof of universal behavior or hidden system mechanisms.
- **Keep implementation elsewhere.** Link to Domains 07, 10, and 13 when a reader needs implementation or strategy; do not reproduce those workflows here.
- **Maintain one canonical explanation.** Cross-link to Domains 02–05 and 07–16 rather than copying their mechanisms, taxonomies, or measurement frameworks.
- **Make uncertainty visible.** Search interfaces change. Mark retired, renamed, experimental, limited, or unverified features accurately and include the date of verification when relevant.

## Development Status

| Area | Status | Coverage |
|---|---|---|
| Domain architecture | Defined | Scope, ownership boundaries, three topic groups, and the 11-topic roadmap are established. |
| [06.1 — Introduction to SERPs & SERP Anatomy](06.1-Introduction-to-SERPs-and-SERP-Anatomy.md) | Documented | Foundational SERP definition, structural model, major regions, result categories, query-dependent composition, observation method, and ownership boundaries documented. |
| [06.2 — Organic Search Result Elements & Presentation](06.2-Organic-Search-Result-Elements-and-Presentation.md) | Documented | Standard organic-result components, Google-specific presentation behavior, title links, snippets, attribution, visible URLs, byline dates, sitelinks, optional enrichments, and observation boundaries documented. |
| [06.3 — Rich Results & Structured Data Search Appearance](06.3-Rich-Results-and-Structured-Data-Search-Appearance.md) | Documented | Structured-data concepts, Schema.org versus Google Search support, rich-result eligibility, policy boundaries, validation tools, display limitations, and feature lifecycle changes documented. |\n| [06.4 — Featured Snippets & Direct Answers](06.4-Featured-Snippets-and-Direct-Answers.md) | Documented | Featured-snippet definition, placements, source relationship, automated selection limits, snippet controls, policy boundaries, and distinction from other answer-oriented SERP features documented. |\n| Cross-domain integration | Architecture and topic-level review (2026-11-19) | The roadmap was compared with existing Domains 01–05; topics 06.1–06.4 received targeted content-level integration reviews. Topics 06.5–06.11 still require topic-level review after drafting. |
| Source audit | Topic-level reviews in progress | Topics 06.1–06.4 have received source verification, citation checks, freshness review, and targeted duplicate/integration QA. Topics 06.5–06.11 require the same review when drafted. |

## Related Domains

- [01 — SEO Fundamentals](../01-SEO-Fundamentals/README.md)
- [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md)
- [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md)
- [04 — Information Retrieval](../04-Information-Retrieval/README.md)
- [05 — Keyword & Search Intent](../05-Keyword-and-Search-Intent/README.md)

## References

These are domain-level entry points and source registries. Individual topic documents must cite the exact current sources that directly support their claims.

1. Google Search Central. ([Search appearance documentation](https://developers.google.com/search/docs/appearance)). Official documentation hub for Google Search result presentation.
2. Google Search Central. ([Search Gallery](https://developers.google.com/search/docs/appearance/structured-data/search-gallery)). Current reference for Google-supported structured-data search appearances; verify feature status when each topic is researched.
3. Google Search Central. ([Introduction to structured data](https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data)). Official guidance on structured data and Google Search appearance eligibility.
4. Google Search Central. ([Influencing title links in search results](https://developers.google.com/search/docs/appearance/title-link)). Official documentation for title-link generation and presentation.
5. Google Search Central. ([Control your snippets in search results](https://developers.google.com/search/docs/appearance/snippet)). Official documentation for snippet controls and presentation.
6. Google Search Central. ([AI features and your website](https://developers.google.com/search/docs/appearance/ai-features)). Official documentation for website presence in Google's AI search features; check for updates before relying on specific behavior.
7. Microsoft Bing Webmaster Guidelines. ([Bing Webmaster Guidelines](https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a)). Official Bing guidance; use more specific current Bing feature documentation where available.
