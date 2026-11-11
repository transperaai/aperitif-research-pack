---
id: P-08
title: "Outreacher invoicing tracked as PayPal links in spreadsheet cells"
decision: "Solve later"
status: addressed
fixed_by: ["DS-11"]
also_helped_by: []
related_only: []
clusters: ["C-23"]
root_causes: ["RC-01"]
pain_points: ["KO-PP16", "KZ-PP08", "MP-PP14", "MP-PP15", "TG-PP05", "TG-PP06", "TG-PP07"]
theme: "Process / automation"
severity: "Medium"
confidence: "Medium – raised by 2"
---

# P-08 · Outreacher invoicing tracked as PayPal links in spreadsheet cells

| | |
| --- | --- |
| Decision | **Solve later** |
| Status | addressed – Fixed by [DS-11](../solutions/ds-11-link-building-workflow-crm.md) |
| Theme · severity · confidence | Process / automation · Medium · Medium – raised by 2 |
| Process area | Finance / admin |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-11 Link-building workflow CRM (orders, publishers, links, invoicing and payments)](../solutions/ds-11-link-building-workflow-crm.md)

## Linked opportunities

- [O-18](../opportunities/README.md#o-18) One link record: standard order template, auto-sync, invoice run – addressed ([DS-11](../solutions/ds-11-link-building-workflow-crm.md))
- [O-20](../opportunities/README.md#o-20) Widen link supply: shared vetting skill, client matching, mentions – addressed ([DS-12](../solutions/ds-12-link-supply-engine-shared-vetting-skill-client.md), [DS-31](../solutions/ds-31-proactive-brand-mention-tracking-for-backlinks.md))

## Root cause and cluster

- Cluster [C-23](../synthesis/clusters-and-root-causes.md#c-23): Link building runs on disconnected sheets; every order, link and invoice is re-keyed – raised by 2 staff + 2 leadership; confidence High.
- Root cause [RC-01](../synthesis/clusters-and-root-causes.md#rc-01): No system of record: budgets, client data, briefs, links and files are held in many hand-maintained copies, so people re-key, reconcile and collate by hand.
- Root cause (problem record): Payments to external outreachers are per-person, per-link, in mixed currencies (USD, AUD) with no ledger outside the sheets.

## Pain points (7)

- [KO-PP16](../pain-points/README.md#ko-pp16) – Link building has no CRM: publishers, orders and outstanding invoices live in spreadsheets, and there is no automatic check for dropped links
  - *Julia: "I would love, like, a CRM for our link-building team specifically. That is still being run out of spreadsheets."* – Julia Van Der Linden, Leadership (kick-off) · staff-raised · [\~79:34 (L368)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L419) · Austin: Agree
- [KZ-PP08](../pain-points/README.md#kz-pp08) – The link lead's time goes on admin (vetting, invoices) instead of developing and growing the link team
  - *"it's like typically going to like that admin side rather than like helping do bigger things and growing the team a bit more"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~11:11 (L111)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L115) · Austin: Agree
- [MP-PP14](../pain-points/README.md#mp-pp14) – Links copied by hand from tracker into CRM for reporting
  - *"When these links go into the tracker, It's still kind of manually being copied over into the CRM for reporting"* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~04:32 (L048)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L51) · Austin: Agree
- [MP-PP15](../pain-points/README.md#mp-pp15) – Link-building admin still on sheets; no capacity to improve it
  - *"there's stuff that we just can't do at the moment because we just don't have the manpower."* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~04:32 (L048)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L51) · Austin: Agree
- [TG-PP05](../pain-points/README.md#tg-pp05) – Orders to external publishers copy-pasted into each publisher's own sheet; order numbers sometimes change
  - *"for the other publishers, since we have different sheets for them, so I copy and paste documents on the sheets"* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~04:25 (L031)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L38) · Austin: Agree
- [TG-PP06](../pain-points/README.md#tg-pp06) – Every published link re-keyed from publisher sheets into the master sheet and other sheets
  - *"And then every published links I've found here. I encode it to the master sheet."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~39:07–39:13 (L404–L405)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L411) · Austin: Agree
- [TG-PP07](../pain-points/README.md#tg-pp07) – Home-built master sheet → Monday.com sync unreliable; managers raised concerns
  - *"for the October, it added already, but I received a few concerns from the managers, from the handlers."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~41:14 (L439)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L446)

## Best quotes and figures

Juliet sheet: PayPal invoice URL and PAID flag per row. Joe: AI agents to follow up on overdue/outstanding invoices for Karl.
