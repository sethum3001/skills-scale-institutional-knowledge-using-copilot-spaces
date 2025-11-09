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
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers, QA)
- End-to-end smoke tests for critical flows before release (QA)
- Security scanning in CI (DevOps Engineer, monitored by Security Lead)
- Manual QA for feature acceptance when needed (QA)
- UX validation for user-facing changes (UX Designer, QA)
- See [Security Review Checklist](./security-review-checklist.md) for security validation steps

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Security issues: Follow Security Lead escalation process (see [Security Review Checklist](./security-review-checklist.md))
- Infrastructure/deployment issues: Engage DevOps Engineer
- Release blockers: Coordinate with Release Manager

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Regular demos scheduled (Project Manager)
- [ ] Risk register updated weekly (Project Manager)
- [ ] Security scanning enabled in CI (DevOps Engineer, Security Lead)
- [ ] Release coordination plan established (Release Manager)

## Related Documents
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) - Role responsibilities
- [Security Review Checklist](./security-review-checklist.md) - Security validation
- [Release Readiness Checklist](./release-readiness-checklist.md) - Release preparation
