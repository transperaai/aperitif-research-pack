# Solutions

One file per solution (DS-01..DS-33). Each file starts with YAML front matter and a summary table, then the solution one-pager. DS-13 is covered by DS-14 (Part B); its file is kept so numbering does not shift. Bundles group the 18 builds; each solution keeps its own scope, KPIs and evidence, and its status names the build it belongs to.

**Costs and value:** the 32 solutions are delivered as 18 builds; prices, maintenance, running costs and dollar value for each build are in [../builds/README.md](../builds/README.md). The research basis behind each value (time saved, capacity unlocked, evidence) is in [../VALUE-BY-BUNDLE.md](../VALUE-BY-BUNDLE.md); time and capacity are the same hours counted two ways, so never add them.


## <a id="bundle-ai-business-brain"></a>AI Business Brain

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-02](ds-02-ai-playbook-repository.md) | AI playbook repository (how we use AI: rules, SOPs, prompts, agents, skills) | everyone (leadership owns) | Recommended – not a separate build (documentation); includes the AI data rule and company Claude seats. DS-03, DS-04, DS-05, DS-06, DS-08, DS-09, DS-14, DS-15 depend on it | evidence-backed | [P-40](../problems/p-40-ai-use-is-personal-and-ungoverned-no.md), [P-12](../problems/p-12-documentation-is-stale-and-rarely-read.md), [P-28](../problems/p-28-regulated-industry-content-lacks-shared-compliance-rules.md), [P-44](../problems/p-44-change-fatigue-and-quiet-ai-anxiety-slow.md) | Fewer repeat questions; lets the other AI solutions run safely |
| [DS-04](ds-04-ai-client-brain.md) | AI client brain (per client) – under the AI Business Brain banner | account managers and delivery (everyone) | Recommended – build 2, Client brain | evidence-backed | [P-14](../problems/p-14-client-knowledge-lives-in-people-s-heads.md), [P-04](../problems/p-04-client-call-prep-takes-longer-than-the.md), [P-27](../problems/p-27-client-handovers-have-no-structured-pack-or.md), [P-28](../problems/p-28-regulated-industry-content-lacks-shared-compliance-rules.md) | 6–9 h/mo · A\$26K–39K capacity; the foundation for DS-03, 05, 14, 27, 28 |
| [DS-10](ds-10-systems-register-and-break-fix-runbook.md) | Systems register and break-fix runbook (everything built, who owns it, what to do when it breaks) | leadership / whoever builds tools | Recommended – not a separate build; ships with every build | evidence-backed | [P-15](../problems/p-15-slack-bots-and-agents-have-no-visible.md) | No reliance on one person |
| [DS-13](ds-13-merged-into-ds-14.md) | Merged into DS-14 – escalation and delegation rules (DS-14 Part B) | leadership and department leads | Merged – see DS-14 | evidence-backed | [P-22](../problems/p-22-escalations-route-around-department-leads-to-the.md) | Part of DS-14 – not valued separately |
| [DS-14](ds-14-client-health-and-growth-intelligence-anti-churn.md) | Client health & growth intelligence: anti-churn and expansion tracking and alerting, with escalation and delegation rules (Part B, from DS-13) | account managers and leadership | Recommended – build 4, Client Retention and Growth AI | mixed | [P-31](../problems/p-31-churn-risk-is-spotted-late-and-account.md), [P-22](../problems/p-22-escalations-route-around-department-leads-to-the.md) | Churn reduced \~1.5% a month (indicative): \~18 clients, \~A\$540K/yr kept |
| [DS-15](ds-15-ai-business-brain-the-umbrella.md) | AI Business Brain – the umbrella (client brains, smart SOPs, one place to ask) | everyone | Recommended – build 3, Business brain | mixed | [P-12](../problems/p-12-documentation-is-stale-and-rarely-read.md), [P-13](../problems/p-13-documentation-and-internal-tooling-held-by-the.md), [P-25](../problems/p-25-no-single-home-for-current-templates-versions.md), [P-47](../problems/p-47-teams-work-in-silos-and-don-t.md), [P-48](../problems/p-48-problems-are-fixed-after-they-break-by.md) | Better visibility for leadership |

## <a id="bundle-ppc-performance"></a>PPC performance

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-01](ds-01-modern-ad-budget-pacing-performance-alerting.md) | Modern ad budget pacing + performance alerting | PPC | Recommended – build 1, PPC pacing and performance assistant (with DS-27) | evidence-backed | [P-02](../problems/p-02-budgets-maintained-by-hand-in-three-places.md), [P-01](../problems/p-01-meta-pacing-sheet-is-broken-supermetrics-connector.md), [P-03](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) | 51–58 h/mo · A\$187K–213K capacity (≈ 5–6 PPC clients) · A\$10K overspend risk removed |
| [DS-25](ds-25-ppc-performance-forecasting-tool.md) | PPC: performance forecasting tool | PPC | Recommended – build 14, Forecasting (with DS-26) | Austin addition | [P-04](../problems/p-04-client-call-prep-takes-longer-than-the.md) | Better budget decisions, fewer surprises |
| [DS-26](ds-26-seo-performance-forecasting-tool.md) | SEO: performance forecasting tool | SEO | Recommended – build 14, Forecasting (with DS-25) | Austin addition | none | Better planning, realistic expectations |
| [DS-27](ds-27-ppc-alert-investigator-ai-diagnosis-and-commentary.md) | PPC: alert investigator – AI diagnosis and commentary on flagged activity | PPC | Recommended – build 1, PPC pacing and performance assistant (with DS-01) | mixed | [P-03](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) | Counted in DS-01 – removes the "what's going on" time when an alert fires |

