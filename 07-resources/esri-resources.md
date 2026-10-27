---
title: Esri Resources
description: Authoritative public Esri documentation for the initial catalog.
---

## Authoritative Esri documentation

### ArcGIS for Power BI

* [Introduction to ArcGIS for Power BI](https://doc.arcgis.com/en/power-bi/latest/get-started/introduction-to-arcgis-for-power-bi.htm)

Esri product documentation introducing ArcGIS for Power BI and its mapping
capabilities. Source reviewed: 2026-10-27.

Consult the current documentation for documented behavior and applicable account
requirements. Do not infer that all ArcGIS capabilities are available in Power BI
or in every deployment environment.

## Personas and user types

The [customer conversation diagram](../assets/diagrams/customer-conversation-map.drawio.svg)
uses Esri terminology where the sources below provide a match. Mapping a label
to a Microsoft workflow is curated seller guidance, not an Esri-defined product
entitlement or an exclusive assignment of people to work.

| Workflow            | Diagram label                 | Basis in Esri documentation                                                                                                                     |
| ------------------- | ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Everyday work       | Viewer / Contributor          | Official user-type names: Viewer views shared content; Contributor can view and edit shared data                                                |
| Data and reporting  | GIS analysts                  | Esri explicitly names GIS analysts as a suitable audience for Professional, and advanced GIS analysts for Professional Plus                     |
| Business processes  | GIS workflow owner (asterisk) | Inferred GIS persona; no directly matching Power Automate workflow-owner persona was established in the sources reviewed                        |
| GIS infrastructure  | GIS administrator (asterisk)  | Inferred GIS infrastructure persona; the documented ArcGIS Online Administrator role does not establish an Azure hosting role or entitlement    |
| Custom applications | Developers                    | Esri explicitly names developers as an audience for Professional Plus; this is not a requirement to buy that user type for .NET SDK development |

The diagram's asterisk means **inferred GIS persona**, not an official Esri
user type or job title. The inference identifies who to involve in discovery.

### Keep personas, user types, and roles separate

A persona describes someone's work. A user type determines the privileges that
can be granted and includes specific apps. A role assigns privileges within that
user type's limits. These are related concepts, not interchangeable labels.

Viewer and Contributor are examples for consuming or editing shared content,
not all everyday-work activities: neither user type allows creating or sharing
items or performing analysis. An authoring or analysis workflow may need a
different user type and appropriate privileges.

Do not treat the diagram as a license-selection tool. Validate the specific
integration, ArcGIS Online versus ArcGIS Enterprise deployment, user type,
role, add-ons, Microsoft licensing, and service requirements separately.
An ArcGIS Online Administrator role does not grant Azure administration rights.

### Authoritative persona and licensing sources

Sources reviewed 2026-10-27; the review date is not a publication or test date:

* [Esri: ArcGIS Online user types](https://doc.arcgis.com/en/arcgis-online/administer/user-types-orgs.htm)
* [Esri: ArcGIS Online member roles](https://doc.arcgis.com/en/arcgis-online/administer/member-roles.htm)
* [Esri: User types overview](https://www.esri.com/en-us/arcgis/products/user-types/overview)

The first source supplies the user-type definitions and the named GIS analyst
and developer personas. The roles source defines organizational administration,
not a validated Azure infrastructure design.

## Curated field guidance

Use this source alongside the [Microsoft documentation](microsoft-resources.md)
and [integration catalog](../02-integration-catalog/README.md). If documentation
is unclear or inconsistent, flag the question rather than inventing an answer.

For current Microsoft 365, Fabric, and Power Automate source links, use the
[integration catalog](../02-integration-catalog/README.md). Select evidence using the
[source policy](source-policy.md); check [visual asset rights](visual-assets.md)
before copying any illustrations.

Additional Esri integration and architecture resources: **Needs current-source validation**.
