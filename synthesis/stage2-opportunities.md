# Merge – Stage 2 – Costing roll-up and opportunity merge (Part A)

## Stage 2 – Costing and opportunities

> **How to read this.**
**How to read this.** Stage 2 of the merge: hours rebuilt per canonical process without double-counting (2.1), the 143 extraction opportunities merged into 35 and ranked (2.2), and a coverage check against the 39 Stage 1 clusters (2.3).
- **Hours** are monthly, agency-wide, for the people interviewed. Low / mid / high; mid = midpoint. Cost = hours × $80 (internal labour rate, pack §9). The high is a ceiling, not an estimate.
- **% stated** = share of mid-point hours resting on a time the interviewee actually gave. Almost every time-per-task in the extractions is an assumption, so most rows are near 0%.
- **Scores**: Impact 1–5 (hours mid band + client/risk bump, reason shown), Confidence 1–5 (average of problem evidence from the primary cluster and the number of people who proposed the fix; −1 if ≤2 proposers and no stated time), Ease 1–5 (from effort and adoption risk). Priority = product. Tags: Quick win (Ease ≥4, Impact ≥3) · Strategic (Impact ≥4, Ease ≤3) · Consider (Impact 3, Ease ≤3) · Fill-in (Impact ≤2, Ease ≥4) · Deprioritise (Impact ≤2, Ease ≤3).
- **Links**: each cluster links to its Problems registry page; each source opportunity ID links to its Transcript Findings page (Ctrl-F the ID there). Opportunity text uses role families, not names.
- **Hours saved** are not additive across opportunities – several draw on the same process hours.

### 2.1 Process costing roll-up

**Method.** For each canonical process every extraction process record was listed with its actor and monthly hours. Where several people described their own share of a shared process (pacing, briefing, reporting, meetings, onboarding), the shares were summed. Where two records described the same work by the same actor, it was counted once: the kick-off and mid-point escalation records are the same Head-of-Client-Services work (MP-P02 dropped; KO-P06 kept), and leadership's link-QA estimate is the outreach work TG-P03 already costs (MP-P04 dropped). Where a manager costed a colleague's steps inside their own record, only their own share was kept and the colleague's time taken from the colleague's own record (SJ-P01/02/03/05, TG-P01, WS-P02, SD-P02/05/06, MC-P01/02/07, LS-P01). Two un-interviewed shares were kept as separate actors: the coordinator's mid-month checks (SD-P07) and receiving managers' handover time (WS-P09).

**160 h cap.** Seven people's high ends exceeded 160 h/month. Their assumed items were scaled down first (no estimated or stated item needed scaling): SEO Director 204.0 h → 160 h (assumed items ×0.72); Senior SEO Manager & LB Lead 217.2 h → 160 h (assumed items ×0.72); Content Specialist 168.6 h → 160 h (assumed items ×0.86); Performance Marketing Director 217.2 h → 160 h (assumed items ×0.74); Senior PMM (SD) 196.8 h → 160 h (assumed items ×0.71); Performance Marketing Manager (DM) 162.5 h → 160 h (assumed items ×0.98); Performance Marketing Specialist 200.5 h → 160 h (assumed items ×0.57). Low ends were all under 160 h.

**Contradictions that affect costing (resolved as Stage 1 did).** X-01 Supermetrics is treated as connected-but-failing, not lapsed – the daily manual Meta workaround is real but no one timed it, so it is not costed (gap). X-02 Google pacing is partly scripted – no manual Google pacing time was added beyond what each manager described. X-03 the pacing bot posts M/W/F; manual performance checks are fortnightly – check counts follow that. X-12 a campaign build is ~1 day of touch inside 3–5 days elapsed – only touch is costed; elapsed sits in touch:wait. X-05 link volume uses ~300/month (300–340 stated by the outreach team; 200 dropped). X-07 the content specialist's ~7 active clients are used. X-18 the technical audit effort (SB-P02, 50–80 h, assumed) is kept but should not be quoted until confirmed. X-30 individual sums above one FTE are handled by the cap.

| Process | Source IDs | Actors | Hours low / mid / high | Cost low / mid / high | % stated | People | Touch : wait | Method |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Client meetings & prep | DM-P06, HT-P06, LS-P08, SB-P05, SD-P04, SH-P06, WS-P12, ZC-P05 | Content Specialist; Performance Marketing Director; Performance Marketing Manager (DM); SEO Director; SEO Manager; Senior PMM (SD); Senior PMM (SH); Technical SEO Specialist | 104.7 / 146.3 / 187.8 | $8,376 / $11,701 / $15,026 | 39% | 8 | Not known | Sum of each actor's own share; high end scaled by the 160 h cap for Content Specialist, Performance Marketing Director, Performance Marketing Manager (DM), SEO Director |
| Content writing & editing | HT-P01, HT-P02, SJ-P02 | Content Manager; Content Specialist | 106.5 / 144.2 / 181.8 | $8,520 / $11,532 / $14,544 | 64% | 2 | Freelancer drafts up to 2 weeks; edits wait on two editors (SJ-P02) – not quantified as a ratio | Sum of each actor's own share; interviewee share only, other actors counted in their own records (SJ-P02); high end scaled by the 160 h cap for Content Specialist |
| Paid media – campaign build | DM-P03, MC-P01, SD-P05, SH-P03, WS-P02 | Performance Marketing Director; Performance Marketing Manager (DM); Performance Marketing Specialist; Senior PMM (SD); Senior PMM (SH) | 85.5 / 115.9 / 146.3 | $6,840 / $9,273 / $11,706 | 0% | 5 | Touch ~1 working day per campaign vs 3–5 days elapsed (X-12; SD-P05 waits 1–2 days per approval loop) ≈ 1:3 to 1:5 | Sum of each actor's own share; interviewee share only, other actors counted in their own records (MC-P01, SD-P05, WS-P02); high end scaled by the 160 h cap for Performance Marketing Director, Performance Marketing Manager (DM), Performance Marketing Specialist, Senior PMM (SD) |
| Paid media – optimisation | DM-P04, MC-P04, SD-P02, SD-P09, SH-P02, WS-P01, WS-P11 | Performance Marketing Director; Performance Marketing Manager (DM); Performance Marketing Specialist; Senior PMM (SD); Senior PMM (SH) | 67.5 / 98.5 / 129.5 | $5,400 / $7,878 / $10,357 | 4% | 5 | Not known | Sum of each actor's own share; interviewee share only, other actors counted in their own records (SD-P02); high end scaled by the 160 h cap for Performance Marketing Director, Performance Marketing Manager (DM), Senior PMM (SD) |
| Link building – sourcing & ordering | KO-P12, KZ-P08, LS-P04, TG-P01, TG-P02, ZC-P03 | Outreach Specialist; SEO Manager; Senior SEO Manager & LB Lead | 43.3 / 89.6 / 135.9 | $3,464 / $7,168 / $10,871 | 8% | 3 | Touch minutes per order vs 1–2 months order-to-live (LS-P04) and 1–2 weeks negotiation + 0–3 weeks publishing (TG-P02) – wait dominates | Sum of each actor's own share; interviewee share only, other actors counted in their own records (TG-P01); high end scaled by the 160 h cap for Senior SEO Manager & LB Lead; described but not costed: KO-P12, LS-P04 |
| Internal task management | DM-P09, HT-P05, KO-P05, MC-P02, MP-P05, SB-P01, SB-P09, SD-P08, SJ-P04, TG-P04, WS-P07 | Content Manager; Content Specialist; Founder; Outreach Specialist; Performance Marketing Director; Performance Marketing Manager (DM); Performance Marketing Specialist; Senior PMM (SD); Technical SEO Specialist | 64.5 / 87.1 / 109.7 | $5,160 / $6,967 / $8,774 | 11% | 9 | Not known | Sum of each actor's own share; interviewee share only, other actors counted in their own records (MC-P02); high end scaled by the 160 h cap for Content Specialist, Performance Marketing Director, Performance Marketing Manager (DM), Performance Marketing Specialist, Senior PMM (SD); described but not costed: KO-P05 |
| Content briefing | HT-P04, KZ-P02, KZ-P06, LS-P03, SJ-P01, ZC-P02 | Content Manager; Content Specialist; SEO Director; SEO Manager; Senior SEO Manager & LB Lead | 48.0 / 81.0 / 114.0 | $3,840 / $6,480 / $9,119 | 0% | 5 | Briefs due week 1, often later; up to 2-day pick-up lag (SJ-P01) – wait not quantified as a ratio | Sum of each actor's own share; interviewee share only, other actors counted in their own records (SJ-P01); high end scaled by the 160 h cap for Content Specialist, SEO Director, Senior SEO Manager & LB Lead |
| Client onboarding – audit & strategy | DM-P08, KZ-P01, LS-P01, MC-P07, SD-P06, SH-P08, WS-P08, ZC-P07 | Performance Marketing Director; Performance Marketing Manager (DM); Performance Marketing Specialist; SEO Director; SEO Manager; Senior PMM (SD); Senior PMM (SH); Senior SEO Manager & LB Lead | 31.7 / 76.5 / 121.4 | $2,536 / $6,123 / $9,710 | 0% | 8 | Touch 16–34 h per SEO onboarding (LS-P01, assumed) inside a 3-week window; paid: ≥1 week elapsed for audit+strategy, then 3–4 days tracking and 3–7 days build (SD-P06) ≈ 1:3 or worse | Sum of each actor's own share; interviewee share only, other actors counted in their own records (LS-P01, MC-P07, SD-P06); high end scaled by the 160 h cap for Performance Marketing Director, Performance Marketing Manager (DM), Performance Marketing Specialist, SEO Director, Senior PMM (SD), Senior SEO Manager & LB Lead |
| Paid media – pacing & budget management | DM-P01, DM-P02, MC-P05, MP-P01, SD-P01, SH-P01, WS-P03 | Founder; Performance Marketing Director; Performance Marketing Manager (DM); Performance Marketing Specialist; Senior PMM (SD); Senior PMM (SH) | 50.1 / 75.7 / 101.4 | $4,008 / $6,059 / $8,111 | 4% | 6 | Up to 2–3 days between checks (SD-P01); client approval of allocations unknown | Sum of each actor's own share; high end scaled by the 160 h cap for Performance Marketing Director, Performance Marketing Manager (DM), Performance Marketing Specialist, Senior PMM (SD) |
| NEW: Team management, coaching & oversight | KO-P10, KZ-P14, LS-P09, MP-P06 | Founder; SEO Director; Senior SEO Manager & LB Lead | 70.0 / 74.1 / 78.2 | $5,600 / $5,928 / $6,257 | 0% | 3 | Not known | Sum of each actor's own share; high end scaled by the 160 h cap for SEO Director, Senior SEO Manager & LB Lead; described but not costed: KO-P10 |
| Monthly SEO delivery | KZ-P03, KZ-P12, LS-P02, SB-P03, ZC-P09, ZC-P10 | SEO Director; SEO Manager; Senior SEO Manager & LB Lead; Technical SEO Specialist | 53.5 / 73.3 / 93.1 | $4,280 / $5,864 / $7,449 | 0% | 4 | Client approvals days to weeks (LS-P02); tech queue (ZC-P09) – not quantified | Sum of each actor's own share; high end scaled by the 160 h cap for SEO Director, Senior SEO Manager & LB Lead |
| Technical SEO audit & fixes | KZ-P11, SB-P02 | Senior SEO Manager & LB Lead; Technical SEO Specialist | 51.0 / 66.3 / 81.6 | $4,080 / $5,304 / $6,527 | 0% | 2 | Not known | Sum of each actor's own share; high end scaled by the 160 h cap for Senior SEO Manager & LB Lead |
| NEW: Client email & ad hoc requests | DM-P07, KZ-P07, MC-P03, SH-P07 | Performance Marketing Manager (DM); Performance Marketing Specialist; Senior PMM (SH); Senior SEO Manager & LB Lead | 34.3 / 52.4 / 70.5 | $2,744 / $4,192 / $5,640 | 15% | 4 | Not known | Sum of each actor's own share; high end scaled by the 160 h cap for Performance Marketing Manager (DM), Performance Marketing Specialist, Senior SEO Manager & LB Lead |
| Monthly reporting | DM-P05, KZ-P04, KZ-P05, LS-P06, MC-P06, SB-P04, SD-P03, SH-P04, SH-P05, ZC-P01 | Performance Marketing Manager (DM); Performance Marketing Specialist; SEO Director; SEO Manager; Senior PMM (SD); Senior PMM (SH); Senior SEO Manager & LB Lead; Technical SEO Specialist | 39.2 / 52.0 / 64.8 | $3,136 / $4,158 / $5,181 | 0% | 8 | Not known | Sum of each actor's own share; high end scaled by the 160 h cap for Performance Marketing Specialist, SEO Director, Senior PMM (SD), Senior SEO Manager & LB Lead |
| Client content approval | HT-P03, SJ-P03, ZC-P04 | Content Manager; Content Specialist; SEO Manager | 17.5 / 41.8 / 66.0 | $1,400 / $3,340 / $5,280 | 0% | 3 | Touch 24–50 min per piece (ZC-P04) vs ~1 week average client review (ZC-P04) ≈ 1:10+ | Sum of each actor's own share; interviewee share only, other actors counted in their own records (SJ-P03); high end scaled by the 160 h cap for Content Specialist |
| Performance monitoring & alerting | KO-P11, LS-P07, SB-P06, SD-P07, SH-P09, WS-P06, ZC-P06 | Performance Marketing Coordinator; Performance Marketing Director; SEO Director; SEO Manager; Senior PMM (SD); Senior PMM (SH); Technical SEO Specialist | 13.3 / 26.0 / 38.7 | $1,064 / $2,079 / $3,094 | 0% | 6 | Breaks undetected up to ~7 days (KO-P11, SH-P09); checks only mid-month (SD-P07) | Sum of each actor's own share; interviewee share only, other actors counted in their own records (SD-P07); high end scaled by the 160 h cap for Performance Marketing Director, SEO Director, Senior PMM (SD); described but not costed: KO-P11 |
| Link building – QA & live checks | KZ-P10, MP-P04, TG-P03 | Outreach Specialist | 10.8 / 23.2 / 35.7 | $864 / $1,860 / $2,856 | 0% | 1 | Not known | Single actor; same work described twice – counted once (excluded MP-P04); described but not costed: KZ-P10 |
| Knowledge & SOPs | MP-P07, SJ-P05, WS-P10, ZC-P12 | Content Manager; Founder; Performance Marketing Director; SEO Manager | 15.4 / 22.1 / 28.7 | $1,232 / $1,765 / $2,297 | 0% | 4 | Not known | Sum of each actor's own share; interviewee share only, other actors counted in their own records (SJ-P05); high end scaled by the 160 h cap for Performance Marketing Director |
| Client escalation | KO-P06, MP-P02 | Head of Client Services | 10.8 / 21.6 / 32.5 | $864 / $1,732 / $2,600 | 0% | 1 | Not known | Single actor; same work described twice – counted once (excluded MP-P02) |
| Quarterly / 6-month review | LS-P05, WS-P04, ZC-P11 | Performance Marketing Director; SEO Director; SEO Manager | 11.1 / 17.2 / 23.2 | $888 / $1,372 / $1,857 | 0% | 3 | Not known | Sum of each actor's own share; high end scaled by the 160 h cap for Performance Marketing Director, SEO Director |
| NEW: Content upload & page build (CMS) | SB-P07 | Technical SEO Specialist | 3.5 / 8.8 / 14.0 | $280 / $700 / $1,120 | 0% | 1 | Not known | Single actor |
| Sales to delivery handover | KO-P03, SB-P08, WS-P09 | Performance Marketing Director; Performance managers receiving handover; Technical SEO Specialist | 2.4 / 8.2 / 14.0 | $192 / $656 / $1,120 | 0% | 2 | Not known | Sum of each actor's own share; interviewee share only, other actors counted in their own records (WS-P09); high end scaled by the 160 h cap for Performance Marketing Director; described but not costed: KO-P03 |
| Sales – lead to proposal | KO-P01, KZ-P13, MP-P03 | Founder; Senior SEO Manager & LB Lead | 3.0 / 7.4 / 11.8 | $240 / $591 / $943 | 0% | 2 | 6–8 week sales cycle (KO-P01, KO-P02); founder availability gates proposals (MP-P03) | Sum of each actor's own share; high end scaled by the 160 h cap for Senior SEO Manager & LB Lead; described but not costed: KO-P01 |
| NEW: Performance forecasting | WS-P05 | Performance Marketing Director | 1.4 / 3.6 / 5.8 | $112 / $288 / $464 | 15% | 1 | Not known | Single actor; high end scaled by the 160 h cap for Performance Marketing Director |
| Creative production | MC-P08, WS-P13 | Performance Marketing Director; Performance Marketing Specialist | 1.7 / 3.5 / 5.4 | $136 / $282 / $429 | 0% | 2 | Not known | Sum of each actor's own share; high end scaled by the 160 h cap for Performance Marketing Director, Performance Marketing Specialist |
| Link building – outreacher invoicing | KZ-P09, TG-P05 | Senior SEO Manager & LB Lead | 1.3 / 2.6 / 3.8 | $104 / $205 / $306 | 0% | 1 | Not known | Single actor; high end scaled by the 160 h cap for Senior SEO Manager & LB Lead; described but not costed: TG-P05 |
| Client onboarding – access & setup | KO-P04, ZC-P08 | SEO Manager | 0.3 / 1.6 / 3.0 | $24 / $132 / $240 | 0% | 1 | Touch 0.5–2 h (ZC-P08) vs "can take a long time" waiting on client access (ZC-P08, KO-P04) – wait dominates; not quantified | Single actor; described but not costed: KO-P04 |
| NEW: Platform compliance checks | MC-P10 | Performance Marketing Specialist | 1.1 / 1.2 / 1.3 | $88 / $94 / $101 | 0% | 1 | Not known | Single actor; high end scaled by the 160 h cap for Performance Marketing Specialist |
| NEW: Client offboarding & handover | MC-P09 | Performance Marketing Specialist | 0.2 / 0.7 / 1.1 | $16 / $54 / $92 | 0% | 1 | Not known | Single actor; high end scaled by the 160 h cap for Performance Marketing Specialist |
| Sales – proposal to signed | KO-P02 | – | – | – | 0% | 1 | Not known | Not costed – no time discussed in KO-P02 |
| Conversion tracking setup | – | – | – | – | 0% | 0 | Not known | Not costed – not described in any interview |
| Website migration | – | – | – | – | 0% | 0 | Not known | Not costed – not described in any interview |
| Hiring & onboarding staff | KO-P09 | – | – | – | 0% | 1 | Not known | Not costed – no time discussed in KO-P09 |
| Finance & billing | KO-P07 | – | – | – | 0% | 1 | Not known | Not costed – no time discussed in KO-P07 |

