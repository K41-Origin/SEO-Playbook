# Domain 09 — Semantic SEO


## Language and Canonical Versions

English is the sole publication language for SEO-Playbook. Each topic has one canonical English document; parallel language editions are not maintained.

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
| [10 — Technical SEO](../10-Technical-SEO/README.md) | Technical delivery and implementation, including structured data implementation | Domain 09 defines the knowledge and meaning a model is intended to represent. Domain 10 owns technical implementation, validation, and delivery of structured data. |
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
| 09.2 | Entity Fundamentals & Entity Identification | Establishes what counts as an entity in a knowledge model; covers entity categories, candidate discovery, initial identification, naming, and the distinction between a referent and the expressions used to describe it. It does not resolve difficult identity collisions or teach search-engine entity extraction. |
| 09.3 | Entity Attributes, Identity & Disambiguation | Defines how an identified entity is described and distinguished: attributes, identifiers, aliases, entity boundaries, identity evidence, ambiguity resolution, and disambiguation decisions. It takes candidate entities from 09.2 and does not cover entity extraction/linking algorithms internal to search systems. |

### Group B — Semantic Relationships & Knowledge Representation

| Topic | Title | Canonical scope |
|---|---|---|
| 09.4 | Semantic Relationships & Relationship Modeling | Defines the meaning of relationships between entities and concepts: relationship types, direction, domain/range constraints, context, provenance, and the distinction between asserted facts and inferred associations. It owns relationship semantics, not graph storage formats or website navigation links. |
| 09.5 | Ontologies, Taxonomies & Controlled Vocabularies | Compares formal conceptual schemas, hierarchical classification systems, and controlled terms; covers their components, differences, selection, and governance as knowledge-modeling structures. It defines the schema or vocabulary, not individual relationship assertions (09.4) or graph serialization (09.6). |
| 09.6 | Knowledge Graphs & Knowledge Representation | Explains graph-based knowledge representation: nodes, edges, properties, triples, graph scope, schema-to-graph mapping, and practical modeling patterns. It explains how modeled knowledge can be represented as a graph, not how search engines retrieve/rank graph data or how to implement structured data technically. |

### Group C — Topical Modeling & Coverage

| Topic | Title | Canonical scope |
|---|---|---|
| 09.7 | Topical Modeling & Knowledge Domains | Organizes a subject as a conceptual knowledge domain: concepts, subdomains, dependencies, and scope boundaries. The output is an abstract model of the subject, not a keyword cluster, editorial calendar, content inventory, or page/URL architecture. |
| 09.8 | Topical Coverage & Semantic Completeness | Evaluates whether a defined topical model adequately represents relevant concepts, relationships, attributes, and information needs within its declared scope. Covers omissions, redundancy, relevance, and uncertainty at the knowledge-model level—not editorial quality audits of published assets or keyword-volume coverage. |

### Group D — Semantic Information Architecture

| Topic | Title | Canonical scope |
|---|---|---|
| 09.9 | [Semantic Information Architecture for Websites](09.9-Semantic-Information-Architecture-for-Websites.md) | Translates a validated topical/knowledge model into website-level information organization, conceptual groupings, page roles, and content-architecture specifications. It defines the intended information structure, not editorial production (08), keyword-to-page research mapping (05), page-level HTML implementation (07), technical delivery (10), or internal-link strategy (11). |
| 09.10 | [Semantic Model Validation, Maintenance & Governance](09.10-Semantic-Model-Validation-Maintenance-and-Governance.md) | Defines validation criteria for entity identity, relationship integrity, schema consistency, provenance, scope, and alignment between the knowledge model and its website architecture; covers versioning, change control, ownership, and maintenance of those semantic models. It does not own organization-wide content governance (08.2), editorial/content audits (08.10), technical implementation audits (10), internal-link audits (11), or organic performance measurement (14). |


## Audit findings and boundary decisions

| Potential collision | Audit decision |
|---|---|
| 09.2 Entity Identification vs 09.3 Identity & Disambiguation | Keep both. 09.2 identifies and names candidate entities; 09.3 resolves identity, attributes, aliases, ambiguity, and entity boundaries after identification. |
| 09.4 Relationship Modeling vs 09.5 Ontologies & Taxonomies | Keep both. 09.4 defines the meaning and evidence of individual relationship types/assertions; 09.5 defines the schema, classification system, and controlled vocabulary used to organize those concepts. |
| 09.4 Relationship Modeling vs 09.6 Knowledge Graphs | Keep both. 09.4 owns relationship semantics; 09.6 owns graph-based representation of modeled entities and relationships. |
| 09.7 Topical Modeling vs 09.8 Topical Coverage | Keep both. 09.7 builds the conceptual model and defines its scope; 09.8 evaluates the model's coverage and identifies omissions or unnecessary overlap within that scope. |
| 09.7/09.8 vs 09.9 Semantic Information Architecture | Keep separate. 09.7–09.8 model and assess the subject domain; 09.9 translates the validated model into website information organization and page-role specifications. |
| 09.8 Topical Coverage vs Domain 08 editorial audit | Keep separate. 09.8 evaluates conceptual coverage in the knowledge model; Domain 08 evaluates published content assets and editorial quality. |
| 09.9 Semantic Architecture vs Domain 11 Internal Linking | Keep separate. 09.9 defines conceptual grouping and information structure; Domain 11 decides and implements hyperlink relationships. |
| 09.10 Validation/Governance vs Domains 08, 10, 11, and 14 | Narrow 09.10 to semantic-model and semantic-architecture integrity. Editorial, technical, internal-link, and performance audits remain with their canonical domains. |
| Semantic SEO vs Domain 04 semantic retrieval | Keep separate. Domain 04 explains retrieval-system representations and algorithms; Domain 09 models website knowledge and its information organization. |

