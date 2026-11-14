# AGENTS.md — SEO-Playbook Knowledge & Editorial Governance

> This file defines the research, source, architecture, and writing rules for contributors and AI agents working in this repository. Follow it before researching, drafting, editing, or reviewing any SEO-Playbook content.

## 1. Mission and Scope

SEO-Playbook is an **encyclopedic SEO Knowledge Base**. Its purpose is to document SEO concepts, systems, mechanisms, evidence, research, limitations, and developments from foundational to advanced levels.

The knowledge base is organized into the following 17 fixed top-level domains:

| No. | Knowledge Domain | Research scope |
|---:|---|---|
| 01 | SEO Fundamentals | Definitions, principles, history, terminology, purpose, and evolution of SEO. |
| 02 | Search Engine Fundamentals | Search discovery, crawling, rendering, indexing, serving, and search infrastructure. |
| 03 | Search Engine Algorithms | Ranking systems, documented updates, spam detection, policy enforcement, and system changes. |
| 04 | Information Retrieval | Queries, relevance, ranking, retrieval models, language understanding, and evaluation concepts. |
| 05 | Keyword & Search Intent | Search queries, query interpretation, intent classification, demand research, and query patterns. |
| 06 | SERP & Search Features | Search result presentation, result features, snippets, images, video, news, Discover, and other search surfaces. |
| 07 | On-Page SEO | Page-level content and markup, titles, headings, metadata, links, images, and page clarity. |
| 08 | Content SEO | Content usefulness, quality, originality, coverage, publishing, maintenance, and content systems. |
| 09 | Semantic SEO | Entities, concepts, relationships, structured data, language understanding, and knowledge representation. |
| 10 | Technical SEO | Site architecture, rendering, crawlability, indexability, performance, accessibility to crawlers, and technical diagnostics. |
| 11 | Internal Linking | Link discovery, site navigation, information architecture, anchor text, and internal link relationships. |
| 12 | Off-Page SEO | External links, reputation, references, digital PR, citations, and off-site signals. |
| 13 | International & Local SEO | Language and regional targeting, local search, business profiles, and location-specific search experiences. |
| 14 | SEO Analytics | Search measurement, Search Console, analytics, experimentation, reporting, attribution, and interpretation. |
| 15 | Advanced SEO | Large-scale SEO, automation, advanced architectures, complex diagnostics, and specialist methods. |
| 16 | AI & Search Evolution | AI in search, generative search experiences, AI Overviews, query expansion, and evolving discovery behavior. |
| 17 | **k41-version — SEO Hacks, Tricks & Experimental Strategies** | Unconventional methods, practical experiments, automation ideas, competitive intelligence, growth experiments, and original k41 investigations. |

Do not silently rename, merge, remove, reorder, or add top-level domains. Propose structural changes for explicit human approval first. Subtopics may be developed beneath the agreed domains without changing this top-level architecture.

## 2. Google-First Evidence Policy

### 2.1 Primary rule

For claims about **Google Search, Google ranking and serving systems, Google crawling and indexing, Google search policies, Google-owned search products, or Google measurement tools**, use current official Google sources as the first authority.

Use the most directly relevant primary source available:
1. Current official Google documentation or policy.
2. Official Google product help center or product documentation.
3. Official Google announcements, Search Central Blog, product blog, or status dashboard.
4. Official Google videos, presentations, and statements by Google representatives.
5. Official Google research papers, patents, or technical publications, where relevant and correctly interpreted.

Third-party sources may provide context, independent testing, critique, or corroboration. They must not override an applicable current official Google policy or be presented as Google's own position.

### 2.2 Important distinction

Google's public documentation does **not** disclose every ranking signal, system implementation, weighting, or internal decision. Never infer that an undocumented factor is a confirmed Google ranking factor. Clearly distinguish:
- What Google explicitly documents.
- What Google representatives have publicly stated.
- What independent researchers have observed.
- What an experiment suggests.
- What remains unknown or hypothetical.

Google tools are not all ranking systems. A metric, diagnostic, report, or recommendation in a Google product must not automatically be described as a ranking factor.

