# LCABIM Ontology (LCA–BIM Workflow)

This repository hosts the published documentation and RDF serializations for the LCABIM ontology stack used in the LCA–BIM Workflow project.

## Persistent namespace (recommended for citation and reuse)

Use the persistent IRIs under:

- https://w3id.org/lcabim/

These IRIs redirect to the currently hosted documentation and files.

## Hosted documentation (current target)

The documentation site is published via GitHub Pages:

- https://g3rezz.github.io/lcabim-ontology/

## Ontology modules

The ontology is published as an umbrella/core ontology plus several modules:

- **LCABIM Core (umbrella)**: `https://w3id.org/lcabim/lcabimcore`
- **ILCD core schema (LinkML-generated)**: `https://w3id.org/lcabim/ilcd`
- **DIN 276 cost groups**: `https://w3id.org/lcabim/din276`
- **ÖKOBAUDAT categories**: `https://w3id.org/lcabim/obd`
- **Concrete classes (derived)**: `https://w3id.org/lcabim/concreteclass`
- **BKI element / layer model**: `https://w3id.org/lcabim/bki`
- **bSDD LCA indicators**: `https://w3id.org/lcabim/bsdd`
- **ILCD LCA indicators**: `https://w3id.org/lcabim/ilcdind`

## RDF downloads

Turtle files are published per module under the persistent namespace, e.g.:

- https://w3id.org/lcabim/lcabimcore/ontology.ttl
- https://w3id.org/lcabim/ilcd/ontology.ttl
- https://w3id.org/lcabim/din276/ontology.ttl
- https://w3id.org/lcabim/obd/ontology.ttl
- https://w3id.org/lcabim/concreteclass/ontology.ttl
- https://w3id.org/lcabim/bki/ontology.ttl
- https://w3id.org/lcabim/bsdd/ontology.ttl
- https://w3id.org/lcabim/ilcdind/ontology.ttl

## How the documentation is generated

The module documentation pages are generated with WIDOCO (bilingual `en`/`de`) and published from the `/docs` folder using GitHub Pages.
