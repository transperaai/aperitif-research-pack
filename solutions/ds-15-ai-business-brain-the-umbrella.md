---
id: DS-15
title: "AI Business Brain – the umbrella (client brains, smart SOPs, one place to ask)"
team: "everyone"  # inferred: the page gives no "Team:" line
bundle: "AI Business Brain"
status: "Decided – framing; cost TBC"
ledger_status: addressed
source_type: "mixed"
opportunities: ["O-27 (company layer)"]
earlier_ideas: ["EI-02 AI Business Brain", "EI-20 Team wiki – fast answers, self-updating, fits into workflows"]
written_sources: []
problems_fixed: ["P-12", "P-13", "P-25", "P-47", "P-48"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["KO-PP10", "KO-PP14", "KO-PP15", "MP-PP04", "MP-PP06", "MP-PP17", "MP-PP20"]
pain_points_interviewer_raised_or_inferred: ["MP-PP06 (interviewer-raised)", "MP-PP17 (interviewer-raised)", "MP-PP20 (interviewer-raised)"]
coi_per_year: "~$44K–$134K combined (DS-02+DS-04+DS-10+DS-14, before overlap); company layer alone $1K–$4K"
build_cost: TBC
opex: TBC
notion_section: "AI Business Brain – the umbrella"
---

# DS-15 · AI Business Brain – the umbrella

*Umbrella for the AI Business Brain (DS-02, DS-04, DS-10, DS-14) plus a company-wide layer; the one home for current templates.*

| | |
| --- | --- |
| Bundle | [AI Business Brain](README.md#bundle-ai-business-brain) |
| Team | everyone *(inferred)* |
| Status | Decided – framing; cost TBC |
| Source type | mixed – Austin addition: umbrella framing grouping DS-02, DS-04, DS-10, DS-14 |
| Opportunities | [O-27](../opportunities/README.md#o-27) (company layer) |
| Earlier ideas | [EI-02](../opportunities/README.md#ei-02) AI Business Brain, [EI-20](../opportunities/README.md#ei-20) Team wiki – fast answers, self-updating, fits into workflows |
| Fixes | [P-12 Documentation is stale and rarely read](../problems/p-12-documentation-is-stale-and-rarely-read.md); [P-13 Documentation and internal tooling held by the founder](../problems/p-13-documentation-and-internal-tooling-held-by-the.md); [P-25 No single home for current templates – versions held by individuals](../problems/p-25-no-single-home-for-current-templates-versions.md); [P-47 Teams work in silos and don't see each other's work or priorities](../problems/p-47-teams-work-in-silos-and-don-t.md); [P-48 Problems are fixed after they break, by individual vigilance](../problems/p-48-problems-are-fixed-after-they-break-by.md) |
| Also helps | – |
| Pain points cited | [KO-PP10](../pain-points/README.md#ko-pp10), [KO-PP14](../pain-points/README.md#ko-pp14), [KO-PP15](../pain-points/README.md#ko-pp15), [MP-PP04](../pain-points/README.md#mp-pp04), [MP-PP06](../pain-points/README.md#mp-pp06) (interviewer-raised), [MP-PP17](../pain-points/README.md#mp-pp17) (interviewer-raised), [MP-PP20](../pain-points/README.md#mp-pp20) (interviewer-raised) |
| Written source | – |
| Cost of inactivity / year | \~\$44K–\$134K combined (DS-02+DS-04+DS-10+DS-14, before overlap); company layer alone \$1K–\$4K – indicative, overlapping |
| Build cost / OpEx | TBC |

## Vision

> **Everything in the business can be seen from here – without overdoing it for the sake of it.** It connects what already exists (client brains, smart SOPs, help docs, client health) rather than adding another system people have to maintain.
>
> **Also in the vision (agreed 9 Nov):**
>
> 1. **One front door** – @oracle in Slack plus one simple home view in the browser; no new app to learn.
> 2. **One-page weekly leadership pulse** – clients at risk and wins ([DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)), overdue work ([DS-06](ds-06-request-sweeper-stray-slack-dm-and-email.md)), performance flags ([DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md), [DS-22](ds-22-seo-automated-monday-client-performance-check.md), [DS-29](ds-29-ppc-automated-monday-client-performance-check.md)), capacity signals.
> 3. **A source earns its place** – start with client brains, the playbook and help docs; connect a new source only when people keep asking about it.
> 4. **Memory with citations** – the brain keeps a memory of what it learns, and every fact links to where it came from so nothing is made up; anything **inferred is labelled as inferred**.
> 5. **Role-based access control (RBAC)** on both its memory and the information it can show – people only see what their role allows (e.g. commercial and HR detail limited to leadership).
> 6. **A connector to the systems of record, not a copy of them** – Monday, HubSpot, Drive, the ad platforms and the link CRM stay the source of truth; the brain reads from them. No staff tracking or timesheets.

**Your decision (9 Nov):** the AI Business Brain is the **umbrella**. It has solutions under it – the client brain, **smart SOPs people can query**, and similar – rather than being one separate tool.

## What sits under it

| Part of the brain | Solution | What it holds or does |
| --- | --- | --- |
| Client brains | [DS-04](ds-04-ai-client-brain.md) | Everything about each client: calls, Slack, email, the work, profile, style guide |
| Smart SOPs and AI playbook | [DS-02](ds-02-ai-playbook-repository.md) | How Aperitif does things – SOPs, prompts, skills, AI rules – **queryable**: staff ask "how do we do X?" and get the current answer |
| Systems register | [DS-10](ds-10-systems-register-and-break-fix-runbook.md) | Everything built, who owns it, what to do when it breaks |
| Client health & growth | [DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md) | Churn and expansion signals built on the client brains |
| **Company layer** ([O-27](../opportunities/README.md#o-27)) | DS-15 | One place to ask across all of the above (the existing Slack assistant); leadership gets a per-client pulse and a Tier 1 summary |

**Solutions that feed it or read from it:** [DS-03](ds-03-automated-ai-brief-drafts-monday-com-tasks.md) brief drafts (read client context and style guide), [DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md) deck generator (reads narrative from the client brain), [DS-06](ds-06-request-sweeper-stray-slack-dm-and-email.md) request sweeper (adds requests), [DS-08](ds-08-ai-sales-handover-extracted-from-sales-calls.md) sales handover (loads the handover), [DS-09](ds-09-ai-prefilled-onboarding-audit-and-master-seo.md) onboarding audit (loads the Master SEO Document and audit).

## Opportunities it covers

- **[O-27](../opportunities/README.md#o-27)** AI business brain over client records and SOPs – rank 27, Consider, effort L (1–4 h/month on its own) – **the company-wide layer**; the per-client part is [DS-04](ds-04-ai-client-brain.md).
- Your earlier ideas: *AI Business Brain*, *Team wiki – fast answers, self-updating, fits into workflows*.

## Problems it fixes and the evidence

- **No usable wiki; the founder re-explains things:** *"No. We need a wiki badly."* – Head of Client Services ([KO-PP15](../pain-points/README.md#ko-pp15)). *"I'm sick of just explaining the same thing over and over again."* – leadership ([MP-PP04](../pain-points/README.md#mp-pp04)). Linked problems: [Documentation is stale and rarely read](../problems/p-12-documentation-is-stale-and-rarely-read.md), [Documentation and internal tooling held by the founder](../problems/p-13-documentation-and-internal-tooling-held-by-the.md).
- **The AI assistant nobody uses:** *"it's got access to the team via a Slack channel. No one utilises it."* – founder ([KO-PP14](../pain-points/README.md#ko-pp14)). Transcripts paid for but unused: *"I think I'm the only one that does anything with the transcripts."* ([MP-PP20](../pain-points/README.md#mp-pp20), *raised by you*).
- **Leadership visibility:** can't see whether work is happening on remote days ([MP-PP06](../pain-points/README.md#mp-pp06), *raised by you*); account data isn't pre-synthesised (*your own observation in the mid-point interview, not staff evidence* – [MP-PP17](../pain-points/README.md#mp-pp17)).
- [No single home for current templates – versions held by individuals](../problems/p-25-no-single-home-for-current-templates-versions.md) – Solve now. The brain becomes the one home for current templates: the playbook ([DS-02](ds-02-ai-playbook-repository.md)) holds the master templates and the brain answers "where's the latest X template?" with the link (your call, 9 Nov).
- [Teams work in silos and don't see each other's work or priorities](../problems/p-47-teams-work-in-silos-and-don-t.md) – Solve now (culture). Every team reads the same client brains and company layer, so SEO, paid and content see each other's work and priorities for a client (your call, 9 Nov).
- **Systems not followed:** *"you can build the best system in the world, but like, people don't use it"* – founder ([KO-PP10](../pain-points/README.md#ko-pp10)). This is the brain's main adoption risk.
- [Problems are fixed after they break, by individual vigilance](../problems/p-48-problems-are-fixed-after-they-break-by.md) – Solve now (culture). The brain and the proactive solutions under it (pacing alerts [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md), link watchdog [DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md), health signals [DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md), market radar [DS-16](ds-16-seasonal-and-trending-content-radar-per-client.md), systems register [DS-10](ds-10-systems-register-and-break-fix-runbook.md)) shift the team from reacting to being warned early.

## Future state

1. Staff ask the brain first – about a client, a process or a system – and get an answer with its source.
2. SOPs are answered in the flow of work, not looked up in a stale wiki.
3. Leadership gets a weekly pulse per client and a Tier 1 summary without chasing.
4. Each new solution plugs into the same brain rather than becoming another silo.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Staff using the brain weekly | \~0 – Slack assistant unused ([KO-PP14](../pain-points/README.md#ko-pp14)) | ≥ 80% of staff |
| Questions to the founder / Head of Client Services on "how do we do X" | Repeated ([MP-PP04](../pain-points/README.md#mp-pp04)) | −50% |
| SOPs answerable by the brain | 0 | 100% of the top-10 repeat tasks ([DS-02](ds-02-ai-playbook-repository.md)) |

## Cost of inactivity (COI)

The umbrella's cost of inactivity is the **sum of the solutions under it** ([DS-02](ds-02-ai-playbook-repository.md), [DS-04](ds-04-ai-client-brain.md), [DS-10](ds-10-systems-register-and-break-fix-runbook.md), [DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md) – roughly \$44K–\$134K a year recoverable combined, before overlap is removed; [DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md)'s share (\$23K–\$52K) is mostly assumed prevented churn, already included – not added again). The company layer on its own adds 1–4 h/month (\$1K–\$4K a year) and leadership time on repeat explanations (not quantified).

*Basis: sum of the member solutions' recoverable figures ([DS-02](ds-02-ai-playbook-repository.md) \$6K–\$35K, [DS-04](ds-04-ai-client-brain.md) \$14K–\$43K, [DS-10](ds-10-systems-register-and-break-fix-runbook.md) \$1K–\$4K, [DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md) \$23K–\$52K incl. staff time and prevented churn) – overlapping, so indicative only. [O-27](../opportunities/README.md#o-27) hours assumed. \$80/hr.*

## Indicative build cost and OpEx

**TBC by Austin.** Priced per member solution; the company layer adds the query interface (Slack assistant) and connectors.

## Assumptions

- Adoption is the main risk ([KO-PP10](../pain-points/README.md#ko-pp10), [KO-PP14](../pain-points/README.md#ko-pp14)): the brain needs to live where people already work (Slack, Monday) and be introduced with training, not just switched on.
- Needs the AI-data rule ([DS-02](ds-02-ai-playbook-repository.md)) before client data is connected.
- The existing Slack assistant (OpenClaw) can be reused or replaced – to confirm.

## Decided (9 Nov)

- The AI Business Brain is the umbrella; client brains, smart SOPs and the other parts are solutions under it.
