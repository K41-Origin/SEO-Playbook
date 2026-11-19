# Domain 09 — Semantic SEO

## Domain Purpose

Domain 09 documents how SEO practitioners identify, describe, connect, and organize entities and concepts into a coherent model of knowledge that can inform website information architecture.

Its canonical focus is **semantic knowledge modeling for websites**: entity understanding, attributes and identity, semantic relationships, knowledge representation, topical models, topical coverage, and semantic information architecture.

Semantic SEO is not a bag of entity keywords, a checklist of related terms, or a promise that adding structured data will improve rankings. The work is to represent subject matter accurately, make conceptual relationships explicit where useful, and organize information around genuine meaning and user needs. Search-engine interpretation and ranking outcomes must be treated as separate questions requiring their own evidence.

## Scope and Ownership

### What Domain 09 owns

- Semantic SEO as a discipline and its conceptual boundaries.
- Entity concepts, entity identification, and entity modeling for SEO contexts.
- Entity attributes, identity, ambiguity, and disambiguation at the knowledge-model level.
- Semantic relationships between entities and concepts, including relationship types and constraints.
- Ontologies, taxonomies, controlled vocabularies, and conceptual classification when used to organize website knowledge.
- Knowledge graphs and graph-based knowledge representation as conceptual models.
- Topical modeling and the organization of knowledge domains.
- Topical coverage and the evaluation of whether a knowledge model represents the relevant subject matter adequately.
- Semantic information architecture for websites, including the relationship between knowledge models and page/content structures.
- Validation, maintenance, and governance of semantic models and website-level semantic architecture.

### What Domain 09 does not own

| Related domain | Canonical ownership | Boundary with Domain 09 |
|---|---|---|
| [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md) | Search-engine architecture, crawling, indexing, query processing, retrieval, and serving | Domain 02 owns the search pipeline. Domain 09 does not claim to document how a particular engine internally extracts or stores every entity. |
| [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md) | Ranking systems, relevance, ranking signals, quality systems, and ranking evaluation | Domain 03 owns ranking mechanisms and documented search-quality systems. A semantic model or entity relationship must not be presented as a confirmed ranking factor without direct evidence. |
| [04 — Information Retrieval](../04-Information-Retrieval/README.md) | Information representation, retrieval models, semantic/neural retrieval, and formal IR evaluation | Domain 04 owns retrieval theory and system-side representations such as embeddings and dense retrieval. Domain 09 uses semantic concepts to model website knowledge; it does not re-teach retrieval algorithms, entity-linking algorithms, or IR evaluation. |
| [05 — Keyword & Search Intent](../05-Keyword-and-Search-Intent/README.md) | Audience-language discovery, keyword research, intent inference, query clustering, prioritization, and keyword-to-page research mapping | Domain 05 groups queries for research and targeting. Domain 09 models entities, concepts, and their relationships. A keyword cluster is not automatically a topic model or knowledge graph. |
| [06 — SERP & Search Features](../06-SERP-and-Search-Features/README.md) | SERP presentation, Knowledge Panels, rich results, and entity-oriented search features | Domain 06 owns the visible search feature and its documented behavior. Domain 09 owns knowledge modeling concepts, not the mechanics, eligibility, or appearance of a Knowledge Panel or rich result. |
| [07 — On-Page SEO](../07-On-Page-SEO/README.md) | Page-level elements, HTML structure, and on-page implementation | Domain 07 owns HTML semantics and page-element implementation. Semantic relationships between concepts are not the same thing as semantic HTML markup. |
| [08 — Content SEO](../08-Content-SEO/README.md) | Content strategy, editorial planning, briefs, production, review, optimization, maintenance, and editorial auditing | Domain 09 can provide entity and topical models as inputs. Domain 08 owns editorial decisions and content production workflows. |
| Domain 10 — Technical SEO (planned) | Technical delivery and implementation, including structured data implementation | Domain 09 defines the knowledge and meaning a model is intended to represent. Domain 10 owns technical implementation, validation, and delivery of structured data. |
| Domain 11 — Internal Linking (planned) | Internal-link architecture, strategy, anchor text, and implementation | Domain 09 may identify meaningful conceptual relationships. Domain 11 decides whether and how those relationships should become internal links. A semantic relationship does not automatically require a hyperlink. |
| Domain 14 — SEO Analytics (planned) | Organic performance measurement, analysis, and reporting | Domain 14 owns performance measurement. Domain 09 may define model-quality checks, but does not own analytics methodology or claim that semantic changes caused ranking changes. |
| Domain 17 — k41-version (experimental) | SEO experiments, unconventional strategies, and original k41 investigations | Domain 09 owns canonical semantic concepts and evidence standards. Experimental entity or topical tactics belong in Domain 17 until their claims are sufficiently validated. |