## <a id="bundle-seo-performance"></a>SEO performance

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-03](ds-03-automated-ai-brief-drafts-monday-com-tasks.md) | Automated AI brief drafts → Monday.com tasks | SEO and content | Recommended – build 6, Brief drafts | evidence-backed | [P-33](../problems/p-33-content-briefs-are-re-cut-and-reformatted.md) | 12–24 h/mo of content-team time → more words written (\~A\$12K–23K a year; not counted as MRR) |
| [DS-09](ds-09-ai-prefilled-onboarding-audit-and-master-seo.md) | AI-prefilled onboarding audit and Master SEO Document | SEO strategists (onboarding) | Recommended – build 7, Onboarding audit | evidence-backed | [P-20](../problems/p-20-onboarding-stalls-on-client-access-and-disrupts.md) | 20–40 h/mo · A\$88K–177K capacity (≈ 2–5 clients) |
| [DS-22](ds-22-seo-automated-monday-client-performance-check.md) | SEO: automated Monday client performance check (GA4, Search Console, Ahrefs) | SEO | Recommended – build 8, SEO monitoring (with DS-23, DS-24) | evidence-backed | [P-03](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) | 17–39 h/mo · A\$88K–202K capacity (≈ 2–5 SEO clients) |
| [DS-23](ds-23-seo-drop-and-anomaly-alerts.md) | SEO: drop and anomaly alerts | SEO | Recommended – build 8, SEO monitoring (with DS-22, DS-24) | mixed | [P-03](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) | 7–11 h/mo · A\$35K–58K capacity (≈ 1–1.5 SEO clients) |
| [DS-24](ds-24-seo-mid-month-wins-sent-to-clients.md) | SEO: mid-month wins sent to clients | SEO | Recommended – build 8, SEO monitoring (with DS-22, DS-23) | mixed | [P-31](../problems/p-31-churn-risk-is-spotted-late-and-account.md) | New standard: wins shared between reports (trust, retention) |

## <a id="bundle-link-building-system"></a>Link-building system

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-07](ds-07-link-watchdog-agent-monitors-every-paid-link.md) | Link watchdog agent: monitors every paid link | link building | Recommended – build 5, Link-building system (with DS-11, DS-12, DS-31) | mixed | [P-07](../problems/p-07-paid-links-disappear-after-payment-detected-manually.md) | Up to A\$10K–16K/yr recovered; client results protected |
| [DS-11](ds-11-link-building-workflow-crm.md) | Link-building workflow CRM (orders, publishers, links, invoicing and payments) | link building | Recommended – build 5, Link-building system (with DS-12, DS-07, DS-31) | evidence-backed | [P-06](../problems/p-06-link-building-runs-on-7-disconnected-spreadsheets.md), [P-08](../problems/p-08-outreacher-invoicing-tracked-as-paypal-links-in.md) | 18.5–30 h/mo · \~9–15 more links a month (delivery capacity) |
| [DS-12](ds-12-link-supply-engine-shared-vetting-skill-client.md) | Link supply engine: shared vetting skill, client matching, brand mentions (sourcing stage of the DS-11 CRM) | link building | Recommended – build 5, Link-building system (with DS-11, DS-07, DS-31) | evidence-backed | [P-34](../problems/p-34-link-sourcing-is-slow-manual-and-supply.md) | 7.5–17 h/mo · \~4–8 more links a month |
| [DS-31](ds-31-proactive-brand-mention-tracking-for-backlinks.md) | Proactive brand-mention tracking for backlinks | link building / SEO | Recommended – build 5, Link-building system (with DS-11, DS-12, DS-07) | evidence-backed | [P-34](../problems/p-34-link-sourcing-is-slow-manual-and-supply.md) | Links won without paying a publisher |

## <a id="bundle-market-intelligence"></a>Market intelligence

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-16](ds-16-seasonal-and-trending-content-radar-per-client.md) | Seasonal & trending content radar per client | SEO and content strategists | Recommended – build 15, Market radar (with DS-32, DS-33) | evidence-backed | [P-24](../problems/p-24-seasonal-and-trending-content-is-planned-too.md) | Content lands before the peak, not after |
| [DS-32](ds-32-competitor-spy-per-client.md) | Competitor spy per client | SEO and content strategists (paid can use it too) | Recommended – build 15, Market radar (with DS-16, DS-33) | evidence-backed | [P-24](../problems/p-24-seasonal-and-trending-content-is-planned-too.md) | React to competitors first |
| [DS-33](ds-33-macro-trend-tracker-per-client.md) | Macro trend tracker per client | SEO, content and paid strategists | Recommended – build 15, Market radar (with DS-16, DS-32) | Austin addition | [P-24](../problems/p-24-seasonal-and-trending-content-is-planned-too.md) | Timely ideas from news and regulation |

