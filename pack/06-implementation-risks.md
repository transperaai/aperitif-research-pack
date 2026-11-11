# Implementation risks

What could stop these solutions working once they're built, and what to do about it. This is separate from the value each solution brings (see VALUE-BY-BUNDLE.md).

| # | Risk | Main solutions affected |
| --- | --- | --- |
| 1 | Change fatigue and AI anxiety | All – especially DS-02, DS-04, DS-15 |
| 2 | Adoption – "people don't use it" | DS-02, DS-04, DS-06, DS-10, DS-15, DS-30 |
| 3 | The AI data rule isn't in place first | DS-03, DS-04, DS-05, DS-06, DS-08, DS-09, DS-14, DS-15 |
| 4 | Key-person reliance | DS-01, DS-03, DS-10, all builds |
| 5 | Data isn't ready | DS-03, DS-04, DS-07, DS-14, DS-16, DS-17, DS-22, DS-29 |
| 6 | Consent and privacy | DS-04, DS-06, DS-08, DS-14, DS-20, DS-30 |
| 7 | Vendor and API risk | DS-01, DS-07, DS-18, DS-19, DS-21, DS-22, DS-29 |

---

## 1. Change fatigue and AI anxiety

**The risk.** Three systems landed in about 50 days (Monday.com, AgencyAnalytics, Employment Hero) and the staff survey said *"too many changes in a short amount of time"* (Joe, KO L381). Some staff quietly fear AI will replace them (KO L412, HT L292). This pack proposes a lot more change (P-44).

**Mitigation**
- Joe and Julia state what AI is for – augmenting, not replacing – before anything launches.
- Stage the rollout: one change per team at a time, with a pause before the next.
- Protected learning time and one champion per team.
- Start with the solutions that remove obvious grind (pacing, brief drafts) so the first experience is a good one.

**Affects:** everything, most of all the "brain" solutions that ask people to change habits (DS-02, DS-04, DS-15).

---

## 2. Adoption – "people don't use it"

**The risk.** Joe: *"you can build the best system in the world, but like, people don't use it"* (KO-PP10). Joe's Slack AI assistant is available to everyone and *"No one utilises it."* (KO-PP14). SOPs are written but not read (MP-PP03); reminders go out and updates don't follow (MP-PP05).

