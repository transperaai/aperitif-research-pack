# Assumption register

Every assumption labelled in the solutions (DS-01 to DS-33), in one place, with how to confirm it. Taken from each solution's **Assumptions** section and the **basis** line under its cost of inactivity (COI). A few rows (marked "audit") come from the independent audit of 9 Nov rather than the page.

**Types**
- **Hours** – an estimate of time saved or spent, not a stated time.
- **Pricing** – a vendor price or rate that needs checking.
- **Evidence-thin** – rests on one person, one document or an inference.
- **Dependency** – needs another solution, access or decision first.
- **Austin addition** – Austin's own idea, with little or no interview evidence.

**One rule applies to all of them:** staff time is costed at **$80/hr (AUD)**, the internal labour cost – not the $150/hr client rate (context pack).

---

## The biggest assumption: client churn (DS-14)

> **Austin's assumption, not from the interviews.** No churn figure was stated by anyone.
>
> - Average retainer: **$5K a month**
> - Churn: **3% of clients a year**
> - Client count: **at least 61** (the paid media book, Nov 2026 – the full count including SEO-only clients is higher)
> - Maths: 61 × 3% ≈ 1.8 clients a year × $60K a year each ≈ **~$110K a year** in lost revenue
> - Recoverable if DS-14 prevents 20–40% of that churn: **~$22K–$44K a year**
>
> **Comparison:** the context pack gives a 98% portfolio retention target (~2% churn). At 2%, the figure would be **~$73K a year**.
>
> **How to confirm:** Joe – what is the real average retainer, the real client count, and last year's churn rate?
>
> **Where it flows:** DS-14's COI; DS-15's combined figure (counted once, not twice); the retention value of DS-23, DS-24 and DS-28.

---

## Register by solution

### DS-01 · Modern ad budget pacing + performance alerting
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (~16–40 h/month) are assumed; only ~4% of the pacing and monitoring hours rest on stated times | Hours | Time one week of pacing and monitoring across the team |
| The channel list (LinkedIn, TikTok, Criteo, Pinterest, ChatGPT ads) comes from one interview (WS-O01) | Evidence-thin | Pull the live channel list per client |
| Bïrch facts from its pricing page and reviews, Nov 2026; LinkedIn not listed | Pricing | Vendor check before deciding |
| Adpulse: Enterprise tier at ~US$1.2M/month spend and 100+ accounts; Slack @mentions, real-time alerts and per-channel alert types not documented | Pricing | Adpulse demo (five questions on the DS-01 page) |
| Supermetrics is connected but failing, not cancelled (contradiction X-01) | Evidence-thin | Check the Supermetrics account |
| Whether the $10K overspend credit was on LinkedIn is not confirmed (contradiction X-10; from the audit, not the page) | Evidence-thin | Ask Joe |

### DS-02 · AI playbook repository
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (6.5–36 h/month) assumed – no stated times for AI tasks | Hours | Ask each prompt owner how long the task took before |
| The AI rule needs Joe's sign-off on client-data use and a check against client contracts | Dependency | Joe sign-off; contract review |
| The library goes stale like the wiki unless linked from Monday and owned | Dependency | Name an owner; review use after 60 days |

### DS-03 · Automated AI brief drafts → Monday.com tasks
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (~10–30 h/month) assumed | Hours | Time a month of briefing before and after |
| Needs one current brief template (C-20), and per-client tone and compliance context from DS-04 | Dependency | Agree the template with the content and SEO teams |
| The Master SEO Document is consistent enough across clients to read automatically | Evidence-thin | Test on 2–3 clients |
| The Monday integration builds on the Make set-up, whose gaps sit with Sid Bali (C-31) | Dependency | Review with Sid |
| Depends on the AI data rule (DS-02) | Dependency | DS-02 first |

### DS-04 · AI client brain (per client)
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (~15–45 h/month) assumed; the only stated figure is 60–75 min prep per call (Shrishti; the audit notes Diya gave ~30 min, X-24) | Hours | Time call prep for a sample of managers |
| Needs client call-recording consent, the AI data rule (DS-02) and read access to Slack, email and ad platforms | Dependency | Consent wording; DS-02; access audit |
| One client-record template agreed across organic and paid | Dependency | Workshop with both teams |
| Slack and email can be reliably tagged to the right client | Evidence-thin | Pilot on 5 clients |

### DS-05 · Automated deck generator: quarterly + 6-month reviews and proposals
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (~10–23 h/month) assumed; the deck saving is capped at 75% of review time, proposals at ~50% of lead-to-proposal time; the only stated time is a half-day for one bespoke deck | Hours | Time the next three review decks |
| Jethro Jason wasn't recorded, so proposal evidence is leadership plus one delivery staff member | Evidence-thin | Interview Jethro |
| Needs one current master template per deck type, the AI data rule (DS-02) and data access | Dependency | Template owner; DS-02 |
| Laura is comfortable with AI-drafted 6-month reviews for smaller clients (LS-O11); larger clients may need more hand-written narrative | Evidence-thin | Confirm the client cut-off with Laura |

