---
id: P-04
title: "Client-call prep takes longer than the call"
decision: "Solve now"
status: addressed
fixed_by: ["DS-04", "DS-25"]
also_helped_by: []
related_only: []
clusters: ["C-05"]
root_causes: ["RC-01"]
pain_points: ["DM-PP01", "DM-PP05", "SD-PP05", "SD-PP06", "SD-PP13", "SD-PP14", "SH-PP13", "WS-PP03", "WS-PP12"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
---

# P-04 · Client-call prep takes longer than the call

| | |
| --- | --- |
| Decision | **Solve now** |
| Status | addressed – Fixed by [DS-04](../solutions/ds-04-ai-client-brain.md), [DS-25](../solutions/ds-25-ppc-performance-forecasting-tool.md) |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Reporting |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-04 AI client brain (per client) – under the AI Business Brain banner](../solutions/ds-04-ai-client-brain.md)
- Fixes: [DS-25 PPC: performance forecasting tool](../solutions/ds-25-ppc-performance-forecasting-tool.md)

## Linked opportunities

- [O-02](../opportunities/README.md#o-02) AI data rule, company Claude seats and shared skills library – addressed ([DS-02](../solutions/ds-02-ai-playbook-repository.md), [DS-25](../solutions/ds-25-ppc-performance-forecasting-tool.md))
- [O-12](../opportunities/README.md#o-12) Cross-account performance monitor with draft diagnosis (paid and SEO) – addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-27](../solutions/ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md), [DS-29](../solutions/ds-29-ppc-automated-monday-client-performance-check.md), [DS-22](../solutions/ds-22-seo-automated-monday-client-performance-check.md), [DS-23](../solutions/ds-23-seo-drop-and-anomaly-alerts.md), [DS-24](../solutions/ds-24-seo-mid-month-wins-sent-to-clients.md))
- [O-13](../opportunities/README.md#o-13) AI per-client summary for reports, calls and data questions – absorbed ([DS-04](../solutions/ds-04-ai-client-brain.md))
- [EI-12](../opportunities/README.md#ei-12) Meeting transcripts → per-client action runsheet – absorbed ([DS-04](../solutions/ds-04-ai-client-brain.md))
- [EI-07](../opportunities/README.md#ei-07) Individual AI client Brains – absorbed ([DS-04](../solutions/ds-04-ai-client-brain.md))

## Root cause and cluster

- Cluster [C-05](../synthesis/clusters-and-root-causes.md#c-05): Managers spend hours collating data across platforms for calls, queries and analysis – raised by 4 staff + 0 leadership; confidence High.
- Root cause [RC-01](../synthesis/clusters-and-root-causes.md#rc-01): No system of record: budgets, client data, briefs, links and files are held in many hand-maintained copies, so people re-key, reconcile and collate by hand.
- Root cause (problem record): Data for a client lives in each ad platform separately; it is collated by hand before every call.

## Pain points (9)

- [DM-PP01](../pain-points/README.md#dm-pp01) – Answering even a Google Ads question means jumping across CRM, GA4 and other platforms
  - *"Even though it's a Google Ads related question, I'll be jumping onto the CRM, GA4 and everything to better understand."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~02:52 (L046)](../interviews/dm-diya-manoj/transcript.md?plain=1#L49) · Austin: Agree
- [DM-PP05](../pain-points/README.md#dm-pp05) – \~30 min data review before every monthly WIP call
  - *"for every monthly bit, what I do is I put like a 30 minutes just before that call to analyze the data"* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~21:42 (L257)](../interviews/dm-diya-manoj/transcript.md?plain=1#L260) · Austin: Agree
- [SD-PP05](../pain-points/README.md#sd-pp05) – Call prep and follow-up take 1 h–1 h 15 per 30-min call, mostly data collation
  - *"for a half an hour call, I'm basically spending about one hour, one hour, 15 minutes on that specific client"* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~18:36 (L161)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L168) · Austin: Agree
- [SD-PP06](../pain-points/README.md#sd-pp06) – AI note-taker action items not accurate enough; follow-ups still manual
  - *"It still doesn't do the most accurate job of sending the action items as discussed."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~18:59 (L162)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L169) · Austin: Agree
- [SD-PP13](../pain-points/README.md#sd-pp13) – Tier 1 (Five Good Friends) analysis needs manual reconciliation across several sources of truth
  - *"there's a lot of data processing involved with this client specifically because they have a lot of different sources of truths."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~09:32 (L076)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L83) · Austin: Agree
- [SD-PP14](../pain-points/README.md#sd-pp14) – Data collation, not analysis, is where the time goes – including much of Tati's work
  - *"a lot of daddies [Tati's] work goes in just collating that data very manually."* – Shrishti Dokwal, Senior Performance Marketing Manager · interviewer-raised · [\~47:51 (L489)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L496) · Austin: Agree
- [SH-PP13](../pain-points/README.md#sh-pp13) – Note-takers capture meetings but actions and talking points still extracted by hand; risk of missing client interests
  - *"we tried to add like note takers to meetings. But then it's like from those notes. taking the actions, conveying the"* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~40:37 (L396–L398)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L396) · Austin: Agree
- [WS-PP03](../pain-points/README.md#ws-pp03) – Platform recommendations ignore account strategy (location splits, client-agreed budgets); analysis means consolidating by hand
  - *"if you knew that the campaigns are separated by location … you need to understand a little bit more out of the strategy"* – Wendlley Simoes, Performance Marketing Director · staff-raised · [\~25:57 (L315)](../interviews/ws-wendlley-simoes/transcript.md?plain=1#L320) · Austin: Agree
- [WS-PP12](../pain-points/README.md#ws-pp12) – Forecasting used to take hours of manual data work; external shocks make history unreliable
  - *"I used to take like hours doing this and Gemini did it in like 15 minutes"* – Wendlley Simoes, Performance Marketing Director · staff-raised · [\~38:18 (L462)](../interviews/ws-wendlley-simoes/transcript.md?plain=1#L467) · Austin: Agree

## Best quotes and figures

Shrishti: \~1h15 to prepare for a 30–45 min call; "most pain comes from pulling data from multiple sources, not the analysis itself". Wendlley: "better optics of what's happening in the ad account so you can make better decisions".
