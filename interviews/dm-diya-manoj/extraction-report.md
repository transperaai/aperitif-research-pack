# Part A – Transcript extraction: Diya Manoj (Performance Marketing Manager)

**Source and method notes**
- Transcript: meeting notes "Diya Manoj – Workflow & Process Interview", 30 Oct 2026, 11:00 am (Melbourne) booking (00:00–01:00 UTC). Full transcript retrieved (668 utterances, ends at sign-off) – not truncated. The AI summary was not used as a source.
- **Timestamps:** the transcript has no timestamps. Every timestamp below is written `~mm:ss (L###)`: L### is the utterance number in `transcript.md`; ~mm:ss is estimated from cumulative word position.
- **Speakers:** the diariser split Austin across A, G and H (G: "Can you see my screen?", L323; H: "So let's just say they've approved", L451) and Diya across B, C, D, E, F and I (mostly C and D; E/F/I are back-channel). All non-Austin lines are treated as Diya. A few one-word D lines could be either speaker; none are relied on.
- **Name and term corrections (transcription):** "cloud" → Claude · "Esten" → Austin · "Wenly" → Wendlley (Simoes) · "Katty and Mickey / Patty / tattooing / Mikhail / Nikaila / Mikaela / Ochaty" → Tati (Tatiana Stinson, Performance Marketing Coordinator) and Michaela (Cruz, Performance Marketing Specialist) · "Tina" → the Tina Slack agent bot (OpenClaw workspace), not Tatiana · "Ruby" → Rubii (Diya spelled it R-U-B-I-I, L143) · "monthly bits / vips" → monthly WIPs · "Facing / basing / pasting" → pacing · "ROS / ROAs" → ROAS · "Convertions" → conversions · "Monday" → Monday.com · "Agency Analytics" → AgencyAnalytics · "Dio / Dia" → Diya.
- Hours are costed at **$80/hr internal labour cost**. Process totals are Diya's time only: the specialists' build time (Michaela / Tati) was not discussed and is not costed.

---

## 0. Interview card

| Field | Detail |
|---|---|
| Interviewee | Diya Manoj |
| Role | Performance Marketing Manager (media buyer) |
| Team | Performance (paid media) |
| Date | 30 Oct 2026 |
| Interviewer | Austin Smith (Transpera AI) |
| Clients managed | ~20, mostly Tier 2 and Tier 3 (stated, L072, L344) |
| Channels / services | Google Ads and Meta only at Aperitif (L550); strategy, budget confirmation, pacing, optimisation, reporting, monthly WIPs, new-client audit and strategy, landing-page and creative brief review |
| Reports to | Wendlley Simoes, Performance Marketing Director (context pack – not discussed; she mentions "telling my manager", L440) |
| Hands work to | Michaela Cruz (Performance Marketing Specialist) and Tati (Tatiana Stinson, Coordinator) – campaign builds, larger optimisations, landing-page and creative briefs, via Monday.com; clients (strategy docs, Meta ad previews, monthly commentary, WIP calls) |
| Receives work from | Clients (briefs, budget confirmations, approvals, ad-hoc questions); Tina Slack agent bot (budget pacing messages); Michaela and Tati (builds back for QA, LP brief drafts); senior colleagues give "expert opinion" when she asks (L072) |

## 1. Five-line summary

1. Diya runs ~20 paid-media clients (mostly Tier 2/3) end to end on Google and Meta; specialists Michaela and Tati build, she does strategy, optimisation, reporting and client contact.
2. Her biggest time sink is pulling data from several systems (Google Ads, CRM, GA4) to answer one client question; she already uses Claude as a crude workaround but briefing it takes time.
3. Her "magic wand" fix is pacing: Tina only reports budget pacing, so she checks conversions and CPA/ROAS/CPL account by account; she wants richer, category-specific pacing in Monday.com (she used Rubii at a previous agency).
4. Monthly AgencyAnalytics commentary takes ~30 min per client (≈10 h/month for 20 clients), plus ~30 min of data review before each monthly WIP call – both rebuilt by hand from change history.
5. Some clients must approve even minor optimisations and every creative change; she waits with "hands tied" yet is held accountable for results. Meta ads built by others are QA'd ad by ad (20–30 per launch) to catch format/placement errors.

## 1a. Time allocation

| Activity | % / hours | Billable? | Quote + timestamp | Certainty |
|---|---|---|---|---|
| Data analysis / investigating performance (incl. cross-platform look-ups) | "Dominates" her day | Billable (client work) | "I feel like I spend a lot of time in analyzing data" ~02:45 (L045) | stated (no %) |
| Strategy for upcoming campaigns | Main focus the interview week | Billable | "this particular week was more into you know strategy side of things and you know analyzing" ~01:43 (L035) | stated (no %) |
| Client calls (monthly WIPs + ad hoc) | "a few client calls" that week; WIPs in first two weeks of month | Billable | "I also had like few client calls." ~02:31 (L040) | stated |
| Delivery work (optimisations, pacing, reporting) | "usual" | Billable | "the delivery work, which is usual" ~02:34 (L042) | stated |
| Briefing specialists / Monday.com admin | Not quantified | Non-billable (assumed) | "briefing requires another time" ~05:47 (L076) | stated (no %) |

- **Busy vs quiet:** month-end and month-start are always busy – "it will be always busy when it comes to month-end and month-starting" ~00:22 (L017); monthly WIPs fall mostly in the first two weeks ~32:29 (L459). Otherwise peaks are client-driven (performance drops, client peak seasons), "not like a seasonal pattern" ~09:30 (L110).
- **No % or hours given.** Estimated split of her costed time (section 2 midpoints, ~114 h/month): optimisation ~19%, client meetings & prep ~19%, campaign build ~16%, pacing checks ~13%, ad-hoc investigation ~10%, reporting ~9%, onboarding ~7%, budget confirmation ~5%, task management ~2% – estimated from assumed frequencies; confirm with timesheets.
- **Billable vs non-billable:** not discussed directly. Assumed split: about 85–90% client-attributable, about 10–15% internal (briefing specialists, Monday.com admin, QA). Confirm with timesheets.

## 2. Processes

Flags: ⏸ bottleneck · 👤 single-person dependent · ⌨️ manual copy / re-keying · ⚠️ error-prone. Interviewee = DM. Team = Michaela / Tati.

