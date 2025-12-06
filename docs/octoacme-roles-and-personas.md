# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testers

### Role Summary
QA/Testers ensure software quality by designing tests, executing test plans, and identifying defects before release. They collaborate with developers and product teams to validate features meet requirements.

### Responsibilities
- Create and maintain test plans and test cases
- Execute manual and automated tests
- Report and track bugs and regressions
- Participate in acceptance testing and sign-off
- Help refine acceptance criteria during planning

### Goals
- Catch defects early to reduce rework
- Ensure features meet acceptance criteria
- Maintain high product quality and user satisfaction

### Typical Communication
- Test status updates in daily standups
- Bug reports and regression tracking
- Sign-off and acceptance criteria validation

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered designs that balance usability, aesthetics, and business goals. They work with Product Managers to understand user needs and collaborate with Developers to implement designs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity mockups
- Define design systems and component libraries
- Collaborate with developers on implementation feasibility
- Validate implemented features match design specifications

### Goals
- Deliver intuitive and accessible user experiences
- Ensure design consistency across the product
- Reduce user friction and improve satisfaction metrics

### Typical Communication
- Design reviews with Product Managers and stakeholders
- Handoff sessions with developers including design specs
- Feedback sessions during sprint demos
- Collaboration on acceptance criteria for UI features

### Collaboration Points
- **With Product Managers**: Translate product requirements into user flows and designs
- **With Developers**: Provide detailed specs, review implementations, and iterate on feasibility
- **With QA/Testers**: Define expected UI behavior for test cases
- **With Business Analysts**: Incorporate business rules into user workflows

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure and automation pipelines that enable reliable, efficient software delivery. They collaborate with developers to streamline CI/CD and ensure production stability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure provisioning and configuration
- Monitor system health, performance, and security
- Implement deployment automation and rollback strategies
- Support incident response and post-mortem analysis

### Goals
- Reduce deployment friction and cycle time
- Ensure high availability and system reliability
- Automate repetitive operational tasks
- Maintain security and compliance standards

### Typical Communication
- Infrastructure status in weekly delivery syncs
- Deployment coordination with Project Managers
- Incident response and escalation
- Capacity planning with technical leads

### Collaboration Points
- **With Developers**: Provide CI/CD support, optimize build times, and troubleshoot deployment issues
- **With Project Managers**: Coordinate deployment windows and communicate infrastructure risks
- **With QA Lead**: Ensure test environments match production configurations
- **With Security**: Implement security scanning and compliance checks in pipelines

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams by gathering requirements, documenting processes, and ensuring solutions align with business objectives.

### Responsibilities
- Elicit and document business requirements
- Analyze current processes and identify improvement opportunities
- Create functional specifications and user stories
- Validate that delivered solutions meet business needs
- Facilitate stakeholder alignment and decision-making

### Goals
- Ensure clear, accurate, and complete requirements
- Reduce rework from requirement misunderstandings
- Align technical solutions with business value

### Typical Communication
- Stakeholder interviews and requirement workshops
- Requirement documentation and specifications
- Validation sessions with Product Managers and developers
- Business case presentations

### Collaboration Points
- **With Product Managers**: Refine product vision into detailed requirements and acceptance criteria
- **With Developers**: Clarify requirements, answer technical questions, and validate implementations
- **With QA/Testers**: Define test scenarios based on business rules
- **With UX/UI Designers**: Ensure designs support business workflows

---

## QA Lead

### Role Summary
QA Leads define and oversee the quality strategy for projects, manage testing teams, and ensure quality standards are met throughout the development lifecycle. They balance hands-on testing with leadership and strategic planning.

### Responsibilities
- Define testing strategy and quality standards
- Lead and mentor QA/Testers team
- Create and maintain test plans for major releases
- Track quality metrics and report on test coverage
- Coordinate acceptance testing and release sign-off
- Escalate quality risks to Project and Product Managers

### Goals
- Establish consistent quality practices across projects
- Minimize production defects through comprehensive testing
- Improve testing efficiency and automation coverage
- Ensure timely and accurate quality reporting

### Typical Communication
- Quality status reports in weekly delivery syncs
- Test strategy reviews during planning
- Escalation of quality risks to leadership
- Coordination with automation and CI/CD teams

### Collaboration Points
- **With Project Managers**: Provide quality metrics, coordinate testing timelines, and flag quality risks
- **With Developers**: Review testability of features, coordinate bug fixes, and plan automation
- **With DevOps Engineers**: Align on test environment setup and CI integration
- **With Product Managers**: Validate acceptance criteria and coordinate user acceptance testing
- **With QA/Testers**: Assign work, provide guidance, and review test coverage

---

## Role Interaction & Communication Matrix

The following table clarifies key handoffs and communication expectations between roles to minimize ambiguity and ensure smooth collaboration:

| From Role | To Role | Key Handoffs | Communication Frequency | Primary Artifacts |
|-----------|---------|--------------|------------------------|-------------------|
| Product Manager | Business Analyst | Product vision, success metrics | Weekly / As needed | Product requirements, roadmap |
| Business Analyst | Developers | Functional specs, acceptance criteria | Sprint planning / Ad-hoc | User stories, requirement docs |
| Business Analyst | UX/UI Designer | Business workflows, user needs | Early in planning | Process flows, requirements |
| UX/UI Designer | Developers | Design specs, mockups, prototypes | Design review / Handoff | Design files, component specs |
| Developers | QA/Testers | Feature implementation, test data | PR ready / Daily | Pull requests, feature branches |
| QA Lead | QA/Testers | Test assignments, quality standards | Daily / Sprint start | Test plans, assignments |
| QA Lead | Project Manager | Quality status, risk escalation | Weekly sync / Ad-hoc | Quality reports, risk log |
| DevOps Engineer | Developers | CI/CD support, deployment info | As needed / Incidents | Pipeline docs, runbooks |
| DevOps Engineer | Project Manager | Deployment schedules, infrastructure risks | Weekly / Release planning | Deployment plans, status |
| Project Manager | All Roles | Timeline updates, blockers, decisions | Weekly status / Daily standup | Project plan, status reports |

### Communication Best Practices

**During Project Initiation:**
- Product Manager and Business Analyst collaborate on requirements
- UX/UI Designer begins early research and conceptual designs
- DevOps Engineer reviews infrastructure needs
- QA Lead provides input on testability and quality requirements

**During Planning:**
- Business Analyst presents detailed requirements to the team
- UX/UI Designer shares design direction and seeks feedback
- QA Lead defines test strategy and resource needs
- DevOps Engineer confirms CI/CD and environment readiness

**During Execution:**
- Developers coordinate with UX/UI Designer on implementation questions
- QA/Testers validate features against acceptance criteria
- DevOps Engineer monitors CI/CD health and assists with deployment issues
- Project Manager tracks progress and escalates blockers

**During Release:**
- QA Lead provides final sign-off on quality
- DevOps Engineer executes deployment and monitors systems
- Project Manager coordinates stakeholder communication
- Product Manager validates business outcomes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

