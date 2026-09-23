# Current Status

## SILT Core v0.2

The **SILT Core v0.2 semantic architecture is finalised and frozen**.

The semantic freeze follows completion of the pre-freeze adversarial test programme and preserves the settled architectural seam:

> Source → Standing → Presentation → evaluation at the encounter

The close-out introduced no new Core object and did not reopen the architectural seam.

The v0.2 architecture now treats the encounter as its conceptual centre, with one or more Profile Expressions able to inform evaluation without becoming part of the architectural seam itself.

## Worked encounters and implementation bridge

The published v0.2.0 minimal semantic conformance suite contains four base encounters and 30 adversarial variants spanning:

- transferable instruments
- credential-carried institutional Standing
- plural and collective Authority
- recursive AI delegation

The conformance programme did not identify a recurring missing semantic concept requiring the Core to be reopened.

They now provide the bridge into bounded implementation work, including institutional delegation and collective Authority encounters. Implementation choices remain distinct from the semantic Core and must not quietly redefine it.

## Evaluation model

A SILT-conformant evaluation may return:

- `SATISFIED`
- `NOT_SATISFIED`
- `INDETERMINATE`

SILT does not infer unstated legal, cultural, institutional or normative rules to manufacture a determinate answer.

Where bounded expression would materially distort a condition, SILT Core does not require that condition to be forced into evaluation.

## Publication status

**[SILT Core v0.2.0](https://github.com/Sugarlicks/silt-identity-core/releases/tag/v0.2.0) was published on 23 September 2026** and is the current public release.

The tagged release provides the stable, citable snapshot of:

- the [v0.2.0 semantic architecture](https://github.com/Sugarlicks/silt-identity-core/blob/v0.2.0/spec/SILT_Core_v0.2.0_Semantic_Architecture.md)
- the [v0.2.0 documentation set](https://github.com/Sugarlicks/silt-identity-core/tree/v0.2.0/docs)
- the minimal semantic conformance schema and suite
- the interim governance, contribution, IPR, trademark and conformance-claim policies

SILT Core v0.1 remains available as the previous public release. A DOI will be added when the tagged release has been archived.

## Architectural boundary

SILT Core remains specification-first, implementation-neutral and deliberately thin about authentication, credentials, key management, transport, runtime policy, dynamic authorisation and execution machinery.

Downstream implementations may authenticate, authorise and execute. SILT preserves the semantic thread explaining what those actions mean.
