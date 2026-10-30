---
title: ArcGIS Connectors for Power Automate
description: A first-pass seller starting point for location-aware flows.
---

## In one sentence

ArcGIS Connectors for Power Automate connect automated workflows to ArcGIS
services so location-related tasks can become part of a business process.

## Conversation card

**30-second explanation:** Find a repeated location-related step in an
existing process. Explore whether an ArcGIS connector can support that specific
step, with the right permissions and an explicit response when it fails.

**Do not promise:** Every action supports API keys, all connectors have the
same license requirements, or a native ArcGIS for Power Apps product exists.

**Agree on a next step:** Ask the process owner, flow maker, and GIS service
owner to select one trigger/action pair and define success and failure handling.
Prepare with the [technical checklist](../../05-architecture/technical-qualification.md).

## Why a customer cares

* Evaluate automation for repeated location-related steps
* Bring geographic information into business records
* Connect a business workflow with the responsible GIS services

## Listen for this

> "Someone manually looks up addresses every time this happens."

> "Our process needs information from GIS."

> "We need to know when a location-related automation fails."

## Questions to ask

* Which trigger and location-related action should the flow handle?
* Which ArcGIS service and connector match that action?
* Who owns credentials, permissions, and failed-flow handling?
* Which environment, subscription, and data restrictions apply?

## See it

Use the actions and examples in the
[Microsoft connector reference](https://learn.microsoft.com/en-us/connectors/arcgis/).
A selected, tested end-to-end demo: **Needs current-source validation**.

## Learn more

* [Esri: Get started with ArcGIS Connectors for Power Automate](https://doc.arcgis.com/en/power-automate/latest/get-started/get-started-with-arcgis-connectors-for-power-automate.htm)
* [Microsoft: ArcGIS connector reference](https://learn.microsoft.com/en-us/connectors/arcgis/)
* [Esri: Set up the ArcGIS Online connector](https://doc.arcgis.com/en/power-automate/latest/get-started/set-up-the-arcgis-online-arcgis-connector.htm)

The current ArcGIS Online connector setup documentation describes sign-in and
API-key authentication. It does not support API-key authentication for triggers,
Survey123 actions, or the Run a data pipeline action. Confirm the requirements
for the exact action rather than assuming API keys work for every flow.

Sources reviewed: 2026-10-30. Premium connector, authentication, and environment
requirements must be checked for the exact connector selected. Do not infer
government-cloud support from commercial documentation or promise a native
ArcGIS for Power Apps product.

## Go deeper

[Power Platform scope](README.md) | [Architecture questions](../../05-architecture/README.md)

For release context, see the
[Power Automate update in Relevant blogs](../../07-resources/relevant-blogs.md#start-with-a-customer-conversation).
