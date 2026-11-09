# Data

Machine-readable files for analysis or for an AI to load.

- [ds_map.json](ds_map.json) – every solution: title, team, bundle, status, source type, opportunities (with part), earlier ideas, problems fixed / helped / related, pain points cited, COI.
- [bundles.json](bundles.json) – bundle → solution IDs.
- [problems.json](problems.json), [pain-points.json](pain-points.json), [interviews.json](interviews.json) – the other layers.
- The full ledger is in [../decisions/ledger.json](../decisions/ledger.json); CSVs are in `pain-points/`, `opportunities/` and `decisions/`.
- [build-info.json](build-info.json) – SHA-256 of each source file used for this build.
