---
id: P-11
title: "Content tracker and link sheets live outside Monday.com"
decision: "Not in proposal"
status: not_in_proposal
fixed_by: []
also_helped_by: ["DS-03"]
related_only: []
clusters: ["C-21", "C-23"]
root_causes: ["RC-01"]
pain_points: ["HT-PP05", "HT-PP09", "KO-PP16", "KZ-PP08", "MP-PP14", "MP-PP15", "SJ-PP01", "SJ-PP02", "SJ-PP03", "SJ-PP04", "SJ-PP06", "SJ-PP08", "SJ-PP10", "SJ-PP11", "TG-PP05", "TG-PP06", "TG-PP07"]
theme: "Process / automation"
severity: "Low"
confidence: "High – raised by 3+ people"
---

# P-11 · Content tracker and link sheets live outside Monday.com

| | |
| --- | --- |
| Decision | **Not in proposal** |
| Status | not in proposal – why: covered by narrower problems (C-21 content tracker, C-23 link sheets), so it isn't carried as its own item; [DS-03](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md) only "also helps" ([DS-03](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md): auto-created Monday tasks (problem not in this proposal)) |
| Theme · severity · confidence | Process / automation · Low · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Also helps: [DS-03 Automated AI brief drafts → Monday.com tasks](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md) – auto-created Monday tasks (problem not in this proposal)

## Linked opportunities

