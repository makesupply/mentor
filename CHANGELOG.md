# Changelog

All notable changes to the mentor skill. Format: [Keep a Changelog](https://keepachangelog.com/); versioning: semver — MAJOR for mode-system, voice-contract, or state-format changes; MINOR for new reference modules, modes, or research refreshes; PATCH for corrections.

## [Unreleased]

Expansion in progress toward v1.1.0: B2B, cross-model benchmarks, life coaching, deeper mental blockers, discipline science, and a 30/60/90 Foresight mode — driven by new research reports 4–10.

### Added
- **Unblock v2** — new `references/blocker-map.md`: differential diagnosis of 10 psychological blockers with replication status stated (ego depletion dead, mindset shrunk to its surviving core, perfectionism split into concerns vs strivings), an 11-row "founder says X → blocker → first question" table, cascade interactions, and a hardened referral boundary. Three new administered scripts in `unblocking-protocols.md`: Worry Window (stimulus control), Ask Ladder (graded exposure), Self-Compassion Reset (Breines & Chen). Distilled from Report 8 (`references/research/report-8-mental-blockers.md`, 62 sources).
- **Foresight mode** — rolling 30/60/90 premortem (write-first, Klein/prospective-hindsight), tripwires with one-number thresholds and pre-agreed responses in new `state/foresight.md`, reference-class checks on forecasts, weekly mechanical tripwire check inside Weekly Review, quarterly full re-run, and a blameless postmortem loop when a tripwire fires. Evidence-backed exclusions built in: no numeric risk-matrix scores (Cox 2008), no paperwork checklists (replication failures). Distilled from Report 10 (`references/research/report-10-foresight-systems.md`) into `references/foresight-protocols.md` + `state/foresight.template.md`.
- `references/failure-taxonomy.md` — census-grade survival base rates (kills the "90% fail" myth), the two-layer failure-cause taxonomy with attribution-bias correction, stall-vs-fail mechanics (Greiner as heuristic, honestly mixed evidence), a checkable early-warning indicator table, and documented recovery levers. Distilled from Report 6 (`references/research/report-6-failure-taxonomy.md`). Wired into Hard Truth.
- `references/b2b-playbook.md` — B2B structural diagnosis (sales cycle × cash timing × concentration × margin structure × capital intensity), 11 B2B patterns, 17 condensed dossiers, failure cases with named causes. Distilled from Report 4 + gap-filling Report 4b (`references/research/`, 131 sources combined). Key 4b additions: services invert the delegation order (delivery first, sales last — Hawke, Single Grain); the margin-mismatch failure mode (Bench); leverage vs integration capacity (Thrasio); receivables-financing ladder with costs; a benchmark guard against vendor outreach statistics.

## [1.0.0] — 2026-08-19

First public release — sanitized and generalized from a personal build, expanded into a full entrepreneur-mentor system.

### Added
- Mode system (10 lanes): Intake, Quick Counsel, Validate, Strategy Session, Unblock, Decision Gate, Weekly Review + quarterly variant, Crisis, Hard Truth.
- Evidence core distilled from three deep-research reports (95+ sources): `references/doctrine.md` (12 laws + applicability scope note), `references/founder-dossiers.md` (12 documented founders), `references/stage-playbooks.md` ($0→$1M→$10M→$100M), `references/unblocking-protocols.md` (block table + 10 administered interventions).
- Seven entrepreneur modules: `validation-playbook.md`, `finance-fundamentals.md`, `marketing-acquisition.md`, `sales-and-pricing.md`, `hiring-and-delegation.md`, `crisis-protocols.md`, `operating-cadence.md`.
- Full sourced research reports in `references/research/`.
- State/content split: read-only `references/`, gitignored live data in `state/` created from templates at Intake (`founder-context`, `ledger`, `metrics`).
- Directness contract: consent and 1–10 intensity calibration established at Intake, recorded in founder-context.
- Anti-drift enforcement: session-integrity self-audit at close, benchmark-provenance guard with vertical scoping, both-ways accountability on Decision Gate recommendations, escalation after 3+ broken/absent commitments.
- Retention loop: append-only metrics history with stage-transition detection, compound-progress session openers, booked return triggers, quarterly ledger compaction and context-staleness refresh.
- Example sessions demonstrating the register.
