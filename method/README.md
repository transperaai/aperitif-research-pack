# Method

## How the research was done

1. **Context.** Austin started from a context pack on Aperitif ([context-pack.md](context-pack.md)): team, clients, tools and known facts. Facts in it were checked against the interviews in Stage 1 (`known_facts_check`).
2. **Interviews.** 14 recorded sessions between 22 Oct and 4 Nov 2026: two with leadership (kick-off and mid-point, Joe Romeo and Julia Van Der Linden) and twelve with staff across Performance (paid) and Organic (SEO, content, link building). Transcripts come from Notion meeting notes; most have no native timestamps, so \~mm:ss is estimated from word position.
3. **Extraction.** Each transcript was run through the [extraction prompt](extraction-prompt.md): Part A is a readable report, Part B is JSON (pain points, processes, opportunities, strengths, facts, tools, dependencies). Every pain point has a quote, a line reference and a source type: *interviewee* (staff-raised), *interviewer* (Austin raised it and the person agreed) or *detected* (inferred by analysis, not stated).
4. **Merge.** The [merge prompt](merge-prompt.md) combined the 14 extractions: Stage 1 clustered 243 pain points into 39 clusters and 8 root causes and logged contradictions; Stage 2 merged the per-interview ideas into 35 opportunities with hours saved (assumed) and rank; Stage 3 wrote the findings; Stage 4 (8 Nov) re-read all transcripts for culture and strengths. See [../synthesis/](../synthesis/README.md).
5. **Problems and decisions.** The clusters became 48 problems in the Problems database (Notion). Austin made a call on each (Solve now / Solve later / Park / Reject), flagged pain points Agree/Disagree, and decided each opportunity and earlier idea (Keep / Change / Drop).
6. **Solutions.** Austin worked the kept opportunities into one-page solutions DS-01..DS-33 on the "Distilled Solutions" page (future state, KPIs, value, build cost/OpEx, assumptions). The vision pass on 9 Nov added a Vision to every DS and split out DS-30..DS-33. Zach Chamberlain's written "AI suggestions" doc was used as a written source (WS-ZC-01).
7. **Ledger.** A script traces every item from pain point to solution and records status and reason ([../decisions/](../decisions/README.md)); its checks are in [gaps-and-issues.md](gaps-and-issues.md).
8. **Independent audit.** A read-only audit checked every cited quote against the transcripts and the cost arithmetic as it stood then ([audit/audit-report.md](audit/audit-report.md), [audit/quote-checks.csv](audit/quote-checks.csv)). It ran on DS-01..DS-21 before the later splits; the fixes Austin applied are in the [decisions log](../decisions/decisions-log.md).

## Conventions

- **Value** is in [../VALUE-BY-BUNDLE.md](../VALUE-BY-BUNDLE.md) (authoritative, 10 Nov): time saved at A\$80/hr and capacity unlocked (hours freed ÷ \~130 productive hours × MRR managed per account manager), based on the live client board (10 Nov: 101 clients, A\$421,121 MRR). Time and capacity are the same hours counted two ways – never add them. Every number carries a basis label.
- **Retention (DS-14)** rests on the client board (10 clients ended 31 Aug–17 Oct 2026, average \~A\$2,500 a month); 3–4 clients saved a year is Austin's estimate.
- **Build cost and monthly fees** are set by Austin per solution (A\$; SaaS and AI tokens in US\$) and shown in each solution file. Tool prices are list prices from web research (Nov 2026), not quotes.
- **Superseded:** the earlier cost-of-inactivity (COI) figures and churn basis still appear in the audit report, gaps-and-issues and the decisions log; those files carry a banner.

## Files

- [extraction-prompt.md](extraction-prompt.md), [merge-prompt.md](merge-prompt.md) – the prompts used.
- [context-pack.md](context-pack.md) – the starting context on Aperitif.
- [audit/](audit/audit-report.md) – independent audit and quote checks.
- [gaps-and-issues.md](gaps-and-issues.md) – issues the ledger build found (reported, not fixed).
- [source/](source/) – raw exports: the Distilled Solutions page as fetched from Notion (v3, with Notion tags), the Problems and Opportunities database exports.
