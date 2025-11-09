# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security Lead
- For infrastructure/deployment issues, engage DevOps Engineer
- For release decisions, coordinate with Release Manager
- See [Security Review Checklist](./security-review-checklist.md) for security escalation details

## Role-Specific Communication Responsibilities
- **Project Manager**: Weekly status updates, risk communication, stakeholder coordination
- **Product Manager**: Roadmap updates, feature specifications, success metrics reporting
- **Release Manager**: Release schedules, deployment status, post-release summaries
- **Security Lead**: Security incidents, vulnerability reports, security training
- **DevOps Engineer**: Infrastructure status, deployment issues, performance alerts
- **Developers**: PR descriptions, technical design docs, implementation updates
- **QA/Testing**: Test results, bug reports, quality sign-offs
- **UX Designer**: Design reviews, user research findings, usability reports

## Related Documents
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) - Communication patterns by role
- [Security Review Checklist](./security-review-checklist.md) - Security incident communication
