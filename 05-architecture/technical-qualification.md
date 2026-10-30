---
title: Prepare the Technical Discussion
description: Qualification questions, product-specific checks, and role-based handoffs.
---

## Begin with a decision, not a design

Use this checklist after agreeing on a customer question. Record answers in the
customer's approved private system, not in this public repository.
Unanswered questions are open requirements, not reasons to assume support.

## Questions for every integration

| Area | Establish before an evaluation | Responsible role |
|------|--------------------------------|------------------|
| Business purpose | One decision, intended users, baseline, success measure, and review date | Business owner |
| Data | Source, permission to use it, location quality, update frequency, and reuse rights | Data owner and GIS specialist |
| Data movement | What leaves the source system, which services receive it, where it is stored, and retention | Solution engineer and security team |
| Identity and access | Accounts, tenant/deployment, approved authentication, minimum permissions, and revocation | Microsoft administrator and GIS administrator |
| Licensing | Current ArcGIS user types, roles, add-ons or consumption, plus Microsoft product requirements | Licensing specialists and account teams |
| Environment | Region, commercial or government cloud, supported versions, network policy, and availability evidence | Workload owner and security team |
| Sharing | Who can see or change content, external access, and any restrictions on publication | Content owner and platform administrator |
| Operations | Updates, monitoring, failure handling, recovery, support ownership, and cleanup | Service owner |

A persona is not a license. Use the
[Esri user-type and role guidance](../07-resources/esri-resources.md#personas-and-user-types)
and current product documentation; do not derive entitlement from the diagram.
Commercial documentation does not establish government-cloud or regional support.

## Product-specific checks

| Integration | Confirm with the technical team | Evidence starting point |
|-------------|---------------------------------|-------------------------|
| Excel | Supported client/add-in, numeric coordinates, guest versus signed-in access, workbook sharing, and services receiving data | [Excel card and sources](../02-integration-catalog/microsoft-365/excel.md#learn-more) |
| Teams | App approval, meeting/channel scope, content permissions, and access for external participants | [Teams card and sources](../02-integration-catalog/microsoft-365/teams.md#learn-more) |
| SharePoint | Supported deployment, web-part installation, list/document permissions, geographic data preparation, and app version | [SharePoint card and sources](../02-integration-catalog/microsoft-365/sharepoint.md#learn-more) |
| Power BI | Visual enablement, source and report permissions, account mode, consent, refresh, and supported sharing/embedding method | [Power BI card and sources](../02-integration-catalog/fabric/power-bi.md#learn-more) |
| Maps for Fabric | Current release status, tenant/workload enablement, capacity, data permissions, and user types | [Maps card and preview boundary](../02-integration-catalog/fabric/maps-for-fabric.md#learn-more) |
| GeoAnalytics | Supported runtime, data scale, authentication, separate consumption, library compatibility, and notebook testing | [GeoAnalytics card and runtime guidance](../02-integration-catalog/fabric/geoanalytics.md#learn-more) |
| Power Automate | Exact connector/action, authentication limits, premium requirements, trigger support, retry behavior, and secret storage | [Connector card and sources](../02-integration-catalog/power-platform/power-automate.md#learn-more) |
| Enterprise on Azure | Version-specific support, topology, network boundaries, resilience, backups, licensing, and operational responsibility | [Azure assessment](../02-integration-catalog/azure/arcgis-enterprise.md#learn-more) |
| Pro on Azure | Supported desktop configuration, graphics, responsiveness, storage, extensions, and licensing | [Desktop assessment](../02-integration-catalog/azure/arcgis-pro.md#learn-more) |
| Maps SDK for .NET | SDK/platform versions, identity, network/offline requirements, distribution, licensing, and application maintenance | [Developer card and sources](../02-integration-catalog/developer/maps-sdk-dotnet.md#learn-more) |

## Keep release status separate from our testing

| Record | What it establishes | What it does not establish |
|--------|---------------------|----------------------------|
| Vendor release status with dated authoritative source | General availability, preview, or support status in that source | Customer entitlement or successful deployment |
| Repository test record with client/version/date/results | What a maintainer actually ran in a stated environment | Support for other tenants, regions, or configurations |
| Customer evaluation evidence in an approved private system | Whether that customer met agreed success criteria | Permission to publish customer details or claim universal results |

Use "Not verified" rather than inferring a release status.
The Excel and Power BI runbooks are currently **drafted, not product-tested**.
Azure designs and customer-specific suitability still need source validation.

## Make the handoff explicit

Bring the business owner, an Esri solution engineer, the customer's GIS owner,
and the Microsoft workload owner together. Add security, licensing, data,
cloud, or application specialists as required.
Use roles rather than named contacts so the handoff works across countries.

Proceed only when the team agrees on safe data, authorized access, evidence for
required capabilities, an evaluation owner, and a cleanup plan. Otherwise record
the blocker and assign someone to resolve it. Do not promise production dates,
cost savings, compliance, or support without evidence.

Use the [evaluation and follow-up templates](../06-sales-enablement/meeting-templates.md),
[Excel worked example](excel-evaluation.md), or
[Power BI worked example](power-bi-evaluation.md).
