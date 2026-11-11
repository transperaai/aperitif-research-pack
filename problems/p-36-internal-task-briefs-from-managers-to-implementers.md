---
id: P-36
title: "Internal task briefs from managers to implementers are slow to write and often incomplete"
decision: "Solve now"
status: addressed
fixed_by: ["DS-06"]
also_helped_by: []
related_only: []
clusters: ["C-27"]
root_causes: ["RC-03"]
pain_points: ["DM-PP13", "LS-PP14", "MC-PP04", "MC-PP05", "SH-PP10"]
theme: "Process / automation"
severity: "Medium"
confidence: "High – raised by 3+ people"
---

# P-36 · Internal task briefs from managers to implementers are slow to write and often incomplete

| | |
| --- | --- |
| Decision | **Solve now** |
| Status | addressed – Fixed by [DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md) |
| Theme · severity · confidence | Process / automation · Medium · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-06 Request sweeper ("Roomba"): stray Slack, DM and email requests → Monday.com](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md)

## Linked opportunities

- [O-06](../opportunities/README.md#o-06) All internal requests via Monday forms; Monday notifies, not people – partly addressed ([DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md))
- [O-11](../opportunities/README.md#o-11) Pacing tracker reads budgets and spend, flags gaps – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [EI-16](../opportunities/README.md#ei-16) Proposal generator – absorbed ([DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md))

## Root cause and cluster

- Cluster [C-27](../synthesis/clusters-and-root-causes.md#c-27): Internal task briefs from managers to implementers are slow to write and often incomplete – raised by 4 staff + 0 leadership; confidence High.
- Root cause [RC-03](../synthesis/clusters-and-root-causes.md#rc-03): Client context isn't captured per client, so every hand-off – sales to delivery, manager to writer or specialist, cover – loses detail.
- Root cause (problem record): [RC-03](../synthesis/clusters-and-root-causes.md#rc-03): Client context isn't captured per client, so hand-offs lose detail. Chain: managers do minor changes themselves rather than brief; implementers chase missing details ([DM-PP13](../pain-points/README.md#dm-pp13), [MC-PP04](../pain-points/README.md#mc-pp04)) → briefs written from scratch per task and arrive incomplete ([SH-PP10](../pain-points/README.md#sh-pp10), [LS-PP14](../pain-points/README.md#ls-pp14)) → Monday.com notifications don't always land ([MC-PP05](../pain-points/README.md#mc-pp05)) → no task-type brief templates with required fields.

## Pain points (5)

- [DM-PP13](../pain-points/README.md#dm-pp13) – Briefing specialists costs enough time that the manager does minor changes herself
  - *"briefing requires another time. So better do it yourself so that it's all sorted."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~05:47 (L076)](../interviews/dm-diya-manoj/transcript.md?plain=1#L79)
- [LS-PP14](../pain-points/README.md#ls-pp14) – Team requests to Laura vary in quality (one sentence versus a full brief)
  - *"Some will send one sentence and I need more."* – Laura Shillington, SEO Director · staff-raised · [\~12:06 (L048)](../interviews/ls-laura-shillington/transcript.md?plain=1#L60) · Austin: Agree – need to standardies requests
- [MC-PP04](../pain-points/README.md#mc-pp04) – Briefs sometimes miss details – chases account manager
  - *"Oh, sometimes I need… to chase up the account manager for details."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~45:52 (L431–L432)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L434) · Austin: Agree – need to standardies requests
- [MC-PP05](../pain-points/README.md#mc-pp05) – Monday.com notifications don't always reach AM; Slack used as backup
  - *"Sometimes Monday.com doesn't notify them."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~11:13 (L109)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L112)
- [SH-PP10](../pain-points/README.md#sh-pp10) – Briefing optimisations to Michaela/Tati is slow and manual; the step she most wants sped up
  - *"If there's like a speedy way of like getting that brief to the girls."* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~35:33 (L343)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L343) · Austin: Agree – need to standardies requests

## Best quotes and figures

"briefing requires another time. So better do it yourself so that it's all sorted." – a performance manager ([DM-PP13](../pain-points/README.md#dm-pp13), \~05:47, L076) | "Oh, sometimes I need… to chase up the account manager for details." – a performance team member ([MC-PP04](../pain-points/README.md#mc-pp04), \~45:52, L431–L432) | "Some will send one sentence and I need more." – an SEO manager ([LS-PP14](../pain-points/README.md#ls-pp14), \~12:06, L048)
