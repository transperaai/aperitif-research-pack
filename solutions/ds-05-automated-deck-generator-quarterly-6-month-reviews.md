---
id: DS-05
title: "Automated deck generator: quarterly + 6-month reviews and proposals"
team: "account managers and sales"  # inferred: the page gives no "Team:" line
bundle: "Delivery & reporting"
status: "Decided – priced"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-05 (deck part)", "O-22 (calculator part)", "O-14 (prospect-deck part)"]
earlier_ideas: ["EI-16 Proposal generator"]
written_sources: []
problems_fixed: ["P-05", "P-19", "P-18"]
problems_also_helped: ["P-21", "P-40", "P-25"]
problems_related_only: []
pain_points_cited: ["KZ-PP18", "KZ-PP21", "LS-PP02", "MP-PP10", "MP-PP11", "MP-PP12", "WS-PP05", "WS-PP07", "WS-PP13"]
pain_points_interviewer_raised_or_inferred: ["MP-PP10 (interviewer-raised)", "WS-PP13 (inferred)"]
value: "22–32 h/mo · A$69K–104K capacity (≈ 1.5–2 clients)"
value_time_h_month: [22, 32]
value_capacity_aud_per_year: [69000, 104000]
build_cost: "A$1850–A$2250"
monthly: "A$350/month maintenance + tokens ~US$5–40"
notion_section: "Automated deck generator: quarterly + 6-month reviews and proposals"
---

# DS-05 · Automated deck generator: quarterly + 6-month reviews and proposals

*Deck generator for quarterly and 6-month reviews and proposals (with price calculator); monthly reports stay in AgencyAnalytics.*

