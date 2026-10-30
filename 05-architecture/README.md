---
title: Architecture Guidance
description: Design review questions and boundaries for future architecture patterns.
---

## Architecture guidance

No validated reference architectures or deployable templates are included yet.
Architecture pattern: **Needs current-source validation**.

## Prepare a technical evaluation

Start with the [technical qualification checklist](technical-qualification.md)
for data, identity, licensing, environment, sharing, and operational questions.
Use role-based ownership so the handoff works across countries and organizations.

| Worked example | Starting point | Status |
|----------------|----------------|--------|
| [Excel evaluation](excel-evaluation.md) | Spreadsheet rows and a geographic question | Conceptual; not product-tested |
| [Power BI evaluation](power-bi-evaluation.md) | Local report and a separately reviewed sharing design | Conceptual; not product-tested |

These are evaluation examples, not certified architectures. Each describes
data boundaries, responsibilities, success criteria, and missing evidence.
Use the [evaluation template](../06-sales-enablement/meeting-templates.md#evaluation-plan)
to agree on a decision and review date.

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
