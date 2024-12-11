# Ontology

## Definition

An _**ontology**_, also referred to as _**ontology specification**_, is a a formal specification describing the concepts and relationships that can formally exist for an agent or a community of agents (e.g. domain experts) \[[gruber93](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:gruber93)]. It encompasses a representation, formal naming, and definition of the categories, properties, and relations between the concepts, data, and entities that substantiate one, many, or all domains of discourse \[[wiki-onto](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:wiki-onto)].

## Description

The ontology constitutes the formal (machine-readable) definition of concepts. Although the languages for expressing ontologies vary in expressivity, we shall keep it light and simple, from the formal point of view, with minimal detail and level of expressivity \[[SC-R2](https://semiceu.github.io/style-guide/1.0.0/gc-semantic-conventions.html#sec:sc-r2)]. Backer & Sutton explain well how lightweight semantics supports interoperability and reuse \[[baker15](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:baker15)].

In the SEMIC context, we only consider _lightweight ontologies_ \[[defined in rule SC-R2](https://semiceu.github.io/style-guide/1.0.0/gc-semantic-conventions.html#sec:sc-r2)]. Therefore, even if this aspect is not emphasised as "lightweight ontology", it is implicitly meant even when simple "ontology" reference is used.

We assume that the ontology is expressed in OWL 2 language \[[SC-R1](https://semiceu.github.io/style-guide/1.0.0/gc-semantic-conventions.html#sec:sc-r1)].

The main purpose of this component is to declare the classes, properties, datatypes and controlled lists. Each construct is established by assigning a URI and decorating it with human-readable labels and descriptions, and constitutes the mechanism to establish common references for humans and machines.
