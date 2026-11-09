---
id: P-16
title: "Reminders go unacted; a broken reminder bot went unnoticed"
austin_call: "Solve now"
austin_note: "we need to modernise and make robust systems for slack bots that the team relies on"
status: addressed
fixed_by: ["DS-06", "DS-30"]
also_helped_by: []
related_only: []
clusters: ["C-30"]
root_causes: ["RC-08"]
pain_points: ["DM-PP09", "KO-PP10", "MC-PP02", "MC-PP03", "MP-PP05", "MP-PP06", "SB-PP01", "SB-PP02", "SB-PP03", "SB-PP04", "SB-PP05", "SB-PP06", "WS-PP15"]
theme: "Cultural"
severity: "Medium"
confidence: "High – raised by 3+ people"
notion_id: 40fe204ff76981e9b92fcb8a575cb3f4
---

# P-16 · Reminders go unacted; a broken reminder bot went unnoticed

| | |
| --- | --- |
| Austin's call | **Solve now** |
| Austin's note | we need to modernise and make robust systems for slack bots that the team relies on |
| Status | addressed – Fixed by [DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md), [DS-30](../solutions/ds-30-daily-priorities-assistant-one-triaged-list-per.md) |
| Theme · severity · confidence | Cultural · Medium · High – raised by 3+ people |
| Process area | People / culture |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-06 Request sweeper ("Roomba"): stray Slack, DM and email requests → Monday.com](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md)
- Fixes: [DS-30 Daily priorities assistant: one triaged list per person from Monday, Slack, email, calendar, ad/SEO performance and seasonal signals](../solutions/ds-30-daily-priorities-assistant-one-triaged-list-per.md)

## Opportunities linked in Notion

