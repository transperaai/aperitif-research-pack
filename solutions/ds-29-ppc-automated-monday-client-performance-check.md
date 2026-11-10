---
id: DS-29
title: "PPC: automated Monday client performance check (Google Ads, Meta and other channels)"
team: "PPC"
bundle: "PPC performance"
status: "Added – priced"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-12 (paid part (weekly check))"]
earlier_ideas: ["EI-15 Proactive PPC monitor and anomaly detector"]
written_sources: []
problems_fixed: ["P-03"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["DM-PP02", "MC-PP08", "MC-PP18", "SH-PP11", "SH-PP12", "SH-PP15"]
pain_points_interviewer_raised_or_inferred: []
coi_per_year: "$8K–$20K"
build_cost: "A$1,500"
monthly: "A$500/month + tokens ~US$5–25"
notion_section: "PPC: automated Monday client performance check"
---

# DS-29 · PPC: automated Monday client performance check

*PPC team: automated Monday performance check per paid client across all channels.*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | PPC |
| Status | Added – priced |
| Source type | evidence-backed – DS-22's PPC twin; DM-PP02, MC-PP08, MC-PP18, SH-PP11/12/15 |
| Opportunities | [O-12](../opportunities/README.md#o-12) (paid part (weekly check)) |
| Earlier ideas | [EI-15](../opportunities/README.md#ei-15) Proactive PPC monitor and anomaly detector |
| Fixes | [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | – |
| Pain points cited | [DM-PP02](../pain-points/README.md#dm-pp02), [MC-PP08](../pain-points/README.md#mc-pp08), [MC-PP18](../pain-points/README.md#mc-pp18), [SH-PP11](../pain-points/README.md#sh-pp11), [SH-PP12](../pain-points/README.md#sh-pp12), [SH-PP15](../pain-points/README.md#sh-pp15) |
| Written source | – |
| Value | New standard: clients hear from Aperitif before they ask (trust, retention) |
| Build cost | A\$1,500 |
| Monthly | A\$500/month + tokens \~US\$5–25 |

## Vision

> **Same as the SEO set: proactive performance intel comes to the PPC team**, so nobody has to go into every account – a steady flow of intel to act on and report to the client from.
>
> **How it's delivered:** from **Adpulse** if chosen for [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) (its portfolio dashboard and custom monitors), or a **light version** built on the modernised pacing bot ([DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) smaller option) if Adpulse isn't bought.

## Pricing & priority

> **Priority: Fill-in · Impact 3 / 5 · Effort 2 / 5 (draft – confirm)** · Bundle: PPC performance
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **PPC Monday performance check – with Adpulse** (Adpulse dashboards and monitors + a Claude summary per client to Slack/Monday and the brain) | **A\$1,500** | **A\$500/month** maintenance + AI tokens \~US\$5–25/month (Adpulse licence counted in [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)) |

**Team:** PPC. **Your decision (9 Nov):** the PPC version of [DS-22](ds-22-seo-automated-monday-client-performance-check.md) – every Monday, an automated performance check for each paid client, so managers read a summary instead of opening every account.

## How it is different from DS-01 and DS-27

- **[DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)** watches pacing and fires **alerts** when a threshold is crossed.
- **[DS-27](ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md)** **diagnoses** an alert once it fires.
- **DS-29** is the **weekly roll-up**: every account's performance in one summary, whether or not anything crossed a threshold – trends, small dips, wins, and housekeeping checks.

## How it works (draft)

1. Every Monday it pulls each client's figures from Google Ads, Meta, LinkedIn and the other live channels, plus GA4 conversions: spend vs pace, conversions, CPA/CPL/ROAS, CTR, frequency.
2. It compares them with last week, last month and the client's targets.
3. It runs the routine checks managers do by hand: tracking firing, Merchant Center / feed status, new auto-enabled platform features, disapproved ads.
4. Each manager gets one short summary per client in Slack/Monday – what moved, what needs a look – and it's stored in the client brain ([DS-04](ds-04-ai-client-brain.md)). Wins feed the client comms assistant ([DS-28](ds-28-client-comms-assistant-monthly-updates-and-expectation.md)).

## Problems it fixes and the evidence

- [No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) – the weekly-check part:
  - *"the one Tina is sending it out is just budget basing… I look for each of the accounts, which actually takes time."* – Diya Manoj, Performance Marketing Manager ([DM-PP02](../pain-points/README.md#dm-pp02), stated; est. 8.8–20.9 h/month for one manager).
  - *"I wanted Tina to report the performance of the account."* – Michaela Cruz, Performance Marketing Specialist ([MC-PP08](../pain-points/README.md#mc-pp08), stated).
  - Tracking breaks found only in manual checks, up to \~7 days later ([SH-PP11](../pain-points/README.md#sh-pp11), Sophie Hesseborn); meeting-heavy weeks delay checks ([SH-PP12](../pain-points/README.md#sh-pp12)).
  - *"I haven't checked Google Merchant Center for like three weeks now."* – Michaela Cruz ([MC-PP18](../pain-points/README.md#mc-pp18), stated).
  - Meta auto-enables new AI features, so every build needs a manual check ([SH-PP15](../pain-points/README.md#sh-pp15)).

## Future state

Every paid client gets a performance check every Monday automatically, including the housekeeping checks that slip in busy weeks.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Weeks every paid client is checked | Manual, slips in busy weeks ([SH-PP12](../pain-points/README.md#sh-pp12)) | 100% (automated) |
| Days a tracking break goes unnoticed | Up to \~7 ([SH-PP11](../pain-points/README.md#sh-pp11)) | ≤ 1 week max, usually same week |
| Merchant Center / feed checks done on time | Missed for \~3 weeks ([MC-PP18](../pain-points/README.md#mc-pp18)) | Weekly |

## Value (revised with Austin, 10 Nov)

**Value: a new standard of client communication.** A weekly performance summary per client that the team can act on and report to the client from. Proactive client updates don't happen today, so this isn't time back – it's clients hearing from Aperitif before they ask, which builds trust and supports retention.

**Goals:** trust · good customer service · retention

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- API access to every live ad account and GA4.
- Check list (tracking, feeds, auto-enabled features) agreed with the performance director.