**Totals.** Agency-wide, for the people interviewed: **944 / 1,422 / 1,901 h a month** (low / mid / high), costing **$75,488 / $113,792 / $152,080 a month** at $80/hr. Only **13%** of the mid-point hours rest on a stated time; the rest are assumed. Against the naive per-person sum of 1,014–2,382 h, de-duplication and the cap remove ~70 h from the low and ~480 h from the high. The high is a ceiling – it means most interviewees' whole working month is accounted for by these processes – not an estimate of waste. What the numbers can support: relative size of processes (pacing, meetings and prep, campaign build, content writing and onboarding are the biggest) and the order of magnitude of any saving. What they can't: a precise dollar figure for any single process, or a total 'recoverable' cost. 14 process records were described without time and are not costed (sales, handover, finance, hiring, live link checks, invoicing).

### 2.2 Ranked opportunities

35 merged opportunities from all 143 extraction opportunities (each used once). Ranked by priority; ties broken on Ease, then Impact. 25 of 35 carry a COI flag because at least one source opportunity was flagged as something Transpera would build.

### O-01 · Restore the pacing data feed and cover every live channel

**Rank 1 · Quick win · Priority 125** (Impact 5 × Confidence 5 × Ease 5) — **Lens:** Change the process — **Anchor:** Performance visibility & margin — **Horizon:** This month

**What changes:** Renew or replace the failing Supermetrics connector (or feed pacing from AgencyAnalytics/platform APIs), name one owner for the pacing pipeline and the M/W/F pacing bot, and add LinkedIn, ChatGPT ads, Criteo, Pinterest and TikTok to the tracker – rule: no spend goes live without a pacing line.

**Fixes:** C-01 (Paid budgets re-keyed by hand in three places, so pacing runs against wrong figures) [R2] · C-02 (Pacing tools are broken or fragile, so Meta and Google pacing is done by hand) [R1] · C-03 (Ad channels beyond Google and Meta have no pacing, so overspends go unseen) [R2] · C-04 (Performance drops and tracking breaks surface only in manual checks, often at month-end) [R3]

**Pain points:** MC-PP06, MC-PP07, MC-PP08, MP-PP02, SD-PP01, SD-PP15, SD-PP19, WS-PP02 (also WS-S01, WS-S05)

**Source opportunities:** SD-O01 · MC-O04 · MP-O01 · WS-O01

**Existing solution idea:** Pacing tracker & adjustment engine (interim step) — **Candidate tool:** Supermetrics renewal or Porter Metrics/Windsor.ai; AgencyAnalytics data; Google Sheets. Transpera build only if direct-API feed chosen.

**Hours saved:** 7.2–18.6 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SD-O01 5.0–8.9 + MC-O04 0.5–3.6 + MP-O01 0.0–1.0 + WS-O01 1.7–5.1 = 7.2–18.6 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 50.1–101.4 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 7.2–18.6 h × $80 = $576–$1,489/month. Avoided overspend: one $10K credit already paid on an untracked/mis-paced incident (MP-PP01, stated; X-10 unresolved whether it is the LinkedIn incident). Frequency unknown, so not added to the monthly figure.

**Effort:** S — **Adoption risk:** L – Restores an existing workflow people already use (SD-O01); the M/W/F bot already posts. Risk is ownership lapsing again – the feed broke unnoticed before (C-02, C-32).

**Prerequisites:** Subscription budget sign-off; named pipeline owner; list of every live channel per client (LinkedIn currently missing).

**COI flag:** **Yes** – Transpera could build this (flagged on MC-O04, WS-O01).

**Scoring notes:** Impact – hours mid 12.9 h → base 3; +2 Severity-5 clusters (C-02, C-03); untracked channel caused an overspend (MP-PP02, WS-PP02). Confidence – problem score 4 (primary cluster C-02: High), solution score 5 (4 raiser(s): SD, MC, leadership, WS); averaged; touched-process stated share 4%.

**KPIs:**

- Days pacing data auto-refreshed – baseline 0 (SD-O01); target 100% of working days (leading)
- % live platforms with a pacing line – baseline Below 100% (LinkedIn missing) (MP-O01); target 100% (leading)

### O-02 · AI data rule, company Claude seats and shared skills library

**Rank 2 · Quick win · Priority 125** (Impact 5 × Confidence 5 × Ease 5) — **Lens:** People & policy — **Anchor:** Operations capacity & process — **Horizon:** This month

**What changes:** founder issues a one-page AI rule (approved tools, what client data may be sent, human owns the decision, no raw AI screenshots in deliverables); move everyone onto company Claude seats sized to use; load proven personal workflows (forecasting prompt, search-term audit, content research prompts, industry research and compliance packs) into shared Claude Projects.

**Fixes:** C-05 (Managers spend hours collating data across platforms for calls, queries and analysis) [R4] · C-12 (Regulated-industry content lacks shared compliance rules and credible sources) [R28] · C-21 (Content hand-offs run on hand-copied sheets: briefs late or unseen, statuses double-keyed) [R11] · C-28 (Meta campaign builds are manual and every ad needs hand QA) [R37] · C-33 (AI use is personal and ungoverned: no policy, shared skills, client context or seats) [R40]

**Pain points:** DM-PP11, DM-PP12, HT-PP08, LS-PP13, MC-PP19, MC-PP20, SB-PP12, SJ-PP06, SJ-PP07, WS-PP12, WS-PP13 (also LS-S01, WS-S03)

**Source opportunities:** DM-O06 · SB-O06 · MC-O03 · LS-O08 · WS-O09 · HT-O06 · SJ-O03

**Existing solution idea:** New (enabler for AI business brain) / Team wiki & L&D — **Candidate tool:** Claude Teams Projects and skills; Notion page for the rule. No build.

**Hours saved:** 6.5–36.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): DM-O06 0.0–0.0 + SB-O06 2.0–6.0 + MC-O03 1.0–2.4 + LS-O08 0.0–4.7 + WS-O09 1.4–7.5 + HT-O06 0.6–2.3 + SJ-O03 1.5–13.1 = 6.5–36.0 h/month. High ends of capped people scaled by their 160 h cap ratio. WS-O09 capped at 1.4–7.5 h (only that process is costed) Process hours available: 123.3–216.3 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 6.5–36.0 h × $80 = $520–$2,878/month

**Effort:** S — **Adoption risk:** L – Staff already use AI daily and some pay personally (MC-O03); risk is the library going stale like the wiki (C-35).

**Prerequisites:** Decision on client-data rules and contract checks; seat budget.

**COI flag:** **Yes** – Transpera could build this (flagged on SB-O06, SJ-O03).

**Scoring notes:** Impact – hours mid 21.2 h → base 4; +1 C-33 High (9 staff + 1 leadership); unmanaged client-data exposure (risk/compliance); enabler for O-04, O-13, O-05. Confidence – problem score 5 (primary cluster C-33: High), solution score 5 (7 raiser(s): DM, SB, MC, LS, WS, HT, SJ); averaged; touched-process stated share 55%.

**KPIs:**

- Written AI-data rule published and acknowledged by Performance team – baseline None (DM-O06); target Published within 2 weeks; 100% acknowledged (leading)
- Staff paying for personal AI tools for work – baseline ≥1 (MC-O03); target 0 (lagging)

### O-03 · AI brief drafts from the Master SEO Document

**Rank 3 · Quick win · Priority 100** (Impact 5 × Confidence 4 × Ease 5) — **Lens:** Augment — **Anchor:** Operations capacity & process — **Horizon:** This month

**What changes:** A Claude skill reads the month's content plan in the Master SEO Document and drafts each brief (and regional localisation metadata) in the house template, output straight to the standard Google Doc; the SEO manager reviews and sends.

**Fixes:** C-18 (Unplanned same-day and high-touch client requests break the planned month) [R32] · C-20 (Content briefs are re-cut and reformatted by hand, eating the first half of each month) [R33]

**Pain points:** KZ-PP05, KZ-PP17, LS-PP03, ZC-PP03 (also LS-S03, ZC-B03)

**Source opportunities:** LS-O01 · KZ-O09 · ZC-O02 · KZ-O05

**Existing solution idea:** Brief & proposal generator — **Candidate tool:** Claude Teams skill + Google Docs template; Ahrefs for keywords. Transpera optional.

**Hours saved:** 9.0–22.3 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): LS-O01 4.0–6.3 + KZ-O09 3.8–11.0 + ZC-O02 1.2–5.0 = 9.0–22.3 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 48.0–114.0 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 9.0–22.3 h × $80 = $720–$1,780/month

**Effort:** S — **Adoption risk:** L – Managers already re-cut briefs by hand and want this; low new behaviour.

**Prerequisites:** One current brief template (C-20); per-client record for context (O-04).

**COI flag:** **Yes** – Transpera could build this (flagged on LS-O01, KZ-O09, KZ-O05).

**Scoring notes:** Impact – hours mid 15.6 h → base 4; +1 Briefing eats the first half of each month (C-20). Confidence – problem score 4 (primary cluster C-20: High), solution score 4 (3 raiser(s): LS, KZ, ZC); averaged; touched-process stated share 0%.

**KPIs:**

- Minutes of SEO manager time per client for monthly briefs – baseline Unknown; assumed 30–60 min (LS-O01); target ≤ 15 min incl. review (leading)
- Briefs needing manual re-formatting – baseline All – copied into Word (ZC-O02); target 0 (leading)

### O-04 · One per-client record fed by call summaries

**Rank 4 · Quick win · Priority 100** (Impact 4 × Confidence 5 × Ease 5) — **Lens:** Change the process — **Anchor:** Client experience & delivery — **Horizon:** This month

**What changes:** Each client gets one record (Monday item or Notion page plus a Claude project for focus clients) holding strategy, USPs, page/keyword map, tone, compliance rules, feedback history and current status; WIP updates go there, not personal docs; every client call is recorded and its AI summary and actions appended within 24 h.

**Fixes:** C-07 (Client knowledge sits in people's heads and personal docs, so briefs and cover suffer) [R14] · C-11 (Content stalls at client approval with no client-facing approval trail) [R10] · C-12 (Regulated-industry content lacks shared compliance rules and credible sources) [R28] · C-20 (Content briefs are re-cut and reformatted by hand, eating the first half of each month) [R33] · C-22 (Content delivery hinges on one manager as editor, router and freelancer manager) [R9] · C-36 (Escalations, sign-offs, QA and Tier 1 relationships funnel to a few senior people) [R22]

**Pain points:** HT-PP03, HT-PP04, HT-PP10, KZ-PP15, KZ-PP16, WS-PP08, WS-PP10, ZC-PP01, ZC-PP02, ZC-PP04, ZC-PP11, ZC-PP13 (also ZC-B03)

**Source opportunities:** HT-O01 · WS-O05 · ZC-O01 · KZ-O11 · ZC-O10

**Existing solution idea:** Transcripts → per-client action runsheet; AI business brain (lightweight) — **Candidate tool:** Monday.com/Notion, Otter or Gemini notes, Claude Teams Projects. Small Make.com automation; no Transpera build needed.

**Hours saved:** 5.0–18.2 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): HT-O01 1.0–3.8 + WS-O05 1.0–2.2 + ZC-O01 2.0–10.0 + KZ-O11 1.0–2.2 = 5.0–18.2 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 168.1–330.5 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 5.0–18.2 h × $80 = $400–$1,457/month

