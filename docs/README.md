# OctoAcme Project Management

This repository contains OctoAcme's project management process documents. The README centralizes links to the canonical process docs in the docs/ folder and provides a short summary of how OctoAcme runs projects to help onboarding and quick reference.

OctoAcme runs projects through a lightweight, repeatable lifecycle that moves work from initiation into planning, execution, release, and continuous improvement. Initiation requires a one‑pager that captures the problem, goals, success metrics, stakeholders, and a high‑level timeline; only after success criteria and stakeholder alignment are confirmed does work move into planning. Planning breaks approved initiatives into shippable backlog items with clear acceptance criteria, estimates, a Definition of Done, and a release plan. Execution uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a pull‑request workflow that favors small PRs, CI/lint gating, linked issues, acceptance criteria in the description, and at least one approval before merge.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate schedules, risks, and communications; Developers implement, test, and document; QA validates acceptance criteria and runs manual checks when needed; stakeholders provide inputs and approvals. Project artifacts—one‑pagers, roadmaps, backlogs, risk registers, and retrospective notes—are the single sources of truth and are expected to be maintained in the repository/docs.

Quality assurance is built into the workflow: unit and integration tests for new logic, security scans in CI, and smoke/end‑to‑end checks for critical flows before release. Pre‑release gates include passing CI and security scans, draft release notes, and a documented rollback/mitigation plan. Retrospectives capture action items which are tracked into the backlog so processes continuously improve.

## Docs (links)
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md
