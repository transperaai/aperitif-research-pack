---
id: P-07
title: "Paid links disappear after payment – detected manually"
austin_call: "Solve now"
austin_note: "Can use Jev AI to scan websites every 5 days to see if the content ha been deleted or removed or editted"
status: addressed
fixed_by: ["DS-07"]
also_helped_by: []
related_only: ["DS-11"]
clusters: ["C-25"]
root_causes: ["RC-02"]
pain_points: ["KZ-PP10", "MP-PP13", "TG-PP11", "ZC-PP10"]
theme: "Process / automation"
severity: "Critical"
confidence: "High – raised by 3+ people"
notion_id: 40fe204ff76981f989dcde7f6575b490
---

# P-07 · Paid links disappear after payment – detected manually

| | |
| --- | --- |
| Austin's call | **Solve now** |
| Austin's note | Can use Jev AI to scan websites every 5 days to see if the content ha been deleted or removed or editted |
| Status | addressed – Fixed by [DS-07](../solutions/ds-07-link-watchdog-agent-monitors-every-paid-link.md) |
| Theme · severity · confidence | Process / automation · Critical · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-07 Link watchdog agent: monitors every paid link](../solutions/ds-07-link-watchdog-agent-monitors-every-paid-link.md)
- Related only: [DS-11 Link-building workflow CRM (orders, publishers, links, invoicing and payments)](../solutions/ds-11-link-building-workflow-crm.md) – enables DS-07

## Opportunities linked in Notion

- [O-07](../opportunities/README.md#o-07) Automated live-link checks with publisher replacement claims – addressed ([DS-07](../solutions/ds-07-link-watchdog-agent-monitors-every-paid-link.md))

## Root cause and cluster

- Cluster [C-25](../synthesis/clusters-and-root-causes.md#c-25): Paid links vanish after payment and nobody re-checks that they stay live – raised by 3 staff + 1 leadership; confidence High.
- Root cause [RC-02](../synthesis/clusters-and-root-causes.md#rc-02): Monitoring is human: nothing pushes signals on spend, performance, tracking, link status, trends or churn, so problems surface late.
- Problems DB root cause: No automated post-placement monitoring or publisher accountability; checks are a bot column and manual notes.
- Merge notes: Stage 1 merge (6 Nov): Reword → [C-25](../synthesis/clusters-and-root-causes.md#c-25). Drop the 32% figure until [X-06](../synthesis/contradictions.md#x-06) is resolved. Proposed rewording in body. Root cause and quotes below are pre-merge document evidence; Stage 1 root cause and anonymised quotes are in the page body.

## Pain points (4)

- [KZ-PP10](../pain-points/README.md#kz-pp10) – No link QA: nobody checks that links are live, on the approved domain, still there months later, or that the domain hasn't decayed; a one-off report found \~100 dead links in \~10 m…
  - *"over the last like 10 months or whatever it was, there's like 100 links that just like were no longer working, like 404s or they took them down"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~54:38 (L546)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L550) · Austin: Agree
- [MP-PP13](../pain-points/README.md#mp-pp13) – Publishers remove paid links after payment; nobody checks they're still live
  - *"we don't have a way to currently check whether these are dropping off"* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~04:32 (L048)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L51) · Austin: Agree
- [TG-PP11](../pain-points/README.md#tg-pp11) – Link-status checker accuracy uncertain
  - *"if you could see other easier or more accurate way to checking it, really helpful."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~33:55 (L352)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L359) · Austin: Agree
- [ZC-PP10](../pain-points/README.md#zc-pp10) – No visibility on whether paid links stay live; no account lead re-checks old links
  - *"Yeah, we have no visibility on whether links stay live or not."* – Zach Chamberlain, SEO Manager · staff-raised · [\~36:35 (L373)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L379) · Austin: Agree

## Best quotes and figures (Problems DB)

Master Outreach Sheet: of \~1,016 links checked Jan–Apr 2026, 32% had a hard fault (wrong anchor, wrong destination, missing, 404). Checking stopped after April – none of the \~1,500 links placed May–Oct has been checked. Order book 'Bot Says' blank on 287 of 293 Aug, 168 of 336 Sep, 107 of 312 Oct rows. 346 of 451 Do Not Use domains are still on outreacher tabs; 26 domains are on both Approved and Do Not Use. Joe: 'links are sometimes removed shortly after payment'. Zach: 'we don't really have any process or visibility on links that are removed'.
