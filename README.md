# SILT Core

**Authority semantics for digital action.**

SILT Core is a specification-first semantic layer for expressing capacity, authority source, mandate scope, consent, reliance, delegation, and revocation across digital systems.

It asks a simple question:

> Is this action legitimately authorised, in this context, right now?

---

## Current Release

**SILT Core v0.1 has been released.**

v0.1 establishes the initial public specification and framing layer, including:

* the authority problem
* the distinction between identity, permission, and authority
* the initial semantic frame for lawful digital action
* foundational primitives
* machine-readable schemas
* threat model and misuse-case test vectors
* an experimental reference consent validator

The reference consent validator is non-normative. It is provided to test early implementation patterns only. It does not define the SILT Core specification and does not constrain future v0.2 schema design.

**v0.2 is being planned.**

Candidate v0.2 areas include structured authority claims, expanded primitive definitions, revocation semantics, validation logic, AI-agent execution contexts, legal and governance workflow examples, digital commerce examples, DID/VC interoperability mapping, and plural authority-source modelling.

These are planning areas, not release commitments.

---

## Why SILT exists

Most digital systems can answer:

* who controls an identifier
* what credentials have been issued
* what permissions an account has
* what a key has signed
* what a system is allowed to execute

But they often cannot answer:

* in what capacity is this action being taken?
* by what authority?
* under what mandate?
* within what scope?
* with what consent?
* can others safely rely on it?
* can that authority be revoked?

That gap matters.

A system may permit an action without proving that the action is legitimately authorised.

SILT Core builds a grammar for making these authority conditions explicit, auditable, scoped, and revocable.

---

## Scope

The current specification work focuses on a public semantic layer for:

* status
* standing
* capacity
* authority source
* mandate scope
* consent
* delegation
* reliance
* revocation

SILT Core is designed to be technology-agnostic and may be implemented across APIs, DID/VC systems, smart contracts, AI-agent frameworks, governance platforms, registries, secure execution environments, or other verification substrates.

Implementation is intentionally secondary to semantic clarity.

The project focuses on specification, threat modelling, schema design, reference validation experiments, and misuse-case testing rather than delivering a canonical application or platform.

---

## What SILT Core is not

SILT Core is not:

* a wallet, identity app, or credential issuer
* a blockchain protocol or chain-specific framework
* a token model, DAO toolkit, or governance platform
* a replacement for DID, VC, zCap, or other identity standards
* a legaltech-only product
* a replacement for legal advice
* a universal law code or claim that code is law

SILT Core is authority semantics infrastructure.

---

## Relationship to Existing Systems

SILT Core is designed to complement existing identity and coordination frameworks rather than replace them.

DID and VC systems can express identifiers and attestations.
Capability systems can express delegated permissions.
Wallets can sign.
DAOs can coordinate.
Smart contracts can execute rules.
AI-agent frameworks can automate action.

SILT Core focuses on the missing semantic question beneath these systems:

> In what capacity is this action being taken, under what authority, within what scope, with what consent, and with what revocation conditions?

This makes SILT Core relevant to DID/VC, ZK, capability systems, DAO governance, AI-agent systems, legal workflows, digital commerce, and institutional coordination without requiring any single implementation path.

---

## Repository Structure

```text
/
├── docs/
├── spec/
├── schemas/
├── reference/
│   └── validators/
│       └── consent/
├── tests/
│   └── misuse-cases/
├── index.html
├── styles.css
├── README.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── SECURITY.md
└── LICENSE
```

---

## Documentation

* [Project overview](docs/overview.md)
* [Roadmap](docs/roadmap.md)
* [Design principles](docs/design-principles.md)
* [Threat model](docs/threat-model.md)
* [Contributing](CONTRIBUTING.md)
* [Governance](GOVERNANCE.md)
* [Security policy](SECURITY.md)

Additional technical, historical, or ecosystem-specific notes may sit under `/docs`, but the core README should remain focused on SILT Core as authority semantics for digital action rather than any one chain or implementation context.

---

## Reference Validator

A reference consent validator is available under:

`/reference/validators/consent`

The validator is experimental and non-normative.

It is provided to test early implementation patterns only. It does not define the SILT Core specification and does not constrain future v0.2 schema design.

---

## Design Principles

SILT Core is guided by the following principles:

* specification-first development
* authority before permission
* capacity before credential
* consent as constraint
* revocation as a first-class primitive
* plural authority sources
* technology-agnostic architecture
* compatibility with diverse legal, institutional, community, and governance systems
* clear separation between normative specification, explanatory documentation, illustrative examples, and experimental reference code

---

## Contribution Boundary

SILT Core defines a public semantic layer.

It may be discussed in external standards bodies, working groups, research forums, and implementation contexts.

However:

* contributions in external forums do not constitute transfer of the full SILT architecture
* SILT may include additional models, structures, instruments, and implementation pathways not disclosed publicly
* this repository reflects the public specification layer only
* reference code is experimental unless expressly marked as normative
* planning notes do not create release commitments

The public grammar is open.

The full architecture may include additional models, implementation pathways, and assurance layers beyond this repository.

---

## License

Apache License 2.0.

See [`LICENSE`](LICENSE).
