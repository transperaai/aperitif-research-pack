---
id: P-02
title: "Budgets maintained by hand in three places; some channels (incl. LinkedIn) not tracked; a missed budget change cost a $10K credit"
decision: "Solve now"
status: addressed
fixed_by: ["DS-01"]
also_helped_by: []
related_only: []
clusters: ["C-01", "C-03"]
root_causes: ["RC-01", "RC-02"]
pain_points: ["MC-PP07", "MP-PP01", "MP-PP02", "SD-PP02", "SD-PP03", "SH-PP01", "SH-PP03", "SH-PP04", "WS-PP02"]
theme: "Process / automation"
severity: "Critical"
confidence: "High – raised by 3+ people"
---

# P-02 · Budgets maintained by hand in three places; some channels (incl. LinkedIn) not tracked; a missed budget change cost a \$10K credit

| | |
| --- | --- |
| Decision | **Solve now** |
| Status | addressed – Fixed by [DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md) |
| Theme · severity · confidence | Process / automation · Critical · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-01 Modern ad budget pacing + performance alerting](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md)

## Linked opportunities

- [O-01](../opportunities/README.md#o-01) Restore the pacing data feed and cover every live channel – addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [O-11](../opportunities/README.md#o-11) Pacing tracker reads budgets and spend, flags gaps – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [O-15](../opportunities/README.md#o-15) Enter budgets once, log every change, written overspend policy – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [EI-13](../opportunities/README.md#ei-13) Pacing tracker + adjustment engine – partly addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))

## Root cause and cluster

- Cluster [C-01](../synthesis/clusters-and-root-causes.md#c-01): Paid budgets re-keyed by hand in three places, so pacing runs against wrong figures – raised by 3 staff + 1 leadership; confidence High.
- Root cause [RC-01](../synthesis/clusters-and-root-causes.md#rc-01): No system of record: budgets, client data, briefs, links and files are held in many hand-maintained copies, so people re-key, reconcile and collate by hand.
- Cluster [C-03](../synthesis/clusters-and-root-causes.md#c-03): Ad channels beyond Google and Meta have no pacing, so overspends go unseen – raised by 1 staff + 1 leadership; confidence Medium.
- Root cause [RC-02](../synthesis/clusters-and-root-causes.md#rc-02): Monitoring is human: nothing pushes signals on spend, performance, tracking, link status, trends or churn, so problems surface late.
- Root cause (problem record): No single source of truth for client budgets. Day 1 of each month budgets are re-keyed into the budget sheet, the pacing sheet and the ad platforms; channels outside Google/Meta (LinkedIn) sit on a side tab with gaps. 8 of 61 Google Ads rows have no manager.

## Pain points (9)

- [MC-PP07](../pain-points/README.md#mc-pp07) – Day 1 each month is a full day of manual budget reverts and pacing-sheet setup
  - *"that's what my whole day would look like, just changing budgets and stuff"* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~20:51 (L201)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L204) · Austin: Agree
- [MP-PP01](../pain-points/README.md#mp-pp01) – Budget changes not entered in pacing sheet; tracker paces against wrong number; overspend paid by agency
  - *"The budget would change and they wouldn't update the sheet. So the trackers are tracking. but it's on the wrong number."* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~31:44 (L377–L378)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L380) · Austin: Agree
- [MP-PP02](../pain-points/README.md#mp-pp02) – LinkedIn had no pacing tracker
  - *"I probably should set up a pacing track with the LinkedIn and then bang, this happens."* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~44:41 (L577)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L580) · Austin: Agree
- [SD-PP02](../pain-points/README.md#sd-pp02) – Budget allocations keyed by hand into three places
  - *"One is the Google Sheet, one is the Pacing Sheet, and the other is the platform itself."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~26:49 (L243)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L250) · Austin: Agree
- [SD-PP03](../pain-points/README.md#sd-pp03) – Underspend adjustments calculated manually, 15–20 min per account
  - *"It's a bit manual. I'm sure there's a better way of doing it"* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~28:40 (L281)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L288) · Austin: Agree
- [SH-PP01](../pain-points/README.md#sh-pp01) – Budget and fee data held separately in HubSpot, Monday and pacing sheets; every change re-keyed in three places
  - *"I'll update it on Monday I'll make sure it's reflected in HubSpot and then the pacing sheet"* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~22:33 (L213)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L213) · Austin: Agree
- [SH-PP03](../pain-points/README.md#sh-pp03) – New month means duplicating formulas to a new tab by hand
  - *"It would be duplicating the formulas and whatnot to a new tab and then creating that one. And it's a lot of manual work."* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~21:32 (L201)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L201) · Austin: Agree
- [SH-PP04](../pain-points/README.md#sh-pp04) – Stale sheet triggers false over/underspend Slack alerts
  - *"the Slack message will say like, oh, it's under, overspending but I know that the new budget is increased so the overspend is not true"* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~22:33 (L213)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L213) · Austin: Agree
- [WS-PP02](../pain-points/README.md#ws-pp02) – Pacing covers only Google and Meta; LinkedIn, ChatGPT ads, Criteo, Pinterest, TikTok untracked; overspends have happened
  - *"We have had a couple of issues with pacing, etc. and accounts. … overspending and stuff"* – Wendlley Simoes, Performance Marketing Director · staff-raised · [\~42:27 (L517–L518)](../interviews/ws-wendlley-simoes/transcript.md?plain=1#L522) · Austin: Agree

## Best quotes and figures

Joe: recent \$10K LinkedIn overspend – LinkedIn had no pacing tracker and the existing tracker had the wrong budget figure due to a manual update failure. Google Ads pacing sheet LinkedIn Budgets tab: 2 clients, one with no budget. Google Ads clients grew from 18 (Dec 2022) to 61 (Nov 2026) and combined monthly budget from \~\$30K to \~\$788K, all on one hand-maintained sheet; manager column blank on 64 of 68 rows in May 2026 and 8 of 61 in Nov. Shrishti: pacing voted #1 pain point; \~15–20 min manual calculation per account; budgets updated in three places each month.
