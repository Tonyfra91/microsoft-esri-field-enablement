---
title: Microsoft + Esri Field Enablement
description: Start with a customer need and find the right Microsoft and ArcGIS conversation.
---

## Location intelligence where work happens

Your customer already makes important decisions using Microsoft and ArcGIS.
Microsoft provides the cloud, productivity, data, analytics, AI, and business
application platforms where people work. ArcGIS adds location intelligence:
context that helps people understand not only what is happening, but where it
is happening and why location matters.

The conversation is bigger than putting maps into Microsoft. It is about bringing
**business data + operational data + location context** together to answer:

| What is happening?   | Where is it happening?   | Why does location matter?   | What should we do next?      |
| :------------------: | :----------------------: | :-------------------------: | :--------------------------: |
| Understand demand    | See the places involved  | Explore local conditions    | Choose an action to evaluate |

ArcGIS integrations bring location context into Microsoft 365, Microsoft Fabric,
Power BI, and Power Automate workflows. Azure is also a conversation about the
infrastructure supporting GIS. These are different starting points, not one
product or a promise that every capability works in every environment.
Explore the source-backed pages below before making a recommendation.

Built for Esri subsidiaries, distributors, sellers, solution engineers, Microsoft
account and partner teams, and partners who know one platform better than the other.

**Five minutes before a meeting?** Open the
[Seller Quick Start](01-start-here/seller-quick-start.md).

## Start with the customer

You do not need to memorize the ArcGIS product portfolio. Find out where your
customer already works and which decision or process needs to improve.
The value statements below are conversation hypotheses to test with the customer,
not guaranteed outcomes.

![Illustrative Esri-aligned labels: Viewer and Contributor for viewing or editing shared content in everyday work; GIS analysts for data and reporting; inferred GIS workflow owner for business processes; inferred GIS administrator for infrastructure; developers for custom applications. These are not licensing recommendations.](assets/diagrams/customer-conversation-map.drawio.svg)

