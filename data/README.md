# Data

Machine-readable files for analysis or for an AI to load.

- [ds_map.json](ds_map.json) – every solution: title, team, bundle, status, source type, opportunities (with part), earlier ideas, problems fixed / helped / related, pain points cited, and `value` (the summary line from [../VALUE-BY-BUNDLE.md](../VALUE-BY-BUNDLE.md)). The older cost-of-inactivity (`coi_*`) fields have been removed as superseded.
- [../pricing/value_model.json](../pricing/value_model.json) – the numbers behind VALUE-BY-BUNDLE.md (hours, capacity, team figures from the 10 Nov client board).
- [bundles.json](bundles.json) – bundle → solution IDs.
- [problems.json](problems.json), [pain-points.json](pain-points.json), [interviews.json](interviews.json) – the other layers.
- The full ledger is in [../decisions/ledger.json](../decisions/ledger.json); CSVs are in `pain-points/`, `opportunities/` and `decisions/`.
- [build-info.json](build-info.json) – SHA-256 of each source file used for this build.
