---
id: DS-14
title: "Client health & growth intelligence: anti-churn and expansion tracking and alerting, with escalation and delegation rules (Part B, from DS-13)"
team: "account managers and leadership"  # inferred: the page gives no "Team:" line
bundle: "AI Business Brain"
status: "Decided – churn basis to confirm; priced"
ledger_status: addressed
source_type: "mixed"
opportunities: ["O-31 (full)", "O-23 (opportunities/upsell part)", "O-21 (Part B (merged from DS-13))"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-31", "P-22"]
problems_also_helped: []
problems_related_only: ["P-41"]
pain_points_cited: ["KO-PP06", "KO-PP20", "KO-PP21", "LS-PP08", "LS-PP09", "LS-PP15", "MP-PP16"]
pain_points_interviewer_raised_or_inferred: ["KO-PP06 (inferred)", "LS-PP09 (interviewer-raised)"]
value: "A$90K–120K/yr retained (3–4 clients saved)"
value_retained_aud_per_year: [90000, 120000]
build_cost: "A$6,500"
monthly: "A$500/month (for now) + tokens ~US$40–150"
notion_section: "Client health & growth intelligence (anti-churn + expansion)"
---

# DS-14 · Client health & growth intelligence (anti-churn + expansion)

*AI tracking of client sentiment and signals to warn of churn and spot growth, with escalation and delegation rules (Part B).*

| | |
| --- | --- |
| Bundle | [AI Business Brain](README.md#bundle-ai-business-brain) |
| Team | account managers and leadership *(inferred)* |
| Status | Decided – churn basis to confirm; priced |
| Source type | mixed – Austin addition: contact personality profiling and self-learning |
| Opportunities | [O-31](../opportunities/README.md#o-31) (full), [O-23](../opportunities/README.md#o-23) (opportunities/upsell part), [O-21](../opportunities/README.md#o-21) (Part B (merged from DS-13)) |
| Earlier ideas | – |
| Fixes | [P-31 Churn risk is spotted late and account teams report rather than advise](../problems/p-31-churn-risk-is-spotted-late-and-account.md); [P-22 Escalations route around department leads to the Head of Client Services](../problems/p-22-escalations-route-around-department-leads-to-the.md) (Part B rules (from DS-13)) |
| Also helps | – |
| Related only | [P-41 Management layer is thin: paid media lacks a senior lead; new leads lack training](../problems/p-41-management-layer-is-thin-paid-media-lacks.md) – Not in proposal |
| Pain points cited | [KO-PP06](../pain-points/README.md#ko-pp06) (inferred), [KO-PP20](../pain-points/README.md#ko-pp20), [KO-PP21](../pain-points/README.md#ko-pp21), [LS-PP08](../pain-points/README.md#ls-pp08), [LS-PP09](../pain-points/README.md#ls-pp09) (interviewer-raised), [LS-PP15](../pain-points/README.md#ls-pp15), [MP-PP16](../pain-points/README.md#mp-pp16) |
| Written source | – |
| Value | A\$90K–120K/yr retained (3–4 clients saved) |
| Build cost | A\$6,500 |
| Monthly | A\$500/month (for now) + tokens \~US\$40–150 |

## Vision

> **It reads everything that's in communication with the client** – calls, emails, Slack, meetings, reports – and **builds a profile of each person** at the client (how they communicate, what they care about, how their sentiment is trending). It watches for churn and growth signals and **alerts the account manager, the department lead and Julia** together, with the evidence and a suggested next step. Part B's escalation rules say who acts.

## Pricing & priority

> **Priority: Strategic build · Impact 4 / 5 · Effort 4 / 5 (draft – confirm)** · **Add-on to the AI client brain ([DS-04](ds-04-ai-client-brain.md))**
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **Client health & growth intelligence** (churn and growth signals, contact profiles, health scores, alerts, outcome learning) + Part B escalation rules | **A\$6,500** | **A\$500/month** maintenance (for now) + AI tokens \~US\$40–150/month |
>
> *Needs [DS-04](ds-04-ai-client-brain.md) live for 2–3 months first; privacy check on profiling client contacts before launch.*

**Decision (9 Nov):** a **proactive system** that tracks every client's words and sentiment, builds a picture of each contact's **personality type**, watches for **signals of churn** and **signals of room to cross-sell or expand**, and alerts the right people. It learns from outcomes, so it **gets smarter over time** – the aim is to minimise churn and maximise account growth.

## How it works (draft)

1. **Reads** everything in the client brain ([DS-04](ds-04-ai-client-brain.md)): call transcripts, emails, Slack, Monday tasks, performance data, contract dates.
2. **Profiles each client contact** – communication style and personality type, what they care about, how sentiment is trending – so the team knows how to approach them.
3. **Churn signals** – the ones leadership already reads by gut (asking to see the contract, going quiet, a new marketing manager, falling results – [KO-PP06](../pain-points/README.md#ko-pp06)), plus sentiment drops, slower replies, fewer approvals, missed meetings.
4. **Growth signals** – a client mentioning a new product, market, budget, hire or pain point the agency could solve; strong results that justify a bigger scope; services they don't buy yet.
5. **Alerts** the account owner, the department lead and Julia – at every risk level – with the evidence (quote, date, source) and a suggested action; [DS-13](ds-13-merged-into-ds-14.md)'s rules say who acts.
6. **Learns**: every alert is marked with what happened (kept, churned, upsold), so the signals that actually predict churn or growth get more weight.
7. Feeds the "opportunities" step in call prep and review decks ([DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md)).

## Opportunities it covers

- **[O-31](../opportunities/README.md#o-31)** Weekly churn-risk signal list per client – rank 31, strategic, effort M (1–8 h/month; protects retention revenue) – extended from a weekly list to continuous alerts with AI.
- **[O-23](../opportunities/README.md#o-23)** "Problem plus recommendation" rule – the **opportunities / upsell** part (rank 23).
- Austin's notes: anti-churn and growth AI tracking and alerting.

## Problems it fixes and the evidence

- [Churn risk is spotted late and account teams report rather than advise](../problems/p-31-churn-risk-is-spotted-late-and-account.md) – leadership + 1 staff. *"you can just recognise it based on their behaviour. Asking to see the contract, I haven't seen you in a while, new marketing manager coming in"* – Head of Client Services ([KO-PP06](../pain-points/README.md#ko-pp06), *problem inferred from her description*). A **six-year client was lost** after poor feedback ([MP-PP16](../pain-points/README.md#mp-pp16)). *"Some go out of the blue."* – SEO director ([LS-PP15](../pain-points/README.md#ls-pp15)).
- **Missed growth:** upsell is occasional – *"a few upsells, but not much. That's an opportunity."* ([LS-PP09](../pain-points/README.md#ls-pp09), raised by Austin); teams describe metrics rather than bringing a recommendation ([KO-PP20](../pain-points/README.md#ko-pp20)); busy teams risk *"just going through the motions"* ([LS-PP08](../pain-points/README.md#ls-pp08)).
- [Escalations route around department leads to the Head of Client Services](../problems/p-22-escalations-route-around-department-leads-to-the.md) – she keeps them partly as her early-warning signal ([KO-PP21](../pain-points/README.md#ko-pp21)); DS-14 gives everyone that signal.

## Future state (draft)

1. Every client has a live health score and growth score, updated as new calls and emails come in.
2. Account owners get an alert with evidence and a suggested next step well before a client leaves.
3. Growth opportunities surface automatically and go into call prep and reviews.
4. Leadership sees portfolio health in one view and steps in only on high-risk alerts.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Churned clients flagged ≥ 30 days ahead | Unknown – some "out of the blue" (MP-O08) | ≥ 80% |
| Portfolio retention % | Not stated (KO-O01) | Hold or improve against the founder's target |
| Upsell / cross-sell proposals raised per month | "a few" (LS-O07) | Baseline, then set a target |
| Expansion revenue per month | Not baselined | Baseline, then set a target |

## Value (revised with Austin, 10 Nov)

> **Early warning on clients at risk – and on growth.** The brain watches every client's signals and alerts the account manager, department lead and Julia with the evidence and a suggested next step, so at-risk clients are caught while there's still time.

**1. Time saved:** none claimed.

**2. Revenue retained**

| Step | Figure |
| --- | --- |
| Clients lost today | 10 archived clients had contracts end between 31 Aug and 17 Oct 2026 (client board) |
| Average retainer of clients who left | \~A\$2,500 a month (client board) |
| Clients saved by early warning | 3–4 a year (Austin's estimate) |
| **Revenue retained** | **\~A\$90K–120K a year** (3–4 × \~A\$2,500 × 12) |

Growth signals (new products, markets, budgets) also surface upsell opportunities – not counted.

**3. Problems it eliminates**

- **P-31** Churn risk is spotted late and account teams report rather than advise
- **P-22** Escalations route around department leads to the Head of Client Services (Part B escalation rules)

**Goals:** retention · trust · good customer service

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Depends on [DS-04](ds-04-ai-client-brain.md) (client brain) being live with transcripts, email and Slack.
- Profiling client contacts' personality and sentiment from their words needs the AI-data rule ([DS-02](ds-02-ai-playbook-repository.md)) and a clear line on what's stored about individuals (privacy) – staff are not profiled.
- "Gets smarter" needs outcomes logged for every alert (kept / churned / upsold); without that, it can't learn.
- Signals are suggestions; people still own the escalation ([O-31](../opportunities/README.md#o-31): "Humans keep the escalation pipeline").

## Decided (9 Nov)

- **Who gets alerts:** the account owner, the **department lead and Julia at every risk level**. Julia's alerts can be **toggled on and off**; she wants them on for now. ([DS-13](ds-13-merged-into-ds-14.md)'s aim to move escalations to department leads still stands – Julia sees alerts, leads act first.)
- **Churn basis:** the client board (10 archived clients ended 31 Aug–17 Oct 2026, average \~A\$2,500); 3–4 saved a year is Austin's estimate – confirm the churn rate with Joe.
- **Personality profiles:** client contacts only – not prospects.
- **Merged with [DS-13](ds-13-merged-into-ds-14.md) (Austin's call, 9 Nov):** the escalation and delegation rules ([O-21](../opportunities/README.md#o-21)) are Part B of this solution – see the [DS-13](ds-13-merged-into-ds-14.md) section above for the rules and evidence.
