# Aperitif audit – context pack

Reference for AI transcript extraction. Attach this alongside every transcript. Compiled 6 Nov 2026 from the audit Evidence Log. Use it to correct mis-heard names, label roles, match problems, and cost time.

Items marked *(inferred)* are best guesses from the evidence – confirm before quoting them in the pack.

---

## 1. The business in one paragraph

Aperitif is a ~27-person Australian digital marketing agency, founded and run by Joe Romeo. Services: SEO / organic search (incl. AI search visibility), content writing, link building, paid media (Google, Meta, Microsoft/Bing, LinkedIn, TikTok, Reddit, ChatGPT ads), creative, and website migrations. Clients are tiered (Tier 1 = largest/enterprise, down to Tier 3/4). The paid media book has grown from 18 clients / ~$30K monthly ad budget (Dec 2022) to 61 clients / ~$788K monthly ad budget (Nov 2026). Link building runs like an agency inside the agency, with internal and external outreachers paid per link.

The audit (by Austin Smith, Transpera AI, Oct–Nov 2026) is looking at where time and margin leak, and what to fix with process change, AI augmentation or automation. Findings presentation: 12 Nov 2026.

## 2. People

### Leadership and sales
| Name | Role | Reports to | Notes |
|---|---|---|---|
| Joe Romeo | Founder & Principal Consultant | – | Maintains much of the Notion wiki; runs personal AI agents (OpenClaw) in Slack |
| Julia Van Der Linden | Head of Client Services | Joe | Escalations currently land with her |
| Jethro Jason | Growth Strategy Lead (sales) | Joe | New hire; interview not recorded |

### Organic (SEO, content, link building)
| Name | Role | Reports to | Notes |
|---|---|---|---|
| Laura Shillington | SEO Director | Julia | Owns most SEO templates and Tier 1 review decks; ~12 clients |
| Karl Zaharopoulos | Senior SEO Manager & Link-building Lead | Laura | Coordinates organic delivery; wrote the Claude SEO-strategy prompt guide |
| Everhardt Strauss | Senior Technical SEO Manager | Karl | Not interviewed |
| JC Aranzado | Senior SEO Analyst | Everhardt | Not interviewed |
| Khaselyn Ibanez | SEO Analyst | Everhardt | Not interviewed |
| Sid (Siddharth) Bali | Technical SEO Specialist | Karl | Set up the Monday.com + Make system |
| Tonie Guevarra | Outreach Specialist (link building) | Sid | Runs link-building sheets and the outreacher network |
| Jasfer Guevarra | Outreach Specialist | Tonie | Also appears as an outreacher in order sheets |
| Zach (Zachary) Chamberlain | SEO Manager | Sid (per chart) | Up to 20 accounts |
| Henry Wong | Technical SEO Director | Karl | Greyed on chart – likely contractor *(inferred)*; manages link orders |
| Sarah Julian | Content Manager | Karl | Largest single writer; edits most output; owns 24 content clients |
| Hayley Tantau | Content Specialist | Sarah | Writer from May 2026; owns 17 content clients |
| Jess Kidd | SEO Copywriter | Sarah | Contractor (greyed) |
| Chloe Moss | SEO Copywriter | Sarah | Contractor (greyed) |
| Nadiya Hisham | SEO Manager | Karl | **Resigned.** Still owns templates and briefed ~34% of 2026 content |
| Spencer Potts | Technical SEO (role unclear) | ? | Not on org chart; holds latest technical audit template; core Notion maintainer. Confirm status |

### Performance (paid media)
| Name | Role | Reports to | Pacing-sheet initials *(inferred)* |
|---|---|---|---|
| Wendlley Simoes | Performance Marketing Director | Julia | WS |
| Sophie Hesseborn | Senior Performance Marketing Manager | Wendlley | – (named on Meta budgets tab) |
| Shrishti Dokwal | Senior Performance Marketing Manager | Wendlley | SD |
| Diya Manoj | Performance Marketing Manager | Wendlley | DM |
| Tanya Rastogi | Performance Marketing Manager | Wendlley | TR |
| Thomas (Tom) Davis | Performance Marketing Manager | unclear on chart | TD |
| Tatiana (Tati/Tina?) Stinson | Performance Marketing Coordinator | Shrishti | Does mid-month checks; "Tina" may also be a Slack bot – disambiguate |
| Michaela Cruz | Performance Marketing Specialist | Shrishti | MC |
| Liam Lau | Conversion Tracking Specialist | Wendlley | Contractor (greyed); sole owner of tracking setup |

