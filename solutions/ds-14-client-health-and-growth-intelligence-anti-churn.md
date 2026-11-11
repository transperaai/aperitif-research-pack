---
id: DS-14
title: "Client health & growth intelligence: anti-churn and expansion tracking and alerting, with escalation and delegation rules (Part B, from DS-13)"
team: "account managers and leadership"  # inferred: the page gives no "Team:" line
bundle: "AI Business Brain"
status: "Recommended – build 4, Client Retention and Growth AI"
coverage: addressed
source_type: "mixed"
opportunities: ["O-31 (full)", "O-23 (opportunities/upsell part)", "O-21 (Part B (merged from DS-13))"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-31", "P-22"]
problems_also_helped: []
problems_related_only: ["P-41"]
pain_points_cited: ["KO-PP06", "KO-PP20", "KO-PP21", "LS-PP08", "LS-PP09", "LS-PP15", "MP-PP16"]
pain_points_interviewer_raised_or_inferred: ["KO-PP06 (inferred)", "LS-PP09 (interviewer-raised)"]
value: "Churn reduced ~1.5% a month (indicative): ~18 clients, ~A$540K/yr kept"
value_retained_aud_per_year: [540000, 540000]
---

# DS-14 · Client health & growth intelligence (anti-churn + expansion)

*AI tracking of client sentiment and signals to warn of churn and spot growth, with escalation and delegation rules (Part B).*

| | |
| --- | --- |
| Bundle | [AI Business Brain](README.md#bundle-ai-business-brain) |
| Team | account managers and leadership *(inferred)* |
| Status | Recommended – build 4, Client Retention and Growth AI |
| Source type | mixed – Austin addition: contact personality profiling and self-learning |
| Opportunities | [O-31](../opportunities/README.md#o-31) (full), [O-23](../opportunities/README.md#o-23) (opportunities/upsell part), [O-21](../opportunities/README.md#o-21) (Part B (merged from DS-13)) |
| Earlier ideas | – |
| Fixes | [P-31 Churn risk is spotted late and account teams report rather than advise](../problems/p-31-churn-risk-is-spotted-late-and-account.md); [P-22 Escalations route around department leads to the Head of Client Services](../problems/p-22-escalations-route-around-department-leads-to-the.md) (Part B rules (from DS-13)) |
| Also helps | – |
| Related only | [P-41 Management layer is thin: paid media lacks a senior lead; new leads lack training](../problems/p-41-management-layer-is-thin-paid-media-lacks.md) – Not in proposal |
| Pain points cited | [KO-PP06](../pain-points/README.md#ko-pp06) (inferred), [KO-PP20](../pain-points/README.md#ko-pp20), [KO-PP21](../pain-points/README.md#ko-pp21), [LS-PP08](../pain-points/README.md#ls-pp08), [LS-PP09](../pain-points/README.md#ls-pp09) (interviewer-raised), [LS-PP15](../pain-points/README.md#ls-pp15), [MP-PP16](../pain-points/README.md#mp-pp16) |
| Written source | – |
| Value | Churn reduced \~1.5% a month (indicative): \~18 clients, \~A\$540K/yr kept |

## Vision

> **It reads everything that's in communication with the client** – calls, emails, Slack, meetings, reports – and **builds a profile of each person** at the client (how they communicate, what they care about, how their sentiment is trending). It watches for churn and growth signals and **alerts the account manager, the department lead and Julia** together, with the evidence and a suggested next step. Part B's escalation rules say who acts.

## Decision

**Decision:** a **proactive system** that tracks every client's words and sentiment, builds a picture of each contact's **personality type**, watches for **signals of churn** and **signals of room to cross-sell or expand**, and alerts the right people. It learns from outcomes, so it **gets smarter over time** – the aim is to minimise churn and maximise account growth.

## How it works

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

## Problems it fixes and the evidence

- [Churn risk is spotted late and account teams report rather than advise](../problems/p-31-churn-risk-is-spotted-late-and-account.md) – leadership + 1 staff. *"you can just recognise it based on their behaviour. Asking to see the contract, I haven't seen you in a while, new marketing manager coming in"* – Head of Client Services ([KO-PP06](../pain-points/README.md#ko-pp06), *problem inferred from her description*). A **six-year client was lost** after poor feedback ([MP-PP16](../pain-points/README.md#mp-pp16)). *"Some go out of the blue."* – SEO director ([LS-PP15](../pain-points/README.md#ls-pp15)).
- **Missed growth:** upsell is occasional – *"a few upsells, but not much. That's an opportunity."* ([LS-PP09](../pain-points/README.md#ls-pp09), raised by Austin); teams describe metrics rather than bringing a recommendation ([KO-PP20](../pain-points/README.md#ko-pp20)); busy teams risk *"just going through the motions"* ([LS-PP08](../pain-points/README.md#ls-pp08)).
- [Escalations route around department leads to the Head of Client Services](../problems/p-22-escalations-route-around-department-leads-to-the.md) – she keeps them partly as her early-warning signal ([KO-PP21](../pain-points/README.md#ko-pp21)); DS-14 gives everyone that signal.

## Future state

1. Every client has a live health score and growth score, updated as new calls and emails come in.
2. Account owners get an alert with evidence and a suggested next step well before a client leaves.
3. Growth opportunities surface automatically and go into call prep and reviews.
4. Leadership sees portfolio health in one view and steps in only on high-risk alerts.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Churned clients flagged ≥ 30 days ahead | Unknown – some "out of the blue" (MP-O08) | ≥ 80% |
| Portfolio retention % | Not stated (KO-O01) | Hold or improve against the founder's target |
| Upsell / cross-sell proposals raised per month | "a few" (LS-O07) | Baseline, then set a target |
| Expansion revenue per month | Not baselined | Baseline, then set a target |

## Value

> **Early warning on clients at risk – and on growth.** The brain watches every client's signals and alerts the account manager, department lead and Julia with the evidence and a suggested next step, so at-risk clients are caught while there's still time.

**1. Time saved:** none claimed.

**2. Revenue retained**

| Step | Figure |
| --- | --- |
| Churn today | \~4% of clients a month (Austin's estimate; the client board shows 10 contracts ended 31 Aug–17 Oct 2026) |
| Average retainer of clients who left | \~A\$2,500 a month (client board) |
| Churn with early warning | \~2.5% a month – \~1.5% of 101 clients a month, about 18 a year, kept (Austin's target) |
| **Revenue kept** | **\~A\$540K a year** (18 × \~A\$2,500 × 12; indicative) |

Aperitif is capped by team capacity, so kept clients don't add growth on top of the capacity figures – they mean \~18 fewer replacement wins (and onboardings) are needed each year, and the business reaches its new ceiling sooner. Not added to the capacity totals.

Growth signals (new products, markets, budgets) also surface upsell opportunities – not counted.

**3. Problems it eliminates**

- **P-31** Churn risk is spotted late and account teams report rather than advise
- **P-22** Escalations route around department leads to the Head of Client Services (Part B escalation rules)

**Goals:** retention · trust · good customer service

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Depends on [DS-04](ds-04-ai-client-brain.md) (client brain) being live with transcripts, email and Slack.
- Profiling client contacts' personality and sentiment from their words needs the AI-data rule ([DS-02](ds-02-ai-playbook-repository.md)) and a clear line on what's stored about individuals (privacy) – staff are not profiled.
- "Gets smarter" needs outcomes logged for every alert (kept / churned / upsold); without that, it can't learn.
- Signals are suggestions; people still own the escalation ([O-31](../opportunities/README.md#o-31): "Humans keep the escalation pipeline").

## Decided

- **Who gets alerts:** the account owner, the **department lead and Julia at every risk level**. Julia's alerts can be **toggled on and off**; she wants them on for now. ([DS-13](ds-13-merged-into-ds-14.md)'s aim to move escalations to department leads still stands – Julia sees alerts, leads act first.)
- **Churn basis:** \~4% a month today, brought down to \~2.5% – Austin's estimate and target. The client board (10 contracts ended 31 Aug–17 Oct 2026, average \~A\$2,500) is consistent with it.
- **Personality profiles:** client contacts only – not prospects.
- **Includes [DS-13](ds-13-merged-into-ds-14.md):** the escalation and delegation rules ([O-21](../opportunities/README.md#o-21)) are Part B of this solution – see the [DS-13](ds-13-merged-into-ds-14.md) section above for the rules and evidence.
