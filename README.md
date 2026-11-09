# Aperitif – AI & business audit: research repository

The full research behind the AI and business audit of **Aperitif**, a \~27-person Australian digital agency (paid media, SEO, content, link building). Audit by Austin Smith for Joe Romeo (founder), November 2026. Nothing is anonymised: names and roles are real.

It traces every recommendation back to what people said in interviews: transcripts → pain points → problems → opportunities → Austin's decisions → solutions. Read [START-HERE.md](START-HERE.md) first.

## How it is organised

| Folder | What is in it |
| --- | --- |
| [solutions/](solutions/README.md) | One file per solution DS-01..DS-33, with front matter and the one-pager; index grouped by bundle |
| [problems/](problems/README.md) | One file per problem P-01..P-48: Austin's call, status, solutions, pain points with quotes, root cause |
| [pain-points/](pain-points/README.md) | All 243 pain points grouped by interview, plus `pain-points.csv` |
| [opportunities/](opportunities/README.md) | Merged opportunities O-01..O-35 and earlier ideas EI-01..EI-21, with decision and reason, plus CSV |
| [interviews/](interviews/README.md) | One folder per interview: transcript, extraction report, structured JSON |
| [decisions/](decisions/README.md) | Decision ledger (CSV/JSON), Austin's decisions log, not-recommending list |
| [synthesis/](synthesis/README.md) | Merge outputs: clusters, root causes, contradictions, opportunities, findings, culture and strengths |
| [method/](method/README.md) | Prompts, method notes, independent audit and quote checks, gaps and issues, raw exports |
| [pack/](pack/README.md) | Drafts of the client pack content (when present) |
| [data/](data/README.md) | Machine-readable JSON: solutions map, bundles, problems, pain points, interviews |

## How to read it

- **Browsing:** start at [START-HERE.md](START-HERE.md), open a bundle, then a solution. Each solution links to the problems it fixes; each problem lists its pain points with the quote, the person and a link to the exact transcript line.
- **Checking a claim:** follow the IDs down to the quote, then to the transcript. If a quote is interviewer-raised or inferred, it is labelled.
- **Status of anything:** [decisions/ledger.csv](decisions/ledger.csv) has one row per item with status and reason.

## If you are an AI

You are reading a structured evidence base. Use it like this.

**Layers (bottom to top):**

1. `interviews/<code>-<name>/transcript.md` – raw transcripts. Lines are numbered `L###`; `~mm:ss` is usually estimated.
2. **PP** pain points – `KO-PP01`, `SB-PP04` … The prefix is the interview code (SD = Shrishti Dokwal; KO = leadership kick-off; MP = leadership mid-point). Index: `pain-points/README.md`, data: `pain-points/pain-points.csv`.
3. **P** problems – `P-01`..`P-48` (Problems database). Several pain points roll up into one problem. Files: `problems/p-xx-*.md`. Stage 1 clusters are `C-xx`, root causes `RC-xx`, contradictions `X-xx` (`synthesis/`).
4. **O** merged opportunities – `O-01`..`O-35` (Stage 2), built from per-interview ideas such as `SB-O02`. **EI** – `EI-01`..`EI-21`, Austin's earlier ideas. Both in `opportunities/`.
5. **DS** solutions – `DS-01`..`DS-33`, Austin's final recommendations (`solutions/`). DS-13 is merged into DS-14. **NR** = not recommending.
6. **X** contradictions – `X-01`..`X-31`: where two sources disagree (`synthesis/contradictions.md`). Also `WS-ZC-01` = Zach Chamberlain's written "AI suggestions" Google Doc (not in the repo).

**Following evidence:** down = DS front matter → `problems_fixed` → problem file → pain points → quote and transcript line. Up = pain point → its problem → the DS that fixes it (`status` / `addressed_by` in the CSV). `decisions/ledger.json` has `links_up` and `links_down` for every row; `data/ds_map.json` is the solutions map.

**Source types of a pain point:**

- *staff-raised* (`interviewee`) – the person raised it themselves. Strongest evidence.
- *interviewer-raised* (`interviewer`) – Austin raised it and the person agreed. Not a staff raise; do not count it as independent support.
- *inferred* (`detected`) – drawn out by analysis, not stated. Treat as a hypothesis.

**Solution source types:** *evidence-backed* (rests on interview evidence), *mixed* (evidence plus Austin's additions), *Austin addition* (Austin's idea, weak or no interview evidence).

**Rules:**

- Cite IDs for every claim (e.g. "DS-06 fixes P-16; evidence SB-PP04, stated").
- Do not treat assumptions as facts. Hours saved, COI figures and churn numbers are marked *assumed* or *estimated*; the churn basis is Austin's assumption. Costs are TBC – do not invent any.
- Austin's calls are decisions, not evidence. A *Park* problem stays parked even if a solution "also helps".
- Where sources conflict, check `synthesis/contradictions.md` and `method/gaps-and-issues.md` before stating a fact.
- Merge outputs (Stage 1–3, 6 Nov) predate Austin's decisions; the ledger and solution files are current.

## Regenerating

This repo is generated. Do not edit files by hand; change the sources and run `python3 /home/claude/deliverable/build_repo.py` (add `--no-ledger` to skip the ledger rebuild). Reasons Austin marked internal on his page are withheld; the suggested wording for Joe is kept. Source hashes for the current build are in [data/build-info.json](data/build-info.json).
