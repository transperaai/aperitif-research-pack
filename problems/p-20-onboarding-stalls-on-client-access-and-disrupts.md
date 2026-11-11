---
id: P-20
title: "Onboarding stalls on client access and disrupts BAU"
decision: "Solve later"
status: addressed
fixed_by: ["DS-09"]
also_helped_by: ["DS-08", "DS-20"]
related_only: []
clusters: ["C-09", "C-10"]
root_causes: ["RC-05", "RC-07"]
pain_points: ["KO-PP08", "KO-PP22", "KZ-PP01", "KZ-PP02", "KZ-PP03", "KZ-PP04", "MC-PP10", "MC-PP12", "MC-PP16", "MC-PP17", "SD-PP09", "SD-PP10", "SD-PP11", "ZC-PP07", "ZC-PP08"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
---

# P-20 · Onboarding stalls on client access and disrupts BAU

| | |
| --- | --- |
| Decision | **Solve later** |
| Status | addressed – Fixed by [DS-09](../solutions/ds-09-ai-prefilled-onboarding-audit-and-master-seo.md); also helped by [DS-08](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md), [DS-20](../solutions/ds-20-new-client-dossier-agent.md) |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Onboarding |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-09 AI-prefilled onboarding audit and Master SEO Document](../solutions/ds-09-ai-prefilled-onboarding-audit-and-master-seo.md)
- Also helps: [DS-08 AI sales handover: extracted from sales calls, confirmed by delivery](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md) – via cluster C-09 in text
- Also helps: [DS-20 New-client dossier agent (at signing → client brain)](../solutions/ds-20-new-client-dossier-agent.md) – "linked problem" only

## Linked opportunities

