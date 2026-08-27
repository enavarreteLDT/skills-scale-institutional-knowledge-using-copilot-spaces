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

## Additional personas (proposed additions to improve clarity & accountability)

Below are proposed new personas to add to the Roles & Personas document. For each, a short summary, key responsibilities, primary interactions with existing roles, and engagement signals are provided. These are intentionally focused on operational clarity, handoffs, and accountability during planning, execution, and release.

### Tech Lead
Role summary:
- Guides technical direction for a squad or project, ensures design quality, and mentors developers.

Responsibilities:
- Make architecture and major design decisions in coordination with product goals.
- Review complex designs and approve significant technical changes.
- Mentor developers and grow team engineering capability.
- Surface technical risks and propose mitigation plans.

Primary interactions:
- Developers: provide technical guidance, approve designs, and perform code reviews.
- Product Managers: advise on feasibility, performance trade-offs, and effort estimates.
- Project Manager: communicate technical dependencies and risks that affect schedule.

Signals to engage:
- New cross-team integration, significant design changes, or technical debt work requiring prioritization.

---

### Engineering Manager
Role summary:
- Owns engineering capacity, hiring/people management, growth, and higher-level team health.

Responsibilities:
- Manage staffing, career development, and resource allocation.
- Ensure teams have the capacity and skills to deliver planned work.
- Resolve team-level blockers and escalate resourcing conflicts.

Primary interactions:
- Project Manager: align on resourcing, timelines, and capacity-based commitments.
- Tech Leads: coach and remove organizational impediments.
- Product Managers: discuss trade-offs where capacity impacts feature scope.

Signals to engage:
- Resource constraints, sustained delivery issues, major hiring/staffing decisions.

---

### Release / CI Engineer (Release Engineer)
Role summary:
- Maintains CI/CD pipelines, deployment automation, and release/runbook integrity.

Responsibilities:
- Build and maintain pipelines, deployment scripts, and rollback procedures.
- Own release automation and coordinate deployments across environments.
- Run or support release validation and post-deploy diagnostics.

Primary interactions:
- Developers: triage build/release failures and support packaging.
- QA: coordinate staging tests and release validation steps.
- Project Manager: schedule deployment windows and communicate release constraints.

Signals to engage:
- Production releases, pipeline failures, or changes to the release process and tooling.

---

### UX Researcher / Designer
Role summary:
- Owns user research, interaction design, and product UX acceptance criteria.

Responsibilities:
- Run research, create prototypes, and produce design specifications.
- Define UX acceptance criteria and accessibility considerations.
- Collaborate on user flows, mockups, and usability validation.

Primary interactions:
- Product Managers: translate requirements into designs and validate assumptions.
- Developers: clarify implementation details and review UI behavior.
- QA: provide acceptance test cases for UX and accessibility.

Signals to engage:
- New user-facing features, changes to critical flows, or when user feedback indicates usability problems.

---

### Data / Analytics Owner
Role summary:
- Defines success metrics, instruments analytics, and validates product experiments.

Responsibilities:
- Propose metrics and dashboards to measure feature impact.
- Ensure event instrumentation and data quality are implemented.
- Analyze experiments and provide insights to product decisions.

Primary interactions:
- Product Managers: agree on success metrics and experiment design.
- Developers: coordinate instrumentation and event schema changes.
- Project Manager: report progress against metrics and outcomes.

Signals to engage:
- Any work with measurable outcomes, experiments, or changes to analytics instrumentation.

---

### Security / Compliance Liaison
Role summary:
- Reviews security and compliance implications, ensures scans and controls are applied.

Responsibilities:
- Review design and code for security issues and compliance risks.
- Define security acceptance criteria and required scans.
- Support incident response and remediation planning.

Primary interactions:
- Developers: prioritize and guide remediation of security findings.
- Release Engineer: ensure security scans are integrated into pipelines.
- Project Manager: escalate security-impacting risks and coordinate mitigation timelines.

Signals to engage:
- Features touching sensitive data, third-party integrations, or compliance-restricted releases.

---

### Support / Customer Success Liaison
Role summary:
- Represents customer-facing teams, communicates customer issues and prioritizes critical fixes.

Responsibilities:
- Triage and communicate high-impact customer problems or trends.
- Provide reproduction steps and business context to the delivery team.
- Coordinate release communications and support readiness.

Primary interactions:
- Product Managers: inform prioritization based on customer impact.
- QA: provide reproduction details and acceptance cases for fixes.
- Project Manager: advise on stakeholder communications and release messaging.

Signals to engage:
- Production incidents, high-volume support trends, or release readiness checks for customer-impacting changes.

---

## How to incorporate these personas into the document
For each persona entry, add:
1. Short role summary (1–2 sentences).
2. Bullet list of responsibilities (3–6 items).
3. Primary interactions with existing roles (who they coordinate with and why).
4. Signals / acceptance criteria indicating when the persona should be engaged.
5. Optional: example scenarios or playbooks for common handoffs (e.g., release runbook owner, security review checklist).

These additions keep role boundaries and handoffs explicit, improving onboarding, reducing ambiguity during execution, and making escalation and accountability clearer for cross-team work.
