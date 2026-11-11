# Part A – Transcript extraction: Sophie Hesseborn (Senior Performance Marketing Manager)

**Source and method notes**
- Transcript: meeting notes "Sophie Hesseborn - Workflow & Process Interview", 29 Oct 2026, 11:30 am (Melbourne). Full transcript retrieved (666 utterances, ends at sign-off "Bye.") – not truncated. The AI summary was not used as a source.
- **Timestamps:** the transcript has no timestamps. Every timestamp below is written `~mm:ss (L###)`: L### is the utterance number in `transcript.md`; ~mm:ss is estimated from cumulative word position. Treat as ±2 min.
- **Speakers:** the diariser labelled Austin as A, F, H, I and J and split Sophie across B, C, D, E, G and "unknown". Labels were assigned by content; a few G lines (e.g. L232, L246) are ambiguous. All non-Austin lines are treated as Sophie.
- **Live Figma process mapping:** ran from ~43:00 to ~53:46 (L423–L579). The Figma board itself was not available to this extraction; the processes mapped are reconstructed from what was said while mapping (section 2, "Processes mapped live in Figma"). Austin will send Sophie the completed flow in ~2 weeks (L661).
- **Name and term corrections (transcription):** "Carl" → Karl (L018) · "Wendley" → Wendlley (L350, L585) · "Patty" → Tati (Tatiana Stinson, L481) · "the girls" → Michaela and Tati (L343) · "Metis" → Meta (L241) · "crow" → CRO (L589) · "whips" → WIPs (L552) · "e-compliance" → e-commerce (L110) · "declined comms" → client comms (L326) · "Agents Analytics / Art in Aging" → AgencyAnalytics (L562, L564) · "breathe" → brief (L460) · "to my sessions" → optimisations (L458) · "add cards" → add-to-carts (L302) · "DDG / DGG" → DDEG (assumed, L268–L270). Unresolved: "Alex Mahim" (L388, Austin – probably garbled filler).
- "Tina" (Slack pacing alerts) = the Tina Slack agent bot (OpenClaw), per the pre-audit briefing; Sophie does not name it.
- Hours are costed at **$80/hr internal labour cost**. Process totals are Sophie's own time; Michaela/Tati implementation time is not costed because no figures were given.

---

## 0. Interview card

| Field | Detail |
|---|---|
| Interviewee | Sophie Hesseborn |
| Role | Senior Performance Marketing Manager |
| Team | Performance (paid media) |
| Date | 29 Oct 2026 |
| Interviewer | Austin Smith (Transpera AI) |
| Clients managed | ~12 clients across three tiers – one Tier 1, one "almost Tier 1" Tier 2, rest Tier 2/3 (stated, L316, L320). Fifth month at Aperitif (L070) |
| Channels / services | Google Ads, Meta, Bing/Microsoft, ChatGPT ads, TikTok, Pinterest (per client relevance, L098); onboarding audit and strategy, client comms and WIPs, briefing and QA of implementers, some campaign builds, pacing, optimisation, AgencyAnalytics reporting |
| Reports to | Wendlley Simoes, Performance Marketing Director (context pack – not discussed) |
| Hands work to | Michaela Cruz (Performance Marketing Specialist) and Tati (Tatiana Stinson, Coordinator) – implementation briefs via Monday.com (L038, L472–L474); clients (strategy, findings, approvals, reports); Liam Lau, conversion tracking contractor (troubleshooting, L592) |
| Receives work from | Sales team (handover call, L139–L140); clients (onboarding questionnaire, creative assets, approvals, budget changes); Tina Slack bot pacing alerts (L213); Michaela and Tati (builds and copy back for review, L042) |

## 1. Five-line summary

1. **Budget data lives in three unsynced places** (HubSpot, Monday, pacing Google Sheets); a one-day lag in updating the sheet produces false over/underspend Slack alerts, and every pacing sheet needs manual account IDs, budgets and a new monthly tab of copied formulas. Sophie calls pacing "probably a big pain point" (L198).
2. **Sophie's time goes on strategy, client comms, briefing and ad-copy review, not implementation** (L285–L287). The briefing handoff to Michaela and Tati is the step she most wants faster (L343, L570).
3. **Capacity limit is the 24-hour email response standard**: adding 7–10 clients would push her to comms at the expense of implementing strategy (L334–L335).
4. **Problems are found by manual checks, not alerts**: tracking breaks (often client-side form/page changes) surface only when a performance check shows zero leads over ~7 days, and busy meeting weeks delay that (L583–L584, L610).
5. **Information, not automation, is the theme**: missing sales-handover context (re-asking clients, L133), files historically on personal drives (L067–L071), note-takers that don't turn into actions (L396–L398), and a weekly manual 4-spreadsheet report for one e-commerce client (L301–L303).

## 1a. Time allocation

| Activity | % / hours | Billable? | Quote + timestamp | Certainty |
|---|---|---|---|---|
| Strategy, client comms and briefing (dominant) | Majority – no % given; ≈ 22% optimisation/briefing + 17% email + 21% WIPs of mapped time | Billable (assumed) | "because I'm doing less of the actual implementation, it's more around strategies, client comms, Overall and briefing." ~30:01 (L285) | stated (no number) · % estimated from section 2 midpoints (~94 h/month mapped) |
| Ad copy review and feedback to implementers | Part of the majority above; ≈ 6% with builds/QA | Mostly billable; mentoring non-billable | "the ad copywriting, reviewing the ad copywriting, giving feedback on the copy" ~30:11 (L287) | stated (no number) · % estimated |
| Briefing implementers (Michaela / Tati) | Named as the time-taker; 4–8 h/month (assumed) | Billable (assumed) | "It's the briefing that takes... time in my day." ~53:14 (L570–L571) | stated · hours assumed |
| Client WIPs | 30–45 min each × ~17.7 meetings/month ≈ 8.9–13.3 h/month (≈ 2–3 h/week) | Billable | "And that's between half and for an hour to 45 minute sessions." ~51:40 (L551) | stated (length) · count estimated |
| Pacing and budget checks | ≈ 13% of mapped time (8.7–14.8 h/month) | Billable (assumed) | "And this would be a check across every single platform and channel that the client is on." ~44:16 (L445) | stated (step) · hours estimated |
| Reporting (monthly AgencyAnalytics + weekly e-com sheets) | ≈ 10% (6.3–12.5 h/month) | Billable | "And that's something that we manually do before 11 a.m. every single Monday." ~32:02 (L303) | stated (cadence) · hours assumed |

- **Busy vs quiet:** start of month (pacing check across every account and channel, performance review, optimisation briefs, report commentary) and the mid-month pacing check are the peaks (L434–L445, L491); Monday mornings before 11 am for the e-commerce client's sheets (L303); ad hoc promo campaigns for e-commerce clients run in parallel (L494). Meeting-heavy weeks delay checks (L610). Quiet periods not discussed.
- **Billable vs non-billable:** not discussed. Assumed ~85–90% client-attributable; non-billable = mentoring Michaela/Tati and internal admin. Confirm with timesheets.

## 2. Processes

Flags: ⏸ bottleneck · 👤 single-person dependent · ⌨️ manual copy / re-keying · ⚠️ error-prone. Interviewee = SH. Team = Michaela / Tati.

