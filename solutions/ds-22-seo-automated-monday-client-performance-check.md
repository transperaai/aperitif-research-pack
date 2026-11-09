---
id: DS-22
title: "SEO: automated Monday client performance check (GA4, Search Console, Ahrefs)"
team: "SEO"
bundle: "SEO performance"
status: "Decided – cost TBC"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-12 (SEO part (ZC-O03, LS-O03))"]
earlier_ideas: []
written_sources: ["WS-ZC-01 Zach Chamberlain \"AI suggestions\" Google Doc"]
problems_fixed: ["P-03"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["LS-PP05", "ZC-PP05"]
pain_points_interviewer_raised_or_inferred: []
coi_per_year: "$3.5K–$9.8K"
build_cost: TBC
opex: TBC
notion_section: "SEO: automated Monday client performance check"
---

# DS-22 · SEO: automated Monday client performance check

*SEO team: automated Monday performance check per client from GA4, Search Console and Ahrefs.*

| | |
| --- | --- |
| Bundle | [SEO performance](README.md#bundle-seo-performance) |
| Team | SEO |
| Status | Decided – cost TBC |
| Source type | evidence-backed – Also rests on Zach's written AI suggestions doc (WS-ZC-01) |
| Opportunities | [O-12](../opportunities/README.md#o-12) (SEO part (ZC-O03, LS-O03)) |
| Earlier ideas | – |
| Fixes | [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | – |
| Pain points cited | [LS-PP05](../pain-points/README.md#ls-pp05), [ZC-PP05](../pain-points/README.md#zc-pp05) |
| Written source | [Zach Chamberlain – "AI suggestions" Google Doc](https://docs.google.com/document/d/1bsjfs6Aw1F6VOA_nvhWwzPoFv8XHxaXp4Q8UHYAgtsw/edit) (WS-ZC-01) |
| Cost of inactivity / year | \$3.5K–\$9.8K – moved out of DS-01 |
| Build cost / OpEx | TBC |

## Vision

> **Proactive performance intel that comes to the team**, so nobody has to go into accounts to find out how a client is doing. A steady flow of intel the team can use to report to the client. (Shared vision for the SEO monitoring set: DS-22 Monday check, [DS-23](ds-23-seo-drop-and-anomaly-alerts.md) drop alerts, [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md) mid-month wins.)

**Team:** SEO. **Your decision (9 Nov):** a separate solution for the SEO team ([DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) is the PPC team's). It automates the Monday "client performance checks" that are often skipped. Source: Zach's written AI suggestions, plus the interviews.

## How it works

1. Every Monday, the check pulls each SEO client's key figures from **GA4, Google Search Console and Ahrefs** (via MCP / API): rankings, organic traffic, conversions, technical issues.
2. It compares them with last week, last month and the client's own thresholds.
3. Each manager gets one short summary per client in Slack/Monday – what moved, what needs a look – so the check is done even on a busy Monday.
4. The summary feeds [DS-23](ds-23-seo-drop-and-anomaly-alerts.md) (drop alerts) and [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md) (mid-month wins), and is stored in the client brain ([DS-04](ds-04-ai-client-brain.md)).

## Problems it fixes and the evidence

- [No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) – the SEO side.
  - *"I find that these can sometimes be an afterthought because you know you're busy"* – Zach, SEO Manager, on the Monday performance check ([ZC-PP05](../pain-points/README.md#zc-pp05), stated).
  - *"I still do it manually, which is silly."* – Laura, SEO Director, checking client performance by hand with no roll-up of drops, red flags and wins ([LS-PP05](../pain-points/README.md#ls-pp05), stated).
  - Zach's written suggestions: the Monday checks *"often get overlooked or sped through on a Monday morning"*; managers work on up to 20 accounts each.

## Future state

Every SEO client is checked every Monday automatically; managers read a summary instead of opening each account.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Weeks the Monday check is completed for every client | Sometimes skipped ([ZC-PP05](../pain-points/README.md#zc-pp05)) | 100% (automated) |
| Manager time on the Monday check | Manual per client ([LS-PP05](../pain-points/README.md#ls-pp05)) | Review summary only |

## Cost of inactivity (COI)

|  | Per month | Per year |
| --- | --- | --- |
| Recoverable SEO staff time | 3.6–10.2 h (\$290–\$820) | **\$3.5K–\$9.8K** |

*Basis: the SEO sources of [O-12](../opportunities/README.md#o-12) – ZC-O03 1.6–5.5 h + LS-O03 2.0–4.7 h. Assumed. \$80/hr. Moved out of [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)'s figure so it isn't counted twice.*

## Indicative build cost and OpEx

**TBC by Austin.** OpEx: GA4/GSC (free), Ahrefs API, AI usage.

## Assumptions

- API access to every client's GA4, Search Console and Ahrefs project.
- Thresholds agreed per client by the SEO team.