- [O-29](../opportunities/README.md#o-29) AI inbox triage and daily brief across Gmail, Slack, Monday – absorbed ([DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md), [DS-30](../solutions/ds-30-daily-priorities-assistant-one-triaged-list-per.md))
- [O-33](../opportunities/README.md#o-33) SOPs linked from Monday templates; stale pages retired – partly addressed ([DS-02](../solutions/ds-02-ai-playbook-repository.md))
- [O-06](../opportunities/README.md#o-06) All internal requests via Monday forms; Monday notifies, not people – partly addressed ([DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md))
- [O-15](../opportunities/README.md#o-15) Enter budgets once, log every change, written overspend policy – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [O-16](../opportunities/README.md#o-16) Own and verify automations: register, backup admin, reconciliation – addressed ([DS-10](../solutions/ds-10-systems-register-and-break-fix-runbook.md))
- [O-27](../opportunities/README.md#o-27) AI business brain over client records and SOPs – addressed ([DS-15](../solutions/ds-15-ai-business-brain-the-umbrella.md), [DS-04](../solutions/ds-04-ai-client-brain.md))

## Root cause and cluster

- Cluster [C-30](../synthesis/clusters-and-root-causes.md#c-30): Monday.com isn't the single home for work: requests bypass it and statuses go stale – raised by 4 staff + 1 leadership; confidence High.
- Root cause [RC-08](../synthesis/clusters-and-root-causes.md#rc-08): Adoption isn't designed or enforced: systems and SOPs are built, then assumed to be used.
- Problems DB root cause: Accountability for daily agendas depends on a bot prompt rather than on managers checking.
- Merge notes: Stage 1 merge (6 Nov): Reword → [C-30](../synthesis/clusters-and-root-causes.md#c-30). Reframe around Monday.com hygiene. Proposed rewording in body. Root cause and quotes below are pre-merge document evidence; Stage 1 root cause and anonymised quotes are in the page body.

## Pain points (13)

- [DM-PP09](../pain-points/README.md#dm-pp09) – Monday.com sends no reminders for overdue tasks; items sit in 'awaiting approval' when nobody updates them
  - *"it might be sitting under like an awaiting approval or something, even though that has been done."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~14:53 (L171)](../interviews/dm-diya-manoj/transcript.md?plain=1#L174) · Austin: Agree
- [KO-PP10](../pain-points/README.md#ko-pp10) – Staff do not follow the systems (notes not updated, ticketing not used correctly), which makes capacity hard to calculate
  - *Joe: "you can build the best system in the world, but like, people don't use it"* – Joe Romeo, Leadership (kick-off) · staff-raised · [\~20:51 (L088)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L106) · Austin: Agree
- [MC-PP02](../pain-points/README.md#mc-pp02) – Daily agenda message to manager duplicates Monday.com view and goes stale
  - *"I feel like that's kind of redundant on my end. If they have access to monday.com"* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~05:10 (L053)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L56)
- [MC-PP03](../pain-points/README.md#mc-pp03) – Priority field often blank; tasks not briefed for week ahead – no forward view
  - *"sometimes they leave this as blank which is also if that is in place that would help me prioritize my task"* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~10:33 (L106)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L109)
- [MP-PP05](../pain-points/README.md#mp-pp05) – Reminders go out but updates don't follow
  - *"Half an hour ago, the reminder went out. We still don't have updates."* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~23:43 (L259)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L262)
- [MP-PP06](../pain-points/README.md#mp-pp06) – Leadership can't see whether work is happening, especially on remote days
  - *"And that's the day people, the days people are in the office. What about the days everyone's at home?"* – Joe Romeo, Leadership (mid-point) · interviewer-raised · [\~24:25 (L274)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L277) · Austin: Agree – AI business brain to track activity
- [SB-PP01](../pain-points/README.md#sb-pp01) – Daily Claude 'Organizer' routine doesn't flag what needs action; emails and Slack asks slip and become last-minute
  - *"I still miss out on things that I need to do, like emails that I need to respond to"* – Sid Bali, Technical SEO Specialist · staff-raised · [\~03:28 (L046)](../interviews/sb-sid-bali/transcript.md?plain=1#L50)
- [SB-PP02](../pain-points/README.md#sb-pp02) – About an hour a day on email triage, much of it unnecessary
  - *"In a day, an hour."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~30:25 (L421)](../interviews/sb-sid-bali/transcript.md?plain=1#L425) · Austin: Agree
- [SB-PP03](../pain-points/README.md#sb-pp03) – Requests arrive as forwarded email chains with conflicting sheet versions; \~30 min to untangle each
  - *"And then I'm just stuck for 30 minutes trying to figure out, OK, this email is a response to this one."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~15:10 (L190)](../interviews/sb-sid-bali/transcript.md?plain=1#L194) · Austin: Agree – AI request extractor and email chains summaries tha tis also conencted to ai company/client brain to make it easier because its already loaded with all the context.
- [SB-PP04](../pain-points/README.md#sb-pp04) – Colleagues send task requests by email and Slack DM instead of Monday
  - *"not everybody uses Monday to like, you know, set up a task."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~02:50 (L039)](../interviews/sb-sid-bali/transcript.md?plain=1#L43) · Austin: Agree
- [SB-PP05](../pain-points/README.md#sb-pp05) – Read-and-archive habit buries important emails
  - *"And then I realize I've archived something that I shouldn't have."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~29:52 (L413)](../interviews/sb-sid-bali/transcript.md?plain=1#L417)
- [SB-PP06](../pain-points/README.md#sb-pp06) – As Monday admin, Sid receives every Monday change notification
  - *"because I run the Monday shindig, I get every fucking notification out there."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~28:33 (L396)](../interviews/sb-sid-bali/transcript.md?plain=1#L400)
- [WS-PP15](../pain-points/README.md#ws-pp15) – Underperformance tickets described as a HubSpot flow though tasks moved to Monday.com; Director doesn't log her own tasks
  - *"If I'm doing it myself, I don't usually add it to that as well."* – Wendlley Simoes, Performance Marketing Director · inferred · [\~31:47 (L383)](../interviews/ws-wendlley-simoes/transcript.md?plain=1#L388)

## Best quotes and figures (Problems DB)

Slack review: "Tina broke and didn't remind people to do their agenda items". Joe: agendas show minimal tasks and reminders go unacted upon.
