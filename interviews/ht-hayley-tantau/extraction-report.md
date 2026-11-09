# Part A – Transcript extraction: Hayley Tantau (Content Specialist)

**Source and method notes**
- Transcript: Notion meeting notes "Hayley - Workflow & Process Interview", 4 Nov 2026, 1:30 pm (Melbourne), booked 60 min (Evidence Log EV-12). Full transcript retrieved (919 utterances, ends at sign-off) – not truncated. The AI summary was not used as a source.
- **The recording holds two sessions.** L001–L388 is the Hayley interview (~33 min; Austin closed early: "I can give you 30 minutes back", L374). L389–L919 is a separate Meta pacing / Supermetrics troubleshooting session between Austin and Wendlley Simoes ("Thanks so much, Wendley", L918). **Only L001–L388 is extracted here.** The second session is saved separately (`/home/claude/HT/transcript-session2-wendlley.md`) and flagged in section 11.
- **Timestamps:** the transcript has no timestamps. Every timestamp below is written `~mm:ss (L###)`: L### is the utterance number in `/home/claude/HT/transcript.md`; ~mm:ss is estimated from cumulative word position across the 60-minute recording (13:30–14:30 AEDT), which puts the end of the Hayley section at ~33:37.
- **Speakers:** the diariser labelled Austin as C (and A for "Hey Hayley" and short backchannels) and split Hayley across B, D and E. A and C are treated as Austin; all other lines in L001–L388 as Hayley. A few short lines are clearly mislabelled (for example L242 "I just write." under C is Hayley's).
- **Name and term corrections (transcription):** "super loop logs" (L048) → Superloop blogs · "kid" (L232) → Sid (Siddharth Bali) · "Monday" → Monday.com · "chat GPT" → ChatGPT · "Apartheid" (L349) → Aperitif · "provisions" (L057) → revisions · "Would count" (L207) → word count · "seo tech" (L155, L269) → SEO specialists · "APRA guidelines" (L117, dental client) → likely AHPRA (health practitioner advertising rules) – inferred · "two on client" (L308) → likely "tier one client" – inferred. Unresolved: "AI fly" (L349), "imperative style" (L218, probably "our style"), "Do you agree with shades?" (L194).
- Hours are costed at **$80/hr internal labour cost**. Process totals cover Hayley's own time unless a row says otherwise (the Content Manager's freelancer assignment time is noted but not costed – not discussed).

---

## 0. Interview card

| Field | Detail |
|---|---|
| Interviewee | Hayley Tantau |
| Role | Content Specialist |
| Team | Organic (content) |
| Date / length | 4 Nov 2026 · ~33 min of a 60-min booking (rest of the recording is a separate session) |
| Interviewer | Austin Smith (Transpera AI) |
| Clients managed | ~7 this month (stated, L147). Context pack says 17 content clients – see 11 |
| Channels / services | SEO content writing: pages and blogs, research, drafting, revisions; editing freelancer overflow; covers freelancer assignment when the Content Manager is away |
| Reports to | Sarah Julian, Content Manager ("Sarah, who's my manager", L040) |
| Hands work to | Clients for approval (via account managers / SEO specialists – "a different AM", L048); Content Manager |
| Receives work from | SEO specialists (content briefs); Content Manager (freelancer overflow to edit, priorities); clients and account managers (revision feedback); one high-priority client directly (last-minute requests outside the brief cycle) |

## 1. Five-line summary

1. **Content delivery is a predictable monthly cycle with a crunch at the end.** Writers work Tier 1 clients first, aim to finish own client work by the 24th, then edit freelancer overflow, so "the end of the month is often crunchy" (L150).
2. **One high-priority client sits outside the system.** It isn't briefed by the SEO specialists and sends work "at the last minute", so Hayley has to hold buffer every month (L155–L156).
3. **Two writers carry the client books, and cover is thin.** When the Content Manager was on leave, Hayley took on freelancer assignment and it was "crunchy"; a junior content writer is being hired to replace costly freelancer reliance (L208–L219).
4. **Tooling is mid-migration.** Freelancer work and the word-count tracker sit in Google Sheets and email while the team moves to Monday.com; nobody knows where the Sheets–Monday connection is up to now that Sid is moving to client work (L169–L177, L226–L236).
5. **AI use is already mature and self-built – the gain here is process and people, not more AI.** Briefs were fixed through joint training with the SEO team; Hayley runs Claude (research and bulk) → human finesse → Gemini (fact-check) and sees no more room for AI without losing the human-written positioning (L250–L292).

## 1a. Time allocation

| Activity | % / hours | Billable? | Quote + timestamp | Certainty |
|---|---|---|---|---|
| Writing and drafting own clients' pages and blogs (incl. AI research) | Majority – ~7 clients × "a couple of days" ≈ 80–106 h/month ≈ 50–65% | Billable | "I kind of work on a client for a couple of days and then I think I have about like Seven this month." ~12:49 (L147) | stated (days, clients) · hours estimated (7 × 1.5–2 days × 7.6 h) |
| Editing freelancer overflow (last week of the month, after the 24th) | ~4–5 working days ≈ 15–30 h/month ≈ 10–20% | Billable | "We are aiming this month to get all our client work done by the 24th because then we edit a bunch of freelancer." ~12:49 (L147) | stated (timing) · hours assumed |
| Revisions on client feedback | Not given – part of most days | Billable | "Today I have revisions and meetings, but that's kind of it." ~04:40 (L058) | stated (no number) |
| Meetings (Content Manager; occasional in-person client) | Low – "I don't have a whole lot of meetings" | Mixed | "I just meet with Sarah and sometimes meet with a very high priority client in person" ~03:54 (L052) | stated (no number) |
| Freelancer assignment (cover only when Content Manager is away) | Occasional | Non-billable (internal) | "she went on leave a few months ago so I did that" ~12:28 (L146) | stated (no number) |

