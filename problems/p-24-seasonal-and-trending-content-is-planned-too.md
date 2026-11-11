---
id: P-24
title: "Seasonal and trending content is planned too late to catch the peak"
decision: "Solve now"
status: addressed
fixed_by: ["DS-16", "DS-32", "DS-33"]
also_helped_by: []
related_only: []
clusters: ["C-15"]
root_causes: ["RC-02"]
pain_points: ["KZ-PP19", "KZ-PP20", "ZC-PP09", "ZC-PP15", "ZC-PP17"]
theme: "Process / automation"
severity: "Medium"
confidence: "High – raised by 3+ people"
---

# P-24 · Seasonal and trending content is planned too late to catch the peak

| | |
| --- | --- |
| Decision | **Solve now** |
| Status | addressed – Fixed by [DS-16](../solutions/ds-16-seasonal-and-trending-content-radar-per-client.md), [DS-32](../solutions/ds-32-competitor-spy-per-client.md), [DS-33](../solutions/ds-33-macro-trend-tracker-per-client.md) |
| Theme · severity · confidence | Process / automation · Medium · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-16 Seasonal & trending content radar per client (split 9 Nov)](../solutions/ds-16-seasonal-and-trending-content-radar-per-client.md) – seasonal & trending part (competitor and news parts split to DS-32, DS-33)
- Fixes: [DS-32 Competitor spy per client (split from DS-16)](../solutions/ds-32-competitor-spy-per-client.md) – competitor part
- Fixes: [DS-33 Macro trend tracker per client (split from DS-16)](../solutions/ds-33-macro-trend-tracker-per-client.md) – news part

## Linked opportunities

- [EI-19](../opportunities/README.md#ei-19) Seasonal & trending content radar per client – absorbed ([DS-16](../solutions/ds-16-seasonal-and-trending-content-radar-per-client.md))
- [O-12](../opportunities/README.md#o-12) Cross-account performance monitor with draft diagnosis (paid and SEO) – addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-27](../solutions/ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md), [DS-29](../solutions/ds-29-ppc-automated-monday-client-performance-check.md), [DS-22](../solutions/ds-22-seo-automated-monday-client-performance-check.md), [DS-23](../solutions/ds-23-seo-drop-and-anomaly-alerts.md), [DS-24](../solutions/ds-24-seo-mid-month-wins-sent-to-clients.md))
- [O-28](../opportunities/README.md#o-28) Seasonal, trending and competitor content radar – addressed ([DS-16](../solutions/ds-16-seasonal-and-trending-content-radar-per-client.md), [DS-32](../solutions/ds-32-competitor-spy-per-client.md))
- [EI-11](../opportunities/README.md#ei-11) Macro trend tracker agent for client industries – addressed ([DS-33](../solutions/ds-33-macro-trend-tracker-per-client.md))

## Root cause and cluster

- Cluster [C-15](../synthesis/clusters-and-root-causes.md#c-15): Seasonal, trending and competitor signals are spotted too late, by hand – raised by 2 staff + 0 leadership; confidence High.
- Root cause [RC-02](../synthesis/clusters-and-root-causes.md#rc-02): Monitoring is human: nothing pushes signals on spend, performance, tracking, link status, trends or churn, so problems surface late.
- Root cause (problem record): Content plans are set monthly from keyword research; nothing watches the calendar or industry news per client, so seasonal pages and news-driven posts are spotted by chance.

## Pain points (5)

- [KZ-PP19](../pain-points/README.md#kz-pp19) – Google Trends monitoring for Disney can only be refreshed every 2–3 days by hand, not daily
  - *"I set up a tracker, but I'm like, I can only do this once every two, three days. I can't do this every single day."* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~38:17 (L388)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L392)
- [KZ-PP20](../pain-points/README.md#kz-pp20) – Major events are missed for content because topics are spotted too late (e.g. World Series)
  - *"like a major event and we'd be too late to even think to do like a content topic or an idea for it."* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~44:01 (L443)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L447) · Austin: Agree
- [ZC-PP09](../pain-points/README.md#zc-pp09) – Seasonal content planned too late to catch peaks (\~2-month lead time)
  - *"we were just getting to those seasonal peaks too late."* – Zach Chamberlain, SEO Manager · staff-raised · [\~30:44 (L322)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L328) · Austin: Agree
- [ZC-PP15](../pain-points/README.md#zc-pp15) – No monitoring of competitors' new pages or site changes
  - *"just kind of see what they're doing and have they created a new page or whatever."* – Zach Chamberlain, SEO Manager · staff-raised · [\~32:40 (L343)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L349) · Austin: Agree
- [ZC-PP17](../pain-points/README.md#zc-pp17) – News-driven content ideas depend on the manager spotting the story
  - *"the surcharge updates in Australia was headline news. So I managed to fast track that and get it in the pipeline as soon as possible."* – Zach Chamberlain, SEO Manager · staff-raised · [\~31:43 (L333)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L339) · Austin: Agree

## Best quotes and figures

Zach: 'I recently used Claude to create a seasonal collection page calendar for a flower delivery company. Our issue was that we were getting to these too late, and once work had been completed, we didn't fully capitalise on the peak of the season/event.' Zach: 'I'm sure there are many similar updates across the client industries we work on, where we are missing out on trending topics.' Karl: 'Automate seasonality for blogs'.
