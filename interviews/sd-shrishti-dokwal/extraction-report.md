# Part A – Transcript extraction: Shrishti Dokwal (Senior Performance Marketing Manager)

**Source and method notes**
- Transcript: meeting notes "Shrishti Dokwal – Workflow & Process Interview", 30 Oct 2026, 2:30 pm (Melbourne). Full transcript retrieved (544 utterances, ends at sign-off) – not truncated. The AI summary was not used as a source.
- **Timestamps:** the transcript has no timestamps. Every timestamp below is written `~mm:ss (L###)`: L### is the utterance number in `transcript.md`; ~mm:ss is estimated from cumulative word position across ~54 minutes (60-minute booking, Austin closed "six minutes early", L533).
- **Speakers:** the diariser labelled Austin as B and split Shrishti across labels A, C, D, E and F. All non-Austin lines are treated as Shrishti.
- **Name and term corrections (transcription):** "Tati / Taddy / daddy / Terti" → Tati (Tatiana Stinson, Performance Marketing Coordinator) · "Tina" → the Tina Slack agent bot (OpenClaw workspace), not Tatiana · "Lord / cloud" → Claude · "EasyML" → easyAML · "Supermetric" → Supermetrics · "auto" (note taker) → Otter · "Monday" → Monday.com · "Mera / Meraz" → Meta · "pasting / facing / spacing" → pacing · "client comps" → client comms · "D1s / D2s" and "201" → Tier 1s / Tier 2s · "weekly whips" → weekly WIPs · "we've leased capacity" → we've breached capacity · "grant work" → grunt work · "Connect, yeah" → Correct, yeah · "Wildjar" → WildJar (call tracking) · "lendier" → lengthier. "Leah's" (L193) → Wendlley (Simoes, Performance Marketing Director). Unresolved: "Holstroms" (L503).
- **Name corrections:** Leah's = Wendlley; Tina = Slack bot; escalation director = Julia.
- Hours are costed at **$80/hr internal labour cost**. Process totals include team time (Michaela, Tati, tracking contractor) where those people do steps in the process; the interviewee-only share is shown separately.

---

## 0. Interview card

| Field | Detail |
|---|---|
| Interviewee | Shrishti Dokwal |
| Role | Senior Performance Marketing Manager |
| Team | Performance (paid media) |
| Date / length | 30 Oct 2026 · ~54 min (booked 60) |
| Interviewer | Austin Smith (Transpera AI) |
| Clients managed | 14 clients across 24 channels (stated, L087–L088) |
| Channels / services | Google Ads, Meta, LinkedIn (mentioned); campaign strategy, budget allocation and forecasting, pacing, optimisation, reporting, onboarding |
| Reports to | Wendlley Simoes, Performance Marketing Director (context pack). Onboarding-capacity escalations go to Julia Van Der Linden, Head of Client Services – the transcript says "our director … she" (L434); Austin confirmed this is Julia |
| Hands work to | Michaela Cruz (Performance Marketing Specialist) and Tati (Tatiana Stinson, Coordinator) – implementation, ad copy, SQRs, via Monday.com; clients (strategy, previews, reports); conversion tracking specialist (not named – likely Liam Lau, inferred) |
| Receives work from | Clients (briefs, approvals, creatives, access); Tina Slack agent bot (M/W/F pacing updates); Tati (mid-month performance flags); Michaela and Tati (completed tasks back for QA); Julia, Head of Client Services (reassigns onboardings when capacity is breached) |

## 1. Five-line summary

