# Part A – Transcript extraction: Sid (Siddharth) Bali (Technical SEO Specialist)

**Source and method notes**
- Transcript: meeting notes "Sid - Workflow & Process Interview", 4 Nov 2026, 11:30 am (Melbourne). Full transcript retrieved (588 utterances, ends at sign-off) – not truncated. The AI summary was not used as a source.
- **Timestamps:** the transcript has no timestamps. Every timestamp below is written `~mm:ss (L###)`: L### is the utterance number in `transcript.md`; ~mm:ss is estimated from cumulative word position across ~40 minutes (60-minute booking; Austin closed "We can give you 20 minutes back in your day", L575; the page was last edited 41 min after the start).
- **Speakers:** the diariser labelled Austin as A and split Sid across labels B and C (plus short fragments D, E, F, G, H – backchannel or background noise). All non-Austin lines are treated as Sid. A few A-labelled lines are probably Sid (e.g. L009, L198).
- **Name and term corrections (transcription):** "cloud" → Claude · "Cloud and Chrome" → Claude in Chrome · "make" → Make.com · "Monday" → Monday.com · "EQ salary" → EQ Saddlery · "Nadia" → Nadiya (Hisham) · "Aparity" → Aperitif · "HubSort" → HubSpot · "Macs" → Max (Claude plan) · "Notion's really good" / "thickness" → Figma (Austin self-corrects, L312) · "Adriatic Furniture" → Adriatic (Tier 3). Unresolved: "Kshalo" (L081 – something in HubSpot that holds logins), "ASFROJS" (L070 – typed prompt), "trendsite.com.au" (L269 – JS-heavy site Sid shared; client status unknown).
- Hours are costed at **$80/hr internal labour cost**. Process totals are Sid's time only; no other actors' time was described with figures.

---

## 0. Interview card

| Field | Detail |
|---|---|
| Interviewee | Sid (Siddharth) Bali |
| Role | Technical SEO Specialist (also runs end-to-end SEO for a few clients; built and runs the Monday.com + Make system) |
| Team | Organic |
| Date / length | 4 Nov 2026 · ~40 min (booked 60) |
| Interviewer | Austin Smith (Transpera AI) |
| Clients managed | 5 end-to-end (said four, then "Actually, five", L249–L255); ~15 technical-only ("estimation it would be around 15", L322) – stated, rough |
| Channels / services | Technical SEO (audits, on-site fixes, page uploads), SEO strategy and client comms for end-to-end clients, content and link briefs, monthly reporting, Monday.com/Make administration |
| Reports to | Karl Zaharopoulos (per context pack – not discussed) |
| Hands work to | Client owners/SEO managers (Monday update + plain-English explanation in client sheet for their monthly report), content team (briefs), link building (briefs), clients (reports, meetings) |
| Receives work from | Monday.com SEO delivery board (auto-generated monthly tasks), client owners/strategists (incl. forwarded email chains), clients (email), sales via HubSpot → Make → Monday |

## 1. Five-line summary

1. The HubSpot → Make → Monday.com handover is automated and works, but it sets the deal closer as the Monday "client owner", which is always wrong; Sid fixes every new client by hand and asks "if I'm not there, who's going to do it?" ~35:09 (L501).
2. Sid is a single point of failure for the whole Monday/Make task system (built it, admin, receives every notification, only person fixing owner assignment).
3. Email is Sid's biggest daily drain: about an hour a day ~30:25 (L421), worsened by forwarded email chains (~30 min each to untangle, L190) and requests sent outside Monday; his own Claude "Organizer" routine doesn't surface what needs action.
4. Content/page uploads loop with clients – one page has gone back and forth for a month ~16:16 (L204–L207) – and it is his "magic wand" fix; he liked Austin's Figma-as-QA idea but questioned JavaScript-heavy sites.
5. Technical delivery itself is planned (technical action plan at onboarding, allocated hours per client, audits already automated via Claude MCP), and Sid says it would scale to +20 technical clients; client communications would break first. The team's Claude Pro-for-Teams token limits are "severely limiting" (L381).

## 1a. Time allocation

Sid gave no percentages. Only email time was quantified.

| Activity | % / hours | Billable? | Quote + timestamp | Certainty |
|---|---|---|---|---|
| Technical tasks (audits, fixes, uploads) | Largest share – "dominates"; ~33–53% (≈50–80 h/month of ~152 h, see SB-P02) | Billable | "It would definitely be the technical task." ~12:58 (L160) | stated (dominant, no number); % estimated – assumes ~152 working h/month; confirm against Monday time logs |
| Email triage and responses | ~1 h/day ≈ 12–13% (≈20–22 h/month) | Mostly non-billable | "In a day, an hour." ~30:25 (L421) | stated (1 h/day); % estimated: 1 h ÷ 7.6–8 h day |
| Client comms, meetings, reporting (5 end-to-end clients) | ~10–15% (assumed) | Billable | "different clients have different dates where they want to have the meeting" ~24:50 (L354) | assumed – not quantified |
| Content and link briefs | ~2–3% (week 1) | Billable | "Similarly with link building, but that's like a two minute process." ~24:37 (L353) | stated (link brief 2 min); rest assumed |
| Ad hoc requests and overdue tickets | Unquantified, constant; peaks week 4 | Mixed | "you're always getting swamped with some other message, some other email" ~13:14 (L163) | stated qualitatively |
| Monday.com/Make administration | Not discussed (assumed 2–6 h/month) | Non-billable | "I run the Monday shindig" ~28:33 (L396) | assumed |

- **Busy vs quiet:** week 1 is busy (reports and content/link briefs); weeks 2–3 are technical tasks, client comms and client meetings (dates vary by client); week 4 is overdue tickets, ad hoc work, the end-of-month client health check and prep for next month's reporting – "there will be overdue tickets always" ~24:50 (L354). Day: agenda set "by like 10 a.m." ~04:03 (L051).
- **Billable vs non-billable:** not discussed directly. Assumed split: about 80–85% client-attributable (technical work, briefs, reports, meetings, much of client email), about 15–20% internal (inbox triage of internal mail and Monday notifications, Monday/Make administration). Confirm with Monday time data.

## 2. Processes

Flags: ⏸ bottleneck · 👤 single-person dependent · ⌨️ manual copy / re-keying · ⚠️ error-prone. Interviewee = SB.

### SB-P01 · Internal task management – daily agenda and inbox triage

