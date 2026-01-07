# OctoAcme Project Management Docs

Welcome to the centralized documentation for OctoAcme's project management practices. This README provides a concise overview of how OctoAcme plans, executes, tracks, and continuously improves projects, and links to the detailed process documents maintained in this folder.

OctoAcme runs projects through a lightweight, stage‑gated lifecycle: Initiation (one‑pager, stakeholder alignment, go/no‑go), Planning (kickoff, prioritized backlog, estimates, Definition of Done), Execution (iterative build/test/review), Release (pre‑release checks, automated deployment when possible), and Close/Retrospective. Day‑to‑day work uses a project board (Backlog → Ready → In Progress → In Review → QA → Done), a Pull Request workflow that favors small PRs and CI gating, and a clear blocker escalation path.

Roles and responsibilities are explicit: Project Managers coordinate delivery and communications; Product Managers own problem definition, prioritization, and success metrics; Developers implement and test; QA owns validation and acceptance; stakeholders provide approvals. Key artifacts include a Project One‑pager, prioritized backlog items with acceptance criteria, a Risk Register, release notes, and retrospective action items to ensure transparency and ownership.

Quality assurance and risk management are embedded in the process: unit/integration/e2e smoke tests and security scanning run in CI, manual QA is used for acceptance when needed, acceptance criteria and a documented Definition of Done drive readiness for review and release, and risk registers are reviewed regularly. Retrospectives produce prioritized action items that are tracked in the backlog to support continuous improvement.

## Process Docs Index
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Quick start
- Read the Project Management Overview to understand lifecycle and cadence.
- Use the Project Initiation Guide to create the project one‑pager and confirm go/no‑go.
- Follow Project Planning and Execution & Tracking during delivery.
- Keep the project README (project-level docs/) and the Risk Register up-to-date during execution.

## Acceptance criteria for this docs set
- Content aligns with the process documents in this folder.
- README provides a useful single-entry summary and links to all process docs.
- New team members can orient themselves quickly using this index and overview.
