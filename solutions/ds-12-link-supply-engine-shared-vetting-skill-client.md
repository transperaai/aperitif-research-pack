---
id: DS-12
title: "Link supply engine: shared vetting skill, client matching, brand mentions (sourcing stage of the DS-11 CRM)"
team: "link building"  # inferred: the page gives no "Team:" line
bundle: "Link-building CRM"
status: "Decided (as written) – cost TBC"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-20 (vetting and matching part (brand mentions moved to DS-31))"]
earlier_ideas: []
written_sources: ["WS-ZC-01 Zach Chamberlain \"AI suggestions\" Google Doc"]
problems_fixed: ["P-34"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["KZ-PP06", "KZ-PP07", "LS-PP12", "TG-PP01", "TG-PP02", "TG-PP03", "TG-PP04", "TG-PP08", "TG-PP10", "ZC-PP16"]
pain_points_interviewer_raised_or_inferred: []
coi_per_year: "$5K–$19K"
build_cost: TBC
opex: TBC
notion_section: "Link supply engine: shared vetting, client matching, brand mentions"
---

# DS-12 · Link supply engine: shared vetting, client matching, brand mentions

*Shared vetting skill, client matching and quota reviews as the sourcing stage of the DS-11 CRM (brand mentions moved to DS-31).*

| | |
| --- | --- |
| Bundle | [Link-building CRM](README.md#bundle-link-building-crm) |
| Team | link building *(inferred)* |
| Status | Decided (as written) – cost TBC |
| Source type | evidence-backed |
| Opportunities | [O-20](../opportunities/README.md#o-20) (vetting and matching part (brand mentions moved to DS-31)) |
| Earlier ideas | – |
| Fixes | [P-34 Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent](../problems/p-34-link-sourcing-is-slow-manual-and-supply.md) |
| Also helps | – |
| Pain points cited | [KZ-PP06](../pain-points/README.md#kz-pp06), [KZ-PP07](../pain-points/README.md#kz-pp07), [LS-PP12](../pain-points/README.md#ls-pp12), [TG-PP01](../pain-points/README.md#tg-pp01), [TG-PP02](../pain-points/README.md#tg-pp02), [TG-PP03](../pain-points/README.md#tg-pp03), [TG-PP04](../pain-points/README.md#tg-pp04), [TG-PP08](../pain-points/README.md#tg-pp08), [TG-PP10](../pain-points/README.md#tg-pp10), [ZC-PP16](../pain-points/README.md#zc-pp16) |
| Written source | [Zach Chamberlain – "AI suggestions" Google Doc](https://docs.google.com/document/d/1bsjfs6Aw1F6VOA_nvhWwzPoFv8XHxaXp4Q8UHYAgtsw/edit) (WS-ZC-01) |
| Cost of inactivity / year | \$5K–\$19K |
| Build cost / OpEx | TBC |

## Vision

> **As written** – one shared vetting skill that agrees with the link lead, automatic client matching with no duplicates, and quota reviews where supply is scarce.
>
> **Bundle:** presented as part of the **Link-building CRM bundle** with [DS-11](ds-11-link-building-workflow-crm.md), but kept as its own solution (own scope, cost and KPIs).

**Your decision (9 Nov):** adopt [O-20](../opportunities/README.md#o-20) as written. It works as the **sourcing stage of the link-building CRM ([DS-11](ds-11-link-building-workflow-crm.md))**: domains are vetted and matched before they become orders.

## How it works

1. **One shared, versioned vetting skill** built from the link team's criteria (authority, relevance, spam signals, niche fit), tested against past approve/reject decisions so it agrees with the link lead.
2. Outreachers and broker intake run every domain through it before submitting; only **borderline domains** go to a person for review.
3. A **client requirements table** (niche, tier, exclusions, domains already used) lets Claude suggest the best client for each approved domain and block duplicates.
4. *(Moved to [DS-31](ds-31-proactive-brand-mention-tracking-for-backlinks.md) – its own solution, 9 Nov.)* **Brand-mention monitoring** (Ahrefs Alerts) finds unlinked mentions of Tier 1/2 clients and queues outreach to turn them into links.
5. Link quotas are reviewed with clients – fewer, higher-quality links where supply is scarce.

## Opportunities it covers

- **[O-20](../opportunities/README.md#o-20)** Widen link supply: shared vetting skill, client matching, mentions – rank 20, strategic, effort M (5–20 h/month, assumed)

## Problems it fixes and the evidence

- [Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent](../problems/p-34-link-sourcing-is-slow-manual-and-supply.md) – Solve now. 4 staff. *"I'll get 60 domains I need to vet and I'll go through one at a time... that's at least an hour or two process"* – the link-building lead ([KZ-PP06](../pain-points/README.md#kz-pp06), stated). The same Claude skill gives different answers – 54 domains passed the outreach specialist's check, the lead approved 27 ([TG-PP02](../pain-points/README.md#tg-pp02)); *"I'm not pretty sure if this is already accurate."* ([TG-PP01](../pain-points/README.md#tg-pp01)). Matching approved domains to clients is manual ([TG-PP04](../pain-points/README.md#tg-pp04)); duplicate domains for the same client were a problem ([TG-PP10](../pain-points/README.md#tg-pp10)).
- **Scarce supply for niche clients:** *"we hardly find leads for the dynamic clients."* ([TG-PP03](../pain-points/README.md#tg-pp03)); AI search gives few new sites ([TG-PP08](../pain-points/README.md#tg-pp08)).
- **Missed easy links:** *"automated scraping for brand mentions"* isn't done today ([ZC-PP16](../pain-points/README.md#zc-pp16)). Zach's written AI suggestions add: scrape weekly/monthly mentions of Tier 1 clients with no link or no dofollow link and contact the webmaster fast – *"if a mention was recently published, they will be more likely to link"*.
- **Slow end to end:** one link takes 1–2 months ([LS-PP12](../pain-points/README.md#ls-pp12)); domains added to the sheet go unseen for days ([KZ-PP07](../pain-points/README.md#kz-pp07)).

## Future state

1. Every domain is vetted by one shared skill that agrees with the link lead; only borderline cases need a person.
2. Each approved domain is matched to the right client automatically, with no duplicates.
3. Unlinked brand mentions become a steady new source of links for top clients.
4. Vetted, matched domains flow straight into the CRM as orders ([DS-11](ds-11-link-building-workflow-crm.md)).

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Lead time per vetting batch (\~60 domains) | 1–2 h, one at a time ([KZ-PP06](../pain-points/README.md#kz-pp06), stated) | ≤ 20 min human review |
| Agreement between skill and link lead | \~50% (54 passed vs 27 approved, [TG-PP02](../pain-points/README.md#tg-pp02)) | ≥ 90% |
| Duplicate domains per client | Has happened ([TG-PP10](../pain-points/README.md#tg-pp10)) | 0 |

## Cost of inactivity (COI)

|  | Per month | Per year |
| --- | --- | --- |
| Staff time on link sourcing & ordering today | 43–136 h (\$3.5K–\$10.9K) | \$42K–\$130K |
| Of which recoverable with this solution | 5–20 h (\$0.4K–\$1.6K) | **\$5K–\$19K** |

Also at risk, not quantified: client link targets missed for niche clients where supply is scarce; money spent on links from domains a consistent check would have rejected.

*Basis: process cost from the Stage 2 roll-up (Link building – sourcing & ordering 43.3–135.9 h; overlaps [DS-11](ds-11-link-building-workflow-crm.md)'s figure, so don't add the two process rows together). Recoverable from [O-20](../opportunities/README.md#o-20). Assumed. \$80/hr.*

## Indicative build cost and OpEx

**TBC by Austin.** OpEx: Claude seats ([DS-02](ds-02-ai-playbook-repository.md)), Ahrefs API and Alerts.

## Assumptions

- Hours saved assumed; the only stated time is 1–2 h per 60-domain batch.
- The link lead's criteria can be written down and tested on past decisions.
- Clients will accept quota changes where supply is scarce.

## Decided (9 Nov)

- Adopt as written; runs as the sourcing stage of the [DS-11](ds-11-link-building-workflow-crm.md) CRM.