1. **Pacing is the #1 pain.** Shrishti picked it as the one thing to fix; the Supermetrics-fed sheets broke when the subscription lapsed, Meta pacing is now done manually in Claude every day by the Performance Director (Wendlley), Google Ads stays manual, and budgets are keyed into three places each month.
2. **No proactive performance view.** Problems are only seen when someone is inside an account, and most are picked up at month-end reporting: "if I'm not in the account, then there's no way of knowing." She proposed concrete alert rules (Meta frequency > 3, CPL > 2× last month).
3. **The bottleneck is data collation, not analysis.** Call prep runs 1 h–1 h 15 for a 30-minute call (30–40 min for easyAML's five channels), and Tier 1 analysis means reconciling the ad platforms with the client's own dashboard.
4. **She is at full capacity.** Ad hoc work (new campaigns, pitches, onboardings with no cap) pushes out BAU, and Tier 2/3 clients are dropped first. Hygiene tasks such as SQRs slip.
5. **Onboarding and launches are gated by clients.** Access "sometimes instant, sometimes a lot of following up", the account audit is the longest manual step, and new campaigns need at least a week, depending on when the creatives arrive. She has already brought in a campaign brief template and uses Claude for ad copy and keyword grunt work.

## 1a. Time allocation

| Activity | % / hours | Billable? | Quote + timestamp | Certainty |
|---|---|---|---|---|
| Client comms and meetings (heaviest in weeks 1–2) | Majority, shared with strategy – no % given | Billable (assumed) | "It's a mix of client comms and strategy because I do have very meeting heavy weeks especially the first two weeks of the month." ~09:02 (L066) | stated (no number) |
| Strategy and analysis in the ad platforms | "majority of my work now is like analysis work" | Billable (assumed) | "majority of my work now is like analysis work, right?" ~03:06 (L039) | stated (no number) |
| Time "on the tools" (calls, prep, pacing) | 60–70% of the day ≈ 4.8–5.6 h of an 8 h day | Mostly billable | "about like, 60-70% of my day is on the tools whether it's during a client call before a client call or pacing" ~16:31 (L139) | stated % · hours estimated (60–70% × 8 h) |
| Delegation (Monday.com briefing) and email | "first couple of hours in the day" ≈ 1.5–2 h/day ≈ 19–25% | Partly non-billable (internal) | "I try to smash that off in the first couple of hours in the day" ~02:14 (L035) | stated · % estimated (1.5–2 h ÷ 8 h) |
| Five Good Friends (single Tier 1 client) | "majority of my week's hours" (>50%) | Billable | "five good friends for example so tier one client it takes up majority of my week's hours" ~08:59 (L073) | stated – conflicts with 14-client load |
| Pitch work for new clients | Ad hoc; competes with BAU | Non-billable | "I have to now prioritize between putting together a pitch client versus working on my existing clients" ~11:13 (L096) | stated (no number) |

- **Busy vs quiet:** weeks 1–2 are busy (client meetings, Day 1 budget changes, monthly reports due within the first two weeks); the second half of the month is "relatively slower in terms of meetings and client comms" ~02:08 (L033).
- **Billable vs non-billable:** not discussed directly. Assumed split: about 75–80% client-attributable, about 20–25% internal (delegation, email triage, pitches, QA admin). Confirm with timesheets.

## 2. Processes

Flags: ⏸ bottleneck · 👤 single-person dependent · ⌨️ manual copy / re-keying · ⚠️ error-prone. Interviewee = SD. Team = Michaela / Tati.

### SD-P01 · Paid media – pacing & budget management
- **Trigger:** month end (budget recommendations) → client approval → Day 1 recalibration → M/W/F pacing updates from the Tina Slack agent bot.
- **Owner role:** Senior Performance Marketing Manager (SD).
- **Frequency:** monthly cycle per client (14 clients / 24 channels), plus pacing checks Monday/Wednesday/Friday (≈ 12–13 pacing days a month).
- **Tools / files:** Google Sheet of budget recommendations and campaign allocations; Pacing Sheet / "Pacing Input Documents"; Google Ads, Meta and other platforms; Claude (Meta connector); Supermetrics (lapsed).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Analyse last month's spend and performance; build next month's budget allocations by campaign | SD | Google Sheet (recs), ad platforms | 15–30 per client (210–420 total) | – | Client | assumed |
| 2 | Send allocations to client as FYI or for approval | SD | Email | incl. in 1 | Client approval: unknown ⏸ | Client → SD | stated (step) / assumed (wait) |
| 3 | Day 1: update budgets in the Google Sheet, Pacing Sheet and platforms ⌨️⚠️👤 | SD | Google Sheet, Pacing Sheet, platforms | 60–120 total for all accounts | – | Tina bot (pacing) | stated ("one or two hours", "about two hours") |
| 4 | Pacing update sent M/W/F, flagging under-spending accounts ⚠️ | Tina (Slack agent bot) – no visible owner or documentation | Slack; Pacing Sheet (Meta data entered manually in Claude by Wendlley) | 0 (automated); upstream manual Meta pacing not costed – time not discussed | Up to 2–3 days between checks ⏸ | SD | stated (step) |
| 5 | Routine pacing review on the other pacing days | SD | Pacing Sheet, platforms | 30 per pacing day × 11–13 days (330–390) | – | – | stated (30 min) / estimated (days) |

- **Happy path total:** touch 600–930 min (10–15.5 h) a month for SD; elapsed: month-end recs → Day 1 changes depend on client approval (unknown), then continuous.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Underspend adjustment ⌨️ | Tina bot flags an account/campaign under-spending | 4–12 accounts / month (assumed) | Reopen allocation sheet, pull month-to-date spend, compare with allocations, run formulas, update platform | 15–20 min per account | SD | stated (15–20 min) / assumed (rate) |
| Meta pacing data unavailable ⚠️👤 | Supermetrics subscription lapsed – sheets broken | Every day since lapse | Wendlley (Performance Director) runs Meta pacing manually in Claude every day; Google Ads manual | Not quantified – time not discussed (daily director time) | Wendlley, SD | stated (event; Leah's = Wendlley per Austin) / time not discussed |
| Tina bot stops posting ⚠️ | Slack agent fails or breaks unnoticed (the Tina agenda-reminder bot has broken before – context pack) | unknown | Pacing updates stop until someone notices; SD checks pacing manually | not quantified | SD, clients | detected |
| Late client approval | Allocations need approval, client slow | unknown | Day 1 changes slip; pacing runs on old allocations | unknown | SD, client | assumed |

- **Decision points:** after step 2 – FYI only vs needs approval (split not given; "Sometimes it's an FYI… Sometimes it's approval", L225–L226 – stated, no %). After step 4 – account on pace (no action) vs under/over-spending (adjust) – split assumed at 4–12 of 24 channels a month.
- **Volume (team):** 61 Google Ads clients and 41 Meta budget lines across the team (context pack); every manager runs the same cycle.
- **Monthly hours:** happy path 600–930 min + bad path (4 × 15 = 60 to 12 × 20 = 240 min) = 660–1,170 min = **11.0–19.5 h** (estimated).
- **Monthly cost:** 11.0 × $80 = **$880** to 19.5 × $80 = **$1,560**.

### SD-P02 · Paid media – optimisation (monthly hygiene optimisations)
- **Trigger:** optimisations identified while writing the monthly report; some need client approval (for example ad copy changes).
- **Owner role:** SD (decides, briefs, QAs); team implements.
- **Frequency:** monthly per client (14).
- **Tools / files:** monthly report (AgencyAnalytics), Monday.com, Google Ads / Meta.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | List next steps / optimisations in the monthly report | SD | AgencyAnalytics report | counted in SD-P03 | – | Client | stated (step) |
| 2 | Client approval if the change is major | Client | Email / report | – | unknown ⏸ | SD | stated (step) |
| 3 | Brief the optimisations into Monday.com | SD | Monday.com | 10–15 per client | – | Michaela / Tati | stated (step) / assumed (time) |
| 4 | Implement hygiene changes | Michaela / Tati | Ad platforms | 30–60 per client | Queue on team capacity | SD (task assigned back) | assumed |
| 5 | Review and QA the changes 👤⏸ | SD | Ad platforms | 10–20 per client | Waits for SD's availability | – | stated (step) / assumed (time) |
| 6 | Monitor impact through the month | SD | Ad platforms | not costed separately (inside SD-P07 / SD-P08) | – | – | stated (step) |

- **Happy path total:** 50–95 min per client; elapsed: report (by mid-month) → approval → implementation, usually inside the month (assumed).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Search query report (SQR) needed | One campaign's CPL much higher than others | 1–3 / month (assumed) | Task SQR to Michaela / Tati; review negatives | 30–60 team + 10 SD | Team, SD | stated (trigger) / assumed (rate, time) |
| Hygiene skipped | No capacity | unknown | SQR "ideally should be done every month but… depends on our time and capacity" | Performance risk, not time | Tier 2/3 clients | stated |
| Meta ad fatigue | Ad frequency > 3 | Seen at monthly report | Pause or refresh creative | not quantified | Team, client | stated (rule) |

- **Decision points:** after step 1 – minor hygiene (straight to team) vs major (client approval first); split not given (assumed 70/30). After step 5 – QA pass vs rework (rate not discussed).
- **Monthly hours:** 14 × 50 = 700 min + 1 × 40 = 740 min (12.3 h) to 14 × 95 = 1,330 + 3 × 70 = 1,540 min (25.7 h) → **12.3–25.7 h** (SD share 4.8–8.7 h; rest is team) – assumed.
- **Monthly cost:** 12.3 × $80 = **$984** to 25.7 × $80 = **$2,056**.

### SD-P03 · Monthly reporting
- **Trigger:** start of month; reports due within the first two weeks.
- **Owner role:** SD.
- **Frequency:** monthly × 14 clients.
- **Tools / files:** AgencyAnalytics ("now automated"), ad platforms.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Report data generated | AgencyAnalytics | AgencyAnalytics | 0 | – | SD | stated |
| 2 | Analyse last month, write commentary and next steps; spot optimisations (frequency, CPL) | SD | AgencyAnalytics, platforms | 20–40 per client | – | Client | stated (step) / assumed (time) |
| 3 | Send report to client | SD | Email / AgencyAnalytics | incl. in 2 | – | Client → SD-P02 | stated |

- **Happy path total:** 20–40 min per client; elapsed: inside the first two weeks.
- **Bad paths:** not discussed.
- **Decision points:** report shows issues → optimisations into SD-P02 (most months, assumed).
- **Monthly hours:** 14 × 20 = 280 min (4.7 h) to 14 × 40 = 560 min (9.3 h) → **4.7–9.3 h** (assumed).
- **Monthly cost:** 4.7 × $80 = **$376** to 9.3 × $80 = **$744**.

### SD-P04 · Client meetings & prep
- **Trigger:** scheduled calls – weekly for Tier 1, monthly for Tier 2.
- **Owner role:** SD.
- **Frequency:** an estimated 16.7–27.3 calls a month (assumed: 2–4 Tier 1 clients × 4.33 weekly calls + 8–10 Tier 2/3 monthly calls).
- **Tools / files:** ad platforms (shown live on calls), Otter AI notes, email, Claude (Meta).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Collate performance across channels; write "what happened / what I'm seeing / what I recommend" ⌨️👤 | SD | Each ad platform | Within 60–75 (prep + post together); easyAML (5 channels): 30–40 prep | – | – | stated |
| 2 | Run call, showing the platforms live | SD | Ad platforms | 30–45 | – | Client | stated |
| 3 | Check Otter notes; write and send follow-up email with action items ⌨️ | SD | Otter, email | Within the 60–75 above | – | Client; team via Monday.com | stated |

- **Happy path total:** 90–120 min per call (prep + post 60–75, call 30–45); elapsed: same day.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| AI note-taker misses action items | Otter summary inaccurate | Most calls (assumed) | Rewrite action items manually | Included in 60–75 | SD, client | stated |
| Multi-channel client | 5+ channels (easyAML) | Some clients | Collate each channel separately | 30–40 prep for one client (stated) | SD | stated |

- **Decision points:** what to focus on changes each week depending on live tests – there is no fixed template ("The focus area keeps changing every week", L182).
- **Monthly hours:** low 16.7 calls × 90 min = 1,500 min (25.0 h); high 27.3 × 120 = 3,276 min (54.6 h) → **25.0–54.6 h** (of which prep/post 16.7–34.1 h) – estimated from stated per-call times and an assumed call count.
- **Monthly cost:** 25.0 × $80 = **$2,000** to 54.6 × $80 = **$4,368**.

### SD-P05 · Paid media – campaign build (ad hoc new campaign for an existing client)
- **Trigger:** client brief by email ("We'd like to get this campaign started ASAP. Please send your strategy") – Tier 1 clients increasingly use the campaign brief template.
- **Owner role:** SD (strategy, QA); team (ad copy, implementation).
- **Frequency:** 1–2 a month (assumed; "a lot of ad hoc requests", L040).
- **Tools / files:** campaign brief template, keyword research tools, ad platforms, Meta Ads Library, Claude, Monday.com, strategy Google Sheet/Doc.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Client sends brief (template or email) | Client | Brief template / email | – | – | SD | stated |
| 2 | Build strategy: keyword research, campaign structure, budget allocations, landing-page recommendations, rationale 👤 | SD | Platforms, Sheets, Claude | 120–240 | 1–2 days elapsed ("at least one or two days") | Team | stated (elapsed) / assumed (touch) |
| 3 | Brief ad copy | SD | Monday.com | 10–20 | – | Michaela / Tati | assumed |
| 4 | Write ad copy (Claude increasingly does this) | Michaela / Tati / Claude | Claude, Sheets | 60–120 | – | SD | assumed |
| 5 | Review and send strategy to client | SD | Email | 30–60 | Client review ⏸ | Client | assumed |
| 6 | Make client revisions | SD | Sheets | 30–60 | Client re-approval | Client | stated (step) / assumed (time) |
| 7 | Client approves; sends creatives | Client | – | – | "probably another couple of days" ⏸ | SD | stated |
| 8 | Brief implementation | SD | Monday.com | 15–30 | – | Michaela / Tati | assumed |
| 9 | Build campaigns | Michaela / Tati | Ad platforms | 180–360 | "about a day or two days" elapsed | SD | stated (elapsed) / assumed (touch) |
| 10 | QA the build 👤⏸ | SD | Ad platforms | 30–60 | – | Client | stated (step) / assumed (time) |
| 11 | Send ad preview links; client approves go-live; launch | SD / client | Email, platforms | 10–20 | Client approval | – | stated (step) / assumed (time) |

- **Happy path total:** touch 485–970 min (8.1–16.2 h) per campaign; elapsed **≥ 1 week** (stated: "generally we require at least a week's time provided the creatives are being sent to us on time", L360).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Creatives late | Client late with assets | unknown | Launch waits | Elapsed days, little touch | Client, SD | stated (dependency) |
| QA finds errors | Build not "to the T" | 20–30% (assumed) | Send back, re-check | 30–60 min | Team, SD | assumed |
| No written brief | Brief given verbally on a call (older pattern, Tier 2/3) | Falling (template adoption) | SD collates from several places | not quantified | SD | stated |

- **Decision points:** after step 5 – client approves first time vs revisions (stated "Client will have some revisions", L051 – assumed mostly revisions); after step 10 – QA pass vs rework (assumed 70–80 / 20–30); after step 11 – go-live approved vs changes (not discussed).
- **Monthly hours:** low 1 × 485 + 0.2 × 30 = 491 min (8.2 h); high 2 × 970 + 0.3 × 60 × 2 = 1,976 min (32.9 h) → **8.2–32.9 h** (SD share 4.2–16.9 h) – assumed.
- **Monthly cost:** 8.2 × $80 = **$656** to 32.9 × $80 = **$2,632**.

### SD-P06 · Client onboarding – audit & strategy (end to end: access, audit, strategy, tracking, build, launch)
- **Trigger:** new client signs.
- **Owner role:** SD as account manager; Julia Van Der Linden (Head of Client Services) reallocates onboardings when capacity is breached (transcript: "our director", L434).
- **Frequency:** varies – "Sometimes we don't have onboarding. Sometimes we have like three onboardings at once" (L433); two arrived in the last couple of weeks. Assumed 0.5–1.5 a month for SD.
- **Tools / files:** discovery call, client ad accounts (read access), audit document (Google Ads / Meta audit – source of truth for onboarding only), strategy Sheet (KPIs, campaign plan), launch checklist, conversion tracking (contractor), Monday.com.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Discovery call (business, goals, introduction) | SD | Call | 60–90 | – | Client | stated (step) / assumed (time) |
| 2 | Request and chase account access ⏸ | SD | Email | 30–120 | "Sometimes it's instant. Sometimes there's a lot of following up" | Client | stated (step) / assumed (time) |
| 3 | Audit accounts line by line – "majority of the times" ⌨️👤 | SD | Ad platforms, audit doc | 240–480 | – | – | stated (longest step) / assumed (time) |
| 4 | Strategy: targets, KPIs, keyword research, campaign plan | SD | Sheets, platforms | 180–360 | Steps 3–4 together ≈ "at least a week" elapsed | Team | stated (elapsed) / assumed (touch) |
| 5 | Ad copy | Michaela / Tati | Sheets / Claude | 60–180 | – | SD | assumed |
| 6 | Present strategy to client | SD | Slides / call | 60–90 | – | Client | stated (step) / assumed (time) |
| 7 | Rework from client feedback; approval | SD | Sheets | 60–180 | Client approval ⏸ | Tracking | stated (step) / assumed (time) |
| 8 | Conversion tracking set-up and testing 👤 | Tracking specialist (likely Liam Lau – inferred) | GTM / platforms | 180–360 | "another three, four days" elapsed | Team | stated (elapsed) / assumed (touch) |
| 9 | Campaign build (alongside tracking) | Michaela / Tati | Ad platforms | 360–720 | "a week, maybe like three or four days" | SD | stated (elapsed) / assumed (touch) |
| 10 | QA the build | SD | Ad platforms, launch checklist | 60–120 | – | – | stated (step) / assumed (time) |
| 11 | Launch | SD | Platforms | 15–30 | – | – | stated (step) |

- **Happy path total:** touch 1,305–2,730 min (21.8–45.5 h) per onboarding (SD 705–1,470 min); elapsed ≈ 2.5–4 weeks after access (estimated: ≥1 week audit/strategy + client review + 3–4 days tracking alongside 3–5 days build), plus however long access takes.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Access delays | Client slow to grant access | "Sometimes" | Repeated follow-ups; audit can't start | Days of elapsed time; 30–120 min chasing (in step 2) | SD, client | stated |
| Approval / dependency road bumps | Many people and approvals involved | "with some of the recent clients" | Re-sequencing; delays | not quantified | SD, team, client | stated |
| Onboarding overload | Several onboardings land at once (up to 3) | Occasional | Escalate to Julia (Head of Client Services), who reassigns | Head of Client Services time; BAU slips | SD, all existing clients | stated |
| Tracking needs prioritising | Launch pressure | unknown | Tracking pushed forward "unless we have to prioritize it" | – | Tracking specialist | stated |

- **Decision points:** after step 2 – access instant vs chasing (split not given); after step 6 – approve vs feedback round (feedback is normal, "they'll have a bunch of feedback", L417); onboarding allocation – SD keeps it vs Julia reassigns (when capacity is breached).
- **Monthly hours:** low 0.5 × 1,305 = 653 min (10.9 h); high 1.5 × 2,730 = 4,095 min (68.2 h) → **10.9–68.2 h** (SD share 5.9–36.8 h) – assumed.
- **Monthly cost:** 10.9 × $80 = **$872** to 68.2 × $80 = **$5,456**.

### SD-P07 · Performance monitoring & alerting
- **Trigger:** mid-month (Tati's manual check); otherwise only when someone happens to be in the account.
- **Owner role:** Tati (Tatiana Stinson, Coordinator) does the check manually ("unless Tati has flagged it", L474); SD investigates. The team plans to hand the check to the Tina Slack agent: "something that we have been meaning to get Tina to now pick up" (L463) – planned, not done.
- **Frequency:** monthly (mid-month) × 24 channels; plus ad hoc spotting.
- **Tools / files:** ad platforms, comparison of the last 15 days against the 15 before.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Compare last 15 days with the prior 15 per account ⌨️ | Tati (Tatiana Stinson, Coordinator) | Ad platforms | 5–10 per channel × 24 (120–240) | Mid-month only ⏸ | SD | stated (step) / assumed (time) |
| 2 | Flag conversion drops to account managers | Tati | not stated | incl. | – | SD | stated |
| 3 | Investigate and brief optimisations | SD | Platforms, Monday.com | 30–60 per flag × 2–5 flags (60–300) | – | Team | assumed |

- **Happy path total:** 180–540 min a month; elapsed: issues can sit up to ~2 weeks (mid-month to month-end) before they are seen.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Issue missed until month-end report | Not in the account; no alert | "Generally" – most issues | Found during reporting; fixed next month | Lost performance (not time) | Client, SD | stated |
| Client spots it first | No alerting | unknown | Reactive fix | not quantified | Client, SD | interviewer (L476) – not contradicted |

- **Decision points:** drop flagged → investigate vs ignore (no thresholds defined today – detected).
- **Monthly hours:** 180–540 min → **3.0–9.0 h** (SD share 1–5 h) – assumed.
- **Monthly cost:** 3.0 × $80 = **$240** to 9.0 × $80 = **$720**.

### SD-P08 · Internal task management (daily delegation and email triage)
- **Trigger:** start of each day.
- **Owner role:** SD.
- **Frequency:** daily (20–22 working days).
- **Tools / files:** email, Monday.com (statuses such as "ready", tasks assigned back for review).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Clear email; answer client ad hoc requests | SD | Email | 45–90 a day (net of briefing counted in P02/P05) | – | Client / team | stated ("first couple of hours") / assumed (net) |
| 2 | Brief and assign tasks; keep team aligned with strategy | SD | Monday.com | incl. above | – | Michaela / Tati | stated |

- **Happy path total:** 45–90 min a day; the stated "first couple of hours" includes briefing already costed in P02/P05, hence the net range.
- **Bad paths:** ad hoc client requests ("Oh, we want this campaign…", L040) break focus time – frequency not quantified.
- **Monthly hours:** 20 × 45 = 900 min (15.0 h) to 22 × 90 = 1,980 min (33.0 h) → **15.0–33.0 h** – assumed.
- **Monthly cost:** 15.0 × $80 = **$1,200** to 33.0 × $80 = **$2,640**.

### SD-P09 · Paid media – optimisation (Tier 1 analysis and test planning – Five Good Friends)
- **Trigger:** running tests; "this is not every day, this is like maybe every 12" (L076 – probably "every one to two weeks"; uncertain).
- **Owner role:** SD.
- **Frequency:** every 1–2 weeks ≈ 2.2–4.3 times a month (estimated from a garbled phrase).
- **Tools / files:** client dashboard (data from Pipedrive and WildJar, attributed to campaign level), member data ("main source of truth"), Google Ads / Meta.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Pull platform numbers | SD | Ad platforms | 60–180 for steps 1–4 combined | – | – | assumed |
| 2 | Pull client dashboard and member data ⌨️ | SD | Client dashboard (Pipedrive, WildJar) | incl. | – | – | stated (step) |
| 3 | Compile "what I'm seeing on my end versus their end" ⌨️⚠️ | SD | Sheets | incl. | – | – | stated |
| 4 | Write the optimisation / scaling / testing plan | SD | Doc / Sheet | incl. | – | Client / team | stated |

- **Happy path total:** 60–180 min per cycle.
- **Bad paths:** sources disagree ("a lot of different sources of truths") – extra reconciliation; frequency not stated.
- **Decision points:** performing well → scale vs not → improve (stated, L077; split not given).
- **Monthly hours:** 2.17 × 60 = 130 min (2.2 h) to 4.33 × 180 = 779 min (13.0 h) → **2.2–13.0 h** – assumed.
- **Monthly cost:** 2.2 × $80 = **$176** to 13.0 × $80 = **$1,040**.

### Process totals

| ID | Process | Monthly hours (all actors) | SD-only hours | Monthly cost (all actors) |
|---|---|---|---|---|
| SD-P01 | Paid media – pacing & budget management | 11.0–19.5 | 11.0–19.5 | $880–$1,560 |
| SD-P02 | Paid media – optimisation (hygiene) | 12.3–25.7 | 4.8–8.7 | $984–$2,056 |
| SD-P03 | Monthly reporting | 4.7–9.3 | 4.7–9.3 | $376–$744 |
| SD-P04 | Client meetings & prep | 25.0–54.6 | 25.0–54.6 | $2,000–$4,368 |
| SD-P05 | Paid media – campaign build (ad hoc) | 8.2–32.9 | 4.2–16.9 | $656–$2,632 |
| SD-P06 | Client onboarding – audit & strategy | 10.9–68.2 | 5.9–36.8 | $872–$5,456 |
| SD-P07 | Performance monitoring & alerting | 3.0–9.0 | 1.0–5.0 | $240–$720 |
| SD-P08 | Internal task management | 15.0–33.0 | 15.0–33.0 | $1,200–$2,640 |
| SD-P09 | Paid media – optimisation (Tier 1 analysis) | 2.2–13.0 | 2.2–13.0 | $176–$1,040 |
| **Total** | | **92.3–265.2 h** | **73.8–196.8 h** | **$7,384–$21,216** |

The high ends can't all happen in the same month: SD's high-end share (~197 h) is more than one full-time month (~152–160 h). Treat the low-to-mid range as more realistic and confirm with calendar and timesheet data.

## 3. Pain points and problems

| ID | Pain point (one line) | Source | Category | Anchor | Process | Impact | How often | Severity 1–5 | Quote + timestamp | Certainty |
|---|---|---|---|---|---|---|---|---|---|---|
| SD-PP01 | Pacing is the #1 pain: sheets broke when the Supermetrics subscription lapsed, and the whole process is manual; the Performance Director now does Meta pacing by hand in Claude every day (👤 – time not quantified) | interviewee (named it when asked the "magic wand" question) | Single point of failure (tool) | Performance visibility & margin | Paid media – pacing & budget management | Time + overspend/underspend risk ($) | Daily / M-W-F | 5 | "the sheets have broken because we no longer have a Supermetric subscription." ~22:57 (L193); "The whole process just feels very manual right now." ~23:18 (L196) | stated |
| SD-PP02 | Budget allocations keyed by hand into three places (recs sheet, Pacing Sheet, platforms) | interviewee (described) | Duplicate data entry | Performance visibility & margin | Paid media – pacing & budget management | 1–2 h on Day 1; error risk | Monthly per client | 4 | "One is the Google Sheet, one is the Pacing Sheet, and the other is the platform itself." ~26:49 (L243) | stated |
| SD-PP03 | Underspend fixes are worked out by hand: 15–20 min per account | interviewee | Manual / repetitive work | Operations capacity & process | Paid media – pacing & budget management | 1–4 h/month (estimated) | Each flagged account | 4 | "It's a bit manual. I'm sure there's a better way of doing it" ~28:40 (L281); "About 15, 20 minutes per account" ~28:34 (L277) | stated |
| SD-PP04 | No proactive alerting: problems are only seen when someone is in the account, most at month-end | interviewee | Missing visibility | Performance visibility & margin | Performance monitoring & alerting | Client performance; reactive work | Continuous | 4 | "if I'm not in the account, then there's no way of knowing." ~51:56 (L516) | stated |
| SD-PP05 | Call prep and post-call notes take 1 h–1 h 15 per 30-min call, mostly collating data across channels | interviewee | Manual / repetitive work | Client experience & delivery | Client meetings & prep | 16.7–34.1 h/month (estimated) | Every client call | 4 | "for a half an hour call, I'm basically spending about one hour, one hour, 15 minutes on that specific client" ~18:36 (L161) | stated (per call) / estimated (monthly) |
| SD-PP06 | AI note-taker (Otter) action items aren't accurate enough, so follow-up emails are still manual | interviewee | Tool not used / adoption | Technology, AI & stack | Client meetings & prep | Minor time | Every call | 2 | "It still doesn't do the most accurate job of sending the action items as discussed." ~18:59 (L162) | stated |
| SD-PP07 | Working at full capacity; ad hoc work (pitches, new campaigns) pushes out BAU and Tier 2/3 clients are dropped first | interviewee | Capacity / overload | Operations capacity & process | Internal task management | Tier 2/3 performance; retention risk | Whenever ad hoc work spikes | 4 | "the first set of clients that take a hit in performance or get neglected are those tier 3, tier 2 clients" ~12:35 (L110) | stated |
| SD-PP08 | Hygiene tasks (SQRs) aren't done monthly because of capacity | interviewee | Capacity / overload | Client experience & delivery | Paid media – optimisation | Wasted spend on poor-intent queries (assumed) | Monthly | 3 | "ideally should be done every month but again depends on our time and capacity" ~50:17 (L504) | stated |
| SD-PP09 | Getting client account access during onboarding can need a lot of chasing | interviewee | Waiting / handoff delay | Client experience & delivery | Client onboarding – audit & strategy | Days of delay; chasing time | Each onboarding (sometimes) | 3 | "Getting access from them is a bit of a friction area. Sometimes it's instant. Sometimes there's a lot of following up." ~41:01 (L414) | stated |
| SD-PP10 | Onboarding has many dependencies and approvals, so timelines slip; it disrupts BAU for all clients and there's no cap on concurrent onboardings | interviewee (delays, no cap); interviewer raised BAU disruption – interviewee agreed "Correct." | Waiting / handoff delay | Operations capacity & process | Client onboarding – audit & strategy | Time-to-launch; BAU slippage; escalations land on the Head of Client Services | Each onboarding; up to 3 at once | 4 | "because of how dependent the dependency there is in terms of approvals and managing a lot of people for one thing The timelines have been delayed." ~42:19 (L422) | stated |
| SD-PP11 | The onboarding account audit is manual, line by line, and the longest onboarding step | interviewee | Manual / repetitive work | Operations capacity & process | Client onboarding – audit & strategy | 4–8 h per onboarding (assumed) | Each onboarding | 3 | "the audit is what takes majority of the times during the whole onboarding process" ~39:57 (L412) | stated (longest) / assumed (hours) |
| SD-PP12 | Ad hoc campaign launch takes at least a week and depends on clients sending creatives and approving twice | interviewee | Waiting / handoff delay | Client experience & delivery | Paid media – campaign build | Speed to market; client experience | 1–2 / month (assumed) | 3 | "generally we require at least a week's time provided the creatives are being sent to us on time." ~34:59 (L360) | stated |
| SD-PP13 | Tier 1 (Five Good Friends) analysis means reconciling platform data with the client's dashboard and member data – several sources of truth | interviewee | Duplicate data entry | Performance visibility & margin | Paid media – optimisation (Tier 1) | 2.2–13 h/month (assumed); largest client | Every 1–2 weeks (uncertain) | 3 | "there's a lot of data processing involved with this client specifically because they have a lot of different sources of truths." ~09:32 (L076) | stated |
| SD-PP14 | Data collation, not analysis, is where the time goes, including much of Tati's work | interviewer framed it; interviewee agreed ("Yes, more or less") and later restated it | Manual / repetitive work | Technology, AI & stack | Performance monitoring & alerting | Team time; slower diagnosis | Continuous | 4 | "a lot of daddies [Tati's] work goes in just collating that data very manually." ~47:51 (L489) | stated |
| SD-PP15 | Claude connects to Meta but not Google Ads, so Google analysis and pacing stay manual | interviewee | Manual / repetitive work | Technology, AI & stack | Paid media – pacing & budget management | Not quantified | Daily | 2 | "I have connected my meta ads to cloud [Claude] now, game changer, and Google Ads tool isn't a connector yet." ~15:50 (L131) | stated |
| SD-PP16 | Every piece of delegated work comes back to SD for QA – a single gate while she's at capacity | detected | Single point of failure (person) | Leadership & dependency | Paid media – optimisation / campaign build | Queue on SD; delay | Every task | 2 | "That's when I have to go in and review whatever work they've done to make sure it's all to the T." ~06:06 (L056–L057) | detected |
| SD-PP17 | Clients used to brief campaigns verbally with nothing written down (partly fixed by the brief template, mainly for Tier 1) | interviewee | Client friction | Client experience & delivery | Paid media – campaign build | Admin time collating briefs | Falling | 2 | "So there was no such documented brief for us." ~07:04 (L060) | stated |
| SD-PP18 | Timelines depend on when WIP and client meetings fall (weekly Tier 1, monthly Tier 2) | interviewee | Waiting / handoff delay | Operations capacity & process | Client meetings & prep | Delays | Monthly | 2 | "makes the timelines either faster or delayed depending on when they're organized." ~32:18 (L327) | stated |
| SD-PP19 | Pacing cadence depends on the Tina Slack agent bot, which has no visible owner or documentation (a Tina bot has broken unnoticed before) | detected | Single point of failure (tool) | Technology, AI & stack | Paid media – pacing & budget management | Pacing flags stop silently; overspend/underspend risk | M/W/F | 3 | "Tina gives us updates and Monday, Wednesday, Friday." ~27:21 (L260) | detected (Tina = bot per Austin) |

**Problem-list matches added 6 Nov:** SD-PP10 also matches "Escalations route around department leads to the Head of Client Services"; SD-PP19 matches "Slack bots and agents have no visible owner or documentation".

**Top 3 by severity – root cause and match**

1. **SD-PP01 Pacing broken and manual (5).** Why manual? The sheets lost their data feed. Why? The Supermetrics subscription lapsed and nobody owned renewing it or replacing it. Why does that matter so much? Pacing depends on one connector and hand-kept allocation sheets, with no single system holding budgets by campaign. **Root cause:** no owned, maintained pacing system – just a tool chain with no owner or monitoring. **Matches:** "Meta pacing sheet is broken – Supermetrics connector failing" (and #2 "Budgets maintained by hand in three places").
2. **SD-PP04 No proactive alerting (4).** Why are issues found late? Detection relies on a person being in the account. Why? There are no rules or thresholds and no cross-account view, and the mid-month check is manual and not yet formally owned. **Root cause:** monitoring is a by-product of other work rather than a defined process with thresholds and an owner. **Matches:** "No proactive performance alerting – problems found at month-end".
3. **SD-PP05 Call prep longer than the call (4).** Why? Data has to be collated channel by channel and written into a client-specific narrative. Why? There is no single per-client data view, and AI notes aren't trusted for client-facing actions. **Root cause:** no consolidated per-client performance data layer and no standard prep format. **Matches:** "Client-call prep takes longer than the call".

## 4. Bottlenecks

| ID | Step | Waiting on | Typical wait | Affected | Knock-on |
|---|---|---|---|---|---|
| SD-B01 | Day 1 budget changes (SD-P01 step 2–3) | Client approval of allocations (when approval is needed) | unknown | Clients needing approval (share unknown) of 14 | Pacing runs on old allocations; Day 1 crunch |
| SD-B02 | Pacing adjustments (SD-P01 step 4) | Tina bot's M/W/F update, then SD's time | Up to 2–3 days between checks | 24 channels | Under/over-spend runs between checks; manual calculation each time |
| SD-B03 | Onboarding audit start (SD-P06 step 2) | Client account access | "instant" to "a lot of following up" | Each new client | Launch slips; work squeezed into BAU |
| SD-B04 | Campaign launch (SD-P05 step 7) | Client creatives; two rounds of client approval | Creatives "another couple of days"; launch ≥ 1 week total | 1–2 campaigns/month (assumed) | Slower time to market |
| SD-B05 | QA of delegated work (SD-P02 step 5, SD-P05 step 10, SD-P06 step 10) | SD's availability | not stated (detected) | All team output for 14 clients | Implementation queues behind SD's meetings and ad hoc work |
| SD-B06 | Conversion tracking (SD-P06 step 8) | Tracking specialist | 3–4 days | Each onboarding | Delays launch "unless we have to prioritize it" |
| SD-B07 | Performance issue detection (SD-P07) | Mid-month check or month-end report | Up to ~2 weeks | All accounts, Tier 2/3 most | Lost performance; next-month fixes |

## 4a. Decisions and approvals

| Decision | Who decides (role) | Who waits | Typical time | Lands on leadership? |
|---|---|---|---|---|
| Monthly budget allocations (FYI vs approval) | Client (SD recommends) | SD; pacing | unknown | No |
| New campaign strategy sign-off | Client | SD, team | Not stated; revisions usual | No |
| Go-live after ad previews | Client | SD, team | Not stated | No |
| Major optimisations (for example ad copy changes) | Client | Team | Not stated | No |
| Onboarding strategy sign-off | Client | SD, tracking, team | Not stated; "a bunch of feedback" usual | No |
| Reallocating onboardings when a manager is over capacity | Julia Van Der Linden, Head of Client Services (transcript says "our director … she", L434; Austin confirmed Julia) | SD | Not stated | **Yes** – lands on the Head of Client Services; could sit with the Performance Director or a capacity rule |
| Pacing adjustment amounts | SD | Team / platforms | 15–20 min per account | No (could sit lower with a calculator / rules) |
| QA sign-off of all implementation | SD | Michaela, Tati | Not stated | No, but concentrated on one senior person |
| Pitch work vs existing-client work | SD (self) | Tier 2/3 clients | Ad hoc | No – no rule, so self-prioritised |

## 5. Suggestions for change (as raised in the interview)

| ID | Idea | Source + reaction | Process | Quote + timestamp |
|---|---|---|---|---|
| SD-S01 | Fix pacing first (magic-wand pick) | interviewer asked; interviewee chose pacing | Paid media – pacing & budget management | "facing [pacing] That's the..." ~22:50 (L190); "I think that's been a big pain point for us recently." ~22:53 (L192) |
| SD-S02 | Fix all pacing from one dashboard instead of going into each account | interviewer; interviewee agreed strongly ("100%") | Paid media – pacing & budget management | "100%." ~17:02 (L144) |
| SD-S03 | The pacing dashboard must show campaign-level allocations, because Tier 1 allocations are campaign-specific and change monthly | interviewee | Paid media – pacing & budget management | "even if we had one dashboard, I would have to have the visibility." ~17:17 (L150); "on a campaign level." ~17:28 (L152) |
| SD-S04 | Pre-diagnose accounts so the manager only makes the judgement call | interviewer; no explicit reaction (she moved on to her own ideas) | Paid media – pacing & budget management | Austin: "have like a diagnosis already for you and then you can make the judgment call" ~17:49 (L156) |
| SD-S05 | A tool that collates each client's data and can be queried and steered to produce client-specific call updates | interviewee | Client meetings & prep | "a tool where everything's collated. I'm asking it the right questions. I am nudging it towards giving me the kind of updates" ~19:36 (L164) |
| SD-S06 | Templated / dynamic call-update format | interviewee floated a template, then doubted it because focus changes weekly; interviewer suggested "augmented" instead | Client meetings & prep | "There could be a templated version of it, but I think..." ~21:17 (L181); "The focus area keeps changing every week." ~22:11 (L182) |
| SD-S07 | Standard client campaign brief template (already in place, pushed hardest with Tier 1) | interviewee (implemented) | Paid media – campaign build | "especially with our tier one clients, I have been really pushing hard on filling out the campaign brief template." ~07:04 (L060) |
| SD-S08 | Cut the lead time between client brief and launch | interviewee | Paid media – campaign build | "one of the things that is something we can really optimize is the lead time it takes between them briefing it in versus us…launching" ~34:59 (L360) |
| SD-S09 | Standardise the minimum information needed for an onboarding strategy and speed it up with AI | interviewer; no explicit reaction | Client onboarding – audit & strategy | Austin: "creating standardized ways of creating the strategies and what the minimum information is" ~43:38 (L437) |
| SD-S10 | One-touch / read-only access tools for onboarding | interviewer; interviewee neutral ("Of course.") | Client onboarding – access & setup | Austin: "there are tools out there that do, like, a one-touch access where you get read-only access immediately." ~44:11 (L440) |
| SD-S11 | Have the Tina bot (or Tati) gather as much performance information as possible to cut tool-switching – transcript says "Tati" (L478); intent likely the bot, confirm | interviewer; interviewee agreed ("Correct, yeah") | Performance monitoring & alerting | Austin: "get Tati to give us the most amount of information we possibly can get" ~47:13 (L478) |
| SD-S12 | A script or tool giving an overarching performance table; automate or augment data collation | interviewee (after interviewer prompt; "100%, yeah") | Performance monitoring & alerting | "If we can automate or augment the data collation side of things and just make it faster for us to diagnose any performance issues" ~48:01 (L491) |
| SD-S13 | Alert rules: Meta ad frequency > 3 (fatigue); CPL > 2× last month | interviewee | Performance monitoring & alerting | "whenever, for example, an ad frequency reaches more than three, maybe just alert the manager" ~52:21 (L524) |
| SD-S14 | An "omnipresent" monitor across every account that says where attention is needed | interviewer; interviewee agreed and added rules | Performance monitoring & alerting | Austin: "an omnipresent thing that can be in every account and then just tell you where it needs your attention." ~52:09 (L520) |
| SD-S15 | Rules specific to each client | interviewer | Performance monitoring & alerting | Austin: "it would also be specific to each client." ~52:55 (L527) |
| SD-S16 | Automate the mid-month 15-vs-15-day check via the Tina Slack agent (planned, not done; Tati does it manually today) | interviewee ("been meaning to") | Performance monitoring & alerting | "this is something that we have been meaning to get Tina to now pick up" ~45:46 (L463) |
| SD-S17 | Claude connector for Google Ads (Meta already connected) | interviewee (implied) | Paid media – optimisation | "Google Ads tool isn't a connector yet." ~15:50 (L131) |

## 6. Opportunity assessment

| ID | Fixes | Lens | What changes | Matches existing solution idea | Existing tool | Hours saved / month (maths) | Effort | Prerequisites | Adoption risk | COI flag |
|---|---|---|---|---|---|---|---|---|---|---|
| SD-O01 | SD-PP01, SD-PP15, SD-PP19 | Automate | Restore the Meta (and Google) data feed into the pacing sheets now: renew Supermetrics or switch to an equivalent connector, and give one person ownership of renewals; ends the Performance Director's daily manual Claude workaround, and the Tina bot keeps delivering M/W/F updates | pacing tracker & adjustment engine (interim step) | Supermetrics, Porter Metrics, Windsor.ai, Google Ads native Sheets export | 5–11 h (assumed: Wendlley's manual Claude Meta pacing 15–30 min/day × 20–22 days – time not discussed) | S | Budget sign-off; named owner | L – restores what the team already used | No (off the shelf) |
| SD-O02 | SD-PP01, SD-PP02, SD-PP03, SD-PP19, SD-B02 | Automate | A campaign-level pacing tracker across all platforms (incl. LinkedIn): allocations entered once, data auto-pulled, recommended daily budgets calculated, under/over-pace flagged through the existing Tina Slack bot (given a named owner and documentation); SD approves the changes | pacing tracker & adjustment engine | Optmyzr / Shape.io budget pacing; Google Ads scripts + Sheets; custom build | 3.9–8.8 h for SD (Day 1 0.5–1 h saved + routine checks 5.5–6.5 h × 50–70% + adjustments 1–4 h × 60–80%); more across the 61-client book | M | Platform API access; agreed allocation data model; data feed (O01) | M – must match how Tier 1 allocations work, or managers won't trust it | Yes |
| SD-O03 | SD-PP02 | Change the process | Allocations are entered once (in the recommendations sheet) and the pacing sheet reads from it (linked range); only the platform change stays manual | pacing tracker & adjustment engine (process step) | Google Sheets IMPORTRANGE / linked tabs | 0.3–0.7 h (one of three Day 1 entries removed: 1–2 h ÷ 3) + fewer errors | S | Shared sheet structure | L | No |
| SD-O04 | SD-PP04, SD-PP08 | Automate | Turn on the platforms' native automated rules now: Meta frequency > 3 and CPL > 2× last month email/Slack alerts; Google Ads rules or scripts for CPL spikes and conversion drops | proactive PPC anomaly monitor (interim) | Meta Ads Manager automated rules; Google Ads automated rules / scripts | 0.5–1.5 h (assumed: fewer exploratory account checks) | S | Thresholds per client; alert channel | L–M – alert noise if thresholds are poor | No |
| SD-O05 | SD-PP04, SD-PP14, SD-B07 | Automate | A cross-account performance table with per-client rules (15-vs-15-day trend, CPL, frequency, conversions, pace) that alerts the account manager in Slack; replaces Tati's manual mid-month check (the planned Tina-bot handover can be the delivery channel) | proactive PPC anomaly monitor | Optmyzr, Adalysis, Looker Studio + Supermetrics, custom | 1.6–5.5 h (mid-month check 2–4 h × 70–100% + investigation 1–5 h × 20–30%) | M | Data feed (O01); rules per client; named bot owner | M – needs trust and tuning | Yes |
| SD-O06 | SD-PP05, SD-PP06, SD-PP14 | Augment | AI pre-call brief per client from all channels' data, which SD can query and steer (focus on that week's tests); post-call follow-up email drafted from the transcript for SD to edit | client-call prep summaries; transcripts → per-client action runsheet | Claude with Meta connector + Google Ads connector/MCP; AgencyAnalytics; Otter | 5.0–17.1 h (prep/post 16.7–34.1 h × 30–50%) | M | Google Ads data access for Claude; per-client context notes | M – she wants control over focus; must not be "generic AI updates" | Yes |
| SD-O07 | SD-PP09, SD-PP10, SD-PP11, SD-B03 | Augment | Onboarding pack: an access checklist sent at signing (with read-only one-touch access where possible) and an AI-assisted first pass of the account audit against the standard checklist, which SD reviews | 1-click audit (read-only access + AI audit) | Leadsie / similar access tools; Claude; Google Ads / Meta audit tools | 0.9–11.6 h (audit 4–8 h × 40–60% + chasing 0.5–2 h × 50%, × 0.5–1.5 onboardings) | M | Audit checklist (request); client consent | M – some clients won't grant one-touch access (Austin, L442) | Yes |
| SD-O08 | SD-PP07, SD-PP10 | People & policy | Cap concurrent onboardings per manager (for example 1–2) with a pre-agreed allocation rule and protected BAU time, rather than escalating each case to the Head of Client Services | new | Monday.com capacity view | 0–2 h (assumed; less context switching); main gain is protecting Tier 2/3 | S | Wendlley + Julia agreement; capacity data | L | No |
| SD-O09 | SD-PP12, SD-PP17, SD-B04 | Change the process | Make the campaign brief template mandatory for all tiers, with creative due dates; build in parallel while creatives are pending; combine strategy and preview approval for small campaigns | brief & proposal generator (partly) | Existing brief template; Monday.com | 0–1 h touch; cycle time ≥ 7 → 4–5 days (target) | S | Client agreement | L–M – clients' habits | No |
| SD-O10 | SD-PP13 | Automate | Automated feed that puts Five Good Friends' dashboard data (Pipedrive / WildJar / member data) beside platform data in one sheet | new | Pipedrive API, WildJar export, Sheets / Looker Studio | 0.8–7.8 h (2.2–13 h × 40–60%) | M | Client data access and consent | M – client data quality | Yes |
| SD-O11 | SD-PP08 | Automate | Scheduled script that lists candidate negative keywords (spend, no conversions) per account monthly, so SQRs happen even when capacity is tight | new | Google Ads scripts; Optmyzr | 0.25–1.5 h (1–3 SQRs × 30–60 min × 50%) | S | Script owner | L | No |
| SD-O12 | SD-PP16, SD-B05 | Change the process | QA checklist for Michaela and Tati to self-check; SD spot-checks hygiene changes and fully QAs only launches and onboardings | new | Monday.com checklist | 0.7–2.3 h (QA 2.3–4.7 h × 30–50%) | S | Checklist; agreement on which tasks need full QA | M – SD may not want to let go of QA | No |

**KPIs**

| Opportunity ID | KPI | How measured | Baseline today | Target | Leading / lagging |
|---|---|---|---|---|---|
| SD-O01 | Days pacing data is auto-refreshed | Sheet refresh log | 0 – "the sheets have broken" (L193) | 100% of working days | Leading |
| SD-O01 | Manual Meta pacing time | Time log | Daily manual Claude run (L193); minutes unknown | 0 | Lagging |
| SD-O02 | % of accounts within ±5–10% of the month's pace | Pacing tracker | unknown | ≥ 90% | Lagging |
| SD-O02 | Minutes per pacing adjustment | Time log | 15–20 min per account (L277) | ≤ 5 min | Leading |
| SD-O03 | Places budgets are hand-keyed | Process audit | 3 (L243) | 2 (then 1 with O02) | Leading |
| SD-O04 | Rules live per account | Platform rules list | 0 – "no way of knowing" (L516) | 100% of Meta accounts with frequency rule | Leading |
| SD-O05 | Days from performance drop to detection | Alert log vs report | Up to ~2 weeks / month-end (L512) | ≤ 2 days | Lagging |
| SD-O05 | Manual mid-month check hours | Time log | unknown (assumed 2–4 h) | 0 | Leading |
| SD-O06 | Prep + follow-up minutes per client call | Calendar / time log | 60–75 min per 30-min call (L161) | ≤ 30–40 min | Leading |
| SD-O06 | Follow-up email sent within 24 h | Email log | unknown | ≥ 95% | Lagging |
| SD-O07 | Days from signing to full access | Onboarding tracker | "instant" to "a lot of following up" (L414) | ≤ 2 business days | Leading |
| SD-O07 | Audit hours per onboarding | Time log | unknown – "majority of the times" (L412) | –40% | Lagging |
| SD-O08 | Concurrent onboardings per manager | Monday.com | Up to 3 (L433) | ≤ 2 | Leading |
| SD-O08 | Tier 2/3 tasks overdue | Monday.com | unknown | –50% | Lagging |
| SD-O09 | Brief → launch cycle time | Monday.com dates | ≥ 1 week (L360) | 4–5 working days | Lagging |
| SD-O09 | % of campaign requests on the template | Brief log | Tier 1 mostly (L060); others unknown | 100% | Leading |
| SD-O10 | Hours per FGF reconciliation | Time log | unknown | –50% | Lagging |
| SD-O11 | Accounts with an SQR done in the month | Script log | Not monthly – "depends on our time and capacity" (L504) | 100% | Leading |
| SD-O12 | Rework rate after QA | Monday.com status changes | unknown | < 10% | Lagging |

**Indicative ranking** (priority = Impact × Confidence × Ease)

| Rank | ID | Impact | Confidence | Ease | Priority | Tag | Reason |
|---|---|---|---|---|---|---|---|
| 1 | SD-O01 | 4 | 4 | 5 | 80 | Quick win | Clearly stated root cause (lapsed subscription); fix is a renewal or swap |
| 2 | SD-O02 | 5 | 5 | 3 | 75 | Strategic | Her #1 pain and the team's; addresses the overspend risk across 61 clients |
| 3 | SD-O06 | 5 | 4 | 3 | 60 | Strategic | Largest hours pool (16.7–34.1 h/month of prep and follow-up) |
| 4 | SD-O03 | 3 | 4 | 4 | 48 | Quick win | Removes one of three hand entries with no new tools |
| 5 | SD-O04 | 3 | 4 | 4 | 48 | Quick win | Her own rules can run today with native platform features |
| 6 | SD-O05 | 4 | 4 | 3 | 48 | Strategic | Closes the "no way of knowing" gap; needs a data feed first |
| 7 | SD-O08 | 3 | 3 | 4 | 36 | Quick win | Policy change; protects Tier 2/3 from onboarding spikes |
| 8 | SD-O07 | 4 | 3 | 3 | 36 | Strategic | Onboarding is the longest manual process; access is partly outside our control |
| 9 | SD-O09 | 2 | 3 | 5 | 30 | Fill-in | Builds on a template that already works |
| 10 | SD-O11 | 2 | 3 | 4 | 24 | Fill-in | Keeps hygiene going when capacity is tight |
| 11 | SD-O10 | 4 | 2 | 3 | 24 | Strategic | Largest client, but the frequency and effort are poorly evidenced |
| 12 | SD-O12 | 2 | 2 | 4 | 16 | Fill-in | Detected, not raised; small hours |

Ties are broken by Ease, then Impact. Automation beats augmentation for pacing and alerting because the existing semi-automated sheet broke unnoticed and manual mid-month checks are "something we have been meaning to" formalise – people-dependent routines haven't stuck.

## 7. What's working well

| Strength | Quote + timestamp |
|---|---|
| The campaign brief template for clients (her initiative) cuts admin and collation | "that way it just minimizes my work as well and just collating things from everywhere and briefing that in." ~07:04 (L060) |
| Claude has taken over ad copy and keyword grunt work; the Meta connector is a "game changer" | "honestly even Claude does that now so I haven't had to rely much on Michaela and Tati for like the grant [grunt] work" ~04:58 (L051) |
| AgencyAnalytics has automated the monthly report build | "which has now been automated because we've used another tool now, Agency Analytics for reporting." ~29:29 (L288) |
| Clear delegation through Monday.com with status flow and assign-back for review | "mainly rely on Monday for all of the briefing side of things." ~06:06 (L057) |
| A good rhythm with her current 14 clients | "I think I've set a good rhythm in terms of managing client expectations, managing the timelines, etc." ~11:01 (L095) |
| Transparency with clients: she shows the platforms live on calls | "it just gives them full visibility of what I'm trying to tell them." ~16:03 (L135) |
| Active test-and-learn management rather than set-and-forget | "I can't just set the campaigns and forget about them because it just takes a toll on the performance." ~13:58 (L116) |
| Tier 1 is protected even under load | "because tier 1 is non-negotiable. We have to do the work." ~12:35 (L110) |

## 8. Numbers and facts

| Value | Unit | Context | Quote + timestamp | Certainty |
|---|---|---|---|---|
| 14 | clients | SD's current book | "I've got 14 clients so far." ~10:47 (L088) | stated |
| 24 | channels | Across her 14 clients | "I'm managing 24 channels." ~10:45 (L087) | stated |
| Weekly / monthly | meeting cadence | Tier 1 weekly WIPs, Tier 2 monthly | "weekly meetings with weekly whips [WIPs] with D1s [T1s], monthly with D2s [T2s]." ~31:58 (L324) | stated |
| 1–2 | hours | Day 1 pacing recalibration, all accounts | "the first day would take about like one or two hours" ~15:05 (L125) | stated |
| ~2 | hours | Same, restated for all channels | "all panels, all accounts, about two hours, I would say." ~15:29 (L127) | stated |
| 30 | minutes | Pacing on other days | "on the other days just to ensure that everything's tracking well if there are changes to be made about 30 minutes." ~15:39 (L130) | stated |
| M / W / F | pacing days | Tina Slack bot's pacing updates | "Tina gives us updates and Monday, Wednesday, Friday." ~27:21 (L260) | stated (she also says "twice a week", L114) |
| 15–20 | minutes per account | Underspend adjustment calculation | "About 15, 20 minutes per account" ~28:34 (L277) | stated |
| 3 | places | Budgets updated by hand | "One is the Google Sheet, one is the Pacing Sheet, and the other is the platform itself." ~26:49 (L243) | stated |
| 60–70 | % of day | Time on the ad platforms | "about like, 60-70% of my day is on the tools" ~16:31 (L139) | stated |
| 60–75 | minutes | Prep + post per 30-min call | "about one hour, one hour, 15 minutes on that specific client before the call to prep for it and after the call" ~18:36 (L161) | stated |
| 5 | channels | easyAML | "one of my clients, EasyML [easyAML], they have five channels going on." ~18:59 (L162) | stated |
| 30–40 / 45 | minutes | easyAML prep / call length | "30 to 40 minutes just preparing updates before I jump into the call and the call itself lasts 45 minutes." ~19:28 (L163) | stated |
| 2 weeks | deadline | Monthly reports due | "we have a deadline to be sending out our monthly reports within the first two weeks of the month." ~29:12 (L286) | stated |
| 1–2 | days | Strategy turnaround after a brief | "I'll need at least one or two days to respond back with a campaign plan" ~34:25 (L359) | stated |
| ~2 | days | Client creatives turnaround | "They then send across to creatives, which is probably another couple of days." ~34:25 (L359) | stated |
| 1–2 | days | Team implementation time | "They get about a day or two days time to work on the implementation delivery side of things." ~05:40 (L054) | stated |
| ≥ 1 | week | Brief to launch | "generally we require at least a week's time provided the creatives are being sent to us on time." ~34:59 (L360) | stated |
| ≥ 1 | week | Onboarding audit / strategy once access is granted | "it takes about at least a week for all of that analysis, auditing, campaign planning, strategizing work to happen." ~41:13 (L415) | stated |
| 3–4 | days | Conversion tracking | "which also takes another three, four days for all the testing, unless we have to prioritize it." ~41:41 (L418) | stated |
| 3–7 | days | Campaign build in onboarding | "which would probably be a week, maybe like three or four days of time." ~41:56 (L419) | stated |
| 0–3 | onboardings at once | Concurrency, no cap | "Sometimes we don't have onboarding. Sometimes we have like three onboardings at once." ~43:09 (L433) | stated |
| 2 | new clients | Recent onboardings | "Let's say we've got a new client, two on board and last couple of weeks" ~39:37 (L411) | stated (garbled) |
| 15 vs 15 | days | Mid-month performance comparison | "The last 15 days versus the 15 days before." ~46:02 (L464) | stated |
| > 3 | ad frequency | Meta fatigue trigger | "So whenever the frequency of any ad is more than three" ~51:07 (L510) | stated |
| > 2× | CPL vs last month | Proposed alert rule | "the overall CPL, for example, has… gone up more than 2x of last month" ~52:21–52:37 (L524–L525) | stated |
| > 50% | of weekly hours | Five Good Friends | "it takes up majority of my week's hours" ~08:59 (L073) | stated |
| 2 | data systems | FGF dashboard sources: Pipedrive and WildJar | "they've got their own dashboard that takes data from their Pipedrive and Wildjar" ~08:59 (L073) | stated |

## 9. Tools, data and workarounds

- **Official tools:** Google Ads and Meta (analysis, pacing, live on calls); LinkedIn Ads (tests); Monday.com (briefing, status, assign-back); Google Sheets (budget recommendations, Pacing Sheet / pacing input documents); AgencyAnalytics (monthly reports); Otter (call notes); Meta Ads Library (competitor creative); campaign brief template (client-facing); onboarding audit document and launch checklist; Supermetrics (lapsed); Tina Slack agent bot (OpenClaw workspace – M/W/F pacing updates).
- **Shadow tools / workarounds:** Claude connected to Meta Ads for analysis ("game changer"); Claude for ad copy and keyword research; Meta pacing done manually in Claude every day by Wendlley (Performance Director) since Supermetrics lapsed; SD's own formulas in the allocation sheet for pacing adjustments.
- **Same data in more than one place:** budget allocations (recommendations sheet, Pacing Sheet, platforms); Five Good Friends performance (platforms vs client dashboard vs member data); call action items (Otter vs SD's email).
- **Data or access she needs but doesn't have:** a cross-account, campaign-level performance and pacing view; a Claude connector for Google Ads; automatic pacing data (Supermetrics); client account access at onboarding; client creatives on time.

## 10. Knowledge and dependency

| What | Who (role) | If absent |
|---|---|---|
| Campaign-level budget allocations and pacing formulas (in her own allocation sheets) | SD | Pacing adjustments for 14 clients / 24 channels stall or get done without the allocation logic |
| Strategy, analysis and QA for all her accounts | SD | Michaela and Tati can implement but not decide; QA queue stops |
| Five Good Friends reconciliation (which source is "truth") | SD | Largest client's analysis loses continuity |
| M/W/F pacing updates | Tina Slack agent bot – no visible owner or documentation | Pacing updates stop, possibly unnoticed; under/over-spend goes unflagged |
| Mid-month 15-vs-15 performance check | Tati (Tatiana Stinson, Coordinator) – planned handover to the Tina bot | Performance drops go unflagged until SD is in the account |
| Daily manual Meta pacing in Claude | Wendlley Simoes (Performance Marketing Director) 👤 | No Meta pacing data; director time absorbed daily |
| Conversion tracking | Tracking specialist (likely Liam Lau, contractor – inferred) | Onboarding launches wait |
| Onboarding capacity decisions | Julia Van Der Linden (Head of Client Services) | Overload rests with each manager |

## 11a. Clients mentioned

| Client | Tier (context pack) | What was said |
|---|---|---|
| Five Good Friends | Tier 1 (SEO list); largest Google Ads budget $168,000, SD | Takes up the majority of her weekly hours; own dashboard from Pipedrive and WildJar; several sources of truth; analysis and test plans every 1–2 weeks (uncertain) |
| easyAML | Not on the SEO tier list; Google Ads $18,200, manager DM per context pack | Five channels; 30–40 min prep for a 45-minute call; SD calls it her client (contradiction) |
| Leaselab | Tier 1 | Named only as Austin's example (L069) – nothing said |
| "Holstroms" | Unknown – not in the context pack | "This is relevant to Holstroms" in the context of high-CPL SQR triggers (L503) – possibly mis-transcribed |
| Unnamed pitch client | – | "we're now switching [pitching?] to another client next week" – pitch work competes with BAU (L096) |