Planned domain paths above describe ownership boundaries only. They are not working navigation destinations until the corresponding files exist.

### Canonical boundary rules

1. **Entities are not keywords.** A query or phrase can refer to an entity, but lexical expressions and the things they denote are different modeling layers.
2. **Keyword clusters are not knowledge models.** Domain 05 groups search queries for research decisions; Domain 09 models concepts, entities, attributes, and relationships.
3. **Semantic SEO is not Information Retrieval.** Domain 04 explains system-side representation and retrieval methods; Domain 09 explains website-side knowledge modeling and information organization.
4. **A knowledge graph is not a ranking-factor disclosure.** A graph can be a useful representation of relationships. Its existence does not prove that a search engine uses that exact graph or rewards a site for publishing one.
5. **Topical coverage is not article count.** Coverage concerns the relevant concepts, relationships, and information needs represented—not the volume of URLs or repeated keyword variants.
6. **Semantic architecture is not internal linking.** Conceptual relationships inform architecture; Domain 11 owns hyperlink strategy and implementation.
7. **Semantic meaning is not HTML semantics.** Domain 07 owns markup and page-level HTML structure; Domain 09 owns the conceptual model represented by the information.
8. **Structured data is an implementation mechanism, not the whole discipline.** Domain 09 defines the model and meaning; Domain 10 owns technical structured-data implementation, while Domain 06 owns search appearance.
9. **Do not promise ranking outcomes.** Claims about entity recognition, topical authority, semantic signals, or ranking effects require claim-specific evidence. Industry repetition is not proof.
10. **Model only defensible relationships.** Distinguish sourced facts, accepted definitions, editorial classifications, inferred relationships, and hypotheses. Do not turn convenient associations into factual relationships.

## Domain Structure

The roadmap is organized into four groups. The sequence moves from modeling entities, to describing relationships and knowledge structures, to building topical models, and finally applying and governing semantic architecture for websites.

### Group A — Semantic SEO & Entity Foundations

| Topic | Title | Canonical scope |
|---|---|---|
| 09.1 | Introduction to Semantic SEO | Defines semantic SEO, its purpose, terminology, workflow, outputs, evidence boundaries, and relationship to the wider SEO discipline. Establishes what semantic SEO is—and what it is not. |
| 09.2 | Entity Fundamentals & Entity Identification | Explains entities as identifiable things or concepts in a knowledge model; covers entity categories, candidate identification, naming, and the difference between a real-world referent and the words used to describe it. |
| 09.3 | Entity Attributes, Identity & Disambiguation | Covers attributes, identifiers, aliases, entity boundaries, ambiguity, and disambiguation decisions. Focuses on defensible knowledge modeling, not search-engine entity extraction algorithms. |

### Group B — Semantic Relationships & Knowledge Representation

| Topic | Title | Canonical scope |
|---|---|---|
| 09.4 | Semantic Relationships & Relationship Modeling | Defines relationships between entities and concepts, relationship direction and types, constraints, context, provenance, and the difference between explicit facts and inferred associations. |
| 09.5 | Ontologies, Taxonomies & Controlled Vocabularies | Compares conceptual schemas, hierarchical classification, and controlled terms; explains when each model is useful and how to choose a suitable level of formality for website knowledge. |
| 09.6 | Knowledge Graphs & Knowledge Representation | Explains graph-based representation, nodes, edges, properties, triples, graph scope, and practical knowledge-model patterns. Does not duplicate retrieval algorithms or claim that a website graph mirrors a search engine's private knowledge graph. |

### Group C — Topical Modeling & Coverage

| Topic | Title | Canonical scope |
|---|---|---|
| 09.7 | Topical Modeling & Knowledge Domains | Organizes a subject into concepts, subdomains, dependencies, and meaningful boundaries. Distinguishes topical models from query clusters, editorial calendars, and URL inventories. |
| 09.8 | Topical Coverage & Semantic Completeness | Evaluates whether a topical model represents relevant concepts, relationships, attributes, and user-facing information needs. Covers omission, redundancy, scope control, and uncertainty without reducing completeness to word count or article count. |

### Group D — Semantic Information Architecture

| Topic | Title | Canonical scope |
|---|---|---|
| 09.9 | Semantic Information Architecture for Websites | Translates validated knowledge models into website-level information organization, page roles, conceptual grouping, and content-architecture decisions. Editorial execution remains in Domain 08; keyword-to-page research remains in Domain 05; internal-link strategy remains in Domain 11. |
| 09.10 | Semantic Architecture Validation & Governance | Defines quality checks, provenance, consistency, change control, model maintenance, and governance for semantic models and website information architecture. Does not replace Domain 08 editorial audits, Domain 10 technical audits, or Domain 14 performance analysis. |