### DM-P01 · Paid media – pacing & budget management (performance pacing checks)
- **Trigger:** fortnightly cycle per client (weekly for new clients); Tina's budget-pacing message in Slack.
- **Owner role:** Performance Marketing Manager (Diya) for her ~20 clients.
- **Frequency:** fortnightly per client, weekly for new clients (stated ~29:30 (L393)) → ~2–2.5 checks/client/month × 20 clients = 40–50 checks/month (estimated). Tina posts M/W/F (~13/month, per brief; Austin thought "daily", L304).
- **Tools / files:** Tina (OpenClaw Slack bot), Google Ads, Meta Ads Manager, CRM and GA4 when a drop needs explaining.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Read Tina's budget pacing message (spend % vs budget) | PMM | Slack (Tina) | 5–10 per message | – | – | assumed |
| 2 | Open each account; check spend vs budget, conversions, CPA/ROAS (e-com) or CPL (lead gen) ⌨️ ⚠️ | PMM 👤 | Google Ads / Meta | 10–15 per account | – | – | assumed (Diya: "takes time", L307; Shrishti's 15–20 min for adjustments in context pack) |
| 3 | Adjust budgets/bids if off-track | PMM | Google Ads / Meta | incl. in step 2 | – | Client if budget change needs approval | assumed |

- **Happy path total:** 10–15 min touch per account check (+5–10 min per Tina message); elapsed same day.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Performance drop needs explaining | Conversions/CPA moved | 10–25% of checks | Cross-check CRM, GA4, change history | +15–30 min | PMM, client | assumed |
| Drop missed between fortnightly checks | No alert | unknown | Found at next check or by client | unknown | Client, PMM | detected |

- **Decision points:** after step 2 – on track (~75–90%) / investigate (~10–25%) – assumed. After step 3 – adjust within approved budget / ask client – not discussed.
- **Volume (team):** not discussed for the team; Diya alone ~40–50 checks/month (estimated).
- **Monthly hours:** low = 20 × 2 × 10 = 400 min + 13 × 5 = 65 + 40 × 10% × 15 = 60 → 525 min = **8.8 h**; high = 20 × 2.5 × 15 = 750 + 13 × 10 = 130 + 50 × 25% × 30 = 375 → 1,255 min = **20.9 h** (estimated).
- **Monthly cost:** 8.8 × $80 = **$704** to 20.9 × $80 = **$1,672**.
- Flags: step 2 👤 ⌨️ ⚠️ (manual per-account review; this is the step she wants automated).

### DM-P02 · Paid media – pacing & budget management (start-of-month budget confirmation)
- **Trigger:** start of month.
- **Owner role:** PMM; client approves.
- **Frequency:** 1 per client per month × 20 clients (stated cadence, ~27:48 (L351)).
- **Tools / files:** email/client comms, Google Ads, Meta (budget sheet not mentioned).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Confirm monthly budget with client and ask about upcoming campaigns | PMM | Email / call | 5–10 | Client reply: hours–days ⏸ | Client | stated (step) / assumed (time) |
| 2 | Make budget adjustments in platforms | PMM ⌨️ | Google Ads / Meta | 5–10 | – | – | stated (step) / assumed (time) |
| 3 | If new campaigns → start strategy (DM-P03) | PMM | – | – | – | DM-P03 | stated |

- **Happy path total:** 10–20 min touch; elapsed 1–5 days (assumed, client response).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Client slow to confirm | No reply | 20–40% of clients | Chase | +5–10 min | PMM; pacing starts late | assumed |

- **Decision points:** new campaigns planned? yes / no – split not stated.
- **Monthly hours:** low = 20 × 10 + 20 × 20% × 5 = 220 min = **3.7 h**; high = 20 × 20 + 20 × 40% × 10 = 480 min = **8.0 h** (estimated).
- **Monthly cost:** 3.7 × $80 = **$296** to 8.0 × $80 = **$640**.

### DM-P03 · Paid media – campaign build (new campaign for an existing client)
- **Trigger:** client briefs a new campaign at month start or ad hoc (~05:21 (L075); ~28:06 (L358)).
- **Owner role:** PMM (strategy, approvals, QA); Performance Marketing Specialist (Michaela or Tati) builds.
- **Frequency:** not stated. Assumed 2–4 launches/month across her 20 clients.
- **Tools / files:** strategy document, Google Ads, Meta Ads Manager, Monday.com (briefs), ad previews.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Develop strategy: targeting, budget, structure, ad copy, creatives | PMM 👤 | Strategy doc | 120–240 | – | Client | stated (step) / assumed (time) |
| 2 | Share strategy; client approves (Google ad copy approved here) | PMM → client | Strategy doc | 15–30 | Client approval ⏸ (unknown) | Client | stated (step) / assumed (time) |
| 3 | Brief specialist on implementation (minor changes done by PMM herself) | PMM | Monday.com | 20–45 | Specialist queue (unknown) | Michaela / Tati | stated (step) / assumed (time) |
| 4 | Specialist builds campaign / ads | Specialist | Google Ads / Meta | not discussed | – | PMM | stated (step) |
| 5 | QA every ad (Meta: 20–30 ads; format vs placement) ⚠️ ⌨️ | PMM 👤 | Meta Ads Manager | 20–60 | – | Client | stated (step, volume) / assumed (time) |
| 6 | Meta only: send ad previews for client approval | PMM → client | Ad previews | 10–20 | Client approval ⏸ | Client | stated (step) / assumed (time) |
| 7 | Launch / check live | PMM | Platforms | 10–20 | – | – | assumed |

- **Happy path total:** 195–415 min PMM touch per launch (3.3–6.9 h); elapsed several days to 2+ weeks (assumed; two client approvals for Meta).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Ad copy changes (brand tone) | Client feedback | 30–50% of launches | Rewrite copy, re-share | +20–45 min | PMM, client | stated ("normally there would be changes", L532) / rate assumed |
| QA finds wrong format/placement (e.g. square in Stories) | Build error or Meta glitch | 20–40% of Meta launches | Fix or re-brief specialist, re-check | +15–30 min | PMM, specialist | stated (risk) / rate assumed |
| Client rejects strategy | Misalignment | Rare ("most of the times it should be completely okay", L531) | Conversation, revise | not quantified | PMM | stated |
| Client changes mind mid-execution | Client | Not experienced yet (L542) | Persuade client | – | PMM | stated |

- **Decision points:** after 2 – approved first time (most) / revisions to copy (common) – stated, no %. After 3 – brief specialist (big change) / do it herself (minor) – stated (L076, L082). After 5 – pass / fix. After 6 (Meta) – approve / change.
- **Volume (team):** not discussed.
- **Monthly hours:** low = 2 × (195 + 30% × 20 + 20% × 15) = 2 × 204 = 408 min = **6.8 h**; high = 4 × (415 + 50% × 45 + 40% × 30) = 4 × 449.5 = 1,798 min = **30.0 h** (estimated – widest range in this transcript; launch count needs confirming).
- **Monthly cost:** 6.8 × $80 = **$544** to 30.0 × $80 = **$2,400**.

### DM-P04 · Paid media – optimisation
- **Trigger:** ongoing; at least fortnightly for newer clients (stated ~30:10 (L410)).
- **Owner role:** PMM (does analysis and actions; briefs specialists only for time-consuming changes, L082).
- **Frequency:** assumed ~2 optimisation passes per client per month × 20 = 40/month.
- **Tools / files:** Google Ads (search term reports, negatives, bids), Meta (creative swaps), CRM/GA4 for context.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Review data: search term report, performance by campaign | PMM 👤 | Google Ads / Meta | 10–20 | – | – | stated (step) / assumed (time) |
| 2 | Decide changes using client context (e.g. negatives on non-converting/irrelevant terms; bigger budgets tolerate competitor terms) | PMM 👤 | – | 5–10 | – | – | stated (logic, L568–L570) |
| 3 | Action changes (negatives, bids, campaign changes, creative swaps) | PMM (or specialist if large) | Google Ads / Meta | 5–10 | – | – | stated (step) / assumed (time) |

- **Happy path total:** 20–40 min touch per pass; elapsed same day.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Client requires approval for any change (incl. minor ones) | Client policy | "Some clients" – assumed 10–20% of passes | Write up change, request approval, chase | +10–15 min touch; wait days ⏸ | PMM, client results | stated (exists, L436–L445) / rate assumed |
| Creative change needs approval (even if client says not needed) | Agency's own caution | Every creative change | Send for approval | wait | PMM | stated (L433) |
| Change too big to do herself | Time-consuming change | not stated | Brief specialist | briefing time | PMM, specialist | stated |

- **Decision points:** after 2 – act now / needs client approval / brief specialist – stated, no split.
- **Monthly hours:** low = 40 × 20 + 40 × 10% × 10 = 840 min = **14.0 h**; high = 40 × 40 + 40 × 20% × 15 = 1,720 min = **28.7 h** (estimated).
- **Monthly cost:** 14.0 × $80 = **$1,120** to 28.7 × $80 = **$2,296**.

### DM-P05 · Monthly reporting (AgencyAnalytics commentary)
- **Trigger:** month end, before each client's monthly WIP.
- **Owner role:** PMM.
- **Frequency:** 1 per client per month × 20 (stated).
- **Tools / files:** AgencyAnalytics, Google Ads / Meta change history.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Open account change history; list changes made ⌨️ | PMM 👤 | Google Ads / Meta | part of 25–35 | – | – | stated (step) |
| 2 | Link changes to performance (last month vs this month) | PMM | AgencyAnalytics | part of 25–35 | – | – | stated |
| 3 | Write plan for next month; publish commentary | PMM | AgencyAnalytics | part of 25–35 | – | Client | stated |

- **Happy path total:** 25–35 min per client ("on average… 30 minutes", smaller clients quicker – ~23:21 (L278), stated average; range estimated).
- **Bad paths:** not discussed.
- **Monthly hours:** 20 × 25 = 500 min = **8.3 h**; 20 × 35 = 700 min = **11.7 h** (estimated from stated 30-min average).
- **Monthly cost:** 8.3 × $80 = **$664** to 11.7 × $80 = **$936**.
- Note: Austin's in-call maths ("20 minutes… that's what 200 minutes", L284) understates it – 20 × 20 = 400 min.

### DM-P06 · Client meetings & prep (monthly WIP calls)
- **Trigger:** monthly WIP cadence, mostly in first two weeks of the month.
- **Owner role:** PMM; agenda sent to the client before the call ("system in place", L287).
- **Frequency:** 1 per client per month × 20 (stated cadence; assumes every client has a monthly WIP).
- **Tools / files:** platforms, AgencyAnalytics, agenda email.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Agenda sent before call day | PMM / system | Email | not stated | – | Client | stated |
| 2 | Review account data before the call ⌨️ | PMM 👤 | Platforms / AgencyAnalytics | 15–30 (stated 30; low end allows overlap with DM-P05 review) | – | – | stated / estimated |
| 3 | Hold WIP call | PMM + client | Video call | 30–45 | – | – | assumed (call length not stated) |

- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Follow-up actions/questions after call | Client requests | 20–40% of calls | Investigate, reply | +10–20 min | PMM | assumed |

- **Monthly hours:** low = 20 × (15 + 30) + 20 × 20% × 10 = 940 min = **15.7 h**; high = 20 × (30 + 45) + 20 × 40% × 20 = 1,660 min = **27.7 h** (estimated).
- **Monthly cost:** 15.7 × $80 = **$1,256** to 27.7 × $80 = **$2,216**.

### DM-P07 · NEW: Ad-hoc client query & performance investigation (cross-platform)
- **Trigger:** client question or request, often when performance drops or in their peak season.
- **Owner role:** PMM; senior colleague for "expert opinion" when needed (L072).
- **Frequency:** not stated. Assumed 5–12 investigations/month; "five or six clients" can land on a single day (stated, L106).
- **Tools / files:** Google Ads, Meta, CRM, GA4, Claude (briefed manually).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Receive question; prioritise against other clients (relationship/fees) | PMM | Email/Slack | incl. below | – | – | stated |
| 2 | Pull data from Google Ads, CRM, GA4 etc. ⌨️ ⚠️ | PMM 👤 | Multiple | 30–75 per query (incl. 3–4) | Access/data lags not discussed | – | stated (step) / assumed (time) |
| 3 | Optionally brief Claude with context to analyse | PMM | Claude | incl. | – | – | stated (L060–L063) |
| 4 | Explain to client (why, solution, next steps) | PMM | Email/call | incl. | – | Client | stated (L120) |

- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| "Perfect storm" – several clients ask on one day | Drops / peak season | 1–2 days/month | Triage, other work slips | +60–120 min | PMM; other clients | stated (exists) / rate assumed |

- **Monthly hours:** low = 5 × 30 + 1 × 60 = 210 min = **3.5 h**; high = 12 × 75 + 2 × 120 = 1,140 min = **19.0 h** (estimated).
- **Monthly cost:** 3.5 × $80 = **$280** to 19.0 × $80 = **$1,520**.

### DM-P08 · Client onboarding – audit & strategy (new paid-media client)
- **Trigger:** new client won.
- **Owner role:** PMM; Tati drafts landing-page brief; PMM reviews.
- **Frequency:** not stated; assumed 0.5–1 new clients/month for Diya.
- **Tools / files:** internal account-audit document ("very detailed document", L628), strategy document (Diya to send Austin the template), competitor websites, landing-page brief, creative brief.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Audit existing account against detailed audit doc | PMM 👤 | Audit doc, platforms | 120–240 | Access (not discussed here) | – | stated (step) / assumed (time) |
| 2 | Share audit findings with client | PMM | Audit doc | 30–60 | Client | Client | stated / assumed |
| 3 | Get client brief; build campaign structure, budget, targeting | PMM | Strategy doc | 120–240 | Client brief ⏸ | – | stated / assumed |
| 4 | Ad copy; source creatives (Meta), or write creative brief for client's in-house team | PMM | Strategy doc / creative brief | 60–120 | Client creatives | Client / specialist | stated / assumed |
| 5 | Landing-page recommendation: Tati writes brief, PMM reviews vs current site and competitors | Tati → PMM | LP brief | 60–120 (PMM review) | Tati queue | Client | stated / assumed |

- **Happy path total:** 390–780 min PMM touch per new client (6.5–13 h); elapsed 1–3 weeks (assumed).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Extra review rounds on LP brief / creative | Gaps vs site/competitors | 30–50% | Re-review | +30–60 min | PMM, Tati | assumed |

- **Decision points:** client has in-house design → creative brief / no → Aperitif supplies creatives (stated, L630–L633). Weak website → recommend landing page (stated). CRO not offered (L638).
- **Monthly hours:** low = 0.5 × (390 + 30% × 30) = 199.5 min = **3.3 h**; high = 1 × (780 + 50% × 60) = 810 min = **13.5 h** (estimated).
- **Monthly cost:** 3.3 × $80 = **$264** to 13.5 × $80 = **$1,080**.

### DM-P09 · Internal task management (Monday.com)
- **Trigger:** tasks assigned to/by Diya in Monday.com; team "completely moved to Monday recently" (L138).
- **Owner role:** each assignee.
- **Frequency:** continuous; not quantified.
- **Tools / files:** Monday.com (notifications on status change only).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Create/brief task | PMM | Monday.com | incl. in DM-P03/04 | – | Specialist | stated |
| 2 | Check for overdue or stuck items ("awaiting approval" never updated) by hand | PMM | Monday.com | 1–3 h/month total | Unknown – items can sit indefinitely ⏸ | – | stated (problem) / assumed (time) |

- **Monthly hours:** 1–3 h of manual checking for stuck/overdue items → **1.0–3.0 h** (assumed).
- **Monthly cost:** 1.0 × $80 = **$80** to 3.0 × $80 = **$240**.

### Process totals

| ID | Process | Monthly hours (all actors) | DM-only hours | Monthly cost (all actors) |
|---|---|---|---|---|
| DM-P01 | Paid media – pacing & budget management (performance pacing checks) | 8.8–20.9 | 8.8–20.9 | $704–$1,672 |
| DM-P02 | Paid media – pacing & budget management (start-of-month budget confirmation) | 3.7–8.0 | 3.7–8.0 | $296–$640 |
| DM-P03 | Paid media – campaign build | 6.8–30.0 | 6.8–30.0 | $544–$2,400 |
| DM-P04 | Paid media – optimisation | 14.0–28.7 | 14.0–28.7 | $1,120–$2,296 |
| DM-P05 | Monthly reporting | 8.3–11.7 | 8.3–11.7 | $664–$936 |
| DM-P06 | Client meetings & prep | 15.7–27.7 | 15.7–27.7 | $1,256–$2,216 |
| DM-P07 | NEW: Ad-hoc client query & performance investigation | 3.5–19.0 | 3.5–19.0 | $280–$1,520 |
| DM-P08 | Client onboarding – audit & strategy | 3.3–13.5 | 3.3–13.5 | $264–$1,080 |
| DM-P09 | Internal task management | 1.0–3.0 | 1.0–3.0 | $80–$240 |
| **Total** | | **65.1–162.5 h** | **65.1–162.5 h** | **$5,208–$13,000** |

"All actors" equals DM-only here because the specialists' build time (Michaela / Tati) was not discussed – add it after their interviews. The high ends can't all happen in the same month: 162.5 h is about one full-time month (~152–165 h). Treat the low-to-mid range (~65–115 h) as more realistic and confirm with calendar, Monday.com and timesheet data.

## 3. Pain points and problems

| ID | Pain point (one line) | Source | Category | Anchor | Process | Impact | How often | Severity 1–5 | Quote + timestamp | Certainty |
|---|---|---|---|---|---|---|---|---|---|---|
| DM-PP01 | Answering even a Google Ads question means jumping across CRM, GA4 and other platforms | interviewee | Missing visibility | Technology, AI & stack | NEW: Ad-hoc client query & performance investigation | time (est. 3.5–19 h/month) | Daily ("dominates") | 4 | "Even though it's a Google Ads related question, I'll be jumping onto the CRM, GA4 and everything to better understand." ~02:52 (L046) | stated |
| DM-PP02 | Tina pacing covers budget only; conversions and CPA/ROAS/CPL checked account by account by hand | interviewee | Manual / repetitive work | Performance visibility & margin | Paid media – pacing & budget management | time (8.8–20.9 h/month); margin/risk | Fortnightly × 20 clients | 4 | "the one Tina is sending it out is just budget basing… I look for each of the accounts, which actually takes time." ~25:27 (L307) | stated |
| DM-PP03 | No alert when an account's performance drops suddenly; found only by going into each account | interviewee (weekly update); interviewer extended to real-time thresholds | Missing visibility | Performance visibility & margin | Performance monitoring & alerting | client / risk | Continuous | 4 | "if there is like a sudden drop… if you get like a weekly update, that would be like really helpful." ~16:37 (L193) | stated |
| DM-PP04 | Monthly commentary written by hand from change history, ~30 min per client | interviewee | Manual / repetitive work | Operations capacity & process | Monthly reporting | time (8.3–11.7 h/month) | Monthly × 20 | 3 | "it will be 30 minutes for each client, I would say." ~23:04 (L272) | stated |
| DM-PP05 | ~30 min data review before every monthly WIP call | interviewee | Manual / repetitive work | Client experience & delivery | Client meetings & prep | time (5–10 h/month prep) | Monthly × 20 | 3 | "for every monthly bit, what I do is I put like a 30 minutes just before that call to analyze the data" ~21:42 (L257) | stated |
| DM-PP06 | Some clients must approve even minor optimisations; manager waits but is blamed for results | interviewee | Waiting / handoff delay | Client experience & delivery | Paid media – optimisation | client results; morale | Ongoing ("currently happening") | 4 | "I feel like my hands are tied back because I can't do anything on the account. I am just waiting for their approval" ~31:53 (L445) | stated |
| DM-PP07 | Creative/ad-copy changes always sent for approval, even when clients say it isn't needed, to avoid blame | interviewee | Waiting / handoff delay | Client experience & delivery | Paid media – optimisation | wait time | Every creative change | 2 | "we seek the ad copy approval because it's on safer side. Otherwise, if something goes off, then we would be getting the blame." ~30:57 (L433) | stated |
| DM-PP08 | Manager QAs every Meta ad built by specialists (20–30 per launch) to catch format/placement errors | interviewee | Rework / errors | Client experience & delivery | Paid media – campaign build | time; risk of cropped creative reaching clients | Each Meta launch | 3 | "if another person is working on it, I won't be having that clarity. I just need to go and individually check each ad." ~20:32 (L237) | stated |
| DM-PP09 | Monday.com sends no reminders for overdue tasks; items sit in "awaiting approval" when nobody updates them | interviewee | Missing visibility | Operations capacity & process | Internal task management | delay; dropped tasks | Ongoing | 3 | "it might be sitting under like an awaiting approval or something, even though that has been done." ~14:53 (L171) | stated |
| DM-PP10 | ~20-client portfolio; overloaded when several clients want things the same day | interviewee | Capacity / overload | Operations capacity & process | NEW: Ad-hoc client query & performance investigation | capacity; Tier 2/3 service | 1–2 days/month (assumed) | 3 | "what if like, you know, five or six clients come to you on a single day and ask you for like so much of things." ~08:41 (L106) | stated (rate assumed) |
| DM-PP11 | Using Claude helps but briefing it with each situation takes time | interviewee | Tool not used / adoption | Technology, AI & stack | NEW: Ad-hoc client query & performance investigation | time | Per use | 2 | "that also requires a lot of time to just brief it, make it understand what exactly is the situation." ~04:00 (L063) | stated |
| DM-PP12 | No clear rule on whether Claude may connect to client ad platforms (data privacy), so she hasn't used it | interviewee | Risk / compliance | Technology, AI & stack | Monthly reporting | blocks AI help; compliance risk if staff improvise | Ongoing | 3 | "I'm not sure how much it is okay to have the data privacy and everything when we do that." ~15:21 (L181) | stated |
| DM-PP13 | Briefing specialists costs enough time that the manager does minor changes herself | interviewee | Waiting / handoff delay | Operations capacity & process | Paid media – optimisation | time; manager does lower-level work | Frequent | 2 | "briefing requires another time. So better do it yourself so that it's all sorted." ~05:47 (L076) | stated |
| DM-PP14 | Clients question the agency for drops caused by economy or tests, creating explanation work | interviewee | Client friction | Client experience & delivery | Client meetings & prep | time; relationship | When performance dips | 2 | "even though the client knows about it they won't be you know taking it… they'll just come back and question you" ~10:27 (L116) | stated |

**Top 3 by severity – root cause and match**

1. **DM-PP02 Performance pacing done by hand (4).** Why? Tina only reports spend vs budget. Why? The bot was built around budget data only and there is no shared definition of per-client KPIs (conversions, CPA/ROAS/CPL by client type). Why? No agreed pacing data model or owner for the pacing tooling (context pack: Supermetrics lapsed; Slack bots have no visible owner). **Root cause:** pacing tooling is budget-only and unowned; performance KPIs per client category are not defined anywhere a system can read. Matches existing problem *"No proactive performance alerting – problems found at month-end"* (partly) and *"Slack bots and agents have no visible owner or documentation"* (detected link). The "Tina is budget-only" gap is new.
2. **DM-PP01 Cross-platform data hunt (4).** Why? Each client's data sits in separate systems (Google Ads, Meta, CRM, GA4). Why? No per-client consolidated data view or warehouse; AgencyAnalytics is used for reports, not for answering questions. **Root cause:** no single per-client data layer that managers can query. **New** problem (closest existing: *"Client knowledge lives in people's heads, not per client"* – not a direct match).
3. **DM-PP06 Approvals for minor optimisations (4).** Why? Some clients insist on approving every change; the agency also seeks approval defensively. Why? Scope of delegated authority is not written into client agreements or onboarding. **Root cause:** no standard "change authority" rule (what the agency may change without approval, and what happens if a client doesn't reply). **New** problem.

(DM-PP03 is also severity 4; it matches existing problem *"No proactive performance alerting – problems found at month-end"*.)

## 4. Bottlenecks

| ID | Step | Waiting on | Typical wait | Affected | Knock-on |
|---|---|---|---|---|---|
| DM-B01 | Optimisations / creative changes on approval-required clients (DM-P04) | Client approval | Days – "still waiting on like few approvals" (~31:32 (L440)); exact time not stated | "Some clients" (count unknown) | Results stall; manager blamed at month end ("why you didn't do that?", L448) |
| DM-B02 | Meta ad QA before launch (DM-P03 step 5) | Diya's time to review 20–30 ads one by one | Not stated | Every Meta launch built by Michaela/Tati | Launch delay; errors slip if rushed |
| DM-B03 | Monday.com tasks stuck in "awaiting approval"/overdue | Someone noticing and updating | Indefinite – no reminder | Team-wide (assumed) | Work looks unfinished; overdue items missed |
| DM-B04 | Start-of-month budget confirmation (DM-P02) | Client reply | Hours–days (assumed) | 20 clients monthly | Pacing and new strategy start late |
| DM-B05 | Meta ad preview approval (DM-P03 step 6) | Client | Not stated | Meta launches | Second approval loop vs Google |

## 4a. Decisions and approvals

| Decision | Who decides (role) | Who waits | Typical time | Lands on leadership? |
|---|---|---|---|---|
| Monthly budget and upcoming campaigns | Client (PMM proposes) | PMM | Not stated | No |
| Campaign strategy (incl. Google ad copy) | Client | PMM, specialists | Not stated; rarely rejected | No |
| Meta ad previews | Client | PMM, launch | Not stated | No |
| Minor optimisations (some clients) | Client | PMM | Days | No – but could be pre-agreed in scope |
| Creative / ad copy changes | Client (sought defensively) | PMM | Not stated | No |
| Whether Claude may connect to client platforms (data privacy) | Founder (Joe) – Austin: "you'd have to double check with Joe" (L182) | All managers wanting to use it | Open | **Yes** – appropriate for a policy, but should become a written rule so it isn't asked case by case |
| Brief a specialist vs do it herself | PMM | – | Instant | No |
| Which client to prioritise on a busy day (relationship, fees) | PMM | Other clients | Instant | No |
| Negative keywords (relevance, budget size, conversion history) | PMM | – | Instant | No |
| Landing-page brief sign-off | PMM reviews Tati's draft | Tati, client | Not stated | No |
| Expert opinion on tricky analysis | Senior colleague (unnamed) | PMM | Not stated | Possibly (Director) – not stated |

## 5. Suggestions for change (as raised in the interview)

| ID | Idea | Source + reaction | Process | Quote + timestamp |
|---|---|---|---|---|
| DM-S01 | Put pacing into Monday.com, Rubii-style (where tracking, over/under) – not necessarily buying Rubii | interviewee | Paid media – pacing & budget management | "as we have completely moved to Monday recently, I was thinking like we can, you know, put that pacing into that particular platform." ~12:15 (L138) |
| DM-S02 | Richer pacing: conversions plus ROAS (e-com) or CPL (lead gen), by client category | interviewee | Paid media – pacing & budget management | "conversions would be the key point. And if it's an e-commerce client, definitely ROAS is important… that will be CPL." ~25:50 (L312) |
| DM-S03 | Monday.com reminders for overdue/stuck tasks | interviewee (Austin: "a great idea… I think it's a native thing") | Internal task management | "send some reminders for the overdue task or something so that we know exactly, okay, this has not been done" ~13:44 (L160) |
| DM-S04 | Connect Claude as a browser extension to ad platforms (e.g. for commentary/audits) – asked whether allowed | interviewee; Austin: check with Joe, turn off training-data sharing, check client contracts | Monthly reporting / ad-hoc analysis | "we can actually connect cloud as a web extension and get connected to the platforms" ~15:21 (L181) |
| DM-S05 | Weekly update flagging sudden performance drops per account | interviewee | Performance monitoring & alerting | "if you get like a weekly update, that would be like really helpful." ~16:37 (L193) |
| DM-S06 | Real-time alert when a tracked metric drops below a threshold | interviewer; Diya agreed and said it would let her handle more clients | Performance monitoring & alerting | Austin: "if it drops below a certain threshold, we get an immediate like notification." ~16:56 (L196) · Diya: "handle more clients maybe." ~17:48 (L211) |
| DM-S07 | Meta ad QA tool that flags wrong format for placement (square in Stories) | interviewee; Austin extended to spell-check and dimension checks (L230) | Paid media – campaign build | "if like a square format ad is placed in the place of a story placement, is there any way to highlight that there is actually an error?" ~18:07 (L217) |
| DM-S08 | One place to ask for all data points about a client | interviewer; Diya: "That will definitely help." | NEW: Ad-hoc client query & performance investigation | "You had a platform where you could ask a question and say like, hey, can you get me all this data" ~03:38 (L053) |
| DM-S09 | Builders should get Meta ads right so the manager needn't QA | interviewer; Diya partly agreed but still QAs "to be on safer side" (L242) | Paid media – campaign build | "I don't think that should be your job either, because you're then stepping into Tati and Michaela's world" ~20:22 (L236) |

## 6. Opportunity assessment

| ID | Fixes | Lens | What changes | Matches existing solution idea | Existing tool | Hours saved / month (maths) | Effort | Prerequisites | Adoption risk | COI flag |
|---|---|---|---|---|---|---|---|---|---|---|
| DM-O01 | DM-PP02, DM-B04 (partly) | Automate | Extend pacing beyond budget: daily pull of spend, conversions and CPA/ROAS/CPL per account, with targets by client category; exceptions only to manager (in Monday.com or Tina) | Pacing tracker & adjustment engine | Tina/OpenClaw, Rubii, Supermetrics → Sheets/Looker Studio, Optmyzr, Monday.com dashboards | Per-account checks 6.7–12.5 h (20 × 2 × 10 min = 6.7 h; 20 × 2.5 × 15 = 12.5 h) × 50–70% = **3.3–8.8 h** | M | Per-client KPI targets and category; API access (Google/Meta); owner for the bot | M – managers may keep checking manually until trusted; automation preferred because a budget-only bot already exists and is used | Yes – Transpera could build |
| DM-O02 | DM-PP03, DM-PP10 | Automate | Threshold alerts (e.g. conversions −30% week-on-week, CPA +30%) per account to Slack/Monday, instead of waiting for fortnightly checks | Proactive PPC anomaly monitor | Google Ads automated rules/scripts, Optmyzr, Adalysis, Tina | Fewer late investigations: DM-P01 bad path 1.0–6.25 h × 30–50% = 0.3–3.1 h + DM-P07 3.5–19 h × 10–20% = 0.35–3.8 h → **0.7–6.9 h** | M | Same data feed as DM-O01; agreed thresholds by category | M – alert fatigue if thresholds poor | Yes |
| DM-O03 | DM-PP09, DM-B03 | Change the process | Turn on Monday.com native automations: "when due date passes and status ≠ Done, notify owner"; "when status is Awaiting approval for 3 days, notify" | None listed (relates to problem 25) | Monday.com automations (native) | DM-P09 1–3 h × 50% = **0.5–1.5 h** | S | Due dates set on tasks; board owner | L – no new behaviour | No |
| DM-O04 | DM-PP08, DM-B02 | Change the process (then Augment) | Builder self-QA checklist (placement → aspect ratio, asset customisation, copy spell-check) signed off in Monday.com; later, a script/AI check of ad previews flags mismatches so the manager only reviews exceptions | AI-assisted creative (partial) / new | Meta Ads Manager asset customisation & preview, Meta Marketing API script, Claude for copy checks | Meta QA 20–60 min × 1–2 Meta launches = 20–120 min × 50–80% = 0.2–1.6 h + avoided rework 0.1–0.4 h → **0.3–2.0 h** | S (checklist) / M (script) | Checklist; confirm Michaela/Tati workflow (not yet interviewed) | M – manager may still re-check everything at first | Partly (script) |
| DM-O05 | DM-PP04, DM-PP05, DM-PP10 | Augment | Auto-generate a monthly per-client summary (change history + month-on-month metrics) that drafts the AgencyAnalytics commentary and doubles as the WIP prep sheet; manager edits | Client-call prep summaries; transcripts → per-client action runsheet | AgencyAnalytics (AI summary/exports), Google Ads change-history export, Claude | Commentary 8.3–11.7 h × 40–60% = 3.3–7.0 h + WIP prep 5–10 h (20 × 15–30 min) × 30–50% = 1.5–5.0 h → **4.8–12.0 h** | S–M | DM-O06 privacy rule; consistent commentary template | L–M – she already uses Claude and asked for this | Yes |
| DM-O06 | DM-PP12, DM-PP11 | People & policy | Founder issues a written AI-data rule: approved tools/settings (training off, business plan), what client data may be sent, contract check list; share prompt templates so briefing Claude is quicker | AI business brain (enabler) / new | Claude Team/Enterprise settings, Notion policy page | **0 h direct** (enabler for DM-O05, DM-O08) | S | Joe's decision; review client contracts for data clauses | L | No |
| DM-O07 | DM-PP06, DM-PP07, DM-B01, DM-B04, DM-B05 | Change the process | Standard "change authority" in onboarding/SOW: list of optimisations the agency may make without approval; approval SLA (e.g. 2 business days then proceed or log as client-delayed); record client-caused delays in the monthly report | New | Proposal/SOW templates, Monday.com approval status | Approval chasing 0.7–2.0 h (40 × 10–20% × 10–15 min) × 50–75% = **0.3–1.5 h**; main value is results and accountability | M | Client services lead agrees wording; existing clients re-papered at renewal | M – some clients will refuse | No |
| DM-O08 | DM-PP01, DM-PP11, DM-PP10 | Augment | Per-client data layer (Google Ads, Meta, GA4, CRM) that managers can query in plain English, so one question doesn't mean four logins | AI business brain | BigQuery/Looker Studio + Supermetrics/Fivetran, Claude with connectors, AgencyAnalytics | DM-P07 3.5–19 h × 30–50% = **1.1–9.5 h** | L | Data access to client CRMs; DM-O06 policy; data owner | M – needs trust in data; she already wants it | Yes – flagged |

**KPIs**

| Opportunity ID | KPI | How measured | Baseline today | Target | Leading / lagging |
|---|---|---|---|---|---|
| DM-O01 | Manager minutes per pacing check | Time log sample / Monday.com time tracking | Unknown; "pacing… taking a lot of time right now" ~24:52 (L299) | ≤5 min per account (exception review only) | Leading |
| DM-O01 | % accounts within ±10% of budget and on target CPA/ROAS at month end | Pacing output | Unknown | ≥90% | Lagging |
| DM-O02 | Time from performance drop to manager awareness | Alert timestamp vs drop date | Up to ~14 days (fortnightly checks, L393) – estimated | Under 24 h | Leading |
| DM-O02 | Client-raised performance complaints per month | Monday.com / email tags | Unknown | −50% | Lagging |
| DM-O03 | Tasks overdue >3 days | Monday.com board filter | Unknown; "Currently I'm not getting any reminders" ~14:13 (L164) | −70% | Leading |
| DM-O04 | Meta ads with format/placement errors found at QA or after launch | QA checklist log | Unknown | Under 2% of ads | Lagging |
| DM-O04 | Manager QA minutes per Meta launch | Time sample | 20–30 ads reviewed one by one (L217) – minutes unknown | ≤10 min | Leading |
| DM-O05 | Minutes per client on monthly commentary | Time sample | ~30 min ("on average, I would say I put like 30 minutes" ~23:21 (L278)) | ≤12 min | Leading |
| DM-O05 | Reports published on time | AgencyAnalytics publish dates | Unknown | 100% by day 5 | Lagging |
| DM-O06 | Written AI-data rule published and acknowledged by Performance team | Notion page + sign-off | None ("I'm not sure how much it is okay" ~15:21 (L181)) | Published within 2 weeks; 100% acknowledged | Leading |
| DM-O07 | Clients with signed change-authority clause | Client records | Unknown | 80% of new clients; renewals within 12 months | Leading |
| DM-O07 | Median approval turnaround for optimisations | Monday.com status timestamps | Unknown ("still waiting on like few approvals" ~31:32 (L440)) | ≤2 business days | Lagging |
| DM-O08 | Minutes to answer an ad-hoc client data question | Time sample | Unknown; multi-platform (L046) | −50% | Leading |
| DM-O08 | Clients per manager at same service level | Portfolio count | ~20 (L072) | 22–24 without overtime | Lagging |

**Indicative ranking** (priority = Impact × Confidence × Ease)

| Rank | ID | Impact | Confidence | Ease | Priority | Tag | Reason |
|---|---|---|---|---|---|---|---|
| 1 | DM-O05 | 4 | 5 | 4 | 80 | Quick win | Stated 30 min × 20 clients; she already uses Claude; one summary serves commentary and WIP prep |
| 2 | DM-O06 | 3 | 4 | 4 | 48 | Quick win | One decision unblocks O05 and O08; asked directly in interview |
| 3 | DM-O01 | 4 | 4 | 3 | 48 | Strategic | Her #1 "magic wand" fix; clear scope but needs data feed and KPI targets |
| 4 | DM-O03 | 2 | 4 | 5 | 40 | Fill-in | Native Monday.com setting; small hours but fixes stuck tasks |
| 5 | DM-O04 | 3 | 3 | 4 | 36 | Quick win | Checklist is quick; error rate and Meta API capability unconfirmed |
| 6 | DM-O02 | 4 | 3 | 3 | 36 | Strategic | Earlier detection protects results and capacity; Austin's idea, Diya agreed |
| 7 | DM-O07 | 3 | 3 | 3 | 27 | Strategic (closest) | Real accountability issue but needs client agreement. Impact 3 / Ease 3 isn't covered by the four tags; closest is Strategic |
| 8 | DM-O08 | 4 | 3 | 2 | 24 | Strategic | Biggest time sink but large build; do after O06 and O01 data feed |

Ties are broken by Ease, then Impact. Automation beats augmentation for pacing and alerting (DM-O01, DM-O02) because Diya already checks accounts by hand and a budget-only bot (Tina) is the one pacing tool that gets used – a tool that pushes exceptions will stick better than a new routine.

## 7. What's working well

| Strength | Quote + timestamp |
|---|---|
| Clear division of labour: specialists build, manager strategises and optimises | "if it's like a campaign build or something, they will be the ones who will be helping me out." ~06:20 (L080) |
| Team growth has eased her load | "a lot of people joined after me. So that has been really helpful… we are able to, you know, divide it and conquer" ~07:46 (L099) |
| Already using Claude; saves time versus before | "compared to what I previously did, I feel like this is actually saving my time." ~04:00 (L063) |
| Tina's budget pacing is useful as far as it goes | "And we have this Tina thing, so that's also helpful." ~29:48 (L394) |
| Agenda sent before each call keeps WIPs focused | "we sent in like the agenda just before that day, like the call day… makes them give like a quick reminder" ~23:46 (L287) |
| Strategies rarely rejected because a client brief comes first | "before like start working on the strategy part, we normally get like a brief from the client side." ~35:13 (L531) |
| Detailed audit document for new accounts | "We have like a, you know, a very detailed document where it states that, okay, this needs to be looked after" ~41:31 (L628) |
| Ongoing testing rather than a set-and-forget setup | "we will be doing like a lot of tests as well, like not going with a, you know, a single campaign set up for the whole year" ~10:27 (L116) |
| Specialists also own landing-page and creative briefs | "landing page brief and everything. She normally works on that. And even for the creative briefing, she actually, you know, takes care" ~33:43 (L506) |
| Proactive about improvement – arrived with a list of ideas | "I actually had some thoughts on like… Like wild ideas" ~11:49 (L127–L129) |

## 8. Numbers and facts

| Value | Unit | Context | Quote + timestamp | Certainty |
|---|---|---|---|---|
| ~20 | clients | Diya's portfolio | "I have a portfolio of mine, which is like approximately 20 clients" ~04:56 (L072) | stated |
| Mostly Tier 2 & 3 | tier | Her client mix | "For me, most of them are tier two and tier three." ~27:29 (L344) | stated |
| 2 | platforms | Google Ads and Meta | "For me, it's just Google and Meta for now." ~36:54 (L550) | stated |
| 30 | min per client | Monthly AgencyAnalytics commentary (average; smaller clients quicker) | "on average, I would say I put like 30 minutes." ~23:21 (L278) | stated |
| 30 | min per call | Data review before each monthly WIP | "I put like a 30 minutes just before that call to analyze the data" ~21:42 (L257) | stated |
| 20–30 | ads | Per Meta launch reviewed by manager | "there will be like a lot of ads which will be going live for example like 20 to 30 ads" ~18:07 (L217) | stated |
| Fortnightly (weekly for new) | cadence | Diya's pacing checks | "So I do it like fortnightly… sometimes weekly if it's like a new client" ~29:30 (L393) | stated |
| Fortnightly | cadence | Optimisations for newer clients | "for those ones it will be more like a fortnightly one." ~30:10 (L410) | stated |
| 5–6 | clients/day | Worst-case simultaneous requests | "five or six clients come to you on a single day" ~08:41 (L106) | stated |
| First 2 weeks | of month | When monthly WIPs happen | "First two weeks of the month, mostly." ~32:29 (L459) | stated |
| Monthly | cadence | WIP calls per client | "we have like monthly bits that is like the cadence that we follow." ~21:37 (L256) | stated |
| 1 of 2 | specialists | Michaela has own clients; Tati does not | "Mikaela actually has her own clients, but not for Tati." ~07:01 (L087) | stated |
| 0 | service | CRO not offered | "We don't normally do that." ~43:29 (L638) | stated |
| Recent | date | Team fully moved to Monday.com | "as we have completely moved to Monday recently" ~12:15 (L138) | stated |
| ~400 | min/month | 20 clients × 20 min (Austin said 200) | "if you're managing 20 clients, even if it's 20 minutes, that's what 200 minutes." ~23:37 (L284) | estimated (Austin's maths corrected) |
| 65.1–162.5 | h/month | Diya's costed processes (section 2) | – | estimated |
| $5,208–$13,000 | AUD/month | At $80/hr | – | estimated |

## 9. Tools, data and workarounds

- **Official tools:** Google Ads, Meta Ads Manager (build, optimise, change history); AgencyAnalytics (monthly reports and commentary); Monday.com (tasks, briefs to specialists – recently fully adopted); Tina / OpenClaw Slack agent (budget pacing messages); CRM and GA4 (conversion context); strategy document and account-audit document (Google Workspace, assumed); email/video for WIPs.
- **Shadow tools / workarounds:** Claude (manually briefed for audits and analysis – "for a product audit or some very specific items", ~03:53 (L060)); manual per-account performance pacing outside Tina; manual Meta ad-by-ad QA; personal judgement for client prioritisation. Has seen others using the Claude browser extension on platforms (L181) – not using it herself.
- **Same data in several places:** performance data in Google Ads/Meta, GA4, CRM and AgencyAnalytics; pacing in Tina (budget) and in her own checks (performance); change history re-read for both commentary and WIP prep.
- **Data / access she lacks:** single per-client cross-platform view; performance (not just budget) pacing; overdue-task reminders; a clear rule on using Claude with client data. Previous-agency tool Rubii gave her richer pacing.

## 10. Knowledge and dependency

| What | Who (role) | If absent |
|---|---|---|
| Client context for each of ~20 accounts (what converts, budget tolerance, relationship/fee priority) – used for negatives and prioritisation | Diya (PMM) | Cover manager must rebuild context from account history; risk of wrong negatives and missed priorities |
| Monthly commentary and WIP narrative built from her own review of change history | Diya | Reports late or thin; no per-client summary exists to hand over |
| Meta ad QA judgement on specialists' builds | Diya | Format/placement errors could go live |
| Budget pacing message | Tina bot (owner not stated) | Budget pacing visibility drops to manual checks |
| Campaign builds, LP briefs, creative briefs | Michaela Cruz, Tatiana Stinson (2 specialists for the team) | Managers do builds themselves or launches wait |
| AI-data permission | Joe (founder) | Managers stay unsure; either don't use AI or improvise |

## 11a. Clients mentioned

| Client | Tier (context pack) | What was said |
|---|---|---|
| None named | – | Diya named no clients. She described her book as ~20 clients, "most of them are tier two and tier three" (L344), with a mix of lead-generation and e-commerce accounts (L116) |
| Leaselab, White & Co Living, easyAML, AMIGA Montessori | Leaselab Tier 1 (SEO list); others not on the SEO tier list – largest paid budgets under DM in the context pack | Not mentioned in the interview. Listed only to flag the tier contradiction in 11 |
