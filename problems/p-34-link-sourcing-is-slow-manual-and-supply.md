---
id: P-34
title: "Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent"
decision: "Solve now"
status: addressed
fixed_by: ["DS-12", "DS-31"]
also_helped_by: []
related_only: []
clusters: ["C-24"]
root_causes: ["RC-06"]
pain_points: ["KZ-PP06", "KZ-PP07", "KZ-PP09", "LS-PP12", "TG-PP01", "TG-PP02", "TG-PP03", "TG-PP04", "TG-PP08", "TG-PP10", "TG-PP12", "ZC-PP16"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
---

# P-34 · Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent

| | |
| --- | --- |
| Decision | **Solve now** |
| Status | addressed – Fixed by [DS-12](../solutions/ds-12-link-supply-engine-shared-vetting-skill-client.md), [DS-31](../solutions/ds-31-proactive-brand-mention-tracking-for-backlinks.md) |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-12 Link supply engine: shared vetting skill, client matching, brand mentions (sourcing stage of the DS-11 CRM)](../solutions/ds-12-link-supply-engine-shared-vetting-skill-client.md)
- Fixes: [DS-31 Proactive brand-mention tracking for backlinks (split from DS-12)](../solutions/ds-31-proactive-brand-mention-tracking-for-backlinks.md) – the supply part

## Linked opportunities

