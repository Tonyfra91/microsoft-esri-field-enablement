---
title: Five-Minute Excel Conversation Demo
description: A prepared demonstration of fictional service locations in a spreadsheet and map.
---

## The customer question

> Where are our service locations, and what should we investigate next?

Show how a geographic view can add context to familiar spreadsheet rows.
Audience: a business owner and GIS colleague. This is a drafted runbook, not
a validated customer solution.

## Status and preparation

| Item | Status |
|------|--------|
| Vendor capability | Coordinate mapping is documented by Esri; confirm the supported client and account mode |
| Repository execution | Not run in Excel; no tested product version or execution date recorded |
| Delivery time | Five-minute target after preparation; not a measured result |
| Sample data | [Original synthetic CSV](data/service-locations.csv); see [rights and expected totals](data/README.md) |

Prepare outside the five-minute meeting segment:

1. Confirm a supported Excel client, approved ArcGIS for Excel installation,
   network access, and organizational permission to use the add-in.
2. Read the [Esri introduction](https://doc.arcgis.com/en/excel/latest/get-started/get-started-with-arcgis-for-excel.htm)
   and [official tutorial](https://learn.arcgis.com/en/projects/get-started-with-arcgis-for-excel/).
   Guest coordinate mapping is documented, but capabilities differ from signed-in use.
   Rehearse the chosen mode; do not assume an ArcGIS subscription is included.
3. Import the CSV into Excel, confirm six columns and eight data rows, and save
   a working copy as an Excel workbook. Verify decimal values using your locale.
4. Open the ArcGIS tab and Show Map. From Layers, choose Excel and add the
   worksheet range A1:F9 with the first row treated as headers.
5. Choose the coordinate location type, mapping Longitude to x and Latitude to y.
   Confirm WGS 84 decimal degrees and add the layer. Follow current product
   labels if they differ; do not use address geocoding for these coordinates.
6. Confirm all eight points and site identifiers, then prepare a clean starting
   workbook with the sample rows visible. Do not publish a hosted layer.

Sources checked: 2026-10-30. These steps adapt documented workflows to original
data; the adapted workflow still requires product rehearsal.

## Five-minute delivery plan

| Time | Show and say |
|------|--------------|
| 0:00-0:45 | Show the eight spreadsheet records. Ask which questions the rows answer and which need geographic context. |
| 0:45-2:00 | Open the prepared map and identify the North and South groups. Explain that these are fictional groups, not service boundaries. |
| 2:00-3:15 | Open a point's information and relate its site identifier to the source row. Compare a North and South location. |
| 3:15-4:15 | Return to the rows: North totals 300 requests; South totals 200. Ask what capacity or population information is missing. |
| 4:15-5:00 | Agree on one evaluation question, a safe dataset, a responsible person, and a review date. Do not recommend a new site from this map. |

## Expected result and checks

The prepared map should show eight distinct locations matching the source.
Record a failure if points are missing, coordinates are reversed, access is
blocked, or the selected client cannot complete the workflow.
The demonstration succeeds only if the audience can identify a useful follow-up
question; displaying a map alone does not establish business value.

## If something does not work

Check numeric types, decimal settings, range A1:F9, coordinate fields, and
supported client/account requirements. If the add-in or network is blocked,
show the CSV and linked official walkthrough and state that the live demo did
not run. Do not substitute an unapproved screenshot or claim success.

## Cleanup and rehearsal evidence

Delete the local working copy when no longer needed, remove the sample layer
from the workbook, and sign out of any demo account. Remove any accidentally
published sample item with the GIS owner's approval; check retention rules
before deleting cloud-hosted workbook copies.

Before calling this runbook tested, complete the
[rehearsal record](README.md#record-a-rehearsal) with the exact client/add-in
versions, account mode, observed result, elapsed time, and remaining limitations.

Next: [Excel conversation card](../02-integration-catalog/microsoft-365/excel.md),
[technical evaluation](../05-architecture/excel-evaluation.md), and
[meeting follow-up](../06-sales-enablement/meeting-templates.md).
