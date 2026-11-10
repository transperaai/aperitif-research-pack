---
id: DS-06
title: "Request sweeper (\"Roomba\"): stray Slack, DM and email requests → Monday.com"
team: "everyone"  # inferred: the page gives no "Team:" line
bundle: "Team productivity"
status: "Decided – priced"
ledger_status: addressed
source_type: "mixed"
opportunities: ["O-06 (capture part)", "O-29 (inbox triage part (daily brief moved to DS-30))"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-16", "P-36"]
problems_also_helped: ["P-21", "P-32"]
problems_related_only: []
pain_points_cited: ["DM-PP09", "LS-PP14", "MC-PP04", "MC-PP05", "MP-PP05", "MP-PP06", "SB-PP01", "SB-PP02", "SB-PP03", "SB-PP04", "SB-PP15"]
pain_points_interviewer_raised_or_inferred: ["MP-PP06 (interviewer-raised)"]
value: "Nothing gets missed"
build_cost: "A$500"
monthly: "A$150/month + tokens ~US$30–120"
notion_section: "Request sweeper (\"Roomba\"): stray Slack, DM and email requests → Monday.com"
---

# DS-06 · Request sweeper ("Roomba"): stray Slack, DM and email requests → Monday.com

*Request sweeper that turns stray Slack, DM and email requests into Monday tasks, plus a task-status sweep (daily priorities moved to DS-30).*

| | |
| --- | --- |
| Bundle | [Team productivity](README.md#bundle-team-productivity) |
| Team | everyone *(inferred)* |
| Status | Decided – priced |
| Source type | mixed – Austin addition: DM and email sweeping ("Roomba"); one interview (SB-PP04) confirms DMs as a request route |
| Opportunities | [O-06](../opportunities/README.md#o-06) (capture part), [O-29](../opportunities/README.md#o-29) (inbox triage part (daily brief moved to DS-30)) |
| Earlier ideas | – |
| Fixes | [P-16 Reminders go unacted; a broken reminder bot went unnoticed](../problems/p-16-reminders-go-unacted-a-broken-reminder-bot.md); [P-36 Internal task briefs from managers to implementers are slow to write and often incomplete](../problems/p-36-internal-task-briefs-from-managers-to-implementers.md) |
| Also helps | [P-21 Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) – Solve now; [P-32 Unplanned same-day and high-touch client requests break the planned month](../problems/p-32-unplanned-same-day-and-high-touch-client.md) – Not in proposal (via cluster C-18 in text) |
| Pain points cited | [DM-PP09](../pain-points/README.md#dm-pp09), [LS-PP14](../pain-points/README.md#ls-pp14), [MC-PP04](../pain-points/README.md#mc-pp04), [MC-PP05](../pain-points/README.md#mc-pp05), [MP-PP05](../pain-points/README.md#mp-pp05), [MP-PP06](../pain-points/README.md#mp-pp06) (interviewer-raised), [SB-PP01](../pain-points/README.md#sb-pp01), [SB-PP02](../pain-points/README.md#sb-pp02), [SB-PP03](../pain-points/README.md#sb-pp03), [SB-PP04](../pain-points/README.md#sb-pp04), [SB-PP15](../pain-points/README.md#sb-pp15) |
| Written source | – |
| Value | Nothing gets missed |
| Build cost | A\$500 |
| Monthly | A\$150/month + tokens \~US\$30–120 |

## Vision

> **The sweeper keeps the AI brain's information fresh, not stale.**
>
> - It catches stray requests from Slack, DMs and email and puts them into Monday, so the brain ([DS-04](ds-04-ai-client-brain.md)) always knows what's been asked.
> - **Task status sweep (added 9 Nov):** the brain also sweeps Monday to check whether tasks are actually done, based on due dates and overdue dates – it flags tasks that look finished but aren't closed, tasks past due with no update, and "awaiting approval" items nobody moved ([DM-PP09](../pain-points/README.md#dm-pp09)), and nudges the owner.
> - The **daily priorities** assistant is now its own solution, **[DS-30](ds-30-daily-priorities-assistant-one-triaged-list-per.md)** (Austin's call: "another thing").

## Pricing & priority

> **Priority: Strategic build · Impact 4 / 5 · Effort 4 / 5 (draft – confirm)**
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **Request sweeper + task-status sweep** – connected to the AI brain (runs on the [DS-04](ds-04-ai-client-brain.md) platform) | **A\$500** | **A\$150/month**  • AI tokens \~US\$30–120/month |

**Decision (9 Nov):** Slack stays for instant call-outs, but requests sent there get lost. A "Roomba"-style sweeper picks up the stray requests – including the many sent in **direct messages** and **email** – and puts them into Monday.com as tasks.

## How it works (draft)

1. The sweeper watches Slack channels, DMs and email inboxes. Channels are preferred, but DMs and email are swept too, because that's where many requests land.
2. AI spots messages that are actually requests ("can you…", "need this by…", a change to an account) and ignores chat.
3. For each request it drafts a Monday task: requester, assignee, client/account, what's needed, due date, links – and flags any missing fields (budget, URLs, QA) back to the requester.
4. **Slack:** the task is created automatically there and then, and the sweeper replies in the thread with the task link. **Email:** the sweeper sends the employee a confirm request first, then creates the task.
5. **Every task shows its evidence** – a link to the original Slack message or email and the quoted text it was drawn from – so people can see where the information came from.
6. *(Moved to [DS-30](ds-30-daily-priorities-assistant-one-triaged-list-per.md) – Daily priorities assistant.)* **Daily priority brief (added 9 Nov, [O-29](../opportunities/README.md#o-29)):** each morning the agent sends every person a **Slack DM with their suggested priorities** for the day – what needs action across Gmail, Slack and Monday, client replies waiting, tasks due or overdue – with one-click links. The inbox is also labelled by what matters (respond to client, task request, FYI) and admin notifications are muted.
7. From then on, Monday is the record and does the notifying; Slack is only the call-out.

## Opportunities it covers

- **[O-06](../opportunities/README.md#o-06)** All internal requests via Monday forms; Monday notifies, not people – rank 6, priority 100, quick win – **the capture part**. This solution catches requests where people actually send them rather than relying on everyone using the form.
- **SB-O02** AI inbox triage (the email-request finder from Sid's call) – the email part: spot requests and replies that matter in the inbox and turn requests into tasks.
- **[O-29](../opportunities/README.md#o-29)** AI inbox triage and daily brief across Gmail, Slack, Monday – rank 29, effort M – added 9 Nov: triage labels and a daily suggested-priority DM from the agent.
- **Not included (Austin's call):** [O-06](../opportunities/README.md#o-06)'s Monday request forms (process for process' sake) and replacing the daily agenda channel messages – those messages stay.

## Problems it fixes and the evidence

- [Reminders go unacted; a broken reminder bot went unnoticed](../problems/p-16-reminders-go-unacted-a-broken-reminder-bot.md) ([C-30](../synthesis/clusters-and-root-causes.md#c-30)) – Solve now. Staff + leadership. *"not everybody uses Monday to like, you know, set up a task."* – a technical SEO specialist, who also gets requests by Slack DM and email ([SB-PP04](../pain-points/README.md#sb-pp04), stated). Forwarded email chains take **\~30 minutes each** to untangle ([SB-PP03](../pain-points/README.md#sb-pp03)). Requests in email and Slack slip and become last-minute ([SB-PP01](../pain-points/README.md#sb-pp01)). Leadership: *"Half an hour ago, the reminder went out. We still don't have updates."* ([MP-PP05](../pain-points/README.md#mp-pp05)).
- [Internal task briefs from managers to implementers are slow to write and often incomplete](../problems/p-36-internal-task-briefs-from-managers-to-implementers.md) ([C-27](../synthesis/clusters-and-root-causes.md#c-27)) – Solve now. Requests range from one sentence to a full brief ([LS-PP14](../pain-points/README.md#ls-pp14)); implementers chase account managers for missing details ([MC-PP04](../pain-points/README.md#mc-pp04)); Monday notifications don't always land, so Slack becomes the backup ([MC-PP05](../pain-points/README.md#mc-pp05)). The sweeper's missing-field check addresses this.
- Also helps: [Managers at capacity – Tier 2/3 clients get dropped first](../problems/p-21-managers-at-capacity-tier-2-3-clients.md) – fewer requests lost in DMs and chased later. Partly: same-day ad hoc requests ([C-18](../synthesis/clusters-and-root-causes.md#c-18), not in this proposal) become visible in Monday, even if they're still same-day.
- *Austin's observation:* a lot of the stray requests are in DMs – one interview confirms DMs as a request route ([SB-PP04](../pain-points/README.md#sb-pp04)).

## Future state (draft)

1. Every request that matters ends up as a Monday task, whether it was sent through Monday, a Slack channel or a DM.
2. Nobody has to remember to copy a request into Monday – the sweeper creates the task automatically from Slack; email requests are confirmed by the employee first.
3. Requests with missing details are flagged straight away, not discovered when the work starts.
4. Leadership sees status in Monday, not by chasing in Slack.

## KPIs (draft)

| KPI | Baseline | Target |
| --- | --- | --- |
| Share of internal requests that exist as a Monday task | Unknown – "not everybody uses Monday" ([SB-PP04](../pain-points/README.md#sb-pp04)) | ≥ 90% |
| Time spent untangling a request from email/Slack | \~30 min per chain ([SB-PP03](../pain-points/README.md#sb-pp03), stated) | ≤ 5 min |
| Requests needing a chase for missing details | Unknown – "sometimes" ([MC-PP04](../pain-points/README.md#mc-pp04)) | −50%; baseline to be measured |
| Tasks overdue > 3 days | Unknown (DM-O03) | −70% ([O-06](../opportunities/README.md#o-06)) |

## Value (revised with Austin, 10 Nov)

**Value: nothing gets missed.** Requests that arrive in Slack DMs and email are caught, confirmed and turned into Monday tasks, so work isn't lost or caught last-minute (Sid Bali: "not everybody uses Monday"). This is about capturing what's missed today, not time back – no hours claimed. It protects delivery quality and the client experience, and gives leadership a true picture of the work.

**Problems it eliminates:** **P-16** Reminders go unacted; a broken reminder bot went unnoticed · **P-36** Internal task briefs are slow to write and unclear · helps **P-32** Unplanned requests break the planned month and **P-21** Managers at capacity

**Goals:** good customer service · good performance · trust

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- **DM access is the hard part:** a Slack app can only read a person's DMs if that person authorises it (a user-level permission). Channels are straightforward. Needs staff consent and a clear rule on what the sweeper reads and keeps (ties to the AI-data rule in [DS-02](ds-02-ai-playbook-repository.md)).
- Monday's own Slack integration can already turn a message into a task by hand – the sweeper adds the automatic detection.
- Automatic creation in Slack may produce some junk tasks at first; the evidence link makes them quick to spot and delete. Detection rules get tuned over the first few weeks.
- Email access needs each person's Gmail authorisation, the same as DMs.

## Decided (9 Nov)

- **Channels preferred, DMs accepted:** people are encouraged to post requests in channels, but the sweeper also covers DMs, since that's where many land. Each person connects their DMs and inbox (needs their authorisation).
- **Email included:** it connects to the email-request finder from Sid's call (SB-O02). The technical SEO specialist spends about an hour a day on email triage ([SB-PP02](../pain-points/README.md#sb-pp02), stated), and forwarded chains take \~30 min each to untangle ([SB-PP03](../pain-points/README.md#sb-pp03)).
- **Automatic where possible:** Slack requests become tasks there and then; email requests go to the employee to confirm first. Every task carries its evidence (link to the source + quoted text).
- **No Monday request form and no change to the agenda channel messages** – the sweeper is the whole solution.
