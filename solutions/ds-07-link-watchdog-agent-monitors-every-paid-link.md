---
id: DS-07
title: "Link watchdog agent: monitors every paid link"
team: "link building"  # inferred: the page gives no "Team:" line
bundle: "Link-building CRM"
status: "Decided – tool choice and cost TBC"
ledger_status: addressed
source_type: "mixed"
opportunities: ["O-07 (full)"]
earlier_ideas: []
written_sources: ["WS-ZC-01 Zach Chamberlain \"AI suggestions\" Google Doc"]
problems_fixed: ["P-07"]
problems_also_helped: []
problems_related_only: ["P-06"]
pain_points_cited: ["KO-PP16", "KZ-PP10", "MP-PP13", "TG-PP11", "ZC-PP10"]
pain_points_interviewer_raised_or_inferred: []
coi_per_year: "$10K–$25K"
build_cost: TBC
opex: TBC
notion_section: "Link watchdog agent: monitors every paid link"
---

# DS-07 · Link watchdog agent: monitors every paid link

*Agent that checks every paid link weekly and drafts publisher emails when a link drops.*

| | |
| --- | --- |
| Bundle | [Link-building CRM](README.md#bundle-link-building-crm) |
| Team | link building *(inferred)* |
| Status | Decided – tool choice and cost TBC |
| Source type | mixed – Austin addition: Jev AI as tool option; publisher emails that learn from sent edits |
| Opportunities | [O-07](../opportunities/README.md#o-07) (full) |
| Earlier ideas | – |
| Fixes | [P-07 Paid links disappear after payment – detected manually](../problems/p-07-paid-links-disappear-after-payment-detected-manually.md) |
| Also helps | – |
| Related only | [P-06 Link building runs on 7+ disconnected spreadsheets](../problems/p-06-link-building-runs-on-7-disconnected-spreadsheets.md) – Solve now |
| Pain points cited | [KO-PP16](../pain-points/README.md#ko-pp16), [KZ-PP10](../pain-points/README.md#kz-pp10), [MP-PP13](../pain-points/README.md#mp-pp13), [TG-PP11](../pain-points/README.md#tg-pp11), [ZC-PP10](../pain-points/README.md#zc-pp10) |
| Written source | [Zach Chamberlain – "AI suggestions" Google Doc](https://docs.google.com/document/d/1bsjfs6Aw1F6VOA_nvhWwzPoFv8XHxaXp4Q8UHYAgtsw/edit) (WS-ZC-01) |
| Cost of inactivity / year | \$10K–\$25K |
| Build cost / OpEx | TBC |

## Vision

> **Make sure every paid link stays up, and track the reliability (rep) rate of each provider** – how often their links drop – so the team keeps buying from publishers that hold up. Everything else as written (weekly checks, drop alerts, templated publisher emails that learn from edits).

**Your decision (9 Nov):** an agent that keeps an eye on every paid link. It monitors the publisher websites for changes and checks that each link still meets the requirements: live, not taken down, and whatever else was agreed. It connects to a wider **link-building workflow CRM**. Tool options: **Jev AI** (no output tokens needed, so cheap to run) or another automation method.

## How it works (draft)

1. Every paid link from the link record (CRM) is added to the watch list with its requirements: target URL, anchor text, dofollow, approved domain, and the date it went live.
2. The agent re-checks each page on a schedule and watches for changes.
3. It checks each requirement: page live (not 404), link still present, anchor and target unchanged, still dofollow, still on the approved domain, and domain health (no sudden authority drop or spam signals).
4. When something breaks, it flags the link in the CRM with the evidence (before/after snapshot, date found) and alerts the link team.
5. It asks whether to email the publisher and offers a **draft from the templates**. The employee tailors it and the system sends it.
6. It **learns from the emails that get sent** (the edits people make), so future drafts need less rework.
7. Over time the CRM shows each publisher's track record: how often their links drop, so unreliable publishers can be avoided.

## Opportunities it covers

- **[O-07](../opportunities/README.md#o-07)** Automated live-link checks with publisher replacement claims – rank 7, priority 80, quick win, effort M (5–10 h/month plus avoided loss, assumed)
- Connects to **[O-18](../opportunities/README.md#o-18)** One link record (order template, auto-sync, invoice run), which is the CRM side – now its own solution, [DS-11](ds-11-link-building-workflow-crm.md) (link-building CRM).
- Your earlier idea: a *link monitor* (offered at kick-off).

## Problems it fixes and the evidence

- [Paid links disappear after payment – detected manually](../problems/p-07-paid-links-disappear-after-payment-detected-manually.md) – Solve now. 3 staff + 1 leadership. A one-off check found **about 100 dead links over roughly 10 months**: *"there's like 100 links that just like were no longer working, like 404s or they took them down"* – the link-building lead ([KZ-PP10](../pain-points/README.md#kz-pp10)). *"we have no visibility on whether links stay live or not."* – an SEO manager ([ZC-PP10](../pain-points/README.md#zc-pp10)). *"we don't have a way to currently check whether these are dropping off"* – leadership ([MP-PP13](../pain-points/README.md#mp-pp13)). The outreach specialist isn't sure the current link-status checker is accurate ([TG-PP11](../pain-points/README.md#tg-pp11)).
- [Link building runs on 7+ disconnected spreadsheets](../problems/p-06-link-building-runs-on-7-disconnected-spreadsheets.md) – Solve now. Leadership wants a CRM for the link team: *"That is still being run out of spreadsheets."* ([KO-PP16](../pain-points/README.md#ko-pp16)). The watchdog needs one link list to read from, so it depends on this being fixed (via the CRM).

## Future state (draft)

1. Every paid link is on the watch list from the day it goes live.
2. Drops and changes are caught within days, not found months later in a one-off report.
3. Each drop is logged with evidence and the publisher's record is updated, so the team can claim a replacement and steer away from bad publishers.
4. Nobody checks links by hand.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Paid links verified each week | 0% (MP-O05) | 100% |
| Paid links still live at 90 days | Unknown – \~100 dead found over \~10 months ([KZ-PP10](../pain-points/README.md#kz-pp10)) | ≥ 97% (KZ-O02) |
| Paid links still live at 12 months | Not tracked | 100% – Zach: links should stay live *"for at least 12 months"* (AI suggestions doc) |
| Time from link drop to the team knowing | Months – found in a one-off report | ≤ 7 days |
| Dropped links replaced or refunded | Unknown | Set after baseline |

## Cost of inactivity (COI)

|  | Per month | Per year |
| --- | --- | --- |
| Staff time the link-QA process would need (Stage 2 roll-up) – most of these checks are **not being done today** (0% verified) | 11–36 h (\$0.9K–\$2.9K) | \$10K–\$34K |
| Recoverable staff time | 5–10 h (\$400–\$800) | \$5K–\$10K |
| Money lost on dead paid links | \~10 links × \$80–\$130 = \$0.8K–\$1.3K | \$10K–\$16K |
| **Total recoverable (time + 50–100% of lost links)** | **\$0.8K–\$2.1K** | **\$10K–\$25K** |

Also at risk, not quantified: client SEO results weakened by links that quietly vanish; paying the same unreliable publishers again because nobody tracks their record.

*Basis: process cost from the Stage 2 roll-up (Link building – QA & live checks 10.8–35.7 h). Dead-link rate and price from KZ-P10/KZ-PP10 (estimated: \~100 dead links over \~10 months). Recovery assumed at 50–100%. \$80/hr.*

## Indicative build cost and OpEx

**TBC by Austin.** OpEx: Jev AI or other monitoring/automation runs, plus Ahrefs API for domain health.

## Assumptions

- The dead-link figure comes from one one-off report (\~100 over \~10 months) – the real rate may differ.
- Needs one clean link list with URLs and requirements, so it depends on the CRM / one link record ([O-18](../opportunities/README.md#o-18)).
- Publisher terms must allow replacement claims or refunds for the money to be recovered.
- Jev AI's fit (scale, scheduling, change detection) to be confirmed.

## Decided (9 Nov)

- **When a link drops:** the team is alerted and asked whether to email the publisher. The system drafts the email from templates, the employee tailors it, and the system sends it. It learns from sent emails to cut rework over time.
- **Check frequency:** weekly to start; the cadence is adjustable.
- **The link-building CRM is its own solution** (with [O-18](../opportunities/README.md#o-18)), covered when we reach it. The watchdog reads its link list from the CRM.
- Still open: tool choice (Jev AI or another automation method) and cost – TBC by Austin.
