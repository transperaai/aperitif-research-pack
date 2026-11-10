---
id: DS-27
title: "PPC: alert investigator – AI diagnosis and commentary on flagged activity"
team: "PPC"
bundle: "PPC performance"
status: "Added – priced"
ledger_status: addressed
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
build_cost: "A$5,000"
monthly: "A$750/month + tokens ~US$15–60"
notion_section: "PPC: alert investigator – AI diagnosis and commentary"
---

# DS-27 · PPC: alert investigator – AI diagnosis and commentary

*PPC team: when DS-01 flags something, AI investigates and gives a first diagnosis.*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | PPC |
| Status | Added – priced |
| Source type | mixed – Austin – new on top of O-12's draft-diagnosis step; WS-PP04, DM-PP01 |
| Opportunities | [O-12](../opportunities/README.md#o-12) (draft-diagnosis part) |
| Earlier ideas | – |
| Fixes | [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | – |
| Pain points cited | [DM-PP01](../pain-points/README.md#dm-pp01), [WS-PP04](../pain-points/README.md#ws-pp04) |
| Written source | – |
| Value | Counted in DS-01 – removes the "what's going on" time when an alert fires |
| Build cost | A\$5,000 |
| Monthly | A\$750/month + tokens \~US\$15–60 |

## Vision

> **Collate the information for the account manager and add intel and a first diagnosis**, so nobody spends 20–30 minutes getting up to speed on a problem – they jump straight into fixing it.

## Build approach (agreed 10 Nov)

**Adpulse metrics + client brain context → a potential diagnosis.** Adpulse flags the change but doesn't explain it (its alerts are threshold-based and its insights are rule-based best-practice checks). So:

1. An Adpulse alert (via its API or the Slack alert) triggers the investigator.
2. It pulls the alert's metrics and recent trend from Adpulse.
3. It adds context from the client brain ([DS-04](ds-04-ai-client-brain.md)): the client's strategy and goals, recent work and changes logged in Monday, recent client comms, and industry, seasonal and news context ([DS-16](ds-16-seasonal-and-trending-content-radar-per-client.md), [DS-33](ds-33-macro-trend-tracker-per-client.md)).
4. Claude writes a **potential diagnosis** – likely causes ranked, with the evidence for each – and what to check first, in the alert's Slack thread.

No direct Google Ads / Meta API connectors are needed at first, which keeps the build light and avoids the API approvals. *Limit: without account-level change history, search terms and auction insights the diagnosis is a well-informed starting point, not a forensic answer; direct ad-platform data can be added later if needed.* Also ask in the Adpulse demo whether it can export change history or search-term data.

## Pricing & priority

> **Priority: Impact 3 / 5 · Effort 3 / 5 (draft – re-scored for the lighter Adpulse + brain approach; confirm)** · Bundle: PPC performance
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **PPC alert investigator** – Adpulse alert metrics + client brain context → potential diagnosis in Slack | **A\$5,000** | **A\$750/month** maintenance + AI tokens \~US\$15–60/month |
>
> *Needs [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) (Adpulse) and [DS-04](ds-04-ai-client-brain.md) (client brain) in place.*

**Team:** PPC. **Decision (9 Nov):** when certain activity is flagged in an ad account, an automation investigates it and gives a commentary or a first diagnosis of the problem.

## Is it already covered?

**Partly.** [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) (pacing + alerting) **alerts** on thresholds, and Bïrch-style SaaS runs **rules** (pause, scale, notify) – neither diagnoses why something happened. [O-12](../opportunities/README.md#o-12) included a "draft diagnosis" step that [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) didn't carry over. So this is a separate layer on top of [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)'s alerting (Adpulse).

## How it works (draft)

1. A [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) alert (e.g. CPA spike, conversion drop, spend anomaly) triggers the investigator.
2. It pulls the alert's metrics from Adpulse and context from the client brain ([DS-04](ds-04-ai-client-brain.md)).
3. It writes a short commentary: what changed, the most likely causes ranked, and what to check first.
4. The manager gets the alert and the diagnosis together in Slack.

## Problems it fixes and the evidence

- [No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) – the diagnosis part:
  - *"currently we have a notification … Like, oh, we've noticed like a decrease in conversions in the past like seven, 14 days"* – Wendlley, Performance Marketing Director: alerts give no cause, and diagnosis is manual ([WS-PP04](../pain-points/README.md#ws-pp04), stated).
  - *"Even though it's a Google Ads related question, I'll be jumping onto the CRM, GA4 and everything to better understand."* – Diya Manoj, Performance Marketing Manager ([DM-PP01](../pain-points/README.md#dm-pp01), stated).
- Source: [O-12](../opportunities/README.md#o-12)'s "draft diagnosis" step (exceptions sent with change history, search terms and auction data).

## Future state

Every alert arrives with a first diagnosis, so managers start fixing rather than investigating.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Alerts with a diagnosis attached | 0% ([WS-PP04](../pain-points/README.md#ws-pp04)) | 100% |
| Time to get up to speed on a flagged problem | \~20–30 min (Austin's estimate) | A few minutes |
| Time from alert to cause found | Manual, varies | −50% |

## Value (revised with Austin, 10 Nov)

> **Gets the account manager straight to the fix.** When an account needs attention, the investigator collates the data and the client's context and gives a first diagnosis, so nobody spends 20–30 minutes working out what's going on.

**1. Time saved and 2. Capacity unlocked:** counted in [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md). The time spent working out what's going on in an account is part of the weekly session already valued there, so it isn't counted again. DS-27 is what makes that time disappear when an alert fires – the diagnosis arrives with it.

**3. Problems it eliminates**

- **P-03** No proactive performance alerting – problems found at month-end (the diagnosis half)
- Helps: **P-21** Managers at capacity – Tier 2/3 clients get dropped first

**Goals:** more MRR managed per person · good performance · good customer service

*Inputs from Austin (10 Nov): \~20–30 min to work out what's going on and fix it today.*

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Needs [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) (Adpulse) and [DS-04](ds-04-ai-client-brain.md) live.
