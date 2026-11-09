---
id: DS-25
title: "PPC: performance forecasting tool"
team: "PPC"
bundle: "PPC performance"
status: "Added – cost TBC"
ledger_status: addressed
source_type: "Austin addition"
opportunities: ["O-02 (WS-O09 forecasting prompt only)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-04"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["WS-PP12", "WS-PP13"]
pain_points_interviewer_raised_or_inferred: ["WS-PP13 (inferred)"]
coi_per_year: "Not separately quantified"
build_cost: TBC
opex: TBC
notion_section: "PPC: performance forecasting tool"
---

# DS-25 · PPC: performance forecasting tool

*PPC team: forecasting tool for each client from history, seasonality and outside signals.*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | PPC |
| Status | Added – cost TBC |
| Source type | Austin addition – Austin – new; evidence is one person (WS-PP12, WS-PP13 detected) |
| Opportunities | [O-02](../opportunities/README.md#o-02) (WS-O09 forecasting prompt only) |
| Earlier ideas | – |
| Fixes | [P-04 Client-call prep takes longer than the call](../problems/p-04-client-call-prep-takes-longer-than-the.md) |
| Also helps | – |
| Pain points cited | [WS-PP12](../pain-points/README.md#ws-pp12), [WS-PP13](../pain-points/README.md#ws-pp13) (inferred) |
| Written source | – |
| Cost of inactivity / year | Not separately quantified – WS-O09 hours sit in DS-02 |
| Build cost / OpEx | TBC |

## Vision

> **A forecasting simulator.** The team can toggle inputs and simulate real-world events and trends (budget changes, seasonality, economic shifts, platform changes) to see how they would affect delivery and results. Shared goal with [DS-26](ds-26-seo-performance-forecasting-tool.md), with PPC-specific nuances. **Starting point:** talk to the leads about how they forecast today (e.g. Wendlley's Gemini method) and then turbo-charge it.

**Team:** PPC. **Your decision (9 Nov):** a forecasting tool that predicts each client's paid performance from history, seasonality, economic trends and predictions, and other outside factors.

## How it works (draft)

1. Pulls each client's ad history (spend, conversions, CPA/ROAS) and seasonality.
2. Adds outside signals: economic indicators, industry trends, events (from the market radar, [DS-16](ds-16-seasonal-and-trending-content-radar-per-client.md)).
3. Produces a forecast per client and channel – expected results at a given budget, with a range – and flags where results are likely to dip.
4. Used for budget planning, proposals ([DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md)) and setting client expectations ([DS-28](ds-28-client-comms-assistant-monthly-updates-and-expectation.md)).

## Problems it fixes and the evidence

- [Client-call prep takes longer than the call](../problems/p-04-client-call-prep-takes-longer-than-the.md) – forecasting part:
  - *"I used to take like hours doing this and Gemini did it in like 15 minutes"* – Wendlley Simoes, Performance Marketing Director, on forecasting ([WS-PP12](../pain-points/README.md#ws-pp12), stated). External shocks also make history unreliable for forecasting.
  - The director's Gemini forecasting is a personal workflow, not shared with the team ([WS-PP13](../pain-points/README.md#ws-pp13), *inferred*).
- Source opportunity: WS-O09 – share the director's forecasting approach as a standard for all managers (2–18 h/month, assumed; currently counted in [DS-02](ds-02-ai-playbook-repository.md)'s prompt library).

## Future state

Every PPC manager can produce a client forecast in minutes, using the same method, with outside factors built in.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Managers producing forecasts with the shared tool | 1 (WS) | All PPC managers |
| Forecast accuracy (actual vs forecast) | Not tracked | Baseline, then improve |

## Cost of inactivity (COI)

Not separately quantified – WS-O09's 2–18 h/month sits in [DS-02](ds-02-ai-playbook-repository.md). The value is better budget decisions and fewer surprises for clients.

## Indicative build cost and OpEx

**TBC by Austin.**

## Assumptions

- Mainly your suggestion; evidence is one person (the performance director), who has largely solved it personally with Gemini.
- Economic and trend data sources to be chosen.
