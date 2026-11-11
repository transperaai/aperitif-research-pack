# Aperitif – AI & business audit: research repository

The full research behind the AI and business audit of **Aperitif**, a \~27-person Australian digital agency (paid media, SEO, content, link building). Audit by Austin Smith for Joe Romeo (founder), November 2026. Nothing is anonymised: names and roles are real.

It traces every recommendation back to what people said in interviews: transcripts → pain points → problems → opportunities → decisions → solutions → builds. Read [START-HERE.md](START-HERE.md) first.

## Contents

- [Builds and pricing](builds/README.md) – the 32 solutions delivered as 18 builds in 9 bundles, with prices, maintenance, running costs, dollar value and start order
- [Value by bundle](VALUE-BY-BUNDLE.md) – time saved, capacity, DLER, evidence and basis for every solution
- [How everything connects](#how-everything-connects)
- [How the solutions connect](#how-the-solutions-connect)
- [How it is organised](#how-it-is-organised)
- [How to read it](#how-to-read-it)
- [Using this repo with an AI tool](#using-this-repo-with-an-ai-tool)

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
  O --> D{"Decisions"}
  D -->|kept| DS["32 solutions<br/>DS-01 to DS-33"]
  D -->|dropped| NR["Dropped ideas"]
  P -->|people and culture| CR["Culture recommendations"]
  DS --> B["9 bundles"]
  DS --> PR["18 builds<br/>pricing and start order"]
```

## How the solutions connect

Arrows show data flowing from one solution to another. The client brain (DS-04) is the shared platform: most solutions either write into it or read from it, which is why it is built first. New services and standalone tools (DS-18 landing pages, DS-19 AI receptionist, DS-21 creative tools) are not shown.

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
  DS01["DS-01 Pacing & alerts (Windsor.ai)"] --> DS27["DS-27 Alert investigator"]
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
| [builds/](builds/README.md) | 18 builds – prices, maintenance, OpEx, dollar value, phases – plus `builds.csv` and `builds.json` |
| [solutions/](solutions/README.md) | One file per solution DS-01..DS-33, with front matter and the one-pager; index grouped by bundle. Pricing is in builds/ |
| [problems/](problems/README.md) | One file per problem P-01..P-48: decision, status, solutions, pain points with quotes, root cause |
| [pain-points/](pain-points/README.md) | All 243 pain points grouped by interview, plus `pain-points.csv` |
| [opportunities/](opportunities/README.md) | Merged opportunities O-01..O-35 and earlier ideas EI-01..EI-21, with decision and reason, plus CSV |
| [interviews/](interviews/README.md) | One folder per interview: transcript, extraction report, structured JSON |
| [synthesis/](synthesis/README.md) | Merge outputs: clusters, root causes, contradictions, opportunities, findings, culture and strengths |
| [method/](method/README.md) | How the research was done, and the conventions used for value and evidence |
| [pack/](pack/README.md) | The client pack pages: strengths, culture, scope and method, risks, assumptions, glossary, bundles |
| [data/](data/README.md) | Machine-readable JSON: solutions map, bundles, problems, pain points, interviews |

## How to read it

- **Browsing:** start at [START-HERE.md](START-HERE.md), open a bundle, then a solution. Each solution links to the problems it fixes; each problem lists its pain points with the quote, the person and a link to the exact transcript line.
- **Checking a claim:** follow the IDs down to the quote, then to the transcript. If a quote is interviewer-raised or inferred, it is labelled.
- **Status of anything:** each problem file, [pain-points.csv](pain-points/pain-points.csv) and [opportunities.csv](opportunities/opportunities.csv) carry the status and reason.

## Using this repo with an AI tool

If you load this repo into an AI tool, it is a structured evidence base. Use it like this.

**Layers (bottom to top):**

1. `interviews/<code>-<name>/transcript.md` – raw transcripts. Lines are numbered `L###`; `~mm:ss` is usually estimated.
2. **PP** pain points – `KO-PP01`, `SB-PP04` … The prefix is the interview code (SD = Shrishti Dokwal; KO = leadership kick-off; MP = leadership mid-point). Index: `pain-points/README.md`, data: `pain-points/pain-points.csv`.
3. **P** problems – `P-01`..`P-48` (Problems database). Several pain points roll up into one problem. Files: `problems/p-xx-*.md`. Stage 1 clusters are `C-xx`, root causes `RC-xx`, contradictions `X-xx` (`synthesis/`).
4. **O** merged opportunities – `O-01`..`O-35` (Stage 2), built from per-interview ideas such as `SB-O02`. **EI** – `EI-01`..`EI-21`, Austin's earlier ideas. Both in `opportunities/`.
5. **DS** solutions – `DS-01`..`DS-33`, the recommendations (`solutions/`). DS-13 is covered by DS-14 (Part B). The 32 solutions are delivered as 18 builds (`builds/`).
6. **X** contradictions – `X-01`..`X-31`: where two sources disagree (`synthesis/contradictions.md`). Also `WS-ZC-01` = Zach Chamberlain's written "AI suggestions" Google Doc (not in the repo).

**Following evidence:** down = DS front matter → `problems_fixed` → problem file → pain points → quote and transcript line. Up = pain point → its problem → the DS that fixes it (`status` / `addressed_by` in the CSV). `data/ds_map.json` is the solutions map.

**Source types of a pain point:**

- *staff-raised* (`interviewee`) – the person raised it themselves. Strongest evidence.
- *interviewer-raised* (`interviewer`) – Austin raised it and the person agreed. Not a staff raise; do not count it as independent support.
- *inferred* (`detected`) – drawn out by analysis, not stated. Treat as a hypothesis.

**Solution source types:** *evidence-backed* (rests on interview evidence), *mixed* (evidence plus Austin's additions), *Austin addition* (Austin's idea, weak or no interview evidence).

**Rules:**

- Cite IDs for every claim (e.g. "DS-06 fixes P-16; evidence SB-PP04, stated").
- Do not treat assumptions as facts. Current prices, maintenance, running costs and dollar values come from builds/README.md (18 builds); the research basis behind each value is in VALUE-BY-BUNDLE.md. Do not invent figures, and never add time and capacity together. Hour and dollar figures in the synthesis files are earlier research estimates; use builds/README.md for current figures.
- Decisions are not evidence. A *Not in proposal* problem stays out even if a solution "also helps".
- Where sources conflict, check `synthesis/contradictions.md` before stating a fact.
- The synthesis outputs (Stage 1–3, 6 Nov) came before the decisions; the problem, solution and build files are current.
- In the synthesis documents (`synthesis/`), **COI means conflict of interest** (Transpera could build the fix, or Austin has a link to it) – not cost of inactivity.

