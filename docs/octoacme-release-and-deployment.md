# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (monitored by DevOps Engineer)
- QA Lead sign-off on test results and quality gates
- UX/UI Designer validates design implementation (if applicable)
- Release notes drafted (Project Manager or Product Manager)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared (QA/Testers)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - Project Manager
- [ ] Backup or snapshot (if applicable) - DevOps Engineer
- [ ] Deploy to staging and run smoke tests - DevOps Engineer + QA/Testers
- [ ] QA Lead approves staging test results
- [ ] Deploy to production (automated pipeline preferred) - DevOps Engineer
- [ ] Run post-deploy verifications - DevOps Engineer + QA/Testers
- [ ] Announce release to stakeholders and support - Project Manager
- [ ] Product Manager monitors business metrics post-release

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - DevOps Engineer triggers incident response and notifies on-call
  - Project Manager coordinates communication with stakeholders
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - QA Lead verifies rollback success
  - Triage root cause and capture action items (cross-functional team)
  - Business Analyst may need to re-assess requirements if issue stems from misunderstanding

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
