---
id: P-27
title: "Client handovers (sales to delivery, offboarding) have no structured pack or trigger"
decision: "Solve now"
status: addressed
fixed_by: ["DS-04", "DS-08"]
also_helped_by: []
related_only: []
clusters: ["C-08"]
root_causes: ["RC-03"]
pain_points: ["KO-PP01", "MC-PP11", "MC-PP14", "SH-PP07", "WS-PP06"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
---

# P-27 · Client handovers (sales to delivery, offboarding) have no structured pack or trigger

| | |
| --- | --- |
| Decision | **Solve now** |
| Status | addressed – Fixed by [DS-04](../solutions/ds-04-ai-client-brain.md), [DS-08](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md) |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Sales |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-04 AI client brain (per client) – under the AI Business Brain banner](../solutions/ds-04-ai-client-brain.md)
- Fixes: [DS-08 AI sales handover: extracted from sales calls, confirmed by delivery](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md)

## Linked opportunities

- [O-08](../opportunities/README.md#o-08) Sales-to-delivery gate: handover fields, owner, access checklist – addressed ([DS-08](../solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md))
- [EI-12](../opportunities/README.md#ei-12) Meeting transcripts → per-client action runsheet – absorbed ([DS-04](../solutions/ds-04-ai-client-brain.md))
- [EI-07](../opportunities/README.md#ei-07) Individual AI client Brains – absorbed ([DS-04](../solutions/ds-04-ai-client-brain.md))

## Root cause and cluster

- Cluster [C-08](../synthesis/clusters-and-root-causes.md#c-08): Client handovers (sales to delivery, offboarding) have no structured pack or trigger – raised by 3 staff + 0 leadership; confidence High.
- Root cause [RC-03](../synthesis/clusters-and-root-causes.md#rc-03): Client context isn't captured per client, so every hand-off – sales to delivery, manager to writer or specialist, cover – loses detail.
- Root cause (problem record): [RC-03](../synthesis/clusters-and-root-causes.md#rc-03): Client context isn't captured per client, so every hand-off loses detail. Chain: clients re-asked, onboarding calls run 'blind', an offboarding handover missed ([SH-PP07](../pain-points/README.md#sh-pp07), [MC-PP11](../pain-points/README.md#mc-pp11), [MC-PP14](../pain-points/README.md#mc-pp14)) → internal sales-to-delivery call late or skipped ([WS-PP06](../pain-points/README.md#ws-pp06)) → handover relies on a transcript and HubSpot notes, not a required pack ([KO-PP01](../pain-points/README.md#ko-pp01), KO-str07) → client lifecycle transitions have no required fields, checklist or trigger.

## Pain points (5)

- [KO-PP01](../pain-points/README.md#ko-pp01) – Sales-to-delivery handover is the call transcript plus the HubSpot deal notes; no structured handover pack, so detail agreed in the pitch is lost
  - *Joe: "just the transcript."* – Joe Romeo, Leadership (kick-off) · interviewer-raised · [\~10:47 (L042)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L51) · Austin: Agree
- [MC-PP11](../pain-points/README.md#mc-pp11) – Onboarding calls run 'blind' – no sales handover from Joe, questionnaire not back – clients get repeat questions
  - *"So sometimes I'm going in blind. So I haven't been, I haven't talked to Joe on what has been communicated on the sales side"* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~30:11 (L266)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L269) · Austin: Agree
- [MC-PP14](../pain-points/README.md#mc-pp14) – Offboarding has no trigger – handover doc missed; client chased 2–3 days after contract end
  - *"Another two or three days has passed… the client is following up on the handover docs… So that makes us look bad."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~27:55 (L249)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L252) · Austin: Agree – ai client brain should create. sub 3 click hand over report
- [SH-PP07](../pain-points/README.md#sh-pp07) – Sales handover context not passed on or findable – client re-asked questions
  - *"So we're like re-asking questions. And ideally, it would be nice to find that information somewhere."* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~14:56 (L133)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L133) · Austin: Agree
- [WS-PP06](../pain-points/README.md#ws-pp06) – Internal sales-to-delivery onboarding call happens late (sometimes 10 min before client call) or the process is skipped, incl. by the founder
  - *"Sometimes that call happens like 10 minutes before the client call."* – Wendlley Simoes, Performance Marketing Director · staff-raised · [\~20:43 (L251)](../interviews/ws-wendlley-simoes/transcript.md?plain=1#L256) · Austin: Agree – ai brain should to provide this automatically with the call be required for clarifications rather than knowledge transfer

## Best quotes and figures

"So we're like re-asking questions. And ideally, it would be nice to find that information somewhere." – a performance manager ([SH-PP07](../pain-points/README.md#sh-pp07), \~14:56, L133) | "So sometimes I'm going in blind… I haven't talked to [sales] on what has been communicated on the sales side" – a performance team member ([MC-PP11](../pain-points/README.md#mc-pp11), \~30:11, L266) | "Another two or three days has passed… the client is following up on the handover docs… So that makes us look bad." – a performance team member ([MC-PP14](../pain-points/README.md#mc-pp14), \~27:55, L249)
