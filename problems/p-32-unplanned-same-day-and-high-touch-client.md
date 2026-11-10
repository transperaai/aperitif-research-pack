---
id: P-32
title: "Unplanned same-day and high-touch client requests break the planned month"
austin_call: "Not in proposal"
austin_note: "Why: mainly a scoping and client-expectation issue, which a build doesn't fix; the capacity freed by the proposed builds gives some headroom for it."
status: not_in_proposal
fixed_by: []
also_helped_by: ["DS-03", "DS-06"]
related_only: []
clusters: ["C-18"]
root_causes: ["RC-05"]
pain_points: ["HT-PP01", "HT-PP02", "KZ-PP05", "KZ-PP23", "MC-PP01", "SB-PP15", "SJ-PP14"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
notion_id: 410e204ff769819496a5d0c622b9e531
---

# P-32 · Unplanned same-day and high-touch client requests break the planned month

| | |
| --- | --- |
| Austin's call | **Not in proposal** |
| Austin's note | Why: mainly a scoping and client-expectation issue, which a build doesn't fix; the capacity freed by the proposed builds gives some headroom for it. |
| Status | not in proposal – why: mainly a scoping and client-expectation issue, which a build doesn't fix; the capacity freed by the proposed builds gives some headroom for it.; [DS-03](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md), [DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md) only "also helps" ([DS-03](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md): slots and cut-offs for the out-of-cycle client, text only) ([DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md): via cluster [C-18](../synthesis/clusters-and-root-causes.md#c-18) in text) |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Also helps: [DS-03 Automated AI brief drafts → Monday.com tasks](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md) – slots and cut-offs for the out-of-cycle client, text only
- Also helps: [DS-06 Request sweeper ("Roomba"): stray Slack, DM and email requests → Monday.com](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md) – via cluster C-18 in text

## Opportunities linked in Notion

- [O-03](../opportunities/README.md#o-03) AI brief drafts from the Master SEO Document – addressed ([DS-03](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md))
- [O-06](../opportunities/README.md#o-06) All internal requests via Monday forms; Monday notifies, not people – partly addressed ([DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md))
- [O-17](../opportunities/README.md#o-17) Cap concurrent onboardings per manager; protect BAU time – dropped
- [O-19](../opportunities/README.md#o-19) Effort model: hours per client, load triggers, rebalanced books – dropped
- [O-25](../opportunities/README.md#o-25) Content intake on Monday with brief standard and slots – absorbed ([DS-03](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md))
- [O-26](../opportunities/README.md#o-26) Spread editing: checklist, trained backup editors, junior writer – partly addressed ([DS-04](../solutions/ds-04-ai-client-brain.md))

## Root cause and cluster

- Cluster [C-18](../synthesis/clusters-and-root-causes.md#c-18): Unplanned same-day and high-touch client requests break the planned month – raised by 5 staff + 0 leadership; confidence High.
- Root cause [RC-05](../synthesis/clusters-and-root-causes.md#rc-05): There is no effort model: time per client isn't measured, scope and onboardings aren't checked against capacity, and intake isn't triaged – so work is sold, priced and scheduled by feel.
- Problems DB root cause: [RC-05](../synthesis/clusters-and-root-causes.md#rc-05): No effort model; intake isn't triaged. Chain: planned days and month-end deadlines break under same-day requests ([MC-PP01](../pain-points/README.md#mc-pp01), [HT-PP01](../pain-points/README.md#ht-pp01), [SB-PP15](../pain-points/README.md#sb-pp15)) → a few high-touch clients sit outside the normal cycle ([HT-PP02](../pain-points/README.md#ht-pp02), [SJ-PP14](../pain-points/README.md#sj-pp14), [KZ-PP23](../pain-points/README.md#kz-pp23)) → brief, report and client deadlines cluster ([KZ-PP05](../pain-points/README.md#kz-pp05)) → no intake triage, service level or buffer rule for unplanned work.
- Merge notes: Stage 1 merge (6 Nov): New – [C-18](../synthesis/clusters-and-root-causes.md#c-18). 5 staff. Related to R21 (capacity). Members: [HT-PP01](../pain-points/README.md#ht-pp01), [HT-PP02](../pain-points/README.md#ht-pp02), [SJ-PP14](../pain-points/README.md#sj-pp14), [KZ-PP23](../pain-points/README.md#kz-pp23), [KZ-PP05](../pain-points/README.md#kz-pp05), [SB-PP15](../pain-points/README.md#sb-pp15), [MC-PP01](../pain-points/README.md#mc-pp01)

## Pain points (7)

- [HT-PP01](../pain-points/README.md#ht-pp01) – End of month is crunchy: own work must be done by the 24th so freelancer overflow can be edited in the last week
  - *"So the end of the month is often crunchy"* – Hayley Tantau, Content Specialist · staff-raised · [\~13:12 (L150)](../interviews/ht-hayley-tantau/transcript.md?plain=1#L155)
- [HT-PP02](../pain-points/README.md#ht-pp02) – One high-priority client sits outside the content cycle – not briefed by SEO, sends last-minute work; writers hold buffer
  - *"even the seo tech doesn't brief it, they just give us things to do at the last minute."* – Hayley Tantau, Content Specialist · staff-raised · [\~13:57 (L155)](../interviews/ht-hayley-tantau/transcript.md?plain=1#L160)
- [KZ-PP05](../pain-points/README.md#kz-pp05) – Deadlines cluster: briefs due in the last days of the month, reports in week one, plus client priorities – 'pretty chaotic'
  - *"client priorities kind of dropping in at the same time, it can get like pretty chaotic to like get everything done together."* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~10:01 (L108)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L112)
- [KZ-PP23](../pain-points/README.md#kz-pp23) – One high-touch client's daily requests force other clients' work to be scheduled around it
  - *"if like another one or two clients come up during the week and they need something, I've got to like map that around Disney a lot of the time"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~16:52 (L160)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L164)
- [MC-PP01](../pain-points/README.md#mc-pp01) – Implementation tasks briefed mid-day (often after Performance team call) and needed same day – planned day breaks
  - *"they'll briefing it in like middle of the day. But sometimes they need it on that day as well."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~14:03 (L130–L131)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L133)
- [SB-PP15](../pain-points/README.md#sb-pp15) – Constant ad hoc requests and sub-problems push planned tickets into an overdue catch-up week
  - *"there will be overdue tickets always."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~24:50 (L354)](../interviews/sb-sid-bali/transcript.md?plain=1#L358)
- [SJ-PP14](../pain-points/README.md#sj-pp14) – One client sends a steady stream of ad hoc content work
  - *"we have this one client that's always like giving like work all the time."* – Sarah Julian, Content Manager · staff-raised · [\~15:15 (L162)](../interviews/sj-sarah-julian/transcript.md?plain=1#L165)

## Best quotes and figures (Problems DB)

"even the seo tech doesn't brief it, they just give us things to do at the last minute." – a content team member ([HT-PP02](../pain-points/README.md#ht-pp02), \~13:57, L155) | "they'll [brief] it in like middle of the day. But sometimes they need it on that day as well." – a performance team member ([MC-PP01](../pain-points/README.md#mc-pp01), \~14:03, L130–L131) | "if like another one or two clients come up during the week and they need something, I've got to like map that around [one high-touch client] a lot of the time" – an SEO manager ([KZ-PP23](../pain-points/README.md#kz-pp23), \~16:52, L160)
