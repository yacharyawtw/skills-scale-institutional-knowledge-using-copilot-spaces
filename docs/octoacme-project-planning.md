# OctoAcme — Project Planning

## Purpose
Turn an approved initiative into an actionable plan and backlog for delivery.

## Objectives
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities

## Activities
1. Kickoff meeting with stakeholders and delivery team
2. Create prioritized backlog with acceptance criteria
3. Estimate scope (T-shirt sizing or story points)
4. Define Definition of Done (DoD)
5. Identify dependencies and integration points
6. Create release plan and milestone map

## Definition of Done (DoD) Template
Use this template during planning and keep it visible in the project board or PR template so everyone evaluates work with the same quality bar.

- Item / Story:
- Owner:
- Planned release or milestone:

### DoD Checklist
- [ ] **Scope & value delivered**: Acceptance criteria are met and validated against the backlog item.
- [ ] **Code quality**: Implementation is complete, follows team conventions, and has no unresolved critical defects.
- [ ] **Code review completed**: PR includes issue context, receives required approvals, and all review comments are resolved or tracked.
- [ ] **Automated tests pass**: Unit/integration tests are added or updated, and CI is green.
- [ ] **Manual validation complete**: Critical user flows are verified in the appropriate environment (QA/staging/preview).
- [ ] **Documentation updated**: User-facing or internal docs, runbooks, and release notes are updated when applicable.
- [ ] **Security & compliance checks complete**: Required security scans pass and no unresolved high-risk findings remain.
- [ ] **Operational readiness confirmed**: Monitoring/logging impacts are considered and rollback or mitigation steps are documented when needed.

### Typical DoD Criteria Examples
- At least one approved code review before merge.
- Unit and integration tests pass in CI for the changed area.
- Feature flags, migrations, and rollback instructions are documented for risky releases.
- API or user workflow changes include updates to docs/changelogs.
- Security checks (such as dependency or code scanning) run and are reviewed before marking complete.

## Backlog Item Template
- Title:
- Description:
- Acceptance criteria:
- Priority:
- Estimate:
- Owner:
- Related docs/links:

## Sprint / Iteration Planning
- Timebox planning to agreed sprint length
- Pull items that meet DoD and have clear acceptance criteria
- Ensure team capacity is respected

## Risk & Dependency Management
- Capture in Risk Register:
  - ID, Description, Impact, Probability, Owner, Mitigation
- Mark cross-team dependencies in the project board and escalate during weekly syncs

## Planning Checklist
- [ ] Project kickoff held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted
