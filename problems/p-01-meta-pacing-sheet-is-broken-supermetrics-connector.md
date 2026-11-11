---
id: P-01
title: "Meta pacing sheet is broken – Supermetrics connector failing"
decision: "Solve now"
status: addressed
fixed_by: ["DS-01"]
also_helped_by: []
related_only: []
clusters: ["C-02"]
root_causes: ["RC-04"]
pain_points: ["MC-PP06", "SD-PP01", "SD-PP15", "SD-PP19", "SH-PP02", "SH-PP05"]
theme: "Process / automation"
severity: "Critical"
confidence: "High – raised by 3+ people"
---

# P-01 · Meta pacing sheet is broken – Supermetrics connector failing

| | |
| --- | --- |
| Decision | **Solve now** |
| Status | addressed – Fixed by [DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md) |
| Theme · severity · confidence | Process / automation · Critical · High – raised by 3+ people |
| Process area | Reporting |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-01 Modern ad budget pacing + performance alerting](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md)

## Linked opportunities

- [O-01](../opportunities/README.md#o-01) Restore the pacing data feed and cover every live channel – addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [O-11](../opportunities/README.md#o-11) Pacing tracker reads budgets and spend, flags gaps – absorbed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))
- [EI-13](../opportunities/README.md#ei-13) Pacing tracker + adjustment engine – partly addressed ([DS-01](../solutions/ds-01-modern-ad-budget-pacing-performance-alerting.md))

## Root cause and cluster

- Cluster [C-02](../synthesis/clusters-and-root-causes.md#c-02): Pacing tools are broken or fragile, so Meta and Google pacing is done by hand – raised by 3 staff + 0 leadership; confidence High.
- Root cause [RC-04](../synthesis/clusters-and-root-causes.md#rc-04): Tools, automations and AI workflows are built by individuals with no owner, documentation, policy or renewal plan, so they break or stay personal.
- Root cause (problem record): Pacing depends on a paid connector (Supermetrics) that lapsed, and the sheet needs a manual re-point of the query on the 1st of every month. No owner monitors whether it's working.

## Pain points (6)

- [MC-PP06](../pain-points/README.md#mc-pp06) – Supermetrics-fed team pacing sheet keeps breaking; Tina pacing updates unreliable; Supermetrics not being renewed
  - *"that's one more issue that Supermetrics is breaking down a lot."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~20:25 (L198)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L201) · Austin: Agree
- [SD-PP01](../pain-points/README.md#sd-pp01) – Pacing is the #1 pain: sheets broke when Supermetrics lapsed; the whole process is manual; the Performance Director now does Meta pacing by hand in Claude daily (single-person dep…
  - *"the sheets have broken because we no longer have a Supermetric subscription."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~22:57 (L193)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L200) · Austin: Agree
- [SD-PP15](../pain-points/README.md#sd-pp15) – Claude connects to Meta but not Google Ads; Google stays manual
  - *"I have connected my meta ads to cloud [Claude] now, game changer, and Google Ads tool isn't a connector yet."* – Shrishti Dokwal, Senior Performance Marketing Manager · staff-raised · [\~15:50 (L131)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L138) · Austin: Agree
- [SD-PP19](../pain-points/README.md#sd-pp19) – Pacing cadence depends on the Tina Slack agent bot, which has no visible owner or documentation
  - *"Tina gives us updates and Monday, Wednesday, Friday."* – Shrishti Dokwal, Senior Performance Marketing Manager · inferred · [\~27:21 (L260)](../interviews/sd-shrishti-dokwal/transcript.md?plain=1#L267) · Austin: Agree
- [SH-PP02](../pain-points/README.md#sh-pp02) – Pacing sheets need manual account ID, name and budget input and often don't pull correctly
  - *"we have to manually input like the ad account ID and the name and the budgets. And then it's not always pulling correctly."* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~20:46 (L198–L199)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L198) · Austin: Agree
- [SH-PP05](../pain-points/README.md#sh-pp05) – Meta account-level daily spend must be summed by hand from ad sets
  - *"if it's in ad set level you have to like go in and just like summarize just add everything up."* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~30:53 (L292)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L292) · Austin: Agree

## Best quotes and figures

Nov tab header: "Error: Facebook error: User may not have permissions to access account". 37 of 42 accounts "No budget set"; 5 "Meta data unavailable via connector – spend not updated". Shrishti: pacing sheets broke after Supermetrics lapsed, now done manually in Claude for Meta.
