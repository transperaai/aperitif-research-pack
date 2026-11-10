---
id: DS-01
title: "Modern ad budget pacing + performance alerting"
team: "PPC"  # inferred: the page gives no "Team:" line
bundle: "PPC performance"
status: "Decided – Adpulse recommended; priced"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-01 (full)", "O-11 (full)", "O-15 (full)", "O-10 (interim step)", "O-12 (paid part (alerting))"]
earlier_ideas: ["EI-13 Pacing tracker + adjustment engine", "EI-15 Proactive PPC monitor and anomaly detector"]
written_sources: []
problems_fixed: ["P-02", "P-01", "P-03"]
problems_also_helped: ["P-21", "P-17"]
problems_related_only: []
pain_points_cited: ["MP-PP01", "MP-PP02", "SD-PP04", "SH-PP02"]
pain_points_interviewer_raised_or_inferred: []
coi_per_year: "$15K–$38K"
build_cost: "Free"
monthly: "US$779/month (US$1M tier, annual); Enterprise quote if 100+ ad accounts"
notion_section: "Modern ad budget pacing + performance alerting"
---

# DS-01 · Modern ad budget pacing + performance alerting

*One pacing and alerting tool across every live ad channel, with per-client thresholds and Slack alerts (PPC team; alerts only).*

