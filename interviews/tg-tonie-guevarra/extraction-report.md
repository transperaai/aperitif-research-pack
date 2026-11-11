# Part A – Transcript extraction: Tonie Guevarra (Outreach Specialist, link building)

**Source and method notes**
- Transcript: meeting notes "Tonie - Workflow & Process Interview", 4 Nov 2026, 3:15 pm (Melbourne). Full transcript retrieved (483 utterances, ends at sign-off) – not truncated. The AI summary was not used as a source.
- **Timestamps:** the transcript has no timestamps. Every timestamp below is written `~mm:ss (L###)`: L### is the utterance number in `transcript.md`; ~mm:ss is estimated from cumulative word position across ~45 minutes (calendar slot 15:15–16:00; the transcript runs from greeting to "Bye-bye"). Actual call length not stated – 45 min is the booked slot.
- **Speakers:** the diariser labelled Austin as B and split Tonie across labels A and C. All non-Austin lines are treated as Tonie. L010 ("So I think if you made the Questions?", label C) may be Austin – no bearing on findings.
- **Name and term corrections (transcription):** "Carl" → Karl (Zaharopoulos, Senior SEO Manager & Link-building Lead) · "Cloud / Lord" → Claude · "HMix" (L115) → Ahrefs · "parking car rentals" → Bargain Car Rentals (BCR) – inferred: the other two "dynamic clients" are Tier 1 clients and BCR is the third Tier 1 car-rental client; confirm · "lease lab / Please Love" → Leaselab · "Tony" → Tonie · "scale" (L232) → skill · "deletes" (L178) → leads · "the main names" (L064) → domain names · "loves / logs" (L284, L286) → blogs · "Monday" → Monday.com · "Apertif" → Aperitif. Unresolved: "Loree" (L413 – probably someone off-call), "nieces" (L339 – niches or issues), "the main.com" (L266), "dynamic clients" (Tonie's term; meaning not explained).
- **Terminology:** Tonie calls the outreachers who place links "publishers" (internal team = her in-house trainees in the Philippines; external = brokers/outreachers). "Leads" = candidate publisher domains. "Tier 1/2/3 leads" are a **content-niche classification of publisher sites**, not client tiers – the two uses collide because the three "dynamic clients" are also Tier 1 clients.
- Hours are costed at **$80/hr internal labour cost**. Process totals include Karl's approval time where he does a step; the interviewee-only share is shown separately. Almost no times were stated in this interview – most per-step times are **assumed** and need checking.

---

## 0. Interview card

| Field | Detail |
|---|---|
| Interviewee | Tonie Guevarra |
| Role | Outreach Specialist (link building) |
| Team | Organic (link building) |
| Date / length | 4 Nov 2026 · ~45 min (booked slot; actual length not stated) |
| Interviewer | Austin Smith (Transpera AI) |
| Clients managed | All link-building clients ("For all the clients, now we're doing 300 plus", L084); count not stated – ~60 on the order book per context pack |
| Channels / services | Link building: lead sourcing and qualification, client allocation, ordering from internal and external publishers, published-link checks, master sheet and Monday.com updates; training in-house publishers |
| Reports to | Sid Bali, Technical SEO Specialist (context pack). In the transcript all lead approvals go to Karl Zaharopoulos (Senior SEO Manager & Link-building Lead); Sid is not mentioned |
| Hands work to | Karl (leads for approval); internal publishers (orders via shared sheet); external publishers/brokers (orders pasted into their own sheets); account managers/"handlers" (published-link data via master sheet and Monday.com) |
| Receives work from | Karl (approve/decline decisions; the lead-review Claude skill); internal and external publishers (blog lists, completed links, replacement requests); inbound brokers (lead lists) |

## 1. Five-line summary

1. **Lead QA is the bottleneck, and the AI checker can't yet be trusted.** About 1,000 leads run through Tonie's Claude skill gave 32 approvals; in the previous batch 54 passed her check and Karl approved 27 "using the same skill". She asked for help making it "more accurate" because it is "rejecting a lot of leads".
2. **Link building runs at 300–340 links a month on a chain of spreadsheets.** Orders are copy-pasted into each external publisher's sheet, completed links are re-keyed into the master sheet, and Tonie wants publisher entries to flow through to the other sheets automatically.
3. **Matching approved domains to clients is manual and "one of the time-consuming tasks"**, and the three "dynamic clients" (BCR, Five Good Friends, Leaselab) need scarce, costly Tier 1 (single-niche) sites – Austin suggested this may be a pricing question.
4. **Tonie is building her own AI tooling.** With Claude she has built a lead-review skill, an Apps Script duplicate-domain checker, a live/issue link-status extension and a master-sheet → Monday.com sync. They are undocumented, unreviewed and she isn't sure they work ("not really sure if these are really working well"); managers have raised concerns about the Monday.com entries.
5. **Supply depends on inbound brokers and a home-grown publisher network.** Self-sourcing via Google search operators, AI Mode and Claude "gives limited results"; brokers who contact her and in-house publishers she is training in the Philippines fill the gap.

## 1a. Time allocation

| Activity | % / hours | Billable? | Quote + timestamp | Certainty |
|---|---|---|---|---|
| Daily routine: check published links, replace leads, send orders, check new leads, allocate approved leads to clients | Whole working day – no % given | Billable (client link delivery; assumed) | "Yeah, so every day that's what I do." ~06:22 (L036) | stated (no number) |
| Lead sourcing and qualification (TG-P01) | ~12–35% of a ~160 h month (18.7–55.5 h) | Billable (assumed) | "So I can check them and then after I check them, I will ask Carl [Karl] for the approval." ~05:15 (L034) | estimated from process hours |
| Client allocation and order dispatch (TG-P02) | ~10–37% (16.3–59.5 h) | Billable (assumed) | "once Carl [Karl] approved them, I will... take time to add them to the different clients." ~05:15–06:16 (L034–L035) | estimated from process hours |
| Published-link checks and master-sheet encoding (TG-P03) | ~7–22% (10.8–35.7 h) | Billable (assumed) | "as I start I begin with checking the published links." ~02:56 (L026) | estimated from process hours |
| Monday.com sync and tool building (TG-P04 and self-built tools) | ~1–3% for the sync (1.5–5.0 h); tool-building time not discussed | Non-billable (internal) | "Somehow I'm learning to to do the admin task. using AI." ~42:15 (L446–L447) | estimated / not discussed |
| Training in-house publishers | Not quantified | Non-billable | "giving them the opportunity to learn this work and training them" ~19:36 (L193) | stated (no number) |

- **Busy vs quiet:** not discussed. Monday.com sync appears to run monthly (October done, November in progress, L437–L439).
- **Billable vs non-billable:** not discussed. Assumed ~95% client-attributable (link delivery), ~5% internal (tool building, Monday.com sync, training). She ran a lead-QA batch "last night" (L134, L149) – possible out-of-hours work (see 12). Confirm with timesheets.

## 2. Processes

Flags: ⏸ bottleneck · 👤 single-person dependent · ⌨️ manual copy / re-keying · ⚠️ error-prone. Interviewee = TG. Approver = Karl (Senior SEO Manager & Link-building Lead).

### TG-P01 · Link building – sourcing & ordering (lead sourcing and qualification)
- **Trigger:** continuous – client link plans need sites; publishers send blog lists; brokers make contact; periodic QA batches of ~1,000 leads.
- **Owner role:** Outreach Specialist (TG); Karl approves or declines.
- **Frequency:** daily sourcing; QA batches of "almost a thousand" leads – batch frequency not stated (assumed 1–2 a month).
- **Tools / files:** Google search operators, Google AI Mode, Claude (own lead-review skill/project plus a skill from Karl), Ahrefs (DR, traffic, keywords), internal publishers' blog list, external publishers' sheets (blog lists), "Approved leads" and "Do not use" reference lists, publishers list with prices.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Self-source candidate domains: search operators ("list of technology blogs"), AI Mode, Claude prompts; check domains "one by one" ⌨️ | TG | Google, AI Mode, Claude | 30–60 a day × 20–22 days (600–1,320) | – | – | stated (step) / assumed (time) |
| 2 | Collect leads from publishers' blog lists and inbound brokers | TG | Publisher sheets, email | 10–20 a day × 20–22 days (200–440) | – | – | stated (step) / assumed (time) |
| 3 | Check metrics (DR 30+, traffic 1,000+, US/AU/CA/NZ, keywords 50+) and run the batch through the Claude lead-review skill, which also returns publisher names and prices ⚠️ | TG + Claude | Ahrefs, Claude skill, publishers list | 180–360 per ~1,000-lead batch × 1–2 (180–720) | – | – | stated (criteria, batch size) / assumed (time, batches) |
| 4 | Manual content check of skill-passed leads (gambling, casino, betting, adult, inappropriate or unreadable domain names); classify Tier 1/2/3 by niche spread | TG | Browser, sheet | 2–4 per lead × 32–54 leads × 1–2 batches (64–432) | – | Karl | stated (step, 32 and 54 passed) / assumed (time) |
| 5 | Approve or decline each lead ⏸👤 | Karl | Sheet; same Claude skill | 2–5 per lead × 32–54 × 1–2 (64–540) | Karl's turnaround – not stated ⏸ | TG | stated (step) / assumed (time) |
| 6 | Record approved and rejected leads in "Approved leads" / "Do not use" lists so the skill can check against them | TG | Sheets, Claude project | 15–30 per batch × 1–2 (15–60) | – | TG-P02 | stated (step) / assumed (time) |

- **Happy path total:** touch 1,123–3,512 min (18.7–58.5 h) a month; elapsed: lead found → approved not stated (depends on Karl); "negotiations" with a publisher then take "a week or two" (L109–L111).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Karl declines about half of skill-approved leads ⚠️ | Skill and Karl disagree "using the same skill" | 1 batch stated: 27 of 54 approved (50%) | Source and check replacements | 60–180 min per batch × 1–2 (60–360) | TG, Karl | stated (27 of 54) / assumed (time, batches) |
| Skill over-rejects valid leads ⚠️ | Skill too strict / inaccurate | Latest batch: 32 approved of ~1,000 (3%) | None – good sites lost from supply | Supply, not time – not costed | TG, dynamic clients | stated (32 of ~1,000) / detected (lost supply) |
| Self-sourcing runs dry | Finite qualifying sites per niche; AI search "gives limited results" | Ongoing | Rely on inbound brokers | not quantified | TG | stated |
| Tier 1 leads needed for dynamic clients | BCR, Five Good Friends, Leaselab need single-niche sites | Ongoing ("we hardly find leads") | Extra searching; higher price | not quantified; cost "really high" | TG, client margin | stated |

- **Decision points:** after step 3 – skill passes vs rejects (latest batch ~3% pass, 32 of ~1,000 – stated); after step 4 – content OK vs excluded (split not given); after step 5 – Karl approves vs declines (previous batch 50/50, 27 of 54 – stated, one batch); tier classification Tier 1 / 2 / 3 (split not given).
- **Volume (team):** Tonie is the only person described doing this; ~1,000 leads per batch (stated).
- **Monthly hours:** happy path 1,123–3,512 min + bad path 60–360 min = 1,183–3,872 min = **19.7–64.5 h** (TG share 18.7–55.5 h; Karl 1.1–9.0 h) – assumed.
- **Monthly cost:** 19.7 × $80 = **$1,576** to 64.5 × $80 = **$5,160**.

### TG-P02 · Link building – sourcing & ordering (client allocation and order dispatch)
- **Trigger:** Karl approves leads; client link plans need filling (300–340 links a month).
- **Owner role:** TG.
- **Frequency:** daily; per link – 300–340 links a month across all clients (stated).
- **Tools / files:** approved-leads sheet, separate dynamic-clients leads sheet, publishers' order sheet (internal publishers), each external publisher's own sheet, Apps Script duplicate-domain checker (built by TG with Claude).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Decide which client(s) each approved domain suits (incl. dynamic clients on a separate sheet) 👤⚠️ | TG | Approved-leads sheet, dynamic-clients sheet | 2–5 per link × 300–340 (600–1,700) | – | – | stated ("time-consuming") / assumed (time) |
| 2 | Duplicate check: Apps Script marks domain used/unused for that client on entry | Apps Script | Order sheet | 0 (automatic) | – | – | stated |
| 3 | Send order: internal publishers – insert into the shared order sheet; external publishers – copy and paste the order into each publisher's own sheet ⌨️⚠️ | TG | Order sheets | 1–4 per order × 300–340 (300–1,360) | – | Publisher | stated (step) / assumed (time) |
| 4 | Publisher negotiates / accepts and writes the article | Publisher | Publisher's site | – | "A week or two" (negotiation); publishing "right away" to 1–3 weeks ⏸ | TG-P03 | stated |

- **Happy path total:** touch 900–3,060 min (15.0–51.0 h) a month; elapsed per link: 0–3 weeks after the order ("Some links can be published right away… it takes one, two, three weeks", L099–L101).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Publisher asks for a replacement lead | Publisher can't place on that domain | "sometimes" – assumed 5–15% of orders (15–51) | Re-check leads, pick and re-send a replacement | 5–10 min each (75–510) | TG, publisher | stated (event) / assumed (rate, time) |
| Order number changes on an external sheet ⚠️ | Copy-paste / external sheet edits | "sometimes" | Reconcile order numbers | not quantified | TG | stated ("sometimes it changes the number", L387) |
| Duplicate domain for the same client | Domain reused for a client | Was a real problem before the Apps Script; accuracy still uncertain | Cancel / replace | not quantified | TG, client | stated |

- **Decision points:** step 1 – which client gets which domain (no rule described; Tonie's judgement); step 2 – used vs unused (automatic); step 3 – internal vs external publisher (split not given).
- **Volume (team):** 300–340 links a month (stated); ~300 a month on the order book (context pack) – consistent.
- **Monthly hours:** happy path 900–3,060 min + bad path 75–510 min = 975–3,570 min = **16.3–59.5 h** – assumed.
- **Monthly cost:** 16.3 × $80 = **$1,304** to 59.5 × $80 = **$4,760**.

### TG-P03 · Link building – QA & live checks (published-link checks and master-sheet encoding)
- **Trigger:** daily – publishers enter completed links in their sheets.
- **Owner role:** TG.
- **Frequency:** daily; 300–340 published links a month.
- **Tools / files:** internal publishers' sheet, external publishers' sheets, link-status checker (Google Sheets extension built by TG with Claude), Master Sheet (visible to Aperitif only).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Check internal and external publisher sheets for newly published links | TG | Publisher sheets | 10–20 a day × 20–22 days (200–440) | – | – | stated (step) / assumed (time) |
| 2 | Link-status extension marks each completed link live or "has issues" | Extension | Order sheet | 0 (automatic) | – | TG | stated |
| 3 | Re-key each published link into the master sheet ("and other sheets") ⌨️ | TG | Master Sheet | 1–3 per link × 300–340 (300–1,020) | – | Account managers; TG-P04 | stated (step) / assumed (time) |

- **Happy path total:** touch 500–1,460 min (8.3–24.3 h) a month; elapsed: same day as the publisher's entry (assumed).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Link flagged with issues ⚠️ | Wrong anchor/URL, not live | assumed 5–10% (15–34 links) | Chase publisher; re-check | 10–20 min each (150–680) | TG, publisher | stated (flag exists) / assumed (rate, time) |
| Extension result unreliable | Accuracy uncertain | unknown | Manual re-check | not quantified | TG | stated ("if you could see other easier or more accurate way", L352) |

- **Decision points:** after step 2 – live vs issue (rate not given; context pack: 32% hard-fault rate on later checks Jan–Apr).
- **Volume (team):** 300–340 links a month (stated).
- **Monthly hours:** happy path 500–1,460 min + bad path 150–680 min = 650–2,140 min = **10.8–35.7 h** – assumed.
- **Monthly cost:** 10.8 × $80 = **$864** to 35.7 × $80 = **$2,856**.

### TG-P04 · Internal task management (master sheet → Monday.com sync of published links)
- **Trigger:** monthly – published links in the master sheet need to appear on the Monday.com board (October done; November in progress).
- **Owner role:** TG (built and runs it).
- **Frequency:** monthly (inferred from "this is November… for the October, it added already", L437–L439).
- **Tools / files:** Master Sheet, Claude-built automation, Monday.com.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Run the Claude-built automation to push published-link details from the master sheet into Monday.com 👤⚠️ | TG + Claude | Master Sheet, Monday.com | 30–60 | – | Account managers ("handlers") | stated (step) / assumed (time) |
| 2 | Check the entries landed correctly | TG | Monday.com | 30–60 | – | – | assumed |

- **Happy path total:** touch 60–120 min a month.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Managers raise concerns about the Monday.com entries ⚠️ | Sync not "working really well" | October run – "a few concerns" (assumed 1–3 a month) | Investigate and correct entries | 30–60 min each (30–180) | TG, account managers | stated (concerns) / assumed (time) |

- **Decision points:** none described.
- **Monthly hours:** happy path 60–120 min + bad path 30–180 min = 90–300 min = **1.5–5.0 h** – assumed.
- **Monthly cost:** 1.5 × $80 = **$120** to 5.0 × $80 = **$400**.

### TG-P05 · Link building – outreacher invoicing (publisher payment)
- **Trigger:** publisher invoices for a placed link.
- **Owner role:** Karl receives and pays the invoice (Austin's description, L239–L246 – not contradicted).
- **Frequency:** per link (300–340 a month).
- **Tools / files:** not discussed (context pack: PayPal links in sheet cells).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Publisher quotes a price ("$100 or $150", Austin's example) | Publisher | – | – | – | Karl | interviewer (example) |
| 2 | Karl receives the invoice and pays | Karl | not stated | not discussed | – | Publisher | interviewer – not contradicted |
| 3 | Publisher publishes – sometimes before payment | Publisher | – | – | – | TG-P03 | stated (L248) |

- **Happy path total:** not discussed.
- **Bad paths:** not discussed. Tonie's "It is me" (L251) after Austin's comment about scams is unclear – she may handle some payments.
- **Decision points:** pay before vs after publishing (both happen; split not given).
- **Monthly hours:** **not costed – not discussed** (0–0 h in totals).
- **Monthly cost:** **$0** (not costed).

### Process totals

| ID | Process | Monthly hours (all actors) | TG-only hours | Monthly cost (all actors) |
|---|---|---|---|---|
| TG-P01 | Link building – sourcing & ordering (lead sourcing and qualification) | 19.7–64.5 | 18.7–55.5 | $1,576–$5,160 |
| TG-P02 | Link building – sourcing & ordering (client allocation and order dispatch) | 16.3–59.5 | 16.3–59.5 | $1,304–$4,760 |
| TG-P03 | Link building – QA & live checks | 10.8–35.7 | 10.8–35.7 | $864–$2,856 |
| TG-P04 | Internal task management (Monday.com sync) | 1.5–5.0 | 1.5–5.0 | $120–$400 |
| TG-P05 | Link building – outreacher invoicing | not costed | – | – |
| **Total** | | **48.3–164.7 h** | **47.3–155.7 h** | **$3,864–$13,176** |

TG's high end (~156 h) is about one full-time month (~152–160 h), which fits "every day that's what I do" (L036); the low end (~47 h) would leave most of her month unexplained. The true figure is probably in the upper half. Confirm per-link and per-batch times with Tonie.

## 3. Pain points and problems

| ID | Pain point (one line) | Source | Category | Anchor | Process | Impact | How often | Severity 1–5 | Quote + timestamp | Certainty |
|---|---|---|---|---|---|---|---|---|---|---|
| TG-PP01 | The Claude lead-review skill rejects most leads (32 approved of ~1,000) and Tonie doesn't know if it's accurate | interviewee | Rework / errors | Technology, AI & stack | Link building – sourcing & ordering | Lost lead supply; manual double-checking | Every QA batch | 4 | "I'm not pretty sure if this is already accurate. So, really need your help with this." ~17:49–18:01 (L170–L171); "it's been rejecting a lot of leads." ~31:24 (L322) | stated |
| TG-PP02 | Same skill, different answers: 54 leads passed Tonie's check, Karl approved 27 | interviewee | Rework / errors | Technology, AI & stack | Link building – sourcing & ordering | Wasted QA and approval time; replacement sourcing | Last batch (one stated) | 4 | "I think 57 only were, 54 were approved on my part. But then when it comes to Carl [Karl]." ~22:19 (L224); "He only approved 27." ~22:51 (L227) | stated |
| TG-PP03 | Tier 1 (single-niche) sites for the dynamic clients (BCR, Five Good Friends, Leaselab) are hard to find and expensive | interviewee (pricing angle raised by interviewer) | Revenue / margin leak | Performance visibility & margin | Link building – sourcing & ordering | Margin on three of the largest clients; delivery risk | Ongoing | 4 | "the struggle is that we hardly find leads for the dynamic clients." ~11:14 (L090); "and it costs really high." ~11:36 (L094) | stated |
| TG-PP04 | Working out which approved domains suit which clients is manual and time-consuming | interviewee | Manual / repetitive work | Operations capacity & process | Link building – sourcing & ordering | 10–28 h/month (assumed, TG-P02 step 1) | Every approved lead | 3 | "Yes, because it is also one of the time-consuming tasks." ~35:46 (L369) | stated (time-consuming) / assumed (hours) |
| TG-PP05 | Orders to external publishers are copy-pasted into each publisher's own sheet, and order numbers sometimes change | interviewee | Duplicate data entry | Operations capacity & process | Link building – sourcing & ordering | 5–23 h/month (assumed); reconciliation errors | Every external order | 3 | "for the other publishers, since we have different sheets for them, so I copy and paste documents on the sheets" ~04:25 (L031); "sometimes it changes the number." ~37:16 (L387) | stated |
| TG-PP06 | Every published link is re-keyed from publisher sheets into the master sheet (and other sheets) | interviewee | Duplicate data entry | Operations capacity & process | Link building – QA & live checks | 5–17 h/month (assumed) | 300–340 links/month | 3 | "And then every published links I've found here. I encode it to the master sheet." ~39:07–39:13 (L404–L405) | stated |
| TG-PP07 | The home-built master sheet → Monday.com sync isn't reliable; managers raised concerns about October's entries | interviewee | Rework / errors | Technology, AI & stack | Internal task management | Account managers see wrong/missing link data; fix-up time | Monthly | 3 | "for the October, it added already, but I received a few concerns from the managers, from the handlers." ~41:14 (L439) | stated |
| TG-PP08 | Self-sourcing new qualifying sites is limited; AI search returns few results, so supply leans on inbound brokers | interviewee (interviewer raised the finite-supply question) | Capacity / overload | Growth & sales engine | Link building – sourcing & ordering | Caps link volume; dependence on brokers | Daily | 3 | "we can find leads, but... limited per day." ~14:45–14:49 (L118–L119); "But this gives limited results." ~27:40 (L279) | stated |
| TG-PP09 | Four home-built tools (lead skill, Apps Script duplicate checker, link-status extension, Monday.com sync) are undocumented, unreviewed and run by one person | detected | Single point of failure (person) | Technology, AI & stack | Link building – QA & live checks | Errors go unnoticed; tools stop if she's away | Daily | 3 | "but if there is really simpler way, and more accurate because yeah, I'm not really sure if these are really working well." ~42:29 (L452) | detected |
| TG-PP10 | Duplicate domains for the same client were a real problem; the Apps Script fix's accuracy is still uncertain | interviewee | Rework / errors | Client experience & delivery | Link building – sourcing & ordering | Wasted link spend; client value | Not quantified | 2 | "previously we really have trouble in having duplicated domains for the same client." ~32:04 (L330) | stated |
| TG-PP11 | Link-status checker accuracy uncertain; she'd like an easier or more accurate check | interviewee | Rework / errors | Client experience & delivery | Link building – QA & live checks | Faulty links missed | Every published link | 2 | "if you could see other easier or more accurate way to checking it, really helpful." ~33:55 (L352) | stated |
| TG-PP12 | Publisher turnaround: negotiation "a week or two"; some links take 1–3 weeks to publish | interviewee | Waiting / handoff delay | Client experience & delivery | Link building – sourcing & ordering | Links land late in the month | Some publishers | 2 | "While some, it takes one, two, three weeks. It depends on the publisher." ~12:50 (L101) | stated |

**Problem-list matches:** TG-PP05, TG-PP06 → "Link building runs on 7+ disconnected spreadsheets". TG-PP07 → "Content tracker and link sheets live outside Monday.com". TG-PP09 → "Slack bots and agents have no visible owner or documentation" (same root cause: automations added without an owner register – partial match, these aren't Slack bots). TG-PP11 → "Paid links disappear after payment – detected manually" (partial: her checker covers publication, not later removal). TG-PP03 → "Pricing is inconsistent across templates and the margin maths is wrong" (partial: link pricing vs Tier 1 lead cost). New: TG-PP01, TG-PP02, TG-PP04, TG-PP08, TG-PP10, TG-PP12.

**Top 3 by severity – root cause and match**

1. **TG-PP01 / TG-PP02 Lead-review skill over-rejects and disagrees with Karl (4).** Why are so few leads approved? The skill rejects most of a 1,000-lead batch, and half of what it passes is then declined. Why? The approval criteria live in two separate prompts (Tonie's and Karl's) and in Karl's judgement, and the skill has never been tested against his actual decisions. Why? Tonie built it herself with no review step or shared test set. **Root cause:** no single, versioned definition of an acceptable lead, and no calibration of the AI check against the approver's real decisions. **Matches:** new (closest: "Link building runs on 7+ disconnected spreadsheets").
2. **TG-PP03 Tier 1 leads for dynamic clients scarce and costly (4).** Why costly? These clients need single-niche sites, which are rare and charge more. Why is that a margin problem? Link prices to clients are set per link ($250/$500 per context pack), not by lead tier, so higher costs aren't passed on. **Root cause:** link pricing doesn't reflect the publisher-tier requirement for the largest clients. **Matches:** partial – "Pricing is inconsistent across templates and the margin maths is wrong".
3. **TG-PP04 Client–domain matching manual (3).** Why manual? There is no recorded mapping of each client's niche/relevance rules to domain categories, so Tonie judges each domain. Why? Link building grew on spreadsheets without a client-requirements table. **Root cause:** client link requirements (niche, tier, exclusions) aren't held as data. **Matches:** new (related to "Link building runs on 7+ disconnected spreadsheets").

## 4. Bottlenecks

| ID | Step | Waiting on | Typical wait | Affected | Knock-on |
|---|---|---|---|---|---|
| TG-B01 | Lead approval (TG-P01 step 5) | Karl's approve/decline decision | not stated | Every batch (32–54 leads) | Allocation and ordering wait; half of submitted leads come back declined |
| TG-B02 | Lead QA (TG-P01 step 3) | Tonie running ~1,000-lead batches through the Claude skill (done "last night") | Batch frequency not stated | All new supply | Few approved leads (32 per batch) feed 300–340 links a month |
| TG-B03 | Tier 1 supply for dynamic clients (TG-P01 / P02) | Finding single-niche sites | not stated – "we hardly find leads" | BCR, Five Good Friends, Leaselab | Delivery risk on three Tier 1 clients; higher link costs |
| TG-B04 | Publisher negotiation and publishing (TG-P02 step 4) | Publisher | "A week or two" negotiation; 0–3 weeks to publish | Some publishers | Links land late; month-end reporting gaps |
| TG-B05 | Client allocation (TG-P02 step 1) | Tonie's manual matching | not stated | All 300–340 links/month | Orders queue behind allocation |

## 4a. Decisions and approvals

| Decision | Who decides (role) | Who waits | Typical time | Lands on leadership? |
|---|---|---|---|---|
| Approve or decline each lead | Karl (Senior SEO Manager & Link-building Lead) | TG | not stated | No (Karl is a senior manager, not a director) – but a single approver for all leads |
| Lead passes metrics/content criteria (first screen) | TG with the Claude skill | Karl | per batch | No |
| Which client gets which domain | TG | Publishers, clients | not stated | No – no written rule |
| Lead tier (1/2/3 by niche spread) | TG | Allocation | – | No |
| Pay publisher (before or after publishing) | Karl receives and pays invoices (Austin's description) | Publisher | not stated | No |
| Charge dynamic clients more for Tier 1 leads | Not decided – Austin "to think about"; owner not stated (assumed leadership / sales) | – | – | Likely **yes** if it changes client pricing (assumed) |

## 5. Suggestions for change (as raised in the interview)

| ID | Idea | Source + reaction | Process | Quote + timestamp |
|---|---|---|---|---|
| TG-S01 | Move outreach and lead checking onto AI (her prior "vision") | interviewee | Link building – sourcing & ordering | "a few months before, I've already had this vision of transitioning the outreach into AI." ~01:17 (L015) |
| TG-S02 | Make the lead-review skill more accurate | interviewee | Link building – sourcing & ordering | "my link reviewer, it's just that I want it to be more accurate." ~30:58 (L319) |
| TG-S03 | Use AI to help keep the link spreadsheets updated | interviewer; interviewee agreed ("Yeah. Really?") | Link building – QA & live checks | Austin: "we can definitely use AI to help you with the spreadsheets to make it easier" ~07:10 (L048) |
| TG-S04 | Charge dynamic clients more given costly Tier 1 leads | interviewer; no reaction recorded | Link building – sourcing & ordering | Austin: "needs to charge the client, then maybe that's a good point to raise" ~11:45 (L096) |
| TG-S05 | AI to judge which clients an approved domain suits | interviewee | Link building – sourcing & ordering | "only the accuracy of the potential clients that we could use for the domain" ~35:24 (L366) |
| TG-S06 | Use AI on order delivery to external publishers | interviewee | Link building – sourcing & ordering | "This is how I deliver the orders to them. Yeah, so with this one, I want to use AI." ~36:57–37:03 (L381–L382) |
| TG-S07 | When a publisher encodes a completed link, update the other sheets automatically | interviewee; interviewer agreed ("Yeah, we can do that.") | Link building – QA & live checks | "Once they have encoded the link, here, could it be possible to automatically" ~38:49 (L400) |
| TG-S08 | A more reliable master sheet → Monday.com sync | interviewee; interviewer to look at it | Internal task management | "From this Master Sheet, I asked Claude to automatically and code delete [encode the] the details" ~40:13 (L421) |
| TG-S09 | An easier or more accurate live-link check | interviewee | Link building – QA & live checks | "if you could see other easier or more accurate way to checking it, really helpful." ~33:55 (L352) |
| TG-S10 | Free Tonie's time for new links and publisher communication instead of admin | interviewer; interviewee partly agreed – already using AI for admin, wants it simpler and more accurate | Link building – sourcing & ordering | Austin: "spend most of your time getting new links and communicating with them rather than having to do all this admin stuff." ~41:56 (L445) |
| TG-S11 | Duplicate-domain checker (already built with Claude/Apps Script) | interviewee (implemented) | Link building – sourcing & ordering | "I've created through the extension here, the Apps Script. I asked Lord [Claude] to help me with this." ~32:04–32:22 (L330–L331) |
| TG-S12 | Link-status checker extension (already built with Claude) | interviewee (implemented) | Link building – QA & live checks | "once we... place the completed links, it will state if the link is live or if it is has Issues." ~33:21 (L343) |

## 6. Opportunity assessment

| ID | Fixes | Lens | What changes | Matches existing solution idea | Existing tool | Hours saved / month (maths) | Effort | Prerequisites | Adoption risk | COI flag |
|---|---|---|---|---|---|---|---|---|---|---|
| TG-O01 | TG-PP01, TG-PP02, TG-B01, TG-B02 | Augment | One shared, versioned lead-review skill (replacing Tonie's and Karl's separate ones), written from Karl's actual criteria and tested on past "Approved" / "Do not use" decisions; it outputs a reason per rejection and a confidence band, and Karl spot-checks borderline leads only | new (part of link-building CRM idea) | Claude Projects/Skills with the approved / do-not-use lists as a test set; Ahrefs export | 1.1–11.1 h (Karl review 64–540 min × 30–50% + replacement sourcing 60–360 × 50% + TG manual checks 64–432 × 25–50% = 65–666 min); plus more approved supply | S | Karl's written criteria; past decisions with reasons; Ahrefs export format | L–M – Karl must trust it; Tonie already uses AI daily | Yes (Austin's action item) |
| TG-O02 | TG-PP06, TG-PP07, TG-PP09, TG-B04 | Automate | When a publisher enters a completed link, a script/Make scenario copies it to the master sheet, runs the live check and updates Monday.com; one owned, documented automation replaces re-keying and the home-built sync | link-building CRM with live-link monitoring and invoice follow-up | Apps Script or Make.com (already in stack) + Monday.com API | 5.6–24.0 h (re-keying 300–1,020 min × 70–90% + Monday sync 90–300 × 70–100% + daily sheet checks 200–440 × 30–50% = 333–1,438 min) | M | Consistent column layout across publisher sheets (O03); Monday board structure agreed with managers | M – external publishers must enter data in a fixed format | Yes |
| TG-O03 | TG-PP05, TG-PP06, TG-PP10 | Change the process | One standard order template for all publishers with fixed order IDs; external publishers get a filtered view/linked tab of a single Aperitif-owned order sheet instead of a pasted copy | link-building CRM (process step) | Google Sheets (filter views, IMPORTRANGE, protected ranges) | 1.5–11.3 h (order dispatch 300–1,360 min × 30–50% = 90–680 min) + fewer order-number errors | S | Publisher agreement; one sheet owner | M – external brokers keep their own formats today | No |
| TG-O04 | TG-PP04, TG-B05 | Augment | Client requirements table (niche, accepted lead tier, exclusions, domains already used) + Claude suggests the best client(s) for each approved domain; Tonie confirms | new | Claude + Sheets; Apps Script duplicate checker | 3.0–14.2 h (allocation 600–1,700 min × 30–50% = 180–850 min) | M | Client requirements table (Karl/SEO managers to define) | M – needs a clear client brief per link client | Yes |
| TG-O05 | TG-PP03, TG-B03 | Change the process | Price links by lead tier: charge dynamic clients a Tier 1 premium, or agree when Tier 2 sites are acceptable; check link margin for BCR, Five Good Friends, Leaselab | sales wiki / spend calculator (pricing) | SEO price calculator | 0 h – margin, not time | S | Link cost per tier (publishers list with prices); leadership decision; client conversation | M – client pushback on price | No |
| TG-O06 | TG-PP08 | Augment | Structured broker/publisher intake: one form or sheet where brokers submit domains, auto-enriched with Ahrefs metrics and run through the O01 skill before Tonie sees them | new | Google Forms/Sheets, Ahrefs API, Claude | 2.7–8.8 h (sourcing steps 1–2 800–1,760 min × 20–30% = 160–528 min) | M | Ahrefs API access; O01 calibrated first | M – brokers must use the form | Yes |
| TG-O07 | TG-PP09 | People & policy | Register and document Tonie's four tools (purpose, owner, backup, where they live), keep them in a shared drive, and name a backup (e.g. Jasfer) | new (relates to "Slack bots and agents have no visible owner") | Notion / shared Drive | 0–1 h (assumed); main gain is continuity | S | 1–2 h of Tonie's time; manager sign-off | L | No |

**KPIs**

| Opportunity ID | KPI | How measured | Baseline today | Target | Leading / lagging |
|---|---|---|---|---|---|
| TG-O01 | % of skill-approved leads that Karl approves | Approval sheet | 50% – 27 of 54 (L224–L229) | ≥ 85% | Leading |
| TG-O01 | Approved leads per 1,000 checked | QA batch log | 32 (L176–L178) | Set after calibration (expect higher) | Lagging |
| TG-O02 | Published links re-keyed by hand | Process audit / sheet edit history | All 300–340 a month (L404–L405) | 0 | Leading |
| TG-O02 | Monday.com link entries queried by managers | Slack / Monday comments | "a few concerns" in October (L439) | 0 a month | Lagging |
| TG-O03 | Separate order formats in use | Sheet inventory | One per external publisher (L031) – count unknown | 1 | Leading |
| TG-O03 | Order-number mismatches per month | Order sheet reconciliation | "sometimes" (L387) – count unknown | 0 | Lagging |
| TG-O04 | Minutes to allocate an approved domain | Time log | unknown – "time-consuming" (L369) | –50% | Leading |
| TG-O05 | Link margin on dynamic clients | Order book cost vs client price | unknown – "costs really high" (L094) | ≥ the agency's target link margin | Lagging |
| TG-O05 | Dynamic-client links delivered vs plan | Order book | unknown – "we hardly find leads" (L090) | 100% of plan | Lagging |
| TG-O06 | Broker leads arriving pre-checked | Intake sheet | 0 | ≥ 80% | Leading |
| TG-O07 | Home-built tools with documented owner and backup | Tool register | 0 of 4 | 4 of 4 | Leading |

**Indicative ranking** (priority = Impact × Confidence × Ease)

| Rank | ID | Impact | Confidence | Ease | Priority | Tag | Reason |
|---|---|---|---|---|---|---|---|
| 1 | TG-O01 | 3 | 4 | 4 | 48 | Quick win | Clearly evidenced with numbers (32 of ~1,000; 27 of 54); fix is a prompt rewrite and test set |
| 2 | TG-O03 | 3 | 3 | 4 | 36 | Quick win | No new tech; removes copy-paste and is the prerequisite for O02 |
| 3 | TG-O02 | 4 | 3 | 3 | 36 | Strategic | Largest hours pool (5.6–24 h) and fixes the Monday.com data managers complained about |
| 4 | TG-O04 | 3 | 3 | 3 | 27 | Strategic (closest – Impact 3 / Ease 3 fits no tag) | Tonie's named time sink, but no times stated |
| 5 | TG-O07 | 2 | 3 | 4 | 24 | Fill-in | Cheap continuity fix for four undocumented tools |
| 6 | TG-O05 | 4 | 2 | 3 | 24 | Strategic | Margin on three Tier 1 clients, but no prices or margins given |
| 7 | TG-O06 | 3 | 2 | 3 | 18 | Strategic (closest – Impact 3 / Ease 3 fits no tag) | Supply gain plausible, poorly evidenced; depends on O01 |

Ties are broken by Ease, then Impact. Augmentation (not full automation) is preferred for lead QA and allocation because Karl's judgement is the standard and current AI output doesn't yet match it; automation is preferred for sheet-to-sheet updates because that work is pure re-keying and the current home-built sync already needs fixing.

## 7. What's working well

| Strength | Quote + timestamp |
|---|---|
| Tonie has built her own AI tools with Claude – lead-review skill, duplicate-domain checker, link-status checker, Monday.com sync | "I've created through the extension here, the Apps Script. I asked Lord [Claude] to help me with this." ~32:04–32:22 (L330–L331) |
| Admin is easier than before thanks to AI | "So Right now, it's easier compared to before." ~42:23 (L449) |
| Clear written lead criteria (DR 30+, traffic 1,000+, four countries, keywords 50+, content exclusions, tiers) | "We have metrics to follow from the domain rating. It should be 30 plus." ~07:51 (L056) |
| Duplicate domains for the same client now flagged automatically | "When I encode the domain here, it Um, Indicates if it is used or unused." ~32:30 (L332) |
| Approved / do-not-use lists kept as a reference for the skill | "I will put the approved leads here for my reference and I will put the The rejected leads here." ~20:59 (L211) |
| Home-grown publisher network: in-house publishers being trained | "So we are training them." ~19:33 (L192) |
| Master sheet kept internal – publishers can't see it | "None of the publishers can see it, only the agency." ~39:33 (L409) |
| High engagement with the audit and AI | "I am excited about it" ~01:17 (L015); "This is really what we need." ~44:31 (L477) |
| Volume: 300–340 links a month delivered | "For all the clients, now we're doing 300 plus." ~10:58 (L084) |

## 8. Numbers and facts

| Value | Unit | Context | Quote + timestamp | Certainty |
|---|---|---|---|---|
| 300+ (max 340) | links / month | All clients | "For all the clients, now we're doing 300 plus." ~10:58 (L084); "Maximum of 340." ~11:07 (L086) | stated |
| 30+ | Domain Rating | Lead criterion | "It should be 30 plus." ~07:51 (L056) | stated |
| 1,000+ | global traffic | Lead criterion | "it should be 1,000 global traffic and above." ~07:51 (L056) | stated |
| 4 | countries | US, Australia, Canada, New Zealand | "it should be coming from the US, Australia, Canada, New Zealand." ~08:09 (L057) | stated |
| 50+ | keyword rankings | Lead criterion | "the keyword ranking, it should be 50 and above." ~08:20 (L058) | stated |
| 1 / 2–3 / 3+ | niches | Lead Tier 1 / 2 / 3 | "tier one focused only on one niche." ~09:40 (L067); "the tier two, it is focused on two to three niches." ~09:57 (L068) | stated |
| ~1,000 | leads | Latest QA batch | "Almost a thousand?" ~16:46 (L153) | stated |
| 32 | leads approved | From the latest ~1,000 | "domains Yeah, almost 1000 deletes [leads], but it only gave me 32 approved." ~18:22 (L178) | stated |
| ~1,000 → 54 → 27 | leads | Previous batch: Tonie's pass vs Karl's approval | "54 were approved on my part." ~22:19 (L224); "He only approved 27." ~22:51 (L227) | stated |
| 50% | Karl approval rate of skill-passed leads | 27 ÷ 54 | as above | estimated (27 ÷ 54) |
| 3% | skill pass rate | 32 ÷ ~1,000 | as above | estimated (32 ÷ 1,000) |
| 2–4+ | publishers per domain | Skill output lists publishers and prices | "it could be two, three, or four or more publishers here." ~18:43 (L182) | stated |
| 3 | dynamic clients | BCR (inferred), Five Good Friends, Leaselab | "the parking car rentals, the lease lab, and for the five good friends." ~05:15 (L034) | stated (BCR inferred) |
| 0–3 | weeks | Order to published | "Some links can be published right away." ~12:38 (L099); "it takes one, two, three weeks." ~12:50 (L101) | stated |
| 1–2 | weeks | Publisher negotiation | "A week or two." ~13:53 (L111) | stated (garbled context) |
| $100–150 | per link | Austin's illustrative example, not a fact | "it's \$100 or \$150, whatever the amount is." ~23:54 (L239) | interviewer (example) |
| 1 | month synced | Monday.com sync done for October; November in progress | "for the October, it added already" ~41:14 (L439) | stated |

## 9. Tools, data and workarounds

- **Official tools:** Google Sheets (internal publishers' order sheet and blog list, external publishers' sheets, dynamic-clients leads sheet, approved / do-not-use lists, Master Sheet, publishers list with prices); Ahrefs (DR, traffic, keywords); Google search and Google AI Mode; Monday.com (link board); Claude.
- **Shadow tools / workarounds:** Tonie's own Claude lead-review skill/project, alongside a separate skill from Karl; Claude prompts/skill for finding blog lists by niche; Apps Script duplicate-domain checker (built with Claude); Google Sheets link-status extension (built with Claude); Claude-built master sheet → Monday.com automation; Gemini used earlier for lead checks (L016).
- **Same data in more than one place:** orders (internal order sheet and each external publisher's sheet); published links (publisher sheets, master sheet, "other sheets", Monday.com); lead decisions (approved / do-not-use lists and the skill's reference copy); approval criteria (Tonie's skill vs Karl's skill vs Karl's judgement).
- **Data or access she needs but doesn't have:** a reliable, agreed lead-approval standard; a client requirements table for allocation; a dependable Monday.com sync; more Tier 1 supply. Austin asked for access to all her spreadsheets and the publishers list with prices (L046, L186, L457).

## 10. Knowledge and dependency

| What | Who (role) | If absent |
|---|---|---|
| Whole link-building operating flow (sourcing, allocation, orders, link checks, master sheet) | TG 👤 | 300–340 links a month stall; nobody else described doing it |
| Lead-review skill, Apps Script checker, link-status extension, Monday.com sync | TG (built them; undocumented) | Tools break or go stale unnoticed |
| Which domain suits which client | TG | Allocation slows or duplicates creep in |
| Final lead approval | Karl (Senior SEO Manager & Link-building Lead) | Leads queue; no other approver described |
| Relationships with in-house and external publishers/brokers | TG | Supply and order delivery disrupted |
| Publisher payments | Karl (per Austin's description) | Publishers unpaid; possible delays |

## 11a. Clients mentioned

| Client | Tier (context pack) | What was said |
|---|---|---|
| Bargain Car Rentals ("parking car rentals" – inferred) | Tier 1 | One of three "dynamic clients" on a separate leads sheet; needs Tier 1 (single-niche) leads – hard to find and expensive |
| Five Good Friends | Tier 1 | Dynamic client; same Tier 1 lead scarcity and cost |
| Leaselab ("lease lab" / "Please Love") | Tier 1 | Dynamic client; same Tier 1 lead scarcity and cost |
| All link-building clients (unnamed) | – | 300–340 links a month across "all the clients" |