### DS-06 · Request sweeper ("Roomba")
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (~10–29 h/month) assumed; uses O-06's figure as a proxy | Hours | Count requests captured in a 2-week pilot |
| Reading DMs needs each person's authorisation; email needs each person's Gmail authorisation | Dependency | Staff opt-in; DS-02 rule |
| Monday's Slack integration already turns a message into a task by hand; the sweeper adds automatic detection | Evidence-thin | Check Monday's current integration |
| Some junk tasks at first; rules tuned over the first few weeks | Evidence-thin | Track false positives in the pilot |

### DS-07 · Link watchdog agent
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Dead-link rate from one one-off report (~100 over ~10 months); the audit notes a document check found a much higher fault rate (32% of ~1,016 links checked Jan–Apr), so the real figure may be higher | Evidence-thin | Run one full check of live paid links |
| Price per link ~$80–$130: the page cites KZ-PP10, but the audit traced it to the context pack and order sheets, not the interview | Pricing | Check the order book |
| Recovery of lost link money assumed at 50–100%; publisher terms must allow replacement claims or refunds | Evidence-thin | Review publisher terms |
| Needs one clean link list with URLs and requirements (DS-11) | Dependency | DS-11 first |
| Jev AI's fit (scale, scheduling, change detection) | Pricing | Trial |

### DS-08 · AI sales handover
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (2–10 h/month) assumed | Hours | Time the next three handovers |
| Sales calls are recorded with prospect consent and transcripts are reachable | Dependency | Check with Jethro and Joe |
| Jethro wasn't interviewed – the sales side of the evidence is leadership's view | Evidence-thin | Interview Jethro |
| Depends on DS-04 and the AI data rule (DS-02) | Dependency | DS-02, DS-04 first |

### DS-09 · AI-prefilled onboarding audit and Master SEO Document
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (5–29 h/month) assumed; precedent is Karl's prompt guide (strategy from ~3 days to ~75–90 min) | Hours | Time the next two onboardings |
| Needs read-only access at signing (DS-08 add-on) and the AI data rule (DS-02) | Dependency | DS-02, DS-08 |
| The 30-item paid audit checklist is current and can be encoded | Evidence-thin | Review with Wendlley |

### DS-10 · Systems register and break-fix runbook
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (1–4 h/month) assumed; the real value is risk | Hours | – |
| Kept up to date only if adding an entry is part of "done" for every build | Dependency | Make it a rule |
| A second admin has capacity to be trained | Dependency | Julia to name the person |

### DS-11 · Link-building workflow CRM
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (6–26 h/month) assumed | Hours | Time one month of order and invoice admin |
| External publishers will use a portal or filtered view rather than their own sheets – some brokers may refuse | Evidence-thin | Ask Tonie's top outreachers |
| Existing sheets can be migrated without losing link history or order IDs | Evidence-thin | Test migration on one month |
| Payment method stays the same; only tracking moves | Dependency | Confirm with Joe |

### DS-12 · Link supply engine
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (5–19 h/month) assumed; the only stated time is 1–2 h per 60-domain batch | Hours | Time a few vetting batches |
| Karl's vetting criteria can be written down and tested on past decisions | Evidence-thin | Back-test on 100 past decisions |
| Clients accept quota changes where supply is scarce | Evidence-thin | Ask account managers |

### DS-13 · Merged into DS-14 (escalation and delegation rules)
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Leadership time (5–16 h/month) assumed, costed at $80/hr – which understates leadership time | Hours | Julia to estimate escalation hours |
| Leads get short coaching on escalations and client comms (MP-PP08) | Dependency | Culture recommendation P-41 |
| Joe sets the contract value threshold | Dependency | Joe |

