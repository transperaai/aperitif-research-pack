---
id: DS-26
title: "SEO: performance forecasting tool"
team: "SEO"
bundle: "PPC performance"
status: "Recommended – build 14, Forecasting (with DS-25)"
coverage: addressed
source_type: "Austin addition"
opportunities: []
earlier_ideas: []
written_sources: []
problems_fixed: []
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["LS-PP16"]
pain_points_interviewer_raised_or_inferred: ["LS-PP16 (interviewer-raised)"]
value: "Better planning, realistic expectations"
---

# DS-26 · SEO: performance forecasting tool

*SEO team: forecasting tool for each client's organic performance.*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | SEO |
| Status | Recommended – build 14, Forecasting (with DS-25) |
| Source type | Austin addition – Austin – new; no SEO forecasting pain point raised (LS-PP16 is interviewer-raised) |
| Opportunities | – |
| Earlier ideas | – |
| Fixes | none |
| Also helps | – |
| Pain points cited | [LS-PP16](../pain-points/README.md#ls-pp16) (interviewer-raised) |
| Written source | – |
| Value | Better planning, realistic expectations |

## Vision

> **The same shared forecasting skill as [DS-25](ds-25-ppc-performance-forecasting-tool.md), for organic:** traffic and ranking scenarios from GA4, Search Console and Ahrefs, with seasonality built in, so the team plans content and links and sets client expectations against a forecast. Together with DS-25 it is build 14, Forecasting.


**Team:** SEO. **Decision:** the SEO version – forecasts each client's organic performance from history, seasonality, search trends, economic and industry movements, and known algorithm changes.

## How it works

1. The shared Claude skill pulls each client's GA4, Search Console and Ahrefs history ([DS-22](ds-22-seo-automated-monday-client-performance-check.md)'s data).
2. It applies seasonality and the manager's assumptions.
3. It returns low / expected / high scenarios for traffic and rankings per client, with the reasoning, and flags expected dips (e.g. seasonal low, demand falling). Forecasts are saved to the client brain and checked against actuals.
4. Feeds reviews ([DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md)) and client expectation setting ([DS-28](ds-28-client-comms-assistant-monthly-updates-and-expectation.md)).

## Problems it fixes and the evidence

- Related: *"it probably wouldn't comment on seasonality. That requires intervention."* – Laura, SEO Director, on reports ([LS-PP16](../pain-points/README.md#ls-pp16), *raised by the interviewer*).
- No SEO forecasting pain point was raised directly – **Austin's addition**.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| SEO clients with a current forecast | 0 | 100% of focus clients |
| Forecast accuracy | Not tracked | Baseline, then improve |

## Value

**Value: better planning, fewer surprises.** Organic forecasts per client let the team set realistic expectations and plan content and links against them, as [DS-25](ds-25-ppc-performance-forecasting-tool.md) does for paid.

**Goals:** good performance · trust · good customer service

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Austin's suggestion; weak direct evidence.
