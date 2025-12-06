# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - Attendees: Developers, QA/Testers, Project Manager
  - Optional: UX/UI Designer (for design-heavy sprints), DevOps Engineer (for deployment sprints)
- Weekly delivery sync — show progress, updates, and flagged risks
  - Attendees: Project Manager, Product Manager, Tech Lead, QA Lead, DevOps Engineer
  - Updates from Business Analyst and UX/UI Designer as needed
- Demo/Review at the end of each sprint or milestone
  - Attendees: Full team + stakeholders
  - UX/UI Designer validates design implementation
  - QA Lead presents quality metrics

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developer responsibility)
- Integration tests where applicable (Developer + QA collaboration)
- End-to-end smoke tests for critical flows before release (QA/Testers)
- Design validation against specs (UX/UI Designer + QA)
- Security scanning in CI (DevOps Engineer setup)
- Manual QA for feature acceptance when needed (QA/Testers)
- QA Lead reviews test coverage and approves quality gates

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
  - Developers, QA/Testers resolve within team
- Level 2: Project Manager escalates to functional leads
  - Technical blockers → Tech Lead
  - Design questions → UX/UI Designer
  - Requirement clarifications → Business Analyst
  - Infrastructure/deployment → DevOps Engineer
  - Quality concerns → QA Lead
- Level 3: Product Lead and stakeholder escalation
  - PM and Product Manager align on priority/scope changes
- Level 4: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Design handoff process established (UX/UI Designer → Developers)
- [ ] Regular demos scheduled with stakeholder attendance
- [ ] QA Lead tracking quality metrics and test coverage
- [ ] Risk register updated weekly by Project Manager
- [ ] DevOps Engineer monitors deployment pipeline health
