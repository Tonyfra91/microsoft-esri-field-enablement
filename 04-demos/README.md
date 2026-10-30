---
title: Demo Resources
description: Draft five-minute runbooks, original sample data, and honest rehearsal status.
---

## Demo resources

Use a prepared example to support one customer question. Setup and rehearsal
take place before the meeting; five minutes is the delivery target, not a
measured result.

| Runbook | Question | Repository test status |
|---------|----------|------------------------|
| [Excel](excel-five-minute-demo.md) | What geographic context is missing from these rows? | Draft; not run in Excel |
| [Power BI](power-bi-five-minute-demo.md) | Where do our reported measures differ? | Draft; not run in Power BI |

Both use [original synthetic data](data/README.md) with eight locations and
documented expected totals. Data checks do not establish product execution.
No recordings, validated reference architectures, or government-specific
demonstrations are included.

For a complete path, continue from each runbook to its
[Excel evaluation](../05-architecture/excel-evaluation.md) or
[Power BI evaluation](../05-architecture/power-bi-evaluation.md), then agree on
an [evaluation plan](../06-sales-enablement/meeting-templates.md#evaluation-plan).

## Official learning starting point

[Microsoft: Create an ArcGIS map in Power BI](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualizations-arcgis)
is an official tutorial, not a repository-owned demo or a government reference
implementation. Source reviewed: 2026-10-27.

Use the [Power BI catalog entry](../02-integration-catalog/fabric/power-bi.md) to check the associated
Microsoft and Esri documentation before preparing a demonstration.

For everyday work, start with the
[Microsoft 365 learning path](https://learn.arcgis.com/en/paths/try-arcgis-for-microsoft/)
and the [Microsoft 365 seller landing](../02-integration-catalog/microsoft-365/README.md).
The official path was reviewed 2026-10-27; it is not a tested repository-owned demo.

## Before a live demonstration

Curated field guidance:

* State the customer question, intended audience, and expected learning outcome
* Link authoritative prerequisites and limitations
* Use public or synthetic data with documented reuse rights and attribution
* Record setup steps, tested versions, test date, cleanup steps, and known gaps
* Remove credentials, tenant identifiers, personal data, and private customer details
* Label illustrative behavior separately from verified product capabilities

Government demo asset: **Needs current-source validation**.

## Record a rehearsal

Record only public-safe evidence. Never publish account identifiers, credentials,
customer details, or private screenshots. Keep sensitive test details in an
approved private system.

| Field | Record after execution |
|-------|------------------------|
| Runbook and revision | Which procedure and repository revision were exercised |
| Test date and tester role | Actual execution date and responsible role |
| Environment | Client/add-in/visual versions, regional settings, and relevant configuration |
| Account mode | Guest, standard, or signed-in organizational mode as applicable; no account names |
| Vendor release status | Dated authoritative source or Not verified; separate from our test result |
| Expected result | Eight distinct points; North 300, South 200, total 500 where totals are displayed |
| Actual result | Observed counts, numeric totals, access behavior, and any failures |
| Duration | Preparation time separately from actual presentation time |
| Cleanup | Working files and any accidentally published items handled according to retention rules |
| Outcome | Passed, failed, or blocked, with limitations and follow-up |

Only change a runbook's test status after recording execution evidence.
A passing run applies to that environment, not every tenant, region, or client.

Next: [architecture review](../05-architecture/README.md).
