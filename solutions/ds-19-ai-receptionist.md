---
id: DS-19
title: "AI receptionist (phone; Aircall add-on)"
team: "sales / leadership (phones)"  # inferred: the page gives no "Team:" line
bundle: "New services and standalone tools"
status: "Recommended – build 17, AI receptionist"
coverage: addressed
source_type: "Austin addition"
opportunities: []
earlier_ideas: ["EI-03 AI receptionist"]
written_sources: []
problems_fixed: []
problems_also_helped: []
problems_related_only: ["P-42"]
pain_points_cited: ["KO-PP17", "KO-PP18"]
pain_points_interviewer_raised_or_inferred: []
value: "No missed calls; callers reach the right person"
---

# DS-19 · AI receptionist

*Aircall's AI receptionist answers inbound calls and routes new leads to Joe and existing clients to their account manager.*

| | |
| --- | --- |
| Bundle | [New services and standalone tools](README.md#bundle-new-services-and-standalone-tools) |
| Team | sales / leadership (phones) *(inferred)* |
| Status | Recommended – build 17, AI receptionist |
| Source type | Austin addition – Earlier idea; weak evidence (KO-PP17, KO-PP18 indirect); no problem fixed |
| Opportunities | – |
| Earlier ideas | [EI-03](../opportunities/README.md#ei-03) AI receptionist |
| Fixes | none |
| Also helps | – |
| Related only | [P-42 Growth depends on the founder and inbound leads while AI erodes core services](../problems/p-42-growth-depends-on-the-founder-and-inbound.md) – Reject |
| Pain points cited | [KO-PP17](../pain-points/README.md#ko-pp17), [KO-PP18](../pain-points/README.md#ko-pp18) |
| Written source | – |
| Value | No missed calls; callers reach the right person |

## Vision

> **Every inbound call reaches the right person – just a call director.** Aircall's AI receptionist answers each call, works out whether it's a new lead or an existing client, sends new leads to Joe and existing clients to their account manager, and logs the call to HubSpot or the client brain. Nothing more complex than that.
>
> - **Bought, not built:** Aircall's AI receptionist add-on (billed about A\$150–370 a month), set up and tuned by Transpera.
> - **Low priority:** there's no data yet on call volumes or missed calls, so it sits last in the start order (build 17, Phase 4); revisit once call data shows missed or misrouted calls.

## Decision

**Decision:** include the AI receptionist (Austin's earlier idea) as build 17, a "Reconsider" item: there's no merged opportunity and **little direct interview evidence**, so the builds above it come first.

## How it works

1. Aircall's AI receptionist answers inbound calls, day or night.
2. It identifies new leads and existing clients.
3. New leads are routed to Joe with the caller's details and logged in HubSpot; existing clients are routed to their account manager and the call is logged in the client brain ([DS-04](ds-04-ai-client-brain.md)).

## Problems it fixes and the evidence

- **Lead handling (indirect):** only about one in ten raw leads closes, and a large share are unreachable or have the wrong budget ([KO-PP18](../pain-points/README.md#ko-pp18), leadership). Sales still depends on the founder ([KO-PP17](../pain-points/README.md#ko-pp17)). An AI receptionist makes sure every new lead reaches Joe quickly. *Note: the related problem "Growth depends on the founder and inbound leads" ([P-42](../problems/p-42-growth-depends-on-the-founder-and-inbound.md)) is not taken forward in this proposal.*
- **Existing tool:** Aperitif already uses Aircall for inbound calls; its AI receptionist is a paid add-on.

## Future state

1. Every inbound call is answered and routed in seconds.
2. New leads reach Joe with the caller's details; existing clients reach their account manager.
3. Every call is logged, so nothing relies on someone remembering to write it down.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Inbound calls answered | Unknown | 100% |
| Calls routed to the right person first time | Unknown | ≥ 95% |

## Value

**Value: no missed calls, and callers reach the right person first time.** New leads go straight to Joe and existing clients go to their account manager, so no enquiry is lost and clients aren't passed around. Not measured – no call volumes or missed-call data.

**Goals:** good customer service · trust

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Austin's suggestion; weak interview evidence and no call volumes.
- Needs Aircall in use for inbound calls, and the HubSpot connection for logging.
- Revisit once call data shows missed or misrouted calls.

## Decided

- **Handles both** new leads and existing clients.
- **Phone only.**
- **Aircall's AI receptionist add-on**, not a custom build.
