# Domain 10 — Technical SEO

## Language and Canonical Versions

English is the sole publication language of SEO-Playbook. Each topic has one canonical English document; parallel language editions are not maintained.

## Domain Purpose

Domain 10 documents the technical implementation and operational conditions that affect how websites are delivered, accessed, crawled, rendered, consolidated, and technically evaluated by search systems.

Its canonical focus is **website-side technical delivery and validation**: site architecture, URL handling, crawler controls, indexability directives, HTTP behavior, rendering, mobile delivery, performance, structured data, technical monitoring, and quality assurance.

Technical SEO is not a ranking-factor checklist or a promise that a technically valid page will be indexed or rank. Technical correctness creates reliable conditions for access and processing; search systems retain independent discovery, selection, indexing, and ranking decisions.

## Scope and Ownership

### What Domain 10 owns

- Website-side technical architecture and URL implementation.
- Crawl accessibility, crawl management, and site-side crawl diagnostics.
- robots.txt and crawler access-control implementation.
- XML sitemap generation, submission, and maintenance.
- Indexability directives, canonical implementation, and duplicate URL controls.
- HTTP response behavior, redirects, and URL/site migrations.
- JavaScript-dependent content delivery and rendering diagnostics.
- Mobile delivery and responsive technical implementation.
- Website performance diagnostics and Core Web Vitals optimization.
- Technical structured-data implementation and validation.
- Server-log analysis, technical monitoring, and crawl diagnostics.
- Technical SEO audits, issue prioritization, QA, and regression testing.

### What Domain 10 does not own

| Related domain | Canonical ownership | Boundary with Domain 10 |
|---|---|---|
| [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md) | Search-engine architecture and provider-side crawling, rendering, indexing, retrieval, and serving | Domain 02 explains search systems; Domain 10 implements and diagnoses website-side conditions. |
| [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md) | Ranking systems, signals, relevance, quality systems, and ranking evaluation | Technical recommendations are not confirmed ranking weights or guarantees. |
| [04 — Information Retrieval](../04-Information-Retrieval/README.md) | Retrieval theory, document representation, indexing structures, and evaluation | Domain 10 covers web delivery and site controls, not retrieval models or search-index internals. |
| [05 — Keyword & Search Intent](../05-Keyword-and-Search-Intent/README.md) | Keyword research, intent inference, clustering, prioritization, and query-to-page mapping | Domain 10 does not own query research or content targeting. |
| [06 — SERP & Search Features](../06-SERP-and-Search-Features/README.md) | Search result presentation, rich-result formats, and feature behavior | Domain 10 implements structured data; Domain 06 owns search appearance and feature behavior. |
| [07 — On-Page SEO](../07-On-Page-SEO/README.md) | Page-level authoring, HTML elements, titles, descriptions, headings, image context, and semantic HTML | Domain 07 owns authored page elements; Domain 10 owns site-wide delivery, resource loading, crawl controls, canonicalization, and technical performance. |
| [08 — Content SEO](../08-Content-SEO/README.md) | Editorial strategy, production, QA, revision, and content lifecycle | Domain 10 covers technical publication and delivery, not editorial decisions or content quality. |
| [09 — Semantic SEO](../09-Semantic-SEO/README.md) | Entity/concept models, semantic relationships, topical models, and semantic information architecture | Domain 09 defines meaning and models; Domain 10 implements technical representations such as structured data. |
| Domain 11 — Internal Linking | Internal-link architecture, linking strategy, anchor text, and implementation | Domain 11 owns hyperlink strategy; Domain 10 may diagnose technical accessibility of links and paths. |
| Domain 13 — International & Local SEO | International, language, regional, and local SEO strategy | Domain 13 owns market/language decisions; Domain 10 may explain bounded implementation such as locale delivery and hreflang. |
| Domain 14 — SEO Analytics | Organic performance measurement, analysis, and reporting | Domain 10 owns technical diagnostics and monitoring; Domain 14 owns organic outcomes and attribution. |

### Canonical Boundary Rules

