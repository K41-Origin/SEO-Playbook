# AGENTS.md

## SEO-Playbook

SEO-Playbook is an encyclopedic knowledge base dedicated to understanding, analyzing, and documenting search engine optimization.

Its purpose is to build, connect, evaluate, and maintain reliable knowledge across the SEO landscape from established fundamentals and technical principles to advanced search systems, emerging developments, and experimental approaches.

This repository is built for understanding, not blindly following instructions.

SEO is an evolving discipline. Search engines change, ranking systems develop, policies shift, and yesterday's assumptions can become today's misinformation. Every document must therefore prioritize evidence, explain underlying mechanisms, and acknowledge the boundaries of what is actually known.

No shortcuts disguised as expertise. No speculation presented as established knowledge.

## Project Identity and Architecture

The 17 top-level knowledge domains documented in `README.md` constitute the established architecture of SEO-Playbook.

This architecture is intentional and must be preserved unless the project owner explicitly approves a structural change.

`README.md` serves as the public reference for the project's identity, purpose, architecture, scope, and documentation principles.

Do not introduce unnecessary domains, reorganize existing structures, or create parallel documentation simply because an alternative arrangement seems more convenient.

Consistency matters. Structural changes must have a legitimate reason.

## k41 Identity and Editorial Voice

The universal identity of k41 is defined in [k41-core](https://github.com/K41-Origin/k41-core).

SEO-Playbook must inherit this identity while developing an editorial voice appropriate for its subject.

SEO-Playbook is not a repository for provocative opinions disguised as research. Sarcasm, satire, and humor may appear when appropriate, but they must never interfere with technical explanations or misrepresent the underlying evidence.

The objective is simple: maintain k41's personality without sacrificing intellectual credibility.

## Mandatory Official Reference Sources

For research concerning Google Search, **Google's official documentation is the primary reference baseline**. Researchers and contributors must consult the relevant official sources before relying on third-party SEO articles, social posts, newsletters, forum discussions, or tool-vendor explanations.

The main entry point is [Google Search Central](https://developers.google.com/search). The broader [Google for Developers](https://developers.google.com/) portal is also an official Google source, but it is a general developer portal—not a substitute for the Search Central documentation when the subject is Google Search.

### Required Google Search reference library

Use the sources relevant to the topic being documented. Do not cite a hub page as if it directly supports a detailed claim when a more specific source exists.

| Priority / Subject | Official reference | When to use it |
|---|---|---|
| Main Search documentation | [Google Search Central](https://developers.google.com/search) | Starting point and navigation to Google's Search documentation. |
| Search eligibility and essentials | [Google Search Essentials](https://developers.google.com/search/docs/essentials) | Technical requirements, key best practices, and spam-policy baseline. |
| How Search works | [In-depth guide to how Google Search works](https://developers.google.com/search/docs/fundamentals/how-search-works) | Crawling, indexing, serving, and the high-level Search pipeline. |
| SEO fundamentals | [SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) | Foundational SEO concepts and practices. |
| Ranking systems | [A guide to Google Search ranking systems](https://developers.google.com/search/docs/appearance/ranking-systems-guide) | Official descriptions of Google's ranking systems. |
| Spam and manipulation | [Spam policies for Google web search](https://developers.google.com/search/docs/essentials/spam-policies) | Spam definitions, prohibited practices, and policy risk assessment. |
| Helpful content | [Creating helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content) | Content quality, people-first principles, and self-assessment. |
| Crawling and indexing | [Crawling and indexing documentation](https://developers.google.com/search/docs/crawling-indexing) | Discovery, crawling, indexing, robots directives, sitemaps, and related technical behavior. |
| JavaScript SEO | [JavaScript SEO basics](https://developers.google.com/search/docs/crawling-indexing/javascript/javascript-seo-basics) | Rendering, JavaScript content, and crawl/index considerations. |
| Robots directives | [Introduction to robots.txt](https://developers.google.com/search/docs/crawling-indexing/robots/intro) | Robots.txt behavior and crawler access controls. |
| Sitemaps | [Learn about sitemaps](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview) | Sitemap discovery, submission, and limitations. |
| URL inspection | [URL Inspection tool](https://support.google.com/webmasters/answer/9012289) | Inspecting Google's indexed version and testing live URLs in Search Console. |
| Structured data | [Introduction to structured data](https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data) | Structured data eligibility, implementation, and general requirements. |
| Search appearance | [Google Search appearance documentation](https://developers.google.com/search/docs/appearance) | Rich results, snippets, titles, images, and other search presentation features. |
| Page experience | [Understanding page experience in Google Search results](https://developers.google.com/search/docs/appearance/page-experience) | Google's documented page-experience guidance; do not turn it into unsupported ranking claims. |
| Core Web Vitals | [Web Vitals](https://web.dev/articles/vitals) and [Core Web Vitals report](https://support.google.com/webmasters/answer/9205520) | Metric definitions and Search Console reporting. Use the source that directly supports the claim. |
| Search performance data | [Search Console Performance report](https://support.google.com/webmasters/answer/7576553) | Impressions, clicks, CTR, position, query/page dimensions, and report limitations. |
| Search Console documentation | [Search Console Help](https://support.google.com/webmasters) | Product behavior, reports, tools, and troubleshooting. |
| Search Console API | [Search Console API](https://developers.google.com/webmaster-tools) | Programmatic access, API behavior, and technical implementation. |
| Official announcements | [Google Search Central Blog](https://developers.google.com/search/blog) | Search announcements, official explanations, and product or policy updates. |
| Documentation change log | [Google Search documentation updates](https://developers.google.com/search/updates) | Changes to Search Central documentation; check this when a claim may have changed. |
| Ranking update history | [Google ranking updates](https://status.search.google.com/products/rGHU1u87FJnkP6W2 GwMi/history) | Officially announced ranking updates and their timelines. |
| Search system incidents | [Google Search Status Dashboard](https://status.search.google.com/) | Confirming reported Search incidents and status events. |

### Rules for using official references

1. **Consult first, not exclusively.** Start with the relevant Google primary documentation for Google Search claims. Then use independent research, standards, patents, reproducible experiments, and practitioner evidence to investigate context, mechanisms, gaps, or claims Google does not document.
2. **Use the narrowest relevant source.** Prefer a specific policy, technical guide, API reference, or product help page over a broad portal or blog summary.
3. **Read the source, not just its search snippet.** Verify the page's actual wording, scope, date, and linked qualifications before citing it.
4. **Attribute precisely.** Say "Google documents/states/recommends" only when the source explicitly supports that wording. Do not imply that Google's documentation confirms a claim it does not discuss.
5. **Do not confuse documentation with a complete disclosure.** Google's public documentation is authoritative for Google's published guidance and policies, but it does not reveal every ranking signal, weight, implementation detail, or internal system behavior.
6. **Do not treat recommendations as ranking guarantees.** Eligibility requirements, best practices, diagnostics, and ranking factors are different things. Preserve those distinctions.
7. **Check freshness.** For volatile topics—ranking systems, spam policies, structured data features, Search Console reports, APIs, crawling behavior, and product availability—check the current documentation, the Search Central updates page, and relevant official announcements. Record the access date when it matters.
8. **Resolve apparent conflicts.** Check publication dates, page scope, newer documentation, and official clarifications. Prefer the currently maintained, topic-specific source; explain unresolved conflicts instead of silently choosing one.
9. **Use Google sources only within their remit.** A Google Developers page is a primary source for the Google product or API it documents. It is not automatically authoritative for general SEO, other search engines, or independent claims about ranking behavior.
10. **Keep independent corroboration.** Official guidance establishes what Google publicly says. It does not replace empirical testing or independent research when evaluating real-world outcomes.

### Source priority by claim type

- **Google Search behavior, policies, eligibility, and Search features:** Google Search Central documentation and official Google Search announcements first.
- **Search Console tools, reports, and APIs:** Search Console Help and the official Search Console API documentation first.
- **Google web platform or developer product behavior:** The relevant official Google Developers product documentation first.
- **Web standards and interoperable specifications:** The responsible standards organization or specification (for example, WHATWG, W3C, IETF, or Schema.org) first; Google documentation may explain Google's implementation or supported subset.
- **General search theory and information retrieval:** Original academic research, textbooks, technical papers, and relevant standards; do not force Google documentation to answer questions outside its scope.
- **Claims about other search engines:** The relevant search engine's own primary documentation first, followed by independent corroboration.

The official source registry is a starting set, not a frozen whitelist. Add or replace links when Google reorganizes documentation. Verify links before relying on them; never preserve a stale URL merely because it appears in this file.

## Documentation Workflow

Before creating a new topic or materially revising an existing document, follow this workflow:

1. **Determine its position.** Identify the correct knowledge domain and establish its relationship with existing documentation.
2. **Define the scope.** Clearly establish the question being investigated, its boundaries, and the terminology involved.
3. **Research the evidence.** Prioritize authoritative, primary, and technically relevant sources. Do not rely on repeated claims as a substitute for independent evidence.
4. **Evaluate the findings.** Separate established facts, documented observations, interpretations, hypotheses, and unresolved questions.
5. **Explain the mechanisms.** Describe how something works, why it matters, and under what conditions the explanation applies.
6. **Identify limitations.** Document uncertainties, exceptions, risks, and relevant search engine policies.
7. **Establish connections.** Add references and cross-links to related topics where they provide genuine informational value.
8. **Review the documentation.** Verify technical accuracy, logical consistency, readability, structural quality, and alignment with the k41 identity.

Adapt the documentation structure to the subject.

Do not force irrelevant sections into a document merely to make it look comprehensive. Structure should serve understanding, not the other way around.

## Repository Governance

The following rules govern the maintenance and development of SEO-Playbook:

- **Preserve the architecture.** Maintain the 17 knowledge domains established in `README.md`.
- **Avoid duplication.** Improve existing documentation or establish cross-references before creating another page covering substantially the same subject.
- **Maintain clear naming.** Use descriptive filenames and headings that accurately represent their contents.
- **Preserve traceability.** Ensure factual claims can be traced to supporting sources. Clearly identify interpretations and hypotheses.
- **Respect evidence boundaries.** Experimental observations must never be silently promoted into universal SEO principles.
- **Maintain relevance.** Review and update outdated documentation when search systems, technical standards, available evidence, or policies change.
- **Control structural changes.** Keep modifications focused and explain meaningful architectural changes.
- **Be honest about research depth.** Never describe a topic as comprehensively researched when its evidence, scope, or coverage remains incomplete.

Documentation quality is not measured by page count, word count, or how authoritative a document sounds.

It is measured by the accuracy of its explanations, the strength of its supporting evidence, the usefulness of its connections, and its ability to distinguish what is known from what is merely assumed.

## Final Principle

SEO-Playbook exists to build a body of knowledge that can withstand scrutiny.

It should be technically credible without becoming unnecessarily academic, critical without becoming cynical for the sake of it, and confident without pretending to know everything.

The goal is not to produce another generic SEO encyclopedia filled with recycled industry advice.

The goal is to build a knowledge base that understands how SEO works, questions what others take for granted, documents what evidence actually supports, and remains honest about what it does not know.

**Understand the system. Question the assumptions. Follow the evidence.**
