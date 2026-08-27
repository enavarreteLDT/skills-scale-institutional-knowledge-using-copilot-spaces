# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This folder contains the core guides used to run projects from initiation through planning, execution, release, and retrospective improvement. The README below gives a concise overview of our approach, key workflows, roles, and quality practices, and links to the full process documents.

OctoAcme follows a staged lifecycle that begins with focused initiation and moves through planning, execution, release, and continuous improvement. Initiation requires a Project One‑pager that captures the problem, objective, success metrics, stakeholders, timeline, and initial risks; a decision gate ensures metrics, stakeholder buy‑in, and team availability before committing to planning. Planning converts approved initiatives into a prioritized backlog with clear acceptance criteria, estimates, a Definition of Done, and a simple risk register to surface and assign mitigations.

Execution is driven by a predictable workflow and board-based tracking: items flow through Backlog → Ready → In Progress → In Review → QA → Done, and pull requests are intentionally small and test-backed (target ≤ 400 lines). Team rhythm includes daily standups for blockers, weekly delivery syncs for progress and risks, and end‑of‑sprint demos. Pull requests should include issue links and acceptance criteria, run CI (tests, lint, security scans), and require at least one approval before merging. Cross-team dependencies and escalations follow documented paths to ensure timely resolution.

Roles are explicit to ensure clear ownership: Product Managers define outcomes and success metrics, Project Managers coordinate schedule, risks, and communications, Developers build and test, and QA validates acceptance and performs manual or automated checks. Quality is enforced through unit/integration tests, smoke tests for critical flows, CI pipelines with security scanning, and a release checklist that includes staging validation and rollback plans. Retrospectives capture actionable improvements (owners and due dates) and feed those items back into the backlog so process and product quality improve iteratively.

## Documents (table of contents)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Quick lifecycle reference
1. Initiation — validate need, align stakeholders, define success metrics  
2. Planning — break into shippable increments, estimate, identify dependencies  
3. Execution — build, test, review, track progress, manage blockers  
4. Release — staging validation, deploy, verify, announce  
5. Close & Retrospective — capture learnings and add improvements to backlog

## Getting started
Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand roles, artifacts, and the broader lifecycle. Use the table above to jump to detailed guidance for each phase.

## Contact
Questions about these processes? Reach out to your Project Manager or Product Lead.