### Processes mapped live in Figma (~43:00–53:46, L423–L579)
Austin's stated aim: "high-level process flow maps... client communication... strategy... implementation" (L426–L428). What was actually walked through, in order:

1. **Monthly delivery cycle (per client, per channel)** – start-of-month budget/pacing check across every platform → performance check (last 7 / 14 / 30 days) → strategise optimisations → brief Michaela/Tati in Monday → client comms on findings (request creative assets / copy & keyword research → client approval before launch; budget pivots within total = inform only) → proactive recommendations (new channel, budget increase, A/B test) → mid-month pacing check → optimise and brief again → ad hoc promo campaigns in parallel → end of month AgencyAnalytics report commentary → scheduled report send. Maps to SH-P01, SH-P02, SH-P03, SH-P04.
2. **Client meetings (WIPs) cadence** – monthly report walk-through for Tier 2/3; weekly or fortnightly catch-ups on the live dashboard for Tier 1 and new clients. Maps to SH-P06.
3. **Conversion tracking troubleshooting** – added by Sophie as "another thing in between" (L581). Maps to SH-P09.
Earlier in the interview (not mapped on the board but described): onboarding audit & strategy (SH-P08), campaign build and QA (SH-P03), weekly e-com spreadsheets (SH-P05).

---

### SH-P01 · Paid media – pacing & budget management
- **Trigger:** first of the month; mid-month check; Slack pacing alerts (Tina bot, M/W/F); client budget change.
- **Owner role:** Senior Performance Marketing Manager (account owner).
- **Frequency:** 2 formal checks/month per client (start + mid-month) across every channel, ~12 clients (stated: L434–L445, L491, L505); budget changes ad hoc.
- **Tools / files:** pacing Google Sheets (manual account ID, name, budget), HubSpot (management fee + ad spend), Monday.com (management fee + ad spend), ad platforms, Slack alerts.
- **Happy path:**

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Open each ad account; check daily spend vs monthly budget per channel | Senior PMM | Ad platforms, pacing sheet | 15–20 per client (all channels) | – | – | assumed (context pack: 15–20 min/account for Shrishti) |
| 2 | Meta: sum ad-set daily budgets to get account-level daily spend ⌨️ | Senior PMM | Meta Ads Manager | incl. in step 1 | – | – | stated (L292) |
| 3 | Decide pacing adjustment (e.g. 5 days left, $1K left, shift to top campaigns) | Senior PMM | – | incl. in step 1 | – | – | stated (Austin summary L217, agreed L218) |
| 4 | Brief adjustment in Monday or make change (budget change "three clicks") | Senior PMM / Michaela or Tati | Monday, ad platform | 1–2 | until implementer picks up (not stated) | Michaela / Tati | stated (L168), wait assumed |
| 5 | Inform client of pivot (no total change) | Senior PMM | Email | 5–10 | – | Client | stated (L483); time assumed |

- **Happy path total:** 15–20 min touch per client per check (assumed); elapsed same day.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Client changes budget → update in three places ⌨️⚠️ | Client asks to spend more/less | 2–6 per month | Update Monday, HubSpot, pacing sheet (+ platform) | 10–15 min each | Senior PMM | stated (L212–L213); frequency/time assumed |
| False over/underspend alert from stale sheet ⚠️ | Sheet updated a day late | 2–4 per month | Investigate which system is right | 10–20 min each | Senior PMM, team | stated (L213); frequency/time assumed |
| New-month tab and formula duplication ⌨️ | Month start | 1 per month | Copy tab, formulas, budgets | 60–120 min | Whoever owns the sheet | stated (L201); time assumed; may be shared across team |
| Sheet not pulling / bug ⚠️ | Connector failure | not stated | Manual check in platform | covered by step 1 | Team | stated (L199–L200) |
| Meta account-level spend summed weekly ⌨️ | Weekly pacing support | ~4 per month | Add up ad-set budgets | 15–30 min per week (all Meta accounts) | Senior PMM | stated (L291–L295); time assumed |

- **Decision points:** after step 1 – on pace / over / under (split not stated); after step 3 – pivot within total (inform client) vs change total (client approval) (L483, L489) – split not stated.
- **Volume (team):** 61 Google Ads clients + 41 Meta lines (context pack) – team-wide this runs ~120+ times/month at 2 checks per client (estimated).
- **Monthly hours:** happy 12 clients × 2 checks × 15–20 min = 360–480 min = 6.0–8.0 h; bad paths: budget changes 2×10=20 to 6×15=90 min; false alerts 2×10=20 to 4×20=80 min; month rollover 60–120 min; Meta summing 4×15=60 to 4×30=120 min. Total low 360+20+20+60+60 = 520 min = **8.7 h**; high 480+90+80+120+120 = 890 min = **14.8 h** (estimated/assumed).
- **Monthly cost:** 8.7 × $80 = **$696** to 14.8 × $80 = **$1,184**.
- Flags: steps 2 and the three-place update ⌨️⚠️; sheet build/rollover ⌨️.

### SH-P02 · Paid media – optimisation
- **Trigger:** start-of-month and mid-month performance checks; pacing findings; client requests.
- **Owner role:** Senior PMM (strategy and brief); Michaela/Tati implement.
- **Frequency:** ~2 cycles/month per client × ~12 clients, per channel (L450–L452, L493, L505) – stated cadence.
- **Tools / files:** ad platforms (7/14/30-day comparisons), Monday (implementation briefs), email, Google Sheets (approved copy).
- **Happy path:**

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Performance check: last 7 / 14 / 30 days, what's working | Senior PMM | Ad platforms | 20–40 per client | – | – | stated step (L450–L452); time assumed |
| 2 | Strategise optimisations (budget, negatives, geo, PMax signals, creative refresh) | Senior PMM | – | incl. in step 1 | – | – | stated (L228–L229, L458) |
| 3 | Write implementation brief in Monday ⏸👤 | Senior PMM | Monday.com | 10–20 per client | – | Michaela / Tati | stated step (L472–L474); time assumed |
| 4 | Implement change | Michaela / Tati | Ad platforms | not Sophie's time | until picked up – not stated | Senior PMM (review) | stated (L038, L460–L462) |
| 5 | Communicate findings / next steps to client | Senior PMM | Email / WIP | counted in SH-P07 | – | Client | stated (L475–L478) |

- **Happy path total:** 30–60 min touch per client per cycle (assumed); elapsed 1–3 days (assumed).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Creative refresh / new ads need client assets and approval ⏸ | Finding = refresh due | 3–6 per month | Request assets; brief copy/keyword research; send for approval; chase | 20–40 min touch; wait on client (not stated) | Senior PMM, implementers, client | stated (L480–L482); frequency/time assumed |
| High-spend account needs same-day change | Tier/spend | not stated | Reprioritise | not stated | Senior PMM | stated (L514, L518) |

