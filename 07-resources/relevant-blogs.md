---
title: Relevant Blogs
description: Public Microsoft and Esri integration reading for customer conversations and technical follow-up.
---

## Choose reading for your customer conversation

Start with where the customer works and the question they need to answer.
Choose one relevant article, rather than trying to learn every integration.

These are public, Esri-authored posts on Esri Community. Author badges, article
content, and publication dates were checked on **2026-10-30**. The publication
date is when the post appeared, not a deployment test date or a product support
guarantee. Some useful articles are from 2025; limitations are noted below.

Blogs provide examples and context. Use the linked
[integration pages](../02-integration-catalog/README.md) and current product
documentation to confirm capabilities, licensing, availability, and support.
No screenshots, recordings, or third-party article content are copied here.

## Start with a customer conversation

| Blog or update                                                                                                                                                                                                      | Published   | Why read it                                                                                                                                                                            | Ask the customer                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| [Bringing GIS into Everyday Forestry Workflows with ArcGIS and Microsoft 365](https://community.esri.com/discussion/1700255/bringing-gis-into-everyday-forestry-workflows-with-arcgis-and-microsoft-365)            | 2026-05-14  | A workflow-led example connecting Excel, SharePoint, and Teams. It is an Esri webinar recap, not a validated customer reference or a government solution.                              | "Where do employees already review data, find documents, and discuss places?" |
| [ArcGIS for SharePoint: October 2026 change log, version 2026.2.0.0](https://community.esri.com/discussion/1721938/change-log-and-updates-october-2026-arcgis-for-sharepoint-v-2026-2-0-0)                          | 2026-10-23  | Explains release-specific changes, including adding geographic files and improving map and content workflows. Check the installed version before showing a feature.                    | "What location data or documents do people need to use from SharePoint?"      |
| [What's new in the 2026.2 release of ArcGIS Connectors for Power Automate](https://community.esri.com/discussion/1706137/what-s-new-in-the-2026-2-release-of-arcgis-connectors-for-power-automate)                  | 2026-06-03  | Introduces authentication and workflow updates. API-key support has action and trigger limits; it is not permission to automate every task without a user account.                     | "Which location task repeats, and who should be allowed to run it?"           |
| [Avoid Broken Maps: Validating ArcGIS for Power BI Before Embed and Publish to Web](https://community.esri.com/discussion/1689131/avoid-broken-maps-validating-arcgis-for-power-bi-before-embed-and-publish-to-web) | 2026-03-06  | Explains why report authors should validate a map before embedding or public publishing. The article discusses version 2025.3; recheck current documentation and sharing requirements. | "Who needs to see this report, and should access be restricted?"              |

Continue with [Microsoft 365](../02-integration-catalog/microsoft-365/README.md),
[Power Automate](../02-integration-catalog/power-platform/power-automate.md), or
[Power BI](../02-integration-catalog/fabric/power-bi.md).
Public publishing is not appropriate for private or customer-sensitive data.

## Prepare a technical follow-up

Bring the relevant solution engineer, GIS owner, and Microsoft workload owner
into these conversations. Sellers do not need to reproduce the technical steps.

| Blog or update                                                                                                                                                                             | Published   | Why read it                                                                                                     | Check before using                                                                                                                                                                                                                                                                 |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ArcGIS GeoAnalytics for Microsoft Fabric: Runtime 1.3 Deprecation](https://community.esri.com/discussion/1721392/arcgis-geoanalytics-for-microsoft-fabric-runtime-1-3-deprecation)        | 2026-10-08  | Identifies a runtime migration task for teams preparing or maintaining analytics notebooks.                     | Confirm Microsoft's current [runtime lifecycle](https://learn.microsoft.com/en-us/fabric/data-engineering/lifecycle) and [Runtime 2.0 guidance](https://learn.microsoft.com/en-us/fabric/data-engineering/runtime-2-0), then test existing workloads before changing environments. |
| [Understanding core-hours in ArcGIS GeoAnalytics for Microsoft Fabric](https://community.esri.com/discussion/1657510/understanding-core-hours-in-arcgis-geoanalytics-for-microsoft-fabric) | 2025-11-05  | Helps explain usage measurement and why GeoAnalytics core-hours are different from Fabric capacity consumption. | Do not reuse the article's Runtime 1.3 example as a current setup recommendation or its example consumption as a cost estimate. Confirm current commercial terms separately.                                                                                                       |
| [Using API key-based authentication with GeoAnalytics for Fabric](https://community.esri.com/discussion/1657491/using-api-key-based-authentication-with-geoanalytics-for-fabric)           | 2025-11-04  | A technical starting point for discussing access management with the data platform team.                        | Confirm current product instructions and organizational secret-management policies. Never place keys or credentials in notebooks shared through this repository.                                                                                                                   |

Continue with [GeoAnalytics](../02-integration-catalog/fabric/geoanalytics.md)
and the [architecture questions](../05-architecture/README.md).

## Preview reading: check current status

| Article                                                                                                                                                                               | Published   | Why read it                                                                 | Availability boundary                                                                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Announcing ArcGIS Maps for Microsoft Fabric, now in public preview](https://community.esri.com/discussion/1670323/announcing-arcgis-maps-for-microsoft-fabric-now-in-public-preview) | 2025-12-04  | Introduces the mapping workload and its intended use alongside Fabric data. | This is a dated public-preview announcement, not evidence of current general availability. Do not reuse its preview pricing, planned features, or installation details as current commitments. |

Check the [Maps for Fabric page](../02-integration-catalog/fabric/maps-for-fabric.md)
and current Esri product information before positioning an evaluation.
Current release status and customer-specific availability:
**Needs current-source validation**.

## Keep the reading list current

Prefer a small set of useful, verified articles to a long list of search results.
This is not a complete list of Microsoft and Esri publications.
No separate Teams, Azure, or .NET blog is selected in this pass; use their
[integration pages](../02-integration-catalog/README.md) for documentation.
The Microsoft 365 workflow article includes Excel and Teams examples.

Before adding or reusing an article:

* Confirm the author or publisher, publication date, and public destination
* Explain the customer question the article helps answer
* Check the current product documentation, not only the article's age
* Separate preview announcements and technical instructions from seller examples
* Keep old UI, sample runtimes, pricing, and roadmap statements out of current claims
* Mark unresolved evidence **Needs current-source validation**

Some blog sites could not be reviewed through automated access during this
check. Only articles whose content could be reviewed are listed above; an
unreviewed article is not treated as verified because another post links to it.
Follow the [source policy](source-policy.md) and [visual asset rules](visual-assets.md).

Return to the [Seller Quick Start](../01-start-here/seller-quick-start.md),
[Microsoft + Esri story](../01-start-here/microsoft-esri-story.md), or
[seller front door](../README.md).
