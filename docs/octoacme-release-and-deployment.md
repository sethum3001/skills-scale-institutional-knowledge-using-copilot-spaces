# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by DevOps Engineer)
- Security review completed and approved by Security Lead
- QA sign-off obtained
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- See [Release Readiness Checklist](./release-readiness-checklist.md) for complete requirements

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (coordinated by Release Manager)
  - Engage Security Lead if security-related
  - Rollback to last known-good release if necessary (executed by DevOps Engineer)
  - Triage root cause and capture action items
  - Conduct post-incident review with all involved roles

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

## Release Roles and Accountability
- **Release Manager**: Coordinates release execution, makes go/no-go decisions
- **DevOps Engineer**: Executes deployment automation, monitors system health
- **Security Lead**: Provides security sign-off, monitors for security events
- **QA/Testing**: Performs smoke tests, validates functionality
- **Product Manager**: Approves release content and scope
- **Project Manager**: Coordinates cross-team dependencies
- **Developers**: Available for troubleshooting during deployment

## Related Documents
- [Release Readiness Checklist](./release-readiness-checklist.md) - Detailed pre-release requirements
- [Security Review Checklist](./security-review-checklist.md) - Security validation steps
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) - Detailed role descriptions

