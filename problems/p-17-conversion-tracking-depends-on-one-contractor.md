---
id: P-17
title: "Conversion tracking depends on one contractor"
decision: "Solve later"
status: partly_addressed
fixed_by: []
also_helped_by: ["DS-01"]
related_only: []
clusters: ["C-09"]
root_causes: ["RC-07"]
pain_points: ["MC-PP10", "MC-PP16", "MC-PP17", "SD-PP09", "SD-PP10", "ZC-PP07"]
theme: "Process / automation"
severity: "Medium"
confidence: "Low – raised by 1"
---

# P-17 · Conversion tracking depends on one contractor

| | |
| --- | --- |
| Decision | **Solve later** |
| Status | partly addressed – Solve later; no DS fixes it – only "also helps" by [DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md) |
| Theme · severity · confidence | Process / automation · Medium · Low – raised by 1 |
| Process area | Onboarding |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Also helps: [DS-01 Modern ad budget pacing + performance alerting](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md)

## Linked opportunities

- [O-08](../opportunities/README.md#o-08) Sales-to-delivery gate: handover fields, owner, access checklist – addressed ([DS-08](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md))
- [O-14](../opportunities/README.md#o-14) AI-prefilled onboarding audit and Master SEO Document – addressed ([DS-09](../solutions/ds-09-ai-prefilled-onboarding-audit-and-master-seo.md), [DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md))
- [O-17](../opportunities/README.md#o-17) Cap concurrent onboardings per manager; protect BAU time – dropped

## Root cause and cluster

- Cluster [C-09](../synthesis/clusters-and-root-causes.md#c-09): Client onboarding stalls waiting on access, client inputs and the tracking contractor – raised by 3 staff + 0 leadership; confidence High.
- Root cause [RC-07](../synthesis/clusters-and-root-causes.md#rc-07): External dependencies – client access, approvals, inputs, contractors and vendors – aren't contracted, time-boxed or tracked, so delivery waits.
- Root cause (problem record): A single contractor (Liam) handles tracking for all accounts; setup is a 3–4 day onboarding step.

## Pain points (6)

- [MC-PP10](../pain-points/README.md#mc-pp10) – Onboarding stalls on client lag – questionnaire, strategy, ad copy (4–5 revisions), previews in series
  - *"The client has like four or five revisions that needed back and forth and stuff. So that's what's taking long."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~31:22 (L271)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L274)
- [MC-PP16](../pain-points/README.md#mc-pp16) – No way to see when tracking contractor has finished – repeated chasing
  - *"I'm always asking if everything's done."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~35:38 (L304)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L307) · Austin: Agree – ai to track website changes
- [MC-PP17](../pain-points/README.md#mc-pp17) – Client replies sit until next scheduled email check, losing hours in onboarding
  - *"If an account manager receives a task that's in an email… that's going to get missed until the end of the day."* – Michaela Cruz, Performance Marketing Specialist · interviewer-raised · [\~28:41 (L254)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L257)
- [SD-PP09](../pain-points/README.md#sd-pp09) – Client account access at onboarding can need a lot of chasing
  - *"Getting access from them is a bit of a friction area. Sometimes it's instant. Sometimes there's a lot of following up."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~41:01 (L414)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L421)
- [SD-PP10](../pain-points/README.md#sd-pp10) – Onboarding dependencies and approvals delay timelines; disrupts BAU; no cap on concurrent onboardings
  - *"because of how dependent the dependency there is in terms of approvals and managing a lot of people for one thing The timelines have been delayed."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~42:19 (L422)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L429)
- [ZC-PP07](../pain-points/README.md#zc-pp07) – Getting access from new clients (tradies, car dealers) takes a long time
  - *"trying to get the access of those kind of guys, it can take a long time."* – Zach Chamberlain, SEO Manager · staff-raised · [\~08:17 (L066)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L72)

## Best quotes and figures

Slack: #conversion-tracking is a group chat for a contractor who manages conversion tracking for all staff. Shrishti: setup takes 3–4 days per client. The only documentation is a 10-field memo template recording what was set up – no setup procedure, QA step, owner or date field, no enhanced-conversions field, and it isn't linked from the Google or Meta audit templates.
