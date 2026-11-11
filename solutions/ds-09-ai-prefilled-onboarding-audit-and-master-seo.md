---
id: DS-09
title: "AI-prefilled onboarding audit and Master SEO Document"
team: "SEO strategists (onboarding)"  # inferred: the page gives no "Team:" line
bundle: "SEO performance"
status: "Recommended – build 7, Onboarding audit"
coverage: addressed
source_type: "evidence-backed"
opportunities: ["O-14 (full)"]
earlier_ideas: ["EI-01 1-click audit access system + AI audit workflow (also a lead magnet)"]
written_sources: []
problems_fixed: ["P-20"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["KZ-PP01", "KZ-PP02", "KZ-PP03", "KZ-PP04", "KZ-PP21", "SD-PP11"]
pain_points_interviewer_raised_or_inferred: []
value: "20–40 h/mo · A$88K–177K capacity (≈ 2–5 clients)"
value_time_h_month: [20, 40]
value_capacity_aud_per_year: [88000, 177000]
---

# DS-09 · AI-prefilled onboarding audit and Master SEO Document

*AI pre-fills the onboarding audit and Master SEO Document for a strategist to sign off.*

| | |
| --- | --- |
| Bundle | [SEO performance](README.md#bundle-seo-performance) |
| Team | SEO strategists (onboarding) *(inferred)* |
| Status | Recommended – build 7, Onboarding audit |
| Source type | evidence-backed |
| Opportunities | [O-14](../opportunities/README.md#o-14) (full) |
| Earlier ideas | [EI-01](../opportunities/README.md#ei-01) 1-click audit access system + AI audit workflow (also a lead magnet) |
| Fixes | [P-20 Onboarding stalls on client access and disrupts BAU](../problems/p-20-onboarding-stalls-on-client-access-and-disrupts.md) |
| Also helps | – |
| Pain points cited | [KZ-PP01](../pain-points/README.md#kz-pp01), [KZ-PP02](../pain-points/README.md#kz-pp02), [KZ-PP03](../pain-points/README.md#kz-pp03), [KZ-PP04](../pain-points/README.md#kz-pp04), [KZ-PP21](../pain-points/README.md#kz-pp21), [SD-PP11](../pain-points/README.md#sd-pp11) |
| Written source | – |
| Value | 20–40 h/mo · A\$88K–177K capacity (≈ 2–5 clients) |

## Vision

> **AI does most of the onboarding work wherever it can.** The team points it at where the audit needs to be done (the site, the ad accounts) and it runs the audit and fills in the sheet – the Master SEO Document and the paid audit checklist. The strategist reviews and signs off.
>
> **Connected to the client brain ([DS-04](ds-04-ai-client-brain.md)):** the finished audit, Master SEO Document and findings are saved into the client's brain, so they feed briefs ([DS-03](ds-03-automated-ai-brief-drafts-monday-com-tasks.md)), reviews ([DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md)), monitoring ([DS-22](ds-22-seo-automated-monday-client-performance-check.md), [DS-29](ds-29-ppc-automated-monday-client-performance-check.md)) and health tracking ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)) from day one.

## Decision

**Decision:** adopt [O-14](../opportunities/README.md#o-14) as written – it speeds up onboarding audits.

## How it works

1. At signing, read-only access to the site and ad accounts is granted ([DS-08](ds-08-ai-sales-handover-extracted-from-sales-calls.md) add-on sends the access checklist).
2. **Organic:** a Claude skill connected to Ahrefs, GA4 and Search Console pre-fills the Master SEO Document – URL/keyword map, draft metadata, competitors – building on the existing Claude SEO-strategy prompt guide.
3. **Paid:** a Claude skill runs a first-pass account audit against the 30-point checklist through Windsor.ai (the same connection as build 1) and drafts the findings.
4. The strategist reviews, corrects and signs off – the human owns the strategy.
5. Output loads into the client brain ([DS-04](ds-04-ai-client-brain.md)). The same engine can later produce prospect decks ([DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md)) and a lead-magnet audit.

## Opportunities it covers

- **[O-14](../opportunities/README.md#o-14)** AI-prefilled onboarding audit and Master SEO Document – rank 14, priority 75, strategic, effort M
- Austin's earlier idea: *1-click audit (read-only access + AI audit)*.

## Problems it fixes and the evidence

- [Onboarding stalls on client access and disrupts BAU](../problems/p-20-onboarding-stalls-on-client-access-and-disrupts.md) – the onboarding-workload part ([C-10](../synthesis/clusters-and-root-causes.md#c-10)): 4 staff + 2 leadership; access delays ([C-09](../synthesis/clusters-and-root-causes.md#c-09)): 3 staff. *"onboarding takes a really long time… onboarding a new client is pretty hectic here as well."* – the link-building lead ([KZ-PP01](../pain-points/README.md#kz-pp01)). A five-site month forced out-of-hours work. *"the audit is what takes majority of the times during the whole onboarding process"* – a senior performance manager ([SD-PP11](../pain-points/README.md#sd-pp11)). Month-one deliverables are copy-paste: *"We just copy-paste all the keywords basically from in here that we had."* ([KZ-PP04](../pain-points/README.md#kz-pp04)).
- **Growth cap:** onboarding effort limits how many new clients a manager can take ([KZ-PP02](../pain-points/README.md#kz-pp02)).
- **Retention risk:** back-to-back onboardings are repetitive and demoralising for junior staff ([KZ-PP03](../pain-points/README.md#kz-pp03)).
- Also helps: prospect decks for sales ([KZ-PP21](../pain-points/README.md#kz-pp21)) – shared engine with [DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md).

## Future state

1. A new client's Master SEO Document and paid audit are drafted within a day of access, not over most of month one.
2. Strategists spend their time on judgement and the client conversation, not copying keywords and checking accounts line by line.
3. Managers can take more new clients at once without out-of-hours work.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Strategist hours per SEO onboarding | \~10–12 h (Austin's estimate; "takes a really long time", KZ-O01) | \~4–6 h |
| Audit hours per paid onboarding | \~10 h (Austin's estimate; longest onboarding step, SD-O07) | \~4–5 h |
| Concurrent onboardings per manager without overtime | Limited ([KZ-PP02](../pain-points/README.md#kz-pp02)) | Set after baseline |

## Value

> **Onboarding stops capping growth.** AI pre-fills the onboarding audit and Master SEO Document so managers check and add strategy instead of building it from scratch – and can take on new clients without working out of hours.

**1. Time saved**

| Task removed | How it's worked out | Per month |
| --- | --- | --- |
| Building the SEO onboarding audit, Master SEO Document and strategy | \~2–3 new SEO onboardings a month × 10–12 h each today; AI pre-filling cuts 50–60% | **\~10–22 h** |
| Running the paid onboarding audit | \~2–3 new paid onboardings a month × \~10 h each today; AI cuts 50–60% | **\~10–18 h** |
| **Total** |  | **\~20–40 h** |

**2. Capacity and revenue unlocked**

SEO hours (\~10–22 h) at \~A\$55.6K MRR per SEO manager plus paid hours (\~10–18 h) at \~A\$39.7K MRR per PPC manager, ÷ \~130 productive hours → **\~A\$88K–177K a year of capacity** (≈ 2–5 more clients). Karl: onboarding effort caps how many new clients managers can take, and a five-onboarding month forced out-of-hours work – faster onboarding removes that cap.

**3. Problems it eliminates**

- **P-20** Onboarding stalls and disrupts BAU (month one is "pretty hectic", [KZ-PP01](../pain-points/README.md#kz-pp01)/02)

**Goals:** more MRR managed per person · good customer service · good performance

*Inputs from Austin: 10–12 h per SEO onboarding and \~10 h per paid onboarding today, 2–3 of each a month. Assumptions: AI pre-filling cuts 50–60% (Karl: it would pull out "90% of the things").*

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Hours saved are estimates; onboarding hours and volumes are Austin's estimates. The strongest precedent is the existing prompt guide that cut strategy from \~3 days to about an hour.
- Needs read-only access at signing ([DS-08](ds-08-ai-sales-handover-extracted-from-sales-calls.md) add-on) and the AI-data rule ([DS-02](ds-02-ai-playbook-repository.md)).
- Needs Windsor.ai live (build 1) for the paid audit.
- The 30-item paid audit checklist is current and can be encoded.
- Aperitif's Ahrefs plan is Lite or above (MCP access) with enough API units.

## Decided

- Adopt as written; human sign-off on every audit and strategy.
