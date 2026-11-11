---
id: P-40
title: "AI use is personal and ungoverned: no policy, shared skills, client context or seats"
decision: "Solve later"
status: addressed
fixed_by: ["DS-02"]
also_helped_by: ["DS-05"]
related_only: []
clusters: ["C-33"]
root_causes: ["RC-04"]
pain_points: ["DM-PP11", "DM-PP12", "HT-PP08", "KO-PP14", "KZ-PP24", "LS-PP13", "MC-PP19", "SB-PP12", "SH-PP14", "WS-PP13", "ZC-PP14"]
theme: "Process / automation"
severity: "Medium"
confidence: "High – raised by 3+ people"
---

# P-40 · AI use is personal and ungoverned: no policy, shared skills, client context or seats

| | |
| --- | --- |
| Decision | **Solve later** |
| Status | addressed – Fixed by [DS-02](../solutions/ds-02-ai-playbook-repository.md); also helped by [DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md) |
| Theme · severity · confidence | Process / automation · Medium · High – raised by 3+ people |
| Process area | Other |
| Source | Transcript merge (Stage 1, 6 Nov) |

## Solutions addressing it

- Fixes: [DS-02 AI playbook repository (how we use AI: rules, SOPs, prompts, agents, skills)](../solutions/ds-02-ai-playbook-repository.md)
- Also helps: [DS-05 Automated deck generator: quarterly + 6-month reviews and proposals](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md)

## Linked opportunities

