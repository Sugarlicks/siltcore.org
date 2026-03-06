# SILT Core

Specification v0.1  
Status: Draft  
Scope: Identity infrastructure for modelling authority, consent, delegation, and revocation in digital systems.

SILT Core is a spec-first identity infrastructure project focused on formalising status, standing, authority, consent, delegation, and revocation as enforceable, technology-agnostic primitives.

Rather than delivering an application or platform, the project defines a missing semantic layer that many civic, governance, and digital systems implicitly depend on but rarely specify.

The work draws on long-standing private-law concepts such as agency, mandate, and reliance to clarify the conditions under which an identity holder may:

• act  
• bind themselves or others  
• delegate authority  
• express consent  
• revoke authority  

SILT Core is designed to be adopted, critiqued, or extended by multiple downstream implementations across diverse legal and technical environments.

---

## Scope

The current specification work focuses on defining a minimal semantic framework for:

- status
- standing
- authority
- consent
- delegation
- revocation

The goal is to make authority relationships explicit, auditable, and revocable by default.

Implementation is intentionally deferred. The project focuses on specification, threat modelling, and schema design rather than delivering a canonical application.

---

## Repository Structure

/docs  
Core specification texts and supporting documentation.

index.html  
Public project overview for siltcore.org.

styles.css  
Minimal styling for the project site.

---

## Documentation

Overview  
docs/overview.md

Bitcoin relevance  
docs/bitcoin.md

Ethereum relevance  
docs/ethereum.md

Current project status  
docs/status.md

---

## Design Principles

- specification-first development  
- technology-agnostic architecture  
- explicit authority modelling  
- revocation as a first-class primitive  
- compatibility with diverse legal and governance systems

---

## Status

Specification version: v0 (draft)

The project currently includes:

- normative specification drafts  
- threat model and misuse cases  
- early schema definitions  

Future work may include reference implementations, additional threat modelling, and interoperability mappings.

---

## License

Apache License 2.0
