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
- Role-specific communication responsibilities:
  - **Project Manager**: Overall status, risks, timeline updates
  - **Product Manager**: Feature updates, business value, roadmap changes
  - **QA Lead**: Quality metrics, test results, release readiness
  - **DevOps Engineer**: Infrastructure status, deployment schedules, incidents
  - **Business Analyst**: Requirement changes, stakeholder feedback

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
- Team-level → Project Manager → Product Lead → Sponsor
- Technical issues: Developer → Tech Lead → DevOps Engineer (if infrastructure-related)
- Quality concerns: QA/Tester → QA Lead → Project Manager
- Design questions: Developer → UX/UI Designer → Product Manager
- Requirement clarifications: Developer → Business Analyst → Product Manager
- For security incidents, follow the security incident runbook and notify Security on-call immediately
