---
id: DS-23
title: "SEO: drop and anomaly alerts"
team: "SEO"
bundle: "SEO performance"
status: "Decided – priced"
ledger_status: addressed
source_type: "mixed"
opportunities: ["O-12 (SEO part)"]
earlier_ideas: []
written_sources: ["WS-ZC-01 Zach Chamberlain \"AI suggestions\" Google Doc"]
problems_fixed: ["P-03"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["LS-PP15"]
pain_points_interviewer_raised_or_inferred: []
value: "7–11 h/mo · A$35K–58K capacity (≈ 1–1.5 SEO clients)"
value_time_h_month: [7, 11]
value_capacity_aud_per_year: [35000, 58000]
build_cost: "A$8,500 for the bundle (DS-22 + DS-23 + DS-24)"
monthly: "A$1,250/month + tokens ~US$8–35"
notion_section: "SEO: drop and anomaly alerts"
---

# DS-23 · SEO: drop and anomaly alerts

*SEO team: daily drop and anomaly alerts per client with a first guess at the cause.*

| | |
| --- | --- |
| Bundle | [SEO performance](README.md#bundle-seo-performance) |
| Team | SEO |
| Status | Decided – priced |
| Source type | mixed – Mainly Zach's written AI suggestions doc (WS-ZC-01) plus LS-PP15 |
| Opportunities | [O-12](../opportunities/README.md#o-12) (SEO part) |
| Earlier ideas | – |
| Fixes | [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | – |
| Pain points cited | [LS-PP15](../pain-points/README.md#ls-pp15) |
| Written source | [Zach Chamberlain – "AI suggestions" Google Doc](https://docs.google.com/document/d/1bsjfs6Aw1F6VOA_nvhWwzPoFv8XHxaXp4Q8UHYAgtsw/edit) (WS-ZC-01) |
| Value | 7–11 h/mo · A\$35K–58K capacity (≈ 1–1.5 SEO clients) |
| Build cost | A\$8,500 for the bundle (DS-22 + DS-23 + DS-24) |
| Monthly | A\$1,250/month + tokens \~US\$8–35 |

## Vision

> Shared with [DS-22](ds-22-seo-automated-monday-client-performance-check.md): **proactive performance intel comes to the team** – drops and anomalies arrive as alerts, so nobody has to dig through accounts to find them.

> **Pricing:** part of the **SEO performance bundle** – see [DS-22](ds-22-seo-automated-monday-client-performance-check.md) (A\$8,500 build, A\$1,250/month for [DS-22](ds-22-seo-automated-monday-client-performance-check.md) + DS-23 + [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md)).

**Team:** SEO. **Decision (9 Nov):** separate solution. AI watches every SEO client for large drop-offs and sudden changes and alerts the manager straight away, so the team is on top of bad results before the client sees them in the monthly report.

## How it works

1. Runs daily on the same data as [DS-22](ds-22-seo-automated-monday-client-performance-check.md) (GA4, Search Console, Ahrefs).
2. Flags anomalies against each client's normal range: ranking drops, traffic or conversion falls, indexing or technical errors, lost backlinks.
3. Sends an alert to the account manager in Slack with what changed, when, and a first guess at why (algorithm update, site change, lost links).
4. Logged in the client brain ([DS-04](ds-04-ai-client-brain.md)) and fed to client health signals ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)).

## Problems it fixes and the evidence

- [No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) – SEO side.
  - Zach's written suggestions: working on up to 20 accounts, *"it can be difficult to spot these instantly, or at all before the effects are being presented to the client in the monthly report."*
  - Laura: churn early warning is limited to ranking trend, and some clients leave *"out of the blue"* ([LS-PP15](../pain-points/README.md#ls-pp15)).

## Future state

SEO drops are known to the manager within a day, with a likely cause, before the client notices.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Days from a ranking/traffic drop to the manager knowing | Unknown – found at month-end (LS-O03) | ≤ 1 day |
| Drops raised by the client before the team | Happens | 0 |

## Value (revised with Austin, 10 Nov)

> **Drops are caught and explained the day they happen.** The alert arrives with the data collated and a first view of the cause and market context, so the manager goes straight to the fix and can tell the client before they notice.

**1. Time saved**

| Task removed | How it's worked out | Per month |
| --- | --- | --- |
| Working out why a client dropped (collating data, reading market signals) | 68 clients × \~0.4 drops a month × 15–25 min saved (20–30 min → \~5 min) | **\~7–11 h** (\~2–3 h per manager) |

**2. Capacity and revenue unlocked:** \~7–11 h ÷ \~130 productive hours × \~A\$55.6K MRR per manager → **\~A\$2.9K–4.9K MRR across the SEO team ≈ A\$35K–58K a year of capacity** (≈ 1–1.5 more SEO clients). Drops found early also protect retention.

**3. Problems it eliminates**

- **P-03** No proactive performance alerting – problems found at month-end
- Helps: **P-21** Managers at capacity

**Goals:** good performance · retention · trust · more MRR managed per person

*Inputs from Austin (10 Nov): \~0.4 drops worth investigating per client per month; 20–30 min to work out why today.*

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Alert thresholds tuned per client so managers aren't flooded.