1. Search-engine behavior is not website implementation.
2. Crawlability is not indexability.
3. robots.txt is not an indexing directive or security boundary.
4. A sitemap is a discovery hint, not an indexing command.
5. Canonicalization is not a substitute for coherent URL architecture.
6. Technical rendering is not content strategy.
7. Structured data is an implementation layer: Domain 09 owns meaning, Domain 10 owns deployment, and Domain 06 owns search appearance.
8. Performance metrics are not ranking guarantees.
9. Technical monitoring is not organic analytics.
10. A passing audit is scoped; state URLs, templates, environments, tools, sampling, date, criteria, and limitations.

## Domain Structure

### Group A — Technical SEO Foundations

| Topic | Title | Canonical scope |
|---|---|---|
| 10.1 | [Introduction to Technical SEO](Introduction to Technical SEO) | Technical SEO concerns the technical conditions under which a website is delivered and made available to users and automated systems. It connects web engineering decisions with search accessibility without claiming control over a search engine's independent processing or ranking decisions. |
| 10.2 | [Website Architecture & URL Structure](Website Architecture & URL Structure) | Website architecture and URL structure define how resources are organized and addressed at the technical layer. They influence maintainability, consistent delivery, URL discovery, and management of large or parameterized URL inventories. |

### Group B — Crawling, Indexability & URL Management

| Topic | Title | Canonical scope |
|---|---|---|
| 10.3 | [Crawlability & Crawl Management](Crawlability & Crawl Management) | Crawlability describes whether a crawler can discover and retrieve a resource under the site's technical configuration and the crawler's own policies, capacity, and scheduling. It does not guarantee that a URL will be crawled on a particular schedule. |
| 10.4 | [Robots.txt & Crawler Access Control](Robots.txt & Crawler Access Control) | robots.txt is a plain-text file implementing the Robots Exclusion Protocol (REP). It communicates crawler access rules for matching URL paths; it is not authentication, authorization, or a reliable mechanism for keeping private resources out of public indexes. |
| 10.5 | [XML Sitemaps & URL Discovery Support](XML Sitemaps & URL Discovery Support) | An XML sitemap is a machine-readable inventory of URLs that a site makes available to search engines. It can support discovery and provide metadata, but it does not command a search engine to crawl, index, or display every listed URL. |
| 10.6 | [Indexability, Canonicalization & Duplicate URL Management](Indexability, Canonicalization & Duplicate URL Management) | Indexability is the set of conditions under which a search engine can consider a resource for inclusion in its index. Site operators can provide directives and canonical hints, but search engines make their own indexing and canonical-selection decisions. |
| 10.7 | [HTTP Status Codes, Redirects & URL Migration](HTTP Status Codes, Redirects & URL Migration) | HTTP status codes communicate the outcome of a request. Redirects tell clients that further action is required, while error and success responses have distinct protocol meanings. Technical SEO depends on returning responses that accurately represent resource state. |

### Group C — Rendering, Mobile & Performance

| Topic | Title | Canonical scope |
|---|---|---|
| 10.8 | [JavaScript SEO & Rendering Optimization](JavaScript SEO & Rendering Optimization) | JavaScript SEO examines whether important page content, metadata, and navigable links are available in the representations that browsers and search crawlers can process. It is a delivery and rendering problem, not a blanket argument for or against JavaScript frameworks. |
| 10.9 | [Mobile SEO & Responsive Technical Implementation](Mobile SEO & Responsive Technical Implementation) | Mobile technical SEO concerns whether the mobile experience exposes the content, metadata, resources, and functionality required by users and search systems. It includes responsive behavior and the technical implications of serving different representations to different devices. |
| 10.10 | [Website Performance & Core Web Vitals](Website Performance & Core Web Vitals) | Website performance work measures and improves how quickly and reliably a page responds and renders for users. Core Web Vitals are field-oriented user-experience metrics; they are not a complete performance model and should not be treated as a deterministic ranking formula. |

### Group D — Structured Data, Diagnostics & Quality Control

