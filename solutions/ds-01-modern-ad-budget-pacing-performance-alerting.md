---
id: DS-01
title: "Modern ad budget pacing + performance alerting"
team: "PPC"  # inferred: the page gives no "Team:" line
bundle: "PPC performance"
status: "Recommended – build 1, PPC pacing and performance assistant (with DS-27)"
coverage: addressed
source_type: "evidence-backed"
opportunities: ["O-01 (full)", "O-11 (full)", "O-15 (full)", "O-10 (interim step)", "O-12 (paid part (alerting))"]
earlier_ideas: ["EI-13 Pacing tracker + adjustment engine", "EI-15 Proactive PPC monitor and anomaly detector"]
written_sources: []
problems_fixed: ["P-02", "P-01", "P-03"]
problems_also_helped: ["P-21", "P-17"]
problems_related_only: []
pain_points_cited: ["MP-PP01", "MP-PP02", "SD-PP04", "SH-PP02"]
pain_points_interviewer_raised_or_inferred: []
value: "51–58 h/mo · A$187K–213K capacity (≈ 5–6 PPC clients) · A$10K overspend risk removed"
value_time_h_month: [51, 58]
value_capacity_aud_per_year: [187000, 213000]
value_extra_clients: [5, 6]
---

# DS-01 · Modern ad budget pacing + performance alerting

