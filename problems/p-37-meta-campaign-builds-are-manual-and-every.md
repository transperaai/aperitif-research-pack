---
id: P-37
title: "Meta campaign builds are manual and every ad needs hand QA"
decision: "Not in proposal"
status: not_in_proposal
fixed_by: []
also_helped_by: []
related_only: []
clusters: ["C-28"]
root_causes: ["RC-04"]
pain_points: ["DM-PP08", "MC-PP20", "SH-PP15", "SH-PP17"]
theme: "Process / automation"
severity: "Medium"
confidence: "High – raised by 3+ people"
---

# P-37 · Meta campaign builds are manual and every ad needs hand QA

| | |
| --- | --- |
| Decision | **Not in proposal** |
| Status | not in proposal – why: a small, contained quick win (3 staff) rather than a core build; can be picked up later if wanted. |
| Theme · severity · confidence | Process / automation · Medium · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- None.

## Linked opportunities

- [O-02](../opportunities/README.md#o-02) AI data rule, company Claude seats and shared skills library – addressed ([DS-02](../solutions/ds-02-ai-playbook-repository.md), [DS-25](../solutions/ds-25-ppc-performance-forecasting-tool.md))
- [O-09](../opportunities/README.md#o-09) Implementer self-QA checklists for page and ad builds – dropped

## Root cause and cluster

- Cluster [C-28](../synthesis/clusters-and-root-causes.md#c-28): Meta campaign builds are manual and every ad needs hand QA – raised by 3 staff + 0 leadership; confidence High.
- Root cause [RC-04](../synthesis/clusters-and-root-causes.md#rc-04): Tools, automations and AI workflows are built by individuals with no owner, documentation, policy or renewal plan, so they break or stay personal.
- Root cause (problem record): [RC-04](../synthesis/clusters-and-root-causes.md#rc-04): Tools and AI workflows are built by individuals with no owner. Chain: every Meta ad is checked by hand for format, placement and auto-enabled AI features ([DM-PP08](../pain-points/README.md#dm-pp08), [SH-PP15](../pain-points/README.md#sh-pp15)) → Meta has no bulk import like Google/Bing editors ([SH-PP17](../pain-points/README.md#sh-pp17)) → the one fix (a Claude preview-link skill) is on a personal account ([MC-PP20](../pain-points/README.md#mc-pp20), [MC-PP19](../pain-points/README.md#mc-pp19)) → no shared Meta build template or QA checklist.

## Pain points (4)

- [DM-PP08](../pain-points/README.md#dm-pp08) – Manager QAs every Meta ad built by specialists (20–30 per launch) to catch format/placement errors
  - *"if another person is working on it, I won't be having that clarity. I just need to go and individually check each ad."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~20:32 (L237)](../interviews/dm-diya-manoj/transcript.md?plain=1#L240)
- [MC-PP20](../pain-points/README.md#mc-pp20) – Meta preview links for \~50-ad builds tedious – solved only by personal Claude skill
  - *"And 50 ad preview links is very, very, like, a lot. So I use Claude to generate those links."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~40:16 (L354)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L357)
- [SH-PP15](../pain-points/README.md#sh-pp15) – Meta auto-enables new AI features; every build needs a manual toggle-off check
  - *"meta rolls out new things and it's like auto on and then you just have to be like super into the nitty gritty"* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~18:26 (L177)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L177)
- [SH-PP17](../pain-points/README.md#sh-pp17) – Meta builds are manual (no bulk import like Google/Bing editors)
  - *"The Google implementation is quicker because there's like this editor tool that can be used to like import an account build."* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~25:43 (L239)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L239)

## Best quotes and figures

"if another person is working on it, I won't be having that clarity. I just need to go and individually check each ad." – a performance manager ([DM-PP08](../pain-points/README.md#dm-pp08), \~20:32, L237) | "The Google implementation is quicker because there's like this editor tool that can be used to like import an account build." – a performance manager ([SH-PP17](../pain-points/README.md#sh-pp17), \~25:43, L239) | "meta rolls out new things and it's like auto on and then you just have to be like super into the nitty gritty" – a performance manager ([SH-PP15](../pain-points/README.md#sh-pp15), \~18:26, L177)
