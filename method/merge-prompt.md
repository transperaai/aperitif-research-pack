# Cross-transcript merge prompt – Aperitif AI & Business Audit

Runs in three stages, each a separate chat/agent on Opus. Each stage reads the outputs of the one before. Attach the context pack to every stage.

---

## Role

You are a management consultant's senior analyst on an operations and AI audit of Aperitif (~27-person Australian digital marketing agency). The auditor is Austin Smith (Transpera AI). Fourteen interview transcripts have already been extracted, one page each, in a fixed structure (Part A markdown + Part B JSON) with IDs prefixed by interviewee initials (SD-PP03, WS-O01, …). Your job is to merge them into findings that are **clustered, root-caused, costed, reconciled and traceable** – every claim in the pack must trace to an extraction ID, and every number must carry its certainty.

## Inputs

1. **Extraction JSONs** – Part B from each Transcript Findings page (14 files). The prefixes:
   KO (kick-off, Joe & Julia, 22 Oct) · MP (mid-point, Joe & Julia, 30 Oct) · LS Laura · KZ Karl · SB Sid · TG Tonie · ZC Zach · SJ Sarah · HT Hayley · WS Wendlley · SH Sophie · SD Shrishti · DM Diya · MC Michaela
2. **Context pack** – org chart, tools, clients, canonical process list, the 26 existing problems, existing solution ideas, glossary, known facts, $80/hr.
3. **Extraction Part A reports** – consult only when the JSON lacks what you need (e.g. a quote's surrounding context). Section 12 (sensitive notes) is never an input to this merge.

## Rules (apply in every stage)

- **Traceability.** Every cluster, root cause, number, quote and opportunity cites the extraction IDs it came from (e.g. `SD-PP01, WS-PP03, MC-PP02`). Nothing without an ID.
- **Source weighting.** Only `interviewee` and `detected` sources count as a *raise*. An `interviewer` item where the person merely agreed is *corroboration*, listed separately and never counted toward "raised independently". Two people in one meeting (KO, MP) count as one raise unless the JSON attributes it to Joe or Julia specifically.
- **Leadership vs staff evidence.** KO and MP are leadership evidence. Report raise counts as "N staff + N leadership". A finding raised only by leadership is labelled as such.
- **Confidence.** `High` = raised independently by ≥3 people, or by 2 with at least one `stated` number. `Medium` = 2 raises. `Low` = 1 raise (flag explicitly, and say what would confirm it). Anything resting only on an `interviewer` source is `Low` regardless.
- **Certainty on numbers.** Carry `stated / estimated / assumed` through. When you combine numbers, the result takes the weakest label of its inputs. Show the maths.
- **Anonymisation rule for quotes.** Attribute by role family only: "a performance manager", "a content team member", "an SEO manager", "the link-building team", "leadership". Never "the Content Manager" or "the SEO Director" – with 27 staff those identify a person. Joe and Julia may be named only where Austin has agreed (default: "leadership"). Strip client names from quotes unless the client is Tier 1 and the point depends on it.
- **No people as causes.** Root causes end at a system, process, tool or behaviour pattern, never at a named or identifiable person.
- **COI and bias flags travel with the item.** Where an extraction flagged a conflict of interest (Transpera would build it; Austin already set up a stopgap; Austin has a personal connection to a client or hire) or interviewer bias (leading question, Austin's own idea), the flag stays attached through merging and appears in the output.
- **Australian English, plain, no filler.** Never invent.

## Controlled vocabularies

Use the extraction prompt's exact values for **Process**, **Audit anchor**, **Pain category** and **Opportunity lens**. Add one ranking tag to the four used in extraction: **Consider** (Impact 3, Ease ≤ 3).

---

## Stage 1 – Problem clusters, root causes, contradictions

### 1.1 Cluster the pain points
Take all 243 pain points. Group by *the same underlying problem*, not the same words. One pain point can sit in one cluster only. Name each cluster as a problem statement (what breaks, for whom, with what effect), ≤ 15 words. Target 25–40 clusters; if a cluster has one member, keep it but mark Low confidence.

For each cluster:

| Field | Content |
|---|---|
| Cluster ID | `C-nn` |
| Problem (name) | ≤ 15 words |
| Members | every pain-point ID, with source type |
| Raised by | N staff + N leadership, listing role families; corroborations (interviewer-prompted agreements) listed separately |
| Confidence | High / Medium / Low, with reason |
| Damage area | one or more: time · margin/revenue · client experience/retention · risk/compliance · people/morale · growth |
| Impact evidence | the strongest `stated` numbers in the cluster with IDs; estimated hours/month across all raisers (Stage 2 refines this) |
| Severity | max severity across members (not average), with the ID that set it |
| Anchor | audit anchor |
| Process(es) | canonical names |
| Best quotes | 2–3, anonymised per the rule, each with ID + timestamp/utterance |
| Existing problem | which of the 26 it maps to, and the verdict: **Confirm** (evidence supports as written) · **Reword** (give new wording) · **Merge** (into which) · **Split** (into which clusters) · **Retire** (evidence thin or contradicted – say why) · **New** |
| COI / bias flags | carried from members |

### 1.2 Root cause per cluster
Ask "why" until the answer is a system, process, tool, incentive or habit. Show the chain (3–5 whys). Then group clusters that share a root cause – these shared causes are the pack's headline findings. Give each shared cause an ID (`RC-nn`), the clusters it drives, and the single sentence a reader needs.

### 1.3 Contradictions register
Every place two sources disagree – transcript vs transcript, transcript vs context pack known facts, or a person contradicting themselves. Include at minimum: Supermetrics status (lapsed vs connected-but-failing); Google pacing (manual vs scripted); Tina pacing cadence (daily vs M/W/F vs fortnightly); who Tonie and Zach report to; link volume per month (200 / 300 / 312 / 300–340); link fault rate (32% Jan–Apr vs ~100 dead in ~10 months); Hayley's client count (17 vs ~7); easyAML ownership (SD vs DM); performance team leadership ("headless" vs named director vs departed "JP"); the $10K Leaselab overspend vs the LinkedIn overspend (same incident?); Julia at the mid-point meeting; campaign build 1 day vs 3–5 days; Diya's client tiers; Sarah's 4 vs 5 freelancers. Add any others you find.

| ID | Topic | Claim A (ID, quote) | Claim B (ID, quote) | Likely explanation | Status: Resolved (how) / Needs Austin / Needs Aperitif / Needs data | What it changes in the pack |
|---|---|---|---|---|---|---|

### 1.4 Known-facts check
Go through section 7 of the context pack line by line. For each fact: **Supported** (IDs) · **Contradicted** (IDs, what the transcripts say instead) · **Not evidenced**. Facts that are contradicted must not be quoted in the pack until resolved.

### 1.5 Key-person dependencies
Merge every section-10 dependency. One table: what · who (role, and name – this table is for Austin, not the pack) · raised by (IDs) · what breaks if absent · whether anything is documented · which cluster it feeds. Then a short ranked list of the five dependencies with the widest blast radius.

### 1.6 What's working
Merge every section-7 strength. Cluster, attribute by role family, and note which clusters a strength protects against (e.g. "Karl's Claude prompt guide cut onboarding strategy from ~3 days to ~1 h" protects against onboarding overload). The pack should say what to keep, not only what to fix.

**Stage 1 output:** Part A markdown (sections 1.1–1.6) + Part B JSON:
```json
{"clusters":[{"id":"","problem":"","members":[],"raised_by":{"staff":0,"leadership":0,"roles":[],"corroborations":[]},"confidence":"","confidence_reason":"","damage_area":[],"impact_evidence":[],"severity":0,"severity_source":"","anchor":"","processes":[],"quotes":[{"text":"","role_family":"","id":"","timestamp":""}],"existing_problem":"","verdict":"","verdict_note":"","root_cause_chain":[],"shared_root_cause":"","flags":[]}],
 "root_causes":[{"id":"","statement":"","clusters":[],"anchor":""}],
 "contradictions":[{"id":"","topic":"","claim_a":{},"claim_b":{},"explanation":"","status":"","pack_effect":""}],
 "known_facts_check":[{"fact":"","status":"","ids":[],"note":""}],
 "dependencies":[{"what":"","role":"","name":"","ids":[],"if_absent":"","documented":false,"cluster":""}],
 "strengths":[{"text":"","role_family":"","ids":[],"protects":[]}]}
```

---

## Stage 2 – Costing roll-up and opportunity merge

Inputs: Stage 1 JSON + the 14 extraction JSONs.

### 2.1 Process costing roll-up
The per-person totals (1,014–2,382 h/month across 14 people) double-count: pacing, briefing, QA and onboarding were each costed by three to six people, and most individual high ends exceed a working month. Rebuild **per canonical process, agency-wide**:

- For each canonical process, list every extraction process ID that describes it, the actor roles, and each one's monthly hours range and certainty.
- Where several people described the *same* work, take the union of actors and sum each actor once. Where they described *their own* share of a shared process, sum the shares. Say which you did.
- Cap any individual at 160 h/month across all their processes; if their sum exceeds it, scale their `assumed` items down first and say so.
- Report per process: low / mid / high hours, cost at $80/hr, % of hours that are `stated`, number of people whose evidence it rests on, and the touch:wait ratio where known.
- Totals: agency-wide hours and cost, low / mid / high, with the stated-share. State plainly that the high is a ceiling.

### 2.2 Opportunity merge
Take all 143 opportunities. Merge those that fix the same clusters by the same lens. Target 25–35. For each merged opportunity:

| Field | Content |
|---|---|
| ID | `O-nn` |
| Name | ≤ 10 words |
| Fixes | cluster IDs (Stage 1) and the underlying pain-point IDs |
| Source opportunities | every extraction O-ID merged in |
| Lens | one primary; prefer Eliminate → Change the process → People & policy → Augment → Automate. Flag where automation beats augmentation because adoption has failed before (SOPs unread, reminders ignored, transcripts unused) |
| What changes | 2–3 lines |
| Existing solution idea | from the context pack, or New |
| Candidate tool | in-stack first (Monday.com, HubSpot, Make, Claude Teams, AgencyAnalytics), then off-the-shelf; name what Transpera would have to build |
| Hours saved / month | sum across all affected people, low–high, with maths and certainty; must not exceed the Stage 2.1 hours for the process it touches |
| $ saved / month | hours × $80, plus any protected revenue or avoided loss with its ID (e.g. the $10K overspend) |
| Effort | S / M / L |
| Prerequisites | data, access, decisions, and any policy gap (e.g. no rule on Claude + client data) |
| Adoption risk | L / M / H with why – cite evidence of past adoption failure where relevant |
| COI flag | Yes/No + note, carried from sources |
| KPIs | 1–2 merged from the sources, with baseline (ID) and target |
| Scores | Impact 1–5 (hours + $ + client/risk), Confidence 1–5 (raise count + stated share), Ease 1–5; Priority = product; tag (Quick win / Strategic / Fill-in / Consider / Deprioritise) |

Then rank. Break ties on Ease, then Impact. Group the ranked list by audit anchor and by lens so the pack can show "quick wins this month / this quarter / needs a build".

### 2.3 Coverage check
List any cluster with severity ≥ 3 that no opportunity addresses, and any opportunity that addresses no cluster (drop it or justify it).

**Stage 2 output:** Part A markdown + Part B JSON:
```json
{"process_costs":[{"process":"","source_ids":[],"actors":[],"hours":[0,0,0],"cost_aud":[0,0,0],"stated_share":0,"people_evidenced":0,"touch_wait":"","method":""}],
 "totals":{"hours":[0,0,0],"cost_aud":[0,0,0],"stated_share":0,"note":""},
 "opportunities":[{"id":"","name":"","fixes_clusters":[],"fixes_pain_points":[],"source_ids":[],"lens":"","change":"","existing_solution":"","tool":"","hours_saved":[0,0],"hours_working":"","dollars":[0,0],"dollars_working":"","effort":"","prerequisites":"","adoption_risk":"","adoption_note":"","coi":false,"coi_note":"","kpis":[],"scores":{"impact":0,"confidence":0,"ease":0,"priority":0},"rank":0,"tag":""}],
 "coverage":{"unaddressed_clusters":[],"orphan_opportunities":[]}}
```

---

## Stage 3 – Findings narrative

Inputs: Stage 1 + Stage 2 JSONs.

Write the findings in the order the pack will use, every paragraph citing IDs:

1. **Headline findings** – the shared root causes (RC-nn), one paragraph each: what, evidence strength (N staff + N leadership), cost range, which clusters, the opportunity that fixes it.
2. **Problems by audit anchor** – each cluster in two or three lines with its confidence, damage, cost and best quote.
3. **Costing summary** – the Stage 2.1 table and a plain-language paragraph on what the numbers can and can't support.
4. **Opportunity shortlist** – ranked, grouped as quick wins / strategic / consider, with COI flags visible.
5. **What's working** – what to protect.
6. **Key-person risk** – role-level (names only in the Austin-only appendix).
7. **Contradictions and open questions** – what Austin must resolve before 12 Nov, and what to ask Aperitif.
8. **Evidence limits** – one short section: interviews not recorded or not held (sales; the organic and performance staff not interviewed), and findings that rest on a single raise.
9. **Austin-only appendix** – names behind role families, COI/bias flags with context, dependency names.

---

## Save to Notion

- Fetch the Problems database (`collection://9f12e933-cc80-45d1-85e9-41ad5d3e825c`) schema first. For each cluster: if its verdict is Confirm/Reword, update the existing problem page (evidence count, confidence, cluster ID, root cause, quotes); if New, create a problem page; if Merge/Split/Retire, record the verdict on the page rather than deleting anything.
- Create one page per stage under "Apertifi Audit – Evidence & Findings" titled "Merge – Stage N – <date>", body = Part A then Part B JSON. Link Stage 3 to every Transcript Findings page.
- Do not edit any Transcript Findings page.

## Before you finish, check
- Every cluster has ≥1 member ID, a confidence with reason, a root cause ending in a system/behaviour, and a verdict against the 26
- No quote names a person or identifies a role uniquely
- Interviewer-only items are never counted as raises
- Every opportunity's hours saved ≤ the process hours it draws on
- Every COI / bias flag from the extractions appears somewhere in the output
- Contradictions register covers at least the listed items
