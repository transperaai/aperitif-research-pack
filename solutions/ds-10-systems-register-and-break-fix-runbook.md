---
id: DS-10
title: "Systems register and break-fix runbook (everything built, who owns it, what to do when it breaks)"
team: "leadership / whoever builds tools"  # inferred: the page gives no "Team:" line
bundle: "AI Business Brain"
status: "Decided – priced"
ledger_status: addressed
source_type: "evidence-backed"
opportunities: ["O-16 (full)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-15"]
problems_also_helped: ["P-39"]
problems_related_only: []
pain_points_cited: ["SB-PP10", "SB-PP11", "SD-PP19"]
pain_points_interviewer_raised_or_inferred: ["SD-PP19 (inferred)"]
coi_per_year: "$1K–$4K"
build_cost: "Free"
monthly: "none (Notion already paid)"
notion_section: "Systems register and break-fix runbook"
---

# DS-10 · Systems register and break-fix runbook

*One register of everything built: owner, backup, dependencies and what to do when it breaks.*

| | |
| --- | --- |
| Bundle | [AI Business Brain](README.md#bundle-ai-business-brain) |
| Team | leadership / whoever builds tools *(inferred)* |
| Status | Decided – priced |
| Source type | evidence-backed |
| Opportunities | [O-16](../opportunities/README.md#o-16) (full) |
| Earlier ideas | – |
| Fixes | [P-15 Slack bots and agents have no visible owner or documentation](../problems/p-15-slack-bots-and-agents-have-no-visible.md) |
| Also helps | [P-39 HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost](../problems/p-39-hubspot-make-monday-integrations-create-wrong-or.md) – Park ("also helps (you parked this problem)") |
| Pain points cited | [SB-PP10](../pain-points/README.md#sb-pp10), [SB-PP11](../pain-points/README.md#sb-pp11), [SD-PP19](../pain-points/README.md#sd-pp19) (inferred) |
| Written source | – |
| Cost of inactivity / year | \$1K–\$4K |
| Build cost | Free |
| Monthly | none (Notion already paid) |

## Vision

> **A help-doc repository for everything that's built, connected to the AI brain so people can ask it and get help.** "How do I use X?", "X stopped working, what do I check?" – the brain answers from the help docs and runbooks (through Slack, like the @oracle in [DS-02](ds-02-ai-playbook-repository.md)). It **reduces Austin's time spent debugging and showing people how to use things**, and means fixes don't depend on one person.

## Pricing & priority

> **Priority: Fill-in – do early (foundation) · Impact 3 / 5 · Effort 1 / 5 (draft – confirm)**
>
> | Item | Build cost | Monthly cost |
> | --- | --- | --- |
> | **Help docs and systems register** – documentation, not a build; connected to the AI brain so @oracle answers from it | **A\$0 – no charge** (documentation supplied with each build) | – (Notion already paid) |

**Your decision (9 Nov):** adopt [O-16](../opportunities/README.md#o-16). In your words, it's **one place with the information for everything that's built and what to do if something breaks**. It sits alongside the AI playbook ([DS-02](ds-02-ai-playbook-repository.md)) and covers every solution in this pack as it goes live.

## What goes in it

| For every system | Example |
| --- | --- |
| What it is and what it does | Make scenario: HubSpot deal won → Monday client board |
| Where it lives, and its logins/admin | Make workspace, HubSpot admin |
| Owner and backup owner | Technical SEO specialist + named second admin |
| What it depends on | Supermetrics connector, Slack channel, API keys |
| **What to do if it breaks** | Symptoms, first checks, how to restart or roll back, who to call |
| Last checked | Date of the monthly check |

Covers Make scenarios, bots (e.g. the M/W/F pacing bot), Apps Scripts, extensions, Claude skills and agents, and each DS solution once built.

## Opportunities it covers

- **[O-16](../opportunities/README.md#o-16)** Own and verify automations: register, backup admin, reconciliation – rank 16, quick win, effort S (1–4 h/month, assumed). Includes naming and training a **second Monday/Make admin** and a **monthly check** that HubSpot tickets and Monday tasks match each client's scope; the HubSpot/Monday keep-or-trim decision before renewal comes out of the register.

## Problems it fixes and the evidence

- [Slack bots and agents have no visible owner or documentation](../problems/p-15-slack-bots-and-agents-have-no-visible.md) – *"But if I'm not there, who's going to do it? It needs to have that system in place."* – the technical SEO specialist who built and maintains it ([SB-PP11](../pain-points/README.md#sb-pp11)).
- Also helps (you parked this problem): [HubSpot–Make–Monday integrations create wrong or unverified tasks, at notable cost](../problems/p-39-hubspot-make-monday-integrations-create-wrong-or.md) – the register documents these automations so errors are found faster; it doesn't fix them. *"the person who closes the deal on HubSpot is never the person who's going to manage the client account."* ([SB-PP10](../pain-points/README.md#sb-pp10)), fixed by hand each time.
- Unowned automations: the pacing bot has no visible owner or documentation (*inferred from the interview, not stated* – [SD-PP19](../pain-points/README.md#sd-pp19)), and the Supermetrics feed failed without anyone owning the fix ([DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)).

## Future state

1. Every automation, bot and AI tool has an entry with an owner, a backup and a break-fix runbook.
2. When something breaks, anyone on the team can find what it is and the first steps, instead of waiting for one person.
3. A second admin can run Monday and Make.
4. Each month, systems are checked and the register's "last checked" dates updated.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Automations and bots with a register entry, owner and runbook | Unknown – undocumented ([SB-PP11](../pain-points/README.md#sb-pp11), [SD-PP19](../pain-points/README.md#sd-pp19)) | 100% |
| Systems with a trained backup owner | 0 for Monday/Make ([SB-PP11](../pain-points/README.md#sb-pp11)) | 100% of critical systems |
| Time to fix a broken automation | Depends on one person being available | Same day, by owner or backup |

## Cost of inactivity (COI)

|  | Per month | Per year |
| --- | --- | --- |
| Recoverable staff time | 1–4 h (\$80–\$320) | **\$1K–\$4K** |

The real cost is risk, not hours: if the one person who knows the Monday/Make set-up is away or leaves, task routing, onboarding boards and syncs stop with nobody able to fix them; unowned automations (like the pacing feed) fail silently – the pacing gap already contributed to a \$10K overspend credit ([DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md)). Possible licence saving from the HubSpot/Monday decision – not quoted until invoices are checked ([X-31](../synthesis/contradictions.md#x-31)).

*Basis: [O-16](../opportunities/README.md#o-16) recoverable hours. Assumed. \$80/hr.*

## Indicative build cost and OpEx

See this solution's green **Pricing & priority** box above.

## Assumptions

- The register is kept up to date only if adding an entry is part of "done" for every new build.
- The second admin has capacity to be trained.

## Decided (9 Nov)

- One place for everything built: what it is, who owns it, and what to do when it breaks. Lives alongside the AI playbook ([DS-02](ds-02-ai-playbook-repository.md)).