- **Trigger:** Start of each working day; then incoming email/Slack all day.
- **Owner role:** Technical SEO Specialist (self).
- **Frequency:** Daily, ~20–22 working days/month; across all ~20 clients.
- **Tools/files:** Gmail (labels: per client, "to respond", updates, platforms – L396), Slack (DMs, personal "Organizer" channel), Monday.com, a Claude routine that scans Gmail + Monday and posts a daily list to "Organizer" (L042).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Claude routine compiles daily list from Gmail + Monday into Slack "Organizer" | Claude routine (automated) | Claude, Gmail, Monday, Slack | 0 | Overnight/morning run | Sid | stated (L042) |
| 2 | Review agenda, Monday tasks due, emails, Slack; plan day | Technical SEO Specialist | Monday, Gmail, Slack | 15–30 | – | – | estimated: day structured "by like 10 a.m." (L051); 15–30 min assumed for the planning itself |
| 3 | Triage and respond to email through the day (24-hour client SLA) ⌨️ ⚠️ | Technical SEO Specialist | Gmail | ~60 (all triage incl. step 2 email) | Clients wait up to 24 h | Clients / colleagues | stated: "In a day, an hour." (L421); SLA stated (L030) |
| 4 | Turn requests into actionable tasks (often manually, as many arrive by email/DM, not Monday) ⌨️ | Technical SEO Specialist | Gmail/Slack → Monday or notes | incl. in step 3 | – | Self | stated qualitatively (L030, L039) |

- **Happy path total:** touch ~60–75 min/day (email hour stated + 0–15 min planning not already in it); elapsed: day set by ~10 a.m.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Missed action item | Routine lists items but no visual cue; email/Slack ask slips | Not stated (assume 2–6/month) | Last-minute rush, possible client chase | 15–30 min each | Sid, client | stated that it happens (L046–L050); rate assumed |
| Forwarded email chain | Colleague forwards long chain with multiple sheet versions | Not stated (assume 2–6/month) | Reconstruct thread, find current file version | 30 min each | Sid | stated (time, L190); rate assumed |
| Accidentally archived email | Read-and-archive habit | Not stated (assume 2–4/month) | Search archive | 10–20 min each | Sid | stated that it happens (L413); time and rate assumed |
| Monday notification flood | Sid is admin, gets every change | Daily | Skim/delete noise | Inside the 1 h/day | Sid | stated (L396) |

- **Decision points:** each email → respond now / turn into task / ignore (split unknown; Sid says much is "not really necessary", L391) – stated qualitatively.
- **Volume (team):** Austin believes the whole team has the same problem (L425) – interviewer view, not evidenced. Per-person only.
- **Monthly hours:** Email 1 h × 20–22 days = 20–22 h (stated rate, estimated month). Bad paths: low = 2 chains × 0.5 h + 2 missed × 0.25 h + 2 archive × 0.17 h ≈ 1.8 h; high = 6 × 0.5 + 6 × 0.5 + 4 × 0.33 ≈ 7.3 h. Planning step mostly inside the email hour; not added. **Total ≈ 21–26 h/month** (rounded; 20+1.8 → 21; 22+7.3 → 29, trimmed to 26 because the 1 h/day already includes some of this rework – estimated).
- **Monthly cost:** 21 × $80 = **$1,680** to 26 × $80 = **$2,080**.
- **Flags:** step 3 ⌨️ ⚠️ (manual triage, items missed); step 4 ⌨️ (re-keying requests into tasks).

### SB-P02 · Technical SEO audit & fixes

- **Trigger:** Monthly technical tasks auto-created on the Monday SEO delivery board from each client's allocated hours (e.g. "five hours of onsite technical work", L512) and the technical action plan set at onboarding (L116); plus ad hoc requests.
- **Owner role:** Technical SEO Specialist (and the technical team).
- **Frequency:** Continuous; ~20 clients (5 end-to-end + ~15 technical-only).
- **Tools/files:** Monday.com "SEO delivery portal" (L062), per-client sheet/technical action plan, Claude with an MCP (audits), "another tool" for audits, client CMS (WordPress, Shopify, Webflow), HubSpot (logins), LastPass (migration in progress).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Open task list, pick tasks by due date | Technical SEO Specialist | Monday SEO delivery board | 2–5 | – | – | estimated from demo (L063) |
| 2 | Open client sheet, check what's planned for the month | Technical SEO Specialist | Client sheet / technical action plan | 2–5 | – | – | estimated (L065–L067) |
| 3 | Run technical audit in parallel (Claude MCP or other tool) | Technical SEO Specialist + Claude | Claude MCP / audit tool | 5–15 hands-on; audit runs "on the side" | Audit run time (minutes) | – | stated method (L068, L072–L073); time assumed |
| 4 | Look up client CMS login in HubSpot (not Monday) ⌨️ | Technical SEO Specialist | HubSpot ("Kshalo"?), LastPass | 2–5 | – | – | stated as pain (L078–L084); time assumed |
| 5 | Make the fix (title/meta length up to full site restructure) | Technical SEO Specialist | Client CMS | 15–240+ (varies with allocated hours and severity) | – | – | stated range of work (L109); time assumed |
| 6 | Update client sheet with plain-English explanation | Technical SEO Specialist | Client sheet | 5–10 | – | Client owner | stated (L098); time assumed |
| 7 | Post Monday update tagging client owner ("task has been done") ⌨️ | Technical SEO Specialist | Monday | 2–5 | Owner reads it at reporting time | Client owner / SEO manager | stated (L099–L101); time assumed |

- **Happy path total:** touch ~35–280 min per task (driven by step 5); elapsed within the month, due dates on Monday.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Problem spawns sub-problems | Fix uncovers related issues | "sometimes" (L162) | Investigate sub-issues, may overrun allocated hours | Unknown (assume 30–120 min) | Sid, other tasks slip to week 4 | stated qualitatively; time assumed |
| Ad hoc interrupts | Urgent message/email | Daily (L163) | Context switch | Not quantified | Sid | stated |
| Overdue tickets carried to week 4 | Above two | Every month ("there will be overdue tickets always", L354) | Catch-up week | Not quantified | Sid, clients | stated |
| Split ownership (strategy by one person, technical by another) | Client not end-to-end | For ~15 technical-only clients | Coordinate, "move pieces around" | Not quantified | Sid, strategist | stated (L151) |

- **Decision points:** Task scope is pre-decided by the technical action plan ("everything that we do for every month has already been strategize at the start", L117); depth depends on "the number of hours allocated for that month for the task and the severity" (L109) – stated, no split.
- **Volume:** Not stated. Example allocation: Adriatic 5 h/month on-site technical (L512).
- **Monthly hours:** Not stated. Estimated as the dominant share of a ~152 h month: 50–80 h (assumes ~33–53% of hours; lowered from "dominates" to leave room for 1 h/day email and client work). **Assumed – confirm with allocated technical hours per client in the Monday/master sheet.**
- **Monthly cost:** 50 × $80 = **$4,000** to 80 × $80 = **$6,400** (mostly billable delivery, not waste).
- **Flags:** step 4 ⌨️ (tool switch for credentials); step 7 ⌨️ (status written twice – sheet and Monday); step 5 👤 for technical depth.

