# SILT Core

**Semantic infrastructure for plural encounters.**

SILT Core v0.2 provides a semantic architecture through which participants, collectives and systems operating under different legal, cultural, customary, private, institutional or technical orders may become mutually legible at moments of encounter without requiring those orders to collapse into a single ontology or surrender their own sources of authority.

SILT is concerned with encounter rather than assimilation.

> Source → Standing → Presentation → evaluation at the encounter

This is the settled architectural seam for v0.2.

---

## Current status

The **SILT Core v0.2 semantic architecture is finalised and frozen** following the pre-freeze stress-test programme.

The semantic freeze introduces no new Core object and preserves the settled movement:

> Source → Standing → Presentation → evaluation at the encounter

Release packaging, repository migration and publication work are now underway. Until a v0.2 GitHub release tag is published, **v0.1 remains the currently tagged public release**.

---

## Conceptual centre

The conceptual centre of SILT Core v0.2 is the encounter.

A Participant arrives from somewhere. SILT does not reduce that “somewhere” to an issuer. It is represented through **Source**.

From Source arises or is grounded a relational position: **Standing**. Standing is relational and Source-grounded. It is not a universal credential, a platform status, or a self-certified claim.

For a particular encounter, the Participant need not reveal the whole relationship. Instead, the Participant makes a bounded, present-tense projection: **Presentation**.

Evaluation then occurs at the encounter. The receiving Participant, order or system may evaluate what has been presented without thereby becoming the source of that Standing.

---

## Profile Expression

One or more **Profile Expressions** may inform evaluation at an encounter.

A Profile Expression is a bounded, selective and non-exhaustive expression of semantic conditions relevant to evaluation. It may arise from a legal, customary, cultural, relational, contractual, institutional, governance or other normative context.

It does not represent or exhaust that context. The originating normative or relational substrate remains prior to, independent of, and unencumbered by the expression.

Presentation and Profile Expression are distinct:

- **Presentation** is what a Participant brings into the encounter.
- **Profile Expression** expresses encounter-relevant conditions under which that Presentation may be evaluated.

Multiple Profile Expressions may coexist or conflict. SILT does not silently merge, rank or privilege them.

---

## Evaluation

Evaluation may concern Standing and, where relevant, Evidence, Authority, Consent, Reliance, Action, Attribution, Revocation and Obligation.

For each evaluated semantic condition, SILT uses three outcomes:

- `SATISFIED`
- `NOT_SATISFIED`
- `INDETERMINATE`

`INDETERMINATE` is a legitimate semantic result. SILT does not import an unstated legal, institutional, cultural or normative rule merely to force a determinate answer.

Where a condition cannot be adequately expressed without material distortion, SILT Core does not require it to be forced into evaluation.

SILT also does not infer an aggregate result across heterogeneous conditions unless the relevant Profile Expression supplies a composition rule.

---

## Where SILT sits

**Semantically thick. Operationally thin.**

SILT standardises the boundary at which relational legitimacy may become selectively legible across systems. It does not standardise the originating ontology or normative substrate itself.

Authentication, credential formats, key management, transport, registries, runtime policy, dynamic authorisation, technical capability systems and execution machinery remain below or adjacent to the SILT semantic layer.

DID/VC systems may carry identifiers and attestations. Capability systems may express technical permissions. Wallets may sign. Policy engines may decide. Agents and smart contracts may execute.

SILT preserves the semantic thread that explains what those actions mean in context.

**Semantic hand-off, not semantic surrender.**

---

## What SILT Core is not

SILT Core is not:

- a universal identity model
- a universal legal ontology
- a universal authorisation engine
- a credential system
- a conflict-of-laws system
- a universal verifier
- a law engine
- a universal method for determining personhood or collective representation
- a replacement for DID/VC, authentication, capability systems, policy engines, courts, arbitration or governance processes
- a system for determining universal Binding, liability or recognition

SILT makes normative difference legible. It does not guarantee agreement between normative orders.

---

## Why this matters

Digital systems increasingly connect people, collectives and institutions whose Standing arises from different legal, cultural, customary, relational and technical orders.

These encounters rarely take place on neutral ground.

Most digital infrastructure recognises Participants through a narrow set of familiar forms: the individual account, the credential holder, the state-issued identity or the incorporated legal person.

These forms may be valid within their own systems. Problems arise when they are treated as the only forms through which a person or collective can become legible.

Standing grounded in relationship, collective recognition, place, history, obligation or living Authority may then be flattened into a credential or severed from the Source that gives it meaning. What cannot be translated into the receiving system’s categories may be treated as absent, informal or invalid.

A credential may therefore be technically valid while the Standing behind it is no longer current. A collective may recognise a representative through its own relationships and processes, while another institution applies different conditions for accepting that representation. Two orders may encounter the same claim differently without either becoming universally authoritative. An AI agent may possess the capability to act without having the Authority to do so.

These are not simply authentication problems. They concern whose categories become infrastructure, whose Standing becomes recognisable, and what meaning is lost in the act of translation.

SILT begins from a different premise: Participants should not have to surrender their sources of meaning in order to interact.

It makes the minimum relevant relational conditions legible at the encounter while allowing different orders to remain different.

---

## AI and delegated systems

AI agents may operate through recursive delegation chains, but technical capability does not itself establish Standing or Authority.

SILT does not attempt to make AI systems legal persons. It provides a semantic grammar through which authority provenance, scope, reliance, attribution, obligation and revocation can remain legible as actions move across human, institutional and machine systems.

An agent with a wallet is not the same thing as an agent with Standing.

---

## Documentation

- [Project overview](docs/overview.md)
- [Current status](docs/status.md)
- [Website](https://siltcore.org)
- [SILT Core repository](https://github.com/Sugarlicks/silt-identity-core)

The canonical v0.2 semantic architecture is being packaged for publication in the SILT Core repository.

---

## Licence

The website repository is licensed under Apache License 2.0. See [`LICENSE`](LICENSE).
