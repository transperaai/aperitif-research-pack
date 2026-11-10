# Independent audit – Aperitif Distilled Solutions (DS-01..DS-21)

> **Historical record (written before 10 Nov 2026).** Cost-of-inactivity (COI) figures, the churn basis (\$5K retainer, 3%/yr, ≥61 clients) and "cost TBC" statuses quoted here are superseded. Current value: [VALUE-BY-BUNDLE.md](../../VALUE-BY-BUNDLE.md); current prices: each solution file.

Audited 9 Nov 2026 (read-only). Sources: distilled_solutions_page.txt, ledger outputs, painpoints/rows.json, Problems and Opportunities exports, stage1/stage2 merge files, 14 transcripts, context pack. Scratch scripts are in /home/claude/ledger/audit/_work/.

## Verdict (10 lines)

1. **Safe to deliver after the six MUST FIX items are fixed. Do not deliver as it stands.** The evidence base is sound. Every quote checks out (66 of 66 verbatim, see below), and the cost-of-inactivity (COI) arithmetic is right in 15 of 17 quantified solutions.
2. The risk is not fabrication. It is overreach and framing: in a few places the page states more than its sources support.
3. Risk 1 – Coverage: the problem raised most widely by staff ("Managers at capacity", P-21, 7 staff + 2 leadership) is shown as fixed by a deck generator. Its real fixes (O-17, O-19, O-32) were all dropped.
4. Risk 2 – A disputed fact stated as settled: DS-01 says LinkedIn is "the channel behind the $10K overspend". Stage 1 contradiction X-10 says not to state that until Joe confirms it, and the Bïrch rejection rests on it.
5. Risk 3 – Evidence that isn't staff evidence: MP-PP17 is Austin's own words (MP transcript L023). SD-PP19 and TG-PP09 are AI-"detected", and their quotes do not say what the page claims.
6. Risk 4 – Money figures: the DS-15 total is mis-added and counts churn twice. DS-14's bold "~$110K revenue lost to churn today" is an unconfirmed assumption, yet it is the largest recoverable figure on the page.
7. Risk 5 – Order of work: 8 "Decided" solutions depend on DS-02's AI-data rule. DS-02 is still "Drafting", its problem (P-40) is only "Solve later", and whether the rule is even in scope is an open question.
8. Quote fidelity: 66/66 PP-cited quotes match their pain point, 66/66 appear in the right transcript, and 64/66 name the speaker's role correctly. The 2 errors both call the SEO Director "an SEO manager".
9. Counts: **6 MUST FIX, 17 SHOULD FIX, 16 NOTE.** Items the ledger builder had already flagged are marked [also in gaps file]. Most findings are new.
10. Expect about half a day to fix. Most fixes are wording, relabelling or one-line recalculations, not new research.

---

## MUST FIX (wrong, or would mislead Joe)

**M1. P-21 "Managers at capacity" is presented as solved when it isn't** – DS-05 (also DS-01, DS-06 "also helps"); ledger P-21.
- What's wrong:
  - P-21 is a Solve-now problem. Stage 1 calls it the "widest raise" (C-17: 7 staff + 2 leadership; 15 pain points).
  - DS-05 lists it under "Problems it fixes" with no "partly" qualifier. The only evidence is one pain point: LS-PP02, the SEO Director's time on small-client 6-month reviews.
  - Every opportunity aimed at the cause of the capacity problem was dropped: O-17 (cap on onboardings), O-19 (effort model and rebalanced books) and O-32 (senior performance seat).
  - The ledger then marks all 15 P-21 pain points "addressed by DS-05". These include "new starter takes ~90 days to ramp" (KO-PP09), "pushing for performance risks attrition" (MP-PP19), "SQR hygiene not done" (SD-PP08) and "Merchant Center unchecked ~3 weeks" (MC-PP18). That inflates the "192 addressed" headline.
- Evidence: ds_map.json lists P-21 as fixed by DS-05. The opportunities export has Drop on O-17, O-19 and O-32. Stage 1 C-17.
- Fix: Move P-21 to "Also helps (partly)" in DS-05, add one line saying capacity itself is not solved in this proposal, and recount the ledger pain points.