- **Decision points:** after step 2 – small change (budget, negatives) vs new ads/campaigns needing client approval (L481–L483), split not stated; after approval – approved / sent back (not discussed).
- **Volume (team):** every account, every channel, twice a month – ~120+ cycles/month team-wide (estimated from context pack client count).
- **Monthly hours:** happy 12 × 2 × 30–60 min = 720–1,440 min = 12–24 h; bad path 3 × 20 = 60 to 6 × 40 = 240 min = 1–4 h. Total **13–28 h** (assumed).
- **Monthly cost:** 13 × $80 = **$1,040** to 28 × $80 = **$2,240**.
- Flags: step 3 briefing ⏸👤 (Sophie is the bottleneck for her own and others' implementers).

### SH-P03 · Paid media – campaign build (incl. QA and copy review)
- **Trigger:** new campaign, new service line (e.g. DDEG), creative refresh, onboarding build.
- **Owner role:** Senior PMM builds some; Michaela/Tati build others; Senior PMM reviews all.
- **Frequency:** not stated; "for many clients I built ads" (L034). Assumed 2–4 own builds + 4–8 reviews per month.
- **Tools / files:** Google Ads Editor and Bing bulk editor (import builds), Meta Ads Manager (manual), approved copy spreadsheets, landing pages, creative assets (client-supplied or produced by tier).
- **Happy path:**

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Research + ad copy / headline variations (+ keyword research for Google) | Senior PMM / implementers | Claude, Sheets | not stated | – | Client (approval) | stated (L270, L281) |
| 2 | Source assets: landing page or website URL, imagery, video; tier decides who produces ⏸ | Senior PMM / client | Drive, Canva | not stated | Wait on client assets – not stated | – | stated (L095, L281) |
| 3 | Build: Google/Bing via editor import; Meta manually ⌨️ | Senior PMM or implementer | Ads Editor, Meta | Meta 45–60 (complex), 10–30 (simple) | – | Senior PMM (QA) | stated (L249, L258, L262–L264) |
| 4 | Turn off Meta auto-on AI enhancements ⚠️ | Builder | Meta | incl. in step 3 | – | – | stated (L173–L177) |
| 5 | QA vs approved spreadsheet: URLs per region (AU/NZ), copy, offer thresholds ($150 vs $170 free shipping) ⚠️ | Senior PMM | Sheets, platform | 15–30 per review | – | Implementer (feedback) | stated (L179–L181); time assumed |
| 6 | Feedback / mentoring on copy and build | Senior PMM | Slack/Monday | incl. in step 5 | – | Michaela / Tati | stated (L042) |

- **Happy path total:** own Meta build 45–60 min (stated) or 10–30 min simple; QA 15–30 min per review (assumed); elapsed days to weeks depending on assets (not stated).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Platform glitches during Meta build | Meta bugs | 1–2 per month | Re-check settings | 15–30 min | Builder | stated (L260); rate/time assumed |
| Instant form + conversion tracking needed | Lead-gen funnel | not stated | Build form, check fields, tracking | not stated | Builder, Liam | stated (L266–L267) |

- **Decision points:** Google/Bing (bulk import) vs Meta (manual) (L239–L241); client supplies vs agency produces creative, by tier (L095); landing page vs website (L281). Splits not stated.
- **Volume (team):** not stated.
- **Monthly hours:** own builds 2 × 30 = 60 to 4 × 60 = 240 min (1–4 h); reviews 4 × 15 = 60 to 8 × 30 = 240 min (1–4 h); glitches 1 × 15 = 15 to 2 × 30 = 60 min (0.25–1 h). Total **2.3–9.0 h** (assumed).
- **Monthly cost:** 2.3 × $80 = **$184** to 9.0 × $80 = **$720**.

### SH-P04 · Monthly reporting
- **Trigger:** month end.
- **Owner role:** Senior PMM.
- **Frequency:** monthly, ~12 clients (stated cadence, L521–L530).
- **Tools / files:** AgencyAnalytics (dashboard widgets, scheduled report); replaced the old running sheet (L525–L529).
- **Happy path:**

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Check report shows last month's data (date range) ⚠️ | Senior PMM | AgencyAnalytics | 5–10 | – | – | stated (L538–L539); time assumed |
| 2 | Write last-page commentary: done this month, next month, pivots | Senior PMM | AgencyAnalytics | 10–20 | – | – | stated (L524); time assumed |
| 3 | Scheduled send at start of month | System | AgencyAnalytics | 0 | – | Client | stated (L530–L533) |

- **Happy path total:** 15–30 min per client (assumed); elapsed: sends on schedule.
- **Bad paths:** wrong date range shown – frequency not stated (L539).
- **Decision points:** none stated.
- **Volume (team):** ~61 paid clients/month (context pack) – estimated.
- **Monthly hours:** 12 × 15–30 min = 180–360 min = **3–6 h** (assumed).
- **Monthly cost:** **$240–$480**.

### SH-P05 · NEW: Weekly client KPI spreadsheet update (e-commerce client)
- **Trigger:** every Monday, due before the client's 11 am finance/leadership meeting (L303–L306).
- **Owner role:** Senior PMM ("we" – may be shared with Michaela/Tati; confirm).
- **Frequency:** weekly, 1 client (~4.33/month) – stated.
- **Tools / files:** four client Google Sheets; Meta/Google platforms.
- **Happy path:**

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Pull daily and weekly spend, clicks, LPVs, frequency, add-to-carts, purchases, CTR, CPC ⌨️ | Senior PMM | Ad platforms → 4 sheets | 30–60 | – | – | stated (L301–L302); time assumed |
| 2 | Write commentary: last 7 days, plans and priorities this week | Senior PMM | Sheets | 15–30 | – | Client | stated (L306–L308); time assumed |

- **Happy path total:** 45–90 min (assumed); hard deadline 11 am Monday ⏸.
- **Bad paths:** not discussed.
- **Decision points:** none.
- **Monthly hours:** 4.33 × 45–90 min = 195–390 min = **3.3–6.5 h** (assumed).
- **Monthly cost:** 3.3 × $80 = **$264** to 6.5 × $80 = **$520**.
- Flags: step 1 ⌨️ (manual re-keying into four sheets).

### SH-P06 · Client meetings & prep (WIPs)
- **Trigger:** cadence by tier – monthly report review (Tier 2/3), fortnightly or weekly (Tier 1), fortnightly for new clients in month one (L553–L555).
- **Owner role:** Senior PMM.
- **Frequency:** stated: 1 weekly client, "a couple" fortnightly; others monthly. Estimated 1 × 4.33 + 2 × 2.17 + 9 × 1 ≈ 17.7 meetings/month.
- **Tools / files:** AgencyAnalytics live dashboard and monthly report; note-takers (tried, L396).
- **Happy path:**

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Prep: review recent notes, historic conversations, dashboard ⌨️ | Senior PMM | Notes, AgencyAnalytics | 15–45 | – | – | assumed (Sophie gave no figure; context pack has 1h15 for Shrishti) |
| 2 | Run WIP | Senior PMM | Video call, dashboard | 30–45 | – | Client | stated (L551) |
| 3 | Extract actions from notes and convey them ⚠️ | Senior PMM | Note-taker output, Monday | incl. in step 1 | – | Michaela / Tati | stated (L396–L398) |

- **Happy path total:** 45–90 min per meeting (estimated).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Missed client interest/follow-up (e.g. ChatGPT ads curiosity) | Notes not reviewed | not stated | Recover later | not stated | Client relationship | stated (L385–L391) |

- **Decision points:** cadence set by tier and client age (L554–L555).
- **Monthly hours:** meetings 17.7 × 30–45 min = 531–797 min = 8.9–13.3 h; prep 17.7 × 15–45 = 266–797 min = 4.4–13.3 h. Total **13.2–26.6 h** (estimated/assumed).
- **Monthly cost:** 13.2 × $80 = **$1,056** to 26.6 × $80 = **$2,128**.

### SH-P07 · NEW: Client email & ad hoc communication
- **Trigger:** client emails; findings to share; approvals; proactive ideas (new channel, budget increase, A/B tests) (L489).
- **Owner role:** Senior PMM. Agency standard: reply within 24 hours (L327).
- **Frequency:** daily – stated as a dominant activity (L285); volume not stated.
- **Tools / files:** email.
- **Happy path:** read → acknowledge within 24 h ("Thanks for the information. We will look into it", L330) → action or brief → follow up. Touch 30–60 min/day (assumed), 21 working days.
- **Bad paths:** comms crowd out strategy implementation when portfolio grows (L334–L335) – not quantified.
- **Decision points:** acknowledge now vs action now (L330).
- **Monthly hours:** 21 × 30–60 min = 630–1,260 min = **10.5–21 h** (assumed – confirm with Sophie).
- **Monthly cost:** **$840–$1,680**.

### SH-P08 · Client onboarding – audit & strategy (incl. sales handover)
- **Trigger:** new client handed over from sales.
- **Owner role:** Senior PMM.
- **Frequency:** not stated; she "recently" gained one Tier 1 client (L320). Assumed 0.5–1 per month.
- **Tools / files:** ad accounts, GA4, audit document + roadmap checklist (L054), onboarding questionnaire (L058), competitor ad libraries (L117), Claude (no standard prompt, L124), shared Google Drive client folder (L065–L066), HubSpot (handover data – not checked, L141).
- **Happy path:**

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Sales handover one-on-one call | Sales → Senior PMM | Call, HubSpot | 30–60 | – | – | stated (L139–L140); time assumed |
| 2 | Gain ad-account access ⏸ | Client | Platforms | – | not stated | – | stated (L052) |
| 3 | Audit each channel: setup, targeting, audiences, search terms, creative, budgets/spend | Senior PMM | Platforms, audit checklist | 120–300 | – | – | stated (L090–L094); time assumed |
| 4 | Audit conversion tracking and GA4 | Senior PMM (+ Liam) | GA4, platforms | 30–60 | – | Liam if broken | stated (L096–L097); time assumed |
| 5 | Research: competitors (ad libraries), market, geo, economics, personas | Senior PMM | Ad libraries, Claude | 60–180 | – | – | stated (L104–L106, L117–L118, L124); time assumed |
| 6 | Kickoff call to fill questionnaire gaps; build on client personas | Senior PMM | Call | 30–60 | wait on client | – | stated (L645–L651); time assumed |
| 7 | Strategy and roadmap; file in client Drive folder | Senior PMM | Drive | 90–180 | – | Client | stated (L054, L066); time assumed |

- **Happy path total:** ~6–12 h touch (sum of 360–840 min ≈ 6–14 h; use 6–12 h – assumed); elapsed not stated (context pack: ≥1 week after access).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Sales context missing → re-ask client | Handover gaps | most onboardings ("hasn't been like the optimal transition") | Re-ask questions, ask sales | 30–60 min | Client, Senior PMM | stated (L133, L137); time assumed |
| Brand-new account – no history to audit | New advertiser | not stated | More research | not stated | Senior PMM | stated (L091) |
| Handed an existing client – files on personal drives | Internal handover | not stated | Search for documents | not stated | Senior PMM | stated (L067–L071) |

- **Decision points:** new vs existing ad account (L091); landing page vs website (L095); who produces creative (tier) (L095); which channels (L098).
- **Monthly hours:** 0.5 × 6 h + 0.5 × 0.5 h = 3.25 h to 1 × 12 h + 1 × 1 h = 13 h → **3.3–13 h** (assumed).
- **Monthly cost:** 3.3 × $80 = **$264** to 13 × $80 = **$1,040**.

### SH-P09 · Performance monitoring & alerting (conversion-tracking troubleshooting)
- **Trigger:** performance check shows no leads from a landing page/form (L583–L584).
- **Owner role:** Senior PMM; Liam Lau (conversion/CRO tracking contractor, analytics@aperitif.agency) looped in (L592, L599) 👤.
- **Frequency:** not stated. Assumed 1–3 incidents/month.
- **Happy path:**

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Notice zero leads in last 7 days during performance check ⏸ | Senior PMM | Platforms, GA4 | – | up to ~7 days undetected | – | stated (L583–L584) |
| 2 | Diagnose: client changed page/form/form ID? | Senior PMM | Site, GA4 | 15–45 | – | Liam if needed 👤 | stated (L584); time assumed |
| 3 | Fix back end / ask client to notify changes | Senior PMM / Liam | GTM/platform | 15–45 | wait on Liam – not stated | Client | stated (L584, L592); time assumed |

- **Happy path total:** 30–90 min touch per incident (assumed); elapsed up to a week+ (stated "seven days").
- **Bad paths:** busy meeting week delays review → issue found too late → unhappy client (L610) – frequency not stated.
- **Decision points:** client-side change vs agency-side fault (L584) – split not stated.
- **Monthly hours:** 1 × 30 = 30 to 3 × 90 = 270 min = **0.5–4.5 h** (assumed).
- **Monthly cost:** **$40–$360**.

### Process totals

| ID | Process | Monthly hours (all actors) | SH-only hours | Monthly cost (all actors) |
|---|---|---|---|---|
| SH-P01 | Paid media – pacing & budget management | 8.7–14.8 | 8.7–14.8 | $696–$1,184 |
| SH-P02 | Paid media – optimisation | 13.0–28.0 | 13.0–28.0 | $1,040–$2,240 |
| SH-P03 | Paid media – campaign build (incl. QA and copy review) | 2.3–9.0 | 2.3–9.0 | $184–$720 |
| SH-P04 | Monthly reporting | 3.0–6.0 | 3.0–6.0 | $240–$480 |
| SH-P05 | NEW: Weekly client KPI spreadsheet update | 3.3–6.5 | 3.3–6.5 | $264–$520 |
| SH-P06 | Client meetings & prep | 13.2–26.6 | 13.2–26.6 | $1,056–$2,128 |
| SH-P07 | NEW: Client email & ad hoc communication | 10.5–21.0 | 10.5–21.0 | $840–$1,680 |
| SH-P08 | Client onboarding – audit & strategy | 3.3–13.0 | 3.3–13.0 | $264–$1,040 |
| SH-P09 | Performance monitoring & alerting | 0.5–4.5 | 0.5–4.5 | $40–$360 |
| **Total** | | **57.8–129.4 h** | **57.8–129.4 h** | **$4,624–$10,352** |

"All actors" equals SH-only here: Michaela/Tati implementation (SH-P02 step 4, SH-P03 builds) and Liam's tracking time were not described in minutes, so they are not costed. Most times are assumed – Sophie gave only three time figures (Meta build 45–60 min, budget change "three clicks", WIPs 30–45 min). The high end (~129 h) is below one full-time month (~152–160 h) but leaves little room for internal work; treat the low-to-mid range as more realistic and confirm with calendar and timesheet data.

## 3. Pain points and problems

| ID | Pain point (one line) | Source | Category | Anchor | Process | Impact | How often | Severity 1–5 | Quote + timestamp | Certainty |
|---|---|---|---|---|---|---|---|---|---|---|
| SH-PP01 | Budget and fee data held separately in HubSpot, Monday and pacing sheets; every change re-keyed in three places | interviewee | Duplicate data entry | Performance visibility & margin | Paid media – pacing & budget management | time + overspend risk | every budget change | 4 | "I'll update it on Monday I'll make sure it's reflected in HubSpot and then the pacing sheet" ~22:33 (L213) | stated |
| SH-PP02 | Pacing sheets need manual account ID, name and budget input and often don't pull correctly | interviewee | Manual / repetitive work | Technology, AI & stack | Paid media – pacing & budget management | time, wrong data | ongoing | 4 | "we have to manually input like the ad account ID and the name and the budgets. And then it's not always pulling correctly." ~20:46 (L198–L199) | stated |
| SH-PP03 | New month means duplicating formulas to a new tab by hand | interviewee | Manual / repetitive work | Operations capacity & process | Paid media – pacing & budget management | 1–2 h/month (assumed) | monthly | 3 | "It would be duplicating the formulas and whatnot to a new tab and then creating that one. And it's a lot of manual work." ~21:32 (L201) | stated (time assumed) |
| SH-PP04 | Stale sheet triggers false over/underspend Slack alerts | interviewee | Rework / errors | Performance visibility & margin | Paid media – pacing & budget management | time, alert fatigue | after each lagged update | 3 | "the Slack message will say like, oh, it's under, overspending but I know that the new budget is increased so the overspend is not true" ~22:33 (L213) | stated |
| SH-PP05 | Meta account-level daily spend must be summed by hand from ad sets | interviewee | Manual / repetitive work | Technology, AI & stack | Paid media – pacing & budget management | 1–2 h/month (assumed) | weekly | 2 | "if it's in ad set level you have to like go in and just like summarize just add everything up." ~30:53 (L292) | stated |
| SH-PP06 | One e-com client needs four spreadsheets updated by hand before 11 am every Monday | interviewee | Manual / repetitive work | Client experience & delivery | NEW: Weekly client KPI spreadsheet update | 3.3–6.5 h/month (assumed) | weekly | 3 | "And that's something that we manually do before 11 a.m. every single Monday." ~32:02 (L303) | stated |
| SH-PP07 | Sales handover context not passed on or findable – client re-asked questions | interviewee | Waiting / handoff delay | Growth & sales engine | Sales to delivery handover | client friction, weaker strategy base | most onboardings | 3 | "So we're like re-asking questions. And ideally, it would be nice to find that information somewhere." ~14:56 (L133) | stated |
| SH-PP08 | Client documents historically on personal drives – hard to find on handover; no standard storage | interviewee | Single point of failure (person) | Leadership & dependency | Knowledge & SOPs | time on handover, continuity risk | each handover | 3 | "I noticed that when I was being handed over clients to me, I was Just like trying to find documents." ~06:52 (L071) | stated |
| SH-PP09 | 24-hour email standard means comms crowd out strategy implementation as the portfolio grows | interviewee (answering Austin's 7–10 more clients hypothetical) | Capacity / overload | Operations capacity & process | NEW: Client email & ad hoc communication | strategy delayed; caps clients per manager | when portfolio grows | 4 | "Based on the 24-hour turnaround time, I would have to focus on the comms, which then... would lead to not implementing the strategies." ~34:59 (L334–L335) | stated |
| SH-PP10 | Briefing optimisations to Michaela/Tati is slow and manual; the step she most wants sped up | interviewee | Waiting / handoff delay | Operations capacity & process | Paid media – optimisation | 4–8 h/month briefing (assumed) | twice monthly per client | 3 | "If there's like a speedy way of like getting that brief to the girls." ~35:33 (L343) | stated |
| SH-PP11 | Tracking breaks (often unannounced client page/form changes) found only via manual performance checks, up to ~7 days later | interviewee | Missing visibility | Performance visibility & margin | Performance monitoring & alerting | wasted spend, lost leads | not stated | 4 | "it could potentially be that the client made changes on the landing page or website themselves and didn't tell us" ~54:10 (L584) | stated |
| SH-PP12 | Meeting-heavy weeks delay checks; tracking issue discovered too late, client unhappy | interviewee | Capacity / overload | Client experience & delivery | Performance monitoring & alerting | client friction | busy weeks | 3 | "you might not have the chance to review it as quickly as you would have wanted to and then discovered the tracking issue too late" ~56:00 (L610) | stated |
| SH-PP13 | Note-takers capture meetings but actions and talking points still have to be extracted by hand; risk of missing client interests | interviewee (after Austin prompted, L371–L381) | Tool not used / adoption | Client experience & delivery | Client meetings & prep | prep time; missed follow-ups | every meeting | 3 | "we tried to add like note takers to meetings. But then it's like from those notes. taking the actions, conveying the" ~40:37 (L396–L398) | stated |
| SH-PP14 | No standard research prompt for strategy; AI use is ad hoc | interviewee | Tool not used / adoption | Technology, AI & stack | Client onboarding – audit & strategy | inconsistent research time | each strategy | 2 | "It would be like now with Claude and stuff and generating report, but I don't have like a go-to prompt" ~13:41 (L124) | stated |
| SH-PP15 | Meta auto-enables new AI features; every build needs a manual toggle-off check | interviewee | Rework / errors | Performance visibility & margin | Paid media – campaign build | wasted spend risk | every Meta build | 2 | "meta rolls out new things and it's like auto on and then you just have to be like super into the nitty gritty" ~18:26 (L177) | stated |
| SH-PP16 | Monthly report still needs manual commentary and a check that it shows the right month | interviewee | Manual / repetitive work | Client experience & delivery | Monthly reporting | 3–6 h/month (assumed) | monthly | 2 | "It's just a manual task to update the last page of what we worked on and just ensuring that the data is reflected last month" ~50:51 (L538) | stated |
| SH-PP17 | Meta builds are manual (no bulk import like Google/Bing editors) | interviewee | Manual / repetitive work | Technology, AI & stack | Paid media – campaign build | 45–60 min per complex build | per build | 2 | "The Google implementation is quicker because there's like this editor tool that can be used to like import an account build." ~25:43 (L239) | stated |

**Top 3 by severity – root cause and match**

1. **SH-PP01 / SH-PP02 Budgets in three places; manual pacing sheets (4).** Why are budgets re-keyed? They live separately in HubSpot, Monday and the pacing sheets. Why? No system is designated the budget master and nothing syncs them. Why? Pacing was built as sheets with a (now lapsed) Supermetrics pull, and Monday/HubSpot were added later for other purposes. **Root cause:** no single source of truth for client budgets and no maintained integration. **Matches:** "Budgets maintained by hand in three places; LinkedIn not tracked → $10K overspend" and "Meta pacing sheet is broken – Supermetrics connector failing". Note Sophie's three places are HubSpot / Monday / pacing sheet (context pack: budget sheet / pacing sheet / platforms).
2. **SH-PP09 Comms crowd out strategy (4).** Why? The 24-hour response standard is answered personally by the account manager. Why? There is no triage or acknowledgement support, and briefs to implementers are slow (SH-PP10). **Root cause:** the account manager carries comms, strategy and briefing with no leverage on the brief step. **Matches:** "Managers at capacity – Tier 2/3 clients get dropped first".
3. **SH-PP11 Tracking breaks found late (4).** Why? They are only detected in scheduled performance checks. Why? There is no automated conversion-volume or site-change monitoring, and clients don't tell the agency about form changes. **Root cause:** no proactive alerting. **Matches:** "No proactive performance alerting – problems found at month-end"; also supports "Conversion tracking depends on one contractor".

## 4. Bottlenecks

| ID | Step | Waiting on | Typical wait | Affected | Knock-on |
|---|---|---|---|---|---|
| SH-B01 | Optimisation briefs to implementers (SH-P02 step 3) | Sophie's time to write briefs | not stated | ~12 clients × 2 cycles/month | Implementation lags; comms take priority (L334–L343) |
| SH-B02 | New ads / creative refresh launch (SH-P02 bad path, SH-P03 step 2) | Client to supply assets and approve | not stated | Clients needing new creative/campaigns | Campaign refresh delayed; tier determines who produces creative |
| SH-B03 | Pacing sheet update after budget change (SH-P01) | Manual update in three systems | ≥1 day lag (stated example) | Any client changing budget | False Slack alerts; mismatch between Monday/HubSpot/sheet |
| SH-B04 | Tracking-break detection (SH-P09 step 1) | Next manual performance check | up to ~7 days (stated) | Lead-gen clients | Lost leads, wasted spend, unhappy client (L610) |
| SH-B05 | Monday 11 am e-com sheets (SH-P05) | Manual data entry before deadline | hard deadline weekly | 1 client | Monday mornings consumed |
| SH-B06 | Strategy start (SH-P08) | Sales context / client re-answering questions | not stated | Each new client | Weaker starting strategy, client repeats themselves |

## 4a. Decisions and approvals

| Decision | Who decides (role) | Who waits | Typical time | Lands on leadership? |
|---|---|---|---|---|
| Launch new campaigns / ads / copy | Client approves | Senior PMM, implementers | not stated | No |
| Budget pivot within agreed total | Senior PMM (client informed) | – | same day | No |
| Change total monthly budget / add channel | Client | Senior PMM | not stated | No |
| In-platform budget change after pacing alert | Senior PMM (human) – Sophie wants this kept human (L219) | Implementers | not stated | No |
| Who produces creative | Set by client tier | – | – | No |
| Turnaround priority | Tier / ad spend (L514, L518) | – | – | No |
| Tracking fix | Senior PMM + Liam (contractor) | Client | not stated | No – but depends on one contractor |

No decision in this transcript was described as landing on Julia, Wendlley or Joe.

## 5. Suggestions for change (as raised in the interview)

| ID | Idea | Source + reaction | Process | Quote + timestamp |
|---|---|---|---|---|
| SH-S01 | All client documents accessible via Monday (link client Drive folder to Monday item) | interviewee | Knowledge & SOPs | "In a dream scenario, we would have everything with easy access through Monday." ~07:06 (L075) |
| SH-S02 | Sales hands over prior conversation info with the client | interviewee | Sales to delivery handover | "when a performance manager gets handed over the client from the sales team, we would also receive a lot of previous information that sales have had" ~14:41 (L132) |
| SH-S03 | Pacing alert auto-creates a Monday implementation task; budget change stays human | interviewee | Paid media – pacing & budget management | "something automatically is created in Monday which is a task, to implement this" ~23:58 (L219) |
| SH-S04 | Synchronise budget data across HubSpot, Monday and pacing sheet | interviewer (Austin: "that's an easy fix", L216) – interviewee described the pain | Paid media – pacing & budget management | "Okay, that's an easy fix. So we can definitely fix that." ~23:23 (L216) |
| SH-S05 | Weekly total account-level daily spend (esp. Meta) | interviewee | Paid media – pacing & budget management | "weekly basis to be like, "Oh, what's the total daily spend in the accounts?" It will support the pacing." ~31:10 (L295) |
| SH-S06 | Automate the Monday e-com spreadsheet update | interviewee | NEW: Weekly client KPI spreadsheet update | "And automating it in a way like that would be Fantastic." ~32:40 (L312) |
| SH-S07 | Faster way to get briefs to Michaela/Tati | interviewee | Paid media – optimisation | "If there's like a speedy way of like getting that brief to the girls." ~35:33 (L343) |
| SH-S08 | Data-informed pre-drafted client emails to approve/edit | interviewer – interviewee lukewarm ("Probably. But I'm thinking like in what capacity?", L373–L374) | NEW: Client email & ad hoc communication | "automatically generates an email that's already like data informed and you just have to approve it or edit it" ~37:38 (L371) |
| SH-S09 | Automated latest-notes summary with talking points and historic conversation review | interviewee (after interviewer prompt about contact notes, L378–L381) | Client meetings & prep | "It's more like an automated, like latest notes summary, maybe something like that." ~39:13 (L382) |
| SH-S10 | Bot that scans client websites and alerts on changes | interviewer – interviewee agreed ("That's really good.", L602) | Performance monitoring & alerting | "we can create a bot that... that can proactively scan and monitor clients' websites." ~55:29 (L600–L601) |
| SH-S11 | Keep report commentary human | interviewer – interviewee agreed ("Yeah", L541) | Monthly reporting | "I feel as if you want to keep that pretty human anyway, because that's the relationship." ~51:06 (L540) |

## 6. Opportunity assessment

| ID | Fixes | Lens | What changes | Matches existing solution idea | Existing tool | Hours saved / month (maths) | Effort | Prerequisites | Adoption risk | COI flag |
|---|---|---|---|---|---|---|---|---|---|---|
| SH-O01 | SH-PP01, PP02, PP03, PP04, PP05, SH-B03 | Automate | One budget master (Monday client item); budgets sync to HubSpot and pacing sheet; account-level spend pulled automatically for all channels incl. Meta; monthly tab auto-rolls | Pacing tracker & adjustment engine | Make.com (already used) + Google Ads/Meta APIs or a connector (Supermetrics renewal, Windsor.ai, Porter); Google Ads scripts | Removes bad paths (0.3+0.3+1+1 = 2.7 to 1.5+1.3+2+2 = 6.8 h) + 20–30% of happy-path checking (6–8 h × 0.2–0.3 = 1.2–2.4 h) = **3.9–9.2 h** (Sophie only; team-wide far larger) | M | Decide budget master system and owner; API access for all ad accounts; connector budget | L – removes work, no new behaviour beyond entering budget once | Yes – Transpera could build |
| SH-O02 | SH-PP04, PP10, SH-B01 | Augment | Over/under-pacing alert creates a Monday task with account, gap and suggested reallocation; Sophie approves; implementer actions in platform | Pacing tracker & adjustment engine | Monday automations + Make.com + Slack bot (Tina) | Pacing-related briefs: ~6–12/month × 5–10 min = 0.5–2 h | M | SH-O01 data must be reliable first | M – alert noise could erode trust if data is wrong | Yes |
| SH-O03 | SH-PP06, SH-B05 | Automate | Data columns in the four client sheets auto-filled each Monday from Meta/Google; Sophie writes commentary only. Alternative (Change the process): ask client to accept a live AgencyAnalytics/Looker dashboard | New | Supermetrics / Looker Studio / AgencyAnalytics export to Sheets | Data entry 60–75% of 3.3–6.5 h = **2.0–4.9 h** | S | Sheet structure from client; connector access | L | Possibly (simple connector – likely off the shelf) |
| SH-O04 | SH-PP10, PP09, SH-B01 | Augment | Standard Monday brief template (account, change, why, deadline, QA check) + AI drafts brief from Sophie's findings or voice note; she reviews and sends | Brief & proposal generator (closest) | Monday forms/templates; Claude | Briefing 4–8 h × 25–50% = **1–4 h** | S | Agree brief template with Michaela/Tati | L – Sophie asked for it | Possibly |
| SH-O05 | SH-PP13, PP09 | Augment | Before each WIP, auto-generate per-client summary: last call actions, open items, client interests ("curious about ChatGPT ads"), recent performance | Client-call prep summaries; transcripts → per-client action runsheet | Otter/Gemini notes (already licensed) + Claude; Monday client item | Prep 4.4–13.3 h × 30–50% = **1.3–6.7 h** | M | Note-taker used consistently in client calls; per-client notes location | H – note-takers "rarely used" by team; automate capture rather than rely on habit | Yes |
| SH-O06 | SH-PP11, PP12, SH-B04 | Automate | Daily conversion-volume anomaly check per form/landing page (zero leads vs baseline) + page/form change monitor; alert account owner and Liam | Proactive PPC anomaly monitor | Google Ads/GA4 custom alerts, Looker Studio, Make.com; uptime/page-change monitors (e.g. Visualping) | Troubleshooting 0.5–4.5 h × 50% = **0.25–2.3 h**; main value is detection days cut from ~7 to ~1 | M | Baselines per conversion action; GA4 access for all clients | L – passive alerts | Yes – Austin offered to build (L600) |
| SH-O07 | SH-PP07, SH-B06 | Change the process | Mandatory handover fields in HubSpot deal (goals, budget, competitors, call notes, objections) pushed to Monday client item via existing Make.com flow; onboarding questionnaire pre-filled | New (relates to AI business brain) | HubSpot + Make.com + Monday (existing) | Re-asking: 0.5–1 onboarding × 0.5–1 h = **0.25–1 h** | S | Sales agrees fields; Jethro (Growth Strategy Lead) ownership | M – depends on sales filling it in | No – process/config |
| SH-O08 | SH-PP08 | Change the process | Standard client folder structure in shared Drive, linked from each Monday client item; move files off personal drives | New (supports "Client work files are owned by individual staff accounts") | Google Drive + Monday link column | Handover search: assumed **0.5–1 h**; larger value is continuity when staff leave | S | Folder template; owner to migrate | L | No |

**KPIs**

| Opportunity ID | KPI | How measured | Baseline today | Target | Leading / lagging |
|---|---|---|---|---|---|
| SH-O01 | Systems updated per budget change | Process audit / Monday log | 3 ("Monday… HubSpot and then the pacing sheet", L213) | 1 | Leading |
| SH-O01 | False pacing alerts per month | Slack alert log vs actual | unknown (stated as occurring, L213) | 0–1 | Lagging |
| SH-O02 | Time from pacing alert to in-platform change | Monday task timestamps | unknown | under 1 business day (same day for high spend) | Leading |
| SH-O03 | Minutes to complete Monday e-com update | Self-timed | unknown (manual, "before 11 a.m. every single Monday", L303) | ≤ 20 min (commentary only) | Leading |
| SH-O04 | Minutes per implementation brief | Self-timed / Monday | unknown ("briefing that takes... time in my day", L570) | –30–50% | Leading |
| SH-O04 | Brief-to-implemented cycle time | Monday task created → done | unknown | –30% | Lagging |
| SH-O05 | Prep minutes per WIP | Self-timed | unknown (Sophie gave none; Shrishti ~75 min per context pack) | ≤ 15 min | Leading |
| SH-O05 | Missed follow-ups raised by client | Client feedback / WIP notes | unknown | 0 | Lagging |
| SH-O06 | Days from tracking break to detection | Alert timestamp vs break date | up to ~7 days ("in the last seven days", L584) | ≤ 1 day | Lagging |
| SH-O07 | Onboarding questions re-asked of client | Kickoff call checklist | unknown ("we're like re-asking questions", L133) | 0 on fields captured by sales | Leading |
| SH-O08 | % client folders in shared Drive and linked from Monday | Drive / Monday audit | unknown | 100% | Leading |

**Indicative ranking** (priority = Impact × Confidence × Ease)

| Rank | ID | Impact | Confidence | Ease | Priority | Tag | Reason |
|---|---|---|---|---|---|---|---|
| 1 | SH-O03 | 3 | 4 | 4 | 48 | Quick win | Stated weekly manual task with a hard 11 am deadline; off-the-shelf connector |
| 2 | SH-O01 | 4 | 4 | 3 | 48 | Strategic | Clearest repeated pain; matches the two critical pacing problems; benefit multiplies across 61+ accounts |
| 3 | SH-O04 | 3 | 3 | 4 | 36 | Quick win | Sophie's own ask; a brief template is cheap |
| 4 | SH-O08 | 3 | 3 | 4 | 36 | Quick win | Low effort; agency-wide continuity risk (files on personal drives) |
| 5 | SH-O06 | 4 | 3 | 3 | 36 | Strategic | Protects spend and leads; Austin proposed, Sophie agreed; frequency not stated |
| 6 | SH-O05 | 3 | 3 | 3 | 27 | Strategic (closest – Impact 3 / Ease 3 isn't covered by the four tags) | Sophie wants it, but prep time not quantified; note-taker adoption risk high |
| 7 | SH-O02 | 3 | 3 | 3 | 27 | Strategic (closest – Impact 3 / Ease 3 isn't covered) | Sophie's idea; depends on SH-O01 data being reliable |
| 8 | SH-O07 | 2 | 3 | 4 | 24 | Fill-in | Small hours for Sophie; depends on sales filling it in |

Ties are broken by Ease, then Impact (same rule as the Shrishti extraction). Automation beats augmentation for pacing (SH-O01), the weekly sheets (SH-O03) and tracking alerts (SH-O06) because these are pure copy/paste or threshold checks, and manual habits haven't stuck (sheets updated a day late, note-takers not turned into actions).

## 7. What's working well

| Strength | Quote + timestamp |
|---|---|
| AgencyAnalytics has replaced the manual running sheet; monthly reports are scheduled automatically | "So Agency Analytics is taking that away. And we're scheduling this report to be sent at the start." ~50:38 (L529–L530) |
| Shared Google Drive with a folder per client | "And then we have a shared Google Drive for all our clients." ~06:08 (L065) |
| Structured onboarding: audit document/roadmap checklist and onboarding questionnaire | "we have this audit document and roadmap that we usually follow just as like a little checklist." ~05:21 (L054) |
| Strong client relationships; churn mostly macroeconomic | "I feel like I've built really good relationships with my clients as well." ~36:37 (L355) |
| Clients value the strategy work | "And they value our strategies a lot as well." ~17:04 (L160) |
| Rigorous QA against approved copy (regional URLs, offer thresholds) | "free shipping has a $150 threshold here, it has a $170 threshold here. Is that conveyed in the ad copy?" ~18:50 (L179) |
| Tier/spend-based prioritisation of turnaround | "If it's like a high spending ad account, we don't want to waste any budget. So we want to make changes swiftly" ~49:17 (L518) |
| Google/Bing bulk-editor builds are quick | "there's like this editor tool that can be used to like import an account build. And same for Bing." ~25:43 (L239–L240) |
| Sales team available for questions at handover | "they might know a bunch of questions because they've had previous chats with the prospects." ~15:48 (L149) |
| Clear access to a tracking specialist | "So if something is, if I'm troubleshooting something, I loop him in." ~55:14 (L592) |

## 8. Numbers and facts

| Value | Unit | Context | Quote + timestamp | Certainty |
|---|---|---|---|---|
| ~12 | clients | Sophie's current portfolio | "Maybe like 12." ~32:56 (L316) | stated |
| 3 | tiers | Portfolio: 1 Tier 1, 1 near-Tier 1 Tier 2, rest Tier 2/3 | "I've recently gotten one tier one client and then I have like a tier two client that's almost a tier one client" ~33:05 (L320) | stated |
| 5th | month | Sophie's tenure at Aperitif | "I've only been at the aperitif for four plus months, this is my fifth month." ~06:44 (L070) | stated |
| 24 | hours | Agency email response standard | "from an agency perspective we have like a 24 hour sort of email response time." ~33:59 (L327) | stated |
| 7–10 | clients | Austin's hypothetical extra load – "would be a lot" | "That would be a lot because I also have declined comms." ~33:54 (L326) | stated (hypothetical) |
| 45–60 | minutes | Typical Meta campaign build | "It's probably like, Maybe 45 minutes, maybe an hour." ~26:15 (L249) | stated |
| ~30 | minutes | Faster Meta build | "It could also take like half an hour and depending on how swift." ~27:23 (L258) | stated |
| 3 | clicks | Budget change in platform | "if it's like a budget change, that's three clicks." ~17:31 (L168) | stated |
| 30–45 | minutes | WIP meeting length | "And that's between half and for an hour to 45 minute sessions." ~51:40 (L551) | stated |
| 1 weekly, ~2 fortnightly | client meetings | Tier 1 cadence | "I have weekly catch-ups with one client. I have fortnightly with a couple more." ~52:04 (L554) | stated |
| 3 | systems | Budget/fee data held in HubSpot, Monday, pacing sheets | "at the moment we have the information of management fee and ad spend in HubSpot." ~21:50 (L205) | stated |
| 4 | spreadsheets | Weekly e-com client update | "we have like four different spreadsheets that we input Daily ad spend, weekly ad spend, and the metrics" ~31:36 (L301) | stated |
| 11 am Monday | deadline | E-com client's finance/leadership meeting | "The client has a finance meeting or a leadership meeting at 11 a.m." ~32:09 (L305) | stated |
| 7 / 14 / 30 | days | Performance comparison windows | "we can compare data from Like last seven days, last fortnight, and last month, previous or even last 30 days." ~44:45 (L452) | stated |
| 2 | pacing checks/month | Start-of-month + mid-month | "we also have like a mid-month pacing check" ~47:34 (L491) | stated |
| ~7 | days | Detection lag for broken tracking | "no leads are pulling through. from this landing page in the last seven days" ~54:06 (L583–L584) | stated |
| 8–12 | months | Bloomfield Estate lead-to-sale cycle | "it takes like eight to 12 months for a lead to convert." ~10:58 (L106) | stated |
| $150 / $170 | free-shipping threshold | AU vs NZ e-com client copy QA | "free shipping has a $150 threshold here, it has a $170 threshold here." ~18:50 (L179) | stated |
| ~$1K | per month | Example client budget increase | "oh, we want to spend 1K more a month." ~22:26 (L212) | stated (example) |
| 5–10 | assets | Typical creative refresh batch | "you have a batch of like five or ten assets." ~17:59 (L172) | stated |
| ~10 | creatives | Per asset/ad group for e-com | "So maybe we have like 10 different creatives per." ~27:17 (L256) | stated |
| 6 | ad platforms | Google, Meta, Bing, ChatGPT, TikTok, Pinterest | "we also run Bing ads, chat GPT ads, TikTok ads, Pinterest ads" ~09:54 (L098) | stated |
| 99% | of the time | Meta AI enhancements should be off | "in like Yeah, 99% of the time, like everything should be toggled off" ~18:26 (L177) | stated |

## 9. Tools, data and workarounds

- **Official tools:** Google Ads + Google Ads Editor, Microsoft (Bing) Ads + bulk editor, Meta Ads Manager, ChatGPT ads, TikTok, Pinterest; GA4; pacing Google Sheets; Monday.com (implementation briefs, budgets/fees); HubSpot (management fee, ad spend, sales history); Slack (pacing alerts); AgencyAnalytics (dashboards, scheduled monthly reports); shared Google Drive (client folders); onboarding questionnaire; audit document + roadmap checklist; competitor ad libraries.
- **Shadow tools / workarounds:** Claude for research with no standard prompt (L124); manual summing of Meta ad-set budgets (L292); four client spreadsheets re-keyed by hand every Monday (L301); meeting note-takers tried but not turned into actions (L396); historically personal Google Drives for client documents (L067–L068).
- **Same data in more than one place:** management fee and ad spend in HubSpot, Monday and pacing sheets (L205–L208); approved copy in spreadsheets and again in platforms (L181); client context in HubSpot, sales' heads and onboarding questionnaire (L132–L149).
- **Data or access she needs but doesn't have:** sales handover history ("Maybe I haven't looked into HubSpot in too much depth", L141); reliable automated spend pulls (L199); account-level Meta daily spend (L292); early warning of client website/form changes (L584).

## 10. Knowledge and dependency

| What | Who (role) | If absent |
|---|---|---|
| Strategy, client relationships and briefs for ~12 clients; review/QA of implementers' work | Senior PMM (Sophie) | Implementers have no briefs; clients' 24-h comms and strategy stall |
| Conversion/CRO tracking troubleshooting | Conversion Tracking Specialist (Liam, contractor) | Tracking issues wait; matches "Conversion tracking depends on one contractor" |
| Where client documents live (historically personal drives) | Individual managers, incl. past staff | Handover requires searching; "if someone's always sick, it's very hard to figure out where the hell is something" (Austin, L082) |
| Sales conversation history | Sales team | Client re-asked; weaker strategy base |
| Pacing sheet formulas and setup | Whoever built/maintains the sheets (not named) | Monthly rollover and fixes stall |
| Client personas / ICP | Client-supplied, built on in kickoff call (L645–L651) | Not documented by Aperitif as standard |

## 11a. Clients mentioned

| Client | Tier (context pack) | What was said |
|---|---|---|
| Bloomfield Estate | Not in context pack | House-and-land packages; leads take 8–12 months to convert; client says lead quality is good (L106–L108) |
| DDEG ("DDG"/"DGG", raised by Austin) | Tier 1 (SEO list) – assumed match | Frequently asks for new service lines; new campaign needs research and copywriting before build (L268–L270) |
| Unnamed truck-parts client | – | Monthly specials; PMax refreshed monthly with static imagery (L229) |
| Unnamed bank client | – (possibly Northern Inland Credit Union – unconfirmed) | Separate home-loan and refinancing funnels (L255) |
| Unnamed e-com client (AU/NZ) | – | AU vs NZ URLs; $150 vs $170 free-shipping thresholds checked in QA (L179) |
| Unnamed e-com client (Monday sheets) | – | Four spreadsheets updated manually before 11 am each Monday for finance/leadership meeting (L301–L306) |
| Unnamed client with Google, Bing and ChatGPT ads | – | Multi-channel example (L512) |
| Unnamed Tier 1 client (recent) | Tier 1 | Recently gained; weekly catch-ups with one client (L320, L554) |