## <a id="bundle-client-lifecycle"></a>Client lifecycle

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-08](ds-08-ai-sales-handover-extracted-from-sales-calls.md) | AI sales handover: extracted from sales calls, confirmed by delivery | sales and delivery | Recommended – build 9, Sales handover | evidence-backed | [P-27](../problems/p-27-client-handovers-have-no-structured-pack-or.md), [P-18](../problems/p-18-sales-commits-to-work-delivery-can-t.md) | New standard: at least an hour of prepared information before kick-off |
| [DS-17](ds-17-client-files-and-logins-in-company-owned.md) | Client files and logins in company-owned shared locations, linked to each client brain | everyone (operations) | Recommended – not a separate build; set up as each client brain is built | evidence-backed | [P-23](../problems/p-23-client-work-files-are-owned-by-individual.md) | Nothing lost when someone leaves |
| [DS-20](ds-20-new-client-dossier-agent.md) | New-client dossier agent (at signing → client brain) | sales and account managers | Recommended – build 10, New-client dossier | Austin addition | none | New standard: every new client researched before kick-off |

## <a id="bundle-delivery-and-reporting"></a>Delivery and reporting

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-05](ds-05-automated-deck-generator-quarterly-6-month-reviews.md) | Automated deck generator: quarterly + 6-month reviews and proposals | account managers and sales | Recommended – build 11, Sales proposal and reporting deck generator | evidence-backed | [P-05](../problems/p-05-client-documents-are-built-by-duplicating-previous.md), [P-19](../problems/p-19-proposals-are-rebuilt-from-scratch-per-prospect.md), [P-18](../problems/p-18-sales-commits-to-work-delivery-can-t.md) | 22–32 h/mo · A\$69K–104K capacity (≈ 2–3 clients) |
| [DS-28](ds-28-client-comms-assistant-monthly-updates-and-expectation.md) | Client comms assistant: monthly updates and expectation setting | account managers (PPC and SEO) | Recommended – build 13, Client comms (with DS-29) | mixed | [P-31](../problems/p-31-churn-risk-is-spotted-late-and-account.md) | Consistent, faster client updates, saved to the brain |
| [DS-29](ds-29-ppc-automated-monday-client-performance-check.md) | PPC: automated Monday client performance check (Google Ads, Meta and other channels) | PPC | Recommended – build 13, Client comms (with DS-28) | evidence-backed | [P-03](../problems/p-03-no-proactive-performance-alerting-problems-found-at.md) | New standard: clients hear from Aperitif before they ask (trust, retention) |

## <a id="bundle-team-productivity"></a>Team productivity

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-06](ds-06-request-sweeper-stray-slack-dm-and-email.md) | Request sweeper ("Roomba"): stray Slack, DM and email requests → Monday.com | everyone | Recommended – build 12, Team assistant (with DS-30) | mixed | [P-16](../problems/p-16-reminders-go-unacted-a-broken-reminder-bot.md), [P-36](../problems/p-36-internal-task-briefs-from-managers-to-implementers.md) | Nothing gets missed |
| [DS-30](ds-30-daily-priorities-assistant-one-triaged-list-per.md) | Daily priorities assistant: one triaged list per person from Monday, Slack, email, calendar, ad/SEO performance and seasonal signals | everyone | Recommended – build 12, Team assistant (with DS-06) | mixed | [P-16](../problems/p-16-reminders-go-unacted-a-broken-reminder-bot.md) | Focus each morning |

## <a id="bundle-new-services-and-standalone-tools"></a>New services and standalone tools

| ID | Solution | Team | Status | Source type | Fixes | Value |
| --- | --- | --- | --- | --- | --- | --- |
| [DS-18](ds-18-landing-page-generator.md) | Landing page generator (ad landing pages, Aperitif-hosted) | PPC | Recommended – build 16, Landing page generator | Austin addition | [P-38](../problems/p-38-creative-and-landing-pages-are-outsourced-slow.md) | A new service to sell: \~A\$18K–72K a year (outsourced today at \~A\$1,500 a page) |
| [DS-19](ds-19-ai-receptionist.md) | AI receptionist (phone; Aircall add-on) | sales / leadership (phones) | Recommended – build 17, AI receptionist | Austin addition | none | No missed calls; callers reach the right person |
| [DS-21](ds-21-ai-creative-tools-to-augment-the-team.md) | AI creative tools to augment the team (existing tools, no build) | PPC and creative | Recommended – build 18, AI creative tools: no build, a one-month trial | Austin addition | [P-38](../problems/p-38-creative-and-landing-pages-are-outsourced-slow.md) | Faster creative in-house |
