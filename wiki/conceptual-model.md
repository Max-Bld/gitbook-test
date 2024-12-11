# Conceptual Model

## **Definition**

A _**conceptual model**_, also referred to as _**conceptual model specification**_, is an abstract representation of a system and comprises well-defined concepts, their qualities or attributes, and their relationships to other concepts. A system is a group of interacting or interrelated elements that act according to a set of rules to form a unified whole.

## Description

A conceptual model is a representation of a system that uses concepts to form said representation. A concept can be viewed as an idea or notion, a unit of thought \[[skos](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:skos)]. However, what constitutes a unit of thought is subjective, and this definition is meant to be suggestive rather than restrictive. That is why each concept needs to be well named by providing preferred and alternative labels and should have a clear and precise definition supported by examples and explanatory notes. The conceptual model comprises representations of concepts, their qualities or attributes and relationships to other concepts. Most commonly, these are association and generalisation relations.

In addition, the conceptual model can be materialised in a graphical representation facilitating knowledge elicitation, organisation and interaction with domain experts. This is relevant because interactions and discussions within a Working Group for a data specification are often driven by a graphical representation. However, the need for a conceptual model and a visual representation shall not be conflated. Thus, we keep clear separation of concerns, which is addressed in detailed in the next section \[[Separation of concerns in SEMIC](https://semiceu.github.io/style-guide/1.0.0/arhitectural-clarifications.html#sec:separation-of-concerns-and-transformation)].

There is no perfect candidate for representing the conceptual model. And, although not without limitations, risks for misunderstandings and mis-interpretations, we choose (a subset of) UML language \[[epo-cm2owl](https://semiceu.github.io/style-guide/1.0.0/references.html#ref:epo-cm2owl)] as most appropriate and instrumental in addressing (a) the concern for having a conceptual model established and (b) the concern for providing a graphical representation. The UML appropriateness has been acknowledged based on a longstanding experience and practices. An entire section of this style guide is dedicated to (UML) conceptual model \[[see Conceptual model conventions](https://semiceu.github.io/style-guide/1.0.0/gc-conceptual-model-conventions.html)].

The subset of the UML language considered in this style guide is comprised (but not limited to) in the following set of UML elements:

* Class
* Class Attribute
* Connector
  * Association
  * Dependency
  * Generalisation
* Enumeration

For visual representation only UML Class Diagrams are considered.

**Note:** UML will be the recommended language for defining the conceptual models until a better and more appropriate alternative with robust tool support is developed, that is also addressing the SEMIC methods and practices \[[see Architectural clarification](https://semiceu.github.io/style-guide/1.0.0/arhitectural-clarifications.html)].
