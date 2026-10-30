---
title: Which Integration Should We Explore
description: Compare familiar workflows without treating adjacent products as interchangeable.
---

## Start with the work, not the product name

These are conversation starting points, not universal recommendations.
More than one integration may be relevant, but start an evaluation with one
question and one responsible team.

## Compare Fabric mapping, analytics, and reporting

| Question | Start with | What is different | Involve |
|----------|------------|-------------------|---------|
| "How do geographic relationships affect large datasets?" | [GeoAnalytics for Fabric](fabric/geoanalytics.md) | Spatial analysis in analytics workflows, not the Power BI map visual | Data engineer or scientist and GIS analyst |
| "What can a map reveal about our Fabric data?" | [Maps for Fabric](fabric/maps-for-fabric.md) | Mapping within Fabric; dated public-preview announcement requires current-status verification | Fabric administrator and GIS owner |
| "Where do the measures in our report vary?" | [ArcGIS for Power BI](fabric/power-bi.md) | Mapping inside reports and dashboards; not a requirement to adopt the other workloads | Report author and GIS owner |

Do not assume shared licensing, availability, capacity requirements, or support.
The [Fabric landing page](fabric/README.md) links current sources and boundaries.
No comparative performance or cost claim is made here.

## Compare everyday Microsoft workflows

| Customer need | Start with | Do not confuse it with |
|---------------|------------|------------------------|
| Explore rows in a workbook geographically | [Excel](microsoft-365/excel.md) | A centrally governed reporting or publishing design |
| Discuss and explore ArcGIS content with colleagues | [Teams](microsoft-365/teams.md) | Unrestricted access to private maps or an automatic license for guests |
| Connect organizational lists or documents to places | [SharePoint](microsoft-365/sharepoint.md) | Permission to expose every document to every map viewer |
| Report geographic context with business measures | [Power BI](fabric/power-bi.md) | The same account, sharing, and refresh rules as an Excel workbook |

## When the need is different

| Customer need | Start with | First boundary to check |
|---------------|------------|-------------------------|
| Automate a repeated location-related step | [Power Automate](power-platform/power-automate.md) | Exact connector/action, authentication, and failure handling |
| Assess enterprise GIS infrastructure | [Enterprise on Azure](azure/arcgis-enterprise.md) | Version-specific supported design; deployment evidence remains pending |
| Assess computing for GIS desktop specialists | [Pro on Azure](azure/arcgis-pro.md) | Supported desktop, graphics, data access, and licensing |
| Build an application around a specific user task | [Maps SDK for .NET](developer/maps-sdk-dotnet.md) | Development effort, platform support, distribution, and maintenance |

Next: select the product page's conversation card, prepare the
[technical questions](../05-architecture/technical-qualification.md), and agree
on an [evaluation plan](../06-sales-enablement/meeting-templates.md#evaluation-plan).
