---
id: DS-11
title: "Link-building workflow CRM (orders, publishers, links, invoicing and payments)"
team: "link building"  # inferred: the page gives no "Team:" line
bundle: "Link-building CRM"
status: "Decided – build vs buy and cost TBC"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-18 (full)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-06", "P-08"]
problems_also_helped: []
problems_related_only: ["P-07"]
pain_points_cited: ["KO-PP16", "KZ-PP08", "LS-PP12", "MP-PP14", "MP-PP15", "TG-PP05", "TG-PP06", "TG-PP07", "TG-PP09"]
pain_points_interviewer_raised_or_inferred: ["TG-PP09 (inferred)"]
coi_per_year: "$6K–$25K"
build_cost: TBC
opex: TBC
notion_section: "Link-building workflow CRM"
---

# DS-11 · Link-building workflow CRM

*Link-building CRM covering publishers, orders, live links, invoicing and payments.*

| | |
| --- | --- |
| Bundle | [Link-building CRM](README.md#bundle-link-building-crm) |
| Team | link building *(inferred)* |
| Status | Decided – build vs buy and cost TBC |
| Source type | evidence-backed – CRM-first is Austin decision |
| Opportunities | [O-18](../opportunities/README.md#o-18) (full) |
| Earlier ideas | – |
| Fixes | [P-06 Link building runs on 7+ disconnected spreadsheets](../problems/p-06-link-building-runs-on-7-disconnected-spreadsheets.md); [P-08 Outreacher invoicing tracked as PayPal links in spreadsheet cells](../problems/p-08-outreacher-invoicing-tracked-as-paypal-links-in.md) |
| Also helps | – |
| Related only | [P-07 Paid links disappear after payment – detected manually](../problems/p-07-paid-links-disappear-after-payment-detected-manually.md) – Solve now |
| Pain points cited | [KO-PP16](../pain-points/README.md#ko-pp16), [KZ-PP08](../pain-points/README.md#kz-pp08), [LS-PP12](../pain-points/README.md#ls-pp12), [MP-PP14](../pain-points/README.md#mp-pp14), [MP-PP15](../pain-points/README.md#mp-pp15), [TG-PP05](../pain-points/README.md#tg-pp05), [TG-PP06](../pain-points/README.md#tg-pp06), [TG-PP07](../pain-points/README.md#tg-pp07), [TG-PP09](../pain-points/README.md#tg-pp09) (inferred) |
| Written source | – |
| Cost of inactivity / year | \$6K–\$25K |
| Build cost / OpEx | TBC |

## Vision

> **The one place that runs the whole link-building operation.** It turns the many spreadsheets into one interconnected, **AI-native** system, so work is quicker and nobody updates multiple sheets.
>
> - Orders, publishers, live links and **payments** are all tracked here.
> - Other solutions **connect to it but stay separate**: the link watchdog ([DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md)), the link supply engine ([DS-12](ds-12-link-supply-engine-shared-vetting-skill-client.md)) and brand-mention tracking ([DS-31](ds-31-proactive-brand-mention-tracking-for-backlinks.md)).
> - It **feeds the AI Business Brain ([DS-15](ds-15-ai-business-brain-the-umbrella.md)) and each client brain ([DS-04](ds-04-ai-client-brain.md))** – which links were built for a client, where, and whether they're still live.

**Your decision (9 Nov):** go **straight to a link-building workflow CRM** (not the sheets-first route in [O-18](../opportunities/README.md#o-18)), covering the whole workflow **including outreacher invoicing and payments**. Custom build or off-the-shelf is TBC. The link watchdog ([DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md)) reads its link list from here.

## What it covers (draft)

| Stage | In the CRM |
| --- | --- |
| Publishers | Publisher and domain records, prices, terms, contact history, reliability score (from [DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md) drops) |
| Orders | One order template with fixed order IDs; client, target URL, anchor, requirements, price |
| Publisher view | External publishers see only their own orders and mark links complete – no copy-paste into their own sheets |
| Live links | Completed links recorded once, synced automatically to Monday and client reporting |
| Monitoring | Every live link handed to the watchdog ([DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md)) |
| Invoicing and payments | Outreachers invoice against link IDs; weekly payment run approved in one pass |

## Opportunities it covers

- **[O-18](../opportunities/README.md#o-18)** One link record: standard order template, auto-sync, invoice run – rank 18, strategic, effort M (6–26 h/month, assumed) – rebuilt as a CRM.
- Your earlier idea: *link-building CRM*. Leadership asked for it directly ([KO-PP16](../pain-points/README.md#ko-pp16)).

## Problems it fixes and the evidence

- [Link building runs on 7+ disconnected spreadsheets](../problems/p-06-link-building-runs-on-7-disconnected-spreadsheets.md) – Solve now. Staff + leadership. *"I would love, like, a CRM for our link-building team specifically. That is still being run out of spreadsheets."* – Head of Client Services ([KO-PP16](../pain-points/README.md#ko-pp16)). *"every published links I've found here. I encode it to the master sheet."* – the outreach specialist, re-keying all 300–340 links a month by hand ([TG-PP06](../pain-points/README.md#tg-pp06)). Orders are copy-pasted into each publisher's own sheet and order numbers sometimes change ([TG-PP05](../pain-points/README.md#tg-pp05)); the home-built Monday sync is unreliable ([TG-PP07](../pain-points/README.md#tg-pp07)); leadership: links are *"still kind of manually being copied over into the CRM for reporting"* ([MP-PP14](../pain-points/README.md#mp-pp14)).
- [Outreacher invoicing tracked as PayPal links in spreadsheet cells](../problems/p-08-outreacher-invoicing-tracked-as-paypal-links-in.md) – Solve later; included per your decision.
- **Link lead's time on admin:** *"it's like typically going to like that admin side rather than like helping do bigger things and growing the team"* ([KZ-PP08](../pain-points/README.md#kz-pp08)). Leadership: no manpower to improve it ([MP-PP15](../pain-points/README.md#mp-pp15)).
- **Home-built tools nobody else understands:** four home-built tools run by one person; the outreach specialist isn't sure they work properly (*undocumented status inferred, not stated* – [TG-PP09](../pain-points/README.md#tg-pp09)).
- Enables [DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md): [Paid links disappear after payment – detected manually](../problems/p-07-paid-links-disappear-after-payment-detected-manually.md) needs one clean link list.

## Future state (draft)

1. Every order, publisher, link and invoice lives in one system with one ID.
2. Publishers update their own orders; nobody re-keys links.
3. Live links flow automatically to Monday, client reporting and the watchdog.
4. Outreachers are paid weekly against verified link IDs in one approval pass.
5. The link lead spends time growing the team and supply, not on admin.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Published links re-keyed by hand | All 300–340 a month (TG-O02) | 0 |
| Order-number mismatches per month | "sometimes" (TG-O03) | 0 |
| Spreadsheets used to run link building | 7+ | 0 (CRM only) |
| Link lead hours on admin per month | Unknown – most of their time ([KZ-PP08](../pain-points/README.md#kz-pp08)) | Baseline, then −50% |

## Cost of inactivity (COI)

|  | Per month | Per year |
| --- | --- | --- |
| Staff time on link sourcing, ordering and invoicing today | 45–140 h (\$3.6K–\$11.2K) | \$43K–\$134K |
| Of which recoverable with this solution | 6–26 h (\$0.5K–\$2.1K) | **\$6K–\$25K** |

Also at risk, not quantified: link volume keeps rising ([LS-PP12](../pain-points/README.md#ls-pp12)) on a process that can't scale; key-person risk on undocumented home-built tools ([TG-PP09](../pain-points/README.md#tg-pp09)); payment errors from PayPal links in cells; and [DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md)'s savings depend on this list existing.

*Basis: process costs from the Stage 2 roll-up (sourcing & ordering 43.3–135.9 h; outreacher invoicing 1.3–3.8 h); recoverable from [O-18](../opportunities/README.md#o-18) (TG-O02 5.6–24.0 + KZ-O13 0.4–2.0). Sourcing time itself (vetting, negotiation) is mostly outside this solution – see [O-20](../opportunities/README.md#o-20). Assumed. \$80/hr.*

## Indicative build cost and OpEx

**TBC by Austin.** OpEx: CRM licence (if bought) or hosting (if built); payment processing.

## Assumptions

- Hours saved assumed.
- External publishers will use a portal/filtered view rather than their own sheets – some brokers may refuse.
- Existing sheets can be migrated (link history, order IDs) without losing data.
- Payment method (PayPal or other) stays the same; only the tracking moves.

## Open questions for you

- **Build vs buy:** custom build, or an off-the-shelf link-building CRM (e.g. Pitchbox, BuzzStream, Respona)? Claude can compare them on publisher portals, invoicing and Monday sync when you're ready.
