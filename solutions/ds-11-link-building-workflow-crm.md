---
id: DS-11
title: "Link-building workflow CRM (orders, publishers, links, invoicing and payments)"
team: "link building"  # inferred: the page gives no "Team:" line
bundle: "Link-building CRM"
status: "Decided – custom build; priced"
coverage: addressed
source_type: "evidence-backed"
opportunities: ["O-18 (full)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-06", "P-08"]
problems_also_helped: []
problems_related_only: ["P-07"]
pain_points_cited: ["KO-PP16", "KZ-PP08", "LS-PP12", "MP-PP14", "MP-PP15", "TG-PP05", "TG-PP06", "TG-PP07", "TG-PP09"]
pain_points_interviewer_raised_or_inferred: ["TG-PP09 (inferred)"]
value: "18.5–30 h/mo · ~9–15 more links a month (delivery capacity)"
value_time_h_month: [18.5, 30]
value_extra_links_month: [9, 15]
---

# DS-11 · Link-building workflow CRM

*Link-building CRM covering publishers, orders, live links, invoicing and payments.*

| | |
| --- | --- |
| Bundle | [Link-building CRM](README.md#bundle-link-building-crm) |
| Team | link building *(inferred)* |
| Status | Decided – custom build; priced |
| Source type | evidence-backed – CRM-first is Austin decision |
| Opportunities | [O-18](../opportunities/README.md#o-18) (full) |
| Earlier ideas | – |
| Fixes | [P-06 Link building runs on 7+ disconnected spreadsheets](../problems/p-06-link-building-runs-on-7-disconnected-spreadsheets.md); [P-08 Outreacher invoicing tracked as PayPal links in spreadsheet cells](../problems/p-08-outreacher-invoicing-tracked-as-paypal-links-in.md) |
| Also helps | – |
| Related only | [P-07 Paid links disappear after payment – detected manually](../problems/p-07-paid-links-disappear-after-payment-detected-manually.md) – Solve now |
| Pain points cited | [KO-PP16](../pain-points/README.md#ko-pp16), [KZ-PP08](../pain-points/README.md#kz-pp08), [LS-PP12](../pain-points/README.md#ls-pp12), [MP-PP14](../pain-points/README.md#mp-pp14), [MP-PP15](../pain-points/README.md#mp-pp15), [TG-PP05](../pain-points/README.md#tg-pp05), [TG-PP06](../pain-points/README.md#tg-pp06), [TG-PP07](../pain-points/README.md#tg-pp07), [TG-PP09](../pain-points/README.md#tg-pp09) (inferred) |
| Written source | – |
| Value | 18.5–30 h/mo · \~9–15 more links a month (delivery capacity) |

## Vision

> **The one place that runs the whole link-building operation.** It turns the many spreadsheets into one interconnected, **AI-native** system, so work is quicker and nobody updates multiple sheets.
>
> - Orders, publishers, live links and **payments** are all tracked here.
> - Other solutions **connect to it but stay separate**: the link watchdog ([DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md)), the link supply engine ([DS-12](ds-12-link-supply-engine-shared-vetting-skill-client.md)) and brand-mention tracking ([DS-31](ds-31-proactive-brand-mention-tracking-for-backlinks.md)).
> - It **feeds the AI Business Brain ([DS-15](ds-15-ai-business-brain-the-umbrella.md)) and each client brain ([DS-04](ds-04-ai-client-brain.md))** – which links were built for a client, where, and whether they're still live.

## Decision

**Decision (9 Nov):** go **straight to a link-building workflow CRM** (not the sheets-first route in [O-18](../opportunities/README.md#o-18)), covering the whole workflow **including outreacher invoicing and payments**. Recommended: a custom AI-native build. The link watchdog ([DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md)) reads its link list from here.

## What it covers

| Stage | In the CRM |
| --- | --- |
| Publishers | Publisher and domain records, prices, terms, contact history, reliability score (from [DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md) drops) |
| Orders | One order template with fixed order IDs; client, target URL, anchor, requirements, price |
| Publisher view | External publishers see only their own orders and mark links complete – no copy-paste into their own sheets |
| Live links | Completed links recorded once, synced automatically to Monday and client reporting |
| Monitoring | Every live link handed to the watchdog ([DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md)) |
| Invoicing and payments | Outreachers invoice against link IDs; weekly payment run approved in one pass |

## Opportunities it covers

- **[O-18](../opportunities/README.md#o-18)** One link record: standard order template, auto-sync, invoice run – rank 18, strategic, effort M – rebuilt as a CRM.
- Austin's earlier idea: *link-building CRM*. Leadership asked for it directly ([KO-PP16](../pain-points/README.md#ko-pp16)).

## Problems it fixes and the evidence

- [Link building runs on 7+ disconnected spreadsheets](../problems/p-06-link-building-runs-on-7-disconnected-spreadsheets.md) – Solve now. Staff + leadership. *"I would love, like, a CRM for our link-building team specifically. That is still being run out of spreadsheets."* – Head of Client Services ([KO-PP16](../pain-points/README.md#ko-pp16)). *"every published links I've found here. I encode it to the master sheet."* – the outreach specialist, re-keying all 300–340 links a month by hand ([TG-PP06](../pain-points/README.md#tg-pp06)). Orders are copy-pasted into each publisher's own sheet and order numbers sometimes change ([TG-PP05](../pain-points/README.md#tg-pp05)); the home-built Monday sync is unreliable ([TG-PP07](../pain-points/README.md#tg-pp07)); leadership: links are *"still kind of manually being copied over into the CRM for reporting"* ([MP-PP14](../pain-points/README.md#mp-pp14)).
- [Outreacher invoicing tracked as PayPal links in spreadsheet cells](../problems/p-08-outreacher-invoicing-tracked-as-paypal-links-in.md) – Solve later; included as decided.
- **Link lead's time on admin:** *"it's like typically going to like that admin side rather than like helping do bigger things and growing the team"* ([KZ-PP08](../pain-points/README.md#kz-pp08)). Leadership: no manpower to improve it ([MP-PP15](../pain-points/README.md#mp-pp15)).
- **Home-built tools nobody else understands:** four home-built tools run by one person; the outreach specialist isn't sure they work properly (*undocumented status inferred, not stated* – [TG-PP09](../pain-points/README.md#tg-pp09)).
- Enables [DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md): [Paid links disappear after payment – detected manually](../problems/p-07-paid-links-disappear-after-payment-detected-manually.md) needs one clean link list.

## Future state

1. Every order, publisher, link and invoice lives in one system with one ID.
2. Publishers update their own orders; nobody re-keys links.
3. Live links flow automatically to Monday, client reporting and the watchdog.
4. Outreachers are paid weekly against verified link IDs in one approval pass.
5. The link lead spends time growing the team and supply, not on admin.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Published links re-keyed by hand | \~320 a month (client board) | 0 |
| Order-number mismatches per month | "sometimes" (TG-O03) | 0 |
| Spreadsheets used to run link building | 7+ | 0 (CRM only) |
| Link lead hours on admin per month | Unknown – most of their time ([KZ-PP08](../pain-points/README.md#kz-pp08)) | Baseline, then −50% |

## Value

> **One system for every link.** Orders, publishers, live links and invoices live in one CRM, so nobody copies orders into publisher sheets or re-keys every published link into the master sheet.

**1. Time saved**

| Task removed | How it's worked out | Per month |
| --- | --- | --- |
| Re-keying orders and live links, matching links to clients | \~320 links a month (live clients, client board) × 5–8 min ≈ 27–43 h today; the CRM removes \~70% (links are still entered once) | **\~18.5–30 h** |

**2. Capacity and revenue unlocked**

At \~2 h of team time per link today, \~18.5–30 h freed ≈ room for **\~9–15 more links a month** without hiring. Links are sold inside SEO retainers, so this is delivery capacity, not extra revenue on top of the SEO figures.

**3. Problems it eliminates**

- **P-06** Link building runs on 7+ disconnected spreadsheets
- **P-08** Outreacher invoicing tracked as PayPal links in spreadsheet cells

**Goals:** more MRR managed per person · good performance · trust

*Inputs from Austin (10 Nov): \~320 links a month for live clients (client board), 5–8 min admin per link, \~2 h team time per link; links are sold to clients at A\$250–500 and cost Aperitif \~A\$80–130. Assumption: CRM removes \~70% of re-keying.*

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Hours saved assumed.
- External publishers will use a portal/filtered view rather than their own sheets – some brokers may refuse.
- Existing sheets can be migrated (link history, order IDs) without losing data.
- Payment method (PayPal or other) stays the same; only the tracking moves.

## Build vs buy

- Off-the-shelf link-building CRMs (e.g. Pitchbox, BuzzStream, Respona) were considered; a **custom AI-native build** is recommended so it fits Aperitif's broker and publisher workflow and connects to the client brain.
