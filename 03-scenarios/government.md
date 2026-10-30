---
title: Government Scenario
description: A discovery-led example for government customer conversations.
---

## Government customer conversation

Curated field guidance for Esri subsidiaries, distributors, partners, and
Microsoft field teams. This is a hypothetical discovery scenario, not a customer
reference, validated solution, or compliance assessment.

## Example need

A government department wants to discuss how service demand and service locations
vary across its area. The conversation should establish whether geographic
context would help staff review coverage and prioritize further analysis.

Suggested opening:

> How do your teams compare where services are needed with where they are
> delivered, and what information is missing from that discussion?

## Follow the journey

1. Define one decision, its users, and a measurable evaluation goal using the
   [discovery questions](../01-start-here/customer-discovery-questions.md).
2. If Power BI reporting is relevant, assess
   [ArcGIS for Power BI](../02-integration-catalog/fabric/power-bi.md) as a candidate.
3. Prepare the [draft Power BI runbook](../04-demos/power-bi-five-minute-demo.md)
   using [original synthetic points](../04-demos/data/README.md).
   It has not been product-tested and does not model actual service demand.
4. Review the [Power BI evaluation example](../05-architecture/power-bi-evaluation.md)
   and [technical checklist](../05-architecture/technical-qualification.md)
   before proposing a design.
5. Confirm details in the [Microsoft](../07-resources/microsoft-resources.md)
   and [Esri](../07-resources/esri-resources.md) documentation.

## Government-specific checks

* Identify the relevant jurisdiction, environment, and public-sector cloud requirements
* Verify data classification, residency, access, accessibility, and sharing requirements
* Confirm whether aggregated data could still expose sensitive locations or individuals
* Validate availability, licensing, procurement, support, and compliance requirements
  with current official sources and the customer's responsible teams

Government-cloud availability and compliance evidence: **Needs current-source validation**.
Do not assume commercial-environment documentation establishes government suitability.

## Proposed evaluation criteria

| Test | Proposed acceptance criterion | Responsible role |
|------|-------------------------------|------------------|
| Sample interpretation | Users identify eight fictional sites and distinguish the North/South groups from actual service areas | Report author and business owner |
| Numeric accuracy | Report totals match the sample: North 300, South 200, total 500 | Report author |
| Coverage limits | The team identifies missing population, service boundaries, capacity, and travel information | GIS specialist |
| Access and suitability | The selected environment and intended viewers have documented support and authorized access before publication | Platform administrator and security team |

These criteria have not been executed. The point map can start a coverage
discussion but cannot establish coverage or justify investment.
Pause if required government-cloud evidence or safe data access is unavailable.

## Suggested next action

Agree on one evaluation question, a safe dataset, an owner, and success criteria.
For example, ask whether users can identify the additional information needed
to assess service coverage. The service owner defines that question; the report
author and GIS owner prepare the evaluation and record a review date using the
[evaluation plan](../06-sales-enablement/meeting-templates.md#evaluation-plan).
Do not promise cost savings, response-time improvements, or production readiness
without evidence.

[All scenarios](README.md)
