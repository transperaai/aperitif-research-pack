# Start here – Aperitif AI & business audit

Research behind Austin Smith's AI and business audit of Aperitif (Nov 2026): 14 interviews, traced from what people said to the solutions Austin recommends.

## The funnel

| Layer | Count | Status |
| --- | --- | --- |
| [Interviews](interviews/README.md) | 14 | 2 leadership + 12 staff, 22 Oct – 4 Nov 2026 |
| [Pain points](pain-points/README.md) (PP) | 243 | addressed 173, parked 48, partly addressed 20, rejected 2 |
| [Problems](problems/README.md) (P) | 48 | Austin's calls: Solve now 29, Park 9, Solve later 5, Reject 5. Ledger: addressed 31, parked 9, rejected 5, partly addressed 3 |
| [Merged opportunities](opportunities/README.md) (O) | 35 | addressed 15, dropped 7, absorbed 7, partly addressed 6 |
| [Earlier ideas](opportunities/README.md#earlier-ideas-table) (EI) | 21 | absorbed 9, addressed 5, dropped 4, partly addressed 2, idea to discuss 1 |
| [Solutions](solutions/README.md) (DS) | 33 | 32 in the final set; DS-13 merged into DS-14 |
| [Not recommending](decisions/not-recommending.md) (NR) | 1 | Email inbox PA assistant |

## The solutions, by bundle

Bundles group solutions for presenting; each solution keeps its own scope, KPIs and cost. Build prices and monthly fees are in each solution file (A\$, SaaS/tokens in US\$).

**AI Business Brain**

- [DS-02 AI playbook repository (how we use AI: rules, SOPs, prompts, agents, skills)](solutions/ds-02-ai-playbook-repository.md) – One repository for how Aperitif uses AI: AI data rule, company Claude seats, SOPs, prompts, agents and skills.
- [DS-04 AI client brain (per client) – under the AI Business Brain banner](solutions/ds-04-ai-client-brain.md) – A per-client AI brain (visible client page plus query box) pulling calls, Slack, email, the work and the client profile incl. style guide.
- [DS-10 Systems register and break-fix runbook (everything built, who owns it, what to do when it breaks)](solutions/ds-10-systems-register-and-break-fix-runbook.md) – One register of everything built: owner, backup, dependencies and what to do when it breaks.
- [DS-13 Merged into DS-14 – escalation and delegation rules (DS-14 Part B)](solutions/ds-13-merged-into-ds-14.md) – Merged into DS-14 (Part B): escalation and delegation rules.
- [DS-14 Client health & growth intelligence: anti-churn and expansion tracking and alerting, with escalation and delegation rules (Part B, from DS-13)](solutions/ds-14-client-health-and-growth-intelligence-anti-churn.md) – AI tracking of client sentiment and signals to warn of churn and spot growth, with escalation and delegation rules (Part B).
- [DS-15 AI Business Brain – the umbrella (client brains, smart SOPs, one place to ask)](solutions/ds-15-ai-business-brain-the-umbrella.md) – Umbrella for the AI Business Brain (DS-02, DS-04, DS-10, DS-14) plus a company-wide layer; the one home for current templates.

**PPC performance**

- [DS-01 Modern ad budget pacing + performance alerting](solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md) – One pacing and alerting tool across every live ad channel, with per-client thresholds and Slack alerts (PPC team; alerts only).
- [DS-25 PPC: performance forecasting tool](solutions/ds-25-ppc-performance-forecasting-tool.md) – PPC team: forecasting tool for each client from history, seasonality and outside signals.
- [DS-27 PPC: alert investigator – AI diagnosis and commentary on flagged activity](solutions/ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md) – PPC team: when DS-01 flags something, AI investigates and gives a first diagnosis.
- [DS-29 PPC: automated Monday client performance check (Google Ads, Meta and other channels)](solutions/ds-29-ppc-automated-monday-client-performance-check.md) – PPC team: automated Monday performance check per paid client across all channels.

**SEO performance**

- [DS-22 SEO: automated Monday client performance check (GA4, Search Console, Ahrefs)](solutions/ds-22-seo-automated-monday-client-performance-check.md) – SEO team: automated Monday performance check per client from GA4, Search Console and Ahrefs.
- [DS-23 SEO: drop and anomaly alerts](solutions/ds-23-seo-drop-and-anomaly-alerts.md) – SEO team: daily drop and anomaly alerts per client with a first guess at the cause.
- [DS-24 SEO: mid-month wins sent to clients](solutions/ds-24-seo-mid-month-wins-sent-to-clients.md) – SEO team: AI spots mid-month wins and drafts a short client note for the manager to send.
- [DS-26 SEO: performance forecasting tool](solutions/ds-26-seo-performance-forecasting-tool.md) – SEO team: forecasting tool for each client's organic performance.

**Link-building CRM**

- [DS-07 Link watchdog agent: monitors every paid link](solutions/ds-07-link-watchdog-agent-monitors-every-paid-link.md) – Agent that checks every paid link weekly and drafts publisher emails when a link drops.
- [DS-11 Link-building workflow CRM (orders, publishers, links, invoicing and payments)](solutions/ds-11-link-building-workflow-crm.md) – Link-building CRM covering publishers, orders, live links, invoicing and payments.
- [DS-12 Link supply engine: shared vetting skill, client matching, brand mentions (sourcing stage of the DS-11 CRM)](solutions/ds-12-link-supply-engine-shared-vetting-skill-client.md) – Shared vetting skill, client matching and quota reviews as the sourcing stage of the DS-11 CRM (brand mentions moved to DS-31).
- [DS-31 Proactive brand-mention tracking for backlinks (split from DS-12)](solutions/ds-31-proactive-brand-mention-tracking-for-backlinks.md) – Link building: weekly scan for unlinked brand mentions of Tier 1/2 clients, ranked, with drafted outreach; wins logged in DS-11.

**Market intelligence**

- [DS-16 Seasonal & trending content radar per client (split 9 Nov)](solutions/ds-16-seasonal-and-trending-content-radar-per-client.md) – Per-client seasonal and trending content radar (competitor spy is DS-32, macro trends DS-33).
- [DS-32 Competitor spy per client (split from DS-16)](solutions/ds-32-competitor-spy-per-client.md) – SEO/content: weekly watch of each client's competitors with a digest in the client brain and Slack alerts.
- [DS-33 Macro trend tracker per client (split from DS-16)](solutions/ds-33-macro-trend-tracker-per-client.md) – Strategists: per-client tracker of news, regulation, economy and industry shifts with "why it matters" and an idea to act on.

**Client lifecycle**

- [DS-08 AI sales handover: extracted from sales calls, confirmed by delivery](solutions/ds-08-ai-sales-handover-extracted-from-sales-calls.md) – AI extracts the sales handover from call transcripts; delivery confirms or denies with reasons (no hard blocks).
- [DS-09 AI-prefilled onboarding audit and Master SEO Document](solutions/ds-09-ai-prefilled-onboarding-audit-and-master-seo.md) – AI pre-fills the onboarding audit and Master SEO Document for a strategist to sign off.
- [DS-17 Client files and logins in company-owned shared locations, linked to each client brain](solutions/ds-17-client-files-and-logins-in-company-owned.md) – Client files and logins moved to company-owned shared locations, linked from each client brain.
- [DS-20 New-client dossier agent (at signing → client brain)](solutions/ds-20-new-client-dossier-agent.md) – At signing, an agent researches the new client and loads a sourced dossier into the client brain.

**Delivery & reporting**

- [DS-03 Automated AI brief drafts → Monday.com tasks](solutions/ds-03-automated-ai-brief-drafts-monday-com-tasks.md) – AI drafts monthly content briefs from the Master SEO Document and turns each into a Monday task, plus the full content-intake standard.
- [DS-05 Automated deck generator: quarterly + 6-month reviews and proposals](solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md) – Deck generator for quarterly and 6-month reviews and proposals (with price calculator); monthly reports stay in AgencyAnalytics.
- [DS-28 Client comms assistant: monthly updates and expectation setting](solutions/ds-28-client-comms-assistant-monthly-updates-and-expectation.md) – Account managers: drafts client updates through the month and expectation-setting notes before likely dips.

**Team productivity**

- [DS-06 Request sweeper ("Roomba"): stray Slack, DM and email requests → Monday.com](solutions/ds-06-request-sweeper-stray-slack-dm-and-email.md) – Request sweeper that turns stray Slack, DM and email requests into Monday tasks, plus a task-status sweep (daily priorities moved to DS-30).
- [DS-30 Daily priorities assistant: one triaged list per person from Monday, Slack, email, calendar, ad/SEO performance and seasonal signals](solutions/ds-30-daily-priorities-assistant-one-triaged-list-per.md) – Everyone: one triaged daily priority list per person from Monday, Slack, email, calendar, performance and seasonal signals, sent as a Slack DM.

**Standalone**

- [DS-18 Landing page generator (ad landing pages, Aperitif-hosted)](solutions/ds-18-landing-page-generator.md) – In-house landing page generator for ad landing pages on Aperitif-hosted pages.
- [DS-19 AI receptionist (phone; Aircall add-on or own build)](solutions/ds-19-ai-receptionist.md) – AI receptionist on the phone for new leads and existing clients; decided: call director, Aircall add-on recommended, own build as alternative.
- [DS-21 AI creative tools to augment the team (existing tools, no build)](solutions/ds-21-ai-creative-tools-to-augment-the-team.md) – Trial existing AI creative tools (no build) to make ad variants and video in-house.

## Biggest open points

- **P-21 Managers at capacity** (Solve now; widest-raised problem, 7 staff + 2 leadership) has no fixing solution – only "also helps"; Austin treats it as a culture/people recommendation. See [P-21](problems/p-21-managers-at-capacity-tier-2-3-clients.md).
- Solutions that fix no listed problem: [DS-19](solutions/ds-19-ai-receptionist.md), [DS-20](solutions/ds-20-new-client-dossier-agent.md), [DS-26](solutions/ds-26-seo-performance-forecasting-tool.md).
- Austin additions with weak or no interview evidence: [DS-18](solutions/ds-18-landing-page-generator.md), [DS-19](solutions/ds-19-ai-receptionist.md), [DS-20](solutions/ds-20-new-client-dossier-agent.md), [DS-21](solutions/ds-21-ai-creative-tools-to-augment-the-team.md), [DS-25](solutions/ds-25-ppc-performance-forecasting-tool.md), [DS-26](solutions/ds-26-seo-performance-forecasting-tool.md), [DS-33](solutions/ds-33-macro-trend-tracker-per-client.md).
- Full list of known gaps: [method/gaps-and-issues.md](method/gaps-and-issues.md).

## Where to look for what

| Question | Go to |
| --- | --- |
| What is recommended and why? | [solutions/](solutions/README.md) – one file per DS |
| What is each solution worth (time, capacity, DLER)? | [VALUE-BY-BUNDLE.md](VALUE-BY-BUNDLE.md) |
| What did people actually say? | [pain-points/](pain-points/README.md), then the [transcripts](interviews/README.md) |
| What is broken, and what did Austin decide about it? | [problems/](problems/README.md) |
| Which ideas were dropped, parked or not recommended? | [decisions/not-recommending.md](decisions/not-recommending.md), [opportunities/](opportunities/README.md) |
| How were decisions recorded? | [decisions/](decisions/README.md) – ledger and log |
| Clusters, root causes, contradictions, culture and strengths | [synthesis/](synthesis/README.md) |
| How was it done, and how reliable is it? | [method/](method/README.md) – prompts, audit, gaps |
| Machine-readable data | [data/](data/README.md) |
