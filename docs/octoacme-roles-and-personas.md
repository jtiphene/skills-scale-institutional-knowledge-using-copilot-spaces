# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Additional Personas (Proposed Additions)

These personas are recommended additions to clarify handoffs, accountability, and cross-functional collaboration for modern delivery practices. Each persona below contains a summary, core responsibilities, and how they typically interact with existing roles.

### Release Manager

Role summary
- Coordinates release planning and execution across teams for predictable, low-risk deployments.

Responsibilities
- Maintain the release calendar and coordinate release windows
- Own the release checklist and readiness gating (pre-release signoffs)
- Validate rollback/runbook and cutover plans
- Coordinate communication and post-deploy verification
- Facilitate triage during release incidents

Interactions
- Works closely with PM to schedule releases and communicate stakeholder expectations
- Collaborates with DevOps Engineers to validate pipelines and rollbacks
- Coordinates with QA Lead for gating and acceptance verification
- Notifies Support and Customer Success for production arrival and known issues

Why this helps
- Centralizes release accountability to reduce last-minute surprises and improve cross-team visibility.

### QA Lead

Role summary
- Owns the test strategy, quality gates, and acceptance criteria signoffs across the project lifecycle.

Responsibilities
- Define test strategy (unit, integration, E2E, performance) for features/releases
- Maintain test plans and acceptance criteria enforcement
- Lead test execution and coordinate manual QA where necessary
- Track test coverage and quality metrics
- Escalate risks related to quality to PM and Product Lead

Interactions
- Partners with Developers to define acceptance criteria and testability
- Works with Product Managers to validate acceptance criteria and business expectations
- Coordinates with Release Manager for gating and release signoffs
- Provides QA status in weekly delivery syncs

Why this helps
- Strengthens quality focus, ensures consistent gating before release, reduces production defects.

### UX Designer

Role summary
- Owns the user experience design, ensuring usability and accessibility are considered through delivery.

Responsibilities
- Translate product requirements into wireframes, mockups, and interaction patterns
- Validate designs with user research or prototypes where feasible
- Define design acceptance criteria and accessibility checks
- Collaborate with developers on implementation details and styling
- Maintain design assets and pattern library

Interactions
- Works with Product Managers to shape feature requirements and user journeys
- Collaborates with Developers to ensure feasible implementation and handoffs
- Provides usability feedback during demos and acceptance reviews
- Coordinates with QA Lead for UX-focused test cases

Why this helps
- Improves user outcomes, reduces rework, and ensures design integrity throughout implementation.

### DevOps Engineer

Role summary
- Ensures reliable build, deployment, and production operations through automation, monitoring, and platform improvements.

Responsibilities
- Maintain CI/CD pipelines and automate repeatable tasks
- Support environment provisioning and infrastructure as code
- Monitor production health and implement observability
- Assist with incident response and post-incident remediation
- Implement deployment safety checks and rollback mechanisms

Interactions
- Partners with Developers for pipeline needs and release automation
- Works with Release Manager to validate deployment plans
- Coordinates with QA Lead for environments and test automation support
- Escalates operational risks to PM when needed

Why this helps
- Accelerates delivery through automation and reduces deployment friction and incidents.

### Support / On-call Representative

Role summary
- Acts as the bridge between production incidents and the delivery team, ensuring customer-impacting issues are handled and communicated.

Responsibilities
- Triage incoming support issues and guide initial investigation
- Communicate recurring or severe issues into project backlog
- Liaise with DevOps/Developers during incidents and postmortems
- Provide customer context and severity to the team

Interactions
- Works with DevOps and Developers during on-call escalations
- Notifies Product and Project Managers of customer-impacting incidents
- Helps prioritize bug fixes and production improvements with Product Managers

Why this helps
- Improves customer feedback loop and ensures production issues are visible and acted on.

---

## How to use these personas

- For each project, list the primary named role (e.g., Release Manager: @username) in the Project One-pager.
- Use the persona sections to write clear role handoffs in handoff checklists (e.g., release handoffs, post-incident tasks).
- When assigning owners to Risks and Action Items, prefer the most relevant persona rather than a generic team tag.

---

## Appendix: Template for role entry

When adding a new persona to the doc, include:
- Role Summary (1–2 lines)
- Responsibilities (bulleted)
- Typical Interactions (who they pair with and handoffs)
- Why this persona matters (short rationale)
