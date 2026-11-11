---
id: DS-30
title: "Daily priorities assistant: one triaged list per person from Monday, Slack, email, calendar, ad/SEO performance and seasonal signals"
team: "everyone"
bundle: "Team productivity"
status: "Added – priced"
coverage: addressed
source_type: "mixed"
opportunities: ["O-29 (daily brief part)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-16"]
problems_also_helped: ["P-21"]
problems_related_only: []
pain_points_cited: ["MC-PP03", "SB-PP01", "SB-PP02"]
pain_points_interviewer_raised_or_inferred: []
value: "Focus each morning"
---

# DS-30 · Daily priorities assistant

*Everyone: one triaged daily priority list per person from Monday, Slack, email, calendar, performance and seasonal signals, sent as a Slack DM.*

| | |
| --- | --- |
| Bundle | [Team productivity](README.md#bundle-team-productivity) |
| Team | everyone |
| Status | Added – priced |
| Source type | mixed – Austin addition: all-sources daily list (calendar, ad/SEO flags, seasonal); evidence SB-PP01, SB-PP02, MC-PP03; O-29 daily brief |
| Opportunities | [O-29](../opportunities/README.md#o-29) (daily brief part) |
| Earlier ideas | – |
| Fixes | [P-16 Reminders go unacted; a broken reminder bot went unnoticed](../problems/p-16-reminders-go-unacted-a-broken-reminder-bot.md) |
| Also helps | [P-21 Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) – Solve now ("also helps (partly)" – the right work surfaces first) |
| Pain points cited | [MC-PP03](../pain-points/README.md#mc-pp03), [SB-PP01](../pain-points/README.md#sb-pp01), [SB-PP02](../pain-points/README.md#sb-pp02) |
| Written source | – |
| Value | Focus each morning |

**Team:** everyone. **Decision (9 Nov):** a solution of its own, alongside [DS-06](ds-06-request-sweeper-stray-slack-dm-and-email.md).

## Vision

> **The thing that keeps people efficient so they can just focus on work.** Every morning each person gets one triaged list of what to do today, pulled from everywhere work comes from: Monday, Slack, email, calendar, ad and SEO performance, seasonal events – anything and everything.

## How it works

1. Each morning the assistant gathers, per person:
   - Monday tasks due, overdue or newly assigned;
   - Slack messages and email threads waiting on them (incl. client replies);
   - today's calendar (meetings and the prep they need – brief from [DS-04](ds-04-ai-client-brain.md));
   - performance flags for their clients ([DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-22](ds-22-seo-automated-monday-client-performance-check.md), [DS-23](ds-23-seo-drop-and-anomaly-alerts.md), [DS-29](ds-29-ppc-automated-monday-client-performance-check.md));
   - seasonal and trend items due for action ([DS-16](ds-16-seasonal-and-trending-content-radar-per-client.md));
   - link drops to chase ([DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md)), churn or growth alerts ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)).
2. It ranks them into a short suggested priority list – what must happen today, what can wait – with one-click links.
3. Sent as a **Slack DM** from the agent each morning; the person can reply to reorder, snooze or turn an item into a task.

## Problems it fixes and the evidence

- [Reminders go unacted; a broken reminder bot went unnoticed](../problems/p-16-reminders-go-unacted-a-broken-reminder-bot.md):
  - *"I still miss out on things that I need to do, like emails that I need to respond to"* – Sid Bali, Technical SEO Specialist; his own Claude "Organizer" routine doesn't flag what needs action ([SB-PP01](../pain-points/README.md#sb-pp01), stated).
  - About an hour a day on email triage ([SB-PP02](../pain-points/README.md#sb-pp02), stated: *"In a day, an hour."*).
  - Priority field often blank, no forward view of the week ([MC-PP03](../pain-points/README.md#mc-pp03), Michaela Cruz).
- Also helps: [Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) (partly – the right work surfaces first).
- Source: [O-29](../opportunities/README.md#o-29) – AI inbox triage and daily brief across Gmail, Slack and Monday.

## Future state

Nobody starts the day by checking five tools; everyone starts from one list that already knows their tasks, messages, meetings and client alerts.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Minutes a day spent triaging email and messages | \~60 ([SB-PP02](../pain-points/README.md#sb-pp02), one person) | ≤ 15 |
| Tasks overdue > 3 days | Unknown (DM-O03) | −70% |
| Staff using the daily DM | 0 | ≥ 80% |

## Value

**Value: everyone starts the day knowing what matters.** A morning DM pulls together what's due, what's been asked and what's flagged across Slack, Monday and email. How people plan their day is personal, so no hours are claimed – the value is focus and fewer things slipping.

**Problems it eliminates:** helps **P-16** Reminders go unacted · **P-21** Managers at capacity

**Goals:** good performance · good customer service

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Each person connects their own inbox, calendar and DMs (same consent as [DS-06](ds-06-request-sweeper-stray-slack-dm-and-email.md)).
- The ranking needs tuning per role so the list stays short.