Conversation guide, not a technical architecture. Branches show choices, not
data flows. Labels use Esri user-type names or documented personas; an asterisk
marks an inferred GIS persona. These are illustrative, not license recommendations.
People may span workflows. See the [persona definitions and sources](07-resources/esri-resources.md#personas-and-user-types).
Use the table below for questions and clickable starting pages.
[Open or edit the draw.io diagram](assets/diagrams/customer-conversation-map.drawio.svg).

| If your customer is...                                     | Start the conversation with...                                    | Customer value                                         | Explore                                                                   |
| ---------------------------------------------------------- | ----------------------------------------------------------------- | ------------------------------------------------------ | ------------------------------------------------------------------------- |
| Working heavily in Excel                                   | "Which spreadsheet decisions depend on location?"                 | See geographic patterns behind rows                    | [Excel](02-integration-catalog/microsoft-365/excel.md)                    |
| Collaborating in Microsoft Teams                           | "How do people discuss maps together?"                            | Bring geographic context into team discussions         | [Teams](02-integration-catalog/microsoft-365/teams.md)                    |
| Managing content through SharePoint                        | "Which lists or documents relate to places?"                      | Find and understand content by location                | [SharePoint](02-integration-catalog/microsoft-365/sharepoint.md)          |
| Building Power BI dashboards                               | "What would location add to your reporting?"                      | Put business measures in geographic context            | [Power BI](02-integration-catalog/fabric/power-bi.md)                     |
| Building an enterprise data foundation in Microsoft Fabric | "Where do business and GIS data need to meet?"                    | Explore enterprise data with geographic context        | [Fabric](02-integration-catalog/fabric/README.md)                         |
| Needing large-scale spatial analytics in Fabric            | "Which location questions are hard to answer at your data scale?" | Analyze geographic relationships across large datasets | [GeoAnalytics](02-integration-catalog/fabric/geoanalytics.md)             |
| Automating business processes with Power Automate          | "Which repeated steps depend on an address or location?"          | Evaluate location-aware automation                     | [Power Automate](02-integration-catalog/power-platform/power-automate.md) |
| Running ArcGIS Enterprise on Azure                         | "What must your GIS platform deliver for the business?"           | Align GIS operations with cloud requirements           | [Enterprise on Azure](02-integration-catalog/azure/arcgis-enterprise.md)  |
| Running ArcGIS Pro using Azure infrastructure              | "How do GIS specialists access the computing they need?"          | Evaluate workstation access and capacity               | [Pro on Azure](02-integration-catalog/azure/arcgis-pro.md)                |

## Explore the integrations

Choose a workflow, then use its page to prepare a question and find official
learning material. Microsoft 365 has the most developed seller landing page in
this first pass. Other families have concise starting pages, not validated
implementation guides. Grouping Power BI under Fabric is a navigation choice,
not a requirement to adopt other Fabric workloads.

| Integration                                                                                     | Microsoft environment    | What it enables                                             | Best conversation starter                                | Go deeper                                                                                      |
| ----------------------------------------------------------------------------------------------- | ------------------------ | ----------------------------------------------------------- | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| [ArcGIS for Microsoft 365](02-integration-catalog/microsoft-365/README.md)                      | Excel, Teams, SharePoint | Location context in everyday work                           | "Where do employees already work with location data?"    | [Choose a workflow](02-integration-catalog/microsoft-365/README.md#choose-a-familiar-workflow) |
| [ArcGIS for Excel](02-integration-catalog/microsoft-365/excel.md)                               | Excel                    | Explore spreadsheet data geographically                     | "What is hidden in those address columns?"               | [Excel sources](02-integration-catalog/microsoft-365/excel.md#learn-more)                      |
| [ArcGIS for Teams](02-integration-catalog/microsoft-365/teams.md)                               | Teams                    | Share and discuss interactive ArcGIS content                | "How do teams explore a map together?"                   | [Teams sources](02-integration-catalog/microsoft-365/teams.md#learn-more)                      |
| [ArcGIS for SharePoint](02-integration-catalog/microsoft-365/sharepoint.md)                     | SharePoint               | Maps and location context for lists and documents           | "Which content is easier to find by place?"              | [SharePoint sources](02-integration-catalog/microsoft-365/sharepoint.md#learn-more)            |
| [ArcGIS for Microsoft Fabric](02-integration-catalog/fabric/README.md)                          | Fabric and Power BI      | Mapping, spatial analytics, and reporting conversations     | "How will GIS data inform enterprise analytics?"         | [Compare starting points](02-integration-catalog/fabric/README.md#choose-the-question-first)   |
| [ArcGIS GeoAnalytics for Microsoft Fabric](02-integration-catalog/fabric/geoanalytics.md)       | Fabric                   | Spatial analytics on large datasets                         | "Which geographic relationships do you need to analyze?" | [GeoAnalytics sources](02-integration-catalog/fabric/geoanalytics.md#learn-more)               |
| [ArcGIS Maps for Microsoft Fabric](02-integration-catalog/fabric/maps-for-fabric.md)            | Fabric                   | Map Fabric data with geographic context                     | "What would a map reveal about your data?"               | [Maps sources](02-integration-catalog/fabric/maps-for-fabric.md#learn-more)                    |
| [ArcGIS for Power BI](02-integration-catalog/fabric/power-bi.md)                                | Power BI                 | Mapping in reports and dashboards                           | "Where do your business measures vary?"                  | [Power BI sources](02-integration-catalog/fabric/power-bi.md#learn-more)                       |
| [ArcGIS for Power Platform](02-integration-catalog/power-platform/README.md)                    | Power Automate initially | Location-aware workflow conversations                       | "Which manual location steps repeat?"                    | [Scope and boundaries](02-integration-catalog/power-platform/README.md)                        |
| [ArcGIS Connectors for Power Automate](02-integration-catalog/power-platform/power-automate.md) | Power Automate           | Connect flows to ArcGIS services                            | "Could a flow handle this location task?"                | [Connector sources](02-integration-catalog/power-platform/power-automate.md#learn-more)        |
| [ArcGIS + Azure](02-integration-catalog/azure/README.md)                                        | Azure                    | GIS infrastructure assessment                               | "What are your GIS hosting requirements?"                | [Assessment boundaries](02-integration-catalog/azure/README.md)                                |
| [ArcGIS Enterprise on Microsoft Azure](02-integration-catalog/azure/arcgis-enterprise.md)       | Azure                    | Enterprise GIS hosting conversation; validation pending     | "Who owns availability and operations?"                  | [Validation needs](02-integration-catalog/azure/arcgis-enterprise.md#learn-more)               |
| [ArcGIS Pro on Microsoft Azure](02-integration-catalog/azure/arcgis-pro.md)                     | Azure infrastructure     | GIS desktop infrastructure conversation; validation pending | "What computing experience do specialists need?"         | [Validation needs](02-integration-catalog/azure/arcgis-pro.md#learn-more)                      |
| [Developer integrations](02-integration-catalog/developer/README.md)                            | .NET applications        | Custom application conversations                            | "Does the need require a purpose-built application?"     | [Developer starting point](02-integration-catalog/developer/maps-sdk-dotnet.md)                |
| [ArcGIS Maps SDK for .NET](02-integration-catalog/developer/maps-sdk-dotnet.md)                 | .NET                     | Custom mapping application development                      | "What must users do beyond a standard app?"              | [SDK sources](02-integration-catalog/developer/maps-sdk-dotnet.md#learn-more)                  |

## Move from a question to a next step

Customer need -> Relevant integration -> Official walkthrough -> Specialist review

1. Ask the [discovery questions](01-start-here/customer-discovery-questions.md).
2. Try the [Government conversation](03-scenarios/government.md) as a hypothetical example.
3. Pick one [official learning resource](04-demos/README.md) using public or synthetic data.
4. Involve a solution engineer for [architecture questions](05-architecture/README.md).
5. Agree on an owner, an evaluation goal, and the next conversation.

## Browse the repository

* [Start here: Microsoft + Esri story](01-start-here/microsoft-esri-story.md)
* [Seller Quick Start](01-start-here/seller-quick-start.md)
* [Customer discovery questions](01-start-here/customer-discovery-questions.md)
* [Integration catalog](02-integration-catalog/README.md)
* [Government scenario](03-scenarios/government.md)
* [Demos](04-demos/README.md)
* [Architecture](05-architecture/README.md)
* [Sales enablement](06-sales-enablement/README.md)
* [Microsoft resources](07-resources/microsoft-resources.md)
* [Esri resources](07-resources/esri-resources.md)
* [Source policy](07-resources/source-policy.md)
* [Visual asset inventory](07-resources/visual-assets.md)
* [Partner enablement resources](07-resources/partner-enablement.md)
* [Localization](08-localization/README.md)

## How to read this guidance

* Official documentation is the authority for product behavior, prerequisites,
  limitations, licensing, availability, and support.
* Curated field guidance consists of suggested questions, candidate use cases,
  and evaluation steps. It is not a product guarantee or an endorsement by
  Microsoft or Esri.
* **Needs current-source validation** means evidence is pending, not a capability
  or customer commitment. See the [source policy](07-resources/source-policy.md).

The catalog is a starting portfolio, not an exhaustive inventory or a maturity
certification. No repository-owned demos or validated architectures are included.
Source review dates record a documentation check, not a tested deployment.
AI, agents, MCP, Copilot extensibility, and roadmap concepts are not part of this
initial navigator. Do not infer commitments or equivalent maturity.

## Public content only

Do not submit Microsoft Confidential information, internal-only materials,
private meeting details, unreleased roadmap information, non-public pricing,
credentials, customer-sensitive data, or unsupported product claims.

See [contribution guidance](CONTRIBUTING.md) and the [MIT License](LICENSE).
Third-party documentation, products, and linked assets retain their own terms.
