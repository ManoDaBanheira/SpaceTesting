# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Knowledge Base. This documentation centralizes our team's approach to running projects, from initiation through retrospectives.

## Overview

OctoAcme uses a structured, iterative project management lifecycle that moves initiatives through initiation, planning, execution, release, and retrospective. During initiation, teams define the business problem, SMART objective, success metrics, stakeholders, timeline, risks, and resource needs in a project one-pager. Once stakeholders confirm the need and priority, the team moves into planning by creating a prioritized backlog, estimating work, identifying dependencies, defining acceptance criteria, and documenting the Definition of Done. Delivery is organized around small, testable increments and tracked through a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done.

Roles and ownership are clearly defined across all projects. The Project Manager coordinates schedules, risks, dependencies, communications, and project documentation, while the Product Manager owns product vision, backlog prioritization, customer outcomes, and success metrics. Developers implement and test features, participate in reviews, and help identify technical risks. QA and testing contributors validate acceptance criteria and overall quality, while stakeholders provide input, approvals, and business context. This model emphasizes clear accountability, customer value, evidence-based decisions, and collaborative delivery.

Communication relies on a regular cadence and transparent reporting throughout project execution. Teams use daily or twice-weekly standups to discuss progress, blockers, and dependencies; weekly PM, product, or delivery syncs to review status and risks; and milestone or sprint demos to show completed work. Stakeholders receive weekly or milestone-based updates using a shared source of truth such as the project README or release documentation. Risks are recorded with impact, likelihood, ownership, mitigation, and status, then reviewed regularly. Escalation proceeds from the delivery team to the Project Manager, Product Lead, and sponsor, with security incidents following the appropriate security escalation path.

Quality assurance is integrated throughout delivery and release rather than performed only at the end. Pull requests should remain small where possible, include issue links and acceptance criteria, and pass automated tests, linting, and security scans before review; at least one approval is generally required before merging. New logic should include unit tests, with integration tests used where appropriate and end-to-end smoke tests covering critical flows. Before release, acceptance criteria must be complete, CI and security checks must pass, release notes and rollback plans must be prepared, and staging smoke tests and post-deployment verification must be completed. After each sprint, release, milestone, or incident, retrospectives capture lessons and create a small number of owned, time-bound improvement actions.

## Core Principles

✓ **Customer-First:** Prioritize customer value and usability  
✓ **Iterative Delivery:** Deliver small, testable increments  
✓ **Clear Ownership:** Each project has a named PM and Product Lead  
✓ **Data-Informed:** Measure impact and iterate based on evidence  
✓ **Psychological Safety:** Encourage feedback and learning

## Quick Links by Phase

### Initiation & Planning
- [Project Management Overview](./octoacme-project-management-overview.md) — Start here for a high-level introduction to our approach, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Define business need, align stakeholders, and decide go/no-go
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments and create your backlog

### Execution & Delivery
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day guidance on standups, workflows, quality, and risk escalation
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, track, and communicate risks and dependencies

### Release & Closure
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized approach to releasing features safely and reliably
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### Reference
- [OctoAcme Personas](./octoacme-roles-and-personas.md) — Define typical roles, responsibilities, and communication patterns

## Core Roles

| Role | Responsibility |
|------|-----------------|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, and measures success |
| **Developers** | Implement features, collaborate on design and testability |
| **QA/Testing** | Validate quality and acceptance criteria |
| **Stakeholders** | Provide inputs and approvals |

## Using These Docs

1. Start with [Project Management Overview](./octoacme-project-management-overview.md) if this is your first time
2. Follow the phase-based links above as your project progresses
3. Refer to [OctoAcme Personas](./octoacme-roles-and-personas.md) to understand roles and responsibilities
4. Use the checklists in each guide as a reference during your project activities