### SB-P03 · Monthly SEO delivery – content and link briefs (end-to-end clients)

- **Trigger:** Week 1 of each month (L351).
- **Owner role:** SEO strategist for the client (Sid for his 5 end-to-end clients).
- **Frequency:** Monthly × 5 clients.
- **Tools/files:** Briefs to content team; link-building brief; Monday tasks auto-created per client (e.g. "Adriatic Furniture needs 200 monthly words", "five links", L511–L512).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Write content briefs for the month | SEO strategist (Sid) | Brief doc / content tracker | 20–45 per client | – | Content team | assumed – not timed |
| 2 | Write link-building brief | SEO strategist (Sid) | Link brief / Monday | 2 per client | – | Link building | stated: "that's like a two minute process" (L353) |

- **Happy path total:** 22–47 min per client; elapsed within week 1.
- **Bad paths:** Not discussed.
- **Decision points:** Not discussed.
- **Monthly hours:** 5 clients × 22–47 min = 110–235 min ≈ **2–4 h** (estimated).
- **Monthly cost:** 2 × $80 = **$160** to 4 × $80 = **$320**.

### SB-P04 · Monthly reporting (end-to-end clients)

- **Trigger:** Week 1 (L347–L350).
- **Owner role:** SEO strategist (Sid for 5 clients). For technical-only clients, Sid feeds explanations into the client owner's report (L101).
- **Frequency:** Monthly × 5 clients.
- **Tools/files:** Not named (AgencyAnalytics per context pack – not confirmed here). Sid says reporting is already optimised: "reporting we've optimized that's fine" ~27:30 (L384).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Create report | SEO strategist (Sid) | Reporting tool | 45–90 per client | – | Client | assumed – not timed |
| 2 | Present/discuss at client meeting (see SB-P05) | SEO strategist | Meeting | – | Meeting date set by client | Client | stated (L354) |

- **Bad paths:** Not discussed.
- **Monthly hours:** 5 × 45–90 min = **3.75–7.5 h ≈ 4–8 h** (assumed).
- **Monthly cost:** 4 × $80 = **$320** to 8 × $80 = **$640**.

### SB-P05 · Client meetings & prep (end-to-end clients)

- **Trigger:** Client-specific meeting dates, weeks 2–3 (L354); client emails (24-hour response limit, L030).
- **Owner role:** SEO strategist (Sid).
- **Frequency:** Monthly meeting × 5 clients, plus ongoing comms.
- **Tools/files:** Email, meetings.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Prep for meeting | SEO strategist | Report, sheets | 30–60 per client | – | – | assumed |
| 2 | Run meeting, "updating them about everything" | SEO strategist | Call | 30–60 per client | Scheduled by client | Client | assumed (meeting stated, L354) |

- **Bad paths:** Scaling – with 5 more end-to-end clients "It's the client side where I will definitely be lacking" (L338).
- **Monthly hours:** 5 × 60–120 min = **5–10 h** (assumed; ongoing client email counted in SB-P01).
- **Monthly cost:** 5 × $80 = **$400** to 10 × $80 = **$800**.

### SB-P06 · Performance monitoring & alerting – end-of-month client health check

- **Trigger:** Week 4 (L355).
- **Owner role:** SEO strategist (Sid).
- **Frequency:** Monthly × 5 clients (possibly also technical issues for others – "technically if there's anything new that's come up", L355).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Review performance for dips and wins; flag to client | SEO strategist | Analytics/rank tools (not named) | 10–25 per client | – | Client / next report | stated activity (L355); time assumed |

- **Bad paths:** Dips only spotted at month-end (detected – no in-month alerting described).
- **Monthly hours:** 5 × 10–25 min ≈ **1–2 h** (assumed).
- **Monthly cost:** **$80–$160**.

### SB-P07 · NEW: Content upload & page build (CMS) – incl. client page approval

- **Trigger:** Content written by the content team is handed back for upload (L202); client page changes.
- **Owner role:** Technical SEO Specialist.
- **Frequency:** Not stated (assume 3–6 pages/month).
- **Tools/files:** Client CMS (Webflow, WordPress, Shopify), email for feedback; AI-generated HTML that needs hand editing (L212–L213).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Receive approved copy from content team | Content team → Sid | Doc | – | Depends on content approval | Sid | stated (L202) |
| 2 | Build/upload page in client CMS ⌨️ | Technical SEO Specialist | Webflow/WordPress/Shopify | 30–60 | – | Client | assumed |
| 3 | Client reviews; feedback by email ⏸ | Client | Email | – | Days | Sid | stated qualitatively (L204–L207) |
| 4 | Apply changes; repeat until approved ⚠️ | Technical SEO Specialist | CMS | – | – | Client | stated |

- **Happy path total:** 30–60 min touch; elapsed days (client review).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Iteration loop on pixels/elements | Unclear requirements; client team members change their minds ("someone else in the team said this", L235) | At least one current page; assume 1–2 pages/month | Repeated change → review rounds; one page "for a month" (L205) | 2–4 h touch per affected page (assumed); elapsed up to a month (stated) | Sid, client, page go-live | stated (elapsed); touch and rate assumed |
| Client can't use Webflow themselves | Client attempts own edits, can't find controls | Not stated | Sid talks client through, then does it anyway | Inside above | Sid, client | stated (L235) |
| JavaScript-heavy site | Mock-up/QA tools can't render | Not stated | Manual work | Unknown | Sid | stated concern (L263) |

- **Decision points:** Client approves page first time vs requests changes – split unknown (assumed 70–80% / 20–30%).
- **Monthly hours:** Happy: 3–6 pages × 0.5–1 h = 1.5–6 h. Bad: 1–2 pages × 2–4 h = 2–8 h. **Total ≈ 3.5–14 h** (assumed).
- **Monthly cost:** 3.5 × $80 = **$280** to 14 × $80 = **$1,120**.
- **Flags:** step 3 ⏸ (waits on client); step 4 ⚠️ (rework loop).

### SB-P08 · Sales to delivery handover – HubSpot → Make → Monday new-client set-up