- **Busy vs quiet:** the month starts with Tier 1 clients and is "pretty predictable" (L159); it gets crunchy from the 24th, when own client work should be done and freelancer overflow editing starts, plus any last-minute requests from the out-of-cycle client (L150–L156).
- **Billable vs non-billable:** not discussed directly. Assumed ~90% client-attributable (writing, editing, revisions) and ~10% internal (meetings with the Content Manager, tracker updates, freelancer cover). Confirm with timesheets.

## 2. Processes

Flags: ⏸ bottleneck · 👤 single-person dependent · ⌨️ manual copy / re-keying · ⚠️ error-prone. Interviewee = HT. Content Manager = Sarah Julian.

### HT-P01 · Content writing & editing (own client content, monthly cycle)
- **Trigger:** start of the month – briefs from the SEO specialists for each client, worked in tier order (Tier 1 first).
- **Owner role:** Content Specialist (HT) for her client book; Content Manager sets priorities.
- **Frequency:** monthly × ~7 clients (stated, L147); "a couple of days" per client.
- **Tools / files:** content briefs (written by SEO specialists, structured with Claude); internal content tracker / word-count tracker (Google Sheets, "Internal content tracker 2026 overview", L318); Monday.com; Claude (research, bulk-out); Gemini (fact-check); Google Docs (assumed).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Pick up the next brief, Tier 1 clients first | HT | Content tracker (Google Sheets) / Monday.com | 5–10 per piece | – | – | stated (step) / assumed (time) |
| 2 | Research and bulk out the content with Claude using very specific prompts | HT | Claude | inside the 684–912 per client below | – | – | stated (step) |
| 3 | Finesse the draft – human flair, client tone of voice, technical accuracy | HT | Google Docs (assumed) | inside the 684–912 per client | – | – | stated (step) |
| 4 | Run the draft through Gemini: "is this factual, relevant to the reader" | HT | Gemini | inside the 684–912 per client | – | – | stated (step) |
| 5 | Submit for approval | HT | Email / tracker (assumed) | incl. | Client / account manager review ⏸ (see HT-P03) | Account manager / client | stated (step) |

- **Happy path total:** "a couple of days" per client = 1.5–2 days × 7.6 h = 684–912 min (11.4–15.2 h) per client; elapsed: inside the month, finished by the 24th (target).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Last-minute requests from the out-of-cycle high-priority client ⏸ | Client sends work directly; not briefed by the SEO specialists | Monthly (assumed – "they're going to throw some stuff at us", L156) | Reprioritise; write without a brief; protect buffer | 120–360 min / month (assumed) | HT, Content Manager, other clients' schedule | stated (event) / assumed (rate, time) |
| Unfamiliar technical topic (for example internet products, anti-money-laundering) | Client in a specialist field | Some clients each month | Extra Claude research and fact-checking | Included in the per-client range | HT | stated (event) |
| Brief lacks detail or context ⚠️ | Brief not to the new standard (mostly fixed since the training) | 0–2 / month (assumed) | Clarify with SEO specialist | 0–30 min each (0–60 total) | HT, SEO specialist | stated (historic problem, L072) / assumed (rate) |

- **Decision points:** after step 1 – Tier 1 first vs the rest (rule, stated L046); out-of-cycle client request arrives → drop current work vs fit into buffer (no split given; stated L155–L156). After step 5 – approved first time vs revisions (split not discussed – see HT-P03).
- **Volume (team):** ~93k words / ~47 requests a month across the team; contractors 48%, Content Manager 37%, Content Specialist 15% (context pack). 15% × 93k ≈ 14k words/month for HT – consistent with 80–113 h at ~120–175 words/h including research (estimated cross-check).
- **Monthly hours:** happy path 7 × 684 = 4,788 min to 7 × 912 = 6,384 min; bad paths 120 + 0 = 120 to 360 + 60 = 420 min; total 4,908–6,804 min = **81.8–113.4 h** (estimated).
- **Monthly cost:** 81.8 × $80 = **$6,544** to 113.4 × $80 = **$9,072**.

