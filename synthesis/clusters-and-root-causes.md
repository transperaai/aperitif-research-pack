# Clusters (C) and root causes (RC) – Stage 1

Generated from [stage1-part-b.json](stage1-part-b.json). Raised by = distinct interviews (staff + leadership); interviewer-raised items are corroboration only.

## Root causes

### <a id="rc-01"></a>RC-01

No system of record: budgets, client data, briefs, links and files are held in many hand-maintained copies, so people re-key, reconcile and collate by hand.

Anchor: Operations capacity & process · Clusters: [C-01](clusters-and-root-causes.md#c-01), [C-05](clusters-and-root-causes.md#c-05), [C-06](clusters-and-root-causes.md#c-06), [C-20](clusters-and-root-causes.md#c-20), [C-21](clusters-and-root-causes.md#c-21), [C-23](clusters-and-root-causes.md#c-23), [C-34](clusters-and-root-causes.md#c-34)

### <a id="rc-02"></a>RC-02

Monitoring is human: nothing pushes signals on spend, performance, tracking, link status, trends or churn, so problems surface late.

Anchor: Performance visibility & margin · Clusters: [C-03](clusters-and-root-causes.md#c-03), [C-04](clusters-and-root-causes.md#c-04), [C-15](clusters-and-root-causes.md#c-15), [C-16](clusters-and-root-causes.md#c-16), [C-25](clusters-and-root-causes.md#c-25)

### <a id="rc-03"></a>RC-03

Client context isn't captured per client, so every hand-off – sales to delivery, manager to writer or specialist, cover – loses detail.

Anchor: Client experience & delivery · Clusters: [C-07](clusters-and-root-causes.md#c-07), [C-08](clusters-and-root-causes.md#c-08), [C-12](clusters-and-root-causes.md#c-12), [C-27](clusters-and-root-causes.md#c-27)

### <a id="rc-04"></a>RC-04

Tools, automations and AI workflows are built by individuals with no owner, documentation, policy or renewal plan, so they break or stay personal.

Anchor: Technology, AI & stack · Clusters: [C-02](clusters-and-root-causes.md#c-02), [C-28](clusters-and-root-causes.md#c-28), [C-31](clusters-and-root-causes.md#c-31), [C-32](clusters-and-root-causes.md#c-32), [C-33](clusters-and-root-causes.md#c-33)

### <a id="rc-05"></a>RC-05

There is no effort model: time per client isn't measured, scope and onboardings aren't checked against capacity, and intake isn't triaged – so work is sold, priced and scheduled by feel.

Anchor: Operations capacity & process · Clusters: [C-10](clusters-and-root-causes.md#c-10), [C-17](clusters-and-root-causes.md#c-17), [C-18](clusters-and-root-causes.md#c-18), [C-19](clusters-and-root-causes.md#c-19), [C-26](clusters-and-root-causes.md#c-26), [C-38](clusters-and-root-causes.md#c-38)

### <a id="rc-06"></a>RC-06

Decisions and quality gates sit with a few senior people because authority isn't delegated and the management layer is thin.

Anchor: Leadership & dependency · Clusters: [C-22](clusters-and-root-causes.md#c-22), [C-24](clusters-and-root-causes.md#c-24), [C-36](clusters-and-root-causes.md#c-36), [C-37](clusters-and-root-causes.md#c-37), [C-39](clusters-and-root-causes.md#c-39)

### <a id="rc-07"></a>RC-07

External dependencies – client access, approvals, inputs, contractors and vendors – aren't contracted, time-boxed or tracked, so delivery waits.

Anchor: Client experience & delivery · Clusters: [C-09](clusters-and-root-causes.md#c-09), [C-11](clusters-and-root-causes.md#c-11), [C-13](clusters-and-root-causes.md#c-13), [C-14](clusters-and-root-causes.md#c-14), [C-29](clusters-and-root-causes.md#c-29)

### <a id="rc-08"></a>RC-08

Adoption isn't designed or enforced: systems and SOPs are built, then assumed to be used.

Anchor: Leadership & dependency · Clusters: [C-30](clusters-and-root-causes.md#c-30), [C-35](clusters-and-root-causes.md#c-35)

## Clusters

### <a id="c-01"></a>C-01 Paid budgets re-keyed by hand in three places, so pacing runs against wrong figures

- Raised by 3 staff + 1 leadership · confidence High (4 independent raises (3 staff + 1 leadership).)
- Root cause: [RC-01](clusters-and-root-causes.md#rc-01)
- Problems: [P-02 Budgets maintained by hand in three places; some channels (incl. LinkedIn) not tracked; a missed budget change cost a \$10K credit](../problems/p-02-budgets-maintained-by-hand-in-three-places.md)
- Members: [MP-PP01](../pain-points/README.md#mp-pp01) (interviewee), [SH-PP01](../pain-points/README.md#sh-pp01) (interviewee), [SD-PP02](../pain-points/README.md#sd-pp02) (interviewee), [SD-PP03](../pain-points/README.md#sd-pp03) (interviewee), [MC-PP07](../pain-points/README.md#mc-pp07) (interviewee), [SH-PP03](../pain-points/README.md#sh-pp03) (interviewee), [SH-PP04](../pain-points/README.md#sh-pp04) (interviewee)

### <a id="c-02"></a>C-02 Pacing tools are broken or fragile, so Meta and Google pacing is done by hand

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-04](clusters-and-root-causes.md#rc-04)
- Problems: [P-01 Meta pacing sheet is broken – Supermetrics connector failing](../problems/p-01-meta-pacing-sheet-is-broken-supermetrics-connector.md)
- Members: [SD-PP01](../pain-points/README.md#sd-pp01) (interviewee), [SH-PP02](../pain-points/README.md#sh-pp02) (interviewee), [SH-PP05](../pain-points/README.md#sh-pp05) (interviewee), [SD-PP15](../pain-points/README.md#sd-pp15) (interviewee), [SD-PP19](../pain-points/README.md#sd-pp19) (detected), [MC-PP06](../pain-points/README.md#mc-pp06) (interviewee)

### <a id="c-03"></a>C-03 Ad channels beyond Google and Meta have no pacing, so overspends go unseen

- Raised by 1 staff + 1 leadership · confidence Medium (2 raises (1 staff + 1 leadership); no stated \$ figure inside the cluster itself – the \$10K sits in MP-PP01 and may be the same incident (X-10). Would confirm: a list of live platforms per client vs pacing lines, and leadership confirming the incident.)
- Root cause: [RC-02](clusters-and-root-causes.md#rc-02)
- Problems: [P-02 Budgets maintained by hand in three places; some channels (incl. LinkedIn) not tracked; a missed budget change cost a \$10K credit](../problems/p-02-budgets-maintained-by-hand-in-three-places.md)
- Members: [MP-PP02](../pain-points/README.md#mp-pp02) (interviewee), [WS-PP02](../pain-points/README.md#ws-pp02) (interviewee)

### <a id="c-04"></a>C-04 Performance drops and tracking breaks surface only in manual checks, often at month-end

- Raised by 7 staff + 0 leadership · confidence High (7 independent raises (7 staff + 0 leadership).)
- Root cause: [RC-02](clusters-and-root-causes.md#rc-02)
- Problems: [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md)
- Members: [SD-PP04](../pain-points/README.md#sd-pp04) (interviewee), [DM-PP03](../pain-points/README.md#dm-pp03) (interviewee), [MC-PP08](../pain-points/README.md#mc-pp08) (interviewee), [DM-PP02](../pain-points/README.md#dm-pp02) (interviewee), [WS-PP04](../pain-points/README.md#ws-pp04) (interviewee), [SH-PP11](../pain-points/README.md#sh-pp11) (interviewee), [SH-PP12](../pain-points/README.md#sh-pp12) (interviewee), [MP-PP17](../pain-points/README.md#mp-pp17) (interviewer), [LS-PP05](../pain-points/README.md#ls-pp05) (interviewee), [ZC-PP05](../pain-points/README.md#zc-pp05) (interviewee)

### <a id="c-05"></a>C-05 Managers spend hours collating data across platforms for calls, queries and analysis

- Raised by 4 staff + 0 leadership · confidence High (4 independent raises (4 staff + 0 leadership).)
- Root cause: [RC-01](clusters-and-root-causes.md#rc-01)
- Problems: [P-04 Client-call prep takes longer than the call](../problems/p-04-client-call-prep-takes-longer-than-the.md)
- Members: [SD-PP05](../pain-points/README.md#sd-pp05) (interviewee), [SD-PP06](../pain-points/README.md#sd-pp06) (interviewee), [DM-PP05](../pain-points/README.md#dm-pp05) (interviewee), [SH-PP13](../pain-points/README.md#sh-pp13) (interviewee), [SD-PP14](../pain-points/README.md#sd-pp14) (interviewer), [DM-PP01](../pain-points/README.md#dm-pp01) (interviewee), [SD-PP13](../pain-points/README.md#sd-pp13) (interviewee), [WS-PP03](../pain-points/README.md#ws-pp03) (interviewee), [WS-PP12](../pain-points/README.md#ws-pp12) (interviewee)

### <a id="c-06"></a>C-06 Client reports, reviews and decks are assembled and narrated by hand each cycle

- Raised by 5 staff + 0 leadership · confidence High (5 independent raises (5 staff + 0 leadership).)
- Root cause: [RC-01](clusters-and-root-causes.md#rc-01)
- Problems: [P-05 Client documents are built by duplicating previous ones – errors reach clients](../problems/p-05-client-documents-are-built-by-duplicating-previous.md)
- Members: [DM-PP04](../pain-points/README.md#dm-pp04) (interviewee), [SH-PP16](../pain-points/README.md#sh-pp16) (interviewee), [LS-PP04](../pain-points/README.md#ls-pp04) (interviewee), [KZ-PP18](../pain-points/README.md#kz-pp18) (interviewee), [SH-PP06](../pain-points/README.md#sh-pp06) (interviewee), [WS-PP05](../pain-points/README.md#ws-pp05) (interviewee), [LS-PP16](../pain-points/README.md#ls-pp16) (interviewer), [DM-PP14](../pain-points/README.md#dm-pp14) (interviewee)

### <a id="c-07"></a>C-07 Client knowledge sits in people's heads and personal docs, so briefs and cover suffer

- Raised by 4 staff + 0 leadership · confidence High (4 independent raises (4 staff + 0 leadership).)
- Root cause: [RC-03](clusters-and-root-causes.md#rc-03)
- Problems: [P-14 Client knowledge lives in people's heads, not per client](../problems/p-14-client-knowledge-lives-in-people-s-heads.md)
- Members: [ZC-PP01](../pain-points/README.md#zc-pp01) (interviewee), [ZC-PP04](../pain-points/README.md#zc-pp04) (interviewee), [HT-PP04](../pain-points/README.md#ht-pp04) (interviewer), [SJ-PP09](../pain-points/README.md#sj-pp09) (interviewee), [KZ-PP15](../pain-points/README.md#kz-pp15) (interviewee), [KZ-PP16](../pain-points/README.md#kz-pp16) (interviewee), [ZC-PP13](../pain-points/README.md#zc-pp13) (interviewee), [MP-PP20](../pain-points/README.md#mp-pp20) (interviewer), [WS-PP08](../pain-points/README.md#ws-pp08) (detected)

### <a id="c-08"></a>C-08 Client handovers (sales to delivery, offboarding) have no structured pack or trigger

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-03](clusters-and-root-causes.md#rc-03)
- Problems: [P-27 Client handovers (sales to delivery, offboarding) have no structured pack or trigger](../problems/p-27-client-handovers-have-no-structured-pack-or.md)
- Members: [KO-PP01](../pain-points/README.md#ko-pp01) (interviewer), [SH-PP07](../pain-points/README.md#sh-pp07) (interviewee), [MC-PP11](../pain-points/README.md#mc-pp11) (interviewee), [WS-PP06](../pain-points/README.md#ws-pp06) (interviewee), [MC-PP14](../pain-points/README.md#mc-pp14) (interviewee)

### <a id="c-09"></a>C-09 Client onboarding stalls waiting on access, client inputs and the tracking contractor

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-07](clusters-and-root-causes.md#rc-07)
- Problems: [P-17 Conversion tracking depends on one contractor](../problems/p-17-conversion-tracking-depends-on-one-contractor.md), [P-20 Onboarding stalls on client access and disrupts BAU](../problems/p-20-onboarding-stalls-on-client-access-and-disrupts.md)
- Members: [ZC-PP07](../pain-points/README.md#zc-pp07) (interviewee), [SD-PP09](../pain-points/README.md#sd-pp09) (interviewee), [SD-PP10](../pain-points/README.md#sd-pp10) (interviewee), [MC-PP10](../pain-points/README.md#mc-pp10) (interviewee), [MC-PP17](../pain-points/README.md#mc-pp17) (interviewer), [MC-PP16](../pain-points/README.md#mc-pp16) (interviewee)

### <a id="c-10"></a>C-10 Onboarding work is manual and heavy; clustered starts swamp BAU and wear staff down

- Raised by 4 staff + 2 leadership · confidence High (6 independent raises (4 staff + 2 leadership).)
- Root cause: [RC-05](clusters-and-root-causes.md#rc-05)
- Problems: [P-20 Onboarding stalls on client access and disrupts BAU](../problems/p-20-onboarding-stalls-on-client-access-and-disrupts.md)
- Members: [KO-PP08](../pain-points/README.md#ko-pp08) (interviewee), [KZ-PP01](../pain-points/README.md#kz-pp01) (interviewee), [KZ-PP02](../pain-points/README.md#kz-pp02) (interviewee), [KZ-PP03](../pain-points/README.md#kz-pp03) (interviewee), [KZ-PP04](../pain-points/README.md#kz-pp04) (interviewee), [ZC-PP08](../pain-points/README.md#zc-pp08) (interviewee), [MC-PP12](../pain-points/README.md#mc-pp12) (interviewee), [SD-PP11](../pain-points/README.md#sd-pp11) (interviewee), [KO-PP22](../pain-points/README.md#ko-pp22) (interviewee)

### <a id="c-11"></a>C-11 Content stalls at client approval with no client-facing approval trail

- Raised by 4 staff + 0 leadership · confidence High (4 independent raises (4 staff + 0 leadership).)
- Root cause: [RC-07](clusters-and-root-causes.md#rc-07)
- Problems: [P-10 Content stalls at client approval – or the tracker can't show what's finished](../problems/p-10-content-stalls-at-client-approval-or-the.md)
- Members: [KZ-PP14](../pain-points/README.md#kz-pp14) (interviewee), [ZC-PP06](../pain-points/README.md#zc-pp06) (interviewee), [LS-PP06](../pain-points/README.md#ls-pp06) (interviewee), [LS-PP07](../pain-points/README.md#ls-pp07) (interviewer), [LS-PP17](../pain-points/README.md#ls-pp17) (interviewee), [HT-PP10](../pain-points/README.md#ht-pp10) (interviewee)

### <a id="c-12"></a>C-12 Regulated-industry content lacks shared compliance rules and credible sources

- Raised by 2 staff + 0 leadership · confidence Medium (2 staff raises; no stated impact number (research hours assumed). Would confirm: count of regulated-client rejections or revision rounds over 6 months.)
- Root cause: [RC-03](clusters-and-root-causes.md#rc-03)
- Problems: [P-28 Regulated-industry content lacks shared compliance rules and credible sources](../problems/p-28-regulated-industry-content-lacks-shared-compliance-rules.md)
- Members: [ZC-PP11](../pain-points/README.md#zc-pp11) (interviewee), [SJ-PP07](../pain-points/README.md#sj-pp07) (interviewee)

### <a id="c-13"></a>C-13 Page builds and content uploads reach clients with errors or loop for weeks

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-07](clusters-and-root-causes.md#rc-07)
- Problems: [P-29 Page builds and content uploads reach clients with errors or loop for weeks](../problems/p-29-page-builds-and-content-uploads-reach-clients.md)
- Members: [KZ-PP13](../pain-points/README.md#kz-pp13) (interviewee), [LS-PP10](../pain-points/README.md#ls-pp10) (interviewee), [SB-PP07](../pain-points/README.md#sb-pp07) (interviewee), [SB-PP08](../pain-points/README.md#sb-pp08) (interviewee)

### <a id="c-14"></a>C-14 Client approval cycles hold up paid optimisations and launches, while managers carry the blame

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-07](clusters-and-root-causes.md#rc-07)
- Problems: [P-30 Client approval cycles hold up paid optimisations and launches, while managers carry the blame](../problems/p-30-client-approval-cycles-hold-up-paid-optimisations.md)
- Members: [DM-PP06](../pain-points/README.md#dm-pp06) (interviewee), [DM-PP07](../pain-points/README.md#dm-pp07) (interviewee), [SD-PP12](../pain-points/README.md#sd-pp12) (interviewee), [SD-PP18](../pain-points/README.md#sd-pp18) (interviewee), [SD-PP17](../pain-points/README.md#sd-pp17) (interviewee), [WS-PP16](../pain-points/README.md#ws-pp16) (interviewee)

### <a id="c-15"></a>C-15 Seasonal, trending and competitor signals are spotted too late, by hand

- Raised by 2 staff + 0 leadership · confidence High (2 staff raises with stated numbers: \~2-month lead time needed (ZC-PP09) and trends refreshable only every 2–3 days (KZ-PP19). Both from SEO managers.)
- Root cause: [RC-02](clusters-and-root-causes.md#rc-02)
- Problems: [P-24 Seasonal and trending content is planned too late to catch the peak](../problems/p-24-seasonal-and-trending-content-is-planned-too.md)
- Members: [ZC-PP09](../pain-points/README.md#zc-pp09) (interviewee), [KZ-PP19](../pain-points/README.md#kz-pp19) (interviewee), [KZ-PP20](../pain-points/README.md#kz-pp20) (interviewee), [ZC-PP17](../pain-points/README.md#zc-pp17) (interviewee), [ZC-PP15](../pain-points/README.md#zc-pp15) (interviewee)

### <a id="c-16"></a>C-16 Churn risk is spotted late and account teams report rather than advise

- Raised by 1 staff + 2 leadership · confidence High (3 independent raises (1 staff + 2 leadership). Mostly leadership evidence.)
- Root cause: [RC-02](clusters-and-root-causes.md#rc-02)
- Problems: [P-31 Churn risk is spotted late and account teams report rather than advise](../problems/p-31-churn-risk-is-spotted-late-and-account.md)
- Members: [KO-PP06](../pain-points/README.md#ko-pp06) (detected), [MP-PP16](../pain-points/README.md#mp-pp16) (interviewee), [LS-PP15](../pain-points/README.md#ls-pp15) (interviewee), [KO-PP20](../pain-points/README.md#ko-pp20) (interviewee), [LS-PP08](../pain-points/README.md#ls-pp08) (interviewee), [LS-PP09](../pain-points/README.md#ls-pp09) (interviewer)

### <a id="c-17"></a>C-17 Managers are at capacity, so lower-tier clients and account hygiene slip first

- Raised by 7 staff + 2 leadership · confidence High (9 independent raises (7 staff + 2 leadership).)
- Root cause: [RC-05](clusters-and-root-causes.md#rc-05)
- Problems: [P-21 Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md)
- Members: [LS-PP01](../pain-points/README.md#ls-pp01) (interviewee), [LS-PP02](../pain-points/README.md#ls-pp02) (interviewee), [WS-PP01](../pain-points/README.md#ws-pp01) (interviewee), [SD-PP07](../pain-points/README.md#sd-pp07) (interviewee), [SD-PP08](../pain-points/README.md#sd-pp08) (interviewee), [MC-PP09](../pain-points/README.md#mc-pp09) (interviewee), [DM-PP10](../pain-points/README.md#dm-pp10) (interviewee), [SB-PP13](../pain-points/README.md#sb-pp13) (interviewee), [SH-PP09](../pain-points/README.md#sh-pp09) (interviewee), [KO-PP26](../pain-points/README.md#ko-pp26) (interviewee), [MC-PP18](../pain-points/README.md#mc-pp18) (interviewee), [KO-PP09](../pain-points/README.md#ko-pp09) (interviewee), [MP-PP18](../pain-points/README.md#mp-pp18) (interviewee), [MP-PP19](../pain-points/README.md#mp-pp19) (interviewee), [MP-PP21](../pain-points/README.md#mp-pp21) (interviewer)

### <a id="c-18"></a>C-18 Unplanned same-day and high-touch client requests break the planned month

- Raised by 5 staff + 0 leadership · confidence High (5 independent raises (5 staff + 0 leadership).)
- Root cause: [RC-05](clusters-and-root-causes.md#rc-05)
- Problems: [P-32 Unplanned same-day and high-touch client requests break the planned month](../problems/p-32-unplanned-same-day-and-high-touch-client.md)
- Members: [HT-PP01](../pain-points/README.md#ht-pp01) (interviewee), [HT-PP02](../pain-points/README.md#ht-pp02) (interviewee), [SJ-PP14](../pain-points/README.md#sj-pp14) (interviewee), [KZ-PP23](../pain-points/README.md#kz-pp23) (interviewee), [KZ-PP05](../pain-points/README.md#kz-pp05) (interviewee), [SB-PP15](../pain-points/README.md#sb-pp15) (interviewee), [MC-PP01](../pain-points/README.md#mc-pp01) (interviewee)

### <a id="c-19"></a>C-19 Effort per client isn't tracked, so capacity, pricing and margin are set by feel

- Raised by 1 staff + 1 leadership · confidence High (2 raises (1 staff + 1 leadership) with a stated number (gross margin 'roughly 30%', DLER only proxy, KO-PP07). Mostly leadership evidence; rests on two people.)
- Root cause: [RC-05](clusters-and-root-causes.md#rc-05)
- Problems: [P-26 Pricing is inconsistent across templates and the margin maths is wrong](../problems/p-26-pricing-is-inconsistent-across-templates-and-the.md)
- Members: [KO-PP07](../pain-points/README.md#ko-pp07) (interviewee), [KZ-PP22](../pain-points/README.md#kz-pp22) (interviewee)

### <a id="c-20"></a>C-20 Content briefs are re-cut and reformatted by hand, eating the first half of each month

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-01](clusters-and-root-causes.md#rc-01)
- Problems: [P-33 Content briefs are re-cut and reformatted by hand, eating the first half of each month](../problems/p-33-content-briefs-are-re-cut-and-reformatted.md)
- Members: [LS-PP03](../pain-points/README.md#ls-pp03) (interviewee), [ZC-PP02](../pain-points/README.md#zc-pp02) (interviewee), [ZC-PP03](../pain-points/README.md#zc-pp03) (interviewee), [KZ-PP17](../pain-points/README.md#kz-pp17) (interviewee)

### <a id="c-21"></a>C-21 Content hand-offs run on hand-copied sheets: briefs late or unseen, statuses double-keyed

- Raised by 2 staff + 0 leadership · confidence High (2 staff raises (both content team) with stated figures: brief unseen up to 2 days vs a 2-week turnaround (SJ-PP02); volume \~40k → \~100k words/month (SJ-PP11). Most members come from one interview (SJ).)
- Root cause: [RC-01](clusters-and-root-causes.md#rc-01)
- Problems: [P-11 Content tracker and link sheets live outside Monday.com](../problems/p-11-content-tracker-and-link-sheets-live-outside.md)
- Members: [SJ-PP01](../pain-points/README.md#sj-pp01) (interviewee), [SJ-PP02](../pain-points/README.md#sj-pp02) (interviewee), [SJ-PP03](../pain-points/README.md#sj-pp03) (interviewee), [SJ-PP06](../pain-points/README.md#sj-pp06) (interviewee), [HT-PP09](../pain-points/README.md#ht-pp09) (interviewee), [SJ-PP04](../pain-points/README.md#sj-pp04) (interviewee), [SJ-PP08](../pain-points/README.md#sj-pp08) (interviewee), [HT-PP05](../pain-points/README.md#ht-pp05) (interviewee), [SJ-PP11](../pain-points/README.md#sj-pp11) (interviewee), [SJ-PP10](../pain-points/README.md#sj-pp10) (interviewee)

### <a id="c-22"></a>C-22 Content delivery hinges on one manager as editor, router and freelancer manager

- Raised by 2 staff + 0 leadership · confidence Medium (2 staff raises, both from the content team; no stated number. Corroborated in dependency sections of two SEO interviews (KZ, LS). Would confirm: share of words edited by the Content Manager from the tracker.)
- Root cause: [RC-06](clusters-and-root-causes.md#rc-06)
- Problems: [P-09 Content delivery hinges on the Content Manager as writer, editor and contractor manager](../problems/p-09-content-delivery-hinges-on-the-content-manager.md)
- Members: [SJ-PP05](../pain-points/README.md#sj-pp05) (interviewee), [HT-PP03](../pain-points/README.md#ht-pp03) (interviewee), [SJ-PP13](../pain-points/README.md#sj-pp13) (interviewee), [SJ-PP12](../pain-points/README.md#sj-pp12) (interviewee), [HT-PP07](../pain-points/README.md#ht-pp07) (interviewee)

### <a id="c-23"></a>C-23 Link building runs on disconnected sheets; every order, link and invoice is re-keyed

- Raised by 2 staff + 2 leadership · confidence High (4 independent raises (2 staff + 2 leadership).)
- Root cause: [RC-01](clusters-and-root-causes.md#rc-01)
- Problems: [P-06 Link building runs on 7+ disconnected spreadsheets](../problems/p-06-link-building-runs-on-7-disconnected-spreadsheets.md), [P-08 Outreacher invoicing tracked as PayPal links in spreadsheet cells](../problems/p-08-outreacher-invoicing-tracked-as-paypal-links-in.md), [P-11 Content tracker and link sheets live outside Monday.com](../problems/p-11-content-tracker-and-link-sheets-live-outside.md)
- Members: [KO-PP16](../pain-points/README.md#ko-pp16) (interviewee), [MP-PP14](../pain-points/README.md#mp-pp14) (interviewee), [MP-PP15](../pain-points/README.md#mp-pp15) (interviewee), [TG-PP05](../pain-points/README.md#tg-pp05) (interviewee), [TG-PP06](../pain-points/README.md#tg-pp06) (interviewee), [TG-PP07](../pain-points/README.md#tg-pp07) (interviewee), [KZ-PP08](../pain-points/README.md#kz-pp08) (interviewee)

### <a id="c-24"></a>C-24 Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent

- Raised by 4 staff + 0 leadership · confidence High (4 independent raises (4 staff + 0 leadership).)
- Root cause: [RC-06](clusters-and-root-causes.md#rc-06)
- Problems: [P-34 Link sourcing is slow, manual and supply-constrained, and AI vetting is inconsistent](../problems/p-34-link-sourcing-is-slow-manual-and-supply.md)
- Members: [KZ-PP06](../pain-points/README.md#kz-pp06) (interviewee), [KZ-PP09](../pain-points/README.md#kz-pp09) (interviewee), [TG-PP01](../pain-points/README.md#tg-pp01) (interviewee), [TG-PP02](../pain-points/README.md#tg-pp02) (interviewee), [TG-PP10](../pain-points/README.md#tg-pp10) (interviewee), [KZ-PP07](../pain-points/README.md#kz-pp07) (interviewee), [LS-PP12](../pain-points/README.md#ls-pp12) (interviewee), [TG-PP12](../pain-points/README.md#tg-pp12) (interviewee), [TG-PP04](../pain-points/README.md#tg-pp04) (interviewee), [TG-PP03](../pain-points/README.md#tg-pp03) (interviewee), [TG-PP08](../pain-points/README.md#tg-pp08) (interviewee), [ZC-PP16](../pain-points/README.md#zc-pp16) (interviewee)

### <a id="c-25"></a>C-25 Paid links vanish after payment and nobody re-checks that they stay live

- Raised by 3 staff + 1 leadership · confidence High (4 independent raises (3 staff + 1 leadership).)
- Root cause: [RC-02](clusters-and-root-causes.md#rc-02)
- Problems: [P-07 Paid links disappear after payment – detected manually](../problems/p-07-paid-links-disappear-after-payment-detected-manually.md)
- Members: [MP-PP13](../pain-points/README.md#mp-pp13) (interviewee), [KZ-PP10](../pain-points/README.md#kz-pp10) (interviewee), [ZC-PP10](../pain-points/README.md#zc-pp10) (interviewee), [TG-PP11](../pain-points/README.md#tg-pp11) (interviewee)

### <a id="c-26"></a>C-26 Strategy and technical SEO run as separate queues, so big technical work slips

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-05](clusters-and-root-causes.md#rc-05)
- Problems: [P-35 Strategy and technical SEO run as separate queues, so big technical work slips](../problems/p-35-strategy-and-technical-seo-run-as-separate.md)
- Members: [KZ-PP11](../pain-points/README.md#kz-pp11) (interviewee), [KZ-PP12](../pain-points/README.md#kz-pp12) (interviewee), [SB-PP14](../pain-points/README.md#sb-pp14) (interviewee), [ZC-PP12](../pain-points/README.md#zc-pp12) (interviewee)

### <a id="c-27"></a>C-27 Internal task briefs from managers to implementers are slow to write and often incomplete

- Raised by 4 staff + 0 leadership · confidence High (4 independent raises (4 staff + 0 leadership).)
- Root cause: [RC-03](clusters-and-root-causes.md#rc-03)
- Problems: [P-36 Internal task briefs from managers to implementers are slow to write and often incomplete](../problems/p-36-internal-task-briefs-from-managers-to-implementers.md)
- Members: [SH-PP10](../pain-points/README.md#sh-pp10) (interviewee), [DM-PP13](../pain-points/README.md#dm-pp13) (interviewee), [MC-PP04](../pain-points/README.md#mc-pp04) (interviewee), [MC-PP05](../pain-points/README.md#mc-pp05) (interviewee), [LS-PP14](../pain-points/README.md#ls-pp14) (interviewee)

### <a id="c-28"></a>C-28 Meta campaign builds are manual and every ad needs hand QA

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-04](clusters-and-root-causes.md#rc-04)
- Problems: [P-37 Meta campaign builds are manual and every ad needs hand QA](../problems/p-37-meta-campaign-builds-are-manual-and-every.md)
- Members: [SH-PP15](../pain-points/README.md#sh-pp15) (interviewee), [SH-PP17](../pain-points/README.md#sh-pp17) (interviewee), [MC-PP20](../pain-points/README.md#mc-pp20) (interviewee), [DM-PP08](../pain-points/README.md#dm-pp08) (interviewee)

### <a id="c-29"></a>C-29 Creative and landing pages are outsourced, slow and hard to brief

- Raised by 2 staff + 1 leadership · confidence High (3 independent raises (2 staff + 1 leadership).)
- Root cause: [RC-07](clusters-and-root-causes.md#rc-07)
- Problems: [P-38 Creative and landing pages are outsourced, slow and hard to brief](../problems/p-38-creative-and-landing-pages-are-outsourced-slow.md)
- Members: [KO-PP25](../pain-points/README.md#ko-pp25) (interviewee), [WS-PP14](../pain-points/README.md#ws-pp14) (interviewee), [MP-PP22](../pain-points/README.md#mp-pp22) (interviewee), [MC-PP15](../pain-points/README.md#mc-pp15) (interviewee)

### <a id="c-30"></a>C-30 Monday.com isn't the single home for work: requests bypass it and statuses go stale

- Raised by 4 staff + 1 leadership · confidence High (5 independent raises (4 staff + 1 leadership).)
- Root cause: [RC-08](clusters-and-root-causes.md#rc-08)
- Problems: [P-16 Reminders go unacted; a broken reminder bot went unnoticed](../problems/p-16-reminders-go-unacted-a-broken-reminder-bot.md)
- Members: [SB-PP01](../pain-points/README.md#sb-pp01) (interviewee), [SB-PP02](../pain-points/README.md#sb-pp02) (interviewee), [SB-PP03](../pain-points/README.md#sb-pp03) (interviewee), [SB-PP04](../pain-points/README.md#sb-pp04) (interviewee), [SB-PP05](../pain-points/README.md#sb-pp05) (interviewee), [SB-PP06](../pain-points/README.md#sb-pp06) (interviewee), [MC-PP02](../pain-points/README.md#mc-pp02) (interviewee), [MC-PP03](../pain-points/README.md#mc-pp03) (interviewee), [DM-PP09](../pain-points/README.md#dm-pp09) (interviewee), [MP-PP05](../pain-points/README.md#mp-pp05) (interviewee), [MP-PP06](../pain-points/README.md#mp-pp06) (interviewer), [WS-PP15](../pain-points/README.md#ws-pp15) (detected), [KO-PP10](../pain-points/README.md#ko-pp10) (interviewee)

### <a id="c-31"></a>C-31 HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost

- Raised by 2 staff + 1 leadership · confidence High (3 independent raises (2 staff + 1 leadership).)
- Root cause: [RC-04](clusters-and-root-causes.md#rc-04)
- Problems: [P-39 HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost](../problems/p-39-hubspot-make-monday-integrations-create-wrong-or.md)
- Members: [KO-PP11](../pain-points/README.md#ko-pp11) (interviewee), [KO-PP12](../pain-points/README.md#ko-pp12) (interviewee), [SB-PP10](../pain-points/README.md#sb-pp10) (interviewee), [MC-PP13](../pain-points/README.md#mc-pp13) (interviewee)

### <a id="c-32"></a>C-32 Home-built automations and tools have one builder, no documentation and no backup

- Raised by 3 staff + 0 leadership · confidence High (3 independent raises (3 staff + 0 leadership).)
- Root cause: [RC-04](clusters-and-root-causes.md#rc-04)
- Problems: [P-15 Slack bots and agents have no visible owner or documentation](../problems/p-15-slack-bots-and-agents-have-no-visible.md)
- Members: [SB-PP11](../pain-points/README.md#sb-pp11) (interviewee), [TG-PP09](../pain-points/README.md#tg-pp09) (detected), [HT-PP06](../pain-points/README.md#ht-pp06) (interviewee)

### <a id="c-33"></a>C-33 AI use is personal and ungoverned: no policy, shared skills, client context or seats

- Raised by 9 staff + 1 leadership · confidence High (10 independent raises (9 staff + 1 leadership).)
- Root cause: [RC-04](clusters-and-root-causes.md#rc-04)
- Problems: [P-40 AI use is personal and ungoverned: no policy, shared skills, client context or seats](../problems/p-40-ai-use-is-personal-and-ungoverned-no.md)
- Members: [KO-PP14](../pain-points/README.md#ko-pp14) (interviewee), [LS-PP13](../pain-points/README.md#ls-pp13) (interviewee), [DM-PP12](../pain-points/README.md#dm-pp12) (interviewee), [MC-PP19](../pain-points/README.md#mc-pp19) (interviewee), [WS-PP13](../pain-points/README.md#ws-pp13) (detected), [SB-PP12](../pain-points/README.md#sb-pp12) (interviewee), [KZ-PP24](../pain-points/README.md#kz-pp24) (interviewee), [SH-PP14](../pain-points/README.md#sh-pp14) (interviewee), [HT-PP08](../pain-points/README.md#ht-pp08) (interviewee), [DM-PP11](../pain-points/README.md#dm-pp11) (interviewee), [ZC-PP14](../pain-points/README.md#zc-pp14) (interviewee)

### <a id="c-34"></a>C-34 Client files and logins sit in personal drives and the CRM, not with the work

- Raised by 2 staff + 0 leadership · confidence Medium (2 staff raises on related but different assets (files vs logins); no stated number. Would confirm: a Drive ownership report for client folders.)
- Root cause: [RC-01](clusters-and-root-causes.md#rc-01)
- Problems: [P-23 Client work files are owned by individual staff accounts, including staff who have left](../problems/p-23-client-work-files-are-owned-by-individual.md)
- Members: [SH-PP08](../pain-points/README.md#sh-pp08) (interviewee), [SB-PP09](../pain-points/README.md#sb-pp09) (interviewee)

### <a id="c-35"></a>C-35 SOPs and new systems aren't adopted, so leaders re-explain and mistakes repeat

- Raised by 2 staff + 2 leadership · confidence High (4 independent raises (2 staff + 2 leadership).)
- Root cause: [RC-08](clusters-and-root-causes.md#rc-08)
- Problems: [P-12 Documentation is stale and rarely read](../problems/p-12-documentation-is-stale-and-rarely-read.md), [P-13 Documentation and internal tooling held by the founder](../problems/p-13-documentation-and-internal-tooling-held-by-the.md)
- Members: [MP-PP03](../pain-points/README.md#mp-pp03) (interviewee), [MP-PP04](../pain-points/README.md#mp-pp04) (interviewee), [WS-PP09](../pain-points/README.md#ws-pp09) (interviewee), [KO-PP15](../pain-points/README.md#ko-pp15) (interviewee), [LS-PP11](../pain-points/README.md#ls-pp11) (interviewee), [KO-PP13](../pain-points/README.md#ko-pp13) (interviewee), [MP-PP07](../pain-points/README.md#mp-pp07) (interviewer)

### <a id="c-36"></a>C-36 Escalations, sign-offs, QA and Tier 1 relationships funnel to a few senior people

- Raised by 2 staff + 2 leadership · confidence High (4 independent raises (2 staff + 2 leadership).)
- Root cause: [RC-06](clusters-and-root-causes.md#rc-06)
- Problems: [P-22 Escalations route around department leads to the Head of Client Services](../problems/p-22-escalations-route-around-department-leads-to-the.md)
- Members: [KO-PP05](../pain-points/README.md#ko-pp05) (interviewee), [KO-PP21](../pain-points/README.md#ko-pp21) (interviewee), [MP-PP08](../pain-points/README.md#mp-pp08) (interviewee), [WS-PP10](../pain-points/README.md#ws-pp10) (interviewee), [SD-PP16](../pain-points/README.md#sd-pp16) (detected), [KO-PP02](../pain-points/README.md#ko-pp02) (interviewee), [KO-PP03](../pain-points/README.md#ko-pp03) (interviewee)

### <a id="c-37"></a>C-37 Management layer is thin: paid media lacks a senior lead; new leads lack training

- Raised by 1 staff + 2 leadership · confidence High (3 independent raises (1 staff + 2 leadership). Mostly leadership evidence.)
- Root cause: [RC-06](clusters-and-root-causes.md#rc-06)
- Problems: [P-41 Management layer is thin: paid media lacks a senior lead; new leads lack training](../problems/p-41-management-layer-is-thin-paid-media-lacks.md)
- Members: [KO-PP04](../pain-points/README.md#ko-pp04) (interviewee), [WS-PP11](../pain-points/README.md#ws-pp11) (interviewee), [MP-PP09](../pain-points/README.md#mp-pp09) (interviewee)

### <a id="c-38"></a>C-38 Sales commits scope and spend that delivery can't meet profitably

- Raised by 1 staff + 1 leadership · confidence High (2 raises (1 staff + 1 leadership) with a stated figure – two months' work for a client with no website (WS-PP07). Bias: interviewer raised MP-PP10 first; no sales-side interview recorded.)
- Root cause: [RC-05](clusters-and-root-causes.md#rc-05)
- Problems: [P-18 Sales commits to work delivery can't profitably do](../problems/p-18-sales-commits-to-work-delivery-can-t.md)
- Members: [MP-PP10](../pain-points/README.md#mp-pp10) (interviewer), [MP-PP12](../pain-points/README.md#mp-pp12) (interviewee), [WS-PP07](../pain-points/README.md#ws-pp07) (interviewee)

### <a id="c-39"></a>C-39 Growth depends on the founder and inbound leads while AI erodes core services

- Raised by 1 staff + 2 leadership · confidence High (3 independent raises (1 staff + 2 leadership). Mostly leadership evidence.)
- Root cause: [RC-06](clusters-and-root-causes.md#rc-06)
- Problems: [P-19 Proposals are rebuilt from scratch per prospect](../problems/p-19-proposals-are-rebuilt-from-scratch-per-prospect.md), [P-42 Growth depends on the founder and inbound leads while AI erodes core services](../problems/p-42-growth-depends-on-the-founder-and-inbound.md)
- Members: [KO-PP17](../pain-points/README.md#ko-pp17) (interviewee), [MP-PP11](../pain-points/README.md#mp-pp11) (interviewee), [KO-PP18](../pain-points/README.md#ko-pp18) (interviewee), [KO-PP24](../pain-points/README.md#ko-pp24) (interviewee), [KO-PP23](../pain-points/README.md#ko-pp23) (interviewee), [KO-PP19](../pain-points/README.md#ko-pp19) (interviewee), [KZ-PP21](../pain-points/README.md#kz-pp21) (interviewee)
