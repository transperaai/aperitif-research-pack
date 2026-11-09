---
id: DS-27
title: "PPC: alert investigator – AI diagnosis and commentary on flagged activity"
team: "PPC"
bundle: "PPC performance"
status: "Added – cost TBC"
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
coi_per_year: "$3K–$18K"
build_cost: TBC
opex: TBC
notion_section: "PPC: alert investigator – AI diagnosis and commentary"
---

# DS-27 · PPC: alert investigator – AI diagnosis and commentary

*PPC team: when DS-01 flags something, AI investigates and gives a first diagnosis.*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | PPC |
| Status | Added – cost TBC |
| Source type | mixed – Austin – new on top of O-12's draft-diagnosis step; WS-PP04, DM-PP01 |
| Opportunities | [O-12](../opportunities/README.md#o-12) (draft-diagnosis part) |
| Earlier ideas | – |
| Fixes | [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | – |
| Pain points cited | [DM-PP01](../pain-points/README.md#dm-pp01), [WS-PP04](../pain-points/README.md#ws-pp04) |
| Written source | – |
| Cost of inactivity / year | \$3K–\$18K – overlaps DS-01 – do not add |
| Build cost / OpEx | TBC |

## Vision

> **Collate the information for the account manager and add intel and a first diagnosis**, so nobody spends 20–30 minutes getting up to speed on a problem – they jump straight into fixing it.

**Team:** PPC. **Your decision (9 Nov):** when certain activity is flagged in an ad account, an automation investigates it and gives a commentary or a first diagnosis of the problem.

## Is it already covered?

**Partly.** [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) (pacing + alerting) **alerts** on thresholds, and Bïrch-style SaaS runs **rules** (pause, scale, notify) – neither diagnoses why something happened. [O-12](../opportunities/README.md#o-12) included a "draft diagnosis" step that [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) didn't carry over. So this is a separate layer on top of whichever alerting tool you choose in [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md).

## How it works (draft)

1. A [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) alert (e.g. CPA spike, conversion drop, spend anomaly) triggers the investigator.
2. It pulls the context: change history, search terms, auction insights, budget and bid changes, landing-page and tracking status, GA4/CRM data.
3. It writes a short commentary: what changed, the most likely causes ranked, and what to check first.
4. The manager gets the alert and the diagnosis together in Slack.

## Problems it fixes and the evidence

- [No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) – the diagnosis part:
  - *"currently we have a notification … Like, oh, we've noticed like a decrease in conversions in the past like seven, 14 days"* – Wendlley, Performance Marketing Director: alerts give no cause, and diagnosis is manual ([WS-PP04](../pain-points/README.md#ws-pp04), stated).
  - *"Even though it's a Google Ads related question, I'll be jumping onto the CRM, GA4 and everything to better understand."* – Diya Manoj, Performance Marketing Manager ([DM-PP01](../pain-points/README.md#dm-pp01), stated; est. 3.5–19 h/month).
- Source: [O-12](../opportunities/README.md#o-12)'s "draft diagnosis" step (exceptions sent with change history, search terms and auction data).

## Future state

Every alert arrives with a first diagnosis, so managers start fixing rather than investigating.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Alerts with a diagnosis attached | 0% ([WS-PP04](../pain-points/README.md#ws-pp04)) | 100% |
| Time to get up to speed on a flagged problem | \~20–30 min (Austin's estimate) | A few minutes |
| Time from alert to cause found | Manual, varies | −50% |

## Cost of inactivity (COI)

|  | Per month | Per year |
| --- | --- | --- |
| Investigation time across platforms (one manager, est.) | 3.5–19 h (\$280–\$1.5K) | **\$3K–\$18K** |

*Basis: [DM-PP01](../pain-points/README.md#dm-pp01) estimate for one manager (estimated, not stated). Overlaps [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)'s [O-12](../opportunities/README.md#o-12) share – do not add the two. \$80/hr.*

## Indicative build cost and OpEx

**TBC by Austin.** Bïrch and pacing SaaS don't include AI diagnosis – likely a build on top of the [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) tool's alerts.

## Assumptions

- Needs API access to ad accounts, GA4 and the CRM.
