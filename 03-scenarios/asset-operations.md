---
title: Asset Operations Conversation
description: A hypothetical evaluation connecting asset records, locations, and supporting information.
---

## The business question

> Can staff connect an asset location to the correct record and supporting information?

Hypothetical example, not a customer reference, deployed solution, or claim of
reduced maintenance costs. An operations team has location records in a workbook
and supporting content in a team site.

## Data and people

For initial discussion, use the [synthetic service points](../04-demos/data/README.md)
as a stand-in for an asset register. They contain no actual assets, inspections,
or document links. Do not describe the sample as an asset maintenance dataset.

For a private evaluation, the data owner would supply approved asset identifiers,
coordinates, record dates, and permitted supporting documents. Involve an
operations owner, GIS specialist, Microsoft 365 administrator, and content owner.

## Choose one workflow

Use [Excel](../02-integration-catalog/microsoft-365/excel.md) if the first
question is about understanding spreadsheet records geographically.
Consider [SharePoint](../02-integration-catalog/microsoft-365/sharepoint.md)
only if finding location-related lists or documents is the actual need.
These are choices, not a tested synchronization or data-transfer pipeline.

## Demonstrate and qualify

1. Prepare the [draft Excel demo](../04-demos/excel-five-minute-demo.md).
   Show how a point relates to a source identifier, not a maintenance recommendation.
2. Ask the team which supporting information a staff member needs at that point.
3. Use the [technical checklist](../05-architecture/technical-qualification.md)
   to check geographic quality, identity, client support, and content permissions.
4. If SharePoint is selected, rehearse its official workflow separately using
   approved sample content. No repository-owned SharePoint demo is validated.

## Proposed evaluation criteria

| Test | Proposed acceptance criterion | Responsible role |
|------|-------------------------------|------------------|
| Record matching | Every one of eight approved example points matches the intended asset identifier | GIS specialist |
| Information access | Intended staff can open the selected permitted record; an unauthorized test account cannot | Content owner and administrator |
| User task | A representative staff member finds the agreed record without a specialist explaining each step | Operations owner |
| Data handling | All test copies and any published samples have a documented cleanup action | Data owner |

Record actual results, not assumed time savings. Pause if access cannot be
restricted, identifiers do not match, or the selected client is unsupported.

## Agree on the next action

The operations owner chooses the user task and sample records. The GIS and
Microsoft 365 owners resolve access and support questions before the next meeting.
Use the [evaluation plan](../06-sales-enablement/meeting-templates.md#evaluation-plan)
to assign a date and a cleanup owner.

[Compare integration choices](../02-integration-catalog/compare-integrations.md) |
[All scenarios](README.md)
