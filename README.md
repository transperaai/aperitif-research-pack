# Aperitif – AI & business audit: research repository

The full research behind the AI and business audit of **Aperitif**, a \~27-person Australian digital agency (paid media, SEO, content, link building). Audit by Austin Smith for Joe Romeo (founder), November 2026. Nothing is anonymised: names and roles are real.

It traces every recommendation back to what people said in interviews: transcripts → pain points → problems → opportunities → Austin's decisions → solutions. Read [START-HERE.md](START-HERE.md) first.

## Contents

- [Value by bundle](VALUE-BY-BUNDLE.md) – time saved, capacity, DLER, evidence and basis for every solution
- [How everything connects](#how-everything-connects)
- [How the solutions connect](#how-the-solutions-connect)
- [How it is organised](#how-it-is-organised)
- [How to read it](#how-to-read-it)
- [If you are an AI](#if-you-are-an-ai)

## How everything connects

From interviews to recommendations. Every box is a folder in this repo; every arrow is a link you can follow in the files.

```mermaid
flowchart TD
  I["14 interviews<br/>(2 leadership + 12 staff)"] --> PP["243 pain points<br/>each with a quote and transcript line"]
  W["Zach Chamberlain's written<br/>'AI suggestions' doc"] --> PP
  PP --> CL["39 clusters → 8 root causes"]
  CL --> P["48 problems"]
  P --> RO["143 raw ideas"]
  RO --> O["35 merged opportunities<br/>+ 21 earlier ideas"]
  O --> D{"Austin's decisions"}
  D -->|kept| DS["32 solutions<br/>DS-01 to DS-33"]
  D -->|dropped| NR["Not recommending<br/>and dropped ideas"]
  P -->|people and culture| CR["Culture recommendations"]
  DS --> B["9 bundles"]
  DS --> PR["Pricing & priority"]
```

## How the solutions connect

Arrows show data flowing from one solution to another. The client brain (DS-04) is the shared platform: most solutions either write into it or read from it, which is why it is built first. Standalone solutions (DS-18 landing pages, DS-19 AI receptionist, DS-21 creative tools) are not shown.

```mermaid
flowchart LR
  subgraph BRAIN["AI Business Brain – DS-15"]
    DS04["DS-04 Client brain<br/>(shared platform)"]
    DS02["DS-02 AI playbook"]
    DS10["DS-10 Help docs + register"]
    DS14["DS-14 Client health & growth"]
  end
  DS02 -. "AI rules for" .-> DS04
  DS08["DS-08 Sales handover"] --> DS04
  DS20["DS-20 New-client dossier"] --> DS04
  DS09["DS-09 Onboarding audit"] --> DS04
  DS17["DS-17 Files & logins"] --> DS04
  DS16["DS-16 Seasonal radar"] --> DS04
  DS32["DS-32 Competitor spy"] --> DS04
  DS33["DS-33 Macro trends"] --> DS04
  DS04 --> DS14
  DS04 --> DS28["DS-28 Client comms"]
  DS04 --> DS05["DS-05 Deck generator"]
  DS04 --> DS03["DS-03 Brief drafts"]
  DS06["DS-06 Request sweeper"] --> DS30["DS-30 Daily priorities"]
  DS06 --> DS04
  DS01["DS-01 Adpulse pacing & alerts"] --> DS27["DS-27 Alert investigator"]
  DS01 --> DS29["DS-29 PPC Monday check"]
  DS04 --> DS27
  DS22["DS-22 SEO Monday check"] --> DS23["DS-23 SEO drop alerts"]
  DS22 --> DS24["DS-24 SEO mid-month wins"]
  DS33 --> DS25["DS-25/26 Forecasting"]
  DS04 --> DS25
  DS12["DS-12 Link supply engine"] --> DS11["DS-11 Link-building CRM"]
  DS31["DS-31 Brand mentions"] --> DS11
  DS11 --> DS07["DS-07 Link watchdog"]
```

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
- Do not treat assumptions as facts. Value figures (time saved, capacity unlocked, retained, recovered) come only from VALUE-BY-BUNDLE.md, which is authoritative and has a basis label on every number – do not invent any, and never add time and capacity together. Any cost-of-inactivity (COI) figure elsewhere is superseded. Build prices are in each solution file.
- Austin's calls are decisions, not evidence. A *Park* problem stays parked even if a solution "also helps".
- Where sources conflict, check `synthesis/contradictions.md` and `method/gaps-and-issues.md` before stating a fact.
- Merge outputs (Stage 1–3, 6 Nov) predate Austin's decisions; the ledger and solution files are current.
- In the synthesis and merge documents (`synthesis/`, `method/merge-prompt.md`), **COI means conflict of interest** (Transpera could build the fix, or Austin has a link to it) – not cost of inactivity.

## Regenerating

This repo is generated. Do not edit files by hand; change the sources and re-run the build script (`build_repo.py`, kept with the sources, not in this repo). Reasons Austin marked internal on his page are withheld; the suggested wording for Joe is kept. Source hashes for the current build are in [data/build-info.json](data/build-info.json).
