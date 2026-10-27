---
title: Visual Asset Inventory
description: Track public visual references separately from permission to redistribute assets.
---

## Link first, copy only with approval

Use original repository artwork for navigation and link to third-party visuals
unless their reuse rights have been validated. The two local conversation
diagrams below are original artwork; the external references remain link-only
source candidates, not an approved image library.

A publicly accessible image is not automatically an approved redistributable
image. Do not copy images from websites, search results, partner decks,
Microsoft or Esri internal documents, or presentations into this public repository.
For third-party imagery, link to the original authoritative page.

## Original repository diagrams

These diagrams use original shapes and text, with no copied artwork, logos, or
screenshots. They are provided under this repository's [MIT License](../LICENSE),
not as official Microsoft or Esri assets. They illustrate seller conversation
choices, not product architecture, technical connections, or data flows.

| Visual                         | Product/topic            | Source                                                                          | Source date        | Public?              | Local copy permitted?       | Used on                                                                                               |
| ------------------------------ | ------------------------ | ------------------------------------------------------------------------------- | ------------------ | -------------------- | --------------------------- | ----------------------------------------------------------------------------------------------------- |
| Customer conversation map      | Seller navigation        | [Editable draw.io SVG](../assets/diagrams/customer-conversation-map.drawio.svg) | Created 2026-10-27 | Public-safe original | Yes, repository MIT License | [Seller front door](../README.md#start-with-the-customer)                                             |
| Microsoft 365 workflow choices | Excel, Teams, SharePoint | [Editable draw.io SVG](../assets/diagrams/microsoft-365-workflows.drawio.svg)   | Created 2026-10-27 | Public-safe original | Yes, repository MIT License | [Microsoft 365 landing](../02-integration-catalog/microsoft-365/README.md#choose-a-familiar-workflow) |

Each `.drawio.svg` file contains both the rendered SVG and its editable draw.io
model. Open it in VS Code using the Draw.io Integration extension. Keep the
`.drawio.svg` extension when saving so the editable model and preview stay
together. Check the rendered result before committing.

The adjacent Markdown tables provide text alternatives and navigation.
The customer diagram's labels follow the
[Esri persona and user-type mapping](esri-resources.md#personas-and-user-types).
Asterisks identify inferred GIS personas; the diagram is not a licensing guide.

## Public visual references

| Visual                     | Product/topic   | Source                                                                                                           | Source date                             | Public?          | Local copy permitted?    | Used on                                                                               |
| -------------------------- | --------------- | ---------------------------------------------------------------------------------------------------------------- | --------------------------------------- | ---------------- | ------------------------ | ------------------------------------------------------------------------------------- |
| Product-page illustrations | Microsoft 365   | [Esri product page](https://www.esri.com/en-us/arcgis/products/arcgis-for-microsoft/arcgis-for-microsoft-365)    | Not stated; reviewed 2026-10-27         | Yes, source page | Not validated; link only | [Microsoft 365 landing](../02-integration-catalog/microsoft-365/README.md), as a link |
| Product-page illustrations | Fabric          | [Esri product page](https://www.esri.com/en-us/arcgis/products/arcgis-for-microsoft/arcgis-for-microsoft-fabric) | Not stated; reviewed 2026-10-27         | Yes, source page | Not validated; link only | [Fabric product pages](../02-integration-catalog/fabric/README.md), as source links   |
| Tutorial screenshots       | Power BI        | [Microsoft walkthrough](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualizations-arcgis)       | Updated 2026-08-24; reviewed 2026-10-27 | Yes, source page | Not validated; link only | [Power BI](../02-integration-catalog/fabric/power-bi.md), as a walkthrough link       |

Public status applies to the referenced page, not blanket permission for every
asset on it. No third-party images are embedded, downloaded, or redistributed here.

## Visuals still to select

* One strong hero visual for the seller front door
* Microsoft 365 integration images with validated reuse rights
* Fabric integration images with validated reuse rights
* Power BI examples appropriate to a seller conversation
* Azure architecture visuals for a validated design
* Demo screenshots from a current, safe, reproducible walkthrough

Selection, freshness, and reuse approval for these assets:
**Needs current-source validation**. Do not manufacture or copy images to fill space.

## Before adding an image file

Record the exact asset, owner, public source, source date, license or written
reuse permission, attribution requirements, and intended use. Verify that the
permission covers public GitHub redistribution and any proposed modification.
Record the approval evidence using a public-safe reference; do not expose
internal correspondence.

Confirm that the image contains no credentials, private tenant or customer
details, confidential material, or stale product UI. Follow the
[source policy](source-policy.md) and [contribution workflow](../CONTRIBUTING.md).

Back to the [seller front door](../README.md).
