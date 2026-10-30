---
title: Excel Evaluation Example
description: A conceptual technical handoff for an original-data spreadsheet mapping evaluation.
---

## Decide what the customer should learn

Question: can a business user connect spreadsheet records to places and identify
a useful follow-up question? Use the
[Excel demo](../04-demos/excel-five-minute-demo.md) and
[synthetic sample](../04-demos/data/README.md) before introducing customer data.

This is a conceptual evaluation example, not a deployed or validated reference
architecture. Product execution has not been recorded.

## Understand the boundaries

```text
Synthetic CSV -> working Excel workbook -> ArcGIS for Excel map
                                             |
                                  permitted ArcGIS services
```

The CSV and workbook are controlled by the presenter. Excel may be local or
cloud-hosted depending on the selected client. ArcGIS services supply the
mapping experience; do not assume workbook data stays on a device because it
started in a spreadsheet. Confirm actual processing, storage, and network
destinations with current product documentation and organizational policy.

No hosted-layer publication, external sharing, demographic enrichment, or
address geocoding is part of this example. Coordinates identify example points,
not actual facilities or approved service areas.

## Work through qualification

| Requirement | Proposed evaluation choice | Evidence still needed |
|-------------|----------------------------|-----------------------|
| Data | Eight original synthetic rows in a working copy | Imported types, coordinates, and row count checked in the selected client |
| Identity | An approved, rehearsed guest or signed-in mode | Product capability limits and relevant permissions |
| Access | Presenter-only workbook and permitted services | Add-in approval, network access, and any cloud storage policy |
| Location question | Identify points and compare the source records | Users understand the result without inferring coverage |
| Success measure | All eight points match their identifiers and the user names one follow-up question | Observed result and customer feedback |
| Cleanup | Remove working files and any accidentally published sample item | Responsible person and retention requirements |

Bring a Microsoft 365 administrator and GIS specialist into the review.
Use the [shared qualification checklist](technical-qualification.md).
Check licensing for the exact capabilities, not the person's job title.

## Evidence and next decision

The [Esri introduction](https://doc.arcgis.com/en/excel/latest/get-started/get-started-with-arcgis-for-excel.htm)
and [official tutorial](https://learn.arcgis.com/en/projects/get-started-with-arcgis-for-excel/)
support the product workflow, not this customer's implementation.
Sources reviewed: 2026-10-30.

Record a product rehearsal before presenting the runbook as tested. If the
customer proceeds, agree on a restricted dataset and a review date using the
[evaluation template](../06-sales-enablement/meeting-templates.md#evaluation-plan).
Regional, government-cloud, and customer-specific suitability:
**Needs current-source validation**.
