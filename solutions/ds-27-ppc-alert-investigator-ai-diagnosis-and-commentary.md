---
id: DS-27
title: "PPC: alert investigator – AI diagnosis and commentary on flagged activity"
team: "PPC"
bundle: "PPC performance"
status: "Recommended – build 1, PPC pacing and performance assistant (with DS-01)"
coverage: addressed
source_type: "mixed"
opportunities: ["O-12 (draft-diagnosis part)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-03"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["DM-PP01", "WS-PP04"]
pain_points_interviewer_raised_or_inferred: []
value: "Counted in DS-01 – removes the \"what's going on\" time when an alert fires"
---

# DS-27 · PPC: alert investigator – AI diagnosis and commentary

*PPC team: when DS-01 flags something, AI investigates and gives a first diagnosis.*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | PPC |
| Status | Recommended – build 1, PPC pacing and performance assistant (with DS-01) |
| Source type | mixed – Austin – new on top of O-12's draft-diagnosis step; WS-PP04, DM-PP01 |
| Opportunities | [O-12](../opportunities/README.md#o-12) (draft-diagnosis part) |
| Earlier ideas | – |
| Fixes | [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | – |
| Pain points cited | [DM-PP01](../pain-points/README.md#dm-pp01), [WS-PP04](../pain-points/README.md#ws-pp04) |
| Written source | – |
| Value | Counted in DS-01 – removes the "what's going on" time when an alert fires |

## Vision

> **Collate the information for the account manager and add intel and a first diagnosis**, so nobody spends 20–30 minutes getting up to speed on a problem – they jump straight into fixing it.

## Build approach

**Windsor.ai account data + client brain context → a diagnosis and a recommended next step.** The pacing engine and performance alerts ([DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)) flag the change; the investigator explains it:

1. A [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) flag (posted to Slack, tagging the account owner) triggers the investigator.
2. An AI agent reads the account through Windsor.ai – the flagged metrics and their recent trend.
3. It adds context from the client brain ([DS-04](ds-04-ai-client-brain.md)): the client's goals and history, recent conversations, what's been tried before, recent work and changes logged in Monday, their industry, competitor intel, seasonality and market trends ([DS-16](ds-16-seasonal-and-trending-content-radar-per-client.md), [DS-32](ds-32-competitor-spy-per-client.md), [DS-33](ds-33-macro-trend-tracker-per-client.md)).
4. It posts a **diagnosis** – likely causes ranked, with the evidence for each – and a recommended next step in the alert's Slack thread.

*Limit: where account-level detail such as change history, search terms or auction insights isn't in the data, the diagnosis is a well-informed starting point, not a forensic answer.*

## Decision

**Team:** PPC. **Decision:** when certain activity is flagged in an ad account, the AI investigates it and gives a first diagnosis and a recommended next step. Delivered with [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) as build 1, the PPC pacing and performance assistant; it needs the client brain (build 2) live, because that's where the client context comes from.

## Is it already covered?

**Partly.** [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) (pacing + alerting) **alerts** on thresholds, and rules tools (pause, scale, notify) don't diagnose why something happened. [O-12](../opportunities/README.md#o-12) included a "draft diagnosis" step; DS-27 is that layer on top of [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)'s alerting, in the same build.

## How it works

1. A [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) alert (e.g. CPA spike, conversion drop, spend anomaly) triggers the investigator.
2. It reads the alert's metrics through Windsor.ai and context from the client brain ([DS-04](ds-04-ai-client-brain.md)).
3. It writes a short commentary: what changed, the most likely causes ranked, and the recommended next step.
4. The manager gets the alert and the diagnosis together in Slack.

## Problems it fixes and the evidence

- [No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) – the diagnosis part:
  - *"currently we have a notification … Like, oh, we've noticed like a decrease in conversions in the past like seven, 14 days"* – Wendlley, Performance Marketing Director: alerts give no cause, and diagnosis is manual ([WS-PP04](../pain-points/README.md#ws-pp04), stated).
  - *"Even though it's a Google Ads related question, I'll be jumping onto the CRM, GA4 and everything to better understand."* – Diya Manoj, Performance Marketing Manager ([DM-PP01](../pain-points/README.md#dm-pp01), stated).
- Source: [O-12](../opportunities/README.md#o-12)'s "draft diagnosis" step (exceptions sent with change history, search terms and auction data).

## Future state

Every alert arrives with a diagnosis and a recommended next step, so managers start deciding rather than investigating.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Alerts with a diagnosis attached | 0% ([WS-PP04](../pain-points/README.md#ws-pp04)) | 100% |
| Time to get up to speed on a flagged problem | \~20–30 min (Austin's estimate) | A few minutes |
| Time from alert to cause found | Manual, varies | −50% |

## Value

> **Gets the account manager straight to the fix.** When an account needs attention, the investigator collates the data and the client's context and gives a first diagnosis, so nobody spends 20–30 minutes working out what's going on.

**1. Time saved and 2. Capacity unlocked:** counted in [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) – together they are build 1, valued at 51–58 hours a month, about A\$187K–213K a year of PPC capacity. The time spent working out what's going on in an account is part of the weekly session already valued there, so it isn't counted again. DS-27 is what makes that time disappear when an alert fires – the diagnosis arrives with it.

**3. Problems it eliminates**

- **P-03** No proactive performance alerting – problems found at month-end (the diagnosis half)
- Helps: **P-21** Managers at capacity – Tier 2/3 clients get dropped first

**Goals:** more MRR managed per person · good performance · good customer service

*Inputs from Austin: \~20–30 min to work out what's going on and fix it today.*

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Needs [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) (Windsor.ai and the alert engine) and the client brain ([DS-04](ds-04-ai-client-brain.md)) live.