- **Trigger:** Deal marked signed in HubSpot (L467–L474).
- **Owner role:** Automated (Make scenario built by Sid); owner assignment fixed manually by Sid.
- **Frequency:** Per new client (rate not stated; assume 1–4 SEO clients/month).
- **Tools/files:** HubSpot (CRM, client info and credentials), Make.com (webhooks/scenarios), Monday.com (client board, onboarding checklist, SEO delivery board, two-way sync), sales form submission.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Deal signed in HubSpot | Sales / founder | HubSpot | – | – | Make | stated (L490) |
| 2 | Make scenario fires; Monday creates client item (channels, tier, form data) and SEO onboarding group/checklist | Make + Monday (automated) | Make, Monday | 0 | Seconds | Monday client board | stated (L475, L490–L507) |
| 3 | Client owner auto-set to deal closer – wrong ⚠️ 👤 | Make (automated) | Monday | 0 | – | – | stated (L477, L496–L498) |
| 4 | Sid asks who the client owner is and reassigns by hand ⏸ 👤 ⌨️ | Technical SEO Specialist | Slack/ask → Monday | 5–15 | Until someone answers (not stated) | Assigned client owner | stated manual (L501); time assumed |
| 5 | Strategy created; monthly recurring tasks (words, links, tech hours) generated from the sheet; two-way sync client board ↔ SEO delivery board | Strategist + Monday automation | Monday | – | – | Delivery team | stated (L508–L521) |

- **Happy path total:** 5–15 min touch per new client; elapsed hours–days until owner confirmed (assumed).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Owner not corrected (Sid away) | Sid absent | Not stated | Tasks sit with deal closer; "confusion about who's going to do the task" (L481) | Unknown | New client, delivery team | stated risk (L501) |
| Old HubSpot ticket ↔ Monday ID link removed | Migration to Monday-only tasks | One-off (done) | – | – | – | stated (L462–L465) |

- **Decision points:** Who is the client owner? – decided outside the system, not recorded at deal stage (stated).
- **Monthly hours:** 1–4 clients × 5–15 min = 5–60 min ≈ **0.1–1 h** (assumed rate).
- **Monthly cost:** **$8–$80**. Low hours; the issue is risk and single-person dependency, not time.
- **Flags:** step 3 ⚠️; step 4 ⏸ 👤 ⌨️.

### SB-P09 · Internal task management – Monday.com and Make system administration

- **Trigger:** Ongoing; changes, broken scenarios, new boards; admin notifications.
- **Owner role:** Technical SEO Specialist (de facto system owner – "because I also created it", L078; "I run the Monday shindig", L396).
- **Frequency:** Ongoing.
- **Tools/files:** Make scenarios (incl. "HubSpot client notification", L462), Monday boards and automations.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Maintain scenarios/boards, fix issues, add columns | Technical SEO Specialist 👤 | Make, Monday | Not discussed (assume 120–360 per month) | – | – | assumed |
| 2 | Receive all Monday change notifications | Technical SEO Specialist | Email | Inside SB-P01 | – | – | stated (L396) |

- **Bad paths:** Sid absent → no one to fix owner assignment or scenarios (L501) – stated for owner assignment; wider dependency detected.
- **Monthly hours:** **2–6 h** (assumed – confirm with Sid).
- **Monthly cost:** **$160–$480**.

### Process totals

| ID | Process | Monthly hours (all actors) | SB-only hours | Monthly cost (all actors) |
|---|---|---|---|---|
| SB-P01 | Internal task management – daily agenda and inbox triage | 21–26 | 21–26 | $1,680–$2,080 |
| SB-P02 | Technical SEO audit & fixes | 50–80 | 50–80 | $4,000–$6,400 |
| SB-P03 | Monthly SEO delivery – content and link briefs | 2–4 | 2–4 | $160–$320 |
| SB-P04 | Monthly reporting | 4–8 | 4–8 | $320–$640 |
| SB-P05 | Client meetings & prep | 5–10 | 5–10 | $400–$800 |
| SB-P06 | Performance monitoring & alerting (end-of-month health check) | 1–2 | 1–2 | $80–$160 |
| SB-P07 | NEW: Content upload & page build (CMS) | 3.5–14 | 3.5–14 | $280–$1,120 |
| SB-P08 | Sales to delivery handover (HubSpot → Make → Monday) | 0.1–1 | 0.1–1 | $8–$80 |
| SB-P09 | Internal task management – Monday.com/Make administration | 2–6 | 2–6 | $160–$480 |
| **Total** | | **88.6–151.0 h** | **88.6–151.0 h** | **$7,088–$12,080** |

The high ends can't all happen in the same month: SB's high-end total (151 h) is about one full-time month (~152–160 h) with nothing left for ad hoc work. Treat the low-to-mid range as more realistic and confirm with Monday.com time and allocated-hours data. Team-wide volumes were not given.

## 3. Pain points and problems

