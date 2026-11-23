# Domain 07 — On-Page SEO


## Language and Canonical Versions

English is the sole publication language for SEO-Playbook. Each topic has one canonical English document; parallel language editions are not maintained.

## Domain Purpose

Domain 07 documents how to optimize the elements and structure of an individual web page so its purpose, subject, and information are clear to both people and search systems.

Its canonical focus is **page-level optimization**: the page title element, meta description, heading hierarchy, URL wording and structure, image elements and alternative text, and meaningful HTML semantics. It also defines how to assess and implement these elements consistently across a site.

On-page SEO is not a bag of keyword-placement tricks. A page does not become relevant because someone sprinkled an exact-match phrase into every available HTML element. Optimization must preserve the page's actual purpose, accurately represent its content, and improve clarity and usability. No individual element should be presented as a guaranteed ranking lever without evidence.

## Scope and Ownership

### What Domain 07 owns

- The principles and practical scope of page-level on-page optimization.
- Alignment between a page's purpose, target query context, and its visible and HTML elements.
- HTML title element optimization (commonly called the title tag).
- Meta description writing and page-specific description quality.
- Heading elements (H1–H6) and their information hierarchy.
- Descriptive URL wording and page-level URL structure decisions.
- Image-element optimization, including meaningful alternative text, filenames, and contextual use.
- Semantic HTML element selection and page-structure meaning at the document level.
- Repeatable workflows for implementing, reviewing, and auditing on-page elements.
- Page-level quality checks for consistency, clarity, accessibility, and avoidable optimization errors.

### What Domain 07 does not own

| Related domain | Canonical ownership | Boundary with Domain 07 |
|---|---|---|
| [01 — SEO Fundamentals](../01-SEO-Fundamentals/README.md) | SEO purpose, disciplines, visibility, ecosystem, and business value | Domain 01 explains SEO's role and objectives. Domain 07 covers one practical SEO discipline: page-level optimization. |
| [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md) | Search-engine architecture, crawling, rendering, indexing, query processing, retrieval, and serving | Domain 02 explains how search systems process web resources. Domain 07 explains how page elements are authored and optimized; it does not reproduce crawler, renderer, or index architecture. |
| [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md) | Ranking systems, ranking signals, relevance assessment, and ranking evaluation | Domain 03 owns algorithmic relevance and ranking explanations. Domain 07 applies page-level optimization practices but must not claim that a specific element has a known ranking weight or guarantees rankings. |
| [04 — Information Retrieval](../04-Information-Retrieval/README.md) | IR theory, document representation, retrieval models, and formal evaluation | Domain 04 owns the theory behind representation and retrieval. Domain 07 does not re-teach tokenization, term weighting, vector models, or retrieval metrics. |
| [05 — Keyword & Search Intent](../05-Keyword-and-Search-Intent/README.md) | Keyword research, intent inference, clustering, prioritization, and keyword-to-page mapping | Domain 05 determines query targets and research-based page mapping. Domain 07 owns the implementation and optimization of page-level elements after those decisions. |
| [06 — SERP & Search Features](../06-SERP-and-Search-Features/README.md) | SERP anatomy, result components, feature formats, and search presentation | Domain 06 owns how title links, snippets, URLs, and other elements are represented in search results. Domain 07 owns the source-page elements that may inform those presentations. Search engines can rewrite or select displayed text; source markup is not a display guarantee. |
| [Domain 08 — Content SEO](../08-Content-SEO/README.md) | Content strategy, editorial planning, production, quality assurance, optimization, and content lifecycle management | Domain 08 owns content substance and editorial development. Domain 07 owns page-level structural and HTML elements. Heading optimization must not become a substitute for content strategy or quality. |
| Domain 09 — Semantic SEO | Entities, semantic relationships, topical coverage, and semantic content architecture | Domain 09 owns entity modeling and broader semantic architecture. Domain 07 may use clear, descriptive language and semantic HTML, but does not own entity graphs, topical authority models, or semantic topic-map design. |
| [10 — Technical SEO](../10-Technical-SEO/README.md) | Technical implementation, crawling/indexing controls, structured data, rendering, performance, and technical validation | Domain 10 owns technical delivery and search-engine access. Domain 07 may discuss an element's authoring and page-level purpose; image compression/delivery, responsive behavior, lazy loading, canonicalization, robots directives, structured-data implementation, and Core Web Vitals remain in Domain 10. |
| Domain 11 — Internal Linking (planned) | Internal-link architecture, linking strategy, and anchor-text practice | Domain 11 owns internal-link strategy and implementation. Domain 07 does not absorb internal-link architecture into its page-element checklist. |
| Domain 14 — SEO Analytics (planned) | Organic performance measurement, analysis, and reporting | Domain 07 defines page-level audit criteria. Domain 14 owns performance measurement and outcome analysis; an on-page audit finding is not proof of ranking or traffic impact. |
| Domain 17 — k41-version (experimental) | Original k41 experiments and unconventional SEO investigations | Domain 07 owns canonical, evidence-backed on-page guidance. Experimental claims must be tested and labeled in Domain 17 rather than promoted into standard guidance without sufficient evidence. |