## 3. Official Google Reference Registry

The following registry is the approved starting catalogue of official Google-owned or Google-published sources relevant to the 17 domains. Use the canonical official URLs below. A reference being listed does not mean every metric or feature in that product is a direct organic ranking factor.

### A. Core Google Search documentation and policy

| Official source | Canonical reference | Primary use |
|---|---|---|
| Google Search Central | https://developers.google.com/search | Main official SEO documentation hub. |
| Google Search documentation | https://developers.google.com/search/docs | Search crawling, indexing, ranking, appearance, and site guidance. |
| Google Search Essentials | https://developers.google.com/search/docs/essentials | Technical requirements, spam policies, and key best practices. |
| SEO Starter Guide | https://developers.google.com/search/docs/fundamentals/seo-starter-guide | Foundational SEO guidance. |
| How Google Search Works | https://developers.google.com/search/docs/fundamentals/how-search-works | Discovery, crawling, indexing, and serving. |
| Crawling and indexing documentation | https://developers.google.com/search/docs/crawling-indexing | Crawlers, robots.txt, sitemaps, canonicalization, rendering, and indexing controls. |
| Ranking and search appearance documentation | https://developers.google.com/search/docs/appearance | Ranking systems and search result appearance. |
| Ranking systems guide | https://developers.google.com/search/docs/appearance/ranking-systems-guide | Google's publicly described ranking systems. |
| Spam policies | https://developers.google.com/search/docs/essentials/spam-policies | Prohibited practices and abuse policies. |
| Search Central Blog | https://developers.google.com/search/blog | Official announcements, explanations, and documentation updates. |
| Search Central What's New | https://developers.google.com/search/updates | Changes to Search Central documentation and guidance. |
| Search Central case studies | https://developers.google.com/search/case-studies | Google-published examples; treat case studies as contextual evidence, not universal causal proof. |
| Search Central help and support | https://developers.google.com/search/help | Official support routes and resources. |
| Google Search Status Dashboard | https://status.search.google.com/ | Search system incidents and status history. |
| Google Search How Search Works (public explainer) | https://www.google.com/search/howsearchworks/ | Public-facing explanation of Search. |

### B. Search Console, indexing diagnostics, and webmaster tools

| Official source | Canonical reference | Primary use |
|---|---|---|
| Google Search Console | https://search.google.com/search-console/about | Search performance and site diagnostics. |
| Search Console Help Center | https://support.google.com/webmasters/ | Help documentation for Search Console reports and tools. |
| Search Console API | https://developers.google.com/webmaster-tools | Programmatic access to supported Search Console data. |
| URL Inspection documentation | https://support.google.com/webmasters/answer/9012289 | Inspect Google's indexed URL information and live test results. |
| Rich Results Test | https://search.google.com/test/rich-results | Test supported rich result structured data eligibility. |
| Google-supported structured data documentation | https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data | Search-specific structured data guidance. |
| Change of Address tool guidance | https://support.google.com/webmasters/answer/9370220 | Site move support where applicable. |

### C. Search surfaces and content formats

| Official source | Canonical reference | Primary use |
|---|---|---|
| Google Images SEO documentation | https://developers.google.com/search/docs/appearance/google-images | Image discovery and appearance in Google Images. |
| Video SEO documentation | https://developers.google.com/search/docs/appearance/video | Video indexing and search appearance. |
| Google News documentation | https://support.google.com/news/publisher-center/ | Publisher and Google News product guidance; verify current product scope. |
| Google Discover documentation | https://developers.google.com/search/docs/appearance/google-discover | Discover eligibility and content guidance. |
| Google Search gallery | https://developers.google.com/search/docs/appearance/structured-data/search-gallery | Search appearance features and supported structured data types. |
| Google Search documentation for ecommerce | https://developers.google.com/search/docs/specialty/ecommerce | Ecommerce-specific Search guidance. |
| Google Search documentation for international and multilingual sites | https://developers.google.com/search/docs/specialty/international | International and multilingual Search guidance. |
| Google Search documentation for JavaScript | https://developers.google.com/search/docs/crawling-indexing/javascript/javascript-seo-basics | JavaScript rendering and SEO. |

