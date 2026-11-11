---
id: P-15
title: "Slack bots and agents have no visible owner or documentation"
decision: "Solve now"
status: addressed
fixed_by: ["DS-10"]
also_helped_by: []
related_only: []
clusters: ["C-32"]
root_causes: ["RC-04"]
pain_points: ["HT-PP06", "SB-PP11", "TG-PP09"]
theme: "Process / automation"
severity: "Medium"
confidence: "High – raised by 3+ people"
---

# P-15 · Slack bots and agents have no visible owner or documentation

| | |
| --- | --- |
| Decision | **Solve now** |
| Status | addressed – Fixed by [DS-10](../solutions/ds-10-systems-register-and-break-fix-runbook.md) |
| Theme · severity · confidence | Process / automation · Medium · High – raised by 3+ people |
| Process area | Other |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-10 Systems register and break-fix runbook (everything built, who owns it, what to do when it breaks)](../solutions/ds-10-systems-register-and-break-fix-runbook.md)

## Linked opportunities

- [O-08](../opportunities/README.md#o-08) Sales-to-delivery gate: handover fields, owner, access checklist – addressed ([DS-08](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md))
- [O-16](../opportunities/README.md#o-16) Own and verify automations: register, backup admin, reconciliation – addressed ([DS-10](../solutions/ds-10-systems-register-and-break-fix-runbook.md))
- [O-18](../opportunities/README.md#o-18) One link record: standard order template, auto-sync, invoice run – addressed ([DS-11](../solutions/ds-11-link-building-workflow-crm.md))
- [O-25](../opportunities/README.md#o-25) Content intake on Monday with brief standard and slots – absorbed ([DS-03](../solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md))

## Root cause and cluster

- Cluster [C-32](../synthesis/clusters-and-root-causes.md#c-32): Home-built automations and tools have one builder, no documentation and no backup – raised by 3 staff + 0 leadership; confidence High.
- Root cause [RC-04](../synthesis/clusters-and-root-causes.md#rc-04): Tools, automations and AI workflows are built by individuals with no owner, documentation, policy or renewal plan, so they break or stay personal.
- Root cause (problem record): Automations were added channel by channel (HubSpot agents, Zapier, Tina/Franco agents, finance agent, Monday mirror) without a register of triggers or owners.

## Pain points (3)

- [HT-PP06](../pain-points/README.md#ht-pp06) – Nobody clearly driving the Sheets–Monday.com tracker connection; it sat with Sid, who is moving to client work
  - *"Yeah, I think that's what's kid [Sid] but I don't know where it's at."* – Hayley Tantau, Content Specialist · staff-raised · [\~20:07 (L232)](../interviews/ht-hayley-tantau/transcript.md?plain=1#L237)
- [SB-PP11](../pain-points/README.md#sb-pp11) – Monday/Make system depends on Sid (built it, admin, sole fixer); no documented backup
  - *"But if I'm not there, who's going to do it? It needs to have that system in place."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~35:09 (L501)](../interviews/sb-sid-bali/transcript.md?plain=1#L505)
- [TG-PP09](../pain-points/README.md#tg-pp09) – Four home-built tools are undocumented, unreviewed and run by one person
  - *"but if there is really simpler way, and more accurate because yeah, I'm not really sure if these are really working well."* – Tonie Guevarra, Outreach Specialist · inferred · [\~42:29 (L452)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L459) · Austin: Agree

## Best quotes and figures

Slack review: at least 6 bot-fed channels; open questions on every trigger; "Who manages the agents in Slack and where are they?"
