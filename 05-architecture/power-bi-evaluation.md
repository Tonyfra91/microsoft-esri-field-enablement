---
title: Power BI Evaluation Example
description: A conceptual technical handoff from local reporting to an access-reviewed evaluation.
---

## Decide what the customer should learn

Question: does a geographic view help report users ask a better question about
their measures? Start with the
[Power BI demo](../04-demos/power-bi-five-minute-demo.md).

This is a conceptual evaluation example, not a deployed or validated reference
architecture. Product execution has not been recorded.

## Understand the boundaries

```text
Synthetic CSV -> local Power BI report -> ArcGIS visual and permitted services
                            |
                 sharing design reviewed separately
```

The presenter controls the original file and local report. ArcGIS mapping uses
services, so local report authoring is not proof of local-only processing.
The five-minute exercise does not publish to the Power BI service, embed a report,
configure refresh, or grant access to another user.

A later shared evaluation needs separate review of the report, its data source,
ArcGIS content, identities, network paths, storage, and viewer permissions.
Do not assume permission to a report grants access to every ArcGIS layer.

## Work through qualification

| Requirement | Proposed evaluation choice | Evidence still needed |
|-------------|----------------------------|-----------------------|
| Data | Original synthetic point locations and request counts | Eight distinct points and numeric total of 500 in the report |
| Authoring | Supported Desktop and approved ArcGIS visual | Consent, client version, account mode, and tenant policies |
| Viewer access | Not exercised in the local demo | Supported sharing method, permissions, and Microsoft/Esri licensing |
| Refresh | Not configured in the demo | Source access, credentials, update schedule, and responsible owner |
| Success measure | Users can relate a location to its record and state what other data is needed | Observed result and user feedback |
| Cleanup | Remove local artifacts; review any cloud publication separately | Owner and retention requirements |

Bring the report author, Power BI administrator, GIS owner, and security team
into the access review. Use the [shared qualification checklist](technical-qualification.md).
Never use public publishing to work around an access restriction.

## Evidence and next decision

Review the [Microsoft tutorial](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualizations-arcgis),
[Esri introduction](https://doc.arcgis.com/en/power-bi/latest/get-started/introduction-to-arcgis-for-power-bi.htm),
and [publishing validation article](../07-resources/relevant-blogs.md#start-with-a-customer-conversation)
with their stated limitations. Sources reviewed: 2026-10-30.

Record a product rehearsal before describing the demo as tested. Agree on
private evaluation data, intended viewers, and a review date using the
[evaluation template](../06-sales-enablement/meeting-templates.md#evaluation-plan).
Government-cloud support and customer-specific compliance:
**Needs current-source validation**.