### D. Google measurement, performance, and web developer resources

| Official source | Canonical reference | Primary use |
|---|---|---|
| Google Analytics | https://analytics.google.com/ | Website and app usage measurement. |
| Google Analytics Help | https://support.google.com/analytics/ | GA4 configuration, reports, and interpretation. |
| Google Analytics developer documentation | https://developers.google.com/analytics | APIs, measurement, and implementation. |
| PageSpeed Insights | https://pagespeed.web.dev/ | Page performance diagnostics and field/lab data where available. |
| PageSpeed Insights documentation | https://developers.google.com/speed/docs/insights/v5/about | PSI API and metric interpretation. |
| Lighthouse | https://developer.chrome.com/docs/lighthouse/overview/ | Automated quality audits; audit scores are not themselves Google Search ranking factors. |
| Chrome for Developers | https://developer.chrome.com/ | Browser platform, performance, and developer documentation. |
| Chrome UX Report (CrUX) | https://developer.chrome.com/docs/crux | Field data about real-world Chrome user experiences. |
| CrUX Dashboard | https://developer.chrome.com/docs/crux/dashboard | Explore CrUX data. |
| web.dev | https://web.dev/ | Web performance, user experience, and platform guidance. |
| Core Web Vitals | https://web.dev/articles/vitals | Definitions and guidance for user experience metrics. |
| Chrome DevTools | https://developer.chrome.com/docs/devtools | Browser debugging and performance investigation. |

### E. Google demand, audience, and advertising research tools

| Official source | Canonical reference | Primary use |
|---|---|---|
| Google Trends | https://trends.google.com/ | Relative search interest and trend exploration; not absolute search volume. |
| Google Trends Help | https://support.google.com/trends/ | Data interpretation and product use. |
| Google Ads | https://ads.google.com/ | Advertising platform; use carefully when studying paid search. |
| Google Ads Help | https://support.google.com/google-ads/ | Keyword Planner and advertising data documentation. |
| Keyword Planner | https://ads.google.com/home/tools/keyword-planner/ | Keyword discovery and advertising estimates; do not treat estimates as exact organic search volume. |
| Google Ads API | https://developers.google.com/google-ads/api | Programmatic advertising data and tools. |

### F. Local, merchant, and business discovery platforms

| Official source | Canonical reference | Primary use |
|---|---|---|
| Google Business Profile | https://www.google.com/business/ | Business presence on Google Search and Maps. |
| Business Profile Help | https://support.google.com/business/ | Profile eligibility, management, and local product guidance. |
| Business Profile APIs | https://developers.google.com/my-business | Supported business profile API capabilities; verify current API availability and naming. |
| Google Maps Platform | https://developers.google.com/maps | Maps APIs and location-related technical integrations. |
| Google Maps Help | https://support.google.com/maps/ | Maps product guidance. |
| Google Merchant Center | https://merchants.google.com/ | Product feeds and merchant presence across Google surfaces. |
| Merchant Center Help | https://support.google.com/merchants/ | Product data, policies, and merchant diagnostics. |
| Merchant API documentation | https://developers.google.com/merchant/api | Merchant Center programmatic integrations. |

### G. Video and creator ecosystem

| Official source | Canonical reference | Primary use |
|---|---|---|
| YouTube | https://www.youtube.com/ | Video search and discovery surface. |
| YouTube Help | https://support.google.com/youtube/ | Official platform and policy documentation. |
| YouTube Studio | https://studio.youtube.com/ | Creator channel and content analytics. |
| YouTube Analytics API | https://developers.google.com/youtube/analytics | Programmatic channel and video analytics. |
| YouTube Data API | https://developers.google.com/youtube/v3 | Video, channel, and playlist data. |
| YouTube Creator Academy / Creators | https://www.youtube.com/creators/ | Official creator education and platform guidance. |

### H. Google AI, research, patents, and technical publications

