# Current Status

## SILT Core v0.2

The **SILT Core v0.2 semantic architecture is finalised and frozen**.

The semantic freeze follows completion of the pre-freeze adversarial test programme and preserves the settled architectural seam:

> Source → Standing → Presentation → evaluation at the encounter

The close-out introduced no new Core object and did not reopen the architectural seam.

The v0.2 architecture now treats the encounter as its conceptual centre, with one or more Profile Expressions able to inform evaluation without becoming part of the architectural seam itself.

## Evaluation model

A SILT-conformant evaluation may return:

- `SATISFIED`
- `NOT_SATISFIED`
- `INDETERMINATE`

SILT does not infer unstated legal, cultural, institutional or normative rules to manufacture a determinate answer.

Where bounded expression would materially distort a condition, SILT Core does not require that condition to be forced into evaluation.

## Publication status

The v0.2 semantic architecture is frozen, but the **v0.2 GitHub release tag has not yet been published**.

Current work therefore concerns release packaging, migration of public documentation and repository materials, copy-editing, publication-level naming, and alignment of implementation artefacts with the frozen architecture.

Until that release is published, **v0.1 remains the currently tagged public release**.

## Architectural boundary

SILT Core remains specification-first, implementation-neutral and deliberately thin about authentication, credentials, key management, transport, runtime policy, dynamic authorisation and execution machinery.

Downstream implementations may authenticate, authorise and execute. SILT preserves the semantic thread explaining what those actions mean.
