# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Definition of Done (DoD) Validation
Before moving any item to **Done**, teams validate it against the Definition of Done created during planning.

### How to Validate DoD During Execution
1. **Developer self-check**: confirm every DoD checklist item is addressed in the PR description or linked task.
2. **Reviewer validation**: verify evidence (approvals, passing CI/tests, scan results, documentation links) before approving merge.
3. **QA/PM confirmation**: confirm acceptance criteria, manual QA expectations, and unresolved risks are handled or explicitly tracked.
4. **Board status update**: only move work to `Done` after merge/deploy criteria are met and evidence is captured in the issue/PR.

### DoD Validation Checklist Before Marking Complete
- [ ] Acceptance criteria are fully met
- [ ] Required code reviews are approved
- [ ] CI checks (tests/lint/security) are passing
- [ ] QA validation is complete or not required (and recorded)
- [ ] Documentation and release notes are updated when applicable
- [ ] Outstanding risks/follow-ups are captured with owner and due date

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