- [O-02](../opportunities/README.md#o-02) AI data rule, company Claude seats and shared skills library – addressed ([DS-02](../solutions/ds-02-ai-playbook-repository.md), [DS-25](../solutions/ds-25-ppc-performance-forecasting-tool.md))
- [O-18](../opportunities/README.md#o-18) One link record: standard order template, auto-sync, invoice run – addressed ([DS-11](../solutions/ds-11-link-building-workflow-crm.md))
- [O-20](../opportunities/README.md#o-20) Widen link supply: shared vetting skill, client matching, mentions – addressed ([DS-12](../solutions/ds-12-link-supply-engine-shared-vetting-skill-client.md), [DS-31](../solutions/ds-31-proactive-brand-mention-tracking-for-backlinks.md))
- [O-25](../opportunities/README.md#o-25) Content intake on Monday with brief standard and slots – absorbed ([DS-03](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md))

## Root cause and cluster

- Cluster [C-21](../synthesis/clusters-and-root-causes.md#c-21): Content hand-offs run on hand-copied sheets: briefs late or unseen, statuses double-keyed – raised by 2 staff + 0 leadership; confidence High.
- Root cause [RC-01](../synthesis/clusters-and-root-causes.md#rc-01): No system of record: budgets, client data, briefs, links and files are held in many hand-maintained copies, so people re-key, reconcile and collate by hand.
- Cluster [C-23](../synthesis/clusters-and-root-causes.md#c-23): Link building runs on disconnected sheets; every order, link and invoice is re-keyed – raised by 2 staff + 2 leadership; confidence High.
- Root cause [RC-01](../synthesis/clusters-and-root-causes.md#rc-01): No system of record: budgets, client data, briefs, links and files are held in many hand-maintained copies, so people re-key, reconcile and collate by hand.
- Root cause (problem record): Teams built their own trackers where Monday didn't fit their workflow; no integration back.

## Pain points (17)

- [HT-PP05](../pain-points/README.md#ht-pp05) – Freelancer work and word-count tracker in Google Sheets (some per freelancer) and email alongside Monday.com – double-ups
  - *"I think for the sake of simplicity and double ups, yeah, we should go to Monday."* – Hayley Tantau, Content Specialist · staff-raised · [\~15:53 (L177)](../interviews/ht-hayley-tantau/transcript.md?plain=1#L182) · Austin: Agree
- [HT-PP09](../pain-points/README.md#ht-pp09) – Briefs used to lack detail and context (fixed by joint training; could drift without quarterly refresh)
  - *"with the SEO specialists to kind of make the briefs better because we weren't getting what we wanted out of them."* – Hayley Tantau, Content Specialist · staff-raised · [\~05:26 (L072)](../interviews/ht-hayley-tantau/transcript.md?plain=1#L77) · Austin: Agree
- [KO-PP16](../pain-points/README.md#ko-pp16) – Link building has no CRM: publishers, orders and outstanding invoices live in spreadsheets, and there is no automatic check for dropped links
  - *Julia: "I would love, like, a CRM for our link-building team specifically. That is still being run out of spreadsheets."* – Julia Van Der Linden, Leadership (kick-off) · staff-raised · [\~79:34 (L368)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L419) · Austin: Agree
- [KZ-PP08](../pain-points/README.md#kz-pp08) – The link lead's time goes on admin (vetting, invoices) instead of developing and growing the link team
  - *"it's like typically going to like that admin side rather than like helping do bigger things and growing the team a bit more"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~11:11 (L111)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L115) · Austin: Agree
- [MP-PP14](../pain-points/README.md#mp-pp14) – Links copied by hand from tracker into CRM for reporting
  - *"When these links go into the tracker, It's still kind of manually being copied over into the CRM for reporting"* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~04:32 (L048)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L51) · Austin: Agree
- [MP-PP15](../pain-points/README.md#mp-pp15) – Link-building admin still on sheets; no capacity to improve it
  - *"there's stuff that we just can't do at the moment because we just don't have the manpower."* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~04:32 (L048)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L51) · Austin: Agree
- [SJ-PP01](../pain-points/README.md#sj-pp01) – Briefs, prior client comms and feedback copied by hand from master sheet into four freelancer sheets – her magic-wand pick
  - *"I copy all of the briefs and the, and the, like feedback or like any like prior, um, like comms I've had with the..."* – Sarah Julian, Content Manager · staff-raised · [\~04:23 (L052)](../interviews/sj-sarah-julian/transcript.md?plain=1#L55) · Austin: Agree
- [SJ-PP02](../pain-points/README.md#sj-pp02) – No single intake or alert for new briefs – a brief can sit unseen for two days against a two-week freelancer turnaround
  - *"if it's dropped in on a day that I'm not checking it Maybe it means that I would see it for two days"* – Sarah Julian, Content Manager · staff-raised · [\~05:53 (L067)](../interviews/sj-sarah-julian/transcript.md?plain=1#L70) · Austin: Agree
- [SJ-PP03](../pain-points/README.md#sj-pp03) – Briefs arrive after the week-1 deadline or change mid-month
  - *"It might be the client hasn't approved something. Maybe they want to change the strategy, yada, yada."* – Sarah Julian, Content Manager · staff-raised · [\~05:53 (L067)](../interviews/sj-sarah-julian/transcript.md?plain=1#L70) · Austin: Agree
- [SJ-PP04](../pain-points/README.md#sj-pp04) – Freelancer and edited versions copied by hand into client folders – risk of not finding the right version
  - *"we still need to differentiate between the freelancer version and the edited, like my edited version, which needs to live in obviously like our client folders"* – Sarah Julian, Content Manager · staff-raised · [\~08:38 (L092)](../interviews/sj-sarah-julian/transcript.md?plain=1#L95) · Austin: Agree
- [SJ-PP06](../pain-points/README.md#sj-pp06) – Incomplete briefs drive freelancer rework and longer editing
  - *"the editing at the end of it will be much quicker because they've got like a much more complete brief"* – Sarah Julian, Content Manager · staff-raised · [\~15:23 (L163)](../interviews/sj-sarah-julian/transcript.md?plain=1#L166) · Austin: Agree
- [SJ-PP08](../pain-points/README.md#sj-pp08) – Master content sheet is a band-aid: status typed in two places; autofill and 20k KPI formatting broken
  - *"Yeah, they don't even auto-fill properly."* – Sarah Julian, Content Manager · staff-raised · [\~22:55 (L263)](../interviews/sj-sarah-julian/transcript.md?plain=1#L266)
- [SJ-PP10](../pain-points/README.md#sj-pp10) – Work sorted by sheet age, not client importance (incl. within tier)
  - *"this is just sorted by age. You know, this is an arbitrary sorting. So really it should be like importance"* – Sarah Julian, Content Manager · staff-raised · [\~25:04 (L283–L284)](../interviews/sj-sarah-julian/transcript.md?plain=1#L286) · Austin: Agree
- [SJ-PP11](../pain-points/README.md#sj-pp11) – Volume grew \~40k → \~100k words/month; spreadsheet set-up won't scale
  - *"now we're like on 100,000 so I'm like very conscious like as we grow as we grow it's not going to be like sustainable"* – Sarah Julian, Content Manager · staff-raised · [\~06:53 (L069)](../interviews/sj-sarah-julian/transcript.md?plain=1#L72)
- [TG-PP05](../pain-points/README.md#tg-pp05) – Orders to external publishers copy-pasted into each publisher's own sheet; order numbers sometimes change
  - *"for the other publishers, since we have different sheets for them, so I copy and paste documents on the sheets"* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~04:25 (L031)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L38) · Austin: Agree
- [TG-PP06](../pain-points/README.md#tg-pp06) – Every published link re-keyed from publisher sheets into the master sheet and other sheets
  - *"And then every published links I've found here. I encode it to the master sheet."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~39:07–39:13 (L404–L405)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L411) · Austin: Agree
- [TG-PP07](../pain-points/README.md#tg-pp07) – Home-built master sheet → Monday.com sync unreliable; managers raised concerns
  - *"for the October, it added already, but I received a few concerns from the managers, from the handlers."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~41:14 (L439)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L446)

## Best quotes and figures

Content tracker and link-building sheets have no Monday task IDs or links.