| | |
| --- | --- |
| Bundle | [Delivery & reporting](README.md#bundle-delivery-and-reporting) |
| Team | account managers and sales *(inferred)* |
| Status | Decided – priced |
| Source type | evidence-backed |
| Opportunities | [O-05](../opportunities/README.md#o-05) (deck part), [O-22](../opportunities/README.md#o-22) (calculator part), [O-14](../opportunities/README.md#o-14) (prospect-deck part) |
| Earlier ideas | [EI-16](../opportunities/README.md#ei-16) Proposal generator |
| Fixes | [P-05 Client documents are built by duplicating previous ones – errors reach clients](../problems/p-05-client-documents-are-built-by-duplicating-previous.md); [P-19 Proposals are rebuilt from scratch per prospect](../problems/p-19-proposals-are-rebuilt-from-scratch-per-prospect.md); [P-18 Sales commits to work delivery can't profitably do](../problems/p-18-sales-commits-to-work-delivery-can-t.md) |
| Also helps | [P-21 Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) – Solve now ("also helps (partly)"; capacity not solved – O-17/O-19/O-32 dropped); [P-40 AI use is personal and ungoverned: no policy, shared skills, client context or seats](../problems/p-40-ai-use-is-personal-and-ungoverned-no.md) – Solve later; [P-25 No single home for current templates – versions held by individuals](../problems/p-25-no-single-home-for-current-templates-versions.md) – Solve now (deck templates only) |
| Pain points cited | [KZ-PP18](../pain-points/README.md#kz-pp18), [KZ-PP21](../pain-points/README.md#kz-pp21), [LS-PP02](../pain-points/README.md#ls-pp02), [MP-PP10](../pain-points/README.md#mp-pp10) (interviewer-raised), [MP-PP11](../pain-points/README.md#mp-pp11), [MP-PP12](../pain-points/README.md#mp-pp12), [WS-PP05](../pain-points/README.md#ws-pp05), [WS-PP07](../pain-points/README.md#ws-pp07), [WS-PP13](../pain-points/README.md#ws-pp13) (inferred) |
| Written source | – |
| Value | 22–32 h/mo · A\$69K–104K capacity (≈ 1.5–2 clients) |
| Build cost | A\$1850–A\$2250 |
| Monthly | A\$350/month maintenance + tokens \~US\$5–40 |

## Vision

> **A tool that gathers the information from multiple sources, the consultant fills in a short form, and the system puts the deck together.**
>
> - Pulls performance data from the ad and analytics platforms.
> - Makes the graphs and visuals the team would normally screenshot by hand.
> - The consultant fills out a form for what the data can't tell it (context, wins, plans, the story).
> - The system assembles the finished deck in Aperitif's template.
>
> **Also in the vision (agreed 9 Nov):**
>
> 1. **The form pre-fills from the client brain** ([DS-04](ds-04-ai-client-brain.md)) – wins, issues and next-quarter plan drafted from calls and tasks; the consultant edits and confirms (\~5 minutes, not 20).
> 2. **Charts built natively** in Aperitif's style, always the right date range – **or the consultant can upload** their own screenshots/visuals where needed.
> 3. **Review step** – the consultant sees the draft, edits, approves; the final version is saved to the client brain.
> 4. **One set-up, several decks** – quarterly review, 6-month review, the bespoke multi-market monthly deck and proposals, each with its own template and form (proposals pull prospect research and the price calculator).

## Pricing & priority

> **Priority: Strategic build · Impact 4 / 5 · Effort 4 / 5 (draft – confirm)**
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **Deck generator** – quarterly + 6-month reviews, the multi-market monthly deck and proposals | **A\$1,850–\$2,250** | **A\$350/month** maintenance + AI tokens \~US\$5–40/month |

**Decision (9 Nov):** **monthly reports stay in AgencyAnalytics** – no change. **Quarterly and 6-month (bi-annual) review decks** are generated automatically through a deck generator, and **proposals are automated** the same way. It could be a custom build.

## How it works (draft)

1. The manager picks the client and deck type (quarterly review, 6-month review, or proposal).
2. The generator pulls the data: platform performance via AgencyAnalytics / GSC / Ahrefs / ad platforms for reviews; prospect research, Ahrefs data and the price calculator for proposals.
3. It fills the master template – charts, tables, work completed and planned – and AI drafts the narrative: wins, issues, recommendations, next-quarter plan.
4. The manager reviews and edits the story (human stays in the loop), then exports to Google Slides / PDF.
5. Proposals always carry the price-calculator output, so pricing isn't pulled from memory.

## Opportunities it covers

- **[O-05](../opportunities/README.md#o-05)** Reports and review decks: auto-filled data, AI-drafted narrative – rank 5, priority 100, quick win, effort M – **the quarterly / 6-month deck part**. The monthly report parts (report last page, weekly KPI sheets) are left out, as decided.
- **[O-22](../opportunities/README.md#o-22)** Sales discipline – the **calculator-in-every-proposal** part (rank 22).
- **[O-14](../opportunities/README.md#o-14)** AI-prefilled onboarding audit – the **prospect-deck** part ("the same engine can produce prospect decks", rank 14).
- Austin's earlier ideas: *Proposal generator*, *QBR / review deck generator*.
- Builds on a workflow the performance director already uses: AI-assisted quarterly reviews (WS-O06, strength WS-S02).

## Problems it fixes and the evidence

- [Client documents are built by duplicating previous ones – errors reach clients](../problems/p-05-client-documents-are-built-by-duplicating-previous.md) ([C-06](../synthesis/clusters-and-root-causes.md#c-06)) – 5 staff. *"these presentations and stuff that we need to do every quarter, etc. Which is like a lot of time consuming"* – the performance director ([WS-PP05](../pain-points/README.md#ws-pp05), stated). One senior SEO manager builds a bespoke multi-market deck by hand: *"So this probably takes me like half a day, if not more, of like work hours."* ([KZ-PP18](../pain-points/README.md#kz-pp18), stated).
- Also helps (partly): [Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) ([C-17](../synthesis/clusters-and-root-causes.md#c-17)) – 6-month reviews for smaller clients are where the SEO director loses time ([LS-PP02](../pain-points/README.md#ls-pp02)). **Capacity itself is not solved by a build**: the fixes aimed at its cause ([O-17](../opportunities/README.md#o-17) onboarding cap, [O-19](../opportunities/README.md#o-19) effort model, [O-32](../opportunities/README.md#o-32) senior performance hire) were dropped, and it is covered in the **culture / people recommendations** instead (Austin's call, 9 Nov).
- [Proposals are rebuilt from scratch per prospect](../problems/p-19-proposals-are-rebuilt-from-scratch-per-prospect.md) ([C-39](../synthesis/clusters-and-root-causes.md#c-39)) – leadership + 1 staff. Prospect decks are slow to build (research, Ahrefs, story) and land on top of BAU ([KZ-PP21](../pain-points/README.md#kz-pp21), stated). The founder is still pulled into building deal strategies and ad-spend numbers: *"So I'm still getting involved in a lot of that, but I don't want to"* – leadership ([MP-PP11](../pain-points/README.md#mp-pp11)).
- [Sales commits to work delivery can't profitably do](../problems/p-18-sales-commits-to-work-delivery-can-t.md) ([C-38](../synthesis/clusters-and-root-causes.md#c-38)) – leadership + 1 staff (the performance director, [WS-PP07](../pain-points/README.md#ws-pp07)); the price calculator exists but isn't used consistently ([MP-PP12](../pain-points/README.md#mp-pp12)). *Bias note: Austin raised this one first ([MP-PP10](../pain-points/README.md#mp-pp10)) and leadership agreed.*
- Also helps (Solve later): [AI use is personal and ungoverned: no policy, shared skills, client context or seats](../problems/p-40-ai-use-is-personal-and-ungoverned-no.md) – the director's personal AI review workflow becomes the shared standard ([WS-PP13](../pain-points/README.md#ws-pp13), *inferred*).
- [No single home for current templates – versions held by individuals](../problems/p-25-no-single-home-for-current-templates-versions.md) – Solve now; the generator runs from one master template per deck type, stored centrally (and registered in [DS-10](ds-10-systems-register-and-break-fix-runbook.md)).

## Future state (draft)

1. Every quarterly and 6-month review deck starts from one master template, filled automatically with the client's data.
2. AI drafts the narrative; the manager spends their time on the story and recommendations, not on screenshots and copy-paste.
3. Proposals and prospect decks are generated from research, Ahrefs and the price calculator, so they don't need the founder's numbers or a senior SEO manager's half-day.
4. Every proposal includes calculator pricing and passes a margin check before it goes out.
5. Monthly reporting carries on in AgencyAnalytics unchanged.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Hours per quarterly / 6-month review deck | Unknown – "a lot of time consuming" ([WS-PP05](../pain-points/README.md#ws-pp05)) | ≤ 1.5 h incl. review ([O-05](../opportunities/README.md#o-05)) |
| Review decks generated from the master template | 0% | 100% |
| Proposals with price-calculator output | Unknown – not consistent (MP-O07) | 100% |
| Time to produce a proposal / prospect deck | Unknown; slow, on top of BAU ([KZ-PP21](../pain-points/README.md#kz-pp21)) | Draft same day; baseline to be measured |
| Proposals needing founder input on numbers | Most ([MP-PP11](../pain-points/README.md#mp-pp11)) | Only above the scope threshold |

## Value (revised with Austin, 10 Nov)

> **Review decks and proposals built for you.** The generator fills Aperitif's slide templates with the client's results and context from the brain, so managers review and add the story instead of building every deck by hand – and sales gets proposals out the same day.

**1. Time saved**

| Task removed | How it's worked out | Per month |
| --- | --- | --- |
| Quarterly and six-month review decks | \~101 live clients: 60% get a six-month review (121 a year), 20% quarterly (81 a year) ≈ 17 decks a month × 1.5–2 h today → \~30 min to review | **\~16–24 h** (meeting prep already counted in [DS-04](ds-04-ai-client-brain.md) removed) |
| Sales proposals | \~6–8 proposals a month (conservative estimate – could be more) × 1.5 h today → \~30 min | **\~6–8 h** (sales and leadership time) |
| **Total** |  | **\~22–32 h ≈ A\$21K–31K a year** |

**2. Capacity and revenue unlocked**

Deck time freed (\~16–24 h) ÷ \~130 productive hours × \~A\$46.8K MRR per manager → **\~A\$5.7K–8.6K MRR ≈ A\$69K–104K a year of capacity** (≈ 1.5–2 more clients). Faster proposals also shorten an already 6–8 week sales cycle.

**3. Problems it eliminates**

- **P-05** Client documents are built by duplicating previous ones – errors reach clients
- **P-19** Proposals are rebuilt from scratch per prospect
- Helps: **P-18** Sales commits to work delivery can't profitably do · **P-21** Managers at capacity · **P-25** No single home for current templates

**Goals:** more MRR managed per person · good customer service · trust

*Inputs from Austin (10 Nov): 60% of clients get a six-month review, 20% quarterly; a deck takes 1.5–2 h (Disney is an outlier); proposals take \~1.5 h and should take \~30 min. Assumptions: \~30 min to review a generated deck; \~6–8 proposals a month.*

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Hours saved assumed; the only stated time is the half-day for one bespoke multi-market deck.
- The sales lead wasn't recorded, so proposal evidence is leadership plus one delivery staff member ([C-38](../synthesis/clusters-and-root-causes.md#c-38)/C-39).
- Needs one current master template per deck type (duplication errors today, [C-06](../synthesis/clusters-and-root-causes.md#c-06)), the AI-data rule ([DS-02](ds-02-ai-playbook-repository.md)) and data access.
- The SEO director is comfortable with AI-drafted 6-month reviews for **smaller clients** (LS-O11); larger clients may need more of the narrative written by hand.

## Decided (9 Nov)

- **Uses Aperitif's own slide templates**, driven either by a Claude skill or a custom workflow – no third-party deck SaaS.
- **The bespoke multi-market monthly deck is included** ([KZ-PP18](../pain-points/README.md#kz-pp18)) – the one monthly deck that moves into the generator.
- **"Work completed / planned" content stays human-supplied**, because forward planning isn't reliable enough to pull from; the generator only handles the **formatting and placement** on the deck.
- **Reads from the client brain ([DS-04](ds-04-ai-client-brain.md))** for the narrative, so reviews and proposals reflect what was agreed on calls.

Approach and price: see Pricing & priority.