**M2. The $10K overspend is attributed to LinkedIn as fact** – DS-01 build-vs-buy research; DS-10 COI.
- What's wrong:
  - DS-01 says Bïrch "does not list LinkedIn – the channel behind the $10K overspend", and rules Bïrch out on that basis.
  - Stage 1 contradiction X-10 says the transcript does not tie the $10K to LinkedIn: "Don't quote as one incident until confirmed". MP-PP01, the $10K quote, is about a stale budget figure on the sheet (L377–L378). MP-PP02, the LinkedIn remark (L573–L577), is a separate comment.
  - DS-01's own COI row wording ("untracked/mis-paced channel") is hedged correctly, but the research section is not.
- Fix: Change the line to "LinkedIn has no pacing today (MP-PP02); confirm with Joe whether the $10K incident was LinkedIn". The Bïrch conclusion still stands on the "every channel" requirement alone.

**M3. The auditor's own words and AI-inferred items are cited as interview evidence**
- MP-PP17 (DS-15, "account data isn't pre-synthesised"): the PP's Ref is "L023, Austin". These are Austin's opening remarks to Joe, not something leadership said.
- SD-PP19 (DS-10 and its KPI baseline, "the pacing bot has no visible owner or documentation"): Source = detected. The quote is only "Tina gives us updates Monday, Wednesday, Friday" and says nothing about ownership.
- TG-PP09 (DS-11 and its COI, "four tools undocumented and run by one person"): Source = detected. The quote is "I'm not really sure if these are really working well". The "four tools", "undocumented" and "one person" details are inferences.
- [The builder flagged these as "not labelled" but did not check that the content isn't supported.]
- Fix: Drop MP-PP17 from the evidence, or label it "Austin's observation". Reword the SD-PP19 and TG-PP09 points as "inferred (not stated)", or cite stated evidence instead.

**M4. The DS-15 COI is mis-added and counts churn twice** – DS-15 COI and Basis.
- What's wrong:
  - The member figures sum to $44K–$134K, not "$48K–$135K". [also in gaps file]
  - Not previously flagged: the DS-14 figure already includes prevented churn ($23K–$52K incl. churn), yet the sentence adds "plus churn exposure" on top.
- Fix: "~$44K–$134K a year combined (includes DS-14 prevented churn; overlapping, indicative)", with "plus churn exposure" removed.

**M5. Eight "Decided" solutions depend on DS-02, which is undecided** – DS-02 and the Progress table.
- What's wrong:
  - DS-03, -04, -05, -06, -08, -09, -14 and -15 each list "the AI-data rule (DS-02)" as a prerequisite. DS-02 itself says "DS-03 and DS-04 can't run safely without the rule and shared seats".
  - DS-02 is "Drafting". Its first open question is whether the AI rule and seats are even part of DS-02 or "separate decisions for Joe". Its problem P-40 is "Solve later".
  - The Progress table gives no sign of this dependency.
- Fix: Decide where the AI-data rule and seats sit before delivery, and add "Depends on DS-02 (AI-data rule)" to the status of those 8 rows. Consider re-calling P-40 as Solve now. [The builder flagged DS-02 drafting and the P-40 call, but not the dependency.]

**M6. DS-14 states an unconfirmed churn assumption as current fact, as the page's largest number** – DS-14 COI table and Decided.
- What's wrong:
  - The bold row "Revenue lost to churn today – ~$110K a year", with "$22K–$44K recoverable", is the largest recoverable figure on the page. It rests entirely on Austin's assumption ($5K retainer, 3%/yr, 61 = paid-media Google Ads clients only). Stage 2 O-31 says "no churn stated in the interviews, so none added".
  - 3%/yr sits oddly against the founder's 98% portfolio retention target in the context pack (≈2%/yr).
  - The page itself says the figure could be about 12× larger.
  - The Decided list says both "to confirm with Joe" and "not confirmed with Joe".
- Fix: Relabel the row "Assumed churn (Austin, to confirm with Joe)", delete the duplicate Decided line, and put the 3%/yr basis to Joe as a question. [Builder flagged the basis but not the "today" framing or the retention-target clash.]

---

## SHOULD FIX (inconsistent or unclear)

**S1. The SEO Director is labelled "an SEO manager"** – DS-02 (LS-PP13) and DS-03 (LS-PP03).
- The speaker is Laura, the SEO Director (verified in LS transcript L026 and L080).
- DS-05 and DS-14 call the same person "SEO director". Joe will know who said it.
- Fix: Use "the SEO director".

**S2. DS-05 says P-18 (sales over-commits) is "leadership only"** – DS-05.
- Stage 1 C-38 = 1 staff + 1 leadership. DS-08 cites the staff evidence (WS-PP07) under the same problem.
- Fix: "leadership + 1 staff (performance director)".

**S3. The same problem gets different raise counts** – DS-04 vs DS-08 (P-27).
- DS-04 says "3 staff"; DS-08 says "4 staff + leadership". Stage 1 C-08 = 3 staff (KO-PP01 is interviewer-raised).
- P-05 ("4 staff" vs 5), P-20 ("2 staff" vs 4 + 1) and P-38 ("leadership + 1 staff" vs 2 staff + 1) are also off. [also in gaps file]
- Fix: Use the Stage 1 counts everywhere.

**S4. DS-02 says "9 staff + 1 leadership"** – P-40.
- One of the 9 is WS-PP13, which is "detected". Interviewee-sourced pain points give 8 staff + 1 leadership.
- Fix: "8 staff + 1 leadership (plus one inferred)", or footnote it.

**S5. DS-04 misreads KO-PP05.**
- DS-04 uses "probably five times a week" as client questions leads could answer themselves. In the transcript (KO L123–L124) it is Julia's answer to "how often do you get churn indicators". DS-13 uses it correctly.
- Fix: Cite KO-PP21 (client-communication questions) in DS-04 instead.

**S6. DS-21 misreads SD-PP12.**
- DS-21 says "ad-hoc launches wait ≥ 1 week for creatives". The quote says a week is needed "provided the creatives are being sent to us on time". The week is build and approval time, and the creatives are client-supplied. SD-PP12 is linked to P-30 (client approvals, parked), not P-38.
- Fix: Drop SD-PP12 and the matching KPI from DS-21, or reword it.

**S7. DS-07 contradicts itself on today's link-check time.**
- The COI says staff spend "11–36 h/month on link QA and live checks today" and recover 5–10 h. The same section's KPI says 0% of links are verified, and Stage 2 notes that "manual checking stopped after April" (X-20).
- The 10.8–35.7 h comes from one person (TG-P03), with 0% of it stated.
- Also, the "$80–$130 per link" is attributed to KZ-PP10 but comes from the context pack, which Stage 1 marks "unit cost not stated in interviews".
- Fix: Reword the row as publication-time checks only, and cite the order sheets for the price.

**S8. DS-05 can recover 100% of the review-deck process time.**
- The basis caps the deck saving "at the process total" (23.2 h high), yet managers still review and edit, and "work completed / planned" stays human-supplied (Decided).
- Fix: Cap the saving at about 50–70% of the process, or label the high end as a ceiling.

**S9. DS-03 under-counts the folded-in O-25.**
- The page says O-25's 4.8–20.1 h is "already counted" because it "overlaps the briefing figure". But O-25's main saving (SJ-O01, 3.8–16.1 h) is the Content Manager copying briefs into freelancer sheets. Stage 2 maps that to Content writing & editing and Internal task management, not to SEO managers' briefing.
- The stale "task-creation part" wording is also still there [also in gaps file].
- Fix: Add the non-overlapping O-25 hours, or state why they are excluded.

**S10. DS-03 decision text conflicts with itself.**
- "Your decision: automation only" and "How it works: each month the automation reads…" conflict with "Decided: Recommended option: a Claude skill… also present a fully automated option as the upgrade path".
- Fix: Pick one headline and make the How-it-works section match.

**S11. DS-06 Future state conflicts with Decided.**
- Future state #2 says "the sweeper proposes it, a person confirms it". Decided says Slack requests become tasks "there and then", automatically, with confirmation only for email. Future state #1 also leaves out email.
- Fix: Align the future state with the decision.

**S12. DS-13 vs DS-14 alert routing.**
- DS-14 sends every alert "at every risk level" to Julia. DS-13's aim and KPI are to move escalations off the Head of Client Services (≥50% handled by leads). DS-14's own future state #4 says leadership steps in "only on high-risk alerts".
- Fix: Route low and medium alerts to the lead only, or explain why Julia sees all of them.

**S13. Stale "later / not decided" text.**
- DS-07 still says O-18 is "not decided yet" [also in gaps file].
- Not previously flagged: DS-02 says the link to the AI brain is "to be discussed later" and asks "how does it connect to the AI brain… (Later.)", but DS-15 has since put DS-02 under the Brain umbrella as "queryable smart SOPs". DS-04 says the company-wide part "stays for a later solution", which is now DS-15.
- Fix: Update all three.

**S14. DS-14 Decided contains an open question** ("Personality profiles: client contacts only, or also prospects?"). [also in gaps file]
- Fix: Move it to Open questions.

**S15. DS-19 calls Aircall's receptionist "built-in".**
- The Progress table and Decided say "Aircall built-in… configured, not built".
- Aircall's AU page sells the AI Receptionist as a separate minute bundle: A$370/month for 1,000 minutes, A$1,190 for 3,500, from A$0.18/min (aircall.io/en-au/products/ai/ai-receptionist, checked 9 Nov 2026).
- Fix: Say "Aircall AI Receptionist add-on, from ~A$370/month" and put that in OpEx.

**S16. DS-21 price claims are shaky.**
- AdCreative.ai is quoted "from about $29–$39/month". Current Starter is $39/month, or $20/month billed annually, and covers 1 brand only. Agency use across many clients needs Professional ($249/month) or higher (tryatria pricing summary, Nov 2026). No $29 tier was found.
- The OpEx line "roughly $29–$39/month per tool" is then applied to every tool. Higgsfield is $19–$129.
- Prices are USD while the page costs in AUD.
- Fix: Quote multi-brand tiers, mark currency, and keep the "verify" label.

**S17. Interviewer-raised items cited without a label: MP-PP20, MP-PP06, KO-PP01.**
- The words are leadership's, but Austin raised the topic. Two other items carry a "Bias note"; these three don't. [also in gaps file]
- Fix: Add "(prompted by you)".

---

## NOTE (minor)

- N1. DS-01: "7 staff, the widest raise in paid media". Two of the 7 (LS, ZC) are SEO staff, and C-17 is equally wide. Say "7 staff across paid and SEO".
- N2. DS-01: "~$1.2M/month (Google ~$788K + Meta ~$422K)" comes from the context pack. Stage 1 marks it "not evidenced" in interviews. Cite the source. [also in gaps file]
- N3. DS-01: "combined ~20–50 h with overlap removed". The five opportunities sum to 30.5–88.1 h, and no method is shown. Add one line of method.
- N4. DS-01: Bïrch "checks roughly every 15 minutes" is not on Bïrch's pricing page. The platform list (Meta, Google, Snapchat, TikTok; no LinkedIn) and Pro at $99/month are confirmed (bir.ch/pricing.md). Label the 15-minute figure as from reviews.
- N5. DS-05 WS-PP05: the quote stops before "…even though I started finding ways to already use AI for it and it saves me a lot of time" (WS L773). Fair use, since the page notes the existing workflow, but it reads slightly more negative than said.
- N6. DS-05: future state #5 says "monthly reporting unchanged", but Decided moves the KZ multi-market monthly deck into the generator. Its time (KZ-O10) is also left out of the COI.
- N7. DS-06: SB-O02 and O-29 are listed as two opportunities with the same 6–11 h. O-29's only source is SB-O02.
- N8. DS-06: "(SB-PP02, stated)" and "(SB-PP03, stated)". Both PPs are "partly stated".
- N9. DS-07: document evidence of a much higher fault rate (32% of ~1,016 links checked Jan–Apr; ~1,500 May–Oct unchecked) was dropped pending X-06. The ~10 links/month COI may be understated. Say so in Assumptions.
- N10. DS-09: "cut strategy from ~3 days to ~75–90 min (context pack)". The context pack gives only 75–90 min. "~3 days" comes from Stage 1 (S-strengths, "to about an hour"). Fix the citation.
- N11. DS-16: KZ-PP19 is described as "on a Tier 1 client". The client is Disney, which is not on the context-pack tier lists, and no tier is stated in the transcript.
- N12. DS-18: "Outsourced pages cost ~$1,500 each, which is a barrier". Wendlley gave the $1,500 (WS L617), but "too expensive" was Austin's line (L615). KO-PP25 supports "reluctant to pay".
- N13. DS-04 KPI baseline "60–75 min per 30-min call (stated)" is one person (Shrishti). DM gave ~30 min (X-24).
- N14. Rounding: hours are shown rounded while dollars use unrounded hours, e.g. DS-08 "2–10 h ($180–$830)", DS-14 "1–8 h ($90–$650)", DS-17 "1–4 h ($100–$340)". The arithmetic is fine; show one decimal or round the dollars.
- N15. DS-20: the Progress table says "O-14 related (KO-PP22)", but KO-PP22 sits in O-08. [also in gaps file]
- N16. I disagree with the gaps file on DS-21 "O-34 trial part". Stage 2 O-34's change text includes "trial AI creative (Canva) for simple variants", so the citation is legitimate. It only needs "(O-34 was otherwise dropped)".

---

## Checks performed (method and coverage)

1. **Quote fidelity.**
   - All 67 italic quotes on the page were extracted; 66 carry a PP ID and 1 is Austin's own note.
   - All 66 were checked against rows.json and the full transcripts. The text was normalised for punctuation and ellipses, and quotes split across consecutive lines were allowed.
   - Results: 66/66 match the PP quote; 66/66 found in the correct transcript. One (WS-PP05) is spliced across Austin's one-word interjection.
   - The speaker was verified from diariser labels for each quote. 64/66 roles are right; the 2 wrong ones are S1.
   - Detail: quote_checks.csv.
2. **Attribution.** Every PP cited on the page (194 citations) was checked against its problem links, and every interviewer or detected source was reviewed. Findings: M3, S5, S6, S17.
3. **Numbers.**
   - Recomputed every COI row: hours × $80, ×12, ranges and sums.
   - Process rows match stage2-part-b.json in all cases (DS-01 63.4–140.1 h, DS-04 104.7–187.8 h, etc.).
   - Opportunity hours match the Opportunities export.
   - Errors: DS-15 sum (M4); DS-05/DS-03/DS-07 basis issues (S7–S9).
   - There is no portfolio-wide total on the page. If one is added, exclude DS-15 and remove overlaps: DS-11/DS-12 share one process row, DS-01 (O-12) and DS-04 (O-13) draw on the same performance managers, and DS-03 and DS-06 both create Monday tasks.
4. **Coverage.**
   - All 29 Solve-now problems were checked against ds_map. 27 are "fixed", but P-21 is hollow (M1), and P-44/P-48 (culture) are "fixed" by a playbook or umbrella with no pain-point evidence.
   - P-25 and P-47 are only partly addressed [gaps file].
   - All 35 merged opportunities and 21 earlier ideas have a DS or a recorded call, except those already listed in the gaps file (O-23 remainder, O-33, EI-05/10/14/18).
   - Each of DS-01..DS-18 links to a problem. DS-19 and DS-20 are labelled as Austin's additions.
5. **Consistency.** The ledger matches the DB calls exactly: 0 differences across 48 problems and 35 opportunities. Page-internal contradictions: S10–S14.
6. **Vendor claims.** Four were spot-checked on the web:
   - Bïrch: confirmed.
   - Higgsfield: Starter $19 and Ultra $129 confirmed; the 15-second Marketing Studio cap was not confirmed.
   - AdCreative.ai: partly wrong (S16).
   - Aircall: misleading (S15).
7. **Overreach.** Every page raise count was compared with the PP-derived and Stage 1 counts (S2–S4, N1), and every "stated" label with PP certainty (N8).
