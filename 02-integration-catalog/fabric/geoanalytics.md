---
title: ArcGIS GeoAnalytics for Microsoft Fabric
description: A first-pass seller starting point for spatial analytics at data scale.
---

## In one sentence

ArcGIS GeoAnalytics for Microsoft Fabric brings tools for analyzing location data
into Fabric analytics workflows.

## Conversation card

**30-second explanation:** Some questions require analyzing geographic
relationships, not only displaying points. Explore one such question with the
data engineering and GIS teams, then test it on a representative dataset.

**Do not promise:** Performance or savings without measurement, compatibility
with an untested runtime, or consumption included in another ArcGIS entitlement.

**Agree on a next step:** Have the data platform owner and GIS analyst define
one analysis, safe input data, expected output, and a runtime compatibility test.
Use the [integration comparison](../compare-integrations.md) and
[technical checklist](../../05-architecture/technical-qualification.md).

## Why a customer cares

* Ask geographic questions across large datasets
* Explore relationships between enterprise records and location
* Keep the discussion connected to the customer's analytics investment

## Listen for this

> "We need to analyze operational data and GIS data together."

> "Our location analysis needs to work at a larger scale."

> "Showing the records on a map does not answer the analysis question."

## Questions to ask

* Which geographic relationship matters to the business decision?
* How much data is involved, how often must it update, and how accurate must it be?
* Who owns the Fabric environment and the GIS data?

## See it

Start with the GeoAnalytics section of the
[official Fabric product page](https://www.esri.com/en-us/arcgis/products/arcgis-for-microsoft/arcgis-for-microsoft-fabric).
A selected, tested walkthrough for this repository: **Needs current-source validation**.

## Learn more

[Esri: ArcGIS for Microsoft Fabric](https://www.esri.com/en-us/arcgis/products/arcgis-for-microsoft/arcgis-for-microsoft-fabric).
Source reviewed: 2026-10-30.

Before preparing a notebook-based evaluation, involve the data platform owner.
Esri's [2026-10-08 runtime update](https://community.esri.com/discussion/1721392/arcgis-geoanalytics-for-microsoft-fabric-runtime-1-3-deprecation)
calls for testing GeoAnalytics workloads on Runtime 2.0. Microsoft's current
[runtime documentation](https://learn.microsoft.com/en-us/fabric/data-engineering/runtime-2-0)
identifies 2.0 as the generally available default; its
[lifecycle guidance](https://learn.microsoft.com/en-us/fabric/data-engineering/lifecycle)
places 1.3 in long-term support through March 2027. Do not select an older runtime
because it appears in a blog example. Sources checked: 2026-10-30.

Concise first-pass page. Confirm current setup, availability, commercial terms,
and data requirements. Do not assume GeoAnalytics is included with an ArcGIS
user type or that Maps and GeoAnalytics have identical entitlements.

## Go deeper

[Fabric choices](README.md) | [Architecture questions](../../05-architecture/README.md)

For usage and access-management reading, see
[technical follow-up blogs](../../07-resources/relevant-blogs.md#prepare-a-technical-follow-up).
