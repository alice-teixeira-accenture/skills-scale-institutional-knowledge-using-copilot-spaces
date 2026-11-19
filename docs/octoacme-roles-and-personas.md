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

### Interactions with Other Roles
- Work with Product Managers to clarify desired outcomes and acceptance criteria.
- Coordinate with Project Managers on delivery commitments and dependencies.
- Partner with QA, UX, Security, and Data roles on quality, usability, security, and measurement.

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

### Interactions with Other Roles
- Align with Project Managers on scope, schedule, and trade-offs.
- Work with UX, Business Analysis, and Data roles to refine problems and success measures.
- Set priorities and acceptance direction for Developers and QA.

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

### Interactions with Other Roles
- Partner with Product Managers on priorities and scope decisions.
- Coordinate delivery dependencies with Developers and specialist roles.
- Track quality, security, operations, and release risks and escalate unresolved impacts.

---

## Release Managers

### Role Summary
Release Managers own release readiness and coordinate the deployment process across teams.

### Responsibilities
- Maintain the release plan and deployment calendar
- Confirm release prerequisites, rollback plans, and post-deployment checks
- Coordinate deployments across environments and stakeholder groups
- Communicate release status, changes, and incidents

### Goals
- Deliver releases safely and predictably
- Reduce deployment failures and recovery time
- Improve stakeholder and support readiness

### Typical Communication
- Release readiness reviews
- Deployment coordination calls
- Release notes and stakeholder announcements

### Accountability and Interactions
- Project Managers provide schedules and track release dependencies.
- Developers provide candidate builds, runbooks, and rollback changes.
- QA leads confirm validation and quality gates.
- Operations and Support leads prepare for production and incident handoffs.
- Security and Compliance leads approve or advise on applicable release controls.

---

## QA Leads / Quality Managers

### Role Summary
QA Leads own test strategy, acceptance quality, defect prioritization, and quality gates.

### Responsibilities
- Define test strategy and quality criteria
- Coordinate manual and automated validation
- Prioritize and track defects
- Advise teams on release readiness and residual quality risk

### Goals
- Prevent defects and improve delivery confidence
- Ensure acceptance criteria are testable and verified
- Maintain effective coverage and observability

### Typical Communication
- Test planning and quality-risk reviews
- Defect triage
- Release go/no-go or readiness discussions

### Accountability and Interactions
- Work with Product Managers to clarify acceptance criteria.
- Partner with Developers on testability, defects, and test automation.
- Advise Project Managers on quality risks, blocked tests, and release readiness.
- Collaborate with Security and UX roles on relevant compliance, security, and usability validation.

---

## UX / Design Leads

### Role Summary
UX and Design Leads represent customer needs, accessibility, and usability throughout planning and delivery.

### Responsibilities
- Facilitate discovery and translate user needs into designs
- Define interaction patterns and accessibility expectations
- Validate concepts and implementations with users and stakeholders
- Align design work with the project backlog and delivery constraints

### Goals
- Improve usability and customer outcomes
- Maintain consistent, accessible experiences
- Resolve design uncertainty early

### Typical Communication
- Discovery and design workshops
- Design reviews and usability validation
- Handoff documentation and critique sessions

### Accountability and Interactions
- Align with Product Managers on problem statements and success measures.
- Work with Developers on feasible implementation and design trade-offs.
- Coordinate with QA Leads on usability and acceptance experience.
- Present designs and findings to Stakeholders for feedback and decisions.

---

## Business Analysts / Requirements Leads

### Role Summary
Business Analysts clarify requirements, process impacts, and data needs so teams build the intended solution.

### Responsibilities
- Elicit and document business, process, and reporting requirements
- Analyze dependencies, edge cases, and stakeholder impacts
- Maintain traceability between needs, backlog items, and acceptance criteria
- Facilitate requirement decisions and change discussions

### Goals
- Reduce requirement ambiguity and rework
- Improve alignment across business and delivery stakeholders
- Make scope impacts visible and actionable

### Typical Communication
- Requirements workshops
- Process and data analysis reviews
- Backlog refinement and change-control discussions

### Accountability and Interactions
- Partner with Product Managers on prioritization and outcome clarity.
- Resolve detailed needs with Stakeholders and subject-matter experts.
- Provide Developers with clear specifications and process context.
- Help Project Managers identify scope, dependency, and change risks.

---

## Operations / Support Leads

### Role Summary
Operations and Support Leads ensure solutions are supportable and prepared for production use.

### Responsibilities
- Define operational readiness, monitoring, and support requirements
- Maintain runbooks, escalation paths, and known-issue documentation
- Support release handoffs and incident response
- Share operational feedback and recurring support trends with delivery teams

### Goals
- Improve availability and supportability
- Reduce incident impact and resolution time
- Enable smooth transitions from delivery to operations

### Typical Communication
- Operational readiness reviews
- Support handoffs and incident retrospectives
- Support trend and on-call reporting

### Accountability and Interactions
- Coordinate with Release Managers on deployment, rollback, and production handoffs.
- Work with Developers on observability, diagnostics, and runbooks.
- Raise operational risks to Project Managers and provide incident updates to Stakeholders.
- Share customer and support feedback with Product Managers.

---

## Security / Compliance Leads

### Role Summary
Security and Compliance Leads define and verify applicable controls and advise teams on risk treatment.

### Responsibilities
- Define security and compliance requirements
- Review designs and implementations for risk
- Coordinate security testing and control evidence
- Recommend mitigations, exceptions, or escalations

### Goals
- Reduce security and compliance risk
- Embed controls into routine delivery
- Maintain clear evidence and accountability for residual risk

### Typical Communication
- Threat and compliance reviews
- Security testing and remediation planning
- Risk and exception escalations

### Accountability and Interactions
- Advise Developers on secure implementation and remediation.
- Work with QA Leads on security validation and evidence.
- Coordinate applicable release gates with Release Managers.
- Record decisions and risk status with Project Managers and escalate unacceptable residual risk through established paths.

---

## Data / Analytics Leads

### Role Summary
Data and Analytics Leads define measurement plans and verify that teams can assess outcomes and operational performance.

### Responsibilities
- Define metrics, event requirements, and reporting plans
- Review data quality and analytical validity
- Interpret results and recommend product or process adjustments
- Support experiment and success-criteria evaluation

### Goals
- Produce trustworthy, actionable evidence
- Improve outcome and experiment measurement
- Reduce uncertainty in prioritization and release decisions

### Typical Communication
- Measurement planning and dashboard reviews
- Experiment readouts
- Outcome and KPI reviews

### Accountability and Interactions
- Partner with Product Managers on success metrics and experiments.
- Define instrumentation requirements with Developers.
- Validate results for Project Managers and Stakeholders and highlight evidence gaps or data-quality risks.
- Coordinate with UX, Operations, and QA roles when measurement spans design, production, or quality validation.

---

## Selecting Roles for a Project

All projects use the core Developer, Product Manager, and Project Manager roles, with QA and Stakeholder participation as applicable. Release Manager, UX/Design Lead, Business Analyst, Operations/Support Lead, Security/Compliance Lead, and Data/Analytics Lead roles may be assigned directly or shared across projects when the work warrants them. At kickoff, the team should name the accountable person for each role and document shared responsibilities rather than leave ownership implicit.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