- [O-33](../opportunities/README.md#o-33) SOPs linked from Monday templates; stale pages retired – partly addressed ([DS-02](../solutions/ds-02-ai-playbook-repository.md))
- [O-02](../opportunities/README.md#o-02) AI data rule, company Claude seats and shared skills library – addressed ([DS-02](../solutions/ds-02-ai-playbook-repository.md), [DS-25](../solutions/ds-25-ppc-performance-forecasting-tool.md))
- [O-05](../opportunities/README.md#o-05) Reports and review decks: auto-filled data, AI-drafted narrative – partly addressed ([DS-05](../solutions/ds-05-automated-deck-generator-quarterly-6-month-reviews.md))
- [O-13](../opportunities/README.md#o-13) AI per-client summary for reports, calls and data questions – absorbed ([DS-04](../solutions/ds-04-ai-client-brain.md))
- [O-27](../opportunities/README.md#o-27) AI business brain over client records and SOPs – addressed ([DS-15](../solutions/ds-15-ai-business-brain-the-umbrella.md), [DS-04](../solutions/ds-04-ai-client-brain.md))

## Root cause and cluster

- Cluster [C-33](../synthesis/clusters-and-root-causes.md#c-33): AI use is personal and ungoverned: no policy, shared skills, client context or seats – raised by 9 staff + 1 leadership; confidence High.
- Root cause [RC-04](../synthesis/clusters-and-root-causes.md#rc-04): Tools, automations and AI workflows are built by individuals with no owner, documentation, policy or renewal plan, so they break or stay personal.
- Root cause (problem record): [RC-04](../synthesis/clusters-and-root-causes.md#rc-04): Tools and AI workflows are built by individuals with no owner, policy or plan. Chain: AI output varies, needs re-briefing and double-checking; some deliverables went out poor ([LS-PP13](../pain-points/README.md#ls-pp13), [HT-PP08](../pain-points/README.md#ht-pp08), [DM-PP11](../pain-points/README.md#dm-pp11), [ZC-PP14](../pain-points/README.md#zc-pp14)) → each person builds their own prompts, skills and accounts, some personal ([MC-PP19](../pain-points/README.md#mc-pp19), [WS-PP13](../pain-points/README.md#ws-pp13), [SH-PP14](../pain-points/README.md#sh-pp14)) → no policy on client data in AI, no shared skills library, no client context, too few seats ([DM-PP12](../pain-points/README.md#dm-pp12), [SB-PP12](../pain-points/README.md#sb-pp12)) → AI adoption has been bottom-up with no owner or standards.

## Pain points (11)

- [DM-PP11](../pain-points/README.md#dm-pp11) – Using Claude helps but briefing it with each situation takes time
  - *"that also requires a lot of time to just brief it, make it understand what exactly is the situation."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~04:00 (L063)](../interviews/dm-diya-manoj/transcript.md?plain=1#L66) · Austin: Agree
- [DM-PP12](../pain-points/README.md#dm-pp12) – No clear rule on whether Claude may connect to client ad platforms (data privacy), so she hasn't used it
  - *"I'm not sure how much it is okay to have the data privacy and everything when we do that."* – Diya Manoj, Performance Marketing Manager · staff-raised · [\~15:21 (L181)](../interviews/dm-diya-manoj/transcript.md?plain=1#L184)
- [HT-PP08](../pain-points/README.md#ht-pp08) – AI tools skew vague; good output needs very specific prompts and individual trial and error
  - *"my main gripe with. like a Claude or a chat GPT is that they do lean like unspecific."* – Hayley Tantau, Content Specialist · staff-raised · [\~21:57 (L254–L255)](../interviews/ht-hayley-tantau/transcript.md?plain=1#L259) · Austin: Agree
- [KO-PP14](../pain-points/README.md#ko-pp14) – AI use is inconsistent and shallow; Joe's OpenClaw assistant is open to the team in Slack but nobody uses it, and nobody was told how
  - *Joe: "it's got access to the team via a Slack channel. No one utilises it."* – Joe Romeo, Leadership (kick-off) · staff-raised · [\~81:13 (L377)](../interviews/ko-leadership-kick-off/transcript.md?plain=1#L428) · Austin: Agree
- [KZ-PP24](../pain-points/README.md#kz-pp24) – Freelance writers' AI use can't be verified (KZ's experience at his last agency; unknown here)
  - *"they'll tell you that they didn't use AI and then someone will say like, 'Hey, my content looks like AI.'"* – Karl Zaharopoulos, Senior SEO Manager & Link-building Lead · staff-raised · [\~52:06 (L532)](../interviews/kz-karl-zaharopoulos/transcript.md?plain=1#L536)
- [LS-PP13](../pain-points/README.md#ls-pp13) – No agreed guardrails for AI use in strategy and client deliverables
  - *"we've had a few cases where team members used AI for the whole thing and it was a mess."* – Laura Shillington, SEO Director · staff-raised · [\~07:00 (L026)](../interviews/ls-laura-shillington/transcript.md?plain=1#L35)
- [MC-PP19](../pain-points/README.md#mc-pp19) – AI skills sit on a personal Claude account she pays for; company Claude won't connect to her browser
  - *"Personally, I set up my personal cloud [Claude] using my work email and I'm paying for it every month."* – Michaela Cruz, Performance Marketing Specialist · staff-raised · [\~39:17 (L343)](../interviews/mc-michaela-cruz/transcript.md?plain=1#L346)
- [SB-PP12](../pain-points/README.md#sb-pp12) – Claude Pro-for-Teams token limits restrict a team that relies on AI; Claude in Chrome burns most tokens; no shared skills library
  - *"it's severely limiting what the team can do because honestly everyone's become very reliant on AI."* – Sid Bali, Technical SEO Specialist · staff-raised · [\~27:17 (L381)](../interviews/sb-sid-bali/transcript.md?plain=1#L385) · Austin: Agree
- [SH-PP14](../pain-points/README.md#sh-pp14) – No standard research prompt for strategy; AI use is ad hoc
  - *"It would be like now with Claude and stuff and generating report, but I don't have like a go-to prompt"* – Sophie Hesseborn, Senior Performance Marketing Manager · staff-raised · [\~13:41 (L124)](../interviews/sh-sophie-hesseborn/transcript.md?plain=1#L124) · Austin: Agree
- [WS-PP13](../pain-points/README.md#ws-pp13) – AI shortcuts (Gemini forecasting, AI quarterly reviews) are personal workflows, not shared with the team
  - *"I guess I started getting Google as well, or like Gemini, yeah, to help me out with forecasting."* – Wendlley Simoes, Performance Marketing Director · inferred · [\~37:37 (L456)](../interviews/ws-wendlley-simoes/transcript.md?plain=1#L461) · Austin: Agree
- [ZC-PP14](../pain-points/README.md#zc-pp14) – Claude keyword research can go 'AWOL' in niche industries – output triple-checked
  - *"I definitely find that double checking it is really important when it's quite a niche industry."* – Zach Chamberlain, SEO Manager · staff-raised · [\~15:41 (L150)](../interviews/zc-zach-chamberlain/transcript.md?plain=1#L156) · Austin: Agree

## Best quotes and figures

"we've had a few cases where team members used AI for the whole thing and it was a mess." – an SEO manager ([LS-PP13](../pain-points/README.md#ls-pp13), \~07:00, L026) | "Personally, I set up my personal [Claude] using my work email and I'm paying for it every month." – a performance team member ([MC-PP19](../pain-points/README.md#mc-pp19), \~39:17, L343) | "I'm not sure how much it is okay to have the data privacy and everything when we do that." – a performance manager ([DM-PP12](../pain-points/README.md#dm-pp12), \~15:21, L181)
