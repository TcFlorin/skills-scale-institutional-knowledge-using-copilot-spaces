# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process library. This documentation provides comprehensive guidance for all phases of project delivery—from initiation through retrospective and continuous improvement.

## Quick Start

New to OctoAcme? Start here:

1. Read [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) for high-level principles and roles
2. Find the relevant phase documentation for your current project stage (links below)

## OctoAcme Process Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The process is organized around five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and create a lightweight Project One-pager that defines the problem, goal, and success metrics, along with stakeholder alignment and resource estimates. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. This structured handoff ensures teams move into execution with clear scope and expectations.

Execution and delivery are guided by a disciplined team rhythm and workflow. Teams conduct daily 15-minute standups focused on progress and blockers, weekly delivery syncs to review progress and flag risks, and demos at sprint or milestone endpoints. Work flows through a project board with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval before merging. Quality is built in through unit and integration tests, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance. When blockers arise, they are triaged in standups (Level 1), escalated to the Product Lead (Level 2), or elevated to sponsors for business-impacting issues (Level 3).

Three core roles drive accountability and decision-making: the **Project Manager** coordinates schedules, risks, and communications; the **Product Manager** defines outcomes, prioritizes the backlog, and measures success; and **Developers** implement features, collaborate on design, and maintain code quality. This clear ownership is reinforced through weekly syncs between PM and PdM, twice-weekly standups, and monthly stakeholder updates. Communication is standardized through templates for weekly status (progress, next steps, risks, decisions) and incident reports. Release decisions are gated by pre-release checklists that confirm acceptance criteria are met, CI/security scans pass, release notes are drafted, and smoke tests are prepared. Finally, after each sprint or release, retrospectives capture what went well and what can improve, with action items tracked and reviewed in subsequent syncs—embedding continuous improvement as a core cultural practice.

## OctoAcme Process Phases

### 1. [Project Initiation](./octoacme-project-initiation.md)
Validate business need, align stakeholders, and create a lightweight plan. Learn when to initiate projects, key deliverables like the One-pager, and the decision gate for moving to planning.

### 2. [Project Planning](./octoacme-project-planning.md)
Turn an approved initiative into an actionable plan and backlog for delivery. Covers kickoff meetings, backlog prioritization, estimation, Definition of Done, and risk management.

### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
Manage day-to-day execution and track progress toward project milestones. Includes team rhythm (standups, syncs, demos), PR workflow, quality and testing practices, and blocker escalation.

### 4. [Risks & Communication](./octoacme-risks-and-communication.md)
Identify, manage, and communicate risks and dependencies. Details risk lifecycle, stakeholder communication templates, and escalation paths.

### 5. [Release & Deployment](./octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production to reduce risk and improve observability. Covers release types, pre-release requirements, deployment checklists, and rollback procedures.

### 6. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements. Learn how to run retrospectives, track action items, and embed continuous improvement as a cultural practice.

## Reference

- [OctoAcme Roles & Personas](./octoacme-roles-and-personas.md) — Understand key roles and responsibilities including Project Managers, Product Managers, and Developers
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — High-level principles, lifecycle overview, key artifacts, and communication cadence

## Key Principles

OctoAcme project management is built on:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Manager (PdM)
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Core Roles at a Glance

| Role | Responsibility |
|------|-----------------|
| **Project Manager** | Coordinates delivery, manages schedules, risks, and communications |
| **Product Manager** | Defines outcomes, prioritizes the backlog, and measures success |
| **Developers** | Implement features, collaborate on design, and maintain code quality |
| **QA/Testing** | Validate quality and acceptance criteria |
| **Stakeholders** | Provide inputs and approvals |

## Getting Help

- **Onboarding new team members?** Start with the Project Management Overview, then assign phase-specific docs as needed.
- **Running a project?** Use the checklists embedded in each phase document to ensure you're following the OctoAcme process.
- **Updating these docs?** See [Adding Content to Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) for the contribution workflow.

## Document Maintenance

These documents are maintained as living artifacts. Suggested updates or clarifications can be submitted using the [Process Doc Update issue template](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). All updates should be reviewed for alignment with existing process docs and team feedback.
