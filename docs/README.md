# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents. The files below provide structured guidance for how OctoAcme initiates, plans, executes, releases, and improves projects. Use this README as the single source of truth to find artifacts, role responsibilities, checklists, and templates that keep work visible and predictable across teams.

OctoAcme runs projects through a lightweight, stage-gated lifecycle that emphasizes clear outcomes, small increments, and frequent feedback. Work begins with a concise Project One-pager that confirms the problem, success metrics, stakeholders, and a go/no‑go decision. Approved initiatives move into planning to produce a prioritized backlog with acceptance criteria, estimates, and a Definition of Done. Execution is tracked on a project board and follows a PR/CI-first approach where small PRs, automated tests, and clear acceptance criteria accelerate review and reduce risk.

Teams use a regular communication cadence—daily standups, weekly delivery syncs, and end‑of‑sprint demos—to surface progress, dependencies, and blockers. Project Managers coordinate schedules and risk, Product Managers own outcomes and prioritization, Developers implement and test, QA validates acceptance, and Stakeholders provide inputs and approvals. Escalation paths are tiered (team → PM → Product Lead → Sponsor) and incident communications follow a triage and blameless retrospective process.

Quality is enforced across the workflow: unit and integration tests, smoke tests for critical flows, security scanning in CI, and manual QA where needed. Releases use a checklist (staging smoke tests, automated pipelines, post‑deploy verifications) and a rollback/incident playbook to minimize production impact. Retrospectives capture prioritized action items that are tracked back into the backlog to ensure continuous improvement.

## Docs (links)

- [Project Management Overview](docs/octoacme-project-management-overview.md) — Introduction to roles, principles, lifecycle, and key artifacts.  
- [Project Initiation Guide](docs/octoacme-project-initiation.md) — One-pager template, initiation checklist, and decision gate criteria.  
- [Project Planning](docs/octoacme-project-planning.md) — Backlog templates, sprint planning guidance, and risk/dependency handling.  
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) — Team rhythms, workflows, PR guidance, quality/testing, and reporting.  
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md) — Release types, deployment checklist, and rollback playbook.  
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking improvements.  
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md) — Risk register format, communication templates, and escalation paths.  
- [Roles & Personas](docs/octoacme-roles-and-personas.md) — Role summaries and responsibilities used across the docs.

## How to contribute

Use the issue template "Add Content to Project Management Process Docs" (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates or new process docs. Include the rationale and suggested content; the template will guide what’s needed to make small, reviewable changes.

## Acceptance Criteria

- [x] Content aligns with existing process docs  
- [x] Update improves clarity or closes a documented gap  
- [ ] Proposed content has been reviewed with stakeholders (if needed)
