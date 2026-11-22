# AGENT INSTRUCTIONS — READ BEFORE ANY WORK

**Canonical repository:** https://github.com/everythingmilo/six-brand-content-package  
**Default branch:** `main`  
**Repository visibility:** Public. Never add secrets, credentials, private customer data, or confidential business information.

## Mandatory startup sequence
1. Open the canonical repository at https://github.com/everythingmilo/six-brand-content-package and read this file and the root `README.md`. If using a local checkout, confirm its remote points to this exact repository.
2. Read `project/PROJECT_OVERVIEW.md` and `project/PRODUCTION_RULES.md`.
3. Read the relevant brand file(s) under `brands/`.
4. Read `design-systems/FIGMA_SYSTEM.md`.
5. Read `production/HANDOFF.md` and the latest entries in `production/logs/`.
6. Inspect the actual Figma file before claiming any design state is current.

## Authority hierarchy
- Brand identity: the current approved brand books in the canonical Figma file; the matching `brands/*.md` file is a text reference.
- Permanent production requirements: `project/PRODUCTION_RULES.md`.
- Project scope and approved content architecture: `project/PROJECT_OVERVIEW.md`.
- Current status, work in progress, blockers and next action: `production/HANDOFF.md`.
- Historical decisions: `production/logs/` and `archive/`. Historical notes do not override current decisions.

## Rules for every agent
- Do not rely on prior chat history when repository files are available.
- Do not proceed when required source files cannot be accessed; report the exact blocker.
- Never silently revise permanent constants, approved creative direction, scope, or quality standards. Propose the change and record it in the decision log after approval.
- Never copy entire stable brand specifications into the live handoff; link/reference the source file.
- Update the live handoff after every material work session: status, completed/in-progress/blocked items, exact Figma references, dependencies, counts and one precise next action.
- Add meaningful changes to `CHANGELOG.md`; add approval-sensitive decisions to `DECISION_LOG.md`.
- Record which knowledge files were consulted and which handoff sections/logs were changed.
- Mark an asset complete only after actual Figma verification and QA.
- Preserve legacy work unless the user expressly authorizes a change.
- Do not invent business facts, testimonials, claims, specifications, pricing, availability, QR destinations, or customer content.
- If a repo update cannot be pushed, prepare exact Markdown changes locally and report that they are not yet published. Never claim a commit is live until the resulting commit/file can be fetched from GitHub.

## End-of-session report
Report: files read; work completed; files changed; exact Figma refs; unresolved questions/blockers; next action; whether GitHub changes were successfully committed and verified.