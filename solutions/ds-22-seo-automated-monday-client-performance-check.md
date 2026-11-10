---
id: DS-22
title: "SEO: automated Monday client performance check (GA4, Search Console, Ahrefs)"
team: "SEO"
bundle: "SEO performance"
status: "Decided – priced"
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
value: "17–39 h/mo · A$88K–202K capacity (≈ 2–5 SEO clients)"
value_time_h_month: [17, 39]
value_capacity_aud_per_year: [88000, 202000]
build_cost: "A$8,500 for the bundle (DS-22 + DS-23 + DS-24)"
monthly: "A$1,250/month + tokens ~US$8–35"
notion_section: "SEO: automated Monday client performance check"
---

# DS-22 · SEO: automated Monday client performance check

*SEO team: automated Monday performance check per client from GA4, Search Console and Ahrefs.*

| | |
| --- | --- |
| Bundle | [SEO performance](README.md#bundle-seo-performance) |
| Team | SEO |
| Status | Decided – priced |
| Source type | evidence-backed – Also rests on Zach's written AI suggestions doc (WS-ZC-01) |
| Opportunities | [O-12](../opportunities/README.md#o-12) (SEO part (ZC-O03, LS-O03)) |
| Earlier ideas | – |
| Fixes | [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | – |
| Pain points cited | [LS-PP05](../pain-points/README.md#ls-pp05), [ZC-PP05](../pain-points/README.md#zc-pp05) |
| Written source | [Zach Chamberlain – "AI suggestions" Google Doc](https://docs.google.com/document/d/1bsjfs6Aw1F6VOA_nvhWwzPoFv8XHxaXp4Q8UHYAgtsw/edit) (WS-ZC-01) |
| Value | 17–39 h/mo · A\$88K–202K capacity (≈ 2–5 SEO clients) |
| Build cost | A\$8,500 for the bundle (DS-22 + DS-23 + DS-24) |
| Monthly | A\$1,250/month + tokens \~US\$8–35 |

## Vision

> **Proactive performance intel that comes to the team**, so nobody has to go into accounts to find out how a client is doing. A steady flow of intel the team can use to report to the client. (Shared vision for the SEO monitoring set: DS-22 Monday check, [DS-23](ds-23-seo-drop-and-anomaly-alerts.md) drop alerts, [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md) mid-month wins.)

## Pricing & priority

> **Priced as one bundle: SEO performance (DS-22 + [DS-23](ds-23-seo-drop-and-anomaly-alerts.md) + [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md))** · Draft scores: DS-22 impact 3 / effort 2 · [DS-23](ds-23-seo-drop-and-anomaly-alerts.md) 3 / 2 · [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md) 2 / 1 (confirm)
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **SEO performance bundle** – Monday performance check, drop and anomaly alerts, mid-month wins (shared GA4 / Search Console / Ahrefs pipeline) | **A\$8,500** | **A\$1,250/month** maintenance + AI tokens \~US\$8–35/month |

**Team:** SEO. **Decision (9 Nov):** a separate solution for the SEO team ([DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) is the PPC team's). It automates the Monday "client performance checks" that are often skipped. Source: Zach's written AI suggestions, plus the interviews.

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

## Value (revised with Austin, 10 Nov)

> **Performance intel comes to the SEO team.** Every Monday each manager gets a digest of how every client is going across GA4, Search Console and Ahrefs, so nobody opens three tools for every client to find out.

**1. Time saved**

| Task removed | How it's worked out | Per month |
| --- | --- | --- |
| Weekly check of each client in GA4, Search Console and Ahrefs | 68 live SEO clients × 5–10 min per week ≈ 25–49 h/month today; the digest removes 70–80% (estimate – the target, not a measured figure) | **\~17–39 h** (\~4–10 h per manager) |

**2. Capacity and revenue unlocked**

| Step | Figure |
| --- | --- |
| SEO managers | 4 (per org chart; \~17 clients each) |
| MRR managed per manager today | \~A\$55.6K (A\$222,374 live SEO MRR across 68 clients ÷ 4) |
| Time freed per manager | \~4–10 h/month ≈ 3–8% of \~130 productive hours (assumption) |
| **Capacity unlocked across the SEO team** | **\~A\$7.3K–16.8K MRR ≈ A\$88K–202K a year** (≈ 2–5 more SEO clients at the \~A\$3,270 average) |

Capacity to grow into without hiring, not guaranteed revenue.

**3. Problems it eliminates**

- **P-03** No proactive performance alerting – problems found at month-end (the SEO side)
- Helps: **P-21** Managers at capacity – Tier 2/3 clients get dropped first

**Goals:** more MRR managed per person · good performance · good customer service

*Inputs from Austin (10 Nov): 68 live SEO clients and A\$222,374 live SEO MRR (client board, paused excluded), 5–10 min weekly check per client, 4 SEO managers (org chart). Assumptions: 70–80% of checks removed; \~130 productive hours per manager per month.*

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- API access to every client's GA4, Search Console and Ahrefs project.
- Thresholds agreed per client by the SEO team.
