# Assumption register

Every assumption labelled in the solutions (DS-01 to DS-33), in one place, with how to confirm it. Taken from each solution's **Assumptions** section and the basis behind its **Value** (see VALUE-BY-BUNDLE.md – every value number there carries a basis label: client board, interview, Austin/leadership input, assumption, or new capability not measured). A few rows (marked "audit") come from the independent audit of 9 Nov rather than the page.

**Types**
- **Hours** – an estimate of time saved or spent, not a stated time.
- **Pricing** – a vendor price or rate that needs checking.
- **Evidence-thin** – rests on one person, one document or an inference.
- **Dependency** – needs another solution, access or decision first.
- **Austin addition** – Austin's own idea, with little or no interview evidence.

**Rules that apply to all of them:** staff time is costed at **$80/hr (AUD)** (Joe's figure) – not the $150/hr client rate. Capacity unlocked = hours freed ÷ ~130 productive hours a month (assumption) × MRR managed per account manager (live client board, 10 Nov: PPC 67 clients / A$198,747 / 5 managers; SEO 68 clients / A$222,374 / 4 managers). Time saved and capacity unlocked are the same hours counted two ways – never add them. Where a solution says "none claimed" or "not measured", no hours are assumed.

---

## The biggest assumption: clients saved by early warning (DS-14)

> **Client board data plus Austin's estimate.** No churn figure was stated in the interviews.
>
> - Churn today: **~4% of clients a month** – Austin's estimate (the client board shows 10 contracts ended 31 Aug–17 Oct 2026, average ~A$2,500)
> - Churn with early warning: **~2.5% a month** – Austin's target: ~1.5% of 101 clients a month, about 18 clients a year kept
> - Maths: 18 × ~A$2,500 × 12 ≈ **~A$540K a year kept** (indicative; see [Builds and pricing](../builds/README.md))
> - Aperitif is capped by team capacity, so kept clients are not added to the capacity totals – they mean fewer replacement wins are needed
>
> **How to confirm:** Joe – is the 31 Aug–17 Oct run of 10 ended contracts typical, and how many of those could an earlier warning have saved?
>
> **Where it flows:** DS-14's Value only. DS-23, DS-24, DS-28 and DS-29 support retention but claim no retention value of their own.

---

## Register by solution

### DS-01 · Modern ad budget pacing + performance alerting
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Time saved (~56–64 h/month): 67 live PPC clients (client board) × ~15 min weekly check (Austin/leadership input) plus pacing fixes (Wendlley); alerts remove 70–80% of checks – the target, not a measured figure | Hours | Time one week of account checks across the PPC team |
| Capacity (~A$186K–213K a year) assumes ~130 productive hours per manager a month | Hours | Confirm productive hours with Julia |
| The channel list (LinkedIn, TikTok, Criteo, Pinterest, ChatGPT ads) comes from one interview (WS-O01) | Evidence-thin | Pull the live channel list per client |
| Bïrch facts from its pricing page and reviews, Nov 2026; LinkedIn not listed | Pricing | Vendor check before deciding |
| Adpulse: Enterprise tier at ~US$1.2M/month spend and 100+ accounts; Slack @mentions, real-time alerts and per-channel alert types not documented | Pricing | Adpulse demo (five questions on the DS-01 page) |
| Supermetrics is connected but failing, not cancelled (contradiction X-01) | Evidence-thin | Check the Supermetrics account |
| Whether the $10K overspend credit was on LinkedIn is not confirmed (contradiction X-10; from the audit, not the page) | Evidence-thin | Ask Joe |

### DS-02 · AI playbook repository
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – value is fewer repeat questions and safe use of the other AI solutions (not measured) | – | – |
| The AI rule needs Joe's sign-off on client-data use and a check against client contracts | Dependency | Joe sign-off; contract review |
| The library goes stale like the wiki unless linked from Monday and owned | Dependency | Name an owner; review use after 60 days |

### DS-03 · Automated AI brief drafts → Monday.com tasks
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Time saved (~8–12 h/month of content-team time): 48 clients receive content (client board) × ~20 min a brief today (Austin input) → ~5–10 min with the form (assumption). Briefs are written by the content team, so the time goes into more words written, not MRR | Hours | Time a month of briefing before and after |
| Needs one current brief template (C-20), and per-client tone and compliance context from DS-04 | Dependency | Agree the template with the content and SEO teams |
| The Master SEO Document is consistent enough across clients to read automatically | Evidence-thin | Test on 2–3 clients |
| The Monday integration builds on the Make set-up, whose gaps sit with Sid Bali (C-31) | Dependency | Review with Sid |
| Depends on the AI data rule (DS-02) | Dependency | DS-02 first |

### DS-04 · AI client brain (per client)
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Time saved (~6–9 h/month): ~36 meetings a month (31 clients with a monthly meeting + Tier 2 quarterly, client board) × 15–20 min prep today → ~5 min with the brain (Austin input) | Hours | Time call prep for a sample of managers |
| Needs client call-recording consent, the AI data rule (DS-02) and read access to Slack, email and ad platforms | Dependency | Consent wording; DS-02; access audit |
| One client-record template agreed across organic and paid | Dependency | Workshop with both teams |
| Slack and email can be reliably tagged to the right client | Evidence-thin | Pilot on 5 clients |

### DS-05 · Automated deck generator: quarterly + 6-month reviews and proposals
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Time saved (~22–32 h/month): 60% of clients get a six-month review and 20% quarterly, 1.5–2 h a deck, proposals 1.5 h (Austin input); ~30 min to review and 6–8 proposals a month are assumptions (proposals conservative) | Hours | Time the next three review decks |
| Jethro Jason wasn't recorded, so proposal evidence is leadership plus one delivery staff member | Evidence-thin | Interview Jethro |
| Needs one current master template per deck type, the AI data rule (DS-02) and data access | Dependency | Template owner; DS-02 |
| Laura is comfortable with AI-drafted 6-month reviews for smaller clients (LS-O11); larger clients may need more hand-written narrative | Evidence-thin | Confirm the client cut-off with Laura |

### DS-06 · Request sweeper ("Roomba")
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – value is that nothing gets missed (not measured) | – | Count requests captured in a 2-week pilot |
| Reading DMs needs each person's authorisation; email needs each person's Gmail authorisation | Dependency | Staff opt-in; DS-02 rule |
| Monday's Slack integration already turns a message into a task by hand; the sweeper adds automatic detection | Evidence-thin | Check Monday's current integration |
| Some junk tasks at first; rules tuned over the first few weeks | Evidence-thin | Track false positives in the pilot |

### DS-07 · Link watchdog agent
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Dead-link rate from one one-off report (~100 over ~10 months); the audit notes a document check found a much higher fault rate (32% of ~1,016 links checked Jan–Apr), so the real figure may be higher | Evidence-thin | Run one full check of live paid links |
| Price per link ~$80–$130: the page cites KZ-PP10, but the audit traced it to the context pack and order sheets, not the interview | Pricing | Check the order book |
| Up to ~A$10K–16K a year recovered: ~10 lost links a month (Karl) × ~A$80–130 a link; assumes publishers refund or re-place once a loss is noticed (Austin input), and some losses are already found by hand | Evidence-thin | Review publisher terms |
| Needs one clean link list with URLs and requirements (DS-11) | Dependency | DS-11 first |
| Jev AI's fit (scale, scheduling, change detection) | Pricing | Trial |

### DS-08 · AI sales handover
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – a new standard: at least an hour of prepared information before kick-off (Austin input) | – | Time the next three handovers |
| Sales calls are recorded with prospect consent and transcripts are reachable | Dependency | Check with Jethro and Joe |
| Jethro wasn't interviewed – the sales side of the evidence is leadership's view | Evidence-thin | Interview Jethro |
| Depends on DS-04 and the AI data rule (DS-02) | Dependency | DS-02, DS-04 first |

### DS-09 · AI-prefilled onboarding audit and Master SEO Document
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Time saved (~10–22 h/month): 10–12 h per SEO onboarding and 3–4 new clients a month (Austin input); 2–3 of them SEO and AI cutting 50–60% are assumptions | Hours | Time the next two onboardings |
| Needs read-only access at signing (DS-08 add-on) and the AI data rule (DS-02) | Dependency | DS-02, DS-08 |
| The 30-item paid audit checklist is current and can be encoded | Evidence-thin | Review with Wendlley |

### DS-10 · Systems register and break-fix runbook
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – value is no reliance on one person (risk, not measured) | – | – |
| Kept up to date only if adding an entry is part of "done" for every build | Dependency | Make it a rule |
| A second admin has capacity to be trained | Dependency | Julia to name the person |

### DS-11 · Link-building workflow CRM
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Time saved (~18.5–30 h/month): ~320 links a month (client board) × 5–8 min admin a link (Austin input); the CRM removing ~70% is an assumption. Freed time ≈ 9–15 more links a month at ~2 h a link – delivery capacity, not extra revenue | Hours | Time one month of order and invoice admin |
| External publishers will use a portal or filtered view rather than their own sheets – some brokers may refuse | Evidence-thin | Ask Tonie's top outreachers |
| Existing sheets can be migrated without losing link history or order IDs | Evidence-thin | Test migration on one month |
| Payment method stays the same; only tracking moves | Dependency | Confirm with Joe |

### DS-12 · Link supply engine
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Time saved (~7.5–17 h/month): 60 domains take 1–2 h to vet (Karl); about half approved (Austin input); AI pre-vetting removing 70–80% is an assumption | Hours | Time a few vetting batches |
| Karl's vetting criteria can be written down and tested on past decisions | Evidence-thin | Back-test on 100 past decisions |
| Clients accept quota changes where supply is scarce | Evidence-thin | Ask account managers |

### DS-13 · Covered by DS-14 (escalation and delegation rules)
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Not valued separately – part of DS-14 | – | Julia to estimate escalation hours |
| Leads get short coaching on escalations and client comms (MP-PP08) | Dependency | Culture recommendation P-41 |
| Joe sets the contract value threshold | Dependency | Joe |

### DS-14 · Client health & growth intelligence
| Assumption | Type | How to confirm |
| --- | --- | --- |
| **Churn ~4% a month → ~2.5% (~18 clients × ~A$2,500 × 12 ≈ A$540K a year kept)** – Austin's estimate and target; see the box at the top | Evidence-thin (Austin's estimate) | Joe – is the recent churn typical? |
| No time saved claimed | – | – |
| Depends on DS-04 being live with transcripts, email and Slack | Dependency | DS-04 first |
| Profiling client contacts needs the AI data rule and a clear line on what's stored about individuals; staff are not profiled | Dependency | DS-02; privacy check |
| "Gets smarter" only if outcomes are logged for every alert | Dependency | Account managers log outcomes |
| Signals are suggestions; people still own the escalation | – | – |