### Topic dependency and handoff sequence

`09.1` establishes terminology and scope. `09.2` identifies candidate entities; `09.3` resolves identity and attributes. `09.4` models relationship meaning, while `09.5` supplies suitable conceptual schemas and vocabularies; both inform `09.6` where graph representation is useful. `09.7` organizes the subject domain and `09.8` assesses its coverage. `09.9` translates the validated model into website information architecture. `09.10` validates and governs the model and its architectural representation over time.

This is a logical dependency map, not a rigid requirement that every project use every modeling technique. A taxonomy may be sufficient where an ontology or graph would add needless complexity.

### Audit conclusion

**PASS WITH SCOPE CLARIFICATIONS.** The ten-topic structure is coherent and can proceed to topic documentation. The review identified boundary risks but no need to add another topic or create a new domain. The scope refinements above are incorporated into the roadmap.

All ten topic documents are now written. Topic-level sources are cited in the corresponding documents; audit evidence and maintenance governance are maintained centrally in k41-core.

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
| 09.1 | Documented | Introduction to Semantic SEO defines the domain's working scope, terminology, workflow, evidence boundaries, and cross-domain handoffs. |
| 09.2 | Documented | Entity Fundamentals & Entity Identification defines entity concepts, candidate categories, discovery sources, first-pass identification, and the handoff to identity resolution. |
| 09.3 | Documented | Entity Attributes, Identity & Disambiguation defines entity boundaries, identity evidence, attributes, identifiers, labels/aliases, disambiguation, provenance, and practical record design. |
| 09.4 | Documented | Semantic Relationships & Relationship Modeling defines relationship meaning, predicates, direction, participant constraints, context, provenance, assertion status, and n-ary relationship considerations. |
| 09.5 | Documented | Ontologies, Taxonomies & Controlled Vocabularies distinguishes formal conceptual schemas, hierarchical classification, controlled terminology, selection criteria, and governance. |
| 09.6 | Documented | Knowledge Graphs & Knowledge Representation explains graph-based modeling, RDF graph structures, identifiers, datasets, provenance, querying, validation, and representation trade-offs. |
| 09.7 | Documented | Topical Modeling & Knowledge Domains defines subject boundaries, concepts, subdomains, dependencies, grouping logic, granularity, and a reusable domain-model specification. |
| 09.8 | Documented | Topical Coverage & Semantic Completeness evaluates concepts, attributes, relationships, information requirements, omissions, redundancy, relevance, and uncertainty against declared scope. |
| 09.9 | Documented | Semantic Information Architecture for Websites translates the validated topical model into user-oriented information groups, page roles, labels, metadata, page boundaries, and architecture specifications. |
| 09.10 | Documented | Semantic Model Validation, Maintenance & Governance defines structural, logical, evidence, scope, and architecture-alignment checks; provenance, ownership, severity, versioning, deprecation, change control, and ongoing maintenance. |



## Related Domains

- [02 — Search Engine Fundamentals](../02-Search-Engine-Fundamentals/README.md)
- [03 — Search Engine Algorithms](../03-Search-Engine-Algorithms/README.md)
- [04 — Information Retrieval](../04-Information-Retrieval/README.md)
- [05 — Keyword & Search Intent](../05-Keyword-and-Search-Intent/README.md)
- [06 — SERP & Search Features](../06-SERP-and-Search-Features/README.md)
- [07 — On-Page SEO](../07-On-Page-SEO/README.md)
- [08 — Content SEO](../08-Content-SEO/README.md)
- [12 — Off-Page SEO](../12-Off-Page-SEO/README.md) — external brand mentions and reputation monitoring are practitioner-side activities; entity modeling and semantic relationships remain in Domain 09.

## References

This index defines the repository's editorial architecture and topic ownership. It does not establish search-engine ranking behavior. Substantive topic documents must cite the primary research, standards, and official documentation that support their individual claims.
