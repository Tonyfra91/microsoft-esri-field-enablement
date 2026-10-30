---
title: Five-Minute Power BI Conversation Demo
description: A prepared report demonstration connecting fictional measures to locations.
---

## The customer question

> Where do our reported measures differ, and what context is missing?

Use the same fictional service locations as the Excel example, this time in a
reporting workflow. Do not imply that showing points establishes service coverage.

## Status and preparation

| Item | Status |
|------|--------|
| Vendor capability | ArcGIS report mapping is documented by Microsoft and Esri; validate the intended environment |
| Repository execution | Not run in Power BI; no tested product version or execution date recorded |
| Delivery time | Five-minute target after preparation; not a measured result |
| Sample data | [Original synthetic CSV](data/service-locations.csv); see [rights and expected totals](data/README.md) |

Prepare outside the five-minute meeting segment:

1. Use a supported Power BI Desktop environment with the ArcGIS visual allowed
   by the organization. Confirm network access and consent requirements.
2. Read the [Microsoft tutorial](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualizations-arcgis)
   and [Esri introduction](https://doc.arcgis.com/en/power-bi/latest/get-started/introduction-to-arcgis-for-power-bi.htm).
   Use the documented standard experience for this local point-map exercise;
   verify additional account requirements before adding other capabilities.
3. In a new report, import the CSV with Get data, Text/CSV. Set Latitude and
   Longitude to decimal numbers and Requests to a whole number. Check locale.
   Assign geographic data categories and do not summarize the coordinate columns.
4. Add an ArcGIS for Power BI visual and accept applicable terms. Assign the
   Latitude and Longitude fields to their matching field wells. Include SiteID
   so individual records can be identified; confirm eight distinct points.
5. Add a table visual with Area and the sum of Requests. Check North = 300,
   South = 200, and total = 500. Do not count Requests as rows.
6. Save a local report copy and rehearse it. Publishing, embedding, refresh,
   and sharing are deliberately outside this five-minute demonstration.

Sources checked: 2026-10-30. Current field labels can vary by version.
The original-data adaptation requires product rehearsal before live use.

## Five-minute delivery plan

| Time | Show and say |
|------|--------------|
| 0:00-0:45 | Explain the reporting question and confirm that all eight sites and their values are fictional. |
| 0:45-2:00 | Show the ArcGIS visual. Locate a North point and a South point using their site identifiers. |
| 2:00-3:15 | Show the Area summary: North 300, South 200, total 500. Explain how the map adds context without proving cause. |
| 3:15-4:15 | Ask who needs the report and whether it should remain restricted. Explain that a local report is not proof of sharing or refresh support. |
| 4:15-5:00 | Agree on one reporting decision to evaluate, a report author, a GIS owner, and an access review before any publication. |

## Expected result and checks

Confirm eight distinct map points, the correct numeric totals, and no customer
or private geographic layers. Treat missing points, incorrect aggregation,
blocked consent, or an unavailable visual as a failed rehearsal.
Do not assume map/table interactions behave a particular way without testing them.

## If something does not work

Check types, locale, coordinate categories, field assignments, and tenant policy.
If the visual is unavailable, state that the map demonstration did not run.
Use the CSV and linked official tutorial to explain the question instead.
Do not enable public publishing or change tenant policy to bypass a blocker.

## Cleanup and rehearsal evidence

Remove the local report and imported working copy when no longer needed.
If anything was published outside this runbook, have the responsible owner
remove the sample report and dataset according to retention rules.
Never use Publish to web as a substitute for an approved sharing design.

Complete the [rehearsal record](README.md#record-a-rehearsal) before calling this
tested. Record the Desktop version, ArcGIS visual information, account mode,
observed point count and totals, time, and blockers.

Next: [Power BI conversation card](../02-integration-catalog/fabric/power-bi.md),
[technical evaluation](../05-architecture/power-bi-evaluation.md), and
[meeting follow-up](../06-sales-enablement/meeting-templates.md).
