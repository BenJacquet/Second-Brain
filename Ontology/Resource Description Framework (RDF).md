
In semantic technologies, the recommended data model to publish graph-based data on the Web is defined in this framework.

An RDF graph consists of a finite set of triples where each triple (**s**, **p**, **o**) is an ordered set of the following terms: a **subject** s, a **predicate** p that associates the subject and the object, and an **object** o.

For example: 
Ben (subject) lives in (predicate)  Versailles (object)
Versailles (subject) is in (predicate) France (object)

We can also use inference to generate new triples from existing triples:
Ben (subject ) lives in (predicate) France (object)

An RDF term is either a URI, a blank node, or a literal.
- URI: references resources unambiguously
- Literal: describes data value with no clear identity
- Blank Node: facilitates quantification for an individual without naming properties


Based on those basic technological building blocks, in recent years, several noteworthy large, cross-domain, and openly available knowledge graphs have been created.
These include DBpedia, Freebase, OpenCyc, Wikidata, and YAGO. They have grown to an impressive number of triples, like Freebase which is the largest knowledge graph with over 3.1B triples.

We can find several RDF datatypes:
- RDF / JSON
- RDF / XML
- TTL or Turtle

The query language and protocol  for RDF is SPARQL.

Databases that store semantic data are calles RDF Triple Stores:
- They are flexible (NoSQL), require no schema upfront
- Fast and scalable
- Subjects and Objects are stored as node, predicates as edges
- Ability to interpret data and discover hidden relationships

![[Application of Semantic Technology for Knowledge Engineering.png]]

