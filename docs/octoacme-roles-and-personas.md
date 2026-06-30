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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed)

### Delivery Lead
Role summary:
Delivery Leads focus on day-to-day coordination of a delivery stream (one or more related features or projects).

Responsibilities:
- Coordinate work across feature teams to ensure milestones are met
- Maintain the delivery schedule and highlight risks to the PM
- Facilitate cross-team backlog grooming and unblock dependencies
- Track progress against milestones and update risk register as needed

Interactions:
- Works closely with the PM for prioritization and with Project Managers for status reporting
- Escalates cross-team blockers to Product Lead or Sponsor when needed
- Partners with Technical Program Managers and Developers to align deliveries

---

### Technical Program Manager (TPM)
Role summary:
TPMs manage technically complex initiatives, owning technical dependencies, integration points, and release coordination.

Responsibilities:
- Track technical dependencies and integration timelines across teams
- Coordinate architecture decisions and design reviews with engineering leads
- Drive end-to-end planning for multi-team technical deliverables
- Maintain an integration and cutover plan for complex releases

Interactions:
- Partners with Developers, Engineering Leads, and Project Managers to align schedules and mitigations
- Works with DevOps/SRE to coordinate deployments, runbooks, and rollbacks
- Communicates technical risk and mitigation strategies to Product and Project leadership

---

### DevOps / SRE Representative
Role summary:
Operational ownership for deployments, observability, and runbook readiness.

Responsibilities:
- Ensure CI/CD pipelines and infra configuration meet release needs
- Define rollout and rollback procedures; own post-deploy verification
- Surface operational risks and performance constraints early in planning
- Ensure monitoring, alerts, and runbooks are in place before release

Interactions:
- Collaborates with Developers, TPMs, and PMs on release readiness
- Coordinates with on-call and support teams for incident preparedness
- Advises on deployment strategy (canary, blue/green, feature flags)

---

### UX Researcher / Designer
Role summary:
Provides user insights, validates designs, and ensures product usability.

Responsibilities:
- Conduct user research and usability testing for features
- Produce design artifacts and acceptance criteria related to UX
- Validate that implementations match design intent
- Provide accessibility guidance and UX acceptance checks

Interactions:
- Works with Product Managers to define success metrics and acceptance criteria
- Collaborates with Developers and QA to ensure design fidelity in implementation
- Participates in demos and usability reviews before release

---

### Business Analyst / Data Analyst
Role summary:
Bridges product and data, ensuring clear requirements and measurable success metrics.

Responsibilities:
- Define detailed acceptance criteria and data requirements
- Produce measurement plans and dashboards to track success metrics
- Support post-release analysis and recommendations
- Ensure instrumentation and analytics are in place for feature validation

Interactions:
- Works with PMs to translate goals into measurable metrics
- Partners with Developers/QA on instrumentation requirements
- Provides analysis to Product and leadership to guide next steps

---

### Stakeholder Advocate
Role summary:
A named stakeholder liaison for large, cross-organizational initiatives.

Responsibilities:
- Maintain stakeholder communication and decisions log
- Represent stakeholder constraints/requirements in planning
- Drive alignment across business units when conflicts arise
- Ensure stakeholder concerns are surfaced in risk and decision logs

Interactions:
- Regular sync with PM and Project Manager for status and decisions
- Escalates strategic issues to Product Lead or Sponsor
- Coordinates stakeholder input into acceptance criteria and release plans

---

(End of file)
