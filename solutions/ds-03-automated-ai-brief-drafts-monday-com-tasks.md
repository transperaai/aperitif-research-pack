---
id: DS-03
title: "Automated AI brief drafts → Monday.com tasks"
team: "SEO and content"  # inferred: the page gives no "Team:" line
bundle: "SEO performance"
status: "Recommended – build 6, Brief drafts"
coverage: addressed
source_type: "evidence-backed"
opportunities: ["O-03 (full)", "O-25 (full)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-33"]
problems_also_helped: ["P-11", "P-09", "P-32"]
problems_related_only: []
pain_points_cited: ["HT-PP01", "HT-PP02", "LS-PP03", "SJ-PP01", "SJ-PP02", "SJ-PP04", "SJ-PP06", "SJ-PP10", "SJ-PP11", "SJ-PP14", "ZC-PP02", "ZC-PP03"]
pain_points_interviewer_raised_or_inferred: []
value: "12–24 h/mo of content-team time → more words written (~A$12K–23K a year; not counted as MRR)"
value_time_h_month: [12, 24]
---

# DS-03 · Automated AI brief drafts → Monday.com tasks

*AI drafts monthly content briefs from the Master SEO Document and turns each into a Monday task, plus the full content-intake standard.*

| | |
| --- | --- |
| Bundle | [SEO performance](README.md#bundle-seo-performance) |
| Team | SEO and content *(inferred)* |
| Status | Recommended – build 6, Brief drafts |
| Source type | evidence-backed |
| Opportunities | [O-03](../opportunities/README.md#o-03) (full), [O-25](../opportunities/README.md#o-25) (full) |
| Earlier ideas | – |
| Fixes | [P-33 Content briefs are re-cut and reformatted by hand, eating the first half of each month](../problems/p-33-content-briefs-are-re-cut-and-reformatted.md) |
| Also helps | [P-11 Content tracker and link sheets live outside Monday.com](../problems/p-11-content-tracker-and-link-sheets-live-outside.md) – Not in proposal (auto-created Monday tasks (problem not in this proposal)); [P-09 Content delivery hinges on the Content Manager as writer, editor and contractor manager](../problems/p-09-content-delivery-hinges-on-the-content-manager.md) – Solve later; [P-32 Unplanned same-day and high-touch client requests break the planned month](../problems/p-32-unplanned-same-day-and-high-touch-client.md) – Not in proposal (slots and cut-offs for the out-of-cycle client, text only) |
| Pain points cited | [HT-PP01](../pain-points/README.md#ht-pp01), [HT-PP02](../pain-points/README.md#ht-pp02), [LS-PP03](../pain-points/README.md#ls-pp03), [SJ-PP01](../pain-points/README.md#sj-pp01), [SJ-PP02](../pain-points/README.md#sj-pp02), [SJ-PP04](../pain-points/README.md#sj-pp04), [SJ-PP06](../pain-points/README.md#sj-pp06), [SJ-PP10](../pain-points/README.md#sj-pp10), [SJ-PP11](../pain-points/README.md#sj-pp11), [SJ-PP14](../pain-points/README.md#sj-pp14), [ZC-PP02](../pain-points/README.md#zc-pp02), [ZC-PP03](../pain-points/README.md#zc-pp03) |
| Written source | – |
| Value | 12–24 h/mo of content-team time → more words written (\~A\$12K–23K a year; not counted as MRR) |

## Vision

> **The month's work comes straight out of the master sheet and turns into to-dos.** AI reads the content plan in the Master SEO Document, drafts the briefs, and each one becomes a task in Monday for the right person – nobody re-cuts the plan or retypes it into tasks. It also covers content intake and freelancer boards; it starts as a Claude skill and moves to full automation in a second phase.

## Decision

**Decision:** AI generates the monthly brief drafts, and each brief is turned into a task in Monday.com. Phase 1 is a **Claude skill** the SEO manager runs on a short standard form and the client's plan; Phase 2 is the **fully automated** end-to-end version (see Decided).

## How it works

1. Each month the automation reads the content plan in the client's **Master SEO Document**.
2. It drafts each brief in the house template (keywords, structure, internal links, tone, regional/localisation metadata where needed) straight into the standard Google Doc – no copy-paste into Word.
3. The content team reviews and approves the draft (human stays in the loop).
4. On approval, a [**Monday.com**](http://Monday.com) **task** is created automatically for each brief: assigned writer, due date, link to the brief, client, word count.
5. Monday notifies the content manager and writer – no brief sits unseen in a sheet.

## Opportunities it covers

- **[O-03](../opportunities/README.md#o-03)** AI brief drafts from the Master SEO Document – rank 3, priority 100, quick win, effort S
- **[O-25](../opportunities/README.md#o-25)** Content intake on Monday with brief standard and slots – all of it (task creation plus intake) (rank 25; overlaps [O-03](../opportunities/README.md#o-03))

## Problems it fixes and the evidence

- [Content briefs are re-cut and reformatted by hand, eating the first half of each month](../problems/p-33-content-briefs-are-re-cut-and-reformatted.md) – High. 3 staff. *"especially early months, the content briefing is pretty much all of my day or say a few days to a week."* – an SEO manager ([ZC-PP02](../pain-points/README.md#zc-pp02)). *"content briefs; we could have automated those years ago."* – the SEO Director ([LS-PP03](../pain-points/README.md#ls-pp03)). Briefs are copied from Claude into Word and reformatted by hand ([ZC-PP03](../pain-points/README.md#zc-pp03)).
- Briefs arrive unseen or late – 2 content team members ([C-21](../synthesis/clusters-and-root-causes.md#c-21), part of [Content tracker and link sheets live outside Monday.com](../problems/p-11-content-tracker-and-link-sheets-live-outside.md), not in this proposal). *"if it's dropped in on a day that I'm not checking it Maybe it means that I would see it for two days"* – a content team member ([SJ-PP02](../pain-points/README.md#sj-pp02)). Auto-created Monday tasks remove this.
- Also helps (Solve later): [Content delivery hinges on the Content Manager as writer, editor and contractor manager](../problems/p-09-content-delivery-hinges-on-the-content-manager.md) – less routing by hand.

## Future state

Monthly briefs are drafted by AI from the plan that already exists, reviewed by the SEO manager in minutes, and land in Monday.com as assigned tasks with due dates. Nobody re-cuts a plan, reformats a document or chases whether a brief was seen.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Content-team time per brief | \~20 min | \~5–10 min |
| Briefs needing manual reformatting | All – copied into Word (ZC-O02) | 0 |
| Time from brief approved to writer task created | Up to 2 days unseen ([SJ-PP02](../pain-points/README.md#sj-pp02)) | Same day, automatic |

## Value

> **Every brief is clear, consistent and in one place.** The content team fills in a short standard form; the brief is produced automatically from it and the Master SEO Document, sent to Monday as a task, and saved in the client brain – so writers get the same clarity every time.

**1. Time saved**

| Task removed | How it's worked out | Per month |
| --- | --- | --- |
| Writing content briefs | 48 clients receive content × 1.5–2 briefs a month (Austin's estimate) ≈ 72–96 briefs × \~20 min today → \~5–10 min with the form and AI draft | **\~12–24 h** (content team) ≈ A\$12K–23K a year at A\$80/hr |

**2. Capacity and revenue unlocked**

Briefs are written by the content team (Sarah Julian and Hayley Tantau), who are measured on words delivered each month – so the freed time goes into **more words written**, not more clients managed. It isn't counted as MRR capacity.

The bigger win is clarity: briefs often lack it today, so writers go back and forth. A standard form fixes what goes into every brief, and drafts can be out on day one of the month instead of waiting on the form.

**3. Problems it eliminates**

- **P-33** Content briefs are re-cut and reformatted by hand, eating the first half of each month
- **P-11** Content tracker and link sheets live outside Monday.com
- Helps: **P-09** Content delivery hinges on the Content Manager · **P-32** Unplanned requests break the planned month

**Goals:** good customer service · good performance · trust

*Inputs from Austin: \~20 min per brief today, often lacking clarity; 1.5–2 briefs per client a month; standardise with a form, produce automatically, save in the brain. Assumption: \~5–10 min per brief with the form.*

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- Hours saved assumed.
- Needs **one current brief template** ([C-20](../synthesis/clusters-and-root-causes.md#c-20)) and, for best output, per-client context (tone, compliance), which comes later from the AI brain / per-client record ([O-04](../opportunities/README.md#o-04)).
- The Master SEO Document structure is consistent enough across clients to be read automatically – checked on 2–3 clients first.
- The Monday.com integration builds on the existing Make set-up, whose gaps sit with the Technical SEO Specialist ([C-31](../synthesis/clusters-and-root-causes.md#c-31)).

## Decided

- **Phase 1: a Claude skill** – the SEO manager runs it on the standard form and the client's plan and gets briefs back in the standard template. **Phase 2: full automation** – at the start of the month a Make scenario reads the plan rows marked for this month and the matching forms, drafts each brief, posts drafts for approval, then creates the Monday task for the writer and saves the brief to the client brain.
- **Monday tasks go to anyone on** [**Monday.com**](http://Monday.com), including freelancers who are on it. For freelancers not on Monday, the finished brief can be **exported ready to send**.

## The rest of O-25 (content intake)

**Decision:** fold the rest of [O-25](../opportunities/README.md#o-25) into this solution.

| Part | What it does |
| --- | --- |
| Minimum brief standard | Every brief carries context, prior client feedback, sources, compliance rules and due date – the AI draft fills these from the client brain ([DS-04](ds-04-ai-client-brain.md)) where it can |
| Rule-based assignment | Briefs are assigned to a writer or freelancer by rule (client, tier, capacity); the content team confirms; Monday alerts the writer |
| Freelancer boards | Freelancers on their own Monday boards with guest access – no more copying briefs into four freelancer sheets |
| Slots and cut-offs | Late briefs roll into a defined slot; freelancer due dates staggered; the out-of-cycle client gets a reserved allowance and a cut-off |
| Auto-filing | Freelancer and edited versions filed to the client folder automatically |
| Priority order | Work sorted by client importance, not sheet age |

**Evidence (content team – 16 pain points):** the content manager copies every brief, prior comms and feedback by hand into four freelancer sheets – her magic-wand pick: *"I copy all of the briefs and the… feedback or like any like prior… comms"* ([SJ-PP01](../pain-points/README.md#sj-pp01), stated). Volume grew from \~40K to \~100K words a month: *"as we grow it's not going to be like sustainable"* ([SJ-PP11](../pain-points/README.md#sj-pp11)). Incomplete briefs drive freelancer rework ([SJ-PP06](../pain-points/README.md#sj-pp06)); work is *"just sorted by age"* not importance ([SJ-PP10](../pain-points/README.md#sj-pp10)); edited versions are filed by hand ([SJ-PP04](../pain-points/README.md#sj-pp04)); the end of the month is *"often crunchy"* ([HT-PP01](../pain-points/README.md#ht-pp01)); one client sits outside the cycle and sends last-minute work ([HT-PP02](../pain-points/README.md#ht-pp02), [SJ-PP14](../pain-points/README.md#sj-pp14)).

**Assumptions:** freelancers accept Monday guest boards; the content manager agrees the assignment rules and slot calendar.
