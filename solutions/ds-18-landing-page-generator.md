---
id: DS-18
title: "Landing page generator (ad landing pages, Aperitif-hosted)"
team: "PPC"  # inferred: the page gives no "Team:" line
bundle: "Standalone"
status: "Decided – cost TBC"
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
build_cost: TBC
opex: TBC
notion_section: "Landing page generator"
---

# DS-18 · Landing page generator

*In-house landing page generator for ad landing pages on Aperitif-hosted pages.*

| | |
| --- | --- |
| Bundle | [Standalone](README.md#bundle-standalone) |
| Team | PPC *(inferred)* |
| Status | Decided – cost TBC |
| Source type | Austin addition – Earlier idea, no merged opportunity; problem evidence KO-PP25, WS-PP14 |
| Opportunities | – |
| Earlier ideas | [EI-09](../opportunities/README.md#ei-09) Landing page generator |
| Fixes | [P-38 Creative and landing pages are outsourced, slow and hard to brief](../problems/p-38-creative-and-landing-pages-are-outsourced-slow.md) |
| Also helps | – |
| Pain points cited | [KO-PP25](../pain-points/README.md#ko-pp25), [SH-PP11](../pain-points/README.md#sh-pp11), [WS-PP07](../pain-points/README.md#ws-pp07), [WS-PP14](../pain-points/README.md#ws-pp14) |
| Written source | – |
| Cost of inactivity / year | Not quantified – needs count of pages outsourced per year |
| Build cost / OpEx | TBC |

## Vision

> **An AI tool like "Landing Page Labs":** clone a client's website brand identity (colours, fonts, style) and make landing pages for ads. It uses Aperitif's own **CRO-optimised page structures**; the team just customises the content, assets and creatives in a CMS.
>
> **Buy-first check (9 Nov):** off-the-shelf AI builders already do brand cloning and AI page generation – e.g. LanderLab (clone any page from a URL), Leadpages (generate a page from a website with brand Style Kits), Flint (extracts a brand system from the client's site), Swipe Pages and Unbounce (AI builder, A/B testing, dynamic text replacement for ad keywords). Worth trialling one with Aperitif's CRO templates before building.

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

## Cost of inactivity (COI)

Not quantified from the interviews: outsourcing at \~\$1,500 a page, campaigns delayed while pages are built, and landing-page revenue lost because clients won't pay the outsourced price. Needs the number of pages outsourced per year to put a dollar figure on it.

## Indicative build cost and OpEx

**TBC by Austin.**

## Assumptions

- Your suggestion; evidence is leadership + one staff member.
- Clients' CMSs allow publishing generated pages (or a hosted page builder is used).

## Decided (9 Nov)

- **Aperitif-controlled hosting** – pages are mainly **landing pages for ads**, published on a page builder Aperitif controls (not the client's CMS).
- **Internal tool for now** – not sold as a separate product yet.
- Pages outsourced per year: **unknown** – COI stays unquantified until counted (worth asking the performance director).