*Daily pacing and proactive performance alerts across every live ad channel, with per-client thresholds and Slack alerts – part of the PPC pacing and performance assistant (build 1).*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | PPC *(inferred)* |
| Status | Recommended – build 1, PPC pacing and performance assistant (with DS-27) |
| Source type | evidence-backed |
| Opportunities | [O-01](../opportunities/README.md#o-01) (full), [O-11](../opportunities/README.md#o-11) (full), [O-15](../opportunities/README.md#o-15) (full), [O-10](../opportunities/README.md#o-10) (interim step), [O-12](../opportunities/README.md#o-12) (paid part (alerting)) |
| Earlier ideas | [EI-13](../opportunities/README.md#ei-13) Pacing tracker + adjustment engine, [EI-15](../opportunities/README.md#ei-15) Proactive PPC monitor and anomaly detector |
| Fixes | [P-02 Budgets maintained by hand in three places; some channels (incl. LinkedIn) not tracked; a missed budget change cost a \$10K credit](../problems/p-02-budgets-maintained-by-hand-in-three-places.md); [P-01 Meta pacing sheet is broken – Supermetrics connector failing](../problems/p-01-meta-pacing-sheet-is-broken-supermetrics-connector.md); [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | [P-21 Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) – Solve now; [P-17 Conversion tracking depends on one contractor](../problems/p-17-conversion-tracking-depends-on-one-contractor.md) – Solve later |
| Pain points cited | [MP-PP01](../pain-points/README.md#mp-pp01), [MP-PP02](../pain-points/README.md#mp-pp02), [SD-PP04](../pain-points/README.md#sd-pp04), [SH-PP02](../pain-points/README.md#sh-pp02) |
| Written source | – |
| Value | 51–58 h/mo · A\$187K–213K capacity (≈ 5–6 PPC clients) · A\$10K overspend risk removed |

## Vision

> **A PPC manager can look after more clients and channels because they only open an account when something is flagged – either it needs a change, or there's a winning ad worth doubling down on.**
>
> - **Daily pacing** across every live channel, flagged when a client is off pace.
> - **Proactive performance alerts** on each client's own KPIs and thresholds – problems to fix and winners to scale.
> - **Alerts go to Slack and tag the account owner**; each one comes with a diagnosis drawn from the account data and the client brain ([DS-27](ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md)).
> - **Later:** autonomous action within agreed limits (e.g. moving budget to a winning ad, pausing a failing one), with the manager kept informed.

## Decision

DS-01 and [DS-27](ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md) are delivered together as build 1, the **PPC pacing and performance assistant** (Phase 1, start order 1). Prices are in [Builds and pricing](../builds/README.md).

- **Windsor.ai (bought, data only)** pulls spend and performance from every channel Aperitif runs – Google, Meta, Microsoft, LinkedIn, TikTok, Pinterest, Reddit, ChatGPT ads, Criteo and DV360 – into one place each day, and exposes it to the AI through its MCP connection and API.
- **Pacing engine (Transpera build):** a budget register holds each client's monthly budget per channel and every change, dated. A daily job compares spend to date with where it should be (straight-line or a set flight plan), forecasts month-end, and flags anything outside the agreed range.
- **Performance alerts (Transpera build):** each client's KPIs and thresholds (CPA, ROAS, conversions, CTR) are checked daily against target and the last 4–8 weeks; drops, spikes, stopped spend and clear winners are flagged.
- **Alerts only at first** – budget changes stay manual. Autonomous actions (Google and Meta budgets, pausing) come in a later phase through Windsor's write actions, within limits agreed per client, every change logged and the manager notified.
- **Ownership:** Transpera owns it technically; the business (account managers / performance lead) owns data validity – correct budgets, thresholds and channel lists.

## What it does

| Capability | Detail |
| --- | --- |
| Pacing | One budget per client entered once, every change logged; spend pulled automatically each day from every live channel incl. LinkedIn through Windsor.ai; daily pace vs budget and a month-end forecast |
| Performance thresholds | Per-client thresholds on CPA, CPL, ROAS, conversions, CTR, frequency etc., checked daily against target and the last 4–8 weeks |
| Alerts | Slack alerts tagging the account owner on over/under-pace, threshold breaches, stopped spend and clear winners – managers open an account when flagged |
| Actions | None automated at first; autonomous action within agreed limits in a later phase |

## Opportunities it covers

- **[O-01](../opportunities/README.md#o-01)** Restore the pacing data feed and cover every live channel – rank 1, priority 125, quick win (7–19 h/month)
- **[O-11](../opportunities/README.md#o-11)** Pacing tracker reads budgets and spend, flags gaps – rank 11, 75 (10–21 h/month)
- **[O-15](../opportunities/README.md#o-15)** Enter budgets once, log every change, written overspend policy – rank 15, 64 (1–4 h/month)
- **[O-10](../opportunities/README.md#o-10)** Switch on native platform alert rules and scripts now – rank 10, 75 (1–8 h/month) – *interim step before the build goes live*
- **[O-12](../opportunities/README.md#o-12)** Cross-account performance monitor with draft diagnosis – rank 12, 75 – **the paid part only**. The SEO part (weekly GA4 / Search Console / Ahrefs digest) is covered by the SEO-team solutions: [DS-22](ds-22-seo-automated-monday-client-performance-check.md), [DS-23](ds-23-seo-drop-and-anomaly-alerts.md), [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md).
- Austin's earlier ideas: *Pacing tracker + adjustment engine* and *Proactive PPC monitor and anomaly detector*

Value for this solution is worked out in **Value** below (\~51–58 h/month saved; \~A\$187K–213K a year of PPC capacity). The hour ranges listed against each opportunity above are earlier research estimates; the Value section is the current figure.

## Problems it fixes and the evidence

- [Budgets maintained by hand in three places; some channels (incl. LinkedIn) not tracked; a missed budget change cost a \$10K credit](../problems/p-02-budgets-maintained-by-hand-in-three-places.md) – Critical. 3 staff + 1 leadership. *"The budget would change and they wouldn't update the sheet. So the trackers are tracking. but it's on the wrong number."* – leadership ([MP-PP01](../pain-points/README.md#mp-pp01)). A \$10K credit was paid on one incident (stated).
- [Meta pacing sheet is broken – Supermetrics connector failing](../problems/p-01-meta-pacing-sheet-is-broken-supermetrics-connector.md) – Critical. 3 staff. *"we have to manually input like the ad account ID and the name and the budgets. And then it's not always pulling correctly."* – a performance manager ([SH-PP02](../pain-points/README.md#sh-pp02)). The performance director fills the Meta sheet by hand daily.
- Channels beyond Google and Meta (LinkedIn, TikTok, Criteo, Pinterest, ChatGPT ads) have no pacing at all – 1 staff + 1 leadership ([C-03](../synthesis/clusters-and-root-causes.md#c-03), part of the budgets problem). *"I probably should set up a pacing track with the LinkedIn and then bang, this happens."* – leadership ([MP-PP02](../pain-points/README.md#mp-pp02)).
- [No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) – High. **7 staff**, the widest raise in paid media. *"if I'm not in the account, then there's no way of knowing."* – a performance manager ([SD-PP04](../pain-points/README.md#sd-pp04)).
- Also helps: [Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) (alerts mean checking accounts only when flagged) and, later, [Conversion tracking depends on one contractor](../problems/p-17-conversion-tracking-depends-on-one-contractor.md) (a conversion-drop alert catches tracking breaks early).

## Options considered

The data layer was chosen after looking at these options; **Windsor.ai is the choice**.

- **Modernise the existing pacing bot** (fix or replace the failing Supermetrics feed, add the missing channels, run pacing daily, Slack alerts). Cheaper, but it fixes pacing only – no custom metric checks or spike/drop alerts across every channel – and it stays a home-built tool that depends on one person to keep running (key-person risk, [DS-10](ds-10-systems-register-and-break-fix-runbook.md)).
- **An all-channel pacing SaaS** such as Adpulse, [Shape.io](http://Shape.io), Pace, ReportGarden or BuyerBridge. These cover pacing and alerts, but some alert features (owner @mentions, real-time alerts, which alert types work on which channels) were not documented, and at Aperitif's \~A\$1.2M a month of spend and 100+ ad accounts the larger tools move to enterprise pricing.
- **Rules tools such as Bïrch (formerly Revealbot)**, which run rules across Meta, Google Ads, TikTok and Snapchat. **They do not list LinkedIn**, which has no pacing line today ([MP-PP02](../pain-points/README.md#mp-pp02)), so they don't fit the every-channel requirement.
- **A fully custom build on each platform's API.** Too heavy for one builder to run:

| What a custom build has to handle | Why it's heavy |
| --- | --- |
| A separate API for every channel (Google, Meta, Microsoft, LinkedIn, TikTok, Pinterest, Reddit, ChatGPT ads) | Each has its own data model, rate limits and login tokens to keep refreshed |
| Access approval per platform | LinkedIn's ad API needs a manual partner review, reported as weeks to months; Google now needs brand verification for API access |
| Constant API changes | Google releases a new Ads API version every 3–4 months and switches old versions off about a year after release, so code must be upgraded several times a year; other platforms change on their own schedules |
| Being the on-call fixer | If a feed breaks, pacing stops – the same key-person risk as today's Supermetrics and Make set-up ([DS-10](ds-10-systems-register-and-break-fix-runbook.md)) |

**Why Windsor.ai:** it buys the hard part – one daily data feed from every channel, connected straight to the AI – at about US\$499–598 a month, and Transpera builds only the pacing engine, budget register, alerts and diagnosis on top, tuned to Aperitif's clients.

## Future state

1. Budgets agreed with the client are entered **once**, with every change logged and dated.
2. Spend from every live channel is pulled automatically each day; nobody fills a sheet by hand.
3. Account managers open an account only when it's flagged – to fix something or to double down on a winner.
4. Every alert comes with a diagnosis and a recommended next step, so the manager starts deciding rather than investigating.
5. Winning ads and audiences are spotted early and scaled, not found at month-end.
6. No spend goes live on a channel without a pacing line.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| % of live channels with a pacing line | Below 100% – LinkedIn and others missing (MP-O01) | 100% |
| Days pacing data refreshes automatically | 0 – filled by hand (SD-O01) | 100% of working days |
| Overspend credits paid to clients | \$10K on one incident ([MP-PP01](../pain-points/README.md#mp-pp01)) | \$0 |
| Performance drops caught before month-end | Unknown – found in manual checks ([SD-PP04](../pain-points/README.md#sd-pp04)) | Alert within 24–48 h |
| Winning ads flagged to scale | Not tracked | Flagged weekly per client |

## Value

> **Works like a junior performance checker on every account.** It watches ad performance and pacing for every client and tells the account manager when something needs attention, so managers stop checking every account by hand and spend their time on client relationships and strategy. That lets each manager confidently take on more clients without being spread thin.

**1. Time saved**

| Task removed | How it's worked out | Per month |
| --- | --- | --- |
| Weekly manual account checks | 67 live PPC clients × \~15 min per client per week ≈ 73 h/month today; alerts remove 70–80% of checks (estimate – the target, not a measured figure) | **\~51–58 h** (\~10–11.5 h per manager) |
| Fixing the pacing feed and pacing gaps (Wendlley Simoes) | Feed breaks 3–4 times a week (\~20 min each); Windsor.ai replaces the failing feed | Removed; not added to the total |
| **Total** |  | **\~51–58 h/month** |

**2. Capacity and revenue unlocked**

Managers divide their time by each client's share of their MRR, so capacity is measured as **MRR managed per person**. Checking an account costs the same whatever the client pays – it's a fixed overhead on every client – so removing it frees time that can go to managing more MRR.

| Step | Figure |
| --- | --- |
| PPC account managers | 5 (per org chart; \~13–14 clients each) |
| MRR managed per manager today | \~A\$39.7K (A\$198,747 live PPC MRR across 67 clients ÷ 5) |
| Time freed per manager | \~10–11.5 h/month ≈ 8–9% of \~130 productive hours (assumption) |
| Extra MRR each manager can carry | \~A\$3.1K–3.5K MRR (≈ 1 more client each) |
| **Capacity unlocked across the PPC team** | **\~A\$15.6K–17.7K MRR ≈ A\$187K–213K a year** (≈ 5–6 more PPC clients at the \~A\$2,970 average) |

This is capacity to grow into without hiring, not guaranteed revenue. It is the dollar value of build 1 (with [DS-27](ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md)); up to \$10,000 of overspend credits avoided is on top (one incident this year; not added). Winner-scaling uplift is not measured.

**3. Problems it eliminates**

- **P-01** Meta pacing sheet is broken – Supermetrics connector failing
- **P-02** Budgets maintained by hand in three places; a missed budget change cost a A\$10K credit
- **P-03** No proactive performance alerting – problems found at month-end
- Helps: **P-21** Managers at capacity – Tier 2/3 clients get dropped first

**Risk removed:** repeats of the A\$10K overspend credit; performance drops and tracking breaks found within a day instead of at month-end.

**Goals:** more MRR managed per person · good performance · good customer service · retention · trust

*Inputs from Austin: 67 live PPC clients and A\$198,747 live PPC MRR (client board, 10 Nov, paused clients excluded), 5 PPC managers (org chart), \~15 min per weekly account check, pacing fixes by Wendlley. Assumptions: 70–80% of checks removed by alerts; \~130 productive hours per manager per month.*

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Hours saved are estimates; the transcripts gave few stated times.
- The channel list (LinkedIn, TikTok, Criteo, Pinterest, ChatGPT ads) comes from one interview (WS-O01); the live channel list per client and the total ad-account count (which sets the Windsor.ai plan) are confirmed before the build.
- Windsor.ai data is daily (cached up to 6 hours), so pacing catches drift by the next morning, not a same-day blowout; a 'no data arrived' check guards against silent connector failures.
- Tested on Windsor.ai's 30-day trial (10 sources, 15 accounts) against a few live accounts before committing.
- Autonomous action is a later phase: it needs agreed limits per client and the team's trust in the alerts first.
- Supermetrics is connected but failing, not cancelled (contradiction [X-01](../synthesis/contradictions.md#x-01)).

## Decided

- All channels through Windsor.ai · per-client thresholds · Slack alerts tagging the owner · alerts first, autonomous action later · Transpera = technical owner, business = data validity.
