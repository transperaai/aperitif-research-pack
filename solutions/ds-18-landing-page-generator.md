---
id: DS-18
title: "Landing page generator (ad landing pages, Aperitif-hosted)"
team: "PPC"  # inferred: the page gives no "Team:" line
bundle: "Standalone"
status: "Decided – priced"
ledger_status: addressed
source_type: "Austin addition"
opportunities: []
earlier_ideas: ["EI-09 Landing page generator"]
written_sources: []
problems_fixed: ["P-38"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["KO-PP25", "SH-PP11", "WS-PP07", "WS-PP14"]
pain_points_interviewer_raised_or_inferred: []
coi_per_year: "Not quantified"
build_cost: "A$12,000"
monthly: "A$1,500/month + hosting/tokens"
notion_section: "Landing page generator"
---

# DS-18 · Landing page generator

*In-house landing page generator for ad landing pages on Aperitif-hosted pages.*

| | |
| --- | --- |
| Bundle | [Standalone](README.md#bundle-standalone) |
| Team | PPC *(inferred)* |
| Status | Decided – priced |
| Source type | Austin addition – Earlier idea, no merged opportunity; problem evidence KO-PP25, WS-PP14 |
| Opportunities | – |
| Earlier ideas | [EI-09](../opportunities/README.md#ei-09) Landing page generator |
| Fixes | [P-38 Creative and landing pages are outsourced, slow and hard to brief](../problems/p-38-creative-and-landing-pages-are-outsourced-slow.md) |
| Also helps | – |
| Pain points cited | [KO-PP25](../pain-points/README.md#ko-pp25), [SH-PP11](../pain-points/README.md#sh-pp11), [WS-PP07](../pain-points/README.md#ws-pp07), [WS-PP14](../pain-points/README.md#ws-pp14) |
| Written source | – |
| Value | A new service offering (outsourced today at \~A\$1,500 a page) |
| Build cost | A\$12,000 |
| Monthly | A\$1,500/month + hosting/tokens |

## Vision

> **An AI tool like "Landing Page Labs":** clone a client's website brand identity (colours, fonts, style) and make landing pages for ads. It uses Aperitif's own **CRO-optimised page structures**; the team just customises the content, assets and creatives in a CMS.
>
> **Buy-first check (9 Nov):** off-the-shelf AI builders already do brand cloning and AI page generation – e.g. LanderLab (clone any page from a URL), Leadpages (generate a page from a website with brand Style Kits), Flint (extracts a brand system from the client's site), Swipe Pages and Unbounce (AI builder, A/B testing, dynamic text replacement for ad keywords). Worth trialling one with Aperitif's CRO templates before building.

## Pricing & priority

> **Priority: Impact 2 / 5 · Effort 2 / 5 (draft – re-score for custom build)** · Standalone
>
> | Option | Build cost | Monthly cost |
> | --- | --- | --- |
> | **Recommended – custom landing page generator** (brand cloning, Aperitif CRO templates, CMS for content and assets, Aperitif-hosted) | **A\$12,000** | **A\$1,500/month** maintenance + hosting/tokens |
> | *For comparison – off-the-shelf builder* (e.g. LanderLab) with Aperitif templates | – | US\$119–239/month |

**Your decision (9 Nov):** add the landing page generator (your earlier idea). There's no merged opportunity for it, but the interviews do support the problem.

## How it works (draft)

1. The manager picks the client, campaign and offer.
2. The generator pulls the client's brand, tone, style guide and USPs from the client brain ([DS-04](ds-04-ai-client-brain.md)), and the campaign's keywords and ad copy.
3. It builds the page from Aperitif's own templates – copy, layout, form, tracking tags – ready to publish to the client's CMS or a hosted page.
4. The manager reviews and edits, then publishes. Variants for testing can be generated from the same page.

## Problems it fixes and the evidence

- [Creative and landing pages are outsourced, slow and hard to brief](../problems/p-38-creative-and-landing-pages-are-outsourced-slow.md) – Solve now. 2 staff + leadership, stated.
  - *"outsourcing landing page builds is a bit clunky"* – founder ([KO-PP25](../pain-points/README.md#ko-pp25)); clients are reluctant to pay for them.
  - *"We don't have the capacity. And like we usually sell them to the clients as well."* – the performance director ([WS-PP14](../pain-points/README.md#ws-pp14)). Outsourced pages cost **\~\$1,500 each**, which is a barrier for clients.
- Also related: clients sold without a working website ([WS-PP07](../pain-points/README.md#ws-pp07)) – a fast page can get a campaign live; client page changes break tracking ([SH-PP11](../pain-points/README.md#sh-pp11)) – pages Aperitif controls are tracked from the start.

## Future state (draft)

1. Landing pages are built in-house in hours, not outsourced over weeks.
2. They become a product Aperitif can sell at a lower price with a better margin.
3. Every page has tracking set up correctly from day one.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Time to a live landing page | Outsourced, "clunky" ([KO-PP25](../pain-points/README.md#ko-pp25)) | ≤ 2 business days |
| Cost per landing page | \~\$1,500 outsourced ([WS-PP14](../pain-points/README.md#ws-pp14)) | Baseline in-house cost, then set |
| Landing pages sold per month | Low – price barrier | Baseline, then set |

## Value (revised with Austin, 10 Nov)

**Value: a new service offering and a capability gain.** Landing pages are outsourced today at \~A\$1,500 each, campaigns wait while they're built, and some clients won't pay that price. With an in-house generator Aperitif can build branded, CRO-structured pages itself, launch campaigns sooner, and sell landing pages as a service. No figures claimed.

**Goals:** good performance · good customer service · more MRR managed per person

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Your suggestion; evidence is leadership + one staff member.
- Clients' CMSs allow publishing generated pages (or a hosted page builder is used).

## Decided (9 Nov)

- **Aperitif-controlled hosting** – pages are mainly **landing pages for ads**, published on a page builder Aperitif controls (not the client's CMS).
- **Internal tool for now** – not sold as a separate product yet.
- Pages outsourced per year: **unknown** – COI stays unquantified until counted (worth asking the performance director).