| Official source | Canonical reference | Primary use |
|---|---|---|
| Google Research | https://research.google/ | Research publications and technical work. |
| Google Research publications | https://research.google/pubs/ | Search, language, retrieval, machine learning, and related research. |
| Google AI | https://ai.google/ | Google's AI research and product information. |
| Google DeepMind | https://deepmind.google/ | AI research relevant to the evolution of search and language systems. |
| Google Patents | https://patents.google.com/ | Public patent documents; a patent is not proof that a technique is deployed in Search. |
| Google Developers | https://developers.google.com/ | Official developer documentation across Google products. |
| Google Cloud | https://cloud.google.com/ | Cloud infrastructure and data tooling where relevant to SEO analysis. |
| BigQuery | https://cloud.google.com/bigquery | Large-scale data analysis and supported public datasets. |
| Google Cloud documentation | https://cloud.google.com/docs | Technical documentation for Google Cloud services. |

### I. Official Google communication and learning channels

| Official source | Canonical reference | Primary use |
|---|---|---|
| Google Search Central YouTube | https://www.youtube.com/@GoogleSearchCentral | Official Search guidance, talks, and office hours. |
| Google for Developers YouTube | https://www.youtube.com/@GoogleDevelopers | Official developer and product technical content. |
| Google Search Central community | https://support.google.com/webmasters/community | Product Expert and community discussions; community posts are not equivalent to official policy. |
| Google News Initiative | https://newsinitiative.withgoogle.com/ | Publisher and news ecosystem education; use only when relevant. |

### Registry maintenance and source limitations

- This is the **SEO-relevant Google source registry**, not a claim that it lists every Google-owned website, app, API, service, or internal platform. Google has a very large and changing product portfolio; an exhaustive list of all Google platforms is neither practical nor necessary for a reliable SEO knowledge base.
- Keep the registry scoped to sources that materially support one or more of the 17 knowledge domains.
- Verify links, product names, API status, and documentation scope before relying on them. Google may retire, rename, consolidate, or redirect products and documentation.
- If an official URL is redirected, discontinued, or unavailable, record the date checked and replace it only with a verified official successor.
- Do not cite a Google product merely because it is owned by Google; establish its relevance to the claim.
- For sources that are official but community-authored or user-generated, label their authority level accurately.

## 4. Source Hierarchy and Citation Rules

Assign evidence levels in every substantial research document:

- **P1 — Official primary:** Current Google documentation, policies, product help, official announcements, official datasets, or official technical papers.
- **P2 — Primary technical/research:** Original peer-reviewed research, technical papers, patents, standards, or reproducible first-party experiments.
- **P3 — Independent corroboration:** Credible independent studies, industry experiments, and specialist analysis.
- **P4 — Practitioner observation:** Case studies, field observations, and community reports with disclosed methods.
- **P5 — Hypothesis/opinion:** Reasoned but unverified interpretation.

Citation requirements:
1. Cite material claims close to the claim, not only in a bibliography.
2. Prefer the exact page supporting the statement over a broad homepage.
3. Record page title, publisher, URL, publication/update date if available, and access/verification date for research notes.
4. Separate a source's explicit statement from our interpretation of it.
5. For time-sensitive claims, verify the latest available official documentation and status before publication.
6. If sources conflict, describe the conflict, compare dates and scope, and prioritize the current source most directly responsible for the product or policy.
7. Never fabricate citations, quotes, dates, test results, or source contents.

## 5. Research and Writing Workflow

For every topic:
1. Identify its primary knowledge domain and related domains.
2. Define the question and scope before researching.
3. Search the official Google source registry for current primary material.
4. Collect and cite relevant official documentation.
5. Add independent research only where it adds useful evidence, critique, or context.
6. Separate documented facts, observations, interpretations, hypotheses, and unknowns.
7. Explain mechanisms only to the level supported by evidence.
8. Record limitations, edge cases, policy implications, and competing explanations.
9. Connect the topic to related knowledge-base entries.
10. Review the document for accuracy, clarity, source quality, and currency.

Do not pad entries with generic advice. Do not turn a list of tips into a knowledge article without explaining the underlying concepts and evidence.

## 6. k41-core Writing Style

All SEO-Playbook content must use **k41-core** as its editorial style.