### Canonical Boundary Rules

1. **Keyword research is upstream; page optimization is downstream.** Domain 05 owns query discovery, intent analysis, clustering, prioritization, and keyword-to-page mapping. Domain 07 owns page-level implementation and must not recreate the research workflow.
2. **Page relevance is not ranking-system disclosure.** Domain 03 owns search-engine relevance and ranking mechanisms. Domain 07 may explain how page elements communicate a page's subject and purpose, but must not invent ranking weights or deterministic formulas.
3. **Source elements are not SERP presentation.** Domain 07 owns the authored title element and meta description. Domain 06 owns title-link and snippet presentation, including search-engine rewriting and query-dependent selection.
4. **Page structure is not content strategy.** Domain 07 owns headings and structural elements as page-level organization. Domain 08 owns editorial planning, substantive content quality, production, and maintenance.
5. **Semantic HTML is not a ranking shortcut.** Explain semantic elements in terms of document meaning, structure, and accessibility. Do not claim that choosing a particular semantic element automatically improves rankings unless direct evidence supports that specific claim.
6. **Image authoring is not image delivery infrastructure.** Domain 07 owns image context, filenames, and alternative text. Domain 10 owns file formats, compression, responsive delivery, loading behavior, and technical performance.
7. **URL wording is not URL control infrastructure.** Domain 07 may cover readable, descriptive URL design. Canonicalization, redirects, parameter handling, crawl controls, and indexation behavior belong to Domain 10.
8. **Page-level checks are not performance measurement.** Domain 07 defines implementation and quality checks. Domain 14 owns the analysis of impressions, clicks, CTR, rankings, traffic, and business outcomes.
9. **Internal links have a canonical home.** Domain 11 owns internal-link strategy, architecture, and anchor text. Domain 07 should not duplicate those topics.
10. **Recommendations are not guarantees.** Distinguish documented search-engine guidance, usability/accessibility rationale, practitioner convention, and hypotheses. Never turn a recommended practice into a universal ranking factor without adequate evidence.

## Domain Structure

The domain is organized into three groups: foundational principles, core page-level elements, and operational implementation and assessment.

### Group A — Foundations

| Topic | Title | Canonical scope |
|---|---|---|
| 07.1 | [Introduction to On-Page SEO](07.1-Introduction-to-On-Page-SEO.md) | Defines on-page SEO, its purpose, scope, components, relationship with adjacent SEO disciplines, and common misconceptions. Establishes the domain's terminology and ownership boundaries. |
| 07.2 | [Page-Level Relevance & Optimization Principles](07.2-Page-Level-Relevance-and-Optimization-Principles.md) | Explains page purpose, query-to-page fit as an implementation context, element-level relevance, contextual consistency, and defensible optimization principles. Does not reproduce Domain 03's query-document relevance or ranking theory, or Domain 05's intent-research workflow. |

### Group B — Core On-Page Elements

