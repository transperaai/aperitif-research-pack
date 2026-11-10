---
id: DS-04
title: "AI client brain (per client) – under the AI Business Brain banner"
team: "account managers and delivery (everyone)"  # inferred: the page gives no "Team:" line
bundle: "AI Business Brain"
status: "Decided – priced"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-04 (full)", "O-13 (full)", "O-27 (per-client part)", "O-26 (style guide only)"]
earlier_ideas: ["EI-07 Individual AI client Brains", "EI-12 Meeting transcripts → per-client action runsheet"]
written_sources: ["WS-ZC-01 Zach Chamberlain \"AI suggestions\" Google Doc"]
problems_fixed: ["P-14", "P-04", "P-27", "P-28"]
problems_also_helped: ["P-22", "P-47"]
problems_related_only: []
pain_points_cited: ["KO-PP05", "MC-PP11", "MC-PP14", "MP-PP16", "MP-PP20", "SB-PP03", "SD-PP05", "SJ-PP09", "ZC-PP04"]
pain_points_interviewer_raised_or_inferred: ["MP-PP20 (interviewer-raised)"]
value: "6–9 h/mo · A$26K–39K capacity; the foundation for DS-03, 05, 14, 27, 28"
value_time_h_month: [6, 9]
value_capacity_aud_per_year: [26000, 39000]
build_cost: "A$12,500"
monthly: "A$850/month maintenance; hosting + tokens TBC (model-agnostic; research needed)"
notion_section: "AI client brain (per client)"
---

# DS-04 · AI client brain (per client)

*A per-client AI brain (visible client page plus query box) pulling calls, Slack, email, the work and the client profile incl. style guide.*