**Effort:** S — **Adoption risk:** L – Transcripts are captured but unused (X-21) – automation of the append step is preferred over asking people to file notes ("I forget half the time", KZ-O11).

**Prerequisites:** Template agreed across organic and paid; call recording consent; AI-data rule.

**COI flag:** **Yes** – Transpera could build this (flagged on ZC-O01, ZC-O10). · Bias/COI carried from clusters: C-07: COI: 'AI business brain' is Austin's own product idea (KO suggestions, interviewer-sourced).

**Scoring notes:** Impact – hours mid 11.6 h → base 3; +1 C-07 High (4 staff); briefs and cover suffer. Confidence – problem score 4 (primary cluster C-07: High), solution score 5 (4 raiser(s): HT, WS, ZC, KZ); averaged; touched-process stated share 23%.

**KPIs:**

- % of active content clients with a current profile – baseline 0 central (HT-O01); target 100% (leading)
- Client calls logged in run sheet within 24 h – baseline unknown – transcripts unused (ZC-O10); target ≥ 95% (leading)

### O-05 · Reports and review decks: auto-filled data, AI-drafted narrative

**Rank 5 · Quick win · Priority 100** (Impact 5 × Confidence 5 × Ease 4) — **Lens:** Augment — **Anchor:** Operations capacity & process — **Horizon:** This quarter

**What changes:** Turn one performance leader's AI quarterly-review workflow into one shared template + prompt + data pull for every QBR and 6-month review; auto-fill the "work completed / planned" report page and weekly client KPI sheets from platform and task data; managers write the commentary only.

**Fixes:** C-06 (Client reports, reviews and decks are assembled and narrated by hand each cycle) [R5] · C-17 (Managers are at capacity, so lower-tier clients and account hygiene slip first) [R21] · C-33 (AI use is personal and ungoverned: no policy, shared skills, client context or seats) [R40]

**Pain points:** KZ-PP18, LS-PP02, LS-PP04, LS-PP16, SH-PP06, WS-PP05, WS-PP13 (also LS-S04, LS-S10, LS-S13, SH-B05, WS-S02, ZC-P11)

**Source opportunities:** WS-O06 · LS-O11 · ZC-O11 · LS-O02 · SH-O03 · KZ-O10

**Existing solution idea:** QBR / review deck generator — **Candidate tool:** Google Slides/Sheets + AgencyAnalytics + Claude Teams; Make.com for sheet fills. Transpera build optional.

**Hours saved:** 13.2–39.7 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): WS-O06 6.0–22.1 + LS-O02 2.0–3.1 + ZC-O11 1.2–6.0 + SH-O03 2.0–4.9 + KZ-O10 2.0–3.6 = 13.2–39.7 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 50.3–88.0 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 13.2–39.7 h × $80 = $1,056–$3,180/month

**Effort:** M — **Adoption risk:** L – Builds on a workflow one leader already uses (WS-S02). Judgement call: merges Augment (decks) with Automate (data fills) because they share one data pull.

**Prerequisites:** One current master template (C-06/R5 duplication errors); data access; AI-data rule.

**COI flag:** **Yes** – Transpera could build this (flagged on WS-O06, LS-O11, ZC-O11, LS-O02, SH-O03, KZ-O10). · Bias/COI carried from clusters: C-17: Bias: interviewer's wrap-up framed organic as having little room to save time (LS-X02, MP-X04) – leading.

**Scoring notes:** Impact – hours mid 26.5 h → base 4; +1 Duplicated decks carry errors to clients (C-06). Confidence – problem score 5 (primary cluster C-06: High), solution score 5 (5 raiser(s): WS, LS, ZC, SH, KZ); averaged; touched-process stated share 0%.

**KPIs:**

- Hours per quarterly / 6-month review deck – baseline unknown (WS-O06); target ≤ 1.5 h (lagging)
- Share of reports where the page is filled from system data – baseline 0% (stated manual) (LS-O02); target 100% (leading)

### O-06 · All internal requests via Monday forms; Monday notifies, not people

**Rank 6 · Quick win · Priority 100** (Impact 5 × Confidence 5 × Ease 4) — **Lens:** Change the process — **Anchor:** Operations capacity & process — **Horizon:** This month

**What changes:** Internal and implementation requests go through Monday.com forms with required fields (account, change, why, budget, URLs, due date, QA); the week's briefs are due Monday morning and same-day asks need a reason; AI drafts the brief from a voice note. Stop the daily agenda message and "post your update" reminders – Monday native automations notify on overdue and stuck items and status is read from Monday.

**Fixes:** C-14 (Client approval cycles hold up paid optimisations and launches, while managers carry the blame) [R30] · C-17 (Managers are at capacity, so lower-tier clients and account hygiene slip first) [R21] · C-18 (Unplanned same-day and high-touch client requests break the planned month) [R32] · C-27 (Internal task briefs from managers to implementers are slow to write and often incomplete) [R36] · C-30 (Monday.com isn't the single home for work: requests bypass it and statuses go stale) [R16] · C-35 (SOPs and new systems aren't adopted, so leaders re-explain and mistakes repeat) [R12]

**Pain points:** DM-PP09, LS-PP11, LS-PP14, MC-PP01, MC-PP02, MC-PP03, MC-PP04, MC-PP05, MP-PP05, MP-PP06, SB-PP03, SB-PP04, SB-PP15, SD-PP12, SD-PP17, SH-PP09, SH-PP10 (also DM-B03, LS-S12, MC-B02, MC-B05, MP-B04, SB-B03, SD-B04, SH-B01)

**Source opportunities:** SB-O01 · MC-O01 · SH-O04 · LS-O10 · SD-O09 · DM-O03 · MC-O05 · MP-O11

**Existing solution idea:** New / Brief & proposal generator (partial) — **Candidate tool:** Monday.com forms and native automations; Claude for brief drafts. No build.

**Hours saved:** 9.7–28.5 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SB-O01 3.0–8.0 + MC-O01 2.1–6.9 + SH-O04 1.0–4.0 + LS-O10 1.0–2.4 + SD-O09 0.0–0.8 + DM-O03 0.5–1.5 + MP-O11 2.1–4.9 = 9.7–28.5 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 217.5–385.5 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 9.7–28.5 h × $80 = $776–$2,279/month

**Effort:** S — **Adoption risk:** M – Requests already bypass Monday (C-30) and reminders go unacted (R16) – removing the reminder (Eliminate) and making the form the only route is the point.

**Prerequisites:** Form templates per team; managers agree the Monday cut-off.

**COI flag:** **Yes** – Transpera could build this (flagged on SH-O04, MP-O11). · Bias/COI carried from clusters: C-17: Bias: interviewer's wrap-up framed organic as having little room to save time (LS-X02, MP-X04) – leading.

**Scoring notes:** Impact – hours mid 19.1 h → base 4; +1 C-18, C-27, C-30 – unplanned asks break the month. Confidence – problem score 5 (primary cluster C-30: High), solution score 5 (7 raiser(s): SB, MC, SH, LS, SD, DM, leadership); averaged; touched-process stated share 4%.

**KPIs:**

- % implementation tasks briefed ≥1 working day ahead – baseline unknown (MC-O01); target ≥70% (leading)
- Tasks overdue >3 days – baseline unknown (DM-O03); target −70% (leading)

### O-07 · Automated live-link checks with publisher replacement claims

**Rank 7 · Quick win · Priority 80** (Impact 5 × Confidence 4 × Ease 4) — **Lens:** Automate — **Anchor:** Performance visibility & margin — **Horizon:** This quarter

**What changes:** Weekly or monthly automated check of every paid link (live, link present, dofollow, on the approved domain); removals emailed to the publisher with a 7-day fix deadline, then a replacement claim or PayPal dispute.

**Fixes:** C-25 (Paid links vanish after payment and nobody re-checks that they stay live) [R7]

**Pain points:** KZ-PP10, MP-PP13, ZC-PP10 (also MP-B05)

**Source opportunities:** MP-O05 · KZ-O02 · ZC-O08

**Existing solution idea:** Link-building CRM with live-link monitoring — **Candidate tool:** Ahrefs/Screaming Frog scheduled crawl + Google Sheets/Make.com – no custom build needed; Transpera only if bundled into a link CRM.

**Hours saved:** 5.0–10.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): MP-O05 5.0–10.0 + KZ-O02 0.0–0.0 + ZC-O08 0.0–0.0 = 5.0–10.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 10.8–35.7 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 5.0–10.0 h × $80 = $400–$800/month + avoided loss $400–$1,300 = $800–$2,100/month. Avoided loss: ~10 dead links/month × $80–130 per link ≈ $800–1,300/month (KZ-P10/KZ-PP10, estimated). Recovery rate unknown – $ counts recovery of 50–100% (assumed).

**Effort:** M — **Adoption risk:** L – Automation chosen because manual checking stopped after April (X-20); no staff behaviour needed except claims.

**Prerequisites:** One link list with URLs (O-18); publisher terms that allow claims.

**COI flag:** **Yes** – Transpera could build this (flagged on MP-O05, KZ-O02, ZC-O08). Link monitor offered by Austin (KO). · Bias/COI carried from clusters: C-25: COI: as C-23 – link monitor offered by Austin (KO suggestions).

**Scoring notes:** Impact – hours mid 7.5 h → base 3; +3 C-25 severity 5; ~10 paid links lost a month. Confidence – problem score 4 (primary cluster C-25: High), solution score 4 (3 raiser(s): leadership, KZ, ZC); averaged; touched-process stated share 0%.

**KPIs:**

- % of paid links live at 90 days – baseline unknown (KZ-O02); target ≥ 97% (lagging)
- % paid links verified live each week – baseline 0% (MP-O05); target 100% (leading)

### O-08 · Sales-to-delivery gate: handover fields, owner, access checklist

**Rank 8 · Quick win · Priority 80** (Impact 4 × Confidence 5 × Ease 4) — **Lens:** Change the process — **Anchor:** Client experience & delivery — **Horizon:** This month

**What changes:** A deal cannot move to onboarding until required HubSpot fields (goals, budget, competitors, promises, delivery owner) are filled, the pre-sales checklist is met (website live, creative supply, access) and a handover call is booked ≥2 business days ahead; the access checklist and how-to guides go out at signing; staged onboarding/offboarding boards in Monday unlock one task at a time, ping on client replies and track conversion-tracking status per action.