| Topic | Title | Canonical scope |
|---|---|---|
| 10.11 | [Structured Data Implementation & Validation](Structured Data Implementation & Validation) | Structured data is a machine-readable representation of information associated with a page or resource. This topic covers technical implementation and validation. Conceptual meaning and entity modeling belong to Domain 09; visible search features and behavior belong to Domain 06. |
| 10.12 | [Server Logs, Crawl Diagnostics & Technical Monitoring](Server Logs, Crawl Diagnostics & Technical Monitoring) | Server logs record requests handled by a web server or intermediary. Analysis can reveal how crawlers and other clients interact with a site, but log data must be interpreted in the context of infrastructure, caching, proxies, and logging configuration. |
| 10.13 | [Technical SEO Auditing & Quality Assurance](Technical SEO Auditing & Quality Assurance) | A technical SEO audit is a scoped assessment of website implementation and delivery against explicit technical criteria. Quality assurance extends that assessment into release checks, regression prevention, and remediation verification. |

## Cross-Domain Integration

- Domain 02 → Domain 10: search-system behavior informs publisher-side implementation and diagnostics.
- Domain 07 ↔ Domain 10: page-level authoring and site-wide delivery are complementary.
- Domain 09 → Domain 10: semantic models inform structured-data requirements; Domain 10 implements the technical representation.
- Domain 10 ↔ Domain 11: crawl-path diagnostics inform internal-link work; Domain 11 owns hyperlink strategy.
- Domain 10 ↔ Domain 13: international/local requirements may need technical implementation; strategy remains in Domain 13.
- Domain 10 → Domain 14: technical diagnostics provide context; organic measurement and attribution remain in Domain 14.

## Technical SEO Working Model

1. Establish the site, URL inventory, templates, environments, and intended indexable resources.
2. Check server availability, HTTPS, response codes, redirects, and resource delivery.
3. Check crawler access, robots directives, sitemap coverage, and crawl paths.
4. Check canonical consistency, duplicate URL variants, and indexability directives.
5. Inspect rendered output, JavaScript-dependent content, and mobile parity.
6. Measure field and lab performance using appropriate metrics and representative templates.
7. Validate structured data against syntax, schema constraints, visible content, and applicable search-feature policies.
8. Analyze logs and monitoring data, then prioritize and validate remediation.

This is a diagnostic workflow, not a ranking formula or proof that every step is required for every site.

## Research and Evidence Principles

Use current official search-engine documentation for engine-specific behavior; standards bodies and protocol specifications for HTTP, HTML, robots exclusion, and sitemap formats; and reproducible tests for observed site behavior. Separate technical validity, accessibility, feature eligibility, indexing outcomes, and ranking outcomes. Record environment, URL sample, device, geography, time window, and measurement source where relevant.

## References

- Google Search Central. ([Crawling and indexing](https://developers.google.com/search/docs/crawling-indexing)).
- Google Search Central. ([JavaScript SEO basics](https://developers.google.com/search/docs/crawling-indexing/javascript/javascript-seo-basics)).
- Google Search Central. ([Robots meta tag and X-Robots-Tag](https://developers.google.com/search/docs/crawling-indexing/robots-meta-tag)).
- Google Crawling Infrastructure. ([Optimize your crawl budget](https://developers.google.com/crawling/docs/crawl-budget)).
- Google Search Central. ([What is URL canonicalization](https://developers.google.com/search/docs/crawling-indexing/canonicalization)).
- Google Search Central. ([What is a sitemap](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview)).
- Google Search Central. ([Mobile-first indexing best practices](https://developers.google.com/search/docs/crawling-indexing/mobile/mobile-sites-mobile-first-indexing)).
- Google Search Central. ([General structured data guidelines](https://developers.google.com/search/docs/appearance/structured-data/sd-policies)).
- Google Crawling Infrastructure. ([HTTP status codes and Google crawlers](https://developers.google.com/crawling/docs/troubleshooting/http-status-codes)).
- IETF. ([RFC 9110: HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110.html)).
- IETF. ([RFC 9309: Robots Exclusion Protocol](https://www.rfc-editor.org/rfc/rfc9309.html)).
- web.dev. ([Web Vitals](https://web.dev/articles/vitals)).
