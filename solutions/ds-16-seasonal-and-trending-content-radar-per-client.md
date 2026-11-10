---
id: DS-16
title: "Seasonal & trending content radar per client (split 9 Nov)"
team: "SEO and content strategists"  # inferred: the page gives no "Team:" line
bundle: "Market intelligence"
status: "Decided – priced"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-28 (seasonal & trending part)"]
earlier_ideas: ["EI-19 Seasonal & trending content radar per client"]
written_sources: ["WS-ZC-01 Zach Chamberlain \"AI suggestions\" Google Doc"]
problems_fixed: ["P-24"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["KZ-PP19", "KZ-PP20", "ZC-PP09", "ZC-PP15", "ZC-PP17"]
pain_points_interviewer_raised_or_inferred: []
coi_per_year: "$2K–$7K"
build_cost: "A$750"
monthly: "A$300/month (+ trends data ~US$20–100 if needed)"
notion_section: "Per-client market radar → now: Seasonal & trending content radar"
---

# DS-16 · Per-client market radar → now: Seasonal & trending content radar

*Per-client seasonal and trending content radar (competitor spy is DS-32, macro trends DS-33).*

| | |
| --- | --- |
| Bundle | [Market intelligence](README.md#bundle-market-intelligence) |
| Team | SEO and content strategists *(inferred)* |
| Status | Decided – priced |
| Source type | evidence-backed – Seasonal & trending part only since the 9 Nov split (competitor spy is DS-32, macro tracker DS-33) |
| Opportunities | [O-28](../opportunities/README.md#o-28) (seasonal & trending part) |
| Earlier ideas | [EI-19](../opportunities/README.md#ei-19) Seasonal & trending content radar per client |
| Fixes | [P-24 Seasonal and trending content is planned too late to catch the peak](../problems/p-24-seasonal-and-trending-content-is-planned-too.md) (seasonal & trending part (competitor and news parts split to DS-32, DS-33)) |
| Also helps | – |
| Pain points cited | [KZ-PP19](../pain-points/README.md#kz-pp19), [KZ-PP20](../pain-points/README.md#kz-pp20), [ZC-PP09](../pain-points/README.md#zc-pp09), [ZC-PP15](../pain-points/README.md#zc-pp15), [ZC-PP17](../pain-points/README.md#zc-pp17) |
| Written source | [Zach Chamberlain – "AI suggestions" Google Doc](https://docs.google.com/document/d/1bsjfs6Aw1F6VOA_nvhWwzPoFv8XHxaXp4Q8UHYAgtsw/edit) (WS-ZC-01) |
| Cost of inactivity / year | \$2K–\$7K – O-28 hours; DS-32/DS-33 not quantified separately |
| Build cost | A\$750 |
| Monthly | A\$300/month (+ trends data \~US\$20–100 if needed) |

## Vision

> **Split into three solutions (your call, 9 Nov):** DS-16 is now the **seasonal & trending content radar**; the **competitor spy** is [DS-32](ds-32-competitor-spy-per-client.md) and the **macro trend tracker** is [DS-33](ds-33-macro-trend-tracker-per-client.md). Each one **lives in every client's brain** ([DS-04](ds-04-ai-client-brain.md)) and **alerts the strategist in Slack**. The description below covers all three as originally written; DS-16's own scope is the seasonal & trending row.

## Pricing & priority

> **Priority: Impact 2 / 5 · Effort 3 / 5 (draft – confirm)** · Bundle: Market intelligence
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **Seasonal & trending content radar** – a **Claude routine** connected to an MCP that uploads results into each AI client brain ([DS-04](ds-04-ai-client-brain.md)) and alerts the strategist in Slack | **A\$750** | **A\$300/month** maintenance (+ trends/search data source if needed, \~US\$20–100/month – to verify) |

**Your decision (9 Nov):** one radar **for each client** with three parts: a **seasonal and trending content radar**, a **competitor spy**, and a **macro trend tracker** for what's happening in the world that affects the client, their industry and more. Sits under the AI Business Brain ([DS-15](ds-15-ai-business-brain-the-umbrella.md)) and writes into each client brain ([DS-04](ds-04-ai-client-brain.md)).

## The three parts

| Part | What it watches | What it sends |
| --- | --- | --- |
| Seasonal & trending content radar | Google Trends for the client's niche, an events calendar (sport, holidays, sales, industry dates), rising searches | Suggested topics 2–3 months before each peak, and fast alerts on sudden spikes |
| Competitor spy | Each client's named competitors: new pages and site changes (sitemaps), new content, ranking moves, new ads | A digest of what changed and what it means for the client |
| Macro trend tracker | News, regulation, economy and industry developments that affect the client and their industry | Alerts with a short "why it matters" and a content or strategy idea |

All three post to the client's strategist (Slack/Monday) and are stored in the client brain, so they feed briefs ([DS-03](ds-03-automated-ai-brief-drafts-monday-com-tasks.md)), reviews ([DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md)) and growth signals ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)).

## Opportunities it covers

- **[O-28](../opportunities/README.md#o-28)** Seasonal, trending and competitor content radar – rank 28, Consider, effort M (2–7 h/month, assumed)
- Your earlier ideas: *Seasonal & trending content radar per client*, *Macro trend tracker agent for client industries*.

## Problems it fixes and the evidence

- [Seasonal and trending content is planned too late to catch the peak](../problems/p-24-seasonal-and-trending-content-is-planned-too.md) – 2 staff, all stated.
  - Trends tracked by hand: *"I can only do this once every two, three days. I can't do this every single day."* – the link-building lead, on a Tier 1 client ([KZ-PP19](../pain-points/README.md#kz-pp19)).
  - Events missed: *"like a major event and we'd be too late to even think to do like a content topic"* ([KZ-PP20](../pain-points/README.md#kz-pp20)).
  - Seasonal peaks missed: *"we were just getting to those seasonal peaks too late."* – an SEO manager ([ZC-PP09](../pain-points/README.md#zc-pp09)); content needs \~2 months' lead time.
  - Competitors unwatched: no monitoring of new pages or site changes ([ZC-PP15](../pain-points/README.md#zc-pp15)).
  - News depends on one person spotting it – a surcharge change was headline news and only fast-tracked because the manager happened to see it ([ZC-PP17](../pain-points/README.md#zc-pp17)).
- **Zach's written AI suggestions** (Google Doc) ask for exactly this: an automated workflow for seasonal and competitor content suggestions (he built a seasonal collection-page calendar for a flower client by hand in Claude) and for news-driven blog topics across client industries, where *"we are missing out on trending topics."*

## Future state

1. Every client has a live radar: seasonal peaks, trends, competitors and world events.
2. Topics reach the strategist 2–3 months before peaks; sudden spikes and news reach them the same day.
3. Competitor moves are reported weekly without anyone checking sites by hand.
4. Strategists bring timely ideas to clients – supporting the "bring a recommendation" goal ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)).

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Seasonal / trend pieces live 4+ weeks before peak | Peaks reached too late (ZC-O07) | ≥ 80% |
| Major events with content published in time | Missed (KZ-O08) | ≥ 80% of calendar events |
| Clients with an active competitor watch | 0 ([ZC-PP15](../pain-points/README.md#zc-pp15)) | 100% |
| Trend checks done by hand | Every 2–3 days for one client ([KZ-PP19](../pain-points/README.md#kz-pp19)) | 0 |

## Cost of inactivity (COI)

|  | Per month | Per year |
| --- | --- | --- |
| Recoverable staff time (manual trend and competitor checks) | 2–7 h (\$180–\$560) | **\$2K–\$7K** |

The bigger cost isn't hours: missed seasonal peaks and events mean content that lands after demand has passed, weaker client results, and fewer proactive ideas to show clients – a retention and growth lever ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)). Not quantified.

*Basis: [O-28](../opportunities/README.md#o-28) recoverable hours (KZ-O08 1.9–5.5 + ZC-O07 0.3–1.5). The macro trend tracker and the spy at full scale go beyond [O-28](../opportunities/README.md#o-28), so time saved may be higher. Assumed. \$80/hr.*

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Hours saved assumed; evidence is from organic only (2 people).
- Each client's competitor list and niche keywords exist or can be pulled from the Master SEO Document.
- Alert volume is tuned per client so strategists aren't flooded.

## Decided (9 Nov)

- One radar per client with three parts: seasonal & trending, competitor spy, macro trend tracker.
