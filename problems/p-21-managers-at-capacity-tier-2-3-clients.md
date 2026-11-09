---
id: P-21
title: "Managers at capacity – Tier 2/3 clients get dropped first"
austin_call: "Solve now"
austin_note: "We need to reduce the amount of effort required to manage t2 and t 3 clients, and also have better optics and observability"
status: partly_addressed
fixed_by: []
also_helped_by: ["DS-01", "DS-05", "DS-06", "DS-30"]
related_only: []
clusters: ["C-17"]
root_causes: ["RC-05"]
pain_points: ["DM-PP10", "KO-PP09", "KO-PP26", "LS-PP01", "LS-PP02", "MC-PP09", "MC-PP18", "MP-PP18", "MP-PP19", "MP-PP21", "SB-PP13", "SD-PP07", "SD-PP08", "SH-PP09", "WS-PP01"]
theme: "Process / automation"
severity: "High"
confidence: "High – raised by 3+ people"
notion_id: 40fe204ff76981208c95f2a96063afd7
---

# P-21 · Managers at capacity – Tier 2/3 clients get dropped first

| | |
| --- | --- |
| Austin's call | **Solve now** |
| Austin's note | We need to reduce the amount of effort required to manage t2 and t 3 clients, and also have better optics and observability |
| Status | partly addressed – Solve now; no DS fixes it – only "also helps" by [DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md), [DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md), [DS-30](../solutions/ds-30-daily-priorities-assistant-one-triaged-list-per.md) ([DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md): "also helps (partly)"; capacity not solved – [O-17](../opportunities/README.md#o-17)/O-19/O-32 dropped) ([DS-30](../solutions/ds-30-daily-priorities-assistant-one-triaged-list-per.md): "also helps (partly)" – the right work surfaces first) |
| Theme · severity · confidence | Process / automation · High · High – raised by 3+ people |
| Process area | Delivery / ops |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Also helps: [DS-01 Modern ad budget pacing + performance alerting](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md)
- Also helps: [DS-05 Automated deck generator: quarterly + 6-month reviews and proposals](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md) – "also helps (partly)"; capacity not solved – O-17/O-19/O-32 dropped
- Also helps: [DS-06 Request sweeper ("Roomba"): stray Slack, DM and email requests → Monday.com](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md)
- Also helps: [DS-30 Daily priorities assistant: one triaged list per person from Monday, Slack, email, calendar, ad/SEO performance and seasonal signals](../solutions/ds-30-daily-priorities-assistant-one-triaged-list-per.md) – "also helps (partly)" – the right work surfaces first

## Opportunities linked in Notion

- [O-05](../opportunities/README.md#o-05) Reports and review decks: auto-filled data, AI-drafted narrative – partly addressed ([DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md))
- [O-06](../opportunities/README.md#o-06) All internal requests via Monday forms; Monday notifies, not people – partly addressed ([DS-06](../solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md))
- [O-10](../opportunities/README.md#o-10) Switch on native platform alert rules and scripts now – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [O-12](../opportunities/README.md#o-12) Cross-account performance monitor with draft diagnosis (paid and SEO) – addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-27](../solutions/ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md), [DS-29](../solutions/ds-29-ppc-automated-monday-client-performance-check.md), [DS-22](../solutions/ds-22-seo-automated-monday-client-performance-check.md), [DS-23](../solutions/ds-23-seo-drop-and-anomaly-alerts.md), [DS-24](../solutions/ds-24-seo-mid-month-wins-sent-to-clients.md))
- [O-13](../opportunities/README.md#o-13) AI per-client summary for reports, calls and data questions – absorbed ([DS-04](../solutions/ds-04-ai-client-brain.md))
- [O-17](../opportunities/README.md#o-17) Cap concurrent onboardings per manager; protect BAU time – dropped
- [O-19](../opportunities/README.md#o-19) Effort model: hours per client, load triggers, rebalanced books – dropped
- [O-21](../opportunities/README.md#o-21) Delegation and triage rules for escalations and sign-offs – absorbed ([DS-14](../solutions/ds-14-client-health-and-growth-intelligence-anti-churn.md))
- [EI-02](../opportunities/README.md#ei-02) AI Business Brain – addressed ([DS-15](../solutions/ds-15-ai-business-brain-the-umbrella.md))
- [EI-15](../opportunities/README.md#ei-15) Proactive PPC monitor and anomaly detector – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-29](../solutions/ds-29-ppc-automated-monday-client-performance-check.md))

## Root cause and cluster

- Cluster [C-17](../synthesis/clusters-and-root-causes.md#c-17): Managers are at capacity, so lower-tier clients and account hygiene slip first – raised by 7 staff + 2 leadership; confidence High.
- Root cause [RC-05](../synthesis/clusters-and-root-causes.md#rc-05): There is no effort model: time per client isn't measured, scope and onboardings aren't checked against capacity, and intake isn't triaged – so work is sold, priced and scheduled by feel.
- Problems DB root cause: Client loads of 12–14 per manager plus ad hoc work, with no capacity model.
- Merge notes: Stage 1 merge (6 Nov): Confirm → [C-17](../synthesis/clusters-and-root-causes.md#c-17) (7 staff + 2 leadership – widest raise). Root cause and quotes below are pre-merge document evidence; Stage 1 root cause and anonymised quotes are in the page body.

## Pain points (15)

- [DM-PP10](../pain-points/README.md#dm-pp10) – \~20-client portfolio; overloaded when several clients want things the same day
  - *"what if like, you know, five or six clients come to you on a single day and ask you for like so much of things."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~08:41 (L106)](../interviews/dm-diya-manoj/transcript.md?plain=1#L109)
- [KO-PP09](../pain-points/README.md#ko-pp09) – A new starter takes about 90 days to reach capacity and DLER takes a hit meanwhile; hiring is slow when work is won in a burst
  - *Joe: "the ramp is, like, 90 days for a new starter"* – Joe Romeo, Leadership (kick-off) · staff-raised · [\~44:27 (L225)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L261)
- [KO-PP26](../pain-points/README.md#ko-pp26) – Team capacity is too tight to log time for a two-week time-and-motion study
  - *Julia: "I think you'd be hard-pressed right now, given the team's capacity as well."* – Julia Van Der Linden, Leadership (kick-off) · staff-raised · [\~88:54 (L417)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L474)
- [LS-PP01](../pain-points/README.md#ls-pp01) – Laura is near capacity because of the team load, so she cannot hand over smaller clients until hires land
  - *"I've still got a few smaller clients that it would be good to hand over, but I'm nearing capacity so I can't yet."* – Laura Shillington, SEO Director · staff-raised · [\~01:20 (L003)](../interviews/ls-laura-shillington/transcript.md?plain=1#L6)
- [LS-PP02](../pain-points/README.md#ls-pp02) – Smaller clients take disproportionate time (her top day-to-day annoyance)
  - *"having the smaller clients. I need to handle them, and I spend too much time on them."* – Laura Shillington, SEO Director · staff-raised · [\~20:17 (L080)](../interviews/ls-laura-shillington/transcript.md?plain=1#L98)
- [MC-PP09](../pain-points/README.md#mc-pp09) – Own low-tier client optimisation squeezed to \~2 days/week; block taken by overflow tasks
  - *"two days in a week. So majority would be the tasks."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~04:12 (L050)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L53) · Austin: Agree
- [MC-PP18](../pain-points/README.md#mc-pp18) – Google Merchant Center / Partner checks not done for \~3 weeks
  - *"I haven't checked Google Merchant Center for like three weeks now. So that's kind of an issue as well."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~06:10 (L061)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L64)
- [MP-PP18](../pain-points/README.md#mp-pp18) – Growth depends on hiring; each hire feels like a risk
  - *"So when I keep hiring people, I feel like I'm just taking a little bit of risk."* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~10:31 (L114)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L117)
- [MP-PP19](../pain-points/README.md#mp-pp19) – Pushing for higher performance risks attrition
  - *"now with this next generation, they just quit, man."* – Joe Romeo, Leadership (mid-point) · staff-raised · [\~27:44 (L313)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L316)
- [MP-PP21](../pain-points/README.md#mp-pp21) – SEO revenue per employee hard to lift because value is human writing
  - *"A lot of your value proposition is based on human writing … So it's very hard to increase revenue per employee there."* – Joe Romeo, Leadership (mid-point) · interviewer-raised · [\~02:45 (L034, Austin)](../interviews/mp-leadership-mid-point/transcript.md?plain=1#L37)
- [SB-PP13](../pain-points/README.md#sb-pp13) – Client communications would break first if end-to-end load grows; already 'borderline'
  - *"It's the client side where I will definitely be lacking."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~23:24 (L338)](../interviews/sb-sid-bali/transcript.md?plain=1#L342)
- [SD-PP07](../pain-points/README.md#sd-pp07) – At full capacity; ad hoc work and pitches push out BAU; Tier 2/3 dropped first
  - *"the first set of clients that take a hit in performance or get neglected are those tier 3, tier 2 clients"* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~12:35 (L110)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L117) · Austin: Agree
- [SD-PP08](../pain-points/README.md#sd-pp08) – SQR hygiene not done monthly because of capacity
  - *"ideally should be done every month but again depends on our time and capacity"* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~50:17 (L504)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L511)
- [SH-PP09](../pain-points/README.md#sh-pp09) – 24-hour email standard means comms crowd out strategy implementation as the portfolio grows
  - *"Based on the 24-hour turnaround time, I would have to focus on the comms, which then... would lead to not implementing the strategies."* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~34:59 (L334–L335)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L334) · Austin: Agree
- [WS-PP01](../pain-points/README.md#ws-pp01) – Director's own channel load nearly doubled (≈10 → 18) on 4 clients since July with no extra resource; own portfolio squeezed
  - *"But then I went from managing probably like 10 channels to like 18."* – Wendlley Simoes, Performance Marketing Director · staff-raised · [\~06:35 (L102)](../interviews/ws-wendlley-simoes/transcript.md?plain=1#L107)

## Best quotes and figures (Problems DB)

Shrishti: 14 clients across 24 channels, at full capacity; "Tier 2 and 3 accounts are the first to be deprioritized". Laura: 12 clients, "stretched because of extra responsibilities".
