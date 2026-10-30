---
title: Synthetic Service Location Data
description: Original sample data for Excel and Power BI meeting demonstrations.
---

## Use safe demonstration data

[service-locations.csv](service-locations.csv) is original synthetic data supplied
under the repository's [MIT License](../../LICENSE). No external dataset was
copied. Site names, area assignments, and request counts are fictional.
Coordinates are illustrative points, not identified facilities or customer sites.
Created: 2026-10-30.

| Field | Meaning | Import type |
|-------|---------|-------------|
| SiteID | Unique fictional site identifier | Text |
| SiteName | Fictional display name | Text |
| Area | Arbitrary North or South group, not an administrative boundary | Text |
| Latitude | WGS 84 latitude in decimal degrees | Decimal number |
| Longitude | WGS 84 longitude in decimal degrees | Decimal number |
| Requests | Fictional count for the same unspecified example period | Whole number |

## Expected data checks

* Eight distinct SiteID values and eight distinct coordinate pairs
* Four North records totaling 300 requests
* Four South records totaling 200 requests
* 500 requests overall, with no missing values

These are dataset checks, not proof that either product walkthrough has run.
Use a period as the decimal separator when importing; check import locale if
your regional settings use a comma. Keep longitude and latitude in separate
numeric columns and do not reverse them.

## What this example cannot establish

There are no service boundaries, population counts, capacity figures, travel
times, or actual demand records. A point map cannot establish service coverage,
fairness, where to invest, or business savings. Use it to identify questions for
further analysis, not to make a site recommendation.

Use the [Excel runbook](../excel-five-minute-demo.md) or
[Power BI runbook](../power-bi-five-minute-demo.md).
