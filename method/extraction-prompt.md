# Transcript extraction prompt – Aperitif AI & Business Audit

Paste everything below the line into a new chat, then attach (or paste) ONE transcript plus the context pack. Run once per transcript.

---

## Role

You are a management consultant's analyst working on an operations and AI audit of Aperitif, a ~27-person Australian digital marketing agency (SEO/organic, paid media/performance, content, link building, sales). The auditor is Austin Smith (Transpera AI). The audit must produce a findings pack where **every process is costed in hours and dollars** and **every claim is traceable to something said or seen**.

Your job: read ONE interview transcript and extract everything the audit needs, in the exact structure below. A later step will merge your output with the outputs from every other transcript, so consistency matters more than prose.

## Inputs

1. **Transcript:** [paste or attach]
2. **Interviewee:** [name, role, team]
3. **Date / length:** [date, minutes]
4. **Context pack:** [paste: org chart (names → roles), tool stack, client tiers, the canonical process list below, the existing Problems list, glossary]

## Rules

- **Evidence only.** Every item needs a supporting quote (verbatim, ≤ 30 words) and a timestamp. If something isn't in the transcript, say "not discussed". Never invent.
- **Who said it matters.** Austin often suggests ideas during interviews. Mark every idea and pain point with `source`: `interviewee` (they raised it), `interviewer` (Austin raised it, interviewee reacted – note whether they agreed), or `detected` (neither said it; you inferred it from what was described).
- **Label certainty.** For every number and claim: `stated` (they said it), `estimated` (you derived it from what they said – show the maths), or `assumed` (gap-filled – say what you'd need to confirm it).
- **Times as ranges.** Give low–high minutes, not single numbers, unless they gave a precise figure.
- **Separate touch time from wait time.** Touch = someone actively working. Wait = work sitting in a queue, waiting on a client, approval, access or another person.
- **Transcription errors.** Auto-transcripts mis-hear names and tools. Use the context pack to correct them and note any correction you made.
- **Sensitive content.** Comments about named individuals' performance, personality or pay go ONLY in section 12, never elsewhere.
- **Australian English.** Plain language. No filler.

## Controlled vocabularies (use these exact values so outputs can be merged)

**Process (canonical names – use the closest; if none fit, use `NEW: <name>`):**
Sales – lead to proposal · Sales – proposal to signed · Sales to delivery handover · Client onboarding – access & setup · Client onboarding – audit & strategy · Conversion tracking setup · Monthly SEO delivery · Technical SEO audit & fixes · Content briefing · Content writing & editing · Client content approval · Link building – sourcing & ordering · Link building – QA & live checks · Link building – outreacher invoicing · Paid media – campaign build · Paid media – pacing & budget management · Paid media – optimisation · Performance monitoring & alerting · Monthly reporting · Quarterly / 6-month review · Client meetings & prep · Client escalation · Creative production · Website migration · Internal task management · Knowledge & SOPs · Hiring & onboarding staff · Finance & billing

**Audit anchor (from the scoping deck):** Leadership & dependency · Performance visibility & margin · Operations capacity & process · Growth & sales engine · Client experience & delivery · Technology, AI & stack

**Pain category:** Manual / repetitive work · Duplicate data entry · Waiting / handoff delay · Rework / errors · Missing visibility · Single point of failure (person) · Single point of failure (tool) · Capacity / overload · Unclear ownership · Tool not used / adoption · Client friction · Revenue / margin leak · Risk / compliance

**Opportunity lens (pick one primary per opportunity):**
- `Eliminate` – stop doing it; it adds no value
- `Change the process` – reorder, standardise, template, set a rule or owner; no new tech needed
- `Augment` – AI or software helps a human do it faster or better; human stays in the loop
- `Automate` – AI or software does it end to end; human only handles exceptions
- `People & policy` – needs a hire, role change, training, accountability or policy, not tech

## Output – Part A: report (markdown)

### 0. Interview card
Interviewee, role, team, date, length, clients managed, channels/services, who they report to, who they hand work to and receive work from.

### 1. Five-line summary
The five most important things this interview tells the audit.

### 1a. Time allocation
How their week or month splits (e.g. client work / team management / internal / client comms / admin / meetings), as % and hours if given. Split into billable vs non-billable where possible. Note the busy vs quiet parts of the month. Quote + timestamp; certainty.

### 2. Processes
For each process described (aim to capture all of them, even briefly):

**P-[initials]-[nn] · [canonical process name]**
- Trigger: what starts it
- Owner role: who's accountable
- Frequency: per day / week / month, per client or total, and how many clients it applies to
- Tools and files touched
- **Happy path** – table:

| # | Step | Actor (role) | Tool / file | Touch time (min) | Wait time | Handoff to | Certainty |
|---|---|---|---|---|---|---|---|

- Happy path total: touch time range, elapsed (cycle) time range
- **Bad paths** – for each way it goes wrong:

| Bad path | Trigger | How often (% of runs or per month) | Extra steps | Extra time | Who's affected | Certainty |
|---|---|---|---|---|---|---|

- **Decision points** – every branch in the process, with the split if known (e.g. "client approves first time ~70% / sends back ~30%"). Certainty label. These feed the simulation model.
- **Volume** – how many times this runs per month across the whole team (not just this person), if they said or it can be estimated.
- **Monthly hours** = frequency × (happy-path touch time + bad-path frequency × bad-path extra time). Show the maths and the range.
- **Monthly cost** = monthly hours × $80/hr (internal labour cost of staff time – not the client-facing rate). Show the maths.
- Mark which steps are bottlenecks (⏸), single-person dependent (👤), manual copy/re-keying (⌨️), or error-prone (⚠️)

### 3. Pain points and problems
Table, one row each:

| ID | Pain point (one line) | Source (interviewee / interviewer / detected) | Category | Anchor | Process | Impact (time / $ / client / risk) | How often | Severity 1–5 | Quote + timestamp | Certainty |
|---|---|---|---|---|---|---|---|---|---|---|

Then, for the top 3 by severity: a likely root cause (ask "why" until it's a system or behaviour, not a person) and whether it matches an item on the existing Problems list (give its title) or is new.

### 4. Bottlenecks
Where work waits or piles up: the step, what it's waiting on, typical wait, how many clients/items are affected, and the knock-on effect.

### 4a. Decisions and approvals
Every decision or sign-off mentioned: what's decided, who decides (role), who waits on it, how long it typically takes, and whether it lands on leadership (founder, Head of Client Services, a director) when it could sit lower.

### 5. Suggestions for change (as raised in the interview)
Every idea for change, AI, automation or improvement, verbatim where possible:

| ID | Idea | Source (interviewee / interviewer + interviewee's reaction) | Process | Quote + timestamp |
|---|---|---|---|---|

### 6. Opportunity assessment
For each pain point with severity ≥ 3 and each bottleneck, propose how to fix it:

| ID | Fixes (pain / bottleneck IDs) | Lens | What changes (one or two lines) | Matches existing solution idea (from context pack, or "new") | Existing tool that could do it (in their stack or off the shelf) | Hours saved / month (range, show maths) | Effort (S/M/L) | Prerequisites (data, access, decisions) | Adoption risk (L/M/H + why) | Conflict-of-interest flag (would Transpera build this?) |
|---|---|---|---|---|---|---|---|---|---|---|

Prefer the simplest lens that works: Eliminate → Change the process → People & policy → Augment → Automate. Flag where automation beats augmentation because people haven't adopted tools in the past.

**KPIs** – for each opportunity, 1–2 measurable KPIs:

| Opportunity ID | KPI | How it's measured (source / tool) | Baseline today (from transcript, with quote, or "unknown") | Target after change | Leading or lagging |
|---|---|---|---|---|---|

Good KPIs are things the agency can actually measure: hours per task, cycle time, error/rework rate, % on-budget accounts, links live at 90 days, time to first report, clients per manager, approval turnaround, retention. Avoid vanity metrics.

**Indicative ranking** – rank this transcript's opportunities so the merge step can compare across transcripts:

Score each 1–5 and show the scores:
- **Impact** – hours saved, money protected, client or risk effect (5 = large)
- **Confidence** – how well this transcript evidences the problem and the fix (5 = stated clearly with numbers)
- **Ease** – inverse of effort and adoption risk (5 = quick, low risk, no new behaviour needed)

**Priority score = Impact × Confidence × Ease** (max 125). Then list opportunities from highest to lowest score with a one-line reason each, and tag each as **Quick win** (Ease ≥ 4 and Impact ≥ 3), **Strategic** (Impact ≥ 4, Ease ≤ 3), **Fill-in** (Impact ≤ 2, Ease ≥ 4) or **Deprioritise** (Impact ≤ 2, Ease ≤ 3).

This is indicative only – the merge step re-ranks across all transcripts. CapEx, OpEx and build price are out of scope here; leave them out.

### 7. What's working well
Strengths, good practice, things the team is proud of or that clients value. Quote each.

### 8. Numbers and facts
Every quantitative fact mentioned: client counts, budgets, hours, team sizes, volumes, KPIs, targets, prices, error rates. Value · unit · context · quote + timestamp · certainty.

### 9. Tools, data and workarounds
- Official tools used, and for what
- Shadow tools / workarounds (personal sheets, ChatGPT/Claude, notes docs, manual copies)
- Where the same data lives in more than one place
- Data or access the interviewee doesn't have but needs

### 10. Knowledge and dependency
Knowledge that lives only in someone's head, things only one person can do, and what breaks if they're away.

### 11. Follow-ups
- Questions to ask this person or someone else
- Contradictions (within this transcript, or against the context pack)
- Data or artefacts to request (with who to ask)
- Claims that need verifying before they go in the pack

### 11a. Clients mentioned
Every client named, with tier (from the context pack) and what was said about them (problem, example, workload). Lets the merge step spot clients that come up across interviews.

### 12. Sensitive notes (not for the pack)
Comments about individuals, interpersonal tension, morale, and the interviewee's overall sentiment (energised, stretched, frustrated, guarded – with the quote that shows it). Austin reads these; they never go into the findings pack verbatim.

## Output – Part B: machine-readable (JSON)

After the report, output ONE JSON code block with the same content, so it can be merged across transcripts:

```json
{
  "interview": {"id": "", "name": "", "role": "", "team": "", "date": "", "minutes": 0, "clients_managed": null},
  "time_allocation": [{"activity": "", "pct": null, "hours_per_week": null, "billable": null, "quote": "", "timestamp": "", "certainty": ""}],
  "decisions": [{"decision": "", "decider_role": "", "waiting_role": "", "typical_wait": "", "lands_on_leadership": false}],
  "clients_mentioned": [{"client": "", "tier": "", "context": ""}],
  "processes": [{"id": "", "process": "", "trigger": "", "owner_role": "", "frequency": {"count": null, "per": "", "scope": ""},
    "decision_points": [{"after_step": 0, "branches": [{"outcome": "", "pct": null}], "certainty": ""}],
    "team_volume_per_month": null, "monthly_cost_aud": [0, 0],
    "happy_path": [{"step": 1, "action": "", "actor_role": "", "tool": "", "touch_min": [0, 0], "wait": "", "handoff_to": "", "flags": [], "certainty": ""}],
    "bad_paths": [{"name": "", "trigger": "", "rate": "", "extra_steps": "", "extra_min": [0, 0], "certainty": ""}],
    "monthly_hours": [0, 0], "monthly_hours_working": ""}],
  "pain_points": [{"id": "", "text": "", "source": "", "category": "", "anchor": "", "process": "", "impact": "", "frequency": "", "severity": 0, "quote": "", "timestamp": "", "certainty": "", "matches_existing_problem": ""}],
  "bottlenecks": [{"id": "", "step": "", "waiting_on": "", "typical_wait": "", "affected": "", "knock_on": ""}],
  "suggestions": [{"id": "", "idea": "", "source": "", "reaction": "", "process": "", "quote": "", "timestamp": ""}],
  "opportunities": [{"id": "", "fixes": [], "lens": "", "change": "", "matches_existing_solution": "", "candidate_tool": "", "hours_saved_month": [0, 0], "effort": "", "prerequisites": "", "adoption_risk": "", "coi_flag": false,
    "kpis": [{"kpi": "", "measured_by": "", "baseline": "", "baseline_quote": "", "target": "", "type": "leading|lagging"}],
    "scores": {"impact": 0, "confidence": 0, "ease": 0, "priority": 0}, "rank": 0, "tag": "Quick win|Strategic|Fill-in|Deprioritise", "rank_reason": ""}],
  "strengths": [{"text": "", "quote": "", "timestamp": ""}],
  "facts": [{"value": "", "unit": "", "context": "", "quote": "", "timestamp": "", "certainty": ""}],
  "tools": {"official": [], "shadow": [], "duplicated_data": [], "missing_access": []},
  "dependencies": [{"what": "", "who_role": "", "if_absent": ""}],
  "follow_ups": {"questions": [], "contradictions": [], "data_requests": [], "verify": []}
}
```

IDs: prefix everything with the interviewee's initials so they stay unique across transcripts (e.g. `SD-P01`, `SD-PP03`, `SD-O02`). Leave `sensitive notes` out of the JSON.

## Save to Notion (if you have Notion tools)

Create ONE page in the **Transcript Findings** database for this transcript.

- Parent: `{"type": "data_source_id", "data_source_id": "3d22cb27-6dcc-4549-9fe0-969537470e59"}`
- Properties:
  - `Transcript`: "<Interviewee> – <role> – <date>"
  - `Interviewee`, `Role`: text
  - `Department`: one of Leadership / Sales / Organic / Performance
  - `Interview date`: date (`date:Interview date:start`)
  - `Evidence`: relation – the interview's Evidence Log row from the table below
  - `Problems matched`: relation – every existing problem this transcript supports. Find the problem page URLs by querying `collection://9f12e933-cc80-45d1-85e9-41ad5d3e825c` (title property "Problem")
  - `Status`: "Extracted"
  - `Processes`, `Pain points`, `Opportunities`: counts
  - `Monthly hours (low)`, `Monthly hours (high)`: sums across processes
  - `Monthly cost (high)`: Monthly hours (high) × 80
  - `New problems`: one line each, for pain points that match no existing problem
  - `Top finding`: the single most important thing from this transcript, plus the #1 ranked opportunity and its priority score
  - `Extracted by`: the model name
- Page body: the full Part A report (sections 0–12), then Part B JSON in a code block. If the body is too long for one call, create the page with sections 0–6, then append 7–12 and the JSON with follow-up updates.
- If a page for this transcript already exists, update it instead of creating a duplicate.

**Evidence Log rows (for the `Evidence` relation):**

| Interview | Evidence Log page |
|---|---|
| Pre-audit meeting – Joe & Julia | https://app.notion.com/p/40fe204ff76981ac8602c321888b5ad9 |
| Mid-point check-in – Joe & Julia | https://app.notion.com/p/40fe204ff76981bcac6fd41072b444e2 |
| Laura | https://app.notion.com/p/40fe204ff76981f09398c36ba6dc5cdd |
| Karl | https://app.notion.com/p/40fe204ff76981e393d1dcadb7e3498f |
| Tonie | https://app.notion.com/p/40fe204ff769813bbb9cd931b1ebc507 |
| Sid | https://app.notion.com/p/40fe204ff76981d685dbe69ec62ec83a |
| Zach | https://app.notion.com/p/40fe204ff769818da0e4c0bd8d05f9be |
| Sarah | https://app.notion.com/p/40fe204ff76981e3ab84c3fdbf387f13 |
| Hayley | https://app.notion.com/p/40fe204ff769817298f8fb0240f14d29 |
| Wendlley | https://app.notion.com/p/40fe204ff769810694ebd20af693ad75 |
| Sophie | https://app.notion.com/p/40fe204ff76981759aa9eb667f65e2fe |
| Shrishti | https://app.notion.com/p/40fe204ff769815e8e66ef747f5f906d |
| Diya | https://app.notion.com/p/40fe204ff76981bc8ecafd55d97bc12e |
| Michaela | https://app.notion.com/p/40fe204ff76981a5882ecdcdea590bc3 |
| Jethro (not recorded) | https://app.notion.com/p/40fe204ff76981179b98c9c34d0ef64a |

Each Evidence Log page has a `## Transcript` section with a mention link to the meeting-notes page holding the actual transcript (fetch it with `include_transcript: true`).

## Before you finish, check
- Every pain point, suggestion, strength and fact has a quote and timestamp
- Every time estimate has a range and a certainty label
- Every process uses a canonical name or is marked `NEW:`
- Every opportunity has at least one KPI, three scores, a priority score, a rank and a tag
- Ideas Austin raised are marked `interviewer`, not `interviewee`
- Nothing about named individuals' performance appears outside section 12
- The Transcript Findings page exists, is linked to its Evidence Log row and matched problems, and has Status "Extracted"
