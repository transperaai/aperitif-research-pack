---
id: DS-17
title: "Client files and logins in company-owned shared locations, linked to each client brain"
team: "everyone (operations)"  # inferred: the page gives no "Team:" line
bundle: "Client lifecycle"
status: "Recommended – not a separate build; set up as each client brain is built"
coverage: addressed
source_type: "evidence-backed"
opportunities: ["O-30 (full)"]
earlier_ideas: []
written_sources: []
problems_fixed: ["P-23"]
problems_also_helped: []
problems_related_only: []
pain_points_cited: ["SB-PP09", "SH-PP08"]
pain_points_interviewer_raised_or_inferred: []
value: "Nothing lost when someone leaves"
---

# DS-17 · Client files and logins in company-owned shared locations

*Client files and logins moved to company-owned shared locations, linked from each client brain.*

| | |
| --- | --- |
| Bundle | [Client lifecycle](README.md#bundle-client-lifecycle) |
| Team | everyone (operations) *(inferred)* |
| Status | Recommended – not a separate build; set up as each client brain is built |
| Source type | evidence-backed |
| Opportunities | [O-30](../opportunities/README.md#o-30) (full) |
| Earlier ideas | – |
| Fixes | [P-23 Client work files are owned by individual staff accounts, including staff who have left](../problems/p-23-client-work-files-are-owned-by-individual.md) |
| Also helps | – |
| Pain points cited | [SB-PP09](../pain-points/README.md#sb-pp09), [SH-PP08](../pain-points/README.md#sh-pp08) |
| Written source | – |
| Value | Nothing lost when someone leaves |

## Vision

> **Not really a build – a foundation: a good file structure and clean data.** It's kept in the pack because the AI Business Brain ([DS-15](ds-15-ai-business-brain-the-umbrella.md)) and the client brains ([DS-04](ds-04-ai-client-brain.md)) are only as good as the files and records they read. Same folder structure for every client, files in company-owned locations, logins in the shared vault, nothing on personal drives.

## Decision

**Decision:** adopt [O-30](../opportunities/README.md#o-30), **connected to the AI client brains ([DS-04](ds-04-ai-client-brain.md))** – each client's brain links to its folder and its login entries, so anyone working on the client finds them in one place.

## What changes

1. Every client gets the same folder structure in the company's shared Google Drive.
2. Files move off personal drives into those folders.
3. The LastPass migration is finished; each client's logins sit in a shared vault entry.
4. The client brain ([DS-04](ds-04-ai-client-brain.md)) and the Monday client item link to the folder and the vault entry. The brain can read the folder's documents (strategy, reports, briefs); it links to logins but never stores passwords.

## Opportunities it covers

- **[O-30](../opportunities/README.md#o-30)** Client files and logins in company-owned shared locations – rank 30, quick win, effort S

## Problems it fixes and the evidence

- **Documents on personal drives:** *"when I was being handed over clients to me, I was Just like trying to find documents."* – a senior performance manager ([SH-PP08](../pain-points/README.md#sh-pp08), stated).
- **Logins in the wrong place:** *"we still have to go into HubSpot… and look into the login information"* – the technical SEO specialist ([SB-PP09](../pain-points/README.md#sb-pp09)); the LastPass migration is unfinished.
- [Client work files are owned by individual staff accounts, including staff who have left](../problems/p-23-client-work-files-are-owned-by-individual.md) – Solve now; this solution moves them to company-owned folders.
- Also helps: handovers ([DS-04](ds-04-ai-client-brain.md), [DS-08](ds-08-ai-sales-handover-extracted-from-sales-calls.md)) and the knowledge-walks-out risk when staff leave.

## Future state

1. Every client's files and logins are in company-owned locations, in the same structure.
2. From the client brain or Monday item, anyone with access is one click from the folder and the logins.
3. Nothing about a client lives on a personal drive.

## KPIs

| KPI | Baseline | Target |
| --- | --- | --- |
| Clients with a standard shared folder linked from the brain | Unknown | 100% |
| Client logins in the shared vault (not HubSpot or personal) | Migration unfinished ([SB-PP09](../pain-points/README.md#sb-pp09)) | 100% |
| Time to find a client's documents on handover | "trying to find documents" ([SH-PP08](../pain-points/README.md#sh-pp08)) | \< 2 min |

## Value

**Value: visibility and risk.** Every client's files and logins live in company-owned locations linked to the client, so nothing is lost when someone leaves and anyone can find what they need. No hours claimed.

**Problems it eliminates:** **P-23** Client work files are owned by individual staff accounts

**Goals:** trust · good customer service

## Pricing

Pricing for this solution is in [Builds and pricing](../builds/README.md).

## Assumptions

- LastPass stays as the password manager.
- Staff move their files across during a set migration window.

## Decided

- Adopt as written; linked from each client brain ([DS-04](ds-04-ai-client-brain.md)), with passwords kept in the vault, not the brain.
