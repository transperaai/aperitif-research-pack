---
id: P-29
title: "Page builds and content uploads reach clients with errors or loop for weeks"
austin_call: "Not in proposal"
austin_note: "Why: the fix (O-09, build QA) was dropped by Austin on 9 Nov; the cause is unclear requirements and build QA, which is process, not a build."
status: not_in_proposal
fixed_by: []
also_helped_by: []
related_only: []
clusters: ["C-13"]
root_causes: ["RC-07"]
pain_points: ["KZ-PP13", "LS-PP10", "SB-PP07", "SB-PP08"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
notion_id: 410e204ff769811096cfd291b9f670da
---

# P-29 · Page builds and content uploads reach clients with errors or loop for weeks

| | |
| --- | --- |
| Austin's call | **Not in proposal** |
| Austin's note | Why: the fix (O-09, build QA) was dropped by Austin on 9 Nov; the cause is unclear requirements and build QA, which is process, not a build. |
| Status | not in proposal – why: Not solving in this proposal – the fix ([O-09](../opportunities/README.md#o-09)) was dropped (Austin, 9 Nov). |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- None.

## Opportunities linked in Notion

- [O-09](../opportunities/README.md#o-09) Implementer self-QA checklists for page and ad builds – dropped

## Root cause and cluster

- Cluster [C-13](../synthesis/clusters-and-root-causes.md#c-13): Page builds and content uploads reach clients with errors or loop for weeks – raised by 3 staff + 0 leadership; confidence High.
- Root cause [RC-07](../synthesis/clusters-and-root-causes.md#rc-07): External dependencies – client access, approvals, inputs, contractors and vendors – aren't contracted, time-boxed or tracked, so delivery waits.
- Problems DB root cause: [RC-07](../synthesis/clusters-and-root-causes.md#rc-07): External dependencies aren't contracted, time-boxed or tracked. Chain: clients find layout/implementation errors first, or pages loop for weeks ([KZ-PP13](../pain-points/README.md#kz-pp13), [LS-PP10](../pain-points/README.md#ls-pp10), [SB-PP07](../pain-points/README.md#sb-pp07)) → implementers aren't web developers and there's no cross-device QA checklist ([KZ-PP13](../pain-points/README.md#kz-pp13)) → requirements aren't fixed before build; CMS complexity adds relay rounds ([SB-PP07](../pain-points/README.md#sb-pp07), [SB-PP08](../pain-points/README.md#sb-pp08)) → no spec–build–QA–sign-off step for page builds.
- Merge notes: Stage 1 merge (6 Nov): New – [C-13](../synthesis/clusters-and-root-causes.md#c-13). 3 staff. Partly overlaps R5's 'errors reach clients', but the cause is build QA and unclear requirements, not document duplication. Members: [KZ-PP13](../pain-points/README.md#kz-pp13), [LS-PP10](../pain-points/README.md#ls-pp10), [SB-PP07](../pain-points/README.md#sb-pp07), [SB-PP08](../pain-points/README.md#sb-pp08)

## Pain points (4)

- [KZ-PP13](../pain-points/README.md#kz-pp13) – Page builds reach clients with errors (especially mobile layouts) – implementers aren't web developers and there's no structured cross-device QA
  - *"sometimes you just don't pick things up and then the client sees it first and they're not happy."* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~55:27 (L551)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L555) · Austin: Agree
- [LS-PP10](../pain-points/README.md#ls-pp10) – Content implementation errors reach clients
  - *"a few content implementation errors, where the client said it wasn't done right"* – Laura Shillington, SEO Director · staff-raised · [\~11:29 (L046)](../interviews/ls-laura-shillington/transcript.md?plain=1#L58) · Austin: Agree
- [SB-PP07](../pain-points/README.md#sb-pp07) – Web page uploads loop with clients for weeks over pixels and elements; requirements unclear and client team changes its mind
  - *"I have been going back and forth. for a month. for a singular page."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~16:16 (L204–L206)](../interviews/sb-sid-bali/transcript.md?plain=1#L208) · Austin: Agree
- [SB-PP08](../pain-points/README.md#sb-pp08) – Webflow is complex; clients can't find controls so Sid relays and does edits
  - *"Like Webflow is not easy."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~18:36 (L231)](../interviews/sb-sid-bali/transcript.md?plain=1#L235)

## Best quotes and figures (Problems DB)

"sometimes you just don't pick things up and then the client sees it first and they're not happy." – an SEO manager ([KZ-PP13](../pain-points/README.md#kz-pp13), \~55:27, L551) | "I have been going back and forth. for a month. for a singular page." – a technical SEO team member ([SB-PP07](../pain-points/README.md#sb-pp07), \~16:16, L204–L206)
