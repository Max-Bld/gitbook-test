# Application Profile

## Definition

An Application Profile is a data specification aimed to facilitate the data exchange in a well-defined application context. It re-uses concepts from one or more semantic data specifications, while adding more specificity, by identifying mandatory, recommended, and optional elements, addressing particular application needs, and providing recommendations for controlled vocabularies to be used \[[dcat-ap](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:dcat-ap)].

## Description

An Application Profile (AP) is a data shape specification which addresses particular application needs (operating within some domain or community) while providing semantic interoperability with other applications based on one or more shared ontologies (vocabularies) \[[dc-ap](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:dc-ap)].

Formally, the Application Profile encompasses (a) reused ontology specifications (one or many) and (b) its own data shape specification. Optionally it may include (c) reused data shape specifications (one or many), and (d) it may provide its own ontology specification to fill the ontological gaps.

* AP =
  * reused lightweight ontology +
  * own data shape +
  * (optionally) reused (permissive) data shape +
  * (optionally) own ontology

## SEMIC Context

In SEMIC, Application Profiles encompass an ontology, which is largely composed of importing the reused ontologies, complemented with an appropriate data shape specification. Terms that are introduced because of the Application Profile needs are, by preference, added to existing Core Vocabularies. If this is not possible, an Application Profile-specific Vocabulary is created.

* AP =
  * reused Core Vocabulary +
  * own data shape +
  * (optionally) own ontology

The data specification document of an Application Profile is elaborated. It provides the application scope and context, and documents the ontology and the data shapes through the conceptual model. It also provides additional information that stimulates the adoption and correct usage of the AP in implementations.