### HT-P02 · Content writing & editing (freelancer overflow editing, last week of the month)
- **Trigger:** own client work done (target the 24th); freelancer overflow drafts come in for editing.
- **Owner role:** Content Manager assigns freelancer work; HT edits a share of the overflow.
- **Frequency:** monthly, roughly the 24th to month end (~4–5 working days).
- **Tools / files:** freelancer Google Sheets (one shared or separate per freelancer, L169); email; Monday.com (moving to); content tracker.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Assign work to freelancers at the start of the month 👤 | Content Manager (HT when she's on leave) | Google Sheets, email | not costed (Content Manager time – not discussed) | – | Freelancers | stated (step) |
| 2 | Freelancers write | Freelancers (contractors) | Google Docs / Sheets | – (contractor) | Through the month ⏸ | HT / Content Manager | stated |
| 3 | Edit freelancer overflow ⏸ | HT | Google Docs (assumed) | 912–1,824 (see maths) | Starts after own work, ~24th | – | stated (step, timing) / assumed (time) |
| 4 | Submit for approval | HT | Email / tracker (assumed) | incl. | Client review (HT-P03) | Client | assumed |

- **Happy path total:** 4–5 working days × 7.6 h × 50–80% editing share = 15.2–30.4 h a month; elapsed: last ~5 working days of the month.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Overflow lands on top of late own work or ad hoc client requests | Own work not done by the 24th; out-of-cycle client requests | Most months ("often crunchy", L150) | Compress editing; work to deadline | not quantified (crunch, not extra hours) | HT, Content Manager | stated |
| Freelancer draft off-style | Freelancers not trained in house style | not discussed | Heavier edit | not quantified | HT, Content Manager | detected (from the reason for hiring a junior, L217–L219) |

- **Decision points:** own work done by the 24th → overflow editing starts on time vs slips into crunch (split not given).
- **Volume (team):** contractors write ~48% of ~93k words a month (~45k words) and cost ~$14k/month (context pack); HT's share of the editing is not discussed.
- **Monthly hours:** low 4 days × 7.6 h × 50% = 15.2 h; high 5 × 7.6 × 80% = 30.4 h → **15.2–30.4 h** – assumed.
- **Monthly cost:** 15.2 × $80 = **$1,216** to 30.4 × $80 = **$2,432**.

### HT-P03 · Client content approval (revisions on client feedback)
- **Trigger:** client or account manager feedback on a submitted draft.
- **Owner role:** HT (writer of the piece); the client approves.
- **Frequency:** "Today I have revisions" (L058) – rounds per month not stated.
- **Tools / files:** drafts, email / tracker (assumed); briefs (client preferences copied forward).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Client reviews the draft | Client | Email / doc | – | not discussed ⏸ | HT | stated (step) |
| 2 | Apply revisions and resubmit | HT | Google Docs (assumed) | 30–60 per round | – | Client | stated (step) / assumed (time) |
| 3 | New client preference is carried into future briefs | SEO specialist / HT | Brief (copied brief to brief) ⌨️ | incl. | – | Next brief | stated |

- **Happy path total:** 30–60 min per revision round; elapsed: depends on the client (not discussed).
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Compliance-sensitive client comments even on a fully detailed brief | Regulated sector (dental – "APRA" [likely AHPRA] guidelines) | 1–2 / month (assumed) | Extra review round | 30–60 min each | HT, client | stated (event, L117) / assumed (rate, time) |
| Client tells writer exactly what to say | Client preference | sometimes | Faster round (positive) | – | HT | stated (L060) |

- **Decision points:** after step 1 – approved vs revisions (split not discussed).
- **Monthly hours:** low 4 rounds × 30 min + 1 × 30 = 150 min (2.5 h); high 10 × 60 + 2 × 60 = 720 min (12.0 h) → **2.5–12.0 h** – assumed.
- **Monthly cost:** 2.5 × $80 = **$200** to 12.0 × $80 = **$960**.

### HT-P04 · Content briefing (brief standard and quarterly refresh)
- **Trigger:** briefs weren't giving writers what they needed; the team now plans a refresh every quarter as content strategy changes (for example AEO).
- **Owner role:** SEO specialists write briefs (structured with Claude); Content Manager and HT set what writers need.
- **Frequency:** one training "a month or two ago" (L072); quarterly from now (L081).
- **Tools / files:** content brief templates; Claude (SEO specialists, structure only).

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Review what writers need from briefs (data, facts, client preferences, context) | Content Manager + HT | Briefs | 120–240 per quarter (HT share) | – | SEO specialists | stated (step) / assumed (time) |
| 2 | Training / agreement with SEO specialists on the brief standard | Content Manager, HT, SEO specialists | Meeting | incl. above | – | SEO specialists | stated |
| 3 | SEO specialists write briefs to the standard; Claude used only to structure them | SEO specialists | Brief template, Claude | not costed (SEO time – not discussed) | – | HT | stated |

- **Happy path total:** 2–4 h a quarter for HT; elapsed: quarterly.
- **Bad paths:** briefs drift back to thin and generic between refreshes – rate not discussed (the original problem, L072).
- **Decision points:** refresh needed this quarter vs not (planned every quarter, L081).
- **Monthly hours:** 120 ÷ 3 = 40 min (0.7 h) to 240 ÷ 3 = 80 min (1.3 h) → **0.7–1.3 h** – assumed.
- **Monthly cost:** 0.7 × $80 = **$56** to 1.3 × $80 = **$104**.

### HT-P05 · Internal task management (tracker updates, Content Manager check-ins, freelancer-assignment cover)
- **Trigger:** weekly rhythm; Content Manager's leave triggers cover.
- **Owner role:** Content Manager; HT covers.
- **Frequency:** weekly (check-ins, tracker); cover a few times a year ("a few months ago", L146).
- **Tools / files:** internal content tracker / word-count tracker (Google Sheets); freelancer sheets; email; Monday.com.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Update word counts and status in the tracker and Monday.com ⌨️ | HT | Google Sheets + Monday.com | 15–30 per week | – | Content Manager | assumed ("double ups", L177) |
| 2 | Meet the Content Manager | HT, Content Manager | Meeting | 30–60 per week | – | – | stated (step, L052) / assumed (time) |
| 3 | Cover: assign freelancer work when the Content Manager is on leave 👤 | HT | Google Sheets, email | 0–120 a month (averaged) | – | Freelancers | stated (event) / assumed (time) |

- **Happy path total:** 45–90 min a week plus occasional cover.
- **Bad paths:**

| Bad path | Trigger | How often | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|
| Content Manager on leave | Leave | A few times a year (assumed) | HT assigns freelancers and carries her own book – "crunchy" | Included in step 3 (averaged) | HT | stated (event, L146, L208) |
| Sheets–Monday.com connection not built ⏸ | Integration owner (Sid) moving to client work | Ongoing | Keep both systems in step | Included in step 1 | Content team | stated (L226–L236) |

- **Decision points:** keep the tracker in Sheets and connect it to Monday.com vs rebuild it in Monday.com (open – L226–L232).
- **Monthly hours:** low 4.33 × (15 + 30) = 195 min + 0 = 3.3 h; high 4.33 × (30 + 60) = 390 min + 120 = 510 min (8.5 h) → **3.3–8.5 h** – assumed.
- **Monthly cost:** 3.3 × $80 = **$264** to 8.5 × $80 = **$680**.

### HT-P06 · Client meetings & prep (in-person meeting with one high-priority client)
- **Trigger:** meeting with the one client Hayley sees face to face (the same client that works outside the content cycle, L154).
- **Owner role:** account lead (not named); HT attends.
- **Frequency:** "sometimes" (L052) – assumed monthly.
- **Tools / files:** not discussed.

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|
| 1 | Prepare and attend in-person meeting | HT | – | 60–180 (incl. travel) | – | – | stated (event) / assumed (time) |
| 2 | Take away ad hoc requests | HT | – | incl. | – | HT-P01 (last-minute work) | stated (L154–L155) |

- **Happy path total:** 1–3 h per meeting.
- **Bad paths:** not discussed.
- **Decision points:** none stated.
- **Monthly hours:** 1 × 60 = 60 min (1.0 h) to 1 × 180 = 180 min (3.0 h) → **1.0–3.0 h** – assumed.
- **Monthly cost:** 1.0 × $80 = **$80** to 3.0 × $80 = **$240**.

### Process totals

| ID | Process | Monthly hours (all actors) | HT-only hours | Monthly cost (all actors) |
|---|---|---|---|---|
| HT-P01 | Content writing & editing (own clients) | 81.8–113.4 | 81.8–113.4 | $6,544–$9,072 |
| HT-P02 | Content writing & editing (freelancer overflow editing) | 15.2–30.4 | 15.2–30.4 | $1,216–$2,432 |
| HT-P03 | Client content approval (revisions) | 2.5–12.0 | 2.5–12.0 | $200–$960 |
| HT-P04 | Content briefing (standard and refresh) | 0.7–1.3 | 0.7–1.3 | $56–$104 |
| HT-P05 | Internal task management | 3.3–8.5 | 3.3–8.5 | $264–$680 |
| HT-P06 | Client meetings & prep | 1.0–3.0 | 1.0–3.0 | $80–$240 |
| **Total** | | **104.5–168.6 h** | **104.5–168.6 h** | **$8,360–$13,488** |

These are Hayley's hours only (Content Manager, SEO specialist and freelancer time is not costed – not discussed). The high end (~169 h) is slightly more than one full-time month (~152–165 h), so the assumptions can't all be at their high end together; the mid range (~135 h) is more realistic. Confirm with timesheets and the word-count tracker (see 11).

## 3. Pain points and problems

| ID | Pain point (one line) | Source | Category | Anchor | Process | Impact | How often | Severity 1–5 | Quote + timestamp | Certainty |
|---|---|---|---|---|---|---|---|---|---|---|
| HT-PP01 | End of month is crunchy: own client work has to be done by the 24th so freelancer overflow can be edited in the last week | interviewee | Capacity / overload | Operations capacity & process | Content writing & editing | Late-month pressure; delivery risk; quality risk on overflow edits | Monthly | 3 | "So the end of the month is often crunchy" ~13:12 (L150) | stated |
| HT-PP02 | One high-priority client sits outside the content cycle – not briefed by the SEO specialists, sends work at the last minute, so writers must hold buffer | interviewee | Client friction | Client experience & delivery | Content writing & editing | 2–6 h/month unplanned work (assumed); schedule disruption for ~7 other clients | Monthly | 3 | "even the seo tech [SEO specialists] doesn't brief it, they just give us things to do at the last minute." ~13:57 (L155) | stated (event) / assumed (hours) |
| HT-PP03 | Content cover is thin: when the Content Manager was on leave, Hayley took on freelancer assignment as well as her own book and it was crunchy | interviewee | Single point of failure (person) | Leadership & dependency | Internal task management | Overload during leave; freelancer work depends on one person | Whenever the Content Manager is away | 3 | "when Sarah went on leave, it was like crunchy for me for sure." ~18:24 (L208) | stated |
| HT-PP04 | Client nuance (tone of voice, compliance preferences) is copied brief to brief and held by the writer who owns the client – no single per-client home; handover docs could be stronger | interviewer raised the central-store question; interviewee said "not a pain point that I feel" but agreed handover could be more robust | Single point of failure (person) | Client experience & delivery | Content briefing | Cover and handover risk; repeat client corrections | Every brief | 3 | "it does usually get copied and pasted from brief to brief." ~09:03 (L108); "I think we could probably protect ourselves more with that in the future" ~11:28 (L135) | stated |
| HT-PP05 | Freelancer work and the word-count tracker live in Google Sheets (some separate per freelancer) and email alongside Monday.com – double-ups | interviewee | Duplicate data entry | Technology, AI & stack | Internal task management | 1–3 h/month double handling (assumed); no single view | Weekly | 3 | "I think for the sake of simplicity and double ups, yeah, we should go to Monday." ~15:53 (L177) | stated (problem) / assumed (hours) |
| HT-PP06 | Nobody is clearly driving the Sheets–Monday.com tracker connection; it sat with Sid, who is moving to client work | interviewee ("I don't know where it's at"); interviewer added Sid's reduced time | Unclear ownership | Technology, AI & stack | Internal task management | Migration stalls; double-ups continue | Ongoing | 3 | "Yeah, I think that's what's kid [Sid] but I don't know where it's at." ~20:07 (L232) | stated |
| HT-PP07 | Overflow relies on freelancers who are costly and not trained in house style; a junior writer hire is under way | interviewee (cost wording is garbled and may be Austin's, L214–L215) | Revenue / margin leak | Operations capacity & process | Content writing & editing | Contractor spend ~$14k/month team-wide (context pack); editing load | Monthly | 3 | "they're amazing, but we want someone that we can train in." ~19:03 (L217) | stated (intent) / context pack ($) |
| HT-PP08 | AI tools skew vague; good output needs very specific prompts and individual trial and error | interviewee | Rework / errors | Technology, AI & stack | Content writing & editing | Prompting time; risk of generic content | Daily | 2 | "my main gripe with. like a Claude or a chat GPT is that they do lean like unspecific." ~21:57 (L254–L255) | stated |
| HT-PP09 | Briefs used to lack the detail and context writers needed (fixed by joint training; could drift without the quarterly refresh) | interviewee | Rework / errors | Client experience & delivery | Content briefing | Was rework and generic AI output; now resolved | Historic | 2 | "we're in the SEO team, but with the SEO specialists to kind of make the briefs better because we weren't getting what we wanted out of them." ~05:26 (L072) | stated |
| HT-PP10 | Compliance-sensitive clients (dental) still comment on drafts even when briefs hold all their preferences – extra review rounds | interviewee (accepts it as fair) | Client friction | Client experience & delivery | Client content approval | 0.5–2 h/month (assumed) | 1–2 / month (assumed) | 2 | "She'll still comment anyway, which is totally fair because it's like APRA [AHPRA] guidelines and her business on the line." ~09:45 (L117) | stated (event) / assumed (rate) |

**Problem-list matches:** HT-PP03 matches "Content delivery hinges on the Content Manager as writer, editor and contractor manager"; HT-PP04 matches "Client knowledge lives in people's heads, not per client"; HT-PP05 matches "Content tracker and link sheets live outside Monday.com". HT-PP01, HT-PP02, HT-PP06, HT-PP07, HT-PP08 are new (HT-PP07 partly overlaps the Content Manager dependency). HT-PP09 is resolved; HT-PP10 is minor.

**Top 3 by severity – root cause and match**

1. **HT-PP02 Out-of-cycle client (3).** Why is work last-minute? The client sends requests straight to the writers. Why? It was never brought into the monthly briefing cycle – the SEO specialists don't brief it. Why does that hurt? The content plan has no reserved capacity or cut-off for unplanned work. **Root cause:** no intake rule or capacity reservation for a client that works outside the standard cycle. **Matches:** new.
2. **HT-PP03 Thin cover (3).** Why was leave crunchy? Freelancer assignment and a full client book landed on one remaining writer. Why? Content delivery runs on two people with fixed client books and no documented cover plan. **Root cause:** no spare in-house writing capacity and no cover process (being addressed by the junior hire). **Matches:** "Content delivery hinges on the Content Manager as writer, editor and contractor manager".
3. **HT-PP05 Sheets and Monday.com double-ups (3).** Why are there double-ups? The team moved to Monday.com a couple of months ago but kept the freelancer sheets and the word-count tracker in Google Sheets. Why? Nobody knows how to bring the tracker across and the person who might have connected them is moving roles (HT-PP06). **Root cause:** a tool migration with no named owner or finish line. **Matches:** "Content tracker and link sheets live outside Monday.com".

## 4. Bottlenecks

| ID | Step | Waiting on | Typical wait | Affected | Knock-on |
|---|---|---|---|---|---|
| HT-B01 | Freelancer overflow editing (HT-P02 step 3) | Own client work finishing (24th) and freelancer drafts | Editing compressed into the last ~4–5 working days | All freelancer overflow (~48% of team words – context pack) | End-of-month crunch; quality and on-time risk |
| HT-B02 | Last-minute work from the out-of-cycle client (HT-P01 bad path) | The client's own requests – no brief, no cut-off | Unpredictable | 1 client; displaces ~7 others' schedule | Buffer held every month; adds to the crunch |
| HT-B03 | Client approval (HT-P03 step 1) | Client feedback | not discussed | All submitted drafts | Revisions bunch with month-end work (assumed) |
| HT-B04 | Sheets–Monday.com tracker connection (HT-P05) | An owner with time and Monday.com/Make skills (Sid moving to client work) | Open-ended – "I don't know where it's at" (L232) | Content team (Content Manager, HT, freelancers) | Double-ups continue; migration stalls |
| HT-B05 | Freelancer assignment (HT-P02 step 1) | Content Manager 👤 | Not stated; falls to HT when she's on leave | All freelancer work | Cover overload (HT-PP03) |

## 4a. Decisions and approvals

| Decision | Who decides (role) | Who waits | Typical time | Lands on leadership? |
|---|---|---|---|---|
| Order of work (tier rule – Tier 1 first) | HT (rule set by the team) | Lower-tier clients | Start of month | No |
| Freelancer assignment | Content Manager (HT when she's on leave) | Freelancers, HT (overflow editing) | Start of month | No |
| Draft approval | Client (via account manager / SEO specialist) | HT | not discussed | No |
| Brief standard and refresh cadence | Content Manager + HT, agreed with SEO specialists | Writers | Quarterly | No |
| Fitting in last-minute requests from the out-of-cycle client | HT (self-prioritised) | Other clients | Ad hoc | No – no rule, so self-prioritised |
| Keep the tracker in Sheets and connect it, or rebuild in Monday.com | Not decided – open between the content team, Sid and Austin | Content team | Open | No |
| Junior content writer hire | Content Manager with HT (reviewing CVs); final approver not discussed | Content team | In progress | not discussed (likely leadership sign-off – confirm) |

## 5. Suggestions for change (as raised in the interview)

| ID | Idea | Source + reaction | Process | Quote + timestamp |
|---|---|---|---|---|
| HT-S01 | Refresh the content briefs every quarter as strategy changes (for example AEO) | interviewee (agreed with the Content Manager) | Content briefing | "I think we might just do it every quarter we decided because things change as well like I mean with AEO and everything." ~06:32 (L081) |
| HT-S02 | Briefs should be as human, data-heavy and contextual as possible – facts, data, client preferences – so writers can add flair and use Claude for research (implemented) | interviewee | Content briefing | "we sort of wanted the briefs to be as human as possible and as data heavy and contextual as possible" ~05:59 (L077) |
| HT-S03 | Bring the freelancer sheets and communication into Monday.com – "all under one roof" | interviewee | Internal task management | "I think we're trying to integrate that into Monday because we're loving Monday. Let's get it all under one roof." ~15:20 (L171) |
| HT-S04 | Connect the Google Sheets word-count tracker to Monday.com rather than rebuild it; Austin to follow up as Sid has less time | interviewer; interviewee agreed it was the plan but didn't know its status | Internal task management | Austin: "I know you can connect Google Sheets to Monday." ~19:57 (L231); "I'll follow it up because I know Sid is moving into more client-focused positions" ~20:19 (L236) |
| HT-S05 | Make briefs or handover docs detailed enough that someone can pick up a client when its writer is away | interviewee | Content briefing / Knowledge & SOPs | "the briefs should be detailed enough or a hand over docs to be like, when one of us goes away." ~11:00 (L130) |
| HT-S06 | Hire a junior content writer, trained in house style, instead of leaning on freelancers (in progress) | interviewee | Hiring & onboarding staff | "we're currently like going through some CVs for a junior" ~18:44 (L214); "I think it is like that longterm efficiency we're going for." ~19:11 (L219) |
| HT-S07 | A research tool for subject matter writers don't know | interviewer; interviewee said AI already does this for her | Content writing & editing | Austin: "Do you think like a research tool might help you?" ~21:22 (L249); "AI has already really helped with that for me" ~21:39 (L250) |
| HT-S08 | Work out what Monday.com can do, especially for content-team ↔ SEO-team communication | interviewee (open question) | Internal task management | "How it can help content team, how content team can speak to SEO team." ~24:28 (L280) |

## 6. Opportunity assessment

| ID | Fixes | Lens | What changes | Matches existing solution idea | Existing tool | Hours saved / month (maths) | Effort | Prerequisites | Adoption risk | COI flag |
|---|---|---|---|---|---|---|---|---|---|---|
| HT-O01 | HT-PP04, HT-PP03, HT-PP10 | Change the process | One content profile per client (tone of voice, compliance rules, client preferences and feedback history, key facts) kept in one place and linked from every brief; the writer updates it after each feedback round; it doubles as the handover doc for leave cover | AI business brain (per-client knowledge, lightweight) · team wiki | Monday.com item docs or a shared Google Doc per client | 1.0–4.0 h (assumed: fewer repeat corrections 0.5–2 h + faster cover ramp-up 0.5–2 h, averaged) | S | Profile template; writer owns each profile; SEO specialists link it in briefs | L – the team already carries these details forward; this formalises it | No |
| HT-O02 | HT-PP07, HT-PP03, HT-PP01 | People & policy | Finish the junior content writer hire; train in house style; shift overflow from freelancers to the junior; write a simple leave-cover plan (who assigns freelancers, who takes which clients) | new | – (hire) | 0–7.6 h (assumed: overflow editing 15.2–30.4 h × 0–25% less after ramp-up); main gain is contractor spend (~$14k/month team-wide, context pack) | L | Budget sign-off; CVs in progress (L214); training time | M – early training and editing load falls on the Content Manager and HT for 2–3 months | No |
| HT-O03 | HT-PP05, HT-PP06, HT-B04 | Automate | Connect the word-count / content tracker Google Sheet to Monday.com (native integration or Make.com sync) so freelancer assignments and word counts live on one board; freelancers get guest access instead of separate sheets and email; name an owner other than Sid | new (problem: content tracker outside Monday.com) | Monday.com Google Sheets integration; Make.com (already in the stack) | 1.1–3.2 h (assumed: double-up handling 15–45 min/week × 4.33) | S | Monday.com admin owner; agreed tracker fields | L – team is "loving Monday" (L171) | Yes (Austin offered to follow up) |
| HT-O04 | HT-PP02, HT-B02, HT-PP01 | Change the process | Bring the out-of-cycle client into the system: agree a monthly reserved allowance (words or hours), a request cut-off date, and log requests through the account lead into Monday.com so they're briefed like other work | new | Monday.com request form | 1.0–4.2 h (unplanned work 2–6 h × 50–70%) | S | Identify client; account lead + client agreement | M – high-value client's habits | No |
| HT-O05 | HT-PP01, HT-B01 | Change the process | Stagger freelancer due dates (for example two batches – mid-month and the 20th) so overflow editing is spread through the month instead of stacked after the 24th | new | Monday.com due dates; content tracker | 0–1 h (crunch relief, few hours saved) | S | Content Manager schedules; freelancer agreement | L | No |
| HT-O06 | HT-PP08 | Augment | Shared content AI playbook: tested prompts for Claude research and bulk-out, a brief-to-prompt template and the Gemini fact-check step, held in a shared Claude Project with the style guide; used by writers, freelancers and the new junior | team wiki / L&D | Claude Projects; Notion | 0.6–2.4 h (trial-and-error prompting 2–4 h × 30–60%) | S | Content Manager + HT document their prompts | L – HT already runs this system (L259–L261) | No |

**KPIs**

| Opportunity ID | KPI | How measured | Baseline today | Target | Leading / lagging |
|---|---|---|---|---|---|
| HT-O01 | % of active content clients with a current profile | Monday.com / Drive audit | 0 central – "copied and pasted from brief to brief" (L108) | 100% | Leading |
| HT-O01 | Revision rounds per piece | Content tracker | unknown | –25% | Lagging |
| HT-O02 | Share of monthly words written in-house vs freelancers | Internal content tracker | Contractors 48% (context pack; not stated in transcript) | ≤ 35% within 6 months | Lagging |
| HT-O02 | Contractor spend per month | Xero | ~$14k/month (context pack) | –20–30% | Lagging |
| HT-O03 | Places freelancer assignments are tracked | Process audit | 3 – Google Sheets (some per freelancer), email, Monday.com (L169–L172) | 1 (Monday.com) | Leading |
| HT-O03 | Minutes a week spent on tracker double-ups | Time log | unknown | ≤ 10 | Lagging |
| HT-O04 | % of that client's requests logged with ≥ 5 working days' notice | Monday.com | Last-minute – "they just give us things to do at the last minute" (L155) | ≥ 80% | Leading |
| HT-O05 | % of freelancer overflow edited before the 24th | Tracker dates | ~0% – editing starts after the 24th (L147) | ≥ 50% | Leading |
| HT-O05 | Pieces delivered after month end | Tracker | unknown | 0 | Lagging |
| HT-O06 | Shared prompts in the playbook | Playbook / Claude Project | 0 shared – individual "trial and error" (L267) | ≥ 10 core prompts | Leading |

**Indicative ranking** (priority = Impact × Confidence × Ease)

| Rank | ID | Impact | Confidence | Ease | Priority | Tag | Reason |
|---|---|---|---|---|---|---|---|
| 1 | HT-O01 | 3 | 3 | 4 | 36 | Quick win | Formalises what the team already does; closes the handover gap she named |
| 2 | HT-O02 | 4 | 3 | 3 | 36 | Strategic | Already under way; tackles cover, crunch and freelancer cost together |
| 3 | HT-O06 | 2 | 3 | 5 | 30 | Fill-in | Captures a working AI workflow so juniors and freelancers can use it |
| 4 | HT-O04 | 3 | 3 | 3 | 27 | Strategic (see note) | Root cause of the unplanned work; needs a high-value client to change habits |
| 5 | HT-O03 | 2 | 3 | 4 | 24 | Fill-in | Small hours, but finishes a migration the team wants |
| 6 | HT-O05 | 2 | 2 | 4 | 16 | Fill-in | Crunch relief; few hours saved |

Ties are broken by Ease, then Impact. Note: HT-O04 (Impact 3, Ease 3) fits none of the four tags; tagged Strategic as the closest (Impact just below the threshold, Ease ≤ 3). Hayley sees little room for more AI ("I don't think I can use any more than I do", L290) – process and people fixes beat automation here.

## 7. What's working well

| Strength | Quote + timestamp |
|---|---|
| Briefs fixed through joint training with the SEO specialists | "And so the briefs have been incredible since then." ~08:06 (L098) |
| A predictable monthly content cycle | "It's pretty predictable, which is really, really nice." ~14:27 (L159) |
| Clear tier-based prioritisation | "tier one being our highest paying, most important clients. I'll tackle their work first." ~03:21 (L046) |
| A self-built AI workflow with a fact-check layer | "I use Claude. to research and kind of like bulk out the content and then I like finesse it … then like run that through Gemini" ~22:08–22:19 (L259–L261) |
| Writers keep their own clients, so they stay across each client's nuance | "We have our clients and we try to stick with them so that we're very across that" ~11:00 (L130) |
| Client feedback is carried into future briefs | "a lot of the time a client will say something after a round of feedback. So then it's like that usually gets applied." ~09:13 (L109–L110) |
| Detailed briefs for a compliance-sensitive dental client | "the briefs are so detailed and have all their preferences." ~09:38 (L115) |
| Monday.com adoption has been easy | "Whereas Monday has kind of been... a very easy transition." ~17:50 (L198–L199) |
| Capacity planned before it became a crisis | "get it before it became like a full pain point." ~18:44 (L214) |
| Human-written content as the agency's point of difference | "So like the greatest point of difference is now being able human like adding that human touch again" ~31:14 (L349) |

## 8. Numbers and facts

| Value | Unit | Context | Quote + timestamp | Certainty |
|---|---|---|---|---|
| ~7 | clients | HT's book this month | "I think I have about like Seven this month." ~12:49 (L147) | stated (context pack says 17 – see 11) |
| ~2 | days per client | Writing time per client per month | "I kind of work on a client for a couple of days" ~12:49 (L147) | stated |
| 24th | day of month | Target to finish own client work | "aiming this month to get all our client work done by the 24th" ~12:49 (L147) | stated |
| 2 | writers with client books | Content Manager and HT | "We have a certain amount of clients each, Sarah and I" ~03:15 (L045) | stated |
| ~6 | months | HT's time at Aperitif | "I only started like six months ago." ~17:09 (L195) | stated (matches context pack, May 2026) |
| ~2 | months | Since the team moved to Monday.com | "we kind of only just got onto Monday a couple months ago." ~14:55 (L167) | stated |
| 1–2 | months ago | Brief training with SEO specialists | "I think like a month or two ago had a training" ~05:26 (L072) | stated |
| Quarterly | cadence | Planned brief refresh | "I think we might just do it every quarter we decided" ~06:32 (L081) | stated |
| 1 | client | Met in person; outside the content cycle | "sometimes meet with a very high priority client in person" ~03:54 (L052) | stated |
| 1 | junior writer | Hire in progress; reviewing CVs | "we're currently like going through some CVs for a junior" ~18:44 (L214) | stated |
| Word count | monthly target | Writers work to a word-count target (value not stated) | "Like we kind of just have a word count." ~03:54 (L052) | stated (value not discussed) |
| A few months ago | – | Content Manager's leave; HT covered freelancer assignment | "she went on leave a few months ago so I did that" ~12:28 (L146) | stated |
| ~30 | minutes | Interview finished early in a 60-min slot | "I can give you 30 minutes back into your calendar" ~33:01 (L374) | stated |

## 9. Tools, data and workarounds

- **Official tools:** content briefs (written by SEO specialists, structured with Claude); internal content tracker / word-count tracker ("Internal content tracker 2026 overview", Google Sheets, with freelancers listed at the bottom, L318, L360–L361); freelancer Google Sheets; email; Monday.com (adopted ~2 months ago); Slack; HubSpot (previously used alongside the content tracker – "clunky", L195).
- **Shadow tools / workarounds:** Claude for research and bulking out drafts; Gemini as a fact-check and relevance layer; ChatGPT mentioned as a comparison; her own prompt "system" (L259).
- **Same data in more than one place:** freelancer assignments and word counts (Google Sheets, email, Monday.com); client tone of voice and preferences (copied into each brief, plus in writers' heads).
- **Data or access she needs but doesn't have:** a working Sheets–Monday.com connection for the tracker; clarity on what Monday.com can do for content ↔ SEO communication; briefs for the out-of-cycle client. Austin was still waiting for access to the content tracker at the start (L319) and was then given it in the call (L357).

## 10. Knowledge and dependency

| What | Who (role) | If absent |
|---|---|---|
| Client tone of voice and preferences for her ~7 clients (several defined by the writers themselves) | HT | Cover writer relies on briefs that may not hold everything; repeat client corrections |
| Freelancer assignment and the word-count tracker design | Content Manager (Sarah Julian) 👤 | Falls to HT on top of her book – "crunchy" (L208) |
| Out-of-cycle client's requests and context (no brief) | HT and the Content Manager | Nobody else can pick up last-minute work without context |
| Sheets–Monday.com integration know-how | Sid (Siddharth Bali, Technical SEO Specialist) – moving to client work | Migration stalls (HT-PP06) |
| AI prompting workflow (Claude → finesse → Gemini) | HT (individual) | New junior and freelancers start from scratch |

## 11. Follow-ups

**Questions**
- Hayley: which client is the out-of-cycle, in-person client, and how many hours a month do its last-minute requests take?
- Hayley: how many revision rounds a month, and how long each? Typical client approval turnaround?
- Hayley / Sarah: how many words a month does Hayley write and edit (from the word-count tracker), and how much of the last week goes on freelancer editing?
- Sarah: is the leave-cover arrangement written down? Who signs off the junior hire and when is the start date?
- Sid / Austin: status of the Google Sheets–Monday.com connection, and who owns it now?
- Hayley: what is "AI fly" (L349) and "imperative style" (L218)?

**Contradictions**
- Context pack says Hayley owns **17 content clients**; she says "about like Seven this month" (L147). Could be active clients this month vs total book – confirm.
- Context pack has the Content Specialist at ~15% of team words (~14k words/month); 7 clients × ~2 days each fits roughly but should be checked against the tracker.
- Combined high-end hours (~169 h/month) are above one FTE – the assumptions can't all be at the high end together.
- Hayley says client nuance is "not a pain point that I feel" (L106) but also that they "could probably protect ourselves more" (L135) – recorded as a risk, not a felt pain.

**Out-of-scope content in this recording**
- L389–L919 (~26 min) is a separate troubleshooting session between Austin and Wendlley Simoes on the broken Supermetrics → Meta pacing sheet connection (Wendlley: "the cloud [Claude] i was doing because the supermetrics was not working", L434). It confirms the known fact that Wendlley has been doing Meta pacing manually in Claude. Per the Notion AI summary, a scheduled Claude automation was set up, the Meta connector reached 4 of 6 accounts, and a Supermetrics access request is waiting on Joe. **This should be extracted against Wendlley's Evidence Log row (or logged as its own evidence), not under Hayley.** Not extracted here.

**Data / artefacts to request**
- A range of briefs, including a freelancer brief and a "very detailed" Tier 1 brief, with Hayley's notes on each (Hayley – agreed in the interview, L303–L312).
- Draft content as submitted to clients for approval, matched to its brief (Hayley – agreed, L314, L362–L364).
- Internal content tracker 2026 overview / word-count tracker (Sarah / Hayley – Austin now has access, L357–L360).
- Freelancer sheets and rates (Sarah).
- Monday.com content board export (Sarah / Sid).

**Claims to verify before the pack**
- ~7 clients and "a couple of days" per client – check against the word-count tracker.
- Freelancer reliance is "so expensive" – the cost line is garbled (L214–L215) and may be Austin's; use the context-pack contractor spend (~$14k/month) instead.
- Dental client's "APRA guidelines" – likely AHPRA advertising rules; confirm which client.

## 11a. Clients mentioned

| Client | Tier (context pack) | What was said |
|---|---|---|
| Superloop | Tier 1 content (context pack) | "I'll write like a few super loop logs [Superloop blogs]" (L048); blogs about "really specific internet things" she doesn't know much about – AI used for research (L090, inferred to be Superloop/Exetel) |
| Your Local Tradesman | Tier 2 | Example of a client whose tone of voice ("down to earth") the writers defined themselves (L121–L124) |
| Unnamed dental client | Unknown (dental clients include FoX – Tier 1, Moda Dental – Tier 2, Orthodontics at Parramatta – Tier 3) | Very detailed briefs with all preferences; the client still comments on drafts because of "APRA" [likely AHPRA] guidelines (L114–L117) |
| Unnamed high-priority client | Likely Tier 1 (inferred) | Met in person; works outside the content cycle; not briefed by the SEO specialists; sends work at the last minute (L052, L154–L156) |
| Possibly easyAML (inferred) | Not on the SEO tier list; paid media client (context pack) | "looking up money laundering content that I don't understand" (L296) – inferred from the topic only; confirm |
| Unnamed client for "a different AM" | Unknown | Two pages to prioritise tomorrow (L048) |

## 12. Sensitive notes (not for the pack)

- **Overall sentiment: positive, relaxed and engaged.** She describes the role as "pretty predictable, which is really, really nice" (L159) and the workload as "at the moment, manageable" (L221). She apologised for not having more problems to share (L367–L368).
- She is self-critical: she puts the end-of-month crunch down partly to "my own time management. issues um that i'm always working on" (L150–L152), and says "I need to get better with Claude" (L267). Austin reassured her she is ahead of most users (L270).
- Some job-security sensitivity around AI: "I don't think I can use any more than I do. do without making myself obsolete." (L290–L292).
- Leave cover was stressful: "when Sarah went on leave, it was like crunchy for me for sure." (L208).
- Positive comments about named colleagues: Zach's briefs for the dental client are "so detailed" (L115); Sarah "can put together a mean spreadsheet" (L195). No negative comments about any individual.
- Clients are "really nice", though feedback sometimes stings ("Spam [?] my feelings", L064–L067).
- Austin said Sid is "moving into more client-focused positions, so he's probably got less time" (L236) – a role change Austin raised, not Hayley.
- Austin's side remarks (an "AI receptionist" vs a receptionist named Joanna, L338; the gun analogy, L335) are not findings.