For this repository, k41-core is defined operationally by the following rules:

### Voice and tone
- Direct, precise, analytical, technically literate, and evidence-led.
- Confident where evidence is strong; explicit about uncertainty where it is not.
- Professional and natural, without hype, sales language, exaggerated claims, or motivational filler.
- Critical rather than agreeable: challenge weak assumptions and correct factual errors.

### Structure
- Use descriptive titles and a clear heading hierarchy.
- Start with the central definition, finding, or answer.
- Progress logically from fundamentals to mechanisms, implications, and limitations.
- Use tables when they improve comparison or classification; do not use them decoratively.
- Use concise paragraphs, meaningful lists, and consistent terminology.
- Explain specialist terms when first introduced.

### Reasoning and evidence
- Distinguish **Fact**, **Google-documented statement**, **Observation**, **Interpretation**, **Hypothesis**, and **Unknown** when the distinction matters.
- Explain why a conclusion follows from the evidence.
- Identify assumptions, confounders, limitations, and alternative explanations.
- Never present correlation as causation.
- Never claim that a tactic is a ranking factor without adequate evidence.
- Prefer precise language over absolute claims such as "always", "guaranteed", or "the secret".

### Language
- Use clear, professional Indonesian as the default language.
- Retain established English SEO and technical terms when translating them would reduce precision; define them on first use when needed.
- Keep official product names, API names, metrics, and Google terminology accurate.
- Avoid unnecessary jargon, repeated explanations, empty transitions, and keyword stuffing.

### Formatting conventions
- Use Markdown.
- Use sentence case for headings.
- Use numbered steps for ordered processes and bullets for unordered points.
- Use code formatting for commands, file paths, API fields, and literal technical values.
- Use citations and a References section for research-based documents.
- Include a concise status or last-verified date when information is likely to change.

### k41-core quality test
Before accepting a document, verify:
- Is the main point clear and technically accurate?
- Are claims supported by appropriately authoritative evidence?
- Are facts separated from interpretations and hypotheses?
- Are mechanisms explained without inventing undisclosed details?
- Are limitations and risks acknowledged?
- Is the writing concise without sacrificing necessary depth?
- Does the document connect to the wider knowledge architecture?

## 7. Special Rules for Domain 17 — k41-version

Domain 17 is a research and experimentation domain, not a license to recommend deceptive or policy-violating tactics.

Document each technique with:
- Technique name and version/date.
- Problem or opportunity addressed.
- Concept and proposed mechanism.
- Preconditions and implementation details.
- Test design, controls, sample, and observation period where applicable.
- Expected and observed outcomes, kept separate.
- Evidence and reproducibility notes.
- Risks, limitations, and Google policy implications.
- Conclusion and next experiment.

Use these maturity labels:
- **Verified:** Supported by sufficiently strong evidence for the stated scope.
- **Tested:** Tested under documented conditions; not necessarily universally validated.
- **Experimental:** Being investigated; outcome remains uncertain.
- **Hypothesis:** Proposed explanation or tactic not yet adequately tested.
- **Unverified:** Insufficient evidence is available.
- **Deprecated:** No longer applicable or effective under the documented conditions.

Explicitly flag techniques that may violate Google Search spam policies. Do not disguise policy violations as "hacks", promise rankings, or imply that an experiment establishes a general ranking rule.

## 8. Repository Governance

- Treat this file as the working instruction source for all agents and contributors.
- Preserve the agreed 17-domain architecture.
- Use k41-core for all new and revised knowledge-base prose.
- Keep research notes and final knowledge articles distinguishable.
- Update source references when official documentation changes.
- Do not claim that a source registry is exhaustive of all Google products; maintain it as a relevant, verified catalogue.
- When a Google product or source is retired, annotate or replace it rather than silently deleting its history.
- When in doubt, report uncertainty and ask for human review rather than inventing a fact.

---

**Architecture status:** Established — 17 domains.  
**Editorial standard:** k41-core.  
**Primary evidence policy:** Current official Google sources first for Google Search and Google product claims.  
**Current development starting point:** Domain 01 — SEO Fundamentals.
