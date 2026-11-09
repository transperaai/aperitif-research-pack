---
id: P-03
title: "No proactive performance alerting – problems found at month-end"
austin_call: "Solve now"
austin_note: "this can be an extension of the pacing checker or a software like revealbot (bir.ch). this would enable people to only have to check accounts when notified rather than juggling accounts or catching things late."
status: addressed
fixed_by: ["DS-01", "DS-22", "DS-23", "DS-27", "DS-29"]
also_helped_by: []
related_only: []
clusters: ["C-04"]
root_causes: ["RC-02"]
pain_points: ["DM-PP02", "DM-PP03", "LS-PP05", "MC-PP08", "MP-PP17", "SD-PP04", "SH-PP11", "SH-PP12", "WS-PP04", "ZC-PP05"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
notion_id: 40fe204ff76981d8a087ed06b4ec140a
---

# P-03 · No proactive performance alerting – problems found at month-end

| | |
| --- | --- |
| Austin's call | **Solve now** |
| Austin's note | this can be an extension of the pacing checker or a software like revealbot (bir.ch). this would enable people to only have to check accounts when notified rather than juggling accounts or catching things late. |
| Status | addressed – Fixed by [DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-22](../solutions/ds-22-seo-automated-monday-client-performance-check.md), [DS-23](../solutions/ds-23-seo-drop-and-anomaly-alerts.md), [DS-27](../solutions/ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md), [DS-29](../solutions/ds-29-ppc-automated-monday-client-performance-check.md) |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-01 Modern ad budget pacing + performance alerting](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md)
- Fixes: [DS-22 SEO: automated Monday client performance check (GA4, Search Console, Ahrefs)](../solutions/ds-22-seo-automated-monday-client-performance-check.md)
- Fixes: [DS-23 SEO: drop and anomaly alerts](../solutions/ds-23-seo-drop-and-anomaly-alerts.md)
- Fixes: [DS-27 PPC: alert investigator – AI diagnosis and commentary on flagged activity](../solutions/ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md)
- Fixes: [DS-29 PPC: automated Monday client performance check (Google Ads, Meta and other channels)](../solutions/ds-29-ppc-automated-monday-client-performance-check.md)

## Opportunities linked in Notion

