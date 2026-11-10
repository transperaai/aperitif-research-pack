---
id: DS-08
title: "AI sales handover: extracted from sales calls, confirmed by delivery"
team: "sales and delivery"  # inferred: the page gives no "Team:" line
bundle: "Client lifecycle"
status: "Decided – priced"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-08 (handover part; access checklist + staged onboarding as add-on)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-27", "P-18"]
problems_also_helped: ["P-20"]
problems_related_only: []
pain_points_cited: ["KO-PP01", "MC-PP10", "MC-PP11", "MC-PP13", "MP-PP10", "SH-PP07", "WS-PP06", "WS-PP07", "ZC-PP07"]
pain_points_interviewer_raised_or_inferred: ["KO-PP01 (interviewer-raised)", "MP-PP10 (interviewer-raised)"]
value: "New standard: at least an hour of prepared information before kick-off"
build_cost: "A$1,250"
monthly: "A$300/month + tokens ~US$1–10"
notion_section: "AI sales handover: extracted from sales calls, confirmed by delivery"
---

# DS-08 · AI sales handover: extracted from sales calls, confirmed by delivery

*AI extracts the sales handover from call transcripts; delivery confirms or denies with reasons (no hard blocks).*

| | |
| --- | --- |
| Bundle | [Client lifecycle](README.md#bundle-client-lifecycle) |
| Team | sales and delivery *(inferred)* |
| Status | Decided – priced |
| Source type | evidence-backed – No-hard-block design is Austin decision |
| Opportunities | [O-08](../opportunities/README.md#o-08) (handover part; access checklist + staged onboarding as add-on) |
| Earlier ideas | – |
| Fixes | [P-27 Client handovers (sales to delivery, offboarding) have no structured pack or trigger](../problems/p-27-client-handovers-have-no-structured-pack-or.md); [P-18 Sales commits to work delivery can't profitably do](../problems/p-18-sales-commits-to-work-delivery-can-t.md) |
| Also helps | [P-20 Onboarding stalls on client access and disrupts BAU](../problems/p-20-onboarding-stalls-on-client-access-and-disrupts.md) – Solve later (via cluster C-09 in text) |
| Pain points cited | [KO-PP01](../pain-points/README.md#ko-pp01) (interviewer-raised), [MC-PP10](../pain-points/README.md#mc-pp10), [MC-PP11](../pain-points/README.md#mc-pp11), [MC-PP13](../pain-points/README.md#mc-pp13), [MP-PP10](../pain-points/README.md#mp-pp10) (interviewer-raised), [SH-PP07](../pain-points/README.md#sh-pp07), [WS-PP06](../pain-points/README.md#ws-pp06), [WS-PP07](../pain-points/README.md#ws-pp07), [ZC-PP07](../pain-points/README.md#zc-pp07) |
| Written source | – |
| Value | New standard: at least an hour of prepared information before kick-off |
| Build cost | A\$1,250 |
| Monthly | A\$300/month + tokens \~US\$1–10 |

## Vision

> **As written – plus: a won deal spawns the new client's entry in the AI brain.** The moment a deal is won, a new client brain ([DS-04](ds-04-ai-client-brain.md)) is created automatically and the handover becomes its first entry, followed by the dossier ([DS-20](ds-20-new-client-dossier-agent.md)) and onboarding audit ([DS-09](ds-09-ai-prefilled-onboarding-audit-and-master-seo.md)). Delivery confirms or denies from there.
>
> **It also sets the client up everywhere else:** creates the standard client folder structure in Google Drive ([DS-17](ds-17-client-files-and-logins-in-company-owned.md)), the Monday client item and onboarding board, the Slack channel, the shared vault entry for logins, and links them all from the client brain – so nobody builds a new client's set-up by hand.

## Pricing & priority

> **Priority: Impact 3 / 5 · Effort 3 / 5 (draft – confirm; borderline)** · Extension of the AI brain ([DS-04](ds-04-ai-client-brain.md))
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **AI sales handover + new-client auto set-up** (handover from sales calls, delivery confirm/deny, new client brain entry, Drive/Monday/Slack set-up) | **A\$1,250** | **A\$300/month** maintenance + AI tokens \~US\$1–10/month |

**Decision (9 Nov):** **no hard blocks** on deals. Instead, the handover is **extracted by AI from the sales call transcripts**, the sales rep is shown **questions to fill any gaps**, the result **loads into the AI client brain ([DS-04](ds-04-ai-client-brain.md))**, and the delivery departments get a **notification to review and confirm or deny – with reasons**.

## How it works (draft)

1. Sales calls are recorded and transcribed (as the founder's handover already relies on: "just the transcript", [KO-PP01](../pain-points/README.md#ko-pp01)).
2. When a deal is won, AI reads the sales call transcripts and HubSpot deal notes and extracts the handover: goals, services and scope sold, budget, promises made, competitors, key contacts and personalities, delivery prerequisites (website live, creative supply, tracking), access needed, and risks.
3. Anything missing or unclear is turned into **short questions for the sales rep** to answer – no blocking, just prompts.
4. The completed handover loads into the client's brain ([DS-04](ds-04-ai-client-brain.md)), so it's findable by anyone later.
5. Only the delivery departments for **the services sold** get a notification to **review and confirm or deny**. A denial needs a reason – e.g. "no live website", "scope not deliverable at this price".
6. Confirmations and denials are posted in the **sales Slack channel**, so Joe, Julia, the sales rep and the delivery lead all see them and resolve any denial before kick-off.
7. **Add-on feature:** at signing, the client is sent the access checklist and how-to guides, and onboarding tasks are set up in Monday to unlock one stage at a time.

## Opportunities it covers

- **[O-08](../opportunities/README.md#o-08)** Sales-to-delivery gate: handover fields, owner, access checklist – rank 8, priority 80, quick win – **the handover part, rebuilt without hard gates**.
- Related: [DS-04](ds-04-ai-client-brain.md)'s "handover report in under three clicks" uses the same brain for client-to-client and offboarding handovers.

## Problems it fixes and the evidence

- [Client handovers (sales to delivery, offboarding) have no structured pack or trigger](../problems/p-27-client-handovers-have-no-structured-pack-or.md) – High. 3 staff, plus the founder's description of the current handover ([KO-PP01](../pain-points/README.md#ko-pp01), raised by Austin). *"So sometimes I'm going in blind. So I haven't been, I haven't talked to Joe on what has been communicated on the sales side"* – a performance team member ([MC-PP11](../pain-points/README.md#mc-pp11)). *"So we're like re-asking questions."* – a senior performance manager ([SH-PP07](../pain-points/README.md#sh-pp07)). The internal handover call sometimes happens *"like 10 minutes before the client call"* or is skipped ([WS-PP06](../pain-points/README.md#ws-pp06)).
- [Sales commits to work delivery can't profitably do](../problems/p-18-sales-commits-to-work-delivery-can-t.md) – clients sold without delivery prerequisites: *"They didn't even have a website ready. So we went two months off doing work for them"* – the performance director ([WS-PP07](../pain-points/README.md#ws-pp07)). Delivery's confirm/deny step surfaces this before kick-off. *Bias note: Austin raised over-commit first ([MP-PP10](../pain-points/README.md#mp-pp10)).*
- Also helps: onboarding delays from access and missing information ([C-09](../synthesis/clusters-and-root-causes.md#c-09) – [ZC-PP07](../pain-points/README.md#zc-pp07), [MC-PP10](../pain-points/README.md#mc-pp10)), since access needs and prerequisites are captured at handover.

## Future state (draft)

1. Every won deal produces a handover within a day, drafted from the sales calls – the rep only fills gaps.
2. Delivery sees exactly what was sold and promised before the first client call, so nobody goes in blind or re-asks the client.
3. Each department confirms it can deliver, or flags why not, before kick-off.
4. The handover lives in the client brain for the life of the client.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Won deals with a handover in the brain before kick-off | Unknown – handover is "just the transcript" ([KO-PP01](../pain-points/README.md#ko-pp01)) | 100% |
| Handovers confirmed by every delivery department before the first client call | Unknown; call sometimes 10 min before ([WS-PP06](../pain-points/README.md#ws-pp06)) | ≥ 90% |
| Clients re-asked questions already answered in sales | Happens ([SH-PP07](../pain-points/README.md#sh-pp07)) | 0 |
| Deals denied by delivery, with reasons logged | Not tracked | Tracked; reasons reviewed monthly with sales |

## Value (revised with Austin, 10 Nov)

> **Teams meet to clarify, not to learn.** What was sold is pulled from the sales call and confirmed by delivery before kick-off, so the delivery manager starts with at least an hour's worth of prepared information instead of going in blind.

**Value:** a new standard rather than time back – today barely any time goes into handover, so delivery starts blind (Michaela Cruz: "sometimes I'm going in blind"). With DS-08 every new client starts with a confirmed scope and context, which means better first months, fewer surprises about what was sold, and more trust from the client and the team.

**Problems it eliminates:** **P-27** Client handovers have no structured pack · **P-18** Sales commits to work delivery can't profitably do · helps **P-20**

**Goals:** good customer service · trust · retention

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Sales calls are recorded with prospect consent and the transcripts are reachable (the founder already relies on them).
- The sales lead wasn't interviewed, so the sales side of the evidence is leadership's view.
- Depends on [DS-04](ds-04-ai-client-brain.md) (client brain) and the AI-data rule ([DS-02](ds-02-ai-playbook-repository.md)).

## Decided (9 Nov)

- **No hard blocks** – AI extracts the handover from sales calls; the rep answers gap questions; it loads into the client brain; delivery confirms or denies with reasons.
- **Who reviews:** only the departments for the services sold.
- **Who sees the outcome:** Joe, Julia, the sales rep and the delivery lead, via the sales Slack channel.
- **Add-on feature:** access checklist and how-to guides sent at signing, plus staged onboarding tasks in Monday (fixes [MC-PP13](../pain-points/README.md#mc-pp13) – HubSpot drops every onboarding task at once – and [ZC-PP07](../pain-points/README.md#zc-pp07) slow access).