| | |
| --- | --- |
| Bundle | [PPC performance](README.md#bundle-ppc-performance) |
| Team | PPC *(inferred)* |
| Status | Decided – Adpulse recommended; priced |
| Source type | evidence-backed |
| Opportunities | [O-01](../opportunities/README.md#o-01) (full), [O-11](../opportunities/README.md#o-11) (full), [O-15](../opportunities/README.md#o-15) (full), [O-10](../opportunities/README.md#o-10) (interim step), [O-12](../opportunities/README.md#o-12) (paid part (alerting)) |
| Earlier ideas | [EI-13](../opportunities/README.md#ei-13) Pacing tracker + adjustment engine, [EI-15](../opportunities/README.md#ei-15) Proactive PPC monitor and anomaly detector |
| Fixes | [P-02 Budgets maintained by hand in three places; some channels (incl. LinkedIn) not tracked; a missed budget change cost a \$10K credit](../problems/p-02-budgets-maintained-by-hand-in-three-places.md); [P-01 Meta pacing sheet is broken – Supermetrics connector failing](../problems/p-01-meta-pacing-sheet-is-broken-supermetrics-connector.md); [P-03 No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) |
| Also helps | [P-21 Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) – Solve now; [P-17 Conversion tracking depends on one contractor](../problems/p-17-conversion-tracking-depends-on-one-contractor.md) – Solve later |
| Pain points cited | [MP-PP01](../pain-points/README.md#mp-pp01), [MP-PP02](../pain-points/README.md#mp-pp02), [SD-PP04](../pain-points/README.md#sd-pp04), [SH-PP02](../pain-points/README.md#sh-pp02) |
| Written source | – |
| Cost of inactivity / year | \$15K–\$38K – plus +\$10K per repeat overspend incident; SEO share moved to DS-22 |
| Build cost | Free |
| Monthly | US\$779/month (US\$1M tier, annual); Enterprise quote if 100+ ad accounts |

## Vision

> **A PPC manager can look after more clients and channels because they only react to what's flagged, instead of constantly checking accounts.**
>
> - **Daily pacing checks** that alert the team when a client is off pace.
> - **Custom metric checks every morning** – each client's own KPIs and thresholds.
> - **Event alerts to Slack** when certain things happen in an account.
> - **Alerts go to a Slack channel and @mention the account owner** (owner taken from the client's Monday item).
> - **Phase 2 option:** overspend protection / auto-pacing (the tool adjusts daily budgets itself). Phase 1 is alerts only.
>
> Tool being looked at: **Adpulse** – covers every channel incl. LinkedIn, pacing, custom metric monitors and Slack alerts; **event/anomaly alerts checked 9 Nov (vendor docs):** yes to user-set spike/drop alerts (% or fixed threshold, own comparison window, per account or tag, on CTR, clicks, cost, CPC, CPA, conversions, conv. rate, value); partly for account events (broken URLs, paused accounts, disapproved ads, campaigns that stop serving are listed; billing failures, feed problems, tracking stopping and budget edits are not documented – a zero-conversions spike/drop rule likely covers tracking breaks); Slack delivery yes, but channel choice, @mentions per owner and real-time vs daily digest are not documented – **confirm in a demo**; which alerts work on which channels is not documented. Pricing is by trailing 30-day ad spend: the US\$1M tier is US\$779/month (annual) and covers up to 100 ad accounts, Aperitif's spend is \~A\$1.2M/month (\~US\$0.78M at A\$1 = US\$0.65), which fits the US\$1M tier (US\$779/month annual) on spend – but with 100+ ad accounts it likely needs Enterprise (custom quote). Confirm the account count in the demo. 14-day free trial. Link: ([adpulse.app](http://adpulse.app)).

## Pricing & priority

> **Priority: Quick win · Impact 5 / 5 · Effort 3 / 5**
>
> | Option | Build cost | Monthly cost |
> | --- | --- | --- |
> | **Recommended – Adpulse** (has native Slack integration; no build) | A\$0 – software only | US\$779/month (US\$1M spend tier, annual) – Enterprise quote if 100+ ad accounts |
> | **Smaller option – modernise the existing pacing bot** (won't get the full Adpulse unlock) | A\$1,250 | A\$300/month management |

**Your decision (9 Nov):** a modern ad budget pacing tool that connects to **every live channel**, tracks pace and performance per client against **thresholds set per client** by the team, and sends **Slack alerts**.

- **Alerts only for now** – no automated actions (pause/scale); budget changes stay manual.
- **Ownership:** Austin owns it technically; the business (account managers / performance lead) owns data validity – correct budgets, thresholds and channel lists.

## What it does

| Capability | Detail |
| --- | --- |
| Pacing | One budget per client entered once; spend pulled automatically from every live channel incl. LinkedIn; daily pace vs budget; automatic month rollover |
| Performance thresholds | Per-client thresholds on CPA, CPL, ROAS, conversions, CTR, frequency etc. |
| Alerts | Slack alerts on over/under-pace and threshold breaches – managers open an account when flagged |
| Actions | None automated for now (phase 2 option) |

## Opportunities it covers

- **[O-01](../opportunities/README.md#o-01)** Restore the pacing data feed and cover every live channel – rank 1, priority 125, quick win (7–19 h/month)
- **[O-11](../opportunities/README.md#o-11)** Pacing tracker reads budgets and spend, flags gaps – rank 11, 75 (10–21 h/month)
- **[O-15](../opportunities/README.md#o-15)** Enter budgets once, log every change, written overspend policy – rank 15, 64 (1–4 h/month)
- **[O-10](../opportunities/README.md#o-10)** Switch on native platform alert rules and scripts now – rank 10, 75 (1–8 h/month) – *interim step while the tool is chosen*
- **[O-12](../opportunities/README.md#o-12)** Cross-account performance monitor with draft diagnosis – rank 12, 75 – **the paid part only**. The SEO part (weekly GA4 / Search Console / Ahrefs digest) is now its own SEO-team solutions: [DS-22](ds-22-seo-automated-monday-client-performance-check.md), [DS-23](ds-23-seo-drop-and-anomaly-alerts.md), [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md) (your call, 9 Nov).
- Your earlier ideas: *Pacing tracker + adjustment engine* and *Proactive PPC monitor and anomaly detector*

Hours overlap between these, so they can't simply be added: indicative combined saving **\~16–40 h/month (\$1.3K–\$3.2K)**, assumed (SEO team's share moved to [DS-22](ds-22-seo-automated-monday-client-performance-check.md)), plus protection against repeats of the **\$10K overspend credit**.

## Problems it fixes and the evidence

- [Budgets maintained by hand in three places; some channels (incl. LinkedIn) not tracked; a missed budget change cost a \$10K credit](../problems/p-02-budgets-maintained-by-hand-in-three-places.md) – Critical. 3 staff + 1 leadership. *"The budget would change and they wouldn't update the sheet. So the trackers are tracking. but it's on the wrong number."* – leadership ([MP-PP01](../pain-points/README.md#mp-pp01)). A \$10K credit was paid on one incident (stated).
- [Meta pacing sheet is broken – Supermetrics connector failing](../problems/p-01-meta-pacing-sheet-is-broken-supermetrics-connector.md) – Critical. 3 staff. *"we have to manually input like the ad account ID and the name and the budgets. And then it's not always pulling correctly."* – a performance manager ([SH-PP02](../pain-points/README.md#sh-pp02)). The performance director fills the Meta sheet by hand daily.
- Channels beyond Google and Meta (LinkedIn, TikTok, Criteo, Pinterest, ChatGPT ads) have no pacing at all – 1 staff + 1 leadership ([C-03](../synthesis/clusters-and-root-causes.md#c-03), part of the budgets problem). *"I probably should set up a pacing track with the LinkedIn and then bang, this happens."* – leadership ([MP-PP02](../pain-points/README.md#mp-pp02)).
- [No proactive performance alerting – problems found at month-end](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) – High. **7 staff**, the widest raise in paid media. *"if I'm not in the account, then there's no way of knowing."* – a performance manager ([SD-PP04](../pain-points/README.md#sd-pp04)).
- Also helps: [Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) (alerts mean checking accounts only when flagged) and, later, [Conversion tracking depends on one contractor](../problems/p-17-conversion-tracking-depends-on-one-contractor.md) (a conversion-drop alert catches tracking breaks early).

## Smaller option: modernise the existing pacing bot (9 Nov)

A lighter, cheaper version for Joe to choose instead of Adpulse: **keep and upgrade the current set-up** (the M/W/F pacing bot and the pacing sheets) rather than buy a new tool.

- Fix the data feed (renew or replace the failing Supermetrics connector) and name one owner for it.
- Add the missing channels (LinkedIn first, then TikTok, Criteo, Pinterest, ChatGPT ads) as far as the feed allows.
- Run pacing **daily** instead of Monday/Wednesday/Friday.
- Send alerts to a Slack channel and @mention the account owner.
- Enter budgets once, with changes logged.

> **This won't get the full unlock that Adpulse would.** No custom metric checks or spike/drop alerts across every channel, no portfolio dashboard, no event alerts (disapprovals, stopped campaigns), no auto-pacing later – and it stays a home-built tool that depends on one person to keep running (key-person risk, [DS-10](ds-10-systems-register-and-break-fix-runbook.md)). It fixes pacing; it doesn't let managers run more clients by reacting only to alerts.

## Build vs buy – how hard is a custom build to run? (9 Nov)

**Recommendation: buy (Adpulse, pending demo); build only a thin layer for any gaps.** A custom all-channel pacing and alerting tool is a lot for one person to build and keep running:

| What a custom build has to handle | Why it's heavy |
| --- | --- |
| A separate API for every channel (Google, Meta, Microsoft, LinkedIn, TikTok, Pinterest, Reddit, ChatGPT ads) | Each has its own data model, rate limits and login tokens to keep refreshed |
| Access approval per platform | LinkedIn's ad API needs a manual partner review, reported as weeks to months; Google now needs brand verification for API access |
| Constant API changes | Google releases a new Ads API version every 3–4 months and switches old versions off about a year after release, so code must be upgraded several times a year; other platforms change on their own schedules |
| Being the on-call fixer | If a feed breaks, pacing stops – the same key-person risk as today's Supermetrics and Make set-up ([DS-10](ds-10-systems-register-and-break-fix-runbook.md)) |

Adpulse already covers every channel, pacing, spike/drop alerts and Slack. A thin layer could still be built on its API (or Slack) if the demo shows gaps – e.g. @mentioning the owner, or sending alerts to the [DS-27](ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md) investigator.

**Questions for the Adpulse demo:**

1. Can a Slack alert go to a chosen channel and @mention the account owner?
2. Are alerts real-time, or only a daily digest?
3. Which alert types (spikes/drops, disapprovals, stopped serving) work on LinkedIn, Meta and the other channels, not just Google?
4. Can it alert on billing failures, feed problems, budget edits and tracking stopping (zero conversions)?
5. Price for \~A\$1.2M/month (\~US\$0.78M) spend and 100+ ad accounts – does it fit the US\$1M tier or need Enterprise? HubSpot budget sync.

## What the build-vs-buy research shows (9 Nov)

- **Bïrch (formerly Revealbot)** runs rules across Meta, Google Ads, TikTok and Snapchat, checking roughly every 15 minutes. **It does not list LinkedIn**, which has no pacing line today ([MP-PP02](../pain-points/README.md#mp-pp02)). Automated rules need the Pro plan (US\$99/month at low spend); pricing scales with total connected ad spend. At Aperitif's \~A\$1.2M/month (Google \~A\$788K + Meta \~A\$422K) it would be an enterprise quote.
- **Pacing-specific SaaS that does include LinkedIn** exists – e.g. [Shape.io](http://Shape.io) (Google, Meta, Microsoft, LinkedIn, X, Pinterest, TikTok), Pace, Adpulse, ReportGarden, BuyerBridge. Worth pricing at least one against the custom build before committing.
- **Implication for your decision:** because it must cover *every* channel, Bïrch alone doesn't fit (no LinkedIn). The choice is between an all-channel pacing SaaS ([Shape.io](http://Shape.io), Pace, Adpulse – check each for Slack alerts and per-client thresholds) and a custom build. **Recommended: Adpulse – see Pricing & priority.**

## Future state (draft)

1. Budgets agreed with the client are entered **once**, with every change logged and dated.
2. Spend from every live channel is pulled automatically each day; nobody fills a sheet by hand.
3. The tracker shows pace vs budget per client and channel and alerts on Slack when a client is over or under pace beyond the team's threshold.
4. Team-set performance thresholds (CPA, conversions, ROAS etc.) trigger alerts, so managers open an account when it's flagged rather than checking every account.
5. No spend goes live on a channel without a pacing line.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| % of live channels with a pacing line | Below 100% – LinkedIn and others missing (MP-O01) | 100% |
| Days pacing data refreshes automatically | 0 – filled by hand (SD-O01) | 100% of working days |
| Overspend credits paid to clients | \$10K on one incident ([MP-PP01](../pain-points/README.md#mp-pp01)) | \$0 |
| Performance drops caught before month-end | Unknown – found in manual checks ([SD-PP04](../pain-points/README.md#sd-pp04)) | Alert within 24–48 h |

## Cost of inactivity (COI)

|  | Per month | Per year |
| --- | --- | --- |
| Staff time spent on pacing and monitoring today | 63–140 h (\$5.1K–\$11.2K) | \$61K–\$134K |
| Of which recoverable with this solution | \~16–40 h (\$1.3K–\$3.2K) | **\$15K–\$38K** |
| Overspend exposure | One \$10K credit already paid on an untracked/mis-paced channel | **+\$10K per repeat incident** |

Also at risk, not quantified: performance drops and tracking breaks found at month-end rather than within days (7 staff raised this) – a retention risk.

*Basis: process costs from the Stage 2 roll-up (pacing & budget management 50–101 h; performance monitoring 13–39 h); recoverable hours from [O-01](../opportunities/README.md#o-01), [O-11](../opportunities/README.md#o-11), [O-15](../opportunities/README.md#o-15), [O-10](../opportunities/README.md#o-10) and the paid part of [O-12](../opportunities/README.md#o-12) with overlap removed (the SEO team's [O-12](../opportunities/README.md#o-12) sources LS-O03 and ZC-O03, 3.6–10.2 h, moved to [DS-22](ds-22-seo-automated-monday-client-performance-check.md)). Assumed – only \~4% of these hours rest on stated times. \$80/hr internal rate.*

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- Hours saved are assumed; the transcripts gave few stated times.
- The channel list (LinkedIn, TikTok, Criteo, Pinterest, ChatGPT ads) comes from one interview (WS-O01) – confirm the live channel list per client.
- Bïrch facts from its pricing page and reviews, Nov 2026; LinkedIn support not listed.
- Supermetrics is connected but failing, not cancelled (contradiction [X-01](../synthesis/contradictions.md#x-01)).

## Open questions for you

- Build vs buy: shortlist one all-channel pacing SaaS to price against a custom build (Claude can compare [Shape.io](http://Shape.io) / Pace / Adpulse on channels, Slack alerts, per-client thresholds and price when you're ready).
- Indicative build cost and OpEx (yours to set).

## Decided

- One tool, all channels · per-client thresholds · Slack alerts only · Austin = technical owner, business = data validity.
