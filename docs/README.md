# OctoAcme Project Management Docs

This `docs/` folder is the entry point for OctoAcme's project management approach. It gives team members a shared source of truth for how work is initiated, planned, delivered, released, and improved over time.

## Table of Contents
- [OctoAcme Project Management Overview](#octoAcme-project-management-overview)
- [Process Phases at a Glance](#process-phases-at-a-glance)
- [Key Workflows, Roles, Communication, and Quality Practices](#key-workflows-roles-communication-and-quality-practices)
- [Core Principles and Values](#core-principles-and-values)
- [Process Documentation Index](#process-documentation-index)

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business needs and create a lightweight One-pager that captures the problem statement, goals, success metrics, stakeholders, and initial risks. This stage serves as a decision gate—work only moves forward to Planning once success metrics are clear, stakeholders are aligned, and team availability is confirmed. This front-loaded clarity reduces downstream surprises and ensures alignment across the organization.

The Planning phase transforms approved initiatives into actionable backlogs and delivery schedules. Teams conduct a kickoff meeting, break work into shippable increments with clear acceptance criteria, estimate scope using T-shirt sizing or story points, and define a **Definition of Done (DoD)** that establishes a consistent quality bar. A critical aspect of OctoAcme planning is explicit identification of dependencies, risks, and integration points—captured in a Risk Register that tracks likelihood, impact, mitigation strategies, and ownership. Release plans and milestone maps create visibility into timelines, and the structured backlog ensures that every item has an owner, clear acceptance criteria, and a planned release target.

During Execution and Tracking, teams operate with a consistent rhythm: daily standups (15 minutes) focused on progress and blockers, weekly delivery syncs showing status and flagged risks, and demos at sprint or milestone completion. Work flows through a project board with columns—Backlog, Ready, In Progress, In Review, QA, Done—and every item is validated against the DoD before marking complete. Quality is embedded throughout: unit and integration tests run in CI, security scanning is mandatory, small PRs (≤400 lines) are encouraged, and at least one approval is required before merge. The DoD Validation Checklist ensures developers self-check their work, reviewers verify evidence, and QA/PM confirm acceptance criteria and risk handling.

Release and post-project activities formalize the deployment process and capture continuous improvement. Pre-release requirements include passing CI/security scans, drafted release notes, and documented rollback plans. Teams conduct post-release smoke tests and stakeholder announcements, with clear escalation and incident response playbooks for failures. After each sprint, release, or milestone, OctoAcme runs a retrospective to capture what went well, what could improve, and generates 2–3 prioritized action items. This embedded learning cycle, combined with clear roles (Project Manager, Product Manager, Developers, QA, Stakeholders), regular communication cadences, and a single source of truth in the project repository, enables OctoAcme to deliver consistently while building institutional knowledge and psychological safety across teams.

## Process Phases at a Glance
1. **Initiation**: Validate the business need, define the problem and success metrics, identify stakeholders, and decide go/no-go for planning.
2. **Planning**: Convert the approved initiative into a prioritized backlog with estimates, milestones, dependencies, risks, and a clear Definition of Done (DoD).
3. **Execution**: Deliver in iterative increments using daily/weekly operating cadence, active blocker management, and transparent project board tracking.
4. **Release**: Confirm release readiness with CI/testing/security checks, publish release notes, execute rollout, and verify post-release health.
5. **Close & Retrospective**: Capture outcomes, review what worked and what did not, and create action items to improve future planning and execution.

## Key Workflows, Roles, Communication, and Quality Practices
- **Workflows**: One-pager to kickoff, backlog-driven iteration, PR-based delivery, release readiness checklists, and retrospective action tracking.
- **Personas/Roles**: Project Managers coordinate delivery and risk, Product Managers prioritize outcomes, Developers build/review/test, QA verifies acceptance and release readiness, and Stakeholders provide alignment and decisions.
- **Communication**: Daily standups, weekly delivery syncs, milestone demos, and clear escalation paths keep teams and stakeholders aligned.
- **Quality Assurance**: Definition of Done validation, CI checks, automated and manual testing as needed, security scanning, peer review, and post-release smoke checks.

## Core Principles and Values
- **Customer value first**: Prioritize measurable outcomes over activity.
- **Clarity and accountability**: Define owners, acceptance criteria, and decision points early.
- **Transparency and communication**: Keep progress, risks, and dependencies visible.
- **Quality by default**: Build testing, review, and security into the delivery flow.
- **Continuous improvement**: Use retrospectives to turn lessons learned into concrete actions.

## Process Documentation Index
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme — Project Planning](./octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)
- [OctoAcme Personas](./octoacme-roles-and-personas.md)