### DS-14 · Client health & growth intelligence
| Assumption | Type | How to confirm |
| --- | --- | --- |
| **Churn: $5K retainer, 3%/yr, ≥61 clients, 20–40% prevented** – see the box at the top | Evidence-thin (Austin's assumption) | Joe – real retainer, client count, churn |
| Staff time (1–8 h/month) assumed | Hours | – |
| Depends on DS-04 being live with transcripts, email and Slack | Dependency | DS-04 first |
| Profiling client contacts needs the AI data rule and a clear line on what's stored about individuals; staff are not profiled | Dependency | DS-02; privacy check |
| "Gets smarter" only if outcomes are logged for every alert | Dependency | Account managers log outcomes |
| Signals are suggestions; people still own the escalation | – | – |

### DS-15 · AI Business Brain – the umbrella
| Assumption | Type | How to confirm |
| --- | --- | --- |
| COI is the overlapping sum of DS-02, DS-04, DS-10 and DS-14 (~$44K–$134K a year, indicative); company layer 1–4 h/month assumed | Hours | – |
| Adoption is the main risk: it must live in Slack and Monday and come with training (KO-PP10, KO-PP14) | Dependency | Adoption plan (risk 2) |
| Needs the AI data rule (DS-02) | Dependency | DS-02 first |
| The existing Slack assistant (OpenClaw) can be reused or replaced | Evidence-thin | Review with Joe |

### DS-16 · Seasonal & trending content radar
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (2–7 h/month) assumed; evidence from organic only (2 people) | Hours / Evidence-thin | Ask paid strategists whether they'd use it |
| Competitor lists and niche keywords exist or can be pulled from the Master SEO Document | Dependency | Check 5 clients |
| Alert volume tuned per client | Evidence-thin | Pilot |

### DS-17 · Client files and logins in company-owned locations
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (1–4 h/month) assumed | Hours | – |
| LastPass stays as the password manager | Dependency | Joe |
| Staff move files across in a set migration window | Dependency | Julia to schedule |

### DS-18 · Landing page generator
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion; evidence is leadership plus one staff member | Austin addition | – |
| Pages published on a builder Aperitif controls (not the client's CMS) | Dependency | Trial one builder |
| COI not quantified – pages outsourced per year unknown (~$1,500 a page quoted by Wendlley) | Evidence-thin | Wendlley to count pages outsourced |

### DS-19 · AI receptionist
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion; weak interview evidence | Austin addition | – |
| Aircall add-on ~A$370/month for 1,000 minutes | Pricing | Re-check before signing |
| COI not quantified – no call or missed-call volumes | Evidence-thin | Pull Aircall call logs |

### DS-20 · New-client dossier agent
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion, supported by one leadership quote (KO-PP22) | Austin addition | – |
| Public information only; LinkedIn data access to be confirmed | Dependency | Check LinkedIn terms |
| COI not quantified – research time not stated | Hours | Julia to estimate time per new client |

### DS-21 · AI creative tools
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's addition; tool list from web research, Nov 2026, not interviews | Austin addition | – |
| Prices and features from vendor and review sites, Nov 2026 (mostly USD) | Pricing | Verify before buying |
| Output quality for lead-gen and service clients is the open question | Evidence-thin | One-month trial on real clients |

### DS-22 · SEO: Monday client performance check
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Hours saved (3.6–10.2 h/month) assumed | Hours | Time the current Monday checks |
| API access to every client's GA4, Search Console and Ahrefs | Dependency | Access audit |
| Thresholds agreed per client by the SEO team | Dependency | SEO team |

### DS-23 · SEO: drop and anomaly alerts
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Thresholds tuned per client so managers aren't flooded | Evidence-thin | Pilot |
| Value is retention – part of DS-14's churn assumption | Evidence-thin | See churn box |

### DS-24 · SEO: mid-month wins sent to clients
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Mainly Zach's suggestion (written doc) plus one interview opportunity (ZC-O03); not raised widely | Evidence-thin | Ask other SEO managers |

### DS-25 · PPC: performance forecasting tool
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Mainly Austin's suggestion; evidence is one person (Wendlley), who has largely solved it personally with Gemini | Austin addition | Ask other performance managers |
| Economic and trend data sources to be chosen | Dependency | – |

### DS-26 · SEO: performance forecasting tool
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion; weak direct evidence (LS-PP16 was raised by Austin) | Austin addition | Ask the SEO team if they'd use it |

### DS-27 · PPC: alert investigator
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Investigation time (3.5–19 h/month) is an estimate for one manager (DM-PP01); overlaps DS-01 – don't add the two | Hours | Time investigations for two weeks |
| Needs API access to ad accounts, GA4 and the CRM | Dependency | Access audit |

### DS-28 · Client comms assistant
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion, supported by SH-PP09 and KO-PP20 | Austin addition | – |
| Managers approve every message; nothing goes to clients automatically | Dependency | Rule in DS-02 |
| Time not quantified separately (sits in the 34–71 h/month of client email and ad hoc work) | Hours | – |

### DS-29 · PPC: Monday client performance check
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Manual checks (8.8–20.9 h/month) estimated for one manager (DM-PP02); overlaps DS-01 – don't add the two | Hours | Time Monday checks for two weeks |
| API access to every live ad account and GA4 | Dependency | Access audit |
| Check list agreed with Wendlley | Dependency | Wendlley |

### DS-30 · Daily priorities assistant
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Triage time (6–11 h/month) is for one person (Sid, O-29); more if rolled out to everyone | Hours / Evidence-thin | Pilot with 3–4 people |
| Each person connects their own inbox, calendar and DMs | Dependency | Staff opt-in |
| Ranking tuned per role so the list stays short | Evidence-thin | Pilot |

### DS-31 · Brand-mention tracking for backlinks
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Mainly Zach's suggestion (interview and written doc) | Evidence-thin | – |

### DS-32 · Competitor spy per client
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Competitor lists exist per client or can be pulled from the Master SEO Document | Dependency | Check 5 clients |

### DS-33 · Macro trend tracker per client
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's earlier idea plus Zach's suggestion; one stated example (ZC-PP17) | Austin addition | – |

---

## Figures that must not be added together

The solutions share hours, so their COI figures overlap:
- **DS-01, DS-27 and DS-29** all draw on paid performance-monitoring hours.
- **DS-11 and DS-12** use the same link sourcing process row.
- **DS-06 and DS-30** – DS-30's triage hours were moved out of DS-06.
- **DS-15** is the sum of DS-02, DS-04, DS-10 and DS-14 – never add it to them.
- **DS-13's** $5K–$15K is kept separate from DS-14.
