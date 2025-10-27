# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master; focus on progress, blockers, dependencies
- Weekly delivery sync — led by Project Manager; show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone — Product Manager and UX Designer present to stakeholders

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers and QA Automation Engineers)
- End-to-end smoke tests for critical flows before release (QA Automation Engineers)
- Security scanning in CI (automated with QA oversight)
- Manual QA for feature acceptance when needed (QA/Testing with UX Designer for usability validation)

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

### Role Responsibilities in Execution
- **Developers**: Write code, create PRs, conduct code reviews, implement fixes
- **Scrum Master**: Facilitates daily standups, tracks sprint progress, removes blockers
- **Project Manager**: Monitors overall progress, manages risks, coordinates stakeholders
- **QA Automation Engineers**: Runs automated tests, reports quality metrics, validates releases
- **UX Designer**: Reviews implemented features for design fidelity, supports UAT
- **Product Manager**: Validates features against acceptance criteria, provides business feedback

For detailed role interactions, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

---

_Related to: Issue #4 - Enhanced role clarity during execution phase_
