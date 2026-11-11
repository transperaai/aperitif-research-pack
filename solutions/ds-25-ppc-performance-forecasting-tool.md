---
id: DS-25
title: "PPC: performance forecasting tool"
team: "PPC"
bundle: "PPC performance"
status: "Recommended – build 14, Forecasting (with DS-26)"
coverage: addressed
source_type: "Austin addition"
opportunities: ["O-02 (WS-O09 forecasting prompt only)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-04"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["WS-PP12", "WS-PP13"]
pain_points_interviewer_raised_or_inferred: ["WS-PP13 (inferred)"]
value: "Better budget decisions, fewer surprises"
---

# DS-25 · PPC: performance forecasting tool

*PPC team: forecasting tool for each client from history, seasonality and outside signals.*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | PPC |
| Status | Recommended – build 14, Forecasting (with DS-26) |
| Source type | Austin addition – Austin – new; evidence is one person (WS-PP12, WS-PP13 detected) |
| Opportunities | [O-02](../opportunities/README.md#o-02) (WS-O09 forecasting prompt only) |
| Earlier ideas | – |
| Fixes | [P-04 Client-call prep takes longer than the call](../problems/p-04-client-call-prep-takes-longer-than-the.md) |
| Also helps | – |
| Pain points cited | [WS-PP12](../pain-points/README.md#ws-pp12), [WS-PP13](../pain-points/README.md#ws-pp13) (inferred) |
| Written source | – |
| Value | Better budget decisions, fewer surprises |

## Vision

> **Every manager can forecast a client's results in minutes using one shared method.** Change a budget, a season or a market assumption and see the scenarios, so planning and client expectations rest on data, not gut feel. It turns the performance director's own forecasting approach (his Gemini workflow) into a shared Claude skill the whole team uses. Shared with [DS-26](ds-26-seo-performance-forecasting-tool.md) for organic; together they are build 14, Forecasting.

## Decision

**Team:** PPC. **Decision:** a forecasting tool that predicts each client's paid performance from history, seasonality, economic trends and predictions, and other outside factors.

## How it works

1. A shared Claude skill pulls each client's spend and results history (spend, conversions, CPA/ROAS) through Windsor.ai.
2. It applies seasonality and the manager's assumptions (budget, season, market); economic and trend data can be added later – the first version uses history and seasonality only.
3. It returns low / expected / high scenarios per client and channel, with the reasoning, and flags where results are likely to dip.
4. Every forecast is saved to the client brain, and a monthly check compares forecasts with actuals.
5. Used for budget planning, proposals ([DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md)) and setting client expectations ([DS-28](ds-28-client-comms-assistant-monthly-updates-and-expectation.md)).

## Problems it fixes and the evidence

- [Client-call prep takes longer than the call](../problems/p-04-client-call-prep-takes-longer-than-the.md) – forecasting part:
  - *"I used to take like hours doing this and Gemini did it in like 15 minutes"* – Wendlley Simoes, Performance Marketing Director, on forecasting ([WS-PP12](../pain-points/README.md#ws-pp12), stated). External shocks also make history unreliable for forecasting.
  - The director's Gemini forecasting is a personal workflow, not shared with the team ([WS-PP13](../pain-points/README.md#ws-pp13), *inferred*).
- Source opportunity: WS-O09 – share the director's forecasting approach as a standard for all managers.

## Future state

Every PPC manager can produce a client forecast in minutes, using the same method, with outside factors built in. The director's method is no longer a personal workflow, and forecasts are checked against actuals, so accuracy is known and improves.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Managers producing forecasts with the shared skill | 1 (the performance director) | All PPC and SEO managers |
| Forecast accuracy (actual vs forecast) | Not tracked | Baseline, then improve |

## Value

**Value: better decisions, fewer surprises.** The team can run scenarios on budget changes, seasonality and market shifts before committing, so budget conversations with clients are backed by a forecast and results land closer to what was promised.

**Goals:** good performance · trust · good customer service

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Mainly Austin's suggestion; evidence is one person (the performance director), who has largely solved it personally with Gemini.
- Needs Windsor.ai (build 1) for PPC history and the client brain (build 2) to store forecasts.
- Economic and trend data sources (if any) are chosen later; the first version uses history and seasonality only.