- [O-08](../opportunities/README.md#o-08) Sales-to-delivery gate: handover fields, owner, access checklist – addressed ([DS-08](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md))
- [O-14](../opportunities/README.md#o-14) AI-prefilled onboarding audit and Master SEO Document – addressed ([DS-09](../solutions/ds-09-ai-prefilled-onboarding-audit-and-master-seo.md), [DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md))
- [EI-01](../opportunities/README.md#ei-01) 1-click audit access system + AI audit workflow (also a lead magnet) – absorbed ([DS-09](../solutions/ds-09-ai-prefilled-onboarding-audit-and-master-seo.md))

## Root cause and cluster

- Cluster [C-09](../synthesis/clusters-and-root-causes.md#c-09): Client onboarding stalls waiting on access, client inputs and the tracking contractor – raised by 3 staff + 0 leadership; confidence High.
- Root cause [RC-07](../synthesis/clusters-and-root-causes.md#rc-07): External dependencies – client access, approvals, inputs, contractors and vendors – aren't contracted, time-boxed or tracked, so delivery waits.
- Cluster [C-10](../synthesis/clusters-and-root-causes.md#c-10): Onboarding work is manual and heavy; clustered starts swamp BAU and wear staff down – raised by 4 staff + 2 leadership; confidence High.
- Root cause [RC-05](../synthesis/clusters-and-root-causes.md#rc-05): There is no effort model: time per client isn't measured, scope and onboardings aren't checked against capacity, and intake isn't triaged – so work is sold, priced and scheduled by feel.
- Root cause (problem record): Access is requested manually per platform; no cap on simultaneous onboardings; the account audit is manual against a 30-item checklist.

## Pain points (15)

- [KO-PP08](../pain-points/README.md#ko-pp08) – Onboarding too many clients at once is the most common cause of team stretch; onboarding is labour-intensive
  - *Joe: "Onboarding too many clients at once, or in a short amount of time, tends to be the most common one"* – Joe Romeo, Leadership (kick-off) · staff-raised · [\~43:57 (L220)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L256)
- [KO-PP22](../pain-points/README.md#ko-pp22) – New-client research (ownership, private equity, LinkedIn profiles) is done by hand by Julia; no client dossier
  - *Julia: "if we bring on a new client, I do want to stalk them across the internet"* – Julia Van Der Linden, Leadership (kick-off) · staff-raised · [\~37:30 (L181)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L211)
- [KZ-PP01](../pain-points/README.md#kz-pp01) – Onboarding a new SEO client takes most of month one and competes with BAU; a five-site month forced out-of-hours work
  - *"onboarding takes a really long time. I don't know if Laura brought that up, but onboarding a new client is pretty hectic here as well."* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~17:23 (L164)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L168) · Austin: Agree
- [KZ-PP02](../pain-points/README.md#kz-pp02) – Onboarding effort caps how many new clients managers can take – growth is constrained by delivery time
  - *"it's pretty hard to take multiple new clients or give multiple new clients to like, for example, to Zach."* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~23:55 (L204)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L208)
- [KZ-PP03](../pain-points/README.md#kz-pp03) – Back-to-back onboardings are repetitive and demoralising for junior/new staff – a staff-retention risk
  - *"if you're new to an agency and you're a junior or a new staff member and you're just copying onboarding after onboarding"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~25:05 (L209)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L213)
- [KZ-PP04](../pain-points/README.md#kz-pp04) – Month-one deliverables are largely manual: metadata copy-paste, keyword list, and a hand-built strategy deck from GSC/GA4
  - *"This is a bit manual. We just copy-paste all the keywords basically from in here that we had."* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~19:38 (L183)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L187)
- [MC-PP10](../pain-points/README.md#mc-pp10) – Onboarding stalls on client lag – questionnaire, strategy, ad copy (4–5 revisions), previews in series
  - *"The client has like four or five revisions that needed back and forth and stuff. So that's what's taking long."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~31:22 (L271)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L274)
- [MC-PP12](../pain-points/README.md#mc-pp12) – Onboarding own client on top of team implementation overwhelms her
  - *"But if I'm onboarding a client, that's where everything changes."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~15:48 (L160)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L163)
- [MC-PP16](../pain-points/README.md#mc-pp16) – No way to see when tracking contractor has finished – repeated chasing
  - *"I'm always asking if everything's done."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~35:38 (L304)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L307) · Austin: Agree – ai to track website changes
- [MC-PP17](../pain-points/README.md#mc-pp17) – Client replies sit until next scheduled email check, losing hours in onboarding
  - *"If an account manager receives a task that's in an email… that's going to get missed until the end of the day."* – Michaela Cruz, Performance Marketing Specialist · interviewer-raised · [\~28:41 (L254)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L257)
- [SD-PP09](../pain-points/README.md#sd-pp09) – Client account access at onboarding can need a lot of chasing
  - *"Getting access from them is a bit of a friction area. Sometimes it's instant. Sometimes there's a lot of following up."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~41:01 (L414)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L421)
- [SD-PP10](../pain-points/README.md#sd-pp10) – Onboarding dependencies and approvals delay timelines; disrupts BAU; no cap on concurrent onboardings
  - *"because of how dependent the dependency there is in terms of approvals and managing a lot of people for one thing The timelines have been delayed."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~42:19 (L422)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L429)
- [SD-PP11](../pain-points/README.md#sd-pp11) – Onboarding account audit is manual, line by line, the longest step
  - *"the audit is what takes majority of the times during the whole onboarding process"* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~39:57 (L412)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L419)
- [ZC-PP07](../pain-points/README.md#zc-pp07) – Getting access from new clients (tradies, car dealers) takes a long time
  - *"trying to get the access of those kind of guys, it can take a long time."* – Zach Chamberlain, SEO Manager · staff-raised · [\~08:17 (L066)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L72)
- [ZC-PP08](../pain-points/README.md#zc-pp08) – Onboarding peaks (five in one month) overload the manager because month 1 is over-serviced
  - *"One month specifically, I had onboarding five clients in the same month."* – Zach Chamberlain, SEO Manager · staff-raised · [\~20:36 (L218)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L224)

## Best quotes and figures

Shrishti: "gaining client access is a key friction point"; account audit is the most time-consuming step; onboarding disrupts BAU for all existing clients. Karl: "Onboarding clients is hard work".