## Domain Workflow

The topics form a connected workflow, not a mandatory one-way production recipe:

1. **Establish the subject and purpose** — define the scope of the knowledge model and the website problem it should solve.
2. **Identify entities and concepts** — record candidate entities, names, attributes, identity evidence, and ambiguity.
3. **Model relationships** — define meaningful relationships, their direction, context, constraints, and provenance.
4. **Choose a representation** — use an appropriate ontology, taxonomy, controlled vocabulary, graph, or a combination where justified.
5. **Build the topical model** — organize the relevant knowledge domain and identify its boundaries and dependencies.
6. **Assess coverage** — find meaningful omissions, unnecessary duplication, and unsupported associations.
7. **Translate into website architecture** — determine how knowledge should be represented and organized across pages and content structures.
8. **Validate and govern** — maintain consistency, evidence provenance, versioning, and review processes as the subject and website evolve.

The workflow can be iterative. New evidence, audience needs, or changes in the website may require revisiting earlier modeling decisions.

## Inputs and Outputs

### Typical inputs

- Subject-matter expertise and reliable reference sources.
- Existing website pages and content inventories.
- Audience and query research from Domain 05.
- Editorial goals, content constraints, and governance from Domain 08.
- Relevant technical and platform constraints from Domain 10.
- Existing information architecture and internal-link context from Domain 11.

### Typical outputs

- Entity and concept inventories with provenance.
- Entity attribute and disambiguation records.
- Relationship models with evidence and confidence notes.
- Ontologies, taxonomies, controlled vocabularies, or knowledge graphs where justified.
- Topical models and coverage assessments.
- Semantic information-architecture specifications.
- Validation criteria, change logs, and governance rules.

These are modeling and planning outputs. They do not automatically prescribe a new URL, a new article, structured data, or an internal link. Those decisions belong to the relevant downstream workflow.

## Research and Modeling Principles

- **Start with meaning, not keyword lists.** Search phrases can provide evidence, but they are not a substitute for understanding the subject.
- **Use the simplest adequate model.** Do not build an ontology or graph when a clear taxonomy or structured inventory is enough.
- **Record provenance.** Important entities, attributes, and relationships should be traceable to reliable sources or clearly labeled as editorial decisions.
- **Preserve uncertainty.** Ambiguous identity and inferred relationships must remain visible in the model.
- **Avoid forced completeness.** A model should cover what is relevant to its declared scope, not every remotely associated concept.
- **Separate facts from classifications.** An editorial taxonomy is a useful organizational choice; it is not automatically a universal or natural classification.
- **Do not confuse correlation with causation.** Semantic improvements may improve clarity and organization, but ranking impact requires separate evidence.
- **Do not worship graphs.** Graph structure is a representation choice, not proof of sophistication or SEO value.
- **Prefer maintainable architecture.** A semantic model that nobody can validate or maintain is documentation debt with extra steps.
- **Keep canonical explanations in one place.** Link to Domains 04–08 and future Domains 10–11 rather than copying their methods.

## Development Status

| Area | Status | Coverage |
|---|---|---|
| Domain architecture | Established | Purpose, ownership boundaries, four topic groups, ten-topic roadmap, workflow, inputs/outputs, and cross-domain dependencies are defined. |
| 09.1–09.10 | Planned | Topic scopes and sequence are defined; substantive topic documents have not yet been created. |
| Cross-domain integration | Architecture reviewed | Boundaries are mapped against existing Domains 02–08 and planned Domains 10, 11, 14, and 17. Topic-level reciprocal links and detailed source checks will be completed as each topic is documented. |
| Source audit | Pending | Substantive claims and topic documents will require claim-level source research and verification under AGENTS.md. |

## Related Domains

- [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md)
- [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md)
- [04 — Information Retrieval](../04-Information-Retrieval/README.md)
- [05 — Keyword & Search Intent](../05-Keyword-and-Search-Intent/README.md)
- [06 — SERP & Search Features](../06-SERP-and-Search-Features/README.md)
- [07 — On-Page SEO](../07-On-Page-SEO/README.md)
- [08 — Content SEO](../08-Content-SEO/README.md)

## References

This index defines the repository's editorial architecture and topic ownership. It does not establish search-engine ranking behavior. Substantive topic documents must cite the primary research, standards, and official documentation that support their individual claims.