| ID | Pain point | Source | Category | Anchor | Process | Impact | How often | Severity 1–5 | Quote + timestamp | Certainty |
|---|---|---|---|---|---|---|---|---|---|---|
| SB-PP01 | Daily Claude "Organizer" routine doesn't flag what needs action; emails and Slack asks slip and become last-minute | interviewee | Missing visibility | Technology, AI & stack | SB-P01 | Time; client (late replies) | Ongoing | 3 | "I still miss out on things that I need to do, like emails that I need to respond to" ~03:28 (L046) | stated |
| SB-PP02 | About an hour a day on email triage, much of it unnecessary | interviewee | Manual / repetitive work | Operations capacity & process | SB-P01 | ~20–22 h/month ($1,600–$1,760) | Daily | 4 | "In a day, an hour." ~30:25 (L421); "there's a lot of random shit that we get that's not really necessary" ~28:11 (L391) | stated (1 h/day); monthly estimated |
| SB-PP03 | Requests arrive as forwarded email chains with several conflicting sheet versions; ~30 min to untangle each | interviewee | Rework / errors | Operations capacity & process | SB-P01 | ~1–3 h/month | Not stated (assume 2–6/month) | 3 | "And then I'm just stuck for 30 minutes trying to figure out, OK, this email is a response to this one." ~15:10 (L190) | stated (time); rate assumed |
| SB-PP04 | Colleagues send task requests by email and Slack DM instead of Monday, so work sits outside the task system | interviewee | Tool not used / adoption | Operations capacity & process | SB-P01 | Missed/late tasks; manual re-keying | Ongoing | 3 | "any emails or any personal Slack messages with things to do because not everybody uses Monday to like, you know, set up a task." ~02:50 (L039) | stated |
| SB-PP05 | Read-and-archive habit buries important emails | interviewee | Rework / errors | Operations capacity & process | SB-P01 | Search time | Not stated | 2 | "And then I realize I've archived something that I shouldn't have." ~29:52 (L413) | stated |
| SB-PP06 | As Monday admin, Sid receives every Monday change notification | interviewee | Missing visibility | Technology, AI & stack | SB-P01 / SB-P09 | Inbox noise | Daily | 2 | "because I run the Monday shindig, I get every fucking notification out there." ~28:33 (L396) | stated |
| SB-PP07 | Web page uploads loop with clients for weeks over pixels and elements; requirements unclear and client team changes its mind | interviewee | Client friction | Client experience & delivery | SB-P07 | 2–8 h/month rework; page live up to a month late | At least one live case | 4 | "I have been going back and forth. for a month. for a singular page." ~16:16 (L204–L206) | stated (elapsed); hours assumed |
| SB-PP08 | Webflow is complex; clients can't find controls, so Sid relays and does edits for them | interviewee | Client friction | Client experience & delivery | SB-P07 | Extra rounds | Not stated | 2 | "Like Webflow is not easy." ~18:36 (L231) | stated |
| SB-PP09 | Client logins sit in HubSpot (sales CRM), not with the Monday task; LastPass migration not finished | interviewee | Duplicate data entry | Technology, AI & stack | SB-P02 | 2–5 min tool switch per task; credentials spread over two systems | Every task needing access | 2 | "But then we still have to go into HubSpot and go into Kshalo and look into the login information" ~07:08 (L081) | stated; time assumed |
| SB-PP10 | Make sets the HubSpot deal closer as Monday client owner – always wrong; Sid fixes each new client by hand | interviewee | Unclear ownership | Operations capacity & process | SB-P08 | Confusion over who does onboarding tasks | Every new client | 4 | "the person who closes the deal on HubSpot is never the person who's going to manage the client account." ~33:23 (L477) | stated |
| SB-PP11 | Monday/Make system depends on Sid (built it, admin, sole fixer); no documented backup | interviewee (owner-fix risk) + detected (wider system) | Single point of failure (person) | Technology, AI & stack | SB-P08 / SB-P09 | Handover and task automation stall if he's away | Ongoing risk | 4 | "But if I'm not there, who's going to do it? It needs to have that system in place." ~35:09 (L501) | stated for owner fix; wider dependency detected |
| SB-PP12 | Claude Pro-for-Teams token limits are restricting a team that now relies on AI; Claude in Chrome burns most tokens; no shared skills/prompt library | interviewee | Single point of failure (tool) | Technology, AI & stack | Agency-wide (all AI-assisted work) | Work blocked when limits hit; not quantified | Ongoing (worse "over the last month") | 3 | "it's severely limiting what the team can do because honestly everyone's become very reliant on AI." ~27:17 (L381) | stated; impact not quantified |
| SB-PP13 | Client communications would break first if end-to-end load grows; already "borderline" | interviewee (answering Austin's hypothetical) | Capacity / overload | Operations capacity & process | SB-P05 | Client experience, retention risk | If +5 end-to-end clients | 3 | "It's the client side where I will definitely be lacking." ~23:24 (L338) | stated (hypothetical) |
| SB-PP14 | Split ownership (strategist vs technical) adds coordination; no performance impact | interviewee | Waiting / handoff delay | Client experience & delivery | SB-P02 | Coordination time | ~15 technical-only clients | 2 | "it's not a hindrance to performance, but I think it just gets in the way of work at times" ~12:23 (L151) | stated |
| SB-PP15 | Constant ad hoc requests and sub-problems push planned tickets into an overdue catch-up week | interviewee | Capacity / overload | Operations capacity & process | SB-P02 | Overdue tickets every month | Daily / monthly | 3 | "there will be overdue tickets always." ~24:50 (L354) | stated |

**Top 3 by severity – root cause and match**

1. **SB-PP02 Email ~1 h/day (sev 4).** Why? Too much inbound, much of it irrelevant. Why? Email is the default channel for client asks, internal requests, forwarded chains and Monday notifications; nothing filters or routes it. Why? No intake rule (requests → Monday) and no triage layer; the personal Claude routine summarises but doesn't prioritise. **Root cause:** no agreed request-intake channel plus no automated triage. **Match:** partial match to #25 "Reminders go unacted; a broken reminder bot went unnoticed"; mostly **new** – "Email is the default intake for tasks; staff lose ~1 h/day to triage".
2. **SB-PP07 Page upload loops (sev 4).** Why? Feedback comes in rounds by email. Why? Requirements not agreed up front, no visual mock-up to annotate, several client stakeholders, no cap on revision rounds. **Root cause:** no structured page-approval step (single consolidated feedback on a visual draft). **Match:** partial – #11 "Content stalls at client approval – or the tracker can't show what's finished" (same pattern at the page-build stage).
3. **SB-PP10 / SB-PP11 Owner assignment and Sid dependency (sev 4).** Why is the owner wrong? Make maps the HubSpot deal owner. Why? The delivery owner isn't decided or recorded at deal stage, so there's no field to map. Why does Sid fix it? He built the system and nobody else owns it. **Root cause:** delivery-owner allocation has no defined decision point or owner, and the automation stack has no documentation or second admin. **Match:** partial – #21 "Slack bots and agents have no visible owner or documentation" (same pattern for Make/Monday automations) and #8 "Documentation and internal tooling held by the founder" (here held by Sid, not the founder). Owner-assignment gap is **new**.

## 4. Bottlenecks

| ID | Step | Waiting on | Typical wait | Affected | Knock-on |
|---|---|---|---|---|---|
| SB-B01 | Page approval (SB-P07 step 3–4) | Client feedback rounds | Days per round; one page a month (L205) | At least 1 page now; assume 1–2/month | Page go-live delayed; content value delayed; Sid's time |
| SB-B02 | New-client owner assignment (SB-P08 step 4) | Someone confirming who owns the account; Sid being available | Not stated | Every new client (1–4/month assumed) | Onboarding tasks unclear; stalls if Sid away |
| SB-B03 | Requests stuck in inbox/DMs before becoming tasks (SB-P01) | Sid noticing them | Until last minute (L050) | Unknown | Late responses; overdue tickets |
| SB-B04 | Week-4 overdue tickets (SB-P02) | Ad hoc work displacing planned tasks | Up to a week | All clients | Catch-up week every month |

## 4a. Decisions and approvals

| Decision | Who decides (role) | Who waits | Typical time | Lands on leadership? |
|---|---|---|---|---|
| Who is client owner for a new client | Not defined – Sid asks around (L501); Austin suggests sales could own it but "that's putting a lot of trust in someone" (L541) | Sid; new client's onboarding tasks | Not stated | Unclear – probably department lead (Karl/Laura) or Julia; confirm |
| Yearly technical action plan per client | Strategist + technical team at onboarding (L116) | Technical team | At onboarding | No |
| Depth of monthly technical work | Allocated hours and severity (L109) | – | – | No |
| Web page approval | Client (several stakeholders) | Sid | Days to a month (L205) | No |
| Upgrade Claude plan (Pro for Teams → Max) | Not stated – assumed founder (Joe) | Whole team | Not stated | Yes (assumed) |
| Which emails need action | Sid, manually | Clients/colleagues | Within 24 h for clients (L030) | No |

## 5. Suggestions for change (as raised in the interview)

| ID | Idea | Source + reaction | Process | Quote + timestamp |
|---|---|---|---|---|
| SB-S01 | Personal "second brain"/PA that watches Gmail, Slack and Monday and pushes a prioritised to-do list | interviewee (Austin named it "second brain… PA"; Sid: "Yes") | SB-P01 | "I need something That can like, you know, be like a push notification or something like on my screen" ~13:56 (L175) |
| SB-S02 | Email triage that labels what matters (e.g. "respond to client", "task request") | interviewee raised need; Austin proposed categories, Sid agreed ("Yeah", L404) | SB-P01 | "i would like a way where my email can tell me what matters and what doesn't" ~28:33 (L396) |
| SB-S03 | AI that edits pages inside the CMS (WordPress/Shopify) by drag-and-drop rather than generating HTML | interviewee | SB-P07 | "I would like an AI that can use the CMS like WordPress or Shopify and create elements like a drag and drop" ~17:08 (L213) |
| SB-S04 | Import pages into Figma so clients can drag, drop and comment, then upload | interviewer; Sid agreed ("That's a great idea", L226; "the Figma thing is so good", L440) but asked about JavaScript-heavy sites (L263) | SB-P07 | "you can copy and paste the HTML onto like onto Figma. And then they can drag and drop and leave comments" ~17:55 (L224–L225) |
| SB-S05 | Clearer up-front requirements for page changes so they're done in one go | interviewee | SB-P07 | "I would like a clearer way of communication, or just understanding the requirements of what they want with the web page" ~16:21 (L207) |
| SB-S06 | Upgrade the team's Claude plan to Max | interviewee | Agency-wide AI use | "I think we use Pro for team, but I think we need Max." ~26:54 (L373) |
| SB-S07 | Shared Claude skills list/directory and help creating skills to cut token use | interviewee | Agency-wide AI use | "we need to set up skills lists and a proper directory" ~27:30 (L384) |
| SB-S08 | Fix client-owner assignment in the Make/Monday handover (system rule, not Sid) | interviewee; Austin suggested sales may need to own it | SB-P08 | "It needs to have that system in place." ~35:09 (L501) |
| SB-S09 | Simplified ("dumbed down") technical audit as a downloadable lead magnet | interviewer; Sid agreed | NEW: Lead generation (Sales – lead to proposal) | "if we had a dumbed down version of that, then Yeah, it could do wonders" ~39:02 (L568) |
| SB-S10 | Do end-to-end (strategy + technical) for all his clients | interviewee | SB-P02 / SB-P05 | "I could just do end to end for all my clients and just like handle them." ~10:34 (L134) |
| SB-S11 | Finish moving logins into LastPass | interviewee (in progress) | SB-P02 | "We're still in the process of getting everything into LastPass." ~07:17 (L084) |

## 6. Opportunity assessment

| ID | Fixes | Lens | What changes | Matches existing solution idea | Existing tool | Hours saved / month (maths) | Effort | Prerequisites | Adoption risk | COI flag |
|---|---|---|---|---|---|---|---|---|---|---|
| SB-O01 | SB-PP03, SB-PP04, SB-PP15, SB-B03 | Change the process | Rule: internal task requests go into Monday (form or Slack → Monday), with the ask summarised and the current file linked – no forwarded chains | New | Monday forms / email-to-board / Slack integration | 3–8 h (Sid): chains 2–6 × 0.5 h = 1–3 h + 0.1–0.25 h/day less triage × 20 days = 2–5 h | S | Leadership backing; Monday request form | M – relies on colleagues changing habits; "not everybody uses Monday" (L039) | No |
| SB-O02 | SB-PP01, SB-PP02, SB-PP05, SB-PP06, SB-B03 | Augment | AI inbox triage and daily "second brain" brief across Gmail, Slack and Monday: labels (respond to client / task request / FYI), push reminders, one-click "create Monday task" | Partial – "AI business brain" | Claude (existing routine + Gmail/Slack/Monday connectors), Gmail filters, Monday email integration; Sid can mute admin notifications | 6–11 h (Sid): cut 1 h/day to 0.45–0.7 h → saves 0.3–0.55 h × 20–22 days ≈ 6–12 h, rounded 6–11. Team-wide unknown | M | Gmail/Slack access for the tool; decide labels; Claude capacity (see SB-O06) | M – Sid already built a routine he says "it's not doing the job" (L173); needs push alerts, not another channel | Yes – Transpera could build the brain |
| SB-O03 | SB-PP10, SB-PP11 (part), SB-B02 | Change the process | Add a required "Delivery owner" field at deal close (set by the department lead, not sales) and map it in Make; fallback: Monday automation assigns an "Assign owner" item to the department lead | New | HubSpot deal property + Make + Monday | 0.5–2 h (owner chasing and fixes, assumed) | S | Decide who allocates accounts (Karl/Laura/Julia) | L – small change, Sid can build it | No |
| SB-O04 | SB-PP11, SB-PP06 | People & policy | Document Make scenarios and Monday architecture; name and train a second admin; route admin notifications to a digest | Partial – "team wiki / L&D" | Notion, Make scenario notes, Monday notification settings | 1–3 h (notification noise; assumed) + resilience | S | Sid's time to document (4–8 h one-off, assumed); a nominated backup | L | No |
| SB-O05 | SB-PP07, SB-PP08, SB-B01 | Change the process | Page-approval step: agree requirements up front, share a visual draft (Figma import or staging link) for one consolidated round of client comments from a single client approver; cap revision rounds in scope | Partial – "client approval portal" | Figma (+ HTML import plugin), Webflow/WordPress staging, comment tools | 2–8 h (removes most of the 1–2 looping pages × 2–4 h) | M | Client agreement on approver and rounds; check plugin on JS-heavy sites (L263) | M – needs client behaviour change | Partial – Austin offered the plugin |
| SB-O06 | SB-PP12 | People & policy | Claude usage policy: shared skills/prompt library, guidance on Claude in Chrome, right-size plan (Max seats for heavy users) | New | Claude Team/Max, shared skills directory | Not quantified – assume 2–6 h (Sid; time lost to limits) | S | Usage data from Claude admin; budget decision | L | Yes – Transpera could build the skills library |
| SB-O07 | SB-PP09 | Change the process | Finish LastPass migration; link the vault entry from each Monday client item so delivery never opens HubSpot for logins | New | LastPass, Monday link column | 0.7–3.3 h (2–5 min × 20–40 tasks; assumed) | S | Migration completion; access rules | L | No |
| SB-O08 | SB-PP13, SB-PP15 | People & policy | Set a load guide for staff doing technical + end-to-end (e.g. ~5 end-to-end + ~15 technical), plus client-update cadence/templates before adding clients | Partial – none exact | Monday workload view | 0 direct; protects client comms/retention | M | Agreed capacity model with Karl/Julia | M | No |
| SB-O09 | SB-S09 (growth idea, not a pain fix) | Augment | Publish a simplified version of the automated technical audit as a downloadable lead magnet | Partial – "1-click audit (read-only access + AI audit)" | Existing audit tool/Claude MCP, HubSpot forms | 0 (revenue idea) | M | Decide scope; lead routing in HubSpot | M | Yes |

**KPIs**

| Opportunity ID | KPI | How measured | Baseline today | Target | Leading / lagging |
|---|---|---|---|---|---|
| SB-O01 | % of internal requests to Sid arriving as Monday items | Monday vs email/Slack count (sample 2 weeks) | Unknown ("not everybody uses Monday", L039) | ≥80% | Leading |
| SB-O01 | Forwarded chains received per month | Gmail label count | Unknown (assume 2–6) | ≤1 | Lagging |
| SB-O02 | Minutes per day in inbox | Self-log or Gmail/RescueTime | ~60 min ("In a day, an hour.", L421) | ≤30 min | Lagging |
| SB-O02 | Client emails answered within 24 h | Gmail response-time sample | Unknown (24-h target stated, L030) | ≥95% | Leading |
| SB-O03 | New clients with correct owner at board creation | Monday client board audit | 0% (closer "is never the person", L477) | 100% | Leading |
| SB-O03 | Days from deal signed to owner confirmed | HubSpot close date vs Monday owner change | Unknown | Same day | Lagging |
| SB-O04 | Make scenarios with written documentation | Notion/Make notes count | Unknown (assume 0) | 100% | Leading |
| SB-O04 | Number of trained Monday/Make admins | Admin list | 1 (Sid) – detected | 2 | Leading |
| SB-O05 | Revision rounds per uploaded page | Monday task updates / email rounds | Unknown; one page looping a month (L205) | ≤2 | Leading |
| SB-O05 | Days from upload to client sign-off | Monday status dates | Up to ~30 days for worst case (L205) | ≤5 working days | Lagging |
| SB-O06 | Times staff hit Claude usage limits per week | Claude admin console / quick survey | Unknown ("severely limiting", L381) | Near zero | Leading |
| SB-O07 | % of Monday client items with a LastPass link | Monday column fill rate | Unknown (migration "in process", L084) | 100% | Leading |
| SB-O08 | End-to-end clients per technical/strategist hybrid vs guide | Monday owner counts | 5 end-to-end + ~15 technical (L252, L322) | Within guide | Leading |
| SB-O08 | Overdue tickets at month-end | Monday overdue filter | Unknown ("always", L354) | –50% | Lagging |
| SB-O09 | Leads from audit download per month | HubSpot form source | 0 (not launched) | Set after pilot | Lagging |

**Indicative ranking** (priority = Impact × Confidence × Ease)

| Rank | ID | Impact | Confidence | Ease | Priority | Tag | Reason |
|---|---|---|---|---|---|---|---|
| 1 | SB-O03 Delivery-owner field at deal close | 3 | 4 | 4 | 48 | Quick win | Clearly evidenced, every new client affected, small Make/HubSpot change |
| 2 | SB-O02 AI inbox triage / second brain | 4 | 4 | 3 | 48 | Strategic | Biggest stated time sink (1 h/day) and Sid's top personal need; Austin thinks it's team-wide |
| 3 | SB-O01 Requests into Monday, no forwarded chains | 3 | 3 | 4 | 36 | Quick win | Cuts triage and 30-min chain untangling; process rule, no new tech |
| 4 | SB-O04 Document Make/Monday + second admin | 3 | 3 | 4 | 36 | Quick win | Removes single-person dependency on the task system |
| 5 | SB-O05 Visual page-approval step | 3 | 3 | 3 | 27 | Strategic (closest – Impact 3 / Ease 3 is not covered by the four tags) | Month-long loop is real, but frequency unknown and needs client change |
| 6 | SB-O06 Claude usage policy and plan | 3 | 2 | 4 | 24 | Quick win | Team-wide constraint, but no usage numbers yet |
| 7 | SB-O07 Finish LastPass, link from Monday | 2 | 3 | 4 | 24 | Fill-in | Small time saving, also tidies credential risk |
| 8 | SB-O08 Load guide for hybrid roles | 3 | 2 | 3 | 18 | Strategic (closest – Impact 3 / Ease 3 is not covered) | Hypothetical in this interview; needs cross-team data |
| 9 | SB-O09 Audit lead magnet | 2 | 2 | 3 | 12 | Deprioritise | Interviewer idea; no evidence of demand |

Ties are broken by Ease, then Impact. Automation beats augmentation for owner assignment (SB-O03): a required field mapped by Make removes the step nobody but Sid remembers. SB-O02 stays Augment, not Automate – Sid's own Claude routine shows a summary alone isn't enough ("it's not doing the job it needs to be", L173), so the fix needs push alerts with him in the loop.

## 7. What's working well

| Strength | Quote + timestamp |
|---|---|
| Deal-to-delivery handover is automated: a signed HubSpot deal creates the Monday client board and onboarding checklist | "Every time a new deal is made on HubSpot, a client is created on Monday with the tasks that they need to have." ~36:03 (L509) |
| Recurring monthly tasks (words, links, technical hours) auto-generate from a sheet | "So those are pretty much automated from this sheet here." ~36:31 (L512) |
| Two-way sync between client boards and the SEO delivery board | "It's a two-way thing between a client board and the SEO delivery board, which is like the main board for tasks." ~36:58 (L521) |
| Technical audits are automated (Claude MCP) | Austin: "We've automated technical audits, right?" Sid: "Yes, we have." ~38:28 (L554–L555) |
| Technical work is planned at onboarding, not improvised | "We create a technical action plan the moment we onboard a client and we just go through it." ~09:30 (L116) |
| Technical work is explained in plain English for client owners' reports | "that is a lot easier to digest for people who aren't technically sound." ~08:05 (L098) |
| 24-hour client response standard | "Client comms are within the 24-hour limit" ~02:11 (L030) |
| Client results are good across the team | "everyone's clients are doing really well." ~12:40 (L155) |
| Good communication between technical and SEO teams | "there's a good round of communication that happens between the technical and the SEO team." ~12:16 (L150) |
| Reporting already optimised | "reporting we've optimized that's fine." ~27:30 (L384) |
| Team has adopted AI widely (MCPs connected) | "The whole team has MCPs connected" ~27:24 (L382) |
| End-to-end ownership lets technical and content work reinforce each other | "I'm going to do technical task A, where I know once it's done, content task B can get a lot more value out of it." ~11:36 (L147) |

## 8. Numbers and facts

| Value | Unit | Context | Quote + timestamp | Certainty |
|---|---|---|---|---|
| 5 | end-to-end clients | Sid's book (said 4, corrected to 5 incl. one to onboard) | "Actually, five." ~20:14 (L252) | stated |
| ~15 | technical-only clients | Rough estimate | "estimation it would be around 15." ~22:52 (L322) | stated (rough) |
| 1 | hour/day | Email triage | "In a day, an hour." ~30:25 (L421) | stated |
| 30 | minutes | Untangling one forwarded email chain | "I'm just stuck for 30 minutes" ~15:10 (L190) | stated |
| 5 | sheet versions | In one forwarded chain | "there's five different sheets in there." ~15:17 (L192) | stated (one example) |
| ~1 | month | One page's back-and-forth with a client | "for a month. for a singular page." ~16:19 (L205–L206) | stated |
| 24 | hours | Client response limit | "Client comms are within the 24-hour limit" ~02:11 (L030) | stated |
| ~10 | a.m. | Time by which the day is planned | "by like 10 a.m., I know what I need to get done." ~04:03 (L051) | stated |
| 2 | minutes | Link-building brief | "that's like a two minute process." ~24:37 (L353) | stated |
| 2,000 (or 200) | words/month | Adriatic monthly content task (said both) | "So 2000 words." ~36:14 (L510); "needs 200 monthly words" ~36:22 (L511) | stated – inconsistent; 2,000 more likely |
| 5 | links/month | Adriatic | "every month needs five links" ~36:31 (L512) | stated |
| 5 | hours/month | Adriatic on-site technical allocation | "five hours of onsite technical work" ~36:31 (L512) | stated |
| +20 | technical clients | Capacity: manageable if technical only | "Technical, if it was just technical tasks, no." ~22:59 (L326) | stated (hypothetical) |
| +20 technical and +5 end-to-end | clients | Capacity: overload | "Yeah, then I'm screwed." ~23:10 (L330) | stated (hypothetical) |
| Pro for Teams | Claude plan | Current; Sid wants Max | "I think we use Pro for team, but I think we need Max." ~26:54 (L373) | stated (Sid's belief) |
| 4 | Gmail label groups | Per client, to respond, updates, platforms | "It's every client, it's to respond, it's updates, it's platforms." ~28:33 (L396) | stated |
| 1 | Make→Monday connection | Only link between HubSpot and Monday (deal signed) | "That's the only connection between HubSpot and Monday currently." ~36:03 (L509) | stated |
| ~40 | minutes | Interview length (60-min slot, finished ~20 min early) | "We can give you 20 minutes back in your day." ~39:33 (L575) | estimated |

## 9. Tools, data and workarounds

- **Official tools:** Monday.com (all delivery tasks; SEO delivery board, client boards, onboarding checklists); Make.com (webhooks/scenarios – HubSpot deal → Monday); HubSpot (sales CRM, client info and credentials; used by sales and Joe); Gmail; Slack; LastPass (rollout in progress); client CMSs (Webflow, WordPress, Shopify); client sheets/technical action plans; Claude with MCPs (audits, daily routine).
- **Shadow tools / workarounds:** Sid's personal Claude routine posting a daily list to his own Slack channel "Organizer" (L042); manual Gmail labels; manual owner reassignment in Monday (L501); Claude in Chrome used across the team (L384); Austin's Figma import plugin (offered, not yet adopted).
- **Same data in more than one place:** client credentials in HubSpot and LastPass (L088–L091); task status written in the client sheet and again as a Monday update (L098–L101); request details split across email chains, sheets (multiple versions) and Monday (L192).
- **Data or access he needs but doesn't have:** delivery owner captured at deal stage (L477); credentials reachable from Monday; a prioritisation layer over email/Slack; more Claude capacity (token limits).
- **Access action:** Sid made Austin a Make admin during the call (L559) – Make scenarios can now be reviewed directly.

## 10. Knowledge and dependency

| What | Who (role) | If absent |
|---|---|---|
| Monday.com architecture and Make scenarios (built, admin, maintains) | Technical SEO Specialist (Sid) 👤 | Handover automation and boards can't be fixed or changed; nobody owns notifications/issues |
| Manual correction of client owner on every new client | Technical SEO Specialist (Sid) 👤 | New clients sit with the deal closer as owner; "who's going to do it?" (L501) |
| Personal agenda routine (Claude → Slack "Organizer") | Sid | Only affects Sid; not documented |
| Technical audit tool/process (automated) | Technical team (earlier work by Spencer Potts per Sid, L562; role/status unclear in context pack) | Not discussed |
| Client technical context for his ~20 clients | Sid | Client owners rely on his sheet explanations for monthly reports |

## 11a. Clients mentioned

| Client | Tier (context pack) | What was said |
|---|---|---|
| EQ Saddlery ("EQ salary") | Tier 2 | Demo of a technical task: titles too long, meta descriptions too short (L073–L074) |
| Adriatic ("Adriatic Furniture") | Tier 3 | Example of auto-generated monthly tasks: 2,000 (or 200) words, 5 links, 5 h technical (L510–L512) |
| trendsite.com.au | Not in pack | JS-heavy site Sid shared to test the Figma import (L269) – client status unknown |
| Aperitif (own site, "Aparity") | Tier 2 (own site) | Austin imported it into Figma as a demo (L257) |
| Unnamed client | – | One page iterated with the client for a month (L203–L207); Webflow client(s) struggling to edit (L231–L235) |
| "Kshalo" | Unresolved | Mentioned when looking up logins in HubSpot (L081) – possibly a client or a HubSpot section |