### Other names that may appear
- **Isabelle Banas** – former core Notion maintainer/owner of many SOP pages; last active Jul 2026 *(likely former staff)*
- **Faraz Malik**, **JJ** – Notion editors; role unknown
- **Content contractors:** Chloe, Jess, Kayla, Aly, Ben (25–40c per word)
- **Internal outreach team** (on order sheets): Iya / Iya2, Ren, Anj, Jac, Eliannah, Jasfer
- **External outreachers** (Tonie's contacts): Damian, Dominic (Go Outreach, AUD), Juliet (USD, PayPal), Nauman (USD)
- **Tina, Franco** – Slack agent/bot workspaces (Tina sends agenda reminders – broke unnoticed)
- **Michael Laps** – introduced Austin to Aperitif
- **Ionata** – BCR's web developer (external)

### Likely mis-transcriptions
Wendlley ↔ Wendley / Wendy · Shrishti ↔ Shruti / Shristi · Diya ↔ Dia · Karl ↔ Carl · Tonie ↔ Toni / Tony · Michaela ↔ Mikayla · Everhardt ↔ Everhard · Khaselyn ↔ Kaselyn · Nadiya ↔ Nadia · Sid ↔ Syd · Hayley ↔ Haley · Monday.com ↔ "Monday" · Aperitif ↔ Apertif · Leaselab ↔ Lease Lab · BCR = Bargain Car Rentals · Higgsfield ↔ "Hicks field" · Cuttable ↔ "Kuttable"

## 3. Tool stack

| Tool | What it's for at Aperitif |
|---|---|
| Slack | Internal chat; ~16 channels, 6+ fed by bots (HubSpot agents, Zapier, Monday mirror, finance agent, Tina/Franco agents) |
| HubSpot | Sales CRM – leads, deals, live chat; posts alerts to Slack |
| Make.com | Pushes HubSpot deals into Monday.com |
| Monday.com | Task tracking for client and internal work, escalations; link building now partly here (Aperitif-only board) |
| Zapier | Slack automations / announcements |
| OpenClaw | Joe's personal AI agent setup running Slack bots |
| Xero | Accounting and invoicing |
| Otter.ai (and Gemini notes) | Meeting recording and transcripts – rarely used by the team |
| Aircall | Phone system; reportedly an AI receptionist *(unverified)* |
| Ahrefs | SEO research: keywords, rankings, backlinks, domain rating |
| Semrush / peec.ai | AI-search visibility tracking (prompts, share of AI answers) |
| SERPRobot | Rank tracking |
| AgencyAnalytics | Client reporting dashboards and monthly reports |
| Supermetrics | Pulls ad data into Google Sheets – **lapsed; Meta pacing sheet broken** |
| Google Workspace (Sheets, Docs, Slides, Drive) | Pacing sheets, master SEO docs, briefs, proposals, QBR decks – files owned by individual staff accounts |
| Notion (Company Home wiki) | SOPs, hubs, guides; 217 pages, 43% not edited in a year |
| Claude / ChatGPT | Used individually: ad copy, keyword research, SEO strategy prompts, Meta pacing workaround |
| Canva | Creative; Tatiana trialling AI creative tools |
| Figma | Austin's live process mapping in interviews |
| PayPal | Paying outreachers per link |

## 4. Clients

### SEO / link-building clients by tier (order book Clients tab, Nov 2026)
- **Tier 1:** Bargain Car Rentals (BCR), Five Good Friends, Leaselab, ANTON Jewellery, ITSM Hub, FoX Dental Implant Centres, The Timber Yard, DDEG, Elipso Louvres
- **Tier 2:** Etheridge Ford, SimRigs, Razorback 4x4, Premier Contact Point (PCP), Vintari, BuildPass, MUJI, EQ Saddlery, Savwinch, Lotus Caravans, Your Local Tradesman, Skills Certified, Commuserv, Tynte, Moda Dental, Marchese Partners (+ Sydney), Burning House, A Little Lacey, Slidetrack, Anny's Jewellery, Aperitif (own site)
- **Tier 3:** CEVA Car Carrying, Orthodontics at Parramatta, Southland Isuzu, Adriatic, Hamilton Murphy, Overnewton, The Faith Agency, Altuva, Cannalink, Bayside Skoda, Stone & Tile Studio, Britex, Alzburg, Hamilton Island Apartments, The Lodge Motel, The Hair & The Honey, Eva, Off Track RV, Sidekicker, Mazzucchellis, Capycool
- **Tier 4:** Advance Therapy, HSE Australia, Chery Southland, Drift West, Kyneton Olive Oil, Urban Angles, Trade My Car, Akira Finance, Krav Maga Australia

Other content/SEO clients seen: Superloop & Exetel (Tier 1 content), HM Advisory, Archa, Lumiere, Lumitter, Equine Eye, Peter Jackson, GoodHuman, Zetta Florence, Jardan.

### Largest paid media clients (Google Ads monthly budget, Nov 2026)
| Client | Google Ads budget | Manager (initials) |
|---|---|---|
| Five Good Friends | $168,000 | SD |
| Leaselab | $141,061 | DM |
| Bargain Car Rentals | $124,800 | SD |
| FoX Implant Centres | $60,500 | SD |
| Northern Inland Credit Union | $28,000 | MC |
| White & Co Living (+ NZ $7,500) | $27,500 | – / DM |
| easyAML | $18,200 | DM |
| My Dental Team | $14,830 | SD |
| Timber Yard | $13,476 | – |
| AMIGA Montessori | $10,000 | DM |

Large Meta budgets: White & Co ~$70K, FoX ~$55K, Leaselab ~$52K, Dental Implant Super Centres ~$32K, MUJI ~$25.5K, Five Good Friends ~$23K, NICU ~$20K, Vacuum Spares ~$20K, BCR ~$15K.

Paid client verticals cluster in **dental/orthodontics** (10+ practices), **automotive/caravans**, **finance**, **education/childcare**.

## 5. Canonical process list

Sales – lead to proposal · Sales – proposal to signed · Sales to delivery handover · Client onboarding – access & setup · Client onboarding – audit & strategy · Conversion tracking setup · Monthly SEO delivery · Technical SEO audit & fixes · Content briefing · Content writing & editing · Client content approval · Link building – sourcing & ordering · Link building – QA & live checks · Link building – outreacher invoicing · Paid media – campaign build · Paid media – pacing & budget management · Paid media – optimisation · Performance monitoring & alerting · Monthly reporting · Quarterly / 6-month review · Client meetings & prep · Client escalation · Creative production · Website migration · Internal task management · Knowledge & SOPs · Hiring & onboarding staff · Finance & billing

### Known process shapes (from evidence – use to spot gaps or contradictions)
- **SEO onboarding:** strategist sets up Master SEO Document → technical SEO runs 81-item Technical SEO Audit → strategist summarises in SEO Strategy & Roadmap deck (month 1). Karl's Claude prompt guide does the strategy in ~75–90 min.
- **Monthly SEO:** master sheet (content plan, link plan, project plan) → SEO manager writes brief → brief added to Internal Content Tracker → writer → client approval → publish. Links ordered via order book / Monday.
- **Paid media onboarding:** discovery call → account audit (30-item Google Ads checklist; longest step) → strategy & client presentation → conversion tracking (3–4 days, one contractor) → campaign build (3–5 days) → launch. Gaining client account access is the main friction.
- **Paid media monthly:** end-of-month budget recommendations → client approval → day 1 budgets updated in three places (budget sheet, pacing sheet, platforms) → pacing checked Mon/Wed/Fri → mid-month manual performance check → monthly report (AgencyAnalytics) → optimisations briefed via Monday → QA by senior manager.
- **Reviews:** QBR (Tier 1, quarterly) and 6-month review decks built by hand from one master template.
- **Link building:** client tier sets link volume → SEO manager orders → outreacher sources site and places link → live check (stopped after Apr 2026) → outreacher invoiced (PayPal, USD/AUD).

## 6. Existing problems (26) – match to these where possible

**Critical**
1. Budgets maintained by hand in three places; LinkedIn not tracked → $10K overspend
2. Meta pacing sheet is broken – Supermetrics connector failing
3. Paid links disappear after payment – detected manually (32% fault rate Jan–Apr; checking stopped after April)

**High**
4. Link building runs on 7+ disconnected spreadsheets
5. Content delivery hinges on the Content Manager as writer, editor and contractor manager
6. Managers at capacity – Tier 2/3 clients get dropped first
7. Client work files are owned by individual staff accounts, including staff who have left
8. Documentation and internal tooling held by the founder
9. Client knowledge lives in people's heads, not per client
10. Onboarding stalls on client access and disrupts BAU
11. Content stalls at client approval – or the tracker can't show what's finished
12. Client documents are built by duplicating previous ones – errors reach clients
13. No proactive performance alerting – problems found at month-end
14. Documentation is stale and rarely read
15. Client-call prep takes longer than the call
16. Sales commits to work delivery can't profitably do
17. Pricing is inconsistent across templates and the margin maths is wrong

**Medium / Low**
18. No single home for current templates – versions held by individuals
19. Conversion tracking depends on one contractor
20. Outreacher invoicing tracked as PayPal links in spreadsheet cells
21. Slack bots and agents have no visible owner or documentation
22. Proposals are rebuilt from scratch per prospect
23. Escalations route around department leads to the Head of Client Services
24. Seasonal and trending content is planned too late to catch the peak
25. Reminders go unacted; a broken reminder bot went unnoticed
26. Content tracker and link sheets live outside Monday.com

### Existing solution ideas (for reference – don't assume they're right)
AI business brain · pacing tracker & adjustment engine · proactive PPC anomaly monitor · client-call prep summaries · QBR / review deck generator · brief & proposal generator · 1-click audit (read-only access + AI audit) · link-building CRM with live-link monitoring and invoice follow-up · client approval portal · team wiki / L&D · seasonal & trending content radar · transcripts → per-client action runsheet · unlinked brand-mention outreach · AI-assisted creative · sales wiki / spend calculator · churn-risk alerts

## 7. Known facts (flag contradictions against these)

- Paid media: 61 Google Ads clients, ~$788K combined monthly Google Ads budget (Nov 2026); 41 Meta budget lines (~$422K)
- Account managers carry 12–20 accounts (Laura 12; Shrishti 14 clients / 24 channels; Zach up to 20)
- Pre-call prep ~1h15 for a 30–45 min client call (Shrishti)
- Pacing adjustments ~15–20 min per account (Shrishti)
- Onboarding ~1 week minimum once access is received; tracking 3–4 days; build 3–5 days
- Content: ~93k words/month, ~47 requests/month (Jan–Oct 2026); contractors 48%, Content Manager 37%, Content Specialist 15%; contractors ~$14k/month
- Link building: ~2,800 orders Jan–Oct 2026 (~300/month); ~$80–130 per link typical; priced to clients at $250–500
- SEO price calculator: technical $150/hr, SEO manager $150/hr, content $0.50/word, links $250 / $500, +30% markup
- SEO career ladder: SEO Manager $40–50k MRR; Senior SEO Manager $50–60k MRR; retention targets 98% (portfolio) / 95% (team)
- Notion wiki: 217 pages, 43% not edited in over a year; Joe last editor on 39%
- Recent incident: $10K LinkedIn overspend (no LinkedIn pacing, wrong budget figure)

## 8. Glossary

| Term | Meaning |
|---|---|
| Tier 1 / 2 / 3 / 4 | Client size/priority bands. Tier 1 = largest; get weekly check-ins and QBRs |
| Pacing | Checking ad spend to date against the monthly budget so a client doesn't over- or underspend |
| QBR | Quarterly business review deck presented to Tier 1 clients |
| 6-month review | Performance & strategy review deck for other clients |
| WIP | Work-in-progress meeting where accounts are discussed verbally |
| BAU | Business as usual – ongoing monthly work, as opposed to onboarding or projects |
| SEO | Search engine optimisation – getting clients found on Google |
| GEO / AEO / AI visibility | Getting clients cited in AI answers (ChatGPT, Google AI Overviews) |
| Link building / backlinks | Paying other websites to link to a client's site to lift rankings |
| Outreacher | Person who finds and negotiates link placements on publisher sites |
| Publisher | Website that hosts a paid link |
| DR | Domain Rating (Ahrefs) – a 0–100 authority score for a website |
| Anchor text | The clickable words of a link |
| Content brief | Instructions for a writer: page, keywords, structure, links |
| Master SEO Document | Per-client spreadsheet: keyword mapping, content plan, link plan, project plan |
| Technical audit | Checklist review of a site's technical SEO health |
| SQR | Search query report – reviewing which searches triggered ads |
| CPL / CPA | Cost per lead / cost per acquisition |
| ROAS | Return on ad spend |
| PMax | Google Performance Max campaign type |
| MRR | Monthly recurring revenue managed by a person |
| Pipeline deck | Templated automotive/finance proposal ("Automotive_Pipeline_Auto_[Master]") |
| Labsolutely | A Leaselab sub-brand with its own campaigns |

## 9. Hourly rate (for $ costing)

**Internal labour cost: $80/hr (AUD) for all staff time.** This is what an hour of staff time costs Aperitif, not what clients are charged. Monthly cost = monthly hours × $80. Never use the $150 client-facing rate for costing.

| Other rates (for reference) | Rate | Source |
|---|---|---|
| Contractor writer | ~$0.25–0.40 per word | Content tracker |
| Outreacher | ~$60–250 per link | Outreacher sheets |
| Client-facing SEO rate (what clients are charged, not cost) | $150/hr | SEO price calculator |
