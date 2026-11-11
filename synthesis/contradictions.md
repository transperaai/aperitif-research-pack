# Contradictions (X) – Stage 1

Where two sources disagree. Generated from [stage1-part-b.json](stage1-part-b.json). Do not state either claim as fact without checking the explanation.

## <a id="x-01"></a>X-01 Supermetrics status

- **A** ([SD-PP01](../pain-points/README.md#sd-pp01)): "the sheets have broken because we no longer have a Supermetric subscription" (\~22:57, L193)
- **B** ([MC-PP06](../pain-points/README.md#mc-pp06) / MC follow-up): Still connected but 'breaking down a lot'; not being renewed (\~20:25, L198). WS follow-up (4 Nov Meta pacing call): subscription not cancelled, connection keeps dropping.
- **Explanation:** Subscription is in run-off or on a reduced plan: the connector still exists but fails, and there is no plan to renew. Context pack's 'lapsed' is too strong.
- **Status:** Needs Aperitif (billing record)

## <a id="x-02"></a>X-02 Google pacing – manual vs scripted

- **A** (MP-str03 / MP follow-up): Joe: Google Ads and Meta pacing 'built' / 'sorted' (\~44:15, L573); KO-str08 Google Ads script flags no-conversion accounts.
- **B** ([SD-PP15](../pain-points/README.md#sd-pp15)): Claude connects to Meta but not Google Ads, so Google stays manual (\~15:50, L131); SH-PP02 sheets need manual IDs and don't pull correctly.
- **Explanation:** A Google pacing sheet exists, but its feed and all adjustments are manual; the script covers one failure type (no conversions), not pacing.
- **Status:** Needs data (open the Google pacing sheet; check its feed)

## <a id="x-03"></a>X-03 Tina pacing cadence

- **A** ([SD-PP19](../pain-points/README.md#sd-pp19)): Tina updates Monday, Wednesday, Friday (\~27:21, L260); SD-X03 also says 'twice a week'.
- **B** (DM-X01 / SH-X02 / MC-X02): Diya checks performance fortnightly (weekly for new clients); Austin said Tina posts daily (SH L193, MC L407, DM L304).
- **Explanation:** Tina posts budget pacing M/W/F. Diya's fortnightly cadence is her manual performance check, a different task. 'Daily' was the interviewer's assumption and wasn't corrected.
- **Status:** Resolved (from evidence) – confirm in Slack

## <a id="x-04"></a>X-04 Who Tonie and Zach report to

- **A** (Context pack §2): Both report to Sid.
- **B** (KZ follow-up (L089, L094); TG follow-up; SB follow-up): Karl says both report to him; all Tonie's approvals go to Karl; Sid describes no management duties.
- **Explanation:** Org chart is out of date; both work to Karl in practice.
- **Status:** Needs Aperitif (confirm the chart)

## <a id="x-05"></a>X-05 Link volume per month

- **A** ([KO-PP16](../pain-points/README.md#ko-pp16)): Julia: about 200 links a month (L368).
- **B** ([LS-PP12](../pain-points/README.md#ls-pp12) / TG-str09 / context pack): Laura: 250 → 312 a month (L090); Tonie: 300–340 a month (L084); pack \~300 (2,800 Jan–Oct).
- **Explanation:** Volume has grown; 200 is an older or rough leadership figure. 312 and 300–340 are consistent with the order book.
- **Status:** Needs data (order book by month)

## <a id="x-06"></a>X-06 Link fault rate

- **A** (Context pack (problem #3)): 32% fault rate Jan–Apr; checking stopped after April.
- **B** ([KZ-PP10](../pain-points/README.md#kz-pp10)): \~100 dead links in \~10 months (\~3% of \~3,000) (\~54:38, L546).
- **Explanation:** Different measures: 32% is likely faults found at live-check (not live, wrong domain, wrong anchor) when checks ran; \~100 is links later removed.
- **Status:** Needs data (Austin's Jan–Apr analysis definitions)

## <a id="x-07"></a>X-07 Hayley's client count

- **A** (Context pack §2): 17 content clients.
- **B** (HT-X01): About 7 this month (L147).
- **Explanation:** 17 is likely all clients she has written for this year; \~7 is the active monthly book.
- **Status:** Needs Aperitif

## <a id="x-08"></a>X-08 easyAML ownership

- **A** (Context pack §4): Google Ads manager DM.
- **B** (SD-X01): Shrishti calls easyAML her client.
- **Explanation:** Possibly split by platform, recently reassigned, or the pacing-sheet initials are stale.
- **Status:** Needs Aperitif

## <a id="x-09"></a>X-09 Performance team leadership

- **A** ([KO-PP04](../pain-points/README.md#ko-pp04)): Julia: 'a bit headless when it comes to performance' (22 Oct, L066).
- **B** ([WS-PP11](../pain-points/README.md#ws-pp11) / WS-X04 / context pack): Wendlley is Performance Marketing Director; 'JP', a Head of Performance, left \~2 weeks before 28 Oct; KO-dep08 calls lead titles 'director titles, not directorships'.
- **Explanation:** Consistent: a senior Head of Performance (JP) above the Director left mid-October; the Director title doesn't carry that seat.
- **Status:** Resolved (from evidence) – confirm JP's role

## <a id="x-10"></a>X-10 \$10K Leaselab overspend vs LinkedIn overspend

- **A** ([MP-PP01](../pain-points/README.md#mp-pp01)): \$10K credit (Leaselab): budget changed but sheet not updated, so tracker paced against the wrong number (L377).
- **B** ([MP-PP02](../pain-points/README.md#mp-pp02) / context pack): LinkedIn had no pacing tracker – 'now we've got to spend on LinkedIn because we didn't have a pacing tracker' (L577); pack: '\$10K LinkedIn overspend (no LinkedIn pacing, wrong budget figure)'. MP-X02: Joe says it sat with 'our most senior person'; pack lists DM on Leaselab Google.
- **Explanation:** Probably one Leaselab LinkedIn incident with two causes (no LinkedIn tracker and a stale budget figure), but the transcript doesn't tie them explicitly.
- **Status:** Open – to confirm with Joe

## <a id="x-11"></a>X-11 Julia at the mid-point meeting

- **A** (Evidence Log): Mid-point listed as Joe & Julia.
- **B** (MP-X01): No line firmly attributable to Julia.
- **Explanation:** Julia may have been present but silent, or absent.
- **Status:** Open – audit team

## <a id="x-12"></a>X-12 Campaign build 1 day vs 3–5 days

- **A** (Context pack §5): Build 3–5 days.
- **B** ([MC-PP10](../pain-points/README.md#mc-pp10) / MC-str08): Build \~1 day once approvals are in (L271); SD-PP12 ad hoc launch ≥ 1 week incl. creatives and approvals.
- **Explanation:** Touch time \~1 day; elapsed time 3–5 days or more because of approvals and creatives.
- **Status:** Resolved (from evidence)

## <a id="x-13"></a>X-13 Diya's client tiers

- **A** (DM-X02): Mostly Tier 2/3 clients.
- **B** (Context pack §4): DM on Leaselab (\$141K Google), White & Co, easyAML, AMIGA.
- **Explanation:** Context-pack tiers are SEO tiers; paid has its own (or no formal) tiering by spend.
- **Status:** Needs Aperitif (paid tier list)

## <a id="x-14"></a>X-14 Sarah's 4 vs 5 freelancers

- **A** (SJ-X04): 'Four freelancers'.
- **B** (Context pack §2): Five contractor names (Chloe, Jess, Kayla, Aly, Ben).
- **Explanation:** Four active now; one occasional or former.
- **Status:** Needs Aperitif

## <a id="x-15"></a>X-15 Is there a usable wiki?

- **A** ([KO-PP15](../pain-points/README.md#ko-pp15)): Julia: 'We need a wiki badly' (L082).
- **B** (KO follow-up): Joe: 'everything's in Notion' (L423), 'a lot of documentation' (L088).
- **Explanation:** Both true: content exists (217 pages) but is stale (43% unedited in a year) and unread (MP-PP03, WS-PP09).
- **Status:** Resolved (from evidence)

## <a id="x-16"></a>X-16 Sales-to-delivery handover

- **A** (KO-str07 / KO follow-up): Joe: one HubSpot record with all notes plus a 15-minute internal call (L301).
- **B** ([WS-PP06](../pain-points/README.md#ws-pp06) / [MC-PP11](../pain-points/README.md#mc-pp11) / [SH-PP07](../pain-points/README.md#sh-pp07)): Call sometimes 10 min before client call or skipped; onboarding calls run 'blind'; clients re-asked.
- **Explanation:** Process exists on paper, not run reliably.
- **Status:** Resolved (from evidence)

## <a id="x-17"></a>X-17 Which 'three places' budgets live in

- **A** ([SH-PP01](../pain-points/README.md#sh-pp01)): HubSpot, Monday.com and pacing sheets.
- **B** ([SD-PP02](../pain-points/README.md#sd-pp02) / context pack): Google budget sheet, pacing sheet and the platform.
- **Explanation:** In practice five places: budget sheet, pacing sheet, platform, HubSpot, Monday.
- **Status:** Resolved (from evidence)

## <a id="x-18"></a>X-18 Technical audit – manual 81 items vs automated

- **A** (Context pack §5): 81-item Technical SEO Audit run by technical SEO.
- **B** (SB-X02 / SB-str04): Audits automated via Claude MCP (Spencer's earlier work; status unclear).
- **Explanation:** Automation may exist for part of the checklist; unclear which is current.
- **Status:** Needs Aperitif

## <a id="x-19"></a>X-19 Is the link-building lead overstretched?

- **A** (KZ-X04 (L156)): 'No, I feel okay.'
- **B** (KZ-X04 (L201, L560)): Overtime in onboarding months; 'at my cap'.
- **Explanation:** Fine in normal months, over capacity in onboarding peaks.
- **Status:** Resolved (from evidence)

## <a id="x-20"></a>X-20 Live link checks stopped after April

- **A** (Context pack (problem #3)): Live checks stopped after April.
- **B** (TG-X02): Outreach lead checks status at publication with a browser extension.
- **Explanation:** Publication-time check continues; post-publication re-checks stopped.
- **Status:** Resolved (from evidence)

## <a id="x-21"></a>X-21 Are call transcripts used?

- **A** (KO-X04): Joe: Otter recordings 'should go into the CRM automatically' (L320).
- **B** ([MP-PP20](../pain-points/README.md#mp-pp20) / [KZ-PP16](../pain-points/README.md#kz-pp16) / [ZC-PP13](../pain-points/README.md#zc-pp13)): Only Joe uses transcripts; Gemini notes switched on inconsistently and rarely reviewed.
- **Explanation:** Captured (sometimes) but not used.
- **Status:** Resolved (from evidence)

## <a id="x-22"></a>X-22 Is there any proactive alerting?

- **A** (KO-str08 / KO-X05): Google Ads script flags 7 days without conversions (L356).
- **B** ([SD-PP04](../pain-points/README.md#sd-pp04) / [DM-PP03](../pain-points/README.md#dm-pp03) / [WS-PP04](../pain-points/README.md#ws-pp04)): Issues seen only in the account; alerts give no cause.
- **Explanation:** Script covers one failure mode only.
- **Status:** Resolved (from evidence)

## <a id="x-23"></a>X-23 What is 'Tina'?

- **A** (SJ-X05): Industry-statistics bot.
- **B** (Context pack / [SD-PP19](../pain-points/README.md#sd-pp19)): Pacing and agenda bot.
- **Explanation:** Tina is an OpenClaw agent workspace with several functions.
- **Status:** Open – to confirm with Joe

## <a id="x-24"></a>X-24 Call-prep time

- **A** ([SD-PP05](../pain-points/README.md#sd-pp05)): 1 h–1 h 15 per 30-min call incl. follow-up (L161).
- **B** ([DM-PP05](../pain-points/README.md#dm-pp05)): \~30 min data review per monthly WIP call (L257).
- **Explanation:** Different scopes (prep+follow-up vs data review) and client complexity.
- **Status:** Resolved (from evidence)

## <a id="x-25"></a>X-25 Underperformance tickets – HubSpot or Monday

- **A** (WS-X03 (L367)): 'Flow in HubSpot'.
- **B** (WS-X03 (L378)): 'Migrated from HubSpot to Monday'.
- **Explanation:** Migrated; the HubSpot description is out of date.
- **Status:** Resolved (from evidence)

## <a id="x-26"></a>X-26 Content volume baseline

- **A** (SJ-X01 (L069)): Started at 40,000 words a month.
- **B** (SJ-X01 (L257) / context pack): Sheet growth 'from 60 to 100'; pack \~93k average.
- **Explanation:** Different start points; \~100k is current and consistent with \~93k average.
- **Status:** Needs data (tracker history)

## <a id="x-27"></a>X-27 Spencer Potts's status

- **A** (Context pack §2): Role unclear; not on chart.
- **B** (LS-X05 / SB-dep4): Laura places him on the tech team; Sid cites his earlier audit work.
- **Explanation:** Probably current or recent tech team member.
- **Status:** Needs Aperitif

## <a id="x-28"></a>X-28 Scope for savings in organic

- **A** (LS-X02 / MP-X04): Austin's wrap-ups suggested little room to save time in organic/SEO.
- **B** ([LS-PP03](../pain-points/README.md#ls-pp03), [LS-PP04](../pain-points/README.md#ls-pp04), [LS-PP12](../pain-points/README.md#ls-pp12), [C-20](clusters-and-root-causes.md#c-20), [C-21](clusters-and-root-causes.md#c-21), [C-23](clusters-and-root-causes.md#c-23)): Laura then lists briefs, content sheets, link building and slides; many organic clusters carry hours.
- **Explanation:** Interviewer framing was leading (bias flag).
- **Status:** Resolved (from evidence)

## <a id="x-29"></a>X-29 Disney not in client lists

- **A** (KZ-X03): Described as one of Karl's largest, highest-paying clients.
- **B** (Context pack §4): Not listed (nor AquaSafe).
- **Explanation:** Client lists are SEO/link order-book based; Disney may be a project/localisation client.
- **Status:** Needs Aperitif

## <a id="x-30"></a>X-30 Individual high-end hours exceed one FTE

- **A** (KZ, TG, ZC, SJ, HT, WS, SD, DM, MC follow-ups): High-end monthly hours 159–217 h per person.
- **B** (Working month \~160 h): Can't all be true at the high end.
- **Explanation:** Assumed ranges stack; Stage 2 caps each person at 160 h.
- **Status:** Resolved (by Stage 2 rule)

## <a id="x-31"></a>X-31 HubSpot saving

- **A** (KO-X07 (L310)): Austin quoted \$24K/yr saving on HubSpot.
- **B** ([KO-PP12](../pain-points/README.md#ko-pp12) (L313)): Joe: HubSpot + Monday 'better part of 30 grand' after a reduction.
- **Explanation:** The saving from dropping HubSpot alone isn't established.
- **Status:** Needs data (invoices)