### DS-15 · AI Business Brain – the umbrella
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – value is better visibility for leadership (not measured); the brain's members (DS-02, DS-04, DS-10, DS-14) carry their own value | – | – |
| Adoption is the main risk: it must live in Slack and Monday and come with training (KO-PP10, KO-PP14) | Dependency | Adoption plan (risk 2) |
| Needs the AI data rule (DS-02) | Dependency | DS-02 first |
| The existing Slack assistant (OpenClaw) can be reused or replaced | Evidence-thin | Review with Joe |

### DS-16 · Seasonal & trending content radar
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – value is ideas and a stronger service offering (not measured); evidence from organic only (2 people) | Evidence-thin | Ask paid strategists whether they'd use it |
| Competitor lists and niche keywords exist or can be pulled from the Master SEO Document | Dependency | Check 5 clients |
| Alert volume tuned per client | Evidence-thin | Pilot |

### DS-17 · Client files and logins in company-owned locations
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – value is nothing lost when someone leaves (risk, not measured) | – | – |
| LastPass stays as the password manager | Dependency | Joe |
| Staff move files across in a set migration window | Dependency | Julia to schedule |

### DS-18 · Landing page generator
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion; evidence is leadership plus one staff member | Austin addition | – |
| Pages published on a builder Aperitif controls (not the client's CMS) | Dependency | Trial one builder |
| Value not measured – a new service offering; pages outsourced per year unknown (~A$1,500 a page quoted by Wendlley) | Evidence-thin | Wendlley to count pages outsourced |

### DS-19 · AI receptionist
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion; weak interview evidence | Austin addition | – |
| Aircall add-on ~A$370/month for 1,000 minutes | Pricing | Re-check before signing |
| Value not measured – no call or missed-call volumes | Evidence-thin | Pull Aircall call logs |

### DS-20 · New-client dossier agent
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion, supported by one leadership quote (KO-PP22) | Austin addition | – |
| Public information only; LinkedIn data access to be confirmed | Dependency | Check LinkedIn terms |
| Value not measured – a new standard; only Julia researches new clients today (~20 min, Austin input) | – | Julia to confirm time per new client |

### DS-21 · AI creative tools
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's addition; tool list from web research, Nov 2026, not interviews | Austin addition | – |
| Prices and features from vendor and review sites, Nov 2026 (mostly USD) | Pricing | Verify before buying |
| Output quality for lead-gen and service clients is the open question | Evidence-thin | One-month trial on real clients |

### DS-22 · SEO: Monday client performance check
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Time saved (~17–39 h/month): 68 live SEO clients (client board) × 5–10 min weekly check (Austin input); the digest removing 70–80% is the target, not a measured figure | Hours | Time the current Monday checks |
| API access to every client's GA4, Search Console and Ahrefs | Dependency | Access audit |
| Thresholds agreed per client by the SEO team | Dependency | SEO team |

### DS-23 · SEO: drop and anomaly alerts
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Thresholds tuned per client so managers aren't flooded | Evidence-thin | Pilot |
| Time saved (~7–11 h/month): ~0.4 drops per client a month, 20–30 min each today (Austin input) → ~5 min with the alert (assumption) | Hours | Count drops and time investigations for a month |

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
| Value counted in DS-01 – the investigation time is part of the weekly check valued there; don't add it again | – | Time investigations for two weeks |
| Needs API access to ad accounts, GA4 and the CRM | Dependency | Access audit |

### DS-28 · Client comms assistant
| Assumption | Type | How to confirm |
| --- | --- | --- |
| Austin's suggestion, supported by SH-PP09 and KO-PP20 | Austin addition | – |
| Managers approve every message; nothing goes to clients automatically | Dependency | Rule in DS-02 |
| No hours claimed – value is consistent, faster client updates (not measured) | – | – |

### DS-29 · PPC: Monday client performance check
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – a new standard of client communication (not measured; the check time is valued in DS-01) | – | – |
| API access to every live ad account and GA4 | Dependency | Access audit |
| Check list agreed with Wendlley | Dependency | Wendlley |

### DS-30 · Daily priorities assistant
| Assumption | Type | How to confirm |
| --- | --- | --- |
| No hours claimed – value is focus each morning; how people plan their day is personal (not measured) | – | Pilot with 3–4 people |
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

- **Time saved and capacity unlocked** are the same hours counted two ways – read them as either/or.
- **DS-27 and DS-29** claim no hours of their own; the paid monitoring time is counted once, in DS-01.
- **DS-11 and DS-12** count separate steps of the link process (admin vs vetting); their extra links are delivery capacity inside SEO retainers, not revenue on top of the SEO figures.
- **DS-13** is part of DS-14 and not valued separately.
- **DS-15** claims no value of its own; don't re-add DS-02, DS-04, DS-10 or DS-14 under it.
