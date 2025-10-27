# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

### Role Responsibilities in Release
- **Project Manager**: Coordinates release timing and stakeholder communication
- **Developers**: Ensure code is merge-ready and assist with deployment troubleshooting
- **QA Automation Engineers**: Execute final smoke tests and validate deployment success
- **Product Manager**: Reviews release notes and approves go-live decision
- **UX Designer**: Validates user-facing changes in production environment
- **Scrum Master**: Facilitates release retrospective and captures lessons learned

For detailed role interactions, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

---

_Related to: Issue #4 - Enhanced role clarity in release and deployment_
