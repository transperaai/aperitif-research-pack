---
id: P-39
title: "HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost"
austin_call: "Park"
austin_note: "Sid Bali made this duct tape solution, he should own it. I think a gap repository needs to be kept so he can actually make these changes as they are found. (claude can you add this to solutions please)"
status: parked
fixed_by: []
also_helped_by: ["DS-10"]
related_only: []
clusters: ["C-31"]
root_causes: ["RC-04"]
pain_points: ["KO-PP11", "KO-PP12", "MC-PP13", "SB-PP10"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
notion_id: 410e204ff76981998f05d3821fbd38e3
---

# P-39 · HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost

| | |
| --- | --- |
| Austin's call | **Park** |
| Austin's note | Sid Bali made this duct tape solution, he should own it. I think a gap repository needs to be kept so he can actually make these changes as they are found. (claude can you add this to solutions please) |
| Status | parked – Parked by Austin: Sid Bali made this duct tape solution, he should own it. I think a gap repository needs to be kept so he can actually make these changes as they are found. (claude can you add this to solutions please); [DS-10](../solutions/ds-10-systems-register-and-break-fix-runbook.md) only "also helps" ([DS-10](../solutions/ds-10-systems-register-and-break-fix-runbook.md): "also helps (you parked this problem)") |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Other |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Also helps: [DS-10 Systems register and break-fix runbook (everything built, who owns it, what to do when it breaks)](../solutions/ds-10-systems-register-and-break-fix-runbook.md) – "also helps (you parked this problem)"

## Opportunities linked in Notion

- [O-08](../opportunities/README.md#o-08) Sales-to-delivery gate: handover fields, owner, access checklist – addressed ([DS-08](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md))
- [O-16](../opportunities/README.md#o-16) Own and verify automations: register, backup admin, reconciliation – addressed ([DS-10](../solutions/ds-10-systems-register-and-break-fix-runbook.md))
- [EI-18](../opportunities/README.md#ei-18) Replace HubSpot – dropped

## Root cause and cluster

- Cluster [C-31](../synthesis/clusters-and-root-causes.md#c-31): HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost – raised by 2 staff + 1 leadership; confidence High.
- Root cause [RC-04](../synthesis/clusters-and-root-causes.md#rc-04): Tools, automations and AI workflows are built by individuals with no owner, documentation, policy or renewal plan, so they break or stay personal.
- Problems DB root cause: [RC-04](../synthesis/clusters-and-root-causes.md#rc-04): Automations are built by individuals with no owner, spec or testing. Chain: monthly work orders may be missing tasks and every new client gets the wrong owner ([KO-PP11](../pain-points/README.md#ko-pp11), [SB-PP10](../pain-points/README.md#sb-pp10)) → the Make/Monday rebuild of the HubSpot automation lost nuances and hasn't been checked against scope ([KO-PP11](../pain-points/README.md#ko-pp11)) → HubSpot drops all onboarding tasks at once with no staged sequence ([MC-PP13](../pain-points/README.md#mc-pp13)) → integrations rebuilt without a spec, test cases or reconciliation report.
- Merge notes: Stage 1 merge (6 Nov): New – [C-31](../synthesis/clusters-and-root-causes.md#c-31). 2 staff + 1 leadership. HubSpot \~\$22–25K/yr plus Monday.com \~\$1,000/month ([KO-PP12](../pain-points/README.md#ko-pp12), leadership-only). COI: KO-O06/KO-O07 would be Transpera builds. Members: [KO-PP11](../pain-points/README.md#ko-pp11), [KO-PP12](../pain-points/README.md#ko-pp12), [SB-PP10](../pain-points/README.md#sb-pp10), [MC-PP13](../pain-points/README.md#mc-pp13)

## Pain points (4)

- [KO-PP11](../pain-points/README.md#ko-pp11) – HubSpot-to-Monday.com monthly work-order sync is unverified; Joe suspects tasks are being missed because the Monday version was rebuilt without all the nuances
  - *Joe: "I'm not fully confident that it's working correctly. Stuff's getting missed."* – Joe Romeo, Leadership (kick-off) · staff-raised · [\~62:00 (L303)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L345) · Austin: Agree
- [KO-PP12](../pain-points/README.md#ko-pp12) – Monday.com costs about \$1,000 a month and the founder sees it as an unnecessary cost that is not purpose-built; HubSpot is still about \$22–25K a year
  - *Joe: "Monday.com for me is the one I'm least satisfied with, 'cause I just see it as a cost."* – Joe Romeo, Leadership (kick-off) · staff-raised · [\~79:16 (L367)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L418) · Austin: Agree
- [MC-PP13](../pain-points/README.md#mc-pp13) – HubSpot drops every onboarding task at once – no staged, guided sequence
  - *"So the first time I onboarded a client, I don't know where to start."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~26:52 (L246)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L249)
- [SB-PP10](../pain-points/README.md#sb-pp10) – Make sets the HubSpot deal closer as Monday client owner – always wrong; fixed by hand
  - *"the person who closes the deal on HubSpot is never the person who's going to manage the client account."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~33:23 (L477)](../interviews/sb-sid-bali/transcript.md?plain=1#L481)

## Best quotes and figures (Problems DB)

"I'm not fully confident that it's working correctly. Stuff's getting missed." – leadership ([KO-PP11](../pain-points/README.md#ko-pp11), \~62:00, L303) | "the person who closes the deal on HubSpot is never the person who's going to manage the client account." – a technical SEO team member ([SB-PP10](../pain-points/README.md#sb-pp10), \~33:23, L477) | "So the first time I onboarded a client, I don't know where to start." – a performance team member ([MC-PP13](../pain-points/README.md#mc-pp13), \~26:52, L246)