| Topic | Title | Canonical scope |
|---|---|---|
| 07.3 | [Title Tags & Page Title Optimization](07.3-Title-Tags-and-Page-Title-Optimization.md) | Covers the HTML title element, its distinction from the H1, descriptive and page-specific wording, keyword use without stuffing, brand inclusion, duplication, consistency with page content, and common implementation mistakes. SERP title-link presentation and rewriting remain in Domain 06. |
| 07.4 | [Meta Descriptions & Snippet Optimization](07.4-Meta-Descriptions-and-Snippet-Optimization.md) | Covers the meta description element, useful page-specific summaries, intent and content alignment, duplication, length considerations, and common mistakes. Distinguishes authored descriptions from search-generated snippets; does not claim meta descriptions are a direct ranking factor or that search engines always use them. |
| 07.5 | [Heading Structure & Hierarchy Optimization](07.5-Heading-Structure-and-Hierarchy-Optimization.md) | Covers H1–H6 semantics, logical hierarchy, descriptive headings, information organization, multiple-H1 considerations, accessibility, and common mistakes. Editorial substance and content quality remain in Domain 08. |
| 07.6 | [URL Structure & Page-Level URL Optimization](07.6-URL-Structure-and-Page-Level-URL-Optimization.md) | Covers readable and descriptive URL design, slugs, word and separator choices, path organization, consistency, and practical trade-offs. Redirects, canonicalization, parameter handling, and crawl/index controls remain in Domain 10. |
| 07.7 | [Image SEO & Image Element Optimization](07.7-Image-SEO-and-Image-Element-Optimization.md) | Covers image relevance and context, alternative text, descriptive filenames, captions where useful, informative versus decorative images, accessibility, and common mistakes. Image delivery, compression, responsive behavior, and performance remain in Domain 10. |
| 07.8 | [HTML Semantics & Page Element Optimization](07.8-HTML-Semantics-and-Page-Element-Optimization.md) | Covers semantic versus generic HTML elements, meaningful document structure, appropriate use of main/article/section/header/footer/nav and related elements, and accessibility implications. Does not claim semantic HTML automatically improves rankings or expand into rendering infrastructure. |

### Group C — Implementation & Quality Control

| Topic | Title | Canonical scope |
|---|---|---|
| 07.9 | [On-Page Optimization Workflow & Implementation](07.9-On-Page-Optimization-Workflow-and-Implementation.md) | Defines a repeatable workflow for selecting pages, reviewing evidence, identifying opportunities, planning changes, prioritizing work, implementing elements, documenting decisions, and performing quality control across new and existing pages. |
| 07.10 | [On-Page SEO Auditing & Quality Assessment](07.10-On-Page-SEO-Auditing-and-Quality-Assessment.md) | Defines an audit framework for title elements, meta descriptions, headings, URLs, image elements, and HTML semantics. Covers audit scope, evidence, issue classification, severity, prioritization, consistency checks, sampling, reporting, and remediation validation. Performance measurement and outcome attribution remain in Domain 14. |

## Cross-Domain Integration

The intended relationship is a connected knowledge workflow, not a rigid linear pipeline:

- **Domain 05 → Domain 07:** keyword research, intent analysis, and keyword-to-page mapping provide the query and page-target context for on-page implementation.
- **Domain 07 ↔ Domain 08:** page elements and content substance must remain consistent. Domain 07 owns structural and HTML elements; Domain 08 owns editorial planning and content quality.
- **Domain 07 ↔ Domain 09:** clear page language and semantic structure can support coherent meaning, while entity relationships and topical architecture remain Domain 09's responsibility.
- **Domain 07 ↔ Domain 10:** authored page elements must be delivered and exposed correctly. Domain 10 owns technical implementation, rendering, crawl/index controls, and performance.
- **Domain 07 ↔ Domain 06:** source-page titles and descriptions may inform search-result presentation, but Domain 06 owns what search engines actually display.
- **Domain 07 → Domain 14:** implementation audits can define what changed; Domain 14 evaluates organic performance and business outcomes without assuming causation from a checklist alone.
- **Domain 11:** internal-link architecture and anchor-text practice remain separately owned and should be referenced rather than re-documented here.

## Research and Documentation Principles