| | |
| --- | --- |
| Bundle | [AI Business Brain](README.md#bundle-ai-business-brain) |
| Team | account managers and delivery (everyone) *(inferred)* |
| Status | Decided – priced |
| Source type | evidence-backed – Design choices (all clients, all sources, custom app, visible client page) are Austin decisions |
| Opportunities | [O-04](../opportunities/README.md#o-04) (full), [O-13](../opportunities/README.md#o-13) (full), [O-27](../opportunities/README.md#o-27) (per-client part), [O-26](../opportunities/README.md#o-26) (style guide only) |
| Earlier ideas | [EI-07](../opportunities/README.md#ei-07) Individual AI client Brains, [EI-12](../opportunities/README.md#ei-12) Meeting transcripts → per-client action runsheet |
| Fixes | [P-14 Client knowledge lives in people's heads, not per client](../problems/p-14-client-knowledge-lives-in-people-s-heads.md); [P-04 Client-call prep takes longer than the call](../problems/p-04-client-call-prep-takes-longer-than-the.md); [P-27 Client handovers (sales to delivery, offboarding) have no structured pack or trigger](../problems/p-27-client-handovers-have-no-structured-pack-or.md); [P-28 Regulated-industry content lacks shared compliance rules and credible sources](../problems/p-28-regulated-industry-content-lacks-shared-compliance-rules.md) |
| Also helps | [P-22 Escalations route around department leads to the Head of Client Services](../problems/p-22-escalations-route-around-department-leads-to-the.md) – Solve now (partly); [P-47 Teams work in silos and don't see each other's work or priorities](../problems/p-47-teams-work-in-silos-and-don-t.md) – Solve now |
| Pain points cited | [KO-PP05](../pain-points/README.md#ko-pp05), [MC-PP11](../pain-points/README.md#mc-pp11), [MC-PP14](../pain-points/README.md#mc-pp14), [MP-PP16](../pain-points/README.md#mp-pp16), [MP-PP20](../pain-points/README.md#mp-pp20) (interviewer-raised), [SB-PP03](../pain-points/README.md#sb-pp03), [SD-PP05](../pain-points/README.md#sd-pp05), [SJ-PP09](../pain-points/README.md#sj-pp09), [ZC-PP04](../pain-points/README.md#zc-pp04) |
| Written source | [Zach Chamberlain – "AI suggestions" Google Doc](https://docs.google.com/document/d/1bsjfs6Aw1F6VOA_nvhWwzPoFv8XHxaXp4Q8UHYAgtsw/edit) (WS-ZC-01) |
| Value | 6–9 h/mo · A\$26K–39K capacity; the foundation for DS-03, 05, 14, 27, 28 |
| Build cost | A\$12,500 |
| Monthly | A\$850/month maintenance; hosting + tokens TBC (model-agnostic; research needed) |

## Vision

> **The nervous system for each client.** One AI brain that captures everything about a client – the work we do, docs, ad and analytics accounts and performance, emails, Slack chats, call transcripts, assets and artefacts.
>
> - Teams can **query** it, and it also **calls out** key things and facts about the client without being asked.
> - Connected to **Monday**, so people can just ask "where is this task at?".
> - Connected to the **anti-churn and growth** solution ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)).
> - Makes it easy for every team to know what's going on with a client and how to perform better.
>
> **Also in the vision (agreed 9 Nov):**
>
> 1. **Every answer cites its source** – "budget agreed at \$8K, call on 3 Oct, 14:20" with a link – so people trust it.
> 2. **Client health card** at the top of every client page: health score ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)), last contact, open risks, open actions, next meeting.
> 3. **Gaps and staleness flagged** – "no call logged in 30 days", "no client email in 3 weeks", "Ahrefs not connected".
> 4. **Weekly digest** to the account owner: what changed for each client this week.
> 5. **Covers the whole client life** – starts at signing (dossier [DS-20](ds-20-new-client-dossier-agent.md), handover [DS-08](ds-08-ai-sales-handover-extracted-from-sales-calls.md), audit [DS-09](ds-09-ai-prefilled-onboarding-audit-and-master-seo.md)) and ends at offboarding with an automatic handover pack.
> 6. **Permissions** – sensitive threads and commercial terms (pricing, disputes, contract talks) can be limited to leadership.
> 7. **Ask and act** – e.g. "@oracle, create a task for Sid to fix the tracking" from Slack goes into Monday (phase 2, with a confirm step).
> 8. **Consent and retention** – clients agree to call recording; a set period for keeping transcripts, decided before launch.

## Pricing & priority

> **Priority: Strategic build · Impact 5 / 5 · Effort 5 / 5 (draft – confirm)**
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **AI client brain** (all clients, all sources, visible client pages, call-outs, health card, digest) – **includes the shared platform** (client registry, connectors, @oracle Slack bot, role-based access, memory with citations) | **A\$12,500** | **A\$850/month** maintenance |
> | Hosting and AI tokens | – | **TBC** – to research; the brain will be model-agnostic. Worksheet draft: tokens \~US\$60–300/month, hosting shared, one-off backfill \~US\$100–500 |

**Decision (9 Nov):** an AI brain **for each client** that pulls from everywhere the client's information currently lives – call transcripts, Slack, emails, the work itself – stitches the loose pieces together, and makes it easy to **review and query**. It sits under the **AI Business Brain** banner but is treated as a separate solution for now.

## What it pulls together (draft)

| Source | What it adds |
| --- | --- |
| Call transcripts (Otter / Gemini notes) | What was discussed and agreed; actions; client mood and feedback |
| Slack | Internal discussion about the client, escalations, decisions |
| Email | Client requests, approvals, change requests, sentiment |
| The work | Master SEO Document, briefs, reports, Monday tasks, ad account change history |
| Client profile | Strategy, USPs, tone of voice, compliance rules, personalities, preferences |
| **Client style guide** (added 9 Nov, from [O-26](../opportunities/README.md#o-26)) | Each client's writing and editing rules – voice, terms to use and avoid, formatting, compliance wording – used by writers, freelancers and AI drafts ([DS-03](ds-03-automated-ai-brief-drafts-monday-com-tasks.md)), so edits are fewer and consistent |

**What people can do with it:** ask questions in plain English ("what did we agree on budgets last month?", "what's this client's tone?"), get a pre-call brief or dossier, get a handover report in under three clicks, and review a running timeline of everything that's happened with the client.

**Visible, not just queryable (added 9 Nov):** every client brain has a page anyone can open and read without asking anything:

| On the client page | What it shows |
| --- | --- |
| Meeting log | Every client meeting saved: date, attendees, the full transcript, and a short summary |
| Email log | Key client email threads saved with a short summary |
| **Key call-outs** | Pulled out of every meeting and email and pinned at the top: decisions made, promises and commitments, client requests, budget or scope changes, complaints or praise, risks |
| Open actions | Actions from meetings and emails, with owner and due date, until done |
| Timeline | Everything above in date order |

The query box is there for questions; the call-outs, logs and actions are always on show.

## Opportunities it covers

- **[O-04](../opportunities/README.md#o-04)** One per-client record fed by call summaries – rank 4, priority 100, quick win, effort S
- **[O-13](../opportunities/README.md#o-13)** AI per-client summary for reports, calls and data questions – rank 13, 75, strategic, effort M (overlaps [O-04](../opportunities/README.md#o-04))
- **[O-27](../opportunities/README.md#o-27)** AI business brain over client records and SOPs – the per-client part (rank 27, Consider) – the company-wide part stays for a later solution
- Austin's earlier ideas: *Individual AI client Brains*, *Meeting transcripts → per-client action runsheet*
- Austin's notes: client brain for call prep dossiers, handover reports ("sub 3 click hand over report"), research and compliance context, request and email-chain summaries

## Problems it fixes and the evidence

- [Client knowledge lives in people's heads, not per client](../problems/p-14-client-knowledge-lives-in-people-s-heads.md) – High. 4 staff. *"I'm finding myself just like, writing, like scribbling down on a Google Doc, oh, the client's asked for this"* – an SEO manager ([ZC-PP04](../pain-points/README.md#zc-pp04)). *"There's notes in here, right? But they don't get, like, they don't get copied over to the next one."* – a content team member ([SJ-PP09](../pain-points/README.md#sj-pp09)).
- [Client-call prep takes longer than the call](../problems/p-04-client-call-prep-takes-longer-than-the.md) – High. 4 staff. *"for a half an hour call, I'm basically spending about one hour, one hour, 15 minutes on that specific client"* – a performance manager ([SD-PP05](../pain-points/README.md#sd-pp05), stated).
- [Client handovers (sales to delivery, offboarding) have no structured pack or trigger](../problems/p-27-client-handovers-have-no-structured-pack-or.md) – High. 3 staff. *"So sometimes I'm going in blind…"* – a performance team member ([MC-PP11](../pain-points/README.md#mc-pp11)). Handover docs missed until the client chased ([MC-PP14](../pain-points/README.md#mc-pp14)).
- [Regulated-industry content lacks shared compliance rules and credible sources](../problems/p-28-regulated-industry-content-lacks-shared-compliance-rules.md) – the client's compliance rules live in its brain.
- [Escalations route around department leads to the Head of Client Services](../problems/p-22-escalations-route-around-department-leads-to-the.md) – partly: about five churn-risk escalations a week land with the Head of Client Services ([KO-PP05](../pain-points/README.md#ko-pp05)); with each client's history in one place, department leads can handle more of them themselves.
- Also helps: [Teams work in silos and don't see each other's work or priorities](../problems/p-47-teams-work-in-silos-and-don-t.md) (organic and paid see the same client picture); request extraction from email chains ([SB-PP03](../pain-points/README.md#sb-pp03), Austin's note).
- **Zach's written AI suggestions** (Google Doc): Otter/Gemini notes sit in different places and he keeps a Google Doc as the source of truth for client meetings – he wants transcripts turned into actions and collected in **one runsheet per client**. The client brain does this.

## Future state (draft)

1. Every active client has one brain; nothing about the client lives only in someone's head or personal doc.
2. Every client call is recorded; its transcript, summary, key call-outs and actions are saved to the client's page within 24 hours. Key client emails are saved the same way. Anyone can read them without querying.
3. Before a call, the manager asks for a brief and gets the last call's actions, open items and month-on-month performance in one view.
4. When a client changes hands or offboards, a handover report is generated in under three clicks.
5. Anyone working on the client – SEO, paid, content, writers – queries the same brain instead of asking a colleague.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Prep minutes per client meeting | 15–20 min (Austin, 10 Nov) | \~5 min |
| % of active clients with a current brain | 0 central (HT-O01) | 100% |
| Client calls summarised into the brain within 24 h | \~0 – transcripts unused (ZC-O10, [MP-PP20](../pain-points/README.md#mp-pp20)) | ≥ 95% |
| Time to produce a handover pack | Unknown; missed until client chased ([MC-PP14](../pain-points/README.md#mc-pp14)) | \< 10 min |

## Value (revised with Austin, 10 Nov)

> **Every client's history, ready before every call.** The brain pulls together calls, emails, Slack, HubSpot, Monday and the work itself, so a manager opens a ready-made prep pack instead of digging through five places – and anyone can get up to speed on a client in minutes.

**1. Time saved**

| Task removed | How it's worked out | Per month |
| --- | --- | --- |
| Preparing for client meetings | \~36 meetings a month (31 live clients with a monthly meeting + Tier 2 clients quarterly) × 15–20 min today → \~5 min with the brain | **\~6–9 h** |

Handovers and cover: target of **15 minutes or less** to get up to speed on any client (measured as a KPI, not counted as hours).

**2. Capacity and revenue unlocked**

\~6–9 h ÷ \~130 productive hours × \~A\$46.8K MRR per manager (A\$421,121 live MRR ÷ 9 managers) → **\~A\$2.2K–3.3K MRR ≈ A\$26K–39K a year of capacity**. Its bigger value is as the foundation – it underpins [DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md), [DS-27](ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md), [DS-28](ds-28-client-comms-assistant-monthly-updates-and-expectation.md), [DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md) and [DS-03](ds-03-automated-ai-brief-drafts-monday-com-tasks.md).

**3. Problems it eliminates**

- **P-14** Client knowledge lives in people's heads, not per client
- **P-04** Client-call prep takes longer than the call
- **P-27** Client handovers (sales to delivery, offboarding) have no structured pack
- Helps: **P-22** Escalations route around department leads · **P-47** Teams work in silos · **P-28** Regulated-industry compliance rules

**Goals:** more MRR managed per person · good customer service · retention · trust

*Inputs from Austin (10 Nov): client board: 101 live clients, 31 with a monthly meeting, Tier 2 clients meet quarterly; 15–20 min prep today, \~5 min with the brain, handovers ≤15 min.*

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Prep time per meeting is Austin's figure (15–20 min); one interviewee reported 60–75 min, treated as an outlier.
- Needs call-recording consent from clients, the AI-data rule ([DS-02](ds-02-ai-playbook-repository.md)) and read access to Slack, email and ad platforms.
- One client-record template agreed across organic and paid.
- Pulling Slack and email per client needs a reliable way to tag which messages belong to which client.

## Decided (9 Nov)

- **All clients** from the start (not Tier 1 first).
- **All sources at once** – transcripts, Slack, email, the work and the client profile; no phasing.
- **A custom app** that connects to the different sources.