- [O-01](../opportunities/README.md#o-01) Restore the pacing data feed and cover every live channel – addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [O-10](../opportunities/README.md#o-10) Switch on native platform alert rules and scripts now – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [O-11](../opportunities/README.md#o-11) Pacing tracker reads budgets and spend, flags gaps – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [O-12](../opportunities/README.md#o-12) Cross-account performance monitor with draft diagnosis (paid and SEO) – addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-27](../solutions/ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md), [DS-29](../solutions/ds-29-ppc-automated-monday-client-performance-check.md), [DS-22](../solutions/ds-22-seo-automated-monday-client-performance-check.md), [DS-23](../solutions/ds-23-seo-drop-and-anomaly-alerts.md), [DS-24](../solutions/ds-24-seo-mid-month-wins-sent-to-clients.md))
- [O-27](../opportunities/README.md#o-27) AI business brain over client records and SOPs – addressed ([DS-15](../solutions/ds-15-ai-business-brain-the-umbrella.md), [DS-04](../solutions/ds-04-ai-client-brain.md))
- [EI-13](../opportunities/README.md#ei-13) Pacing tracker + adjustment engine – partly addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [EI-15](../opportunities/README.md#ei-15) Proactive PPC monitor and anomaly detector – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-29](../solutions/ds-29-ppc-automated-monday-client-performance-check.md))

## Root cause and cluster

- Cluster [C-04](../synthesis/clusters-and-root-causes.md#c-04): Performance drops and tracking breaks surface only in manual checks, often at month-end – raised by 7 staff + 0 leadership; confidence High.
- Root cause [RC-02](../synthesis/clusters-and-root-causes.md#rc-02): Monitoring is human: nothing pushes signals on spend, performance, tracking, link status, trends or churn, so problems surface late.
- Problems DB root cause: No macro view across accounts. Consultants only see an issue when they are inside that account; the only check is a manual mid-month comparison.
- Merge notes: Stage 1 merge (6 Nov): Reword → [C-04](../synthesis/clusters-and-root-causes.md#c-04). Add SEO and tracking breaks. Proposed rewording in body. Root cause and quotes below are pre-merge document evidence; Stage 1 root cause and anonymised quotes are in the page body.

## Pain points (10)

- [DM-PP02](../pain-points/README.md#dm-pp02) – Tina pacing covers budget only; conversions and CPA/ROAS/CPL checked account by account by hand
  - *"the one Tina is sending it out is just budget basing… I look for each of the accounts, which actually takes time."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~25:27 (L307)](../interviews/dm-diya-manoj/transcript.md?plain=1#L310) · Austin: Agree
- [DM-PP03](../pain-points/README.md#dm-pp03) – No alert when an account's performance drops suddenly; found only by going into each account
  - *"if there is like a sudden drop… if you get like a weekly update, that would be like really helpful."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~16:37 (L193)](../interviews/dm-diya-manoj/transcript.md?plain=1#L196) · Austin: Agree
- [LS-PP05](../pain-points/README.md#ls-pp05) – Laura checks client performance by hand; no roll-up showing drops, red flags and wins
  - *"I still do it manually, which is silly."* – Laura Shillington, SEO Director · staff-raised · [\~14:34 (L060)](../interviews/ls-laura-shillington/transcript.md?plain=1#L75) · Austin: Agree
- [MC-PP08](../pain-points/README.md#mc-pp08) – No automated performance-trend alerting – Tina reports budget only; declines found in manual checks
  - *"I wanted Tina to report the performance of the account."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~44:09 (L409)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L412) · Austin: Agree
- [MP-PP17](../pain-points/README.md#mp-pp17) – Account data not pre-synthesised; consultants review ad accounts by hand, capping clients per head
  - *"rather than people having to synthesize that information by going onto the ad account, reviewing all the stats"* – Joe Romeo, Leadership (mid-point) · interviewer-raised · [\~01:01 (L023, Austin)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L26) · Austin: Agree
- [SD-PP04](../pain-points/README.md#sd-pp04) – No proactive alerting – issues only seen when in the account, mostly at month-end
  - *"if I'm not in the account, then there's no way of knowing."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~51:56 (L516)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L523) · Austin: Agree
- [SH-PP11](../pain-points/README.md#sh-pp11) – Tracking breaks (often unannounced client page/form changes) found only via manual performance checks, up to \~7 days later
  - *"it could potentially be that the client made changes on the landing page or website themselves and didn't tell us"* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~54:10 (L584)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L584) · Austin: Agree
- [SH-PP12](../pain-points/README.md#sh-pp12) – Meeting-heavy weeks delay checks; tracking issue discovered too late, client unhappy
  - *"you might not have the chance to review it as quickly as you would have wanted to and then discovered the tracking issue too late"* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~56:00 (L610)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L610) · Austin: Agree
- [WS-PP04](../pain-points/README.md#ws-pp04) – Alerts flag a conversion drop but give no cause; diagnosis is manual
  - *"currently we have a notification … Like, oh, we've noticed like a decrease in conversions in the past like seven, 14 days"* – Wendlley Simoes, Performance Marketing Director · staff-raised · [\~59:22 (L780)](../interviews/ws-wendlley-simoes/transcript.md?plain=1#L785) · Austin: Agree
- [ZC-PP05](../pain-points/README.md#zc-pp05) – Monday performance check often skipped when busy; dips and wins surface at month-end
  - *"I find that these can sometimes be an afterthought because you know you're busy"* – Zach Chamberlain, SEO Manager · staff-raised · [\~27:39 (L285)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L291) · Austin: Agree

## Best quotes and figures (Problems DB)

Shrishti: "only knows an account is underperforming when actively inside the platform"; "most performance issues are only caught during monthly reporting". Wendlley: wants trigger automation to investigate ad account activity and diagnose.