- **Start with primary evidence.** For Google Search behavior, consult the relevant current Google Search Central documentation first. Use standards such as WHATWG HTML and W3C/WAI accessibility guidance for HTML semantics and alternative text; use primary documentation from other search engines when making claims about them.
- **Separate recommendation types.** Label search-engine requirements, documented recommendations, accessibility or usability rationale, common conventions, and practitioner hypotheses accurately.
- **Explain mechanisms and limits.** Describe why an element is useful, what it can communicate, and what it cannot guarantee.
- **Reject folklore.** Do not invent ideal character counts, keyword-density formulas, fixed heading rules, mandatory exact-match placement, or ranking boosts unsupported by evidence.
- **Use practical examples.** Include concise HTML examples, before/after comparisons, and realistic implementation mistakes when they clarify the topic. Label illustrative examples as such.
- **Avoid duplicate canonical explanations.** Link to Domains 02–06 and later domains for concepts they own instead of rebuilding those explanations inside Domain 07.
- **Keep volatile claims fresh.** Recheck current search-engine documentation when discussing title links, snippets, image handling, supported behavior, or other product-specific guidance.
- **Record uncertainty.** If a recommendation rests on limited evidence or practitioner convention, say so. Do not present it as a confirmed ranking factor.

## Development Status

**Domain architecture and topics 07.1–07.10 documented.**

Each topic document maintains its own references. Review scope, source-verification findings, and limitations are tracked centrally in k41-core rather than duplicated in this public index.

| Topic | Status |
|---|---|
| [07.1 — Introduction to On-Page SEO](07.1-Introduction-to-On-Page-SEO.md) | Documented |
| [07.2 — Page-Level Relevance & Optimization Principles](07.2-Page-Level-Relevance-and-Optimization-Principles.md) | Documented |
| [07.3 — Title Tags & Page Title Optimization](07.3-Title-Tags-and-Page-Title-Optimization.md) | Documented |
| [07.4 — Meta Descriptions & Snippet Optimization](07.4-Meta-Descriptions-and-Snippet-Optimization.md) | Documented |
| [07.5 — Heading Structure & Hierarchy Optimization](07.5-Heading-Structure-and-Hierarchy-Optimization.md) | Documented |
| [07.6 — URL Structure & Page-Level URL Optimization](07.6-URL-Structure-and-Page-Level-URL-Optimization.md) | Documented; English edition consolidated |
| [07.7 — Image SEO & Image Element Optimization](07.7-Image-SEO-and-Image-Element-Optimization.md) | Documented; English edition consolidated; structural checks completed; translation-fidelity review pending |
| [07.8 — HTML Semantics & Page Element Optimization](07.8-HTML-Semantics-and-Page-Element-Optimization.md) | Documented; English edition consolidated; structural checks completed; translation-fidelity review pending |
| [07.9 — On-Page Optimization Workflow & Implementation](07.9-On-Page-Optimization-Workflow-and-Implementation.md) | Documented; English edition consolidated; structural checks completed; translation-fidelity review pending |
| [07.10 — On-Page SEO Auditing & Quality Assessment](07.10-On-Page-SEO-Auditing-and-Quality-Assessment.md) | Documented; English edition consolidated; structural checks completed; translation-fidelity review pending |

The roadmap defines the intended scope and ownership of each topic. Only topics explicitly marked documented have completed topic-level documentation.

## Related Domains

- [Domain 05 — Keyword & Search Intent](../05-Keyword-and-Search-Intent/README.md)
- [Domain 06 — SERP & Search Features](../06-SERP-and-Search-Features/README.md)
- [Domain 08 — Content SEO](../08-Content-SEO/README.md)
- [Domain 09 — Semantic SEO](../09-Semantic-SEO/README.md)
- Domain 10 — Technical SEO (planned)
- Domain 11 — Internal Linking (planned)
- Domain 14 — SEO Analytics (planned)

## References

This file is a domain navigation and scope document. It establishes the approved roadmap and canonical ownership boundaries; it does not make substantive claims about search-engine behavior. Topic-level factual claims must be researched and cited in the corresponding topic documents, under the repository-wide governance maintained in k41-core.
