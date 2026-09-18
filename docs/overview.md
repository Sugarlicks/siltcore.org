# Overview

SILT Core v0.2 is a semantic architecture for encounters between participants, collectives and systems operating under different legal, cultural, customary, private, institutional or technical orders.

Its central problem is not simply identity verification or permissioning. It is how different orders become mutually legible at a moment of encounter without requiring one order to collapse into another or surrender its own source of authority.

The settled architectural seam is:

> Source → Standing → Presentation → evaluation at the encounter

This expresses semantic dependency, not a mandatory one-to-one processing pipeline.

## Source

A Participant arrives from somewhere. SILT does not reduce that “somewhere” to an issuer, registry or credential authority. It is represented through Source.

A Standing may be grounded in multiple Sources, and a Source may support multiple relational positions.

## Standing

Standing is a relational position grounded in Source.

It is not a universal credential, a platform status, or a self-certified claim. The receiving system may evaluate a Presentation of Standing without becoming the source of that Standing.

## Presentation

Presentation is the bounded, present-tense act or envelope through which a Participant brings the minimum relevant projection of Standing into a particular encounter.

A Presentation may contain more than one relevant semantic claim. An encounter need not require a substantive Standing claim where none is necessary.

## Profile Expression

One or more Profile Expressions may inform evaluation at an encounter.

A Profile Expression is a bounded, selective and non-exhaustive expression of semantic conditions relevant to evaluation. It may arise from legal, customary, cultural, relational, contractual, institutional, governance or other normative contexts.

The originating normative or relational substrate remains prior to and independent of the expression. A Profile Expression does not capture, constitute, modify, constrain, govern or otherwise encumber that substrate.

Presentation and Profile Expression are distinct: Presentation is what the Participant brings; Profile Expression expresses encounter-relevant conditions under which that Presentation may be evaluated.

Multiple Profile Expressions may coexist or conflict. SILT does not silently merge or rank them.

## Evaluation

Evaluation may concern Standing and, where relevant:

- Evidence
- Authority
- Consent
- Reliance
- Action
- Attribution
- Revocation
- Obligation

For each evaluated semantic condition, SILT uses three outcomes:

- `SATISFIED`
- `NOT_SATISFIED`
- `INDETERMINATE`

SILT must not infer an unstated legal, institutional, cultural or normative rule merely to force a determinate result.

Where a condition cannot be adequately expressed without material distortion, SILT Core does not require that condition to be forced into evaluation.

Evaluation is encounter-specific. It does not acquire jurisdiction over the Participant's underlying Source-grounded relations or over the normative substrate from which a Profile Expression arose.

## Architectural boundary

SILT Core is semantically thick and operationally thin.

It remains deliberately thin about:

- authentication
- credential formats
- key management
- transport
- registries
- runtime policy
- dynamic authorisation
- technical capabilities
- execution machinery

These systems may interact with SILT, but they do not become SILT Core merely because they are adjacent to it.

SILT Core does not determine universal legal validity, personhood, cultural authenticity, collective representation, Binding or liability. Nor does it replace DID/VC systems, authentication protocols, capability systems, policy engines, courts, arbitration or governance processes.

Its role is narrower and more precise: to make relevant legitimacy semantics selectively legible at the encounter.

**Semantic hand-off, not semantic surrender.**