**Fixes:** C-08 (Client handovers (sales to delivery, offboarding) have no structured pack or trigger) [R27] · C-09 (Client onboarding stalls waiting on access, client inputs and the tracking contractor) [R20] · C-10 (Onboarding work is manual and heavy; clustered starts swamp BAU and wear staff down) [R20] · C-31 (HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost) [R39] · C-32 (Home-built automations and tools have one builder, no documentation and no backup) [R15] · C-38 (Sales commits scope and spend that delivery can't meet profitably) [R18]

**Pain points:** KO-PP01, KO-PP22, MC-PP10, MC-PP11, MC-PP12, MC-PP13, MC-PP14, MC-PP16, MC-PP17, SB-PP10, SB-PP11, SH-PP07, WS-PP06, WS-PP07, ZC-PP07 (also MC-B01, MC-B03, MC-B07, SB-B02, SH-B06, WS-B02, WS-B04, WS-S09, WS-S10, ZC-B02)

**Source opportunities:** KO-O02 · WS-O02 · SH-O07 · MC-O07 · SB-O03 · ZC-O05 · MC-O02 · MC-O11 · MC-O12

**Existing solution idea:** Transcripts → per-client action runsheet (partial) / New — **Candidate tool:** HubSpot required properties, existing Make.com flow, Monday.com boards and automations, Gmail→Slack filter. No Transpera build.

**Hours saved:** 2.2–10.4 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KO-O02 0.0–0.0 + WS-O02 0.8–3.5 + SH-O07 0.2–1.0 + MC-O02 0.5–2.4 + SB-O03 0.5–2.0 + ZC-O05 0.2–1.5 = 2.2–10.4 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 2.9–18.1 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 2.2–10.4 h × $80 = $180–$834/month

**Effort:** S — **Adoption risk:** M – A handover step already exists on paper but is skipped (X-16) – enforce it in HubSpot stages rather than by SOP.

**Prerequisites:** Sales lead and department leads agree the gate; HubSpot admin time.

**COI flag:** **Yes** – Transpera could build this (flagged on KO-O02, MC-O11). · Bias/COI carried from clusters: C-10: COI: Austin offered his own client-research agent for new-client dossiers (KO suggestions, leadership's request). | C-38: Bias: interviewer raised the sales-overcommit problem first (MP-PP10); leadership agreed strongly.

**Scoring notes:** Impact – hours mid 6.3 h → base 3; +1 C-08 and C-09 High; onboarding waits on access (C-09). Confidence – problem score 4 (primary cluster C-08: High), solution score 5 (6 raiser(s): leadership, WS, SH, MC, SB, ZC); averaged; touched-process stated share 0%.

**KPIs:**

- % of new clients with handover call ≥2 business days before kick-off – baseline unknown (WS-O02); target ≥ 90% (leading)
- Days from signing to full access – baseline 'can take a long time' (ZC-O05); target ≤ 3 business days (lagging)

### O-09 · Implementer self-QA checklists for page and ad builds

**Rank 9 · Quick win · Priority 80** (Impact 4 × Confidence 5 × Ease 4) — **Lens:** Change the process — **Anchor:** Client experience & delivery — **Horizon:** This month

**What changes:** Implementers complete a QA checklist (devices, templates, text; Meta placements, aspect ratios, copy) before hand-off; one consolidated page-approval round from a single client approver on a visual draft; seniors spot-check rather than full QA except launches.

**Fixes:** C-13 (Page builds and content uploads reach clients with errors or loop for weeks) [R29] · C-28 (Meta campaign builds are manual and every ad needs hand QA) [R37] · C-36 (Escalations, sign-offs, QA and Tier 1 relationships funnel to a few senior people) [R22]

**Pain points:** DM-PP08, KZ-PP13, SB-PP07, SB-PP08, SD-PP16 (also DM-B02, SB-B01, SD-B05)

**Source opportunities:** KZ-O04 · SB-O05 · DM-O04 · SD-O12

**Existing solution idea:** New / AI-assisted creative (partial) — **Candidate tool:** Monday.com checklist items; multi-device screenshot tool. No build.

**Hours saved:** 3.1–12.7 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KZ-O04 0.1–0.9 + SB-O05 2.0–8.0 + DM-O04 0.3–2.0 + SD-O12 0.7–1.9 = 3.1–12.7 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 89.0–160.3 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 3.1–12.7 h × $80 = $248–$1,018/month

**Effort:** S — **Adoption risk:** M – Checklists are a known adoption risk (SOPs unread, C-35); make the Monday status depend on the checklist.

**Prerequisites:** Checklists written by the senior reviewers.

**COI flag:** **Yes** – Transpera could build this (flagged on SB-O05).

**Scoring notes:** Impact – hours mid 7.9 h → base 3; +1 Errors reach clients (C-13); senior QA bottleneck (C-36). Confidence – problem score 4 (primary cluster C-13: High), solution score 5 (4 raiser(s): KZ, SB, DM, SD); averaged; touched-process stated share 0%.

**KPIs:**

- Builds with issues found by the client – baseline unknown – 'the client sees it first' (L551) (KZ-O04); target 0 a month (lagging)
- Manager QA minutes per Meta launch – baseline 20–30 ads checked one by one; minutes unknown (DM-O04); target ≤10 min (leading)

### O-10 · Switch on native platform alert rules and scripts now

**Rank 10 · Quick win · Priority 75** (Impact 3 × Confidence 5 × Ease 5) — **Lens:** Change the process — **Anchor:** Performance visibility & margin — **Horizon:** This month

**What changes:** Turn on Meta automated rules (frequency > 3, CPL > 2× target) and Google Ads rules/scripts for CPL spikes, conversion drops (e.g. −30% week on week) and monthly negative-keyword candidates; route Merchant Center disapprovals to Slack and add a weekly owned Monday check.

**Fixes:** C-04 (Performance drops and tracking breaks surface only in manual checks, often at month-end) [R3] · C-17 (Managers are at capacity, so lower-tier clients and account hygiene slip first) [R21]

**Pain points:** DM-PP03, DM-PP10, MC-PP18, SD-PP04, SD-PP08

**Source opportunities:** SD-O04 · DM-O02 · SD-O11 · MC-O09

**Existing solution idea:** Proactive PPC anomaly monitor (interim, native) — **Candidate tool:** Google Ads rules/scripts, Meta automated rules, Slack email routing, Monday recurring item. No build.

**Hours saved:** 1.2–8.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SD-O04 0.5–1.2 + DM-O02 0.7–6.8 + MC-O09 0.0–0.0 = 1.2–8.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 81.9–169.5 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 1.2–8.0 h × $80 = $96–$641/month

**Effort:** S — **Adoption risk:** L – Uses tools already paid for; no new behaviour beyond reading an alert. Watch for alert fatigue (reminders already go unacted – C-30).

**Prerequisites:** Per-client thresholds agreed by account owners; Slack channel per team.

**COI flag:** **Yes** – Transpera could build this (flagged on DM-O02). · Bias/COI carried from clusters: C-17: Bias: interviewer's wrap-up framed organic as having little room to save time (LS-X02, MP-X04) – leading.

**Scoring notes:** Impact – hours mid 4.6 h → base 2; +1 Problems surface at month-end (C-04, 7 staff raises). Confidence – problem score 5 (primary cluster C-17: High), solution score 4 (3 raiser(s): SD, DM, MC); averaged; touched-process stated share 3%.

**KPIs:**

- Rules live per account – baseline 0 (SD-O04); target 100% of Meta accounts with frequency rule (leading)
- Time from performance drop to manager awareness – baseline Up to ~14 days (fortnightly checks) – estimated (DM-O02); target Under 24 h (leading)

### O-11 · Pacing tracker reads budgets and spend, flags gaps

**Rank 11 · Strategic · Priority 75** (Impact 5 × Confidence 5 × Ease 3) — **Lens:** Automate — **Anchor:** Performance visibility & margin — **Horizon:** Needs a build

**What changes:** One budget master (Monday client item or budget sheet) syncs to the pacing sheet; account- and campaign-level spend is pulled for all channels; the tracker recommends daily budgets, flags mismatches and creates a Monday task for over/under-pace; Day 1 resets run from bulk sheets/scripts.

**Fixes:** C-01 (Paid budgets re-keyed by hand in three places, so pacing runs against wrong figures) [R2] · C-02 (Pacing tools are broken or fragile, so Meta and Google pacing is done by hand) [R1] · C-03 (Ad channels beyond Google and Meta have no pacing, so overspends go unseen) [R2] · C-04 (Performance drops and tracking breaks surface only in manual checks, often at month-end) [R3] · C-27 (Internal task briefs from managers to implementers are slow to write and often incomplete) [R36]

**Pain points:** MC-PP07, MP-PP01, MP-PP02, MP-PP17, SD-PP01, SD-PP02, SD-PP03, SD-PP19, SH-PP01, SH-PP02, SH-PP03, SH-PP04, SH-PP05, SH-PP10 (also SD-B02, SH-B01, SH-B03)

**Source opportunities:** SD-O02 · SH-O01 · MP-O03 · MC-O10 · SH-O02

**Existing solution idea:** Pacing tracker & adjustment engine — **Candidate tool:** Google Ads scripts + Meta bulk edit, Make.com, Monday.com; Transpera would build the sync and recommendation logic.

**Hours saved:** 9.8–20.8 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SD-O02 3.9–7.2 + SH-O01 3.9–9.2 + MC-O10 2.0–4.5 = 9.8–20.8 h/month. Leadership estimate MP-O03 5.0–12.0 is team-wide and overlaps the staff figures – used as a cross-check only. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 50.1–101.4 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 9.8–20.8 h × $80 = $784–$1,666/month. Same $10K overspend exposure (MP-PP01) – counted once, under the first pacing opportunity.

**Effort:** M — **Adoption risk:** M – Automation beats augmentation here: the manual three-place entry has failed repeatedly (MP-PP01, SH-PP01, SD-PP02). Risk is false alerts eroding trust (SH-PP04).

**Prerequisites:** O-01 restored first; budget master agreed; API access to all ad accounts; decision on who approves auto-recommendations.

**COI flag:** **Yes** – Transpera could build this (flagged on SD-O02, SH-O01, MP-O03, MC-O10, SH-O02).

**Scoring notes:** Impact – hours mid 15.3 h → base 4; +1 Severity-5 clusters C-01, C-02. Confidence – problem score 4 (primary cluster C-01: High), solution score 5 (4 raiser(s): SD, SH, leadership, MC); averaged; touched-process stated share 4%.

**KPIs:**

- Systems updated per budget change – baseline 3 (SH-O01); target 1 (leading)
- Minutes per pacing adjustment – baseline 15–20 min per account (SD-O02); target ≤ 5 min (leading)

### O-12 · Cross-account performance monitor with draft diagnosis (paid and SEO)

**Rank 12 · Strategic · Priority 75** (Impact 5 × Confidence 5 × Ease 3) — **Lens:** Automate — **Anchor:** Operations capacity & process — **Horizon:** Needs a build

**What changes:** One daily table across all paid accounts (spend, conversions, CPA/ROAS/CPL, frequency, pace vs per-client rules) and a weekly SEO digest (GA4, Search Console, Ahrefs ranking/traffic drops, tech issues, wins). Exceptions go to the account owner in Slack/Monday with change history, search terms and auction data attached as a draft diagnosis. Replaces the manual mid-month check.

**Fixes:** C-04 (Performance drops and tracking breaks surface only in manual checks, often at month-end) [R3] · C-05 (Managers spend hours collating data across platforms for calls, queries and analysis) [R4] · C-15 (Seasonal, trending and competitor signals are spotted too late, by hand) [R24] · C-16 (Churn risk is spotted late and account teams report rather than advise) [R31] · C-17 (Managers are at capacity, so lower-tier clients and account hygiene slip first) [R21]

**Pain points:** DM-PP02, LS-PP05, LS-PP15, MC-PP08, MC-PP09, MP-PP16, MP-PP17, MP-PP18, SD-PP04, SD-PP14, SH-PP11, SH-PP12, WS-PP04, ZC-PP05, ZC-PP17 (also DM-B04, LS-S05, SD-B07, SH-B04, WS-S04)

**Source opportunities:** SD-O05 · DM-O01 · MC-O06 · MP-O04 · WS-O03 · SH-O06 · LS-O03 · ZC-O03

**Existing solution idea:** Proactive PPC anomaly monitor — **Candidate tool:** AgencyAnalytics alerts and Looker Studio first; otherwise Make.com + platform APIs + Claude. Transpera would build the rules engine and diagnosis step.

**Hours saved:** 11.5–37.1 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SD-O05 1.6–4.5 + DM-O01 3.3–8.7 + MC-O06 1.8–5.9 + WS-O03 1.0–5.5 + SH-O06 0.2–2.3 + LS-O03 2.0–4.7 + ZC-O03 1.6–5.5 = 11.5–37.1 h/month. Leadership estimate MP-O04 10.0–41.0 is team-wide and overlaps the staff figures – used as a cross-check only. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 134.3–261.3 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 11.5–37.1 h × $80 = $924–$2,966/month

**Effort:** M — **Adoption risk:** M – Alerts compete with ignored reminders (C-30, MP-PP05). Automation preferred over a checklist because manual checks are already skipped (ZC-O03 baseline "sometimes skipped").

**Prerequisites:** Native rules (above) live first to learn thresholds; per-client targets; API access; conversion-tracking baseline per form (C-09 contractor dependency).

**COI flag:** **Yes** – Transpera could build this (flagged on SD-O05, DM-O01, MC-O06, MP-O04, WS-O03, SH-O06, LS-O03, ZC-O03). · Bias/COI carried from clusters: C-17: Bias: interviewer's wrap-up framed organic as having little room to save time (LS-X02, MP-X04) – leading.

**Scoring notes:** Impact – hours mid 24.3 h → base 4; +1 C-04 High confidence, 7 staff; tracking breaks undetected ~7 days (SH-PP11). Confidence – problem score 5 (primary cluster C-04: High), solution score 5 (8 raiser(s): SD, DM, MC, leadership, WS, SH, LS, ZC); averaged; touched-process stated share 2%.

**KPIs:**

- Days from drop to detection – baseline Up to ~2 weeks / month-end (SD-O05); target ≤ 2 days (lagging)
- Days from tracking break to detection – baseline up to ~7 days (SH-O06); target ≤ 1 day (lagging)

### O-13 · AI per-client summary for reports, calls and data questions

**Rank 13 · Strategic · Priority 75** (Impact 5 × Confidence 5 × Ease 3) — **Lens:** Augment — **Anchor:** Operations capacity & process — **Horizon:** Needs a build

**What changes:** Each month (and before each call or WIP) an AI draft per client pulls change history, month-on-month metrics across channels, last call actions and open items; it drafts the AgencyAnalytics commentary, the pre-call brief and the post-call follow-up for the manager to edit. Phase 2: a per-client data layer (Ads, Meta, GA4, CRM) managers can query in plain English.

**Fixes:** C-05 (Managers spend hours collating data across platforms for calls, queries and analysis) [R4] · C-06 (Client reports, reviews and decks are assembled and narrated by hand each cycle) [R5] · C-07 (Client knowledge sits in people's heads and personal docs, so briefs and cover suffer) [R14] · C-17 (Managers are at capacity, so lower-tier clients and account hygiene slip first) [R21] · C-33 (AI use is personal and ungoverned: no policy, shared skills, client context or seats) [R40]

**Pain points:** DM-PP01, DM-PP04, DM-PP05, DM-PP10, DM-PP11, SD-PP05, SD-PP06, SD-PP13, SD-PP14, SH-PP09, SH-PP13, WS-PP03, WS-PP08 (also WS-S06)

**Source opportunities:** DM-O05 · SD-O06 · SH-O05 · DM-O08 · WS-O04 · SD-O10

**Existing solution idea:** Client-call prep summaries; AI business brain (phase 2) — **Candidate tool:** AgencyAnalytics + Claude Teams project per client first; phase 2 data warehouse/Looker + Claude. Transpera would build the data pull and prompts.

**Hours saved:** 14.0–39.6 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): DM-O05 4.8–11.8 + SD-O06 5.0–13.9 + SH-O05 1.3–6.7 + WS-O04 2.9–7.2 = 14.0–39.6 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 178.2–323.1 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 14.0–39.6 h × $80 = $1,120–$3,171/month

**Effort:** M — **Adoption risk:** M – Prep is a personal craft; one manager gave no prep time (SH-O05 risk H). Transcripts exist but are unused (X-21) – design so the draft arrives unasked.

**Prerequisites:** Company Claude seats and AI-data rule (C-33); call recording on; read-only API access to platforms.

**COI flag:** **Yes** – Transpera could build this (flagged on DM-O05, SD-O06, SH-O05, DM-O08, WS-O04, SD-O10). · Bias/COI carried from clusters: C-07: COI: 'AI business brain' is Austin's own product idea (KO suggestions, interviewer-sourced). | C-17: Bias: interviewer's wrap-up framed organic as having little room to save time (LS-X02, MP-X04) – leading.

**Scoring notes:** Impact – hours mid 26.8 h → base 4; +1 C-05 High (4 staff); prep ~1h15 for a 30–45 min call (pack §7, SD-PP05). Confidence – problem score 4 (primary cluster C-05: High), solution score 5 (4 raiser(s): DM, SD, SH, WS); averaged; touched-process stated share 26%.

**KPIs:**

- Prep + follow-up minutes per call – baseline 60–75 min per 30-min call (SD-O06); target ≤ 30–40 min (leading)
- Minutes per client on monthly commentary – baseline ~30 min (DM-O05); target ≤12 min (leading)

### O-14 · AI-prefilled onboarding audit and Master SEO Document

**Rank 14 · Strategic · Priority 75** (Impact 5 × Confidence 5 × Ease 3) — **Lens:** Augment — **Anchor:** Client experience & delivery — **Horizon:** Needs a build

**What changes:** From the signed site and read-only access, AI (Claude + Ahrefs) pre-fills the Master SEO Document (URL/keyword map, draft metadata, competitors) and a first-pass paid account audit against the 30-item checklist; the strategist reviews. The same engine can produce prospect decks and a lead-magnet audit later.

**Fixes:** C-09 (Client onboarding stalls waiting on access, client inputs and the tracking contractor) [R20] · C-10 (Onboarding work is manual and heavy; clustered starts swamp BAU and wear staff down) [R20] · C-39 (Growth depends on the founder and inbound leads while AI erodes core services) [R42]

**Pain points:** KZ-PP01, KZ-PP02, KZ-PP03, KZ-PP04, KZ-PP21, SD-PP09, SD-PP10, SD-PP11 (also KZ-B03, SB-S09, SD-B03)

**Source opportunities:** KZ-O01 · SD-O07 · KZ-O12 · SB-O09

**Existing solution idea:** 1-click audit (read-only access + AI audit) — **Candidate tool:** Claude Teams + Ahrefs API; Google Ads read-only access. Transpera would build the engine.

**Hours saved:** 5.1–29.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KZ-O01 4.2–19.5 + SD-O07 0.9–9.4 + SB-O09 0.0–0.0 = 5.1–29.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 31.7–121.4 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 5.1–29.0 h × $80 = $408–$2,316/month

**Effort:** M — **Adoption risk:** M – Builds on a prompt guide that already cut strategy from ~3 days to ~75–90 min (pack §5) – adoption precedent is good. COI: Austin offered his own client-research agent for dossiers.

**Prerequisites:** The existing Claude SEO-strategy prompt guide as the base (strength); read-only access at signing (O-08); AI-data rule.

**COI flag:** **Yes** – Transpera could build this (flagged on KZ-O01, SD-O07, KZ-O12, SB-O09). Austin offered his own client-research agent for new-client dossiers (KO). · Bias/COI carried from clusters: C-10: COI: Austin offered his own client-research agent for new-client dossiers (KO suggestions, leadership's request).

**Scoring notes:** Impact – hours mid 17.0 h → base 4; +1 C-10 severity 5; clustered starts swamp BAU. Confidence – problem score 5 (primary cluster C-10: High), solution score 4 (3 raiser(s): KZ, SD, SB); averaged; touched-process stated share 0%.

**KPIs:**

- Strategist hours per onboarding – baseline unknown – 'takes a really long time' (L164) (KZ-O01); target –50 to –67% (lagging)
- Audit hours per onboarding – baseline unknown (SD-O07); target -40% (lagging)

### O-15 · Enter budgets once, log every change, written overspend policy

**Rank 15 · Quick win · Priority 64** (Impact 4 × Confidence 4 × Ease 4) — **Lens:** Change the process — **Anchor:** Performance visibility & margin — **Horizon:** This month

**What changes:** Allocations are typed once in the recommendations sheet and the pacing sheet reads from it; every budget change goes in one log the same day and is checked at WIP; a written overspend-credit policy says who pays and when.

**Fixes:** C-01 (Paid budgets re-keyed by hand in three places, so pacing runs against wrong figures) [R2] · C-30 (Monday.com isn't the single home for work: requests bypass it and statuses go stale) [R16]

**Pain points:** MP-PP01, MP-PP05, SD-PP02 (also MP-B03)

**Source opportunities:** SD-O03 · MP-O02

**Existing solution idea:** Pacing tracker & adjustment engine (process step) / New (policy) — **Candidate tool:** Google Sheets formulas; Monday.com WIP item. No build.

**Hours saved:** 0.8–3.6 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SD-O03 0.3–0.6 + MP-O02 0.5–3.0 = 0.8–3.6 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 50.1–101.4 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.8–3.6 h × $80 = $64–$286/month. Protects against repeats of the $10K overspend credit (MP-PP01, stated).

**Effort:** S — **Adoption risk:** M – Relies on people updating one log the same day – the same behaviour that failed before (MP-PP01, budgets not entered). Pair with O-11 to remove the manual step.

**Prerequisites:** Agree which sheet is the source; leadership signs the overspend policy.

**COI flag:** No

**Scoring notes:** Impact – hours mid 2.2 h → base 2; +2 Severity-5 cluster C-01; $10K credit incident. Confidence – problem score 4 (primary cluster C-01: High), solution score 3 (2 raiser(s): SD, leadership); averaged; touched-process stated share 4%.

**KPIs:**

- Places budgets hand-keyed – baseline 3 (SD-O03); target 2 (then 1 with O02) (leading)
- Overspend incidents per month – baseline ~0.5–1 (estimated) (MP-O02); target 0 (lagging)

### O-16 · Own and verify automations: register, backup admin, reconciliation

**Rank 16 · Quick win · Priority 60** (Impact 3 × Confidence 4 × Ease 5) — **Lens:** People & policy — **Anchor:** Technology, AI & stack — **Horizon:** This month

**What changes:** Register every Make scenario, bot, Apps Script and extension (purpose, owner, backup, location); name and train a second Monday/Make admin; run a 1st-of-month check that tickets in HubSpot and tasks in Monday match each client's scope; decide keep/trim/replace on HubSpot and Monday before the renewal.

**Fixes:** C-30 (Monday.com isn't the single home for work: requests bypass it and statuses go stale) [R16] · C-31 (HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost) [R39] · C-32 (Home-built automations and tools have one builder, no documentation and no backup) [R15] · C-35 (SOPs and new systems aren't adopted, so leaders re-explain and mistakes repeat) [R12]

**Pain points:** KO-PP11, KO-PP12, KO-PP13, SB-PP06, SB-PP11, TG-PP09 (also KO-B06)

**Source opportunities:** SB-O04 · TG-O07 · KO-O06 · KO-O07

**Existing solution idea:** New (fixes "Slack bots and agents have no visible owner") — **Candidate tool:** Notion register; HubSpot/Monday reports. No build.

**Hours saved:** 1.0–4.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SB-O04 1.0–3.0 + TG-O07 0.0–1.0 + KO-O06 0.0–0.0 = 1.0–4.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 66.9–123.7 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 1.0–4.0 h × $80 = $80–$320/month. Possible licence saving from the HubSpot/Monday decision – not quoted until invoices are checked (X-31).

**Effort:** S — **Adoption risk:** L – Mostly documentation; the pacing bot already broke unnoticed (pack §2).

**Prerequisites:** Time from the builders to document; renewal date.

**COI flag:** **Yes** – Transpera could build this (flagged on KO-O06, KO-O07).

**Scoring notes:** Impact – hours mid 2.5 h → base 2; +1 C-31, C-32 – one builder, no backup; ~$30K/yr stack (KO-PP12). Confidence – problem score 4 (primary cluster C-32: High), solution score 4 (3 raiser(s): SB, TG, leadership); averaged; touched-process stated share 10%.

**KPIs:**

- Make scenarios with written documentation – baseline unknown (assume 0) (SB-O04); target 100% (leading)
- Clients whose monthly task set matches scope – baseline Unknown (KO-O06); target 100% each month, with alerts for gaps (leading)

### O-17 · Cap concurrent onboardings per manager; protect BAU time

**Rank 17 · Quick win · Priority 60** (Impact 3 × Confidence 5 × Ease 4) — **Lens:** People & policy — **Anchor:** Operations capacity & process — **Horizon:** This month

**What changes:** Maximum two concurrent onboardings per manager with an allocation rule; pool month-1 keyword research above the cap; when a specialist onboards, cap team implementation that week; send access requests with the contract to start the clock earlier.

**Fixes:** C-09 (Client onboarding stalls waiting on access, client inputs and the tracking contractor) [R20] · C-10 (Onboarding work is manual and heavy; clustered starts swamp BAU and wear staff down) [R20] · C-17 (Managers are at capacity, so lower-tier clients and account hygiene slip first) [R21] · C-18 (Unplanned same-day and high-touch client requests break the planned month) [R32] · C-19 (Effort per client isn't tracked, so capacity, pricing and margin are set by feel) [R26] · C-20 (Content briefs are re-cut and reformatted by hand, eating the first half of each month) [R33]

**Pain points:** KO-PP08, KO-PP09, KZ-PP02, KZ-PP05, KZ-PP22, KZ-PP23, MC-PP01, MC-PP09, MC-PP12, SD-PP07, SD-PP10, ZC-PP02, ZC-PP08 (also KO-B03, KO-B04)

**Source opportunities:** KO-O15 · KZ-O07 · ZC-O06 · SD-O08 · MC-O08

**Existing solution idea:** New — **Candidate tool:** Monday.com workload view. No build.

**Hours saved:** 0.0–5.2 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KO-O15 0.0–0.0 + KZ-O07 0.0–0.0 + ZC-O06 0.0–2.0 + SD-O08 0.0–1.6 + MC-O08 0.0–1.6 = 0.0–5.2 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 31.7–121.4 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.0–5.2 h × $80 = $0–$418/month

**Effort:** S — **Adoption risk:** M – Conflicts with sales timing (C-38) – needs leadership to hold the line.

**Prerequisites:** Leadership agrees the cap and what happens to sales start dates.

**COI flag:** No · Bias/COI carried from clusters: C-10: COI: Austin offered his own client-research agent for new-client dossiers (KO suggestions, leadership's request). | C-17: Bias: interviewer's wrap-up framed organic as having little room to save time (LS-X02, MP-X04) – leading.

**Scoring notes:** Impact – hours mid 2.6 h → base 2; +1 C-10 severity 5, 4 staff + 2 leadership. Confidence – problem score 5 (primary cluster C-10: High), solution score 5 (5 raiser(s): leadership, KZ, ZC, SD, MC); averaged; touched-process stated share 0%.

**KPIs:**

- Concurrent onboardings per manager – baseline Up to 5 sites in a month (L164) (KZ-O07); target ≤ 2 (leading)
- Days from signing to fully onboarded – baseline About 1 month (KO-O15); target Under 21 days (lagging)

### O-18 · One link record: standard order template, auto-sync, invoice run

**Rank 18 · Strategic · Priority 60** (Impact 5 × Confidence 4 × Ease 3) — **Lens:** Change the process — **Anchor:** Operations capacity & process — **Horizon:** This quarter

**What changes:** One standard order template with fixed order IDs; external publishers see a filtered view of one Aperitif-owned order sheet; a publisher's completed-link entry triggers copy to the master sheet and Monday.com via one owned automation; outreachers invoice against link IDs on a form and payment runs weekly in one approval pass. A link-building CRM only if the sheet route fails.

**Fixes:** C-23 (Link building runs on disconnected sheets; every order, link and invoice is re-keyed) [R6] · C-24 (Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent) [R34] · C-32 (Home-built automations and tools have one builder, no documentation and no backup) [R15]

**Pain points:** KO-PP16, KZ-PP08, MP-PP14, MP-PP15, TG-PP05, TG-PP06, TG-PP07, TG-PP09, TG-PP10 (also TG-B04)

**Source opportunities:** TG-O03 · TG-O02 · MP-O06 · KO-O08 · KZ-O13

**Existing solution idea:** Link-building CRM with live-link monitoring and invoice follow-up — **Candidate tool:** Google Sheets + Apps Script/Make.com + Monday.com first; CRM would be a Transpera build.

**Hours saved:** 6.0–26.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): TG-O02 5.6–24.0 + KZ-O13 0.4–2.0 = 6.0–26.0 h/month. Leadership estimate MP-O06 4.0–9.0 is team-wide and overlaps the staff figures – used as a cross-check only. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 55.4–175.4 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 6.0–26.0 h × $80 = $480–$2,079/month

**Effort:** M — **Adoption risk:** M – Seven-plus sheets used by external publishers; change must not slow supply. COI: Austin offered to build a link CRM with leadership.

**Prerequisites:** Agree the master sheet; document existing home-built scripts (C-32).

**COI flag:** **Yes** – Transpera could build this (flagged on TG-O02, MP-O06, KO-O08). Austin offered to build a link-building CRM/monitor with leadership (KO). · Bias/COI carried from clusters: C-23: COI: Austin offered to build a link-building CRM/link monitor with leadership ('maybe we can do something together', KO suggestions).

**Scoring notes:** Impact – hours mid 16.0 h → base 4; +1 C-23 High; every order re-keyed. Confidence – problem score 4 (primary cluster C-23: High), solution score 4 (3 raiser(s): TG, leadership, KZ); averaged; touched-process stated share 6%.

**KPIs:**

- Published links re-keyed by hand – baseline All 300–340 a month (TG-O02); target 0 (leading)
- Order-number mismatches per month – baseline 'sometimes' (TG-O03); target 0 (lagging)

### O-19 · Effort model: hours per client, load triggers, rebalanced books

**Rank 19 · Strategic · Priority 60** (Impact 4 × Confidence 5 × Ease 3) — **Lens:** Change the process — **Anchor:** Operations capacity & process — **Horizon:** This quarter

**What changes:** Use hours already allocated on monthly HubSpot/Monday tickets to compare allocated vs actual effort per client and per role (no timesheets); set client-load triggers per role for hiring; rebalance the two most overloaded senior books (move smaller clients and ~8 paid channels to senior managers).

**Fixes:** C-17 (Managers are at capacity, so lower-tier clients and account hygiene slip first) [R21] · C-18 (Unplanned same-day and high-touch client requests break the planned month) [R32] · C-19 (Effort per client isn't tracked, so capacity, pricing and margin are set by feel) [R26] · C-35 (SOPs and new systems aren't adopted, so leaders re-explain and mistakes repeat) [R12] · C-37 (Management layer is thin: paid media lacks a senior lead; new leads lack training) [R41]

**Pain points:** KO-PP07, KO-PP26, LS-PP01, LS-PP02, MP-PP07, MP-PP18, MP-PP19, SB-PP13, SB-PP15, WS-PP01, WS-PP11 (also LS-B03, LS-S14)

**Source opportunities:** KO-O03 · MP-O13 · LS-O06 · WS-O08 · SB-O08

**Existing solution idea:** Sales wiki / spend calculator (partial) / New — **Candidate tool:** HubSpot + Monday.com reporting; Google Sheets model. No build.

**Hours saved:** 0.0–0.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KO-O03 0.0–0.0 + LS-O06 8.5–16.7 + WS-O08 8.7–12.7 + SB-O08 0.0–0.0 = 0.0–0.0 h/month. High ends of capped people scaled by their 160 h cap ratio. These 17.2–29.4 h are senior hours freed by moving work to others – redistributed, not saved agency-wide, so saving is shown as 0. Process hours available: 191.0–300.8 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.0–0.0 h × $80 = $0–$0/month

**Effort:** M — **Adoption risk:** H – Effort tracking has never existed ("a bit of a feel", KZ-O07); reassigning accounts touches client relationships.

**Prerequisites:** Agreed hours per client tier from the price calculator; leadership decision on reassignments.

**COI flag:** No · Bias/COI carried from clusters: C-17: Bias: interviewer's wrap-up framed organic as having little room to save time (LS-X02, MP-X04) – leading.

**Scoring notes:** Impact – hours mid 0.0 h → base 1; +3 Margin set by feel (C-19) and managers at capacity (C-17, 7 staff + 2 leadership). Confidence – problem score 5 (primary cluster C-17: High), solution score 5 (4 raiser(s): leadership, LS, WS, SB); averaged; touched-process stated share 2%.

**KPIs:**

- Clients with allocated hours vs revenue shown (margin per client) – baseline 0% – no timesheets or utilisation tracking (KO-O03); target All tier-1 and tier-2 clients within one quarter (leading)
- Channels managed by the senior performance lead – baseline 18 (WS-O08); target ≤ 10 (leading)

### O-20 · Widen link supply: shared vetting skill, client matching, mentions

**Rank 20 · Strategic · Priority 60** (Impact 4 × Confidence 5 × Ease 3) — **Lens:** Augment — **Anchor:** Operations capacity & process — **Horizon:** This quarter

**What changes:** One shared, versioned lead-review skill built from the link-building team's criteria and tested on past decisions; outreachers and broker intake run it before submitting, and only borderline domains go for human review; a client requirements table lets Claude suggest the best client per approved domain; review link quotas (fewer, higher-quality links); unlinked brand-mention outreach for Tier 1/2.

**Fixes:** C-23 (Link building runs on disconnected sheets; every order, link and invoice is re-keyed) [R6] · C-24 (Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent) [R34]

**Pain points:** KZ-PP06, KZ-PP07, KZ-PP08, KZ-PP09, LS-PP12, TG-PP01, TG-PP02, TG-PP04, TG-PP08, ZC-PP16 (also KZ-B01, LS-B02, LS-S08, TG-B01, TG-B02, TG-B05)

**Source opportunities:** KZ-O03 · TG-O01 · TG-O06 · TG-O04 · LS-O09 · ZC-O09

**Existing solution idea:** Link-building CRM (part) / Unlinked brand-mention outreach — **Candidate tool:** Claude Teams skill + Ahrefs; Google Forms intake; brand-mention monitor (Ahrefs Alerts). Transpera optional.

**Hours saved:** 5.0–19.5 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KZ-O03 2.0–5.3 + TG-O04 3.0–14.2 + LS-O09 0.0–0.0 + ZC-O09 0.0–0.0 = 5.0–19.5 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 43.3–135.9 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 5.0–19.5 h × $80 = $400–$1,560/month

**Effort:** M — **Adoption risk:** M – AI vetting today is inconsistent between people (C-24) – a versioned shared skill is the fix, but needs calibration.

**Prerequisites:** Criteria written down by the link-building team; past approve/decline data.

**COI flag:** **Yes** – Transpera could build this (flagged on TG-O01, TG-O06, TG-O04, ZC-O09). · Bias/COI carried from clusters: C-23: COI: Austin offered to build a link-building CRM/link monitor with leadership ('maybe we can do something together', KO suggestions).

**Scoring notes:** Impact – hours mid 12.3 h → base 3; +1 Supply-constrained, manual sourcing (C-24, 4 staff). Confidence – problem score 4 (primary cluster C-24: High), solution score 5 (4 raiser(s): KZ, TG, LS, ZC); averaged; touched-process stated share 8%.

**KPIs:**

- % of skill-approved leads the link-building lead approves – baseline 50% (TG-O01); target ≥ 85% (leading)
- Days from domain added to approval decision – baseline 'a couple of days' (L132) (KZ-O03); target ≤ 1 working day (leading)

### O-21 · Delegation and triage rules for escalations and sign-offs

**Rank 21 · Quick win · Priority 48** (Impact 4 × Confidence 3 × Ease 4) — **Lens:** People & policy — **Anchor:** Leadership & dependency — **Horizon:** This month

**What changes:** Escalation playbook (department lead first, leadership on defined triggers); triage SOP → senior manager → director; senior managers sign off experienced managers' strategies; standard SME contracts under a set value signed without the founder; bookkeeper prepares AP/payroll batches for approval only; a named second relationship owner for each Tier 1 account.

**Fixes:** C-17 (Managers are at capacity, so lower-tier clients and account hygiene slip first) [R21] · C-35 (SOPs and new systems aren't adopted, so leaders re-explain and mistakes repeat) [R12] · C-36 (Escalations, sign-offs, QA and Tier 1 relationships funnel to a few senior people) [R22] · C-37 (Management layer is thin: paid media lacks a senior lead; new leads lack training) [R41] · C-39 (Growth depends on the founder and inbound leads while AI erodes core services) [R42]

**Pain points:** KO-PP02, KO-PP03, KO-PP17, MP-PP08, MP-PP09, WS-PP01, WS-PP09, WS-PP10 (also KO-B01, KO-B05, MP-B01, WS-B01, WS-B05)

**Source opportunities:** MP-O09 · WS-O07 · KO-O05 · KO-O04

**Existing solution idea:** New (fixes "escalations route around department leads") — **Candidate tool:** Notion playbook; Xero bill approvals. No build.

**Hours saved:** 5.3–15.7 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): MP-O09 2.0–8.0 + WS-O07 3.3–7.7 = 5.3–15.7 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 80.8–110.7 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 5.3–15.7 h × $80 = $424–$1,253/month

**Effort:** S — **Adoption risk:** M – Habit of going to the top is entrenched (C-36); needs leadership to redirect consistently.

**Prerequisites:** Leadership agrees thresholds; coaching for department leads.

**COI flag:** No · Bias/COI carried from clusters: C-17: Bias: interviewer's wrap-up framed organic as having little room to save time (LS-X02, MP-X04) – leading.

**Scoring notes:** Impact – hours mid 10.5 h → base 3; +1 C-36 key-person risk on the founder and leadership (part of the saving is redistribution to department leads). Confidence – problem score 4 (primary cluster C-36: High), solution score 3 (2 raiser(s): leadership, WS); averaged −1 (no stated time in touched processes, ≤2 raisers); touched-process stated share 0%.

**KPIs:**

- % escalations handled by department leads – baseline Low (MP-O09); target ≥50% (leading)
- Contracts signed without the founder – baseline 0% – the founder signs every contract (KO-O05); target Standard SME deals signed without the founder (lagging)

### O-22 · Sales discipline: calculator, margin check, speed-to-lead

**Rank 22 · Quick win · Priority 48** (Impact 4 × Confidence 3 × Ease 4) — **Lens:** Change the process — **Anchor:** Growth & sales engine — **Horizon:** This month

**What changes:** Price-calculator output mandatory in every proposal and a delivery-lead margin check above a scope threshold; price links by lead tier (premium for dynamic clients); HubSpot speed-to-lead alert (no call in 5 minutes), objections library and loss-reason field; pilot two or three new offers with written margins.

**Fixes:** C-24 (Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent) [R34] · C-29 (Creative and landing pages are outsourced, slow and hard to brief) [R38] · C-38 (Sales commits scope and spend that delivery can't meet profitably) [R18] · C-39 (Growth depends on the founder and inbound leads while AI erodes core services) [R42]

**Pain points:** KO-PP17, KO-PP18, KO-PP19, KO-PP23, KO-PP24, KO-PP25, MP-PP10, MP-PP11, MP-PP12, TG-PP03 (also KO-B01, MP-B02, TG-B03)

**Source opportunities:** MP-O07 · TG-O05 · KO-O11 · KO-O12

**Existing solution idea:** Sales wiki / spend calculator — **Candidate tool:** HubSpot workflows and required properties; existing price calculator. No build.

**Hours saved:** 1.0–4.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): MP-O07 1.0–4.0 + TG-O05 0.0–0.0 = 1.0–4.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 3.0–11.8 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 1.0–4.0 h × $80 = $80–$320/month. Link margin leak on dynamic clients – not quantified (TG-O05).

**Effort:** S — **Adoption risk:** M – Sales is new and the interview was not recorded – evidence is leadership-only plus delivery staff (C-38).

**Prerequisites:** Calculator margin maths fixed first (R26 – margin maths wrong); sales lead buy-in.

**COI flag:** **Yes** – Transpera could build this (flagged on KO-O11). · Bias/COI carried from clusters: C-38: Bias: interviewer raised the sales-overcommit problem first (MP-PP10); leadership agreed strongly.

**Scoring notes:** Impact – hours mid 2.5 h → base 2; +2 Unprofitable scope sold (C-38); margin leak on links (TG-PP03). Confidence – problem score 4 (primary cluster C-39: High), solution score 3 (2 raiser(s): leadership, TG); averaged −1 (no stated time in touched processes, ≤2 raisers); touched-process stated share 0%.

**KPIs:**

- % proposals with calculator output – baseline unknown (MP-O07); target 100% (leading)
- Leads called within 5 minutes – baseline Unknown (KO-O11); target At least 80% (leading)

### O-23 · "Problem plus recommendation" rule in reports and calls

**Rank 23 · Quick win · Priority 48** (Impact 3 × Confidence 4 × Ease 4) — **Lens:** People & policy — **Anchor:** Client experience & delivery — **Horizon:** This month

**What changes:** Every client update and monthly report states the problem and a recommendation; add an "opportunities" step to call prep and 6-month reviews with an upsell template and short coaching in WIPs.

**Fixes:** C-16 (Churn risk is spotted late and account teams report rather than advise) [R31]

**Pain points:** KO-PP20, LS-PP08, LS-PP09 (also LS-S09)

**Source opportunities:** KO-O13 · LS-O07

**Existing solution idea:** Client-call prep summaries (partial) / New — **Candidate tool:** Report template in AgencyAnalytics; WIP agenda. No build.

**Hours saved:** 0.0–0.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KO-O13 0.0–0.0 + LS-O07 0.0–0.0 = 0.0–0.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 143.9–252.6 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.0–0.0 h × $80 = $0–$0/month. Expansion MRR not baselined (LS-O07).

**Effort:** S — **Adoption risk:** M – Behaviour change across ~12 account managers; earlier SOPs went unread (C-35).

**Prerequisites:** Template; leadership coaching time.

**COI flag:** No

**Scoring notes:** Impact – hours mid 0.0 h → base 1; +2 Account teams report rather than advise – churn and upsell risk (C-16). Confidence – problem score 4 (primary cluster C-16: High), solution score 3 (2 raiser(s): leadership, LS); averaged; touched-process stated share 29%.

**KPIs:**

- Monthly reports with an explicit recommendation – baseline Unknown (KO-O13); target 100% of tier-1 reports (leading)
- Upsell/cross-sell proposals raised per month – baseline Unknown ("a few") (LS-O07); target Set after baseline count (leading)

### O-24 · Client approval SLAs with logged dates and reminders

**Rank 24 · Quick win · Priority 48** (Impact 3 × Confidence 4 × Ease 4) — **Lens:** Change the process — **Anchor:** Client experience & delivery — **Horizon:** This month

**What changes:** Log sent and approved dates for every client approval; approval window in the client agreement (e.g. 5 business days, deemed approved for low-risk content; 2 days for paid optimisations under a "change authority" clause) with automatic reminders on day 3 and 5 and a stalled-client flag. A client portal (phase 2) only if SLAs do not move the numbers.

**Fixes:** C-11 (Content stalls at client approval with no client-facing approval trail) [R10] · C-14 (Client approval cycles hold up paid optimisations and launches, while managers carry the blame) [R30]

**Pain points:** DM-PP06, DM-PP07, LS-PP06, LS-PP07, LS-PP17, ZC-PP06 (also DM-B01, DM-B04, DM-B05, LS-B01, LS-S06, LS-S07, LS-S11, ZC-B01)

**Source opportunities:** LS-O04 · ZC-O04 · DM-O07 · LS-O05

**Existing solution idea:** Client approval portal (lightweight version first) — **Candidate tool:** Monday.com date columns and automations; contract template. Portal would be a Transpera build.

**Hours saved:** 2.6–8.7 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): LS-O05 2.0–4.7 + ZC-O04 0.3–2.5 + DM-O07 0.3–1.5 = 2.6–8.7 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 85.0–195.5 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 2.6–8.7 h × $80 = $208–$695/month

**Effort:** S — **Adoption risk:** M – Client-facing change; managers carry the blame for delays today (C-14).

**Prerequisites:** Contract wording change; account managers willing to enforce.

**COI flag:** **Yes** – Transpera could build this (flagged on LS-O05).

**Scoring notes:** Impact – hours mid 5.6 h → base 2; +1 C-11, C-14 High; ~1 week average approval (ZC-P04). Confidence – problem score 4 (primary cluster C-11: High), solution score 4 (3 raiser(s): LS, ZC, DM); averaged; touched-process stated share 3%.

**KPIs:**

- Days from content sent to approval – baseline ~7 days average (ZC-O04); target ≤ 4 business days (lagging)
- Median approval turnaround for optimisations – baseline unknown (DM-O07); target ≤2 business days (lagging)

### O-25 · Content intake on Monday with brief standard and slots

**Rank 25 · Strategic · Priority 48** (Impact 4 × Confidence 4 × Ease 3) — **Lens:** Change the process — **Anchor:** Operations capacity & process — **Horizon:** This quarter

**What changes:** One brief intake route in Monday.com with a minimum brief standard (context, prior feedback, sources, compliance, due date); rule-based assignment confirmed by the content team with alerts; freelancers on their own boards with guest access; late briefs roll to a defined slot; staggered freelancer due dates; the out-of-cycle client gets a reserved allowance and cut-off; edited files auto-filed and the tracker sheet linked until retired.

**Fixes:** C-07 (Client knowledge sits in people's heads and personal docs, so briefs and cover suffer) [R14] · C-18 (Unplanned same-day and high-touch client requests break the planned month) [R32] · C-21 (Content hand-offs run on hand-copied sheets: briefs late or unseen, statuses double-keyed) [R11] · C-22 (Content delivery hinges on one manager as editor, router and freelancer manager) [R9] · C-32 (Home-built automations and tools have one builder, no documentation and no backup) [R15]

**Pain points:** HT-PP01, HT-PP02, HT-PP05, HT-PP06, SJ-PP01, SJ-PP02, SJ-PP03, SJ-PP04, SJ-PP05, SJ-PP06, SJ-PP08, SJ-PP09, SJ-PP10, SJ-PP11, SJ-PP12, SJ-PP14 (also HT-B01, HT-B02, HT-B04, SJ-B01, SJ-B02, SJ-B03, SJ-B04)

**Source opportunities:** SJ-O01 · SJ-O02 · SJ-O04 · SJ-O05 · SJ-O07 · HT-O03 · HT-O04 · HT-O05

**Existing solution idea:** New (fixes "content tracker and link sheets live outside Monday") — **Candidate tool:** Monday.com forms, automations, guest access; Make.com for Drive filing. No Transpera build.

**Hours saved:** 4.8–20.1 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SJ-O01 3.8–16.1 + HT-O04 1.0–4.0 = 4.8–20.1 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 219.0–405.5 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 4.8–20.1 h × $80 = $384–$1,607/month

**Effort:** M — **Adoption risk:** M – Monday is already underused for content (C-30); the freelancer step is new behaviour.

**Prerequisites:** Monday seats for freelancers; owner other than the technical SEO specialist (C-32).

**COI flag:** **Yes** – Transpera could build this (flagged on HT-O03). · Bias/COI carried from clusters: C-07: COI: 'AI business brain' is Austin's own product idea (KO suggestions, interviewer-sourced).

**Scoring notes:** Impact – hours mid 12.4 h → base 3; +1 C-21/C-22: one person routes all content. Confidence – problem score 4 (primary cluster C-21: High), solution score 3 (2 raiser(s): SJ, HT); averaged; touched-process stated share 33%.

**KPIs:**

- % of briefs submitted through the single intake – baseline 0% – sheet, email and tags (SJ-O01); target 100% (leading)
- % of briefs in by end of week 1 – baseline unknown (SJ-O04); target ≥ 90% (leading)

### O-26 · Spread editing: checklist, trained backup editors, junior writer

**Rank 26 · Strategic · Priority 36** (Impact 4 × Confidence 3 × Ease 3) — **Lens:** People & policy — **Anchor:** Operations capacity & process — **Horizon:** This quarter

**What changes:** Written editing checklist and style guide; content specialists and contracted freelancers trained to self- and peer-edit; named backup for each Tier 1/2 content client; finish the junior writer hire and shift overflow from freelancers.

**Fixes:** C-18 (Unplanned same-day and high-touch client requests break the planned month) [R32] · C-22 (Content delivery hinges on one manager as editor, router and freelancer manager) [R9]

**Pain points:** HT-PP01, HT-PP03, HT-PP07, SJ-PP05, SJ-PP13 (also SJ-B03)

**Source opportunities:** SJ-O06 · HT-O02

**Existing solution idea:** Team wiki / L&D — **Candidate tool:** Hire; Notion style guide. No build.

**Hours saved:** 0.0–7.2 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SJ-O06 0.0–0.0 + HT-O02 0.0–7.2 = 0.0–7.2 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 106.5–181.8 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.0–7.2 h × $80 = $0–$577/month. Possible contractor saving if overflow moves in-house: target −20–30% of ~$14k/month (HT-O02, assumed) – not added to the $ total.

**Effort:** M — **Adoption risk:** M – Depends on the content team finding time to write the guide while at capacity (C-22).

**Prerequisites:** Hire approved; style guide written by the content team.

**COI flag:** No

**Scoring notes:** Impact – hours mid 3.6 h → base 2; +2 Single point of failure on content (C-22); contractors ~$14k/month (pack §7). Confidence – problem score 3 (primary cluster C-22: Medium), solution score 3 (2 raiser(s): SJ, HT); averaged; touched-process stated share 64%.

**KPIs:**

- Share of freelancer pieces edited by someone other than the content team – baseline unknown – two editors today (SJ-O06); target ≥ 50% (leading)
- Contractor spend per month – baseline ~$14k/month (context pack) (HT-O02); target -20–30% (lagging)

### O-27 · AI business brain over client records and SOPs

**Rank 27 · Consider · Priority 36** (Impact 3 × Confidence 4 × Ease 3) — **Lens:** Augment — **Anchor:** Technology, AI & stack — **Horizon:** Needs a build

**What changes:** Once client records and live SOPs exist, connect them (plus transcripts, email and ad change logs) to the existing Slack assistant so staff ask it first and leadership gets a per-client pulse and Tier 1 summary.

**Fixes:** C-04 (Performance drops and tracking breaks surface only in manual checks, often at month-end) [R3] · C-07 (Client knowledge sits in people's heads and personal docs, so briefs and cover suffer) [R14] · C-30 (Monday.com isn't the single home for work: requests bypass it and statuses go stale) [R16] · C-33 (AI use is personal and ungoverned: no policy, shared skills, client context or seats) [R40] · C-35 (SOPs and new systems aren't adopted, so leaders re-explain and mistakes repeat) [R12]

**Pain points:** KO-PP10, KO-PP14, KO-PP15, MP-PP04, MP-PP06, MP-PP17, MP-PP20

**Source opportunities:** MP-O10 · KO-O09

**Existing solution idea:** AI business brain — **Candidate tool:** OpenClaw or Claude Teams over Notion/Monday/Drive; Transpera would build.

**Hours saved:** 1.0–4.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): MP-O10 1.0–4.0 = 1.0–4.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 120.1–216.5 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 1.0–4.0 h × $80 = $80–$320/month

**Effort:** L — **Adoption risk:** M – Near-zero weekly use of the current Slack assistant (KO-O09 baseline); wiki 43% stale (pack §7).

**Prerequisites:** O-04 and O-33 done first; owner per Notion section; AI-data rule.

**COI flag:** **Yes** – Transpera could build this (flagged on MP-O10, KO-O09). "AI business brain" is Austin's own product idea (KO suggestions). · Bias/COI carried from clusters: C-07: COI: 'AI business brain' is Austin's own product idea (KO suggestions, interviewer-sourced).

**Scoring notes:** Impact – hours mid 2.5 h → base 2; +1 Spans C-07, C-30, C-35 – repeated questions to leadership. Confidence – problem score 5 (primary cluster C-30: High), solution score 2 (1 raiser(s): leadership); averaged; touched-process stated share 34%.

**KPIs:**

- Weekly staff using the Slack assistant – baseline About zero (KO-O09); target At least half of staff weekly in 90 days (leading)
- % client calls with transcript summary filed – baseline ~0 (MP-O10); target ≥90% (leading)

### O-28 · Seasonal, trending and competitor content radar

**Rank 28 · Consider · Priority 36** (Impact 3 × Confidence 4 × Ease 3) — **Lens:** Automate — **Anchor:** Growth & sales engine — **Horizon:** Needs a build

**What changes:** Scheduled Google Trends pull and events calendar per client niche, plus a competitor sitemap watch, posting suggested topics 2–3 months before peaks to the strategist.

**Fixes:** C-15 (Seasonal, trending and competitor signals are spotted too late, by hand) [R24]

**Pain points:** KZ-PP19, KZ-PP20, ZC-PP09, ZC-PP15, ZC-PP17

**Source opportunities:** KZ-O08 · ZC-O07 · ZC-O12

**Existing solution idea:** Seasonal & trending content radar — **Candidate tool:** Google Trends + Make.com + Claude; Visualping for competitors. Transpera build likely.

**Hours saved:** 2.2–7.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KZ-O08 1.9–5.5 + ZC-O07 0.3–1.5 = 2.2–7.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 135.8–277.6 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 2.2–7.0 h × $80 = $176–$556/month

**Effort:** M — **Adoption risk:** M – Another feed to read – adoption risk as with reminders (C-30).

**Prerequisites:** Topic lists per client; owner who acts on the feed.

**COI flag:** **Yes** – Transpera could build this (flagged on KZ-O08, ZC-O07, ZC-O12).

**Scoring notes:** Impact – hours mid 4.6 h → base 2; +1 Peaks missed (C-15). Confidence – problem score 4 (primary cluster C-15: High), solution score 3 (2 raiser(s): KZ, ZC); averaged; touched-process stated share 4%.

**KPIs:**

- Seasonal / trend pieces live 4+ weeks before peak – baseline Peaks reached too late (ZC-O07); target ≥ 80% (lagging)
- Major events with content published in time – baseline a major sporting event missed (L443) (KZ-O08); target ≥ 80% of calendar events (lagging)

### O-29 · AI inbox triage and daily brief across Gmail, Slack, Monday

**Rank 29 · Consider · Priority 36** (Impact 3 × Confidence 4 × Ease 3) — **Lens:** Augment — **Anchor:** Technology, AI & stack — **Horizon:** This quarter

**What changes:** AI labels and summarises email and Slack each morning, proposes one-click Monday tasks, and admin notifications move to a digest.

**Fixes:** C-30 (Monday.com isn't the single home for work: requests bypass it and statuses go stale) [R16]

**Pain points:** SB-PP01, SB-PP02, SB-PP05, SB-PP06 (also SB-B03)

**Source opportunities:** SB-O02

**Existing solution idea:** AI business brain (partial) — **Candidate tool:** Gmail/Gemini or Claude with Gmail; Monday.com. Transpera build optional.

**Hours saved:** 6.0–11.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SB-O02 6.0–11.0 = 6.0–11.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 64.5–109.7 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 6.0–11.0 h × $80 = $480–$880/month

**Effort:** M — **Adoption risk:** M – Single raiser; personal workflow change.

**Prerequisites:** AI-data rule; Gmail admin approval.

**COI flag:** **Yes** – Transpera could build this (flagged on SB-O02).

**Scoring notes:** Impact – hours mid 8.5 h → base 3. Confidence – problem score 5 (primary cluster C-30: High), solution score 2 (1 raiser(s): SB); averaged; touched-process stated share 11%.

**KPIs:**

- Minutes per day in inbox – baseline ~60 min (SB-O02); target ≤30 min (lagging)

### O-30 · Client files and logins in company-owned shared locations

**Rank 30 · Quick win · Priority 30** (Impact 3 × Confidence 2 × Ease 5) — **Lens:** Change the process — **Anchor:** Technology, AI & stack — **Horizon:** This month

**What changes:** Standard client folder structure in the shared Drive linked from each Monday client item; move files off personal drives; finish the LastPass migration and link each vault entry from the client item.

**Fixes:** C-34 (Client files and logins sit in personal drives and the CRM, not with the work) [R23]

**Pain points:** SB-PP09, SH-PP08

**Source opportunities:** SH-O08 · SB-O07

**Existing solution idea:** New (fixes "client work files owned by individual staff accounts") — **Candidate tool:** Google Shared Drives, LastPass, Monday.com. No build.

**Hours saved:** 1.2–4.3 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): SH-O08 0.5–1.0 + SB-O07 0.7–3.3 = 1.2–4.3 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 15.4–28.7 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 1.2–4.3 h × $80 = $96–$344/month

**Effort:** S — **Adoption risk:** L – One-off migration; low behaviour change once links sit on the Monday item.

**Prerequisites:** Shared Drive admin; owner for the migration.

**COI flag:** No

**Scoring notes:** Impact – hours mid 2.8 h → base 2; +1 Files held by staff who have left (R23) – continuity risk. Confidence – problem score 3 (primary cluster C-34: Medium), solution score 3 (2 raiser(s): SH, SB); averaged −1 (no stated time in touched processes, ≤2 raisers); touched-process stated share 0%.

**KPIs:**

- % client folders in shared Drive and linked from Monday – baseline unknown (SH-O08); target 100% (leading)
- % of Monday client items with a LastPass link – baseline unknown (SB-O07); target 100% (leading)

### O-31 · Weekly churn-risk signal list per client

**Rank 31 · Strategic · Priority 24** (Impact 4 × Confidence 2 × Ease 3) — **Lens:** Augment — **Anchor:** Client experience & delivery — **Horizon:** This quarter

**What changes:** Turn the signs leadership already reads (contract requests, silence, new marketing manager, falling results) into a weekly per-client risk list from HubSpot, Monday and email; v1 is keyword filters and a 50% conversion-drop flag, v2 adds AI over emails and transcripts. Humans keep the escalation pipeline.

**Fixes:** C-16 (Churn risk is spotted late and account teams report rather than advise) [R31] · C-36 (Escalations, sign-offs, QA and Tier 1 relationships funnel to a few senior people) [R22]

**Pain points:** KO-PP05, KO-PP06, KO-PP21, MP-PP16 (also KO-B02)

**Source opportunities:** KO-O01 · MP-O08

**Existing solution idea:** Churn-risk alerts — **Candidate tool:** HubSpot workflows and dashboards, Gmail filters, Monday.com, OpenClaw; v2 Transpera build.

**Hours saved:** 1.1–8.1 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KO-O01 1.1–8.1 = 1.1–8.1 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 10.8–32.5 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 1.1–8.1 h × $80 = $88–$648/month. Protects retention revenue; no churn $ stated in the interviews, so none added.

**Effort:** M — **Adoption risk:** M – Leadership values reading cases personally (KO-O01) – frame as a helper. Leadership-only evidence.

**Prerequisites:** Indicator list agreed with leadership; HubSpot activity data; named person who acts on the list.

**COI flag:** **Yes** – Transpera could build this (flagged on KO-O01, MP-O08).

**Scoring notes:** Impact – hours mid 4.6 h → base 2; +2 Retention is a stated top goal (KO); ~5 escalations a week land on one person (KO-PP05). Confidence – problem score 4 (primary cluster C-36: High), solution score 2 (1 raiser(s): leadership); averaged −1 (no stated time in touched processes, ≤2 raisers); touched-process stated share 0%.

**KPIs:**

- % churned clients flagged ≥30 days ahead – baseline unknown (MP-O08); target ≥80% (leading)
- Portfolio retention % (company and department) – baseline Unknown – figure not stated (KO-O01); target Hold or improve retention against the target leadership sets (lagging)

### O-32 · Fill the senior performance leadership seat

**Rank 32 · Strategic · Priority 24** (Impact 4 × Confidence 2 × Ease 3) — **Lens:** People & policy — **Anchor:** Leadership & dependency — **Horizon:** This quarter

**What changes:** Hire or appoint an interim senior performance lead and move the operational work leadership is covering back to that seat.

**Fixes:** C-37 (Management layer is thin: paid media lacks a senior lead; new leads lack training) [R41]

**Pain points:** KO-PP04 (also KO-B07)

**Source opportunities:** KO-O14

**Existing solution idea:** New — **Candidate tool:** Hire. No build.

**Hours saved:** 0.0–0.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KO-O14 0.0–0.0 = 0.0–0.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 80.8–110.7 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.0–0.0 h × $80 = $0–$0/month

**Effort:** L — **Adoption risk:** M – Hiring lead time; interim must have authority.

**Prerequisites:** Budget; role scope agreed with the performance team.

**COI flag:** No

**Scoring notes:** Impact – hours mid 0.0 h → base 1; +3 C-37: paid media (61 clients, ~$788K/month budgets) has a vacant senior seat. Confidence – problem score 4 (primary cluster C-37: High), solution score 2 (1 raiser(s): leadership); averaged −1 (no stated time in touched processes, ≤2 raisers); touched-process stated share 0%.

**KPIs:**

- leadership's share of time on performance operations – baseline Unknown (KO-O14); target Under 10% within a quarter of the hire (leading)

### O-33 · SOPs linked from Monday templates; stale pages retired

**Rank 33 · Fill-in · Priority 16** (Impact 2 × Confidence 2 × Ease 4) — **Lens:** Change the process — **Anchor:** Technology, AI & stack — **Horizon:** This quarter

**What changes:** Link the relevant SOP from each Monday task template ("link first" when answering a how-to question); retire Notion pages unused for 12 months; a 90-day pause on new tools while current ones bed in, short role-based training and one AI champion per department.

**Fixes:** C-30 (Monday.com isn't the single home for work: requests bypass it and statuses go stale) [R16] · C-33 (AI use is personal and ungoverned: no policy, shared skills, client context or seats) [R40] · C-35 (SOPs and new systems aren't adopted, so leaders re-explain and mistakes repeat) [R12]

**Pain points:** KO-PP10, KO-PP13, KO-PP14, MP-PP03, MP-PP04

**Source opportunities:** MP-O12 · KO-O10

**Existing solution idea:** Team wiki / L&D — **Candidate tool:** Notion + Monday.com templates. No build.

**Hours saved:** 0.5–3.0 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): MP-O12 0.5–3.0 = 0.5–3.0 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 15.4–28.7 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.5–3.0 h × $80 = $40–$240/month

**Effort:** S — **Adoption risk:** M – SOPs are unread today (C-35, 43% of pages stale); leadership-only evidence for the tool freeze.

**Prerequisites:** Owner per Notion section.

**COI flag:** **Yes** – Transpera could build this (flagged on KO-O10).

**Scoring notes:** Impact – hours mid 1.8 h → base 1; +1 C-35: leaders re-explain, mistakes repeat. Confidence – problem score 4 (primary cluster C-35: High), solution score 2 (1 raiser(s): leadership); averaged −1 (no stated time in touched processes, ≤2 raisers); touched-process stated share 0%.

**KPIs:**

- Repeat how-to questions to founder per month – baseline unknown (MP-O12); target -50% (lagging)
- Tickets updated on time – baseline Unknown (KO-O10); target At least 90% (leading)

### O-34 · Standard creative brief with one consolidated feedback round

**Rank 34 · Fill-in · Priority 16** (Impact 2 × Confidence 2 × Ease 4) — **Lens:** Change the process — **Anchor:** Client experience & delivery — **Horizon:** This quarter

**What changes:** Standard design-partner brief with must-haves, examples and an acceptance checklist; one consolidated feedback round; trial AI creative (Canva) for simple variants.

**Fixes:** C-29 (Creative and landing pages are outsourced, slow and hard to brief) [R38]

**Pain points:** MC-PP15 (also MC-B04)

**Source opportunities:** MC-O13

**Existing solution idea:** AI-assisted creative — **Candidate tool:** Canva AI; brief template. No build.

**Hours saved:** 0.3–2.2 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): MC-O13 0.3–2.2 = 0.3–2.2 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 1.7–5.4 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.3–2.2 h × $80 = $24–$172/month

**Effort:** S — **Adoption risk:** M – Single raiser; outsourced partner must accept the format.

**Prerequisites:** Template written by a specialist.

**COI flag:** No

**Scoring notes:** Impact – hours mid 1.2 h → base 1; +1 Slow outsourced creative delays launches (C-29). Confidence – problem score 4 (primary cluster C-29: High), solution score 2 (1 raiser(s): MC); averaged −1 (no stated time in touched processes, ≤2 raisers); touched-process stated share 0%.

**KPIs:**

- Creative revision rounds per design-partner brief – baseline Several (MC-O13); target ≤1 (lagging)

### O-35 · Joint monthly tech-priority check between strategist and tech team

**Rank 35 · Fill-in · Priority 16** (Impact 2 × Confidence 2 × Ease 4) — **Lens:** Change the process — **Anchor:** Client experience & delivery — **Horizon:** This quarter

**What changes:** Strategist and technical SEO agree the month's tasks by impact before work starts; tech tickets due by the 25th so reports show them done.

**Fixes:** C-26 (Strategy and technical SEO run as separate queues, so big technical work slips) [R35]

**Pain points:** KZ-PP11, KZ-PP12 (also KZ-B04)

**Source opportunities:** KZ-O06

**Existing solution idea:** New — **Candidate tool:** Monday.com. No build.

**Hours saved:** 0.5–1.5 h/month (assumed). Per person, the largest saving among their merged sources (overlapping ideas from one person are not added): KZ-O06 0.5–1.5 = 0.5–1.5 h/month. High ends of capped people scaled by their 160 h cap ratio. Process hours available: 104.5–174.7 h. Certainty: assumed (reduction percentages are assumptions).

**$ saved:** 0.5–1.5 h × $80 = $40–$118/month

**Effort:** S — **Adoption risk:** M – Two queues with different managers (X-04 reporting lines unclear).

**Prerequisites:** None beyond a 30-minute monthly slot.

**COI flag:** No

**Scoring notes:** Impact – hours mid 1.0 h → base 1; +1 Big technical work slips for months (C-26). Confidence – problem score 4 (primary cluster C-26: High), solution score 2 (1 raiser(s): KZ); averaged −1 (no stated time in touched processes, ≤2 raisers); touched-process stated share 0%.

**KPIs:**

- % of tech tasks done by report date – baseline unknown – sometimes still in progress on the 5th (L333) (KZ-O06); target ≥ 90% (leading)

### 2.2 Grouped views

**Quick win (18)**: O-01 Restore the pacing data feed and cover every live channel (P125, COI) · O-02 AI data rule, company Claude seats and shared skills library (P125, COI) · O-03 AI brief drafts from the Master SEO Document (P100, COI) · O-04 One per-client record fed by call summaries (P100, COI) · O-05 Reports and review decks: auto-filled data, AI-drafted narrative (P100, COI) · O-06 All internal requests via Monday forms; Monday notifies, not people (P100, COI) · O-07 Automated live-link checks with publisher replacement claims (P80, COI) · O-08 Sales-to-delivery gate: handover fields, owner, access checklist (P80, COI) · O-09 Implementer self-QA checklists for page and ad builds (P80, COI) · O-10 Switch on native platform alert rules and scripts now (P75, COI) · O-15 Enter budgets once, log every change, written overspend policy (P64) · O-16 Own and verify automations: register, backup admin, reconciliation (P60, COI) · O-17 Cap concurrent onboardings per manager; protect BAU time (P60) · O-21 Delegation and triage rules for escalations and sign-offs (P48) · O-22 Sales discipline: calculator, margin check, speed-to-lead (P48, COI) · O-23 "Problem plus recommendation" rule in reports and calls (P48) · O-24 Client approval SLAs with logged dates and reminders (P48, COI) · O-30 Client files and logins in company-owned shared locations (P30)

**Strategic (11)**: O-11 Pacing tracker reads budgets and spend, flags gaps (P75, COI) · O-12 Cross-account performance monitor with draft diagnosis (paid and SEO) (P75, COI) · O-13 AI per-client summary for reports, calls and data questions (P75, COI) · O-14 AI-prefilled onboarding audit and Master SEO Document (P75, COI) · O-18 One link record: standard order template, auto-sync, invoice run (P60, COI) · O-19 Effort model: hours per client, load triggers, rebalanced books (P60) · O-20 Widen link supply: shared vetting skill, client matching, mentions (P60, COI) · O-25 Content intake on Monday with brief standard and slots (P48, COI) · O-26 Spread editing: checklist, trained backup editors, junior writer (P36) · O-31 Weekly churn-risk signal list per client (P24, COI) · O-32 Fill the senior performance leadership seat (P24)

**Consider (3)**: O-27 AI business brain over client records and SOPs (P36, COI) · O-28 Seasonal, trending and competitor content radar (P36, COI) · O-29 AI inbox triage and daily brief across Gmail, Slack, Monday (P36, COI)

**Fill-in (3)**: O-33 SOPs linked from Monday templates; stale pages retired (P16, COI) · O-34 Standard creative brief with one consolidated feedback round (P16) · O-35 Joint monthly tech-priority check between strategist and tech team (P16)

**Deprioritise (0)**: none

**COI summary.** 25 of 35 merged opportunities carry a COI flag (at least one source opportunity flagged as something Transpera would build). Most of the in-stack Quick wins carry the flag only because one source suggested a build – O-01, O-02, O-03, O-04, O-06, O-08, O-09, O-10, O-16 and O-24 can all be done without Transpera. The flag matters most for the six "Needs a build" items and for O-07 / O-18 / O-27, where Austin personally offered the link monitor/CRM and the AI business brain is his own idea. The 16 existing solution ideas in the pack predate the interviews – the verdict table below checks each against interview evidence rather than assuming they are right.

**By horizon**

| Horizon | Opportunities |
| --- | --- |
| This month | O-01 Restore the pacing data feed and cover every live channel, O-02 AI data rule, company Claude seats and shared skills library, O-03 AI brief drafts from the Master SEO Document, O-04 One per-client record fed by call summaries, O-06 All internal requests via Monday forms; Monday notifies, not people, O-08 Sales-to-delivery gate: handover fields, owner, access checklist, O-09 Implementer self-QA checklists for page and ad builds, O-10 Switch on native platform alert rules and scripts now, O-15 Enter budgets once, log every change, written overspend policy, O-16 Own and verify automations: register, backup admin, reconciliation, O-17 Cap concurrent onboardings per manager; protect BAU time, O-21 Delegation and triage rules for escalations and sign-offs, O-22 Sales discipline: calculator, margin check, speed-to-lead, O-23 "Problem plus recommendation" rule in reports and calls, O-24 Client approval SLAs with logged dates and reminders, O-30 Client files and logins in company-owned shared locations |
| This quarter | O-05 Reports and review decks: auto-filled data, AI-drafted narrative, O-07 Automated live-link checks with publisher replacement claims, O-18 One link record: standard order template, auto-sync, invoice run, O-19 Effort model: hours per client, load triggers, rebalanced books, O-20 Widen link supply: shared vetting skill, client matching, mentions, O-25 Content intake on Monday with brief standard and slots, O-26 Spread editing: checklist, trained backup editors, junior writer, O-29 AI inbox triage and daily brief across Gmail, Slack, Monday, O-31 Weekly churn-risk signal list per client, O-32 Fill the senior performance leadership seat, O-33 SOPs linked from Monday templates; stale pages retired, O-34 Standard creative brief with one consolidated feedback round, O-35 Joint monthly tech-priority check between strategist and tech team |
| Needs a build | O-11 Pacing tracker reads budgets and spend, flags gaps, O-12 Cross-account performance monitor with draft diagnosis (paid and SEO), O-13 AI per-client summary for reports, calls and data questions, O-14 AI-prefilled onboarding audit and Master SEO Document, O-27 AI business brain over client records and SOPs, O-28 Seasonal, trending and competitor content radar |

This month = Quick win with effort S and no build. This quarter = everything else that can be done in-stack. Needs a build = the candidate tool names a Transpera build.

**By audit anchor and lens**

| Anchor | Eliminate | Change the process | People & policy | Augment | Automate |
| --- | --- | --- | --- | --- | --- |
| Client experience & delivery | – | O-04, O-08, O-09, O-24, O-34, O-35 | O-23 | O-14, O-31 | – |
| Growth & sales engine | – | O-22 | – | – | O-28 |
| Leadership & dependency | – | – | O-21, O-32 | – | – |
| Operations capacity & process | – | O-06, O-18, O-19, O-25 | O-02, O-17, O-26 | O-03, O-05, O-13, O-20 | O-12 |
| Performance visibility & margin | – | O-01, O-10, O-15 | – | – | O-07, O-11 |
| Technology, AI & stack | – | O-30, O-33 | O-16 | O-27, O-29 | – |

Eliminate appears only inside O-06 (stopping the daily agenda message and status reminders, MC-O05) – it was merged into the Monday request opportunity because it fixes the same clusters. Automation was preferred over augmentation where adoption has already failed: pacing entry (MP-PP01), link re-checks (stopped after April, X-20), call notes (transcripts unused, X-21), and status chasing (reminders ignored, R16).

**Existing solution ideas (pack §6) – verdict**

| Existing idea | Verdict | Merged opportunity | Why |
| --- | --- | --- | --- |
| Pacing tracker & adjustment engine | Confirmed | O-01, O-15, O-11 | 4 staff + leadership; start with the feed and single entry, then build |
| Proactive PPC anomaly monitor | Confirmed | O-10, O-12 | 8 proposers; native rules first |
| Client-call prep summaries | Confirmed | O-13 | 4 performance staff; prep ~1h15 per call |
| QBR / review deck generator | Confirmed | O-05 | 5 proposers; builds on an existing AI workflow |
| Transcripts → per-client action runsheet | Confirmed | O-04 | Capture exists, use doesn't (X-21) |
| Brief & proposal generator | Partly – briefs confirmed, proposals not | O-03, O-22 | Brief drafts by 3 SEO staff; proposal generation only via one prospect-deck idea (KZ-O12) |
| 1-click audit (read-only access + AI audit) | Partly | O-14 | Supported as an onboarding accelerator; the lead-magnet version (SB-O09) addresses no cluster |
| Link-building CRM with live-link monitoring and invoice follow-up | Partly – monitoring confirmed, CRM not yet | O-07, O-18 | Live-link checks strongly supported; a sheet-first single record before any CRM |
| Seasonal & trending content radar | Confirmed (narrow) | O-28 | 2 SEO staff; Consider tag |
| Sales wiki / spend calculator | Confirmed (leadership-led) | O-22 | Mostly leadership evidence; sales not interviewed |
| Churn-risk alerts | Supported by leadership only | O-31 | No staff proposer; confidence 2 |
| AI business brain | Not supported as a first step | O-27 | Austin's own idea; one leadership proposer; depends on client records and SOP adoption first |
| Team wiki / L&D | Reframed | O-33, O-02 | Wiki exists; the problem is adoption and currency (X-15) |
| Client approval portal | Not supported as a first step | O-24 | Single proposer (LS-O05); SLAs and logged dates first |
| Unlinked brand-mention outreach | Weak | O-20 | Single proposer (ZC-O09); folded into link supply |
| AI-assisted creative | Weak | O-34, O-09 | Single proposer (MC-O13); Fill-in |

### 2.3 Coverage check

**Clusters with severity ≥3 that no opportunity addresses:** none. All 39 Stage 1 clusters are addressed by at least one merged opportunity.

**Opportunities that address no cluster:** none among the merged set. Two source opportunities fix no Stage 1 cluster on their own and were kept only as extensions: SB-O09 (lead-magnet audit) inside O-14 – justified because it reuses the same engine and serves C-39 growth; ZC-O11 (draft 6-month reviews) inside O-05 – it fixes process ZC-P11, which sits under C-06.

**Thin coverage (one opportunity only):** C-08 → O-08, C-13 → O-09, C-25 → O-07, C-26 → O-35, C-34 → O-30. C-25 (paid links vanish, severity 5) rests on one opportunity – keep it on the shortlist.

**Before you rely on these numbers:** savings are assumed percentages of mostly assumed process hours; leadership team-wide estimates were used only as cross-checks where staff gave their own (O-11, O-12, O-18); senior hours freed by rebalancing books are shown as redistributed, not saved (O-19). O-07's 5–10 h rests on one leadership estimate for re-keying links (MP-O05) – live re-checks currently take 0 h because nobody does them, so its value is mainly the avoided link loss. Hours saved are not additive across opportunities.