# Core Vocabulary

## Definition

A Core Vocabulary (CV) is a basic, reusable and extensible [data specification](data-specification/) that captures the fundamental characteristics of an entity in a context-neutral fashion. Its main objective is to provide terms to be reused in the broadest possible context.

## Broad Context

On the Semantic Web, vocabularies define the concepts and relationships (also referred to as "terms") used to describe and represent an area of concern. Vocabularies are used to classify the terms that can be used in a particular application, characterise possible relationships, and define possible constraints on using those terms. In practice, vocabularies can be very complex (with several thousands of terms) or very simple (describing one or two concepts only) \[[vocab](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:vocab)].

There is no clear division between what is referred to as "vocabulary" and "[ontology](ontology.md)". The trend is to use the word "ontology" for a more complex and possibly quite formal collection of terms, whereas "vocabulary" is used when such strict formalism is not necessarily used or used only in a very loose sense \[[vocab](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:vocab)].

Formally, a Core Vocabulary encompasses a lightweight ontology, and, optionally, a (permissive) data shape specification, and it is expressed in a condensed, comprehensive data specification document.

* CV =
  * lightweight ontology +
  * (optionally) a (permissive) data shape

For more details see section on \[[Data specification and artefact types](https://semiceu.github.io/style-guide/1.0.0/arhitectural-clarifications.html#sec:data-specification-and-artefact-types)].

The qualifications _lightweight_ and _permissive_ are used to better emphasise the intention _to be reused in the broadest possible context_. More precise boundaries are defined further in this document.

***

Source: SEMIC 2024
