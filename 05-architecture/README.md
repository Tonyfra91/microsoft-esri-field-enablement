---
title: Architecture Guidance
description: Design review questions and boundaries for future architecture patterns.
---

## Architecture guidance

No validated reference architectures or deployable templates are included yet.
Architecture pattern: Source to be validated.

## Questions before selecting a pattern

Curated field guidance:

* Which systems own the data, and where would data be stored, processed, or transferred?
* Which users and services need access, and how would identity and authorization work?
* Which documented sharing, network, and deployment constraints apply?
* What data residency, privacy, security, and accessibility requirements must be met?
* Who owns monitoring, recovery, support, and ongoing operations?

Treat unanswered questions as design gaps, not assumed capabilities.

## Evidence required for a future pattern

Include a scoped use case, diagram, data flows, trust boundaries, prerequisites,
limitations, and links to authoritative Microsoft and Esri documentation.
Record the environment, versions, validation date, and unresolved assumptions.
Distinguish a conceptual illustration from a tested implementation.

For the [Government scenario](../03-scenarios/government.md), validate the target
environment explicitly. Do not label a pattern compliant or government-ready
without applicable public evidence and appropriate review.

Continue to [Microsoft resources](../07-resources/microsoft-resources.md) and
[Esri resources](../07-resources/esri-resources.md).
