# Six-Brand Content Package — Project Knowledge Base

This public repository is the shared source of truth for stable project knowledge and agent instructions. Do not store credentials, private customer data, unreleased confidential commercial information, or personal data here. The dynamic production tracker lives at [`production/HANDOFF.md`](production/HANDOFF.md).

## Start here — agents must follow this order
1. [`project/AGENT_INSTRUCTIONS.md`](project/AGENT_INSTRUCTIONS.md)
2. [`project/PROJECT_OVERVIEW.md`](project/PROJECT_OVERVIEW.md)
3. [`project/PRODUCTION_RULES.md`](project/PRODUCTION_RULES.md)
4. The applicable brand file(s) in [`brands/`](brands/)
5. [`design-systems/FIGMA_SYSTEM.md`](design-systems/FIGMA_SYSTEM.md)
6. [`production/HANDOFF.md`](production/HANDOFF.md) and current logs

**Repository location:** https://github.com/everythingmilo/six-brand-content-package  
**Repository visibility:** Public (created by the project owner on 2026-11-22).  
**Default branch:** `main`.  
**GitHub publishing status:** Repository existence and write permissions verified through the connected GitHub account. All 18 knowledge-base files have been committed to `main`; the repository contents have been verified.

## Authority model
- GitHub project and brand files define durable project constants, standards, and instructions.
- `production/HANDOFF.md` defines current status, checklist progress, milestones, blockers, Figma references, and next actions.
- The current approved brand books inside the canonical Figma file remain the visual source of truth.
- `archive/ORIGINAL_FULL_HANDOFF.md` preserves the complete original long-form handoff, including every individual deliverable brief, for traceability. Do not use superseded legacy directions where newer approved rules conflict.

## Repository map
```text
/
  README.md
  brands/                         # one stable Markdown file per brand
  project/                        # overview, production rules, agent instructions
  design-systems/                 # Figma workspace/continuity system
  production/
    HANDOFF.md                    # live production state
    checklists/                   # QA and delivery gates
    logs/                         # chronological changes and decisions
  archive/                        # full preserved original handoff
```

## Update policy
- Update stable constants only when the user approves a change; record it in the decision log and changelog.
- Update the production handoff after meaningful work. Keep it concise and current.
- Never treat a working creative assumption as verified business information.
- Never claim a GitHub commit or Figma change until it is verified.