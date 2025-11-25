# OctoAcme Project Management Docs

This README introduces OctoAcme's project management practices and provides links to all key process documents for quick reference and onboarding.

## Summary of OctoAcme Project Management Processes

OctoAcme employs a structured, iterative approach to project management, spanning phases of Initiation, Planning, Execution, Release, and Retrospective. Each phase is backed by artifacts such as one-pagers, risk registers, and checklists, ensuring clear objectives and accountability.

### Project Lifecycle

- **Initiation:** Define the problem statement, identify stakeholders, and establish high-level timelines.
- **Planning:** Break work into shippable increments, estimate scope, and create a prioritized backlog.
- **Execution:** Build, test, review, and iterate using project boards and PR workflows.
- **Release:** Deploy, verify, and announce with rollback plans in place.
- **Retrospective:** Capture learnings and drive continuous improvement.

### Key Workflows

- **Project Boards:** Use GitHub Projects with columns: Backlog, Ready, In Progress, In Review, QA, Done.
- **PR Conventions:** Small PRs (≤400 lines), include issue links and acceptance criteria, require CI checks and at least one approval before merging.
- **Backlog Management:** Prioritized items with clear acceptance criteria, estimates, and owners.
- **Checklists:** Initiation, planning, execution, deployment, and retrospective checklists guide actions at every stage.

### Roles & Personas

| Role | Responsibilities |
|------|------------------|
| **Project Managers** | Coordinate delivery, manage schedules, risks, and communications; facilitate meetings and ensure documentation. |
| **Product Managers** | Own problem statements, prioritize the backlog, define success metrics, and validate outcomes. |
| **Developers** | Implement features, write tests, participate in code reviews, and help identify technical risks. |
| **QA** | Ensure final deliverables meet acceptance criteria through testing and validation. |
| **Stakeholders** | Provide inputs, feedback, and approvals throughout the project lifecycle. |

### Communication Strategies

- **Daily Standups:** 15-minute syncs focused on progress, blockers, and dependencies.
- **Weekly Syncs:** PM + Product Lead alignment; delivery sync to show progress and flagged risks.
- **Stakeholder Updates:** Monthly updates and milestone-based reports.
- **Escalation Paths:** Team-level → PM → Product Lead → Sponsor; security incidents follow dedicated runbooks.
- **Documentation:** Status, risks, and decisions are regularly documented and shared via project README or release docs.

### Quality Assurance Practices

- **Automated CI Tests:** Unit tests, integration tests, and linting run automatically in CI.
- **Security Scanning:** Security scans integrated into the CI pipeline.
- **Manual QA:** Feature acceptance validation when needed.
- **End-to-End Tests:** Smoke tests for critical flows before release.
- **Deployment Checklists:** Pre-release requirements, staging validation, and post-deploy verifications.
- **Retrospectives:** After sprints/releases to feed learnings into continuous improvement.

### Core Principles

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Each project has a named Project Manager and Product Lead.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback and learning.

## Docs Links

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