**Mitigation**
- Put solutions where people already work – Slack and Monday – not in a new app (DS-15's "one front door").
- Make the solution do the work rather than ask for input (DS-06 creates the task; DS-03 drafts the brief).
- Agree one or two adoption measures per solution and have team leads review them.
- Link each SOP from the Monday task it belongs to (DS-02).
- Give every solution a business owner, not just a technical one (DS-01 sets this pattern: Transpera owns the tech; account managers own data validity).

**Affects:** DS-02, DS-04, DS-06, DS-10, DS-15, DS-30 most.

---

## 3. The AI data rule has to come first

**The risk.** Eight solutions need the AI data rule and company Claude seats (DS-02) before client data is connected: **DS-03, DS-04, DS-05, DS-06, DS-08, DS-09, DS-14 and DS-15**. Today AI use is personal – at least one staff member pays for her own Claude account (MC-PP19), and staff aren't sure what's allowed: *"I'm not sure how much it is okay to have the data privacy and everything"* (DM-PP12).

**Mitigation**
- Do DS-02 first. Joe signs off the rule.
- Check the rule against client contracts, especially regulated clients (dental, finance).
- Move the useful personal tools onto company accounts as part of DS-02.

**Affects:** the eight solutions above. If DS-02 slips, they slip too.

---

## 4. Key-person reliance

**The risk.**
- **Sid Bali** built and is the only person who knows the Monday.com and Make set-up. If he's away or leaves, task routing, onboarding boards and syncs stop (DS-10, culture item C-K10). DS-03's Monday integration builds on that same set-up.
- **Austin as builder.** If Transpera builds several solutions, Austin becomes the new single point of failure – the same pattern as today's Supermetrics feed and Make set-up. DS-01's options section makes this point: a custom all-channel tool is *"a lot for one person to build and keep running"*.
- **Personal AI tools** across the team (strength 15) sit with their makers.

**Mitigation**
- DS-10 systems register first: every build has an owner, a backup admin and a break-fix runbook.
- Train a second admin for Monday/Make.
- Prefer bought tools where they do the job (DS-01's Windsor.ai data layer, DS-19 Aircall, DS-21 existing tools) so less depends on one builder.
- Make "registered in DS-10" part of done for every new build.

**Affects:** DS-01 (the pacing engine and alerts built on Windsor.ai), DS-03, DS-10, and every custom build.

---

## 5. Data isn't ready

**The risk.** Several solutions assume clean, consistent data that doesn't exist yet.
- **Client files and logins** live in individual staff accounts, including people who have left (P-23). DS-17 fixes this, and DS-04 client brains need it.
- **Client tagging** – DS-04 has to know which Slack messages and emails belong to which client, reliably, for every client.
- **Master SEO Document** structure must be consistent enough to read automatically (DS-03 – check 2–3 clients first). Competitor lists per client are assumed to exist (DS-16, DS-32).
- **One clean link list** with URLs and requirements is needed before the link watchdog can run (DS-07 depends on DS-11).
- **Outcomes logged** – DS-14 can only "get smarter" if every alert is marked kept, churned or upsold.
- **API access** to every client's GA4, Search Console, Ahrefs and ad accounts (DS-22, DS-29).

**Mitigation**
- Do DS-17 (file structure) early – it's "not really a build, a foundation".
- Pilot data-hungry solutions on a few clients before switching on for all.
- Run an access check per client as part of onboarding (DS-08 add-on).

**Affects:** DS-03, DS-04, DS-07, DS-14, DS-16, DS-17, DS-22, DS-29.

---

## 6. Consent and privacy

**The risk.**
- **Call recording** – DS-04 and DS-08 rely on recorded client and sales calls. Clients and prospects must agree, and a retention period for transcripts must be set before launch (DS-04 vision).
- **Staff DMs and inboxes** – DS-06 and DS-30 can only read a person's DMs and email if that person authorises it.
- **Profiling client contacts** – DS-14 builds a profile of each client contact's style and sentiment. That needs a clear line on what is stored about individuals. Staff are not profiled; prospects are not profiled.
- **Public research on people** – DS-20 researches new clients' leadership; it uses public information only, and LinkedIn access is checked first.
- **Who sees what** – commercial and HR detail must be limited by role (DS-15 RBAC).

**Mitigation**
- Write consent and retention into the DS-02 AI data rule.
- Opt-in for staff DM and inbox access, with a plain statement of what is read and kept.
- Role-based access in the brain from day one.
- A privacy check against Australian privacy law before DS-14 profiling goes live. *[Assumption: legal advice is outside this audit.]*

**Affects:** DS-04, DS-06, DS-08, DS-14, DS-20, DS-30.

---

## 7. Vendor and API risk

**The risk.**
- **Ad platform APIs change often.** Google releases a new Ads API version every 3–4 months and switches old ones off about a year later. LinkedIn's ad API needs a manual partner review that can take weeks to months (DS-01).
- **Vendor limits.** Windsor.ai's data is daily (cached up to 6 hours), so pacing catches drift by the next morning, not a same-day blowout, and its plan depends on the total ad-account count (DS-01). Jev AI's fit for the link watchdog is checked at build (DS-07).
- **Prices change.** Tool prices were checked in Nov 2026 and are mostly in USD (DS-01, DS-21). Aircall's AI receptionist is a paid add-on (billed about A$150–370 a month), not built in (DS-19).
- **Lead-gen fit.** Most AI creative tools are built for e-commerce, not Aperitif's clients (MP-PP22) – hence a trial first (DS-21).
- **Feeds fail quietly.** The Supermetrics connector is failing today and the Meta pacing sheet broke without anyone owning the fix (P-01).

**Mitigation**
- Buy where a vendor carries the API upkeep (DS-01's Windsor.ai data layer).
- Trial before committing: Windsor.ai's 30-day trial (10 sources, 15 accounts) against a few live accounts, and a 'no data arrived' check against silent connector failures (DS-01).
- Name an owner for every feed and add it to DS-10.
- Re-check prices before signing.

**Affects:** DS-01, DS-07, DS-18, DS-19, DS-21, DS-22, DS-29.