- [O-18](../opportunities/README.md#o-18) One link record: standard order template, auto-sync, invoice run – addressed ([DS-11](../solutions/ds-11-link-building-workflow-crm.md))
- [O-20](../opportunities/README.md#o-20) Widen link supply: shared vetting skill, client matching, mentions – addressed ([DS-12](../solutions/ds-12-link-supply-engine-shared-vetting-skill-client.md), [DS-31](../solutions/ds-31-proactive-brand-mention-tracking-for-backlinks.md))
- [O-22](../opportunities/README.md#o-22) Sales discipline: calculator, margin check, speed-to-lead – partly addressed ([DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md))
- [EI-21](../opportunities/README.md#ei-21) Unlinked brand-mention monitoring and outreach (Tier 1) – absorbed ([DS-31](../solutions/ds-31-proactive-brand-mention-tracking-for-backlinks.md))

## Root cause and cluster

- Cluster [C-24](../synthesis/clusters-and-root-causes.md#c-24): Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent – raised by 4 staff + 0 leadership; confidence High.
- Root cause [RC-06](../synthesis/clusters-and-root-causes.md#rc-06): Decisions and quality gates sit with a few senior people because authority isn't delegated and the management layer is thin.
- Root cause (problem record): [RC-06](../synthesis/clusters-and-root-causes.md#rc-06): Decisions and quality gates sit with a few senior people. Chain: links reach clients 1–2 months late ([LS-PP12](../pain-points/README.md#ls-pp12), [KZ-PP07](../pain-points/README.md#kz-pp07), [TG-PP12](../pain-points/README.md#tg-pp12)) → domains queue for one approver and are vetted by hand; qualifying supply is scarce ([KZ-PP06](../pain-points/README.md#kz-pp06), [KZ-PP07](../pain-points/README.md#kz-pp07), [TG-PP03](../pain-points/README.md#tg-pp03), [TG-PP08](../pain-points/README.md#tg-pp08)) → the AI lead-review skill disagrees with the approver ([TG-PP01](../pain-points/README.md#tg-pp01), [TG-PP02](../pain-points/README.md#tg-pp02), [TG-PP10](../pain-points/README.md#tg-pp10)) → vetting criteria live in one approver's judgement and were never calibrated or delegated.

## Pain points (12)

- [KZ-PP06](../pain-points/README.md#kz-pp06) – Domain vetting is slow and manual: \~60 domains through Ahrefs plus a manual spam check takes 1–2 h a batch
  - *"I'll get 60 domains I need to vet and I'll go through one at a time... that's at least an hour or two process"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~13:14 (L131)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L135)
- [KZ-PP07](../pain-points/README.md#kz-pp07) – A link takes at least a month end to end; late links come from review delays, domains added to the sheet unseen and publishers going quiet
  - *"It takes me a couple of days maybe to get to reviewing the domains and then Tony [Tonie] will add more to the sheet and I don't see"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~13:55 (L132)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L136)
- [KZ-PP09](../pain-points/README.md#kz-pp09) – Outreach shortlists included spammy, low-quality domains, adding review time (now mitigated by shared Claude prompts)
  - *"i'm looking through these sites that are like dictionary websites and stuff that are clearly just trying to like get spammy keywords"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~15:00 (L145)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L149)
- [LS-PP12](../pain-points/README.md#ls-pp12) – Link building is slow (1–2 months per link) and still largely manual; volume keeps rising
  - *"One link takes a month to two months, with a delay usually."* – Laura Shillington, SEO Director · staff-raised · [\~22:18 (L090)](../interviews/ls-laura-shillington/transcript.md?plain=1#L108) · Austin: Agree
- [TG-PP01](../pain-points/README.md#tg-pp01) – Claude lead-review skill rejects most leads (32 of \~1,000) and its accuracy is unknown
  - *"I'm not pretty sure if this is already accurate. So, really need your help with this."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~17:49–18:01 (L170–L171)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L177) · Austin: Agree
- [TG-PP02](../pain-points/README.md#tg-pp02) – Same skill, different answers: 54 passed Tonie's check, Karl approved 27
  - *"He only approved 27."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~22:51 (L227)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L234) · Austin: Agree
- [TG-PP03](../pain-points/README.md#tg-pp03) – Tier 1 (single-niche) sites for dynamic clients (BCR, Five Good Friends, Leaselab) are scarce and expensive
  - *"the struggle is that we hardly find leads for the dynamic clients."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~11:14 (L090)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L97)
- [TG-PP04](../pain-points/README.md#tg-pp04) – Matching approved domains to clients is manual and time-consuming
  - *"Yes, because it is also one of the time-consuming tasks."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~35:46 (L369)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L376) · Austin: Agree
- [TG-PP08](../pain-points/README.md#tg-pp08) – Self-sourcing new qualifying sites is limited; AI search gives few results; supply leans on brokers
  - *"But this gives limited results."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~27:40 (L279)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L286)
- [TG-PP10](../pain-points/README.md#tg-pp10) – Duplicate domains for the same client were a problem; checker accuracy still uncertain
  - *"previously we really have trouble in having duplicated domains for the same client."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~32:04 (L330)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L337) · Austin: Agree
- [TG-PP12](../pain-points/README.md#tg-pp12) – Publisher negotiation 1–2 weeks; some links take 1–3 weeks to publish
  - *"While some, it takes one, two, three weeks. It depends on the publisher."* – Tonie Guevarra, Outreach Specialist · staff-raised · [\~12:50 (L101)](../interviews/tg-tonie-guevarra/transcript.md?plain=1#L108)
- [ZC-PP16](../pain-points/README.md#zc-pp16) – Unlinked client brand mentions aren't monitored or turned into links
  - *"one thing that we're currently not doing that I think we could would be automated scraping for brand mentions."* – Zach Chamberlain, SEO Manager · staff-raised · [\~34:41 (L363)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L369) · Austin: Agree

## Best quotes and figures

"I'll get 60 domains I need to vet and I'll go through one at a time... that's at least an hour or two process" – the link-building team ([KZ-PP06](../pain-points/README.md#kz-pp06), \~13:14, L131) | "I'm not pretty sure if this is already accurate. So, really need your help with this." – the link-building team ([TG-PP01](../pain-points/README.md#tg-pp01), \~17:49, L170–L171) | "One link takes a month to two months, with a delay usually." – an SEO manager ([LS-PP12](../pain-points/README.md#ls-pp12), \~22:18, L090)
