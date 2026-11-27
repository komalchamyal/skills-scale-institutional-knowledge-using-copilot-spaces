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

### Interactions
- Work with Product Managers to clarify outcomes and acceptance criteria.
- Coordinate with Project Managers on estimates, dependencies, and delivery risks.
- Partner with QA/Testing, Release, Security, and Operations roles on quality, release readiness, and production support.

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

### Interactions
- Align with Project Managers on scope, schedule, dependencies, and stakeholder decisions.
- Work with Developers to refine feasible solutions and with QA/Testing to validate outcomes.
- Incorporate input from Business Analysts, UX, Security, Operations, and customer advocates to balance value, usability, risk, and supportability.

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

### Interactions
- Partner with Product Managers on priorities and outcome trade-offs.
- Coordinate Developers and QA/Testing around capacity, milestones, dependencies, and quality gates.
- Work with Release, Security, Operations, UX, and stakeholder representatives to plan launches, communicate risks, and resolve cross-functional decisions.

---

## Release Manager

### Role Summary
Release Managers own release readiness and coordinate controlled delivery of approved changes to production.

### Responsibilities
- Define release scope, schedule, and deployment plan
- Coordinate go/no-go decisions and rollback readiness
- Verify required approvals, release notes, smoke tests, and monitoring
- Facilitate release communication and post-deployment verification

### Goals
- Reduce deployment risk
- Maintain predictable, observable releases
- Ensure stakeholders and support teams are ready for changes

### Typical Communication
- Release readiness reviews
- Deployment plans and go/no-go updates
- Release notes and incident escalations

### Interactions
- Work with Developers on deployment packages, known issues, and fixes.
- Coordinate with QA/Testing on acceptance evidence and smoke-test results.
- Align with Project Managers on schedule and stakeholder communication and with Operations on runbooks, monitoring, and support readiness.

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define quality strategy and lead validation of whether delivered work meets acceptance criteria and quality standards.

### Responsibilities
- Define test scope and testing strategy
- Plan and coordinate automated and manual validation
- Verify acceptance criteria and report quality risks
- Support defect triage and release-quality decisions

### Goals
- Prevent defects from reaching production
- Provide clear evidence of readiness
- Improve test coverage and feedback speed

### Typical Communication
- Test plans and quality reports
- Sprint reviews and defect triage
- Quality gate and release-readiness updates

### Interactions
- Collaborate with Developers on testability and defect resolution.
- Clarify acceptance criteria with Product Managers and UX researchers.
- Provide quality and delivery-risk updates to Project Managers and Release Managers.

---

## Business Analyst / Requirements Analyst

### Role Summary
Business Analysts turn stakeholder needs into clear, traceable requirements and ensure delivery remains aligned to business outcomes.

### Responsibilities
- Elicit and analyze stakeholder needs
- Define and refine functional and process requirements
- Maintain traceability from outcomes to backlog items
- Support clarification and impact analysis

### Goals
- Reduce ambiguity and requirement churn
- Improve alignment between business need and delivered scope
- Make decisions and trade-offs explicit

### Typical Communication
- Workshops and requirement reviews
- Process maps and decision logs
- Refined backlog items and acceptance criteria

### Interactions
- Work with Product Managers to refine outcomes and prioritization.
- Support Developers and QA/Testing with clear requirements, constraints, and test scenarios.
- Engage stakeholder representatives to resolve needs and confirm decisions.

---

## UX Designer / Researcher

### Role Summary
UX Designers and Researchers represent users and ensure proposed solutions are understandable, usable, accessible, and informed by evidence.

### Responsibilities
- Conduct or synthesize user research
- Produce interaction designs, prototypes, and usability guidance
- Define usability and accessibility expectations
- Validate designs and delivered experiences with users

### Goals
- Improve usability and customer value
- Reduce design rework
- Ensure evidence informs product decisions

### Typical Communication
- Research findings and prototypes
- Design reviews and usability testing
- Usability and accessibility acceptance criteria

### Interactions
- Partner with Product Managers to understand customer needs and prioritize improvements.
- Collaborate with Developers on implementation feasibility and with QA/Testing on usability and accessibility validation.
- Present customer evidence to Project Managers and stakeholder representatives.

---

## Security Lead

### Role Summary
Security Leads establish security expectations, identify risks, and coordinate security review and incident response for project work.

### Responsibilities
- Define applicable security requirements and threat models
- Review high-risk designs and changes
- Coordinate vulnerability remediation and security incident response
- Track security risks and required controls

### Goals
- Reduce security exposure
- Embed security practices into delivery
- Improve readiness for incidents and compliance requirements

### Typical Communication
- Threat models and security reviews
- Risk assessments and remediation plans
- Security incident updates

### Interactions
- Advise Developers on secure design and remediation.
- Coordinate security testing with QA/Testing.
- Escalate material risk through Project Managers and work with Operations on incident response and monitoring.

---

## Support / Operations Lead

### Role Summary
Support and Operations Leads represent operational readiness and ensure the team can operate, support, and learn from released services.

### Responsibilities
- Plan runbooks, monitoring, support coverage, and operational readiness
- Coordinate incident response and escalation
- Track production feedback and recurring operational issues
- Feed operational learning into backlog and release planning

### Goals
- Improve reliability and supportability
- Shorten incident detection and recovery
- Turn production evidence into continuous improvement

### Typical Communication
- Runbooks and operational readiness reviews
- Incident status and post-incident reviews
- Operational metrics and support feedback

### Interactions
- Work with Release Managers and Developers on deployment readiness and runbooks.
- Share operational impact and customer feedback with Product Managers.
- Keep Project Managers informed of risks, incidents, dependencies, and stakeholder impacts.

---

## Stakeholder Representative / Customer Advocate

### Role Summary
Stakeholder Representatives and Customer Advocates provide relevant stakeholder or customer context, raise concerns, and confirm whether outcomes address the intended need.

### Responsibilities
- Represent stakeholder or customer priorities and constraints
- Review outcomes and provide timely feedback
- Confirm decisions and communicate changes to represented groups
- Surface adoption, business, or customer-impact risks

### Goals
- Improve alignment and decision quality
- Ensure delivered outcomes are understandable and useful
- Increase stakeholder buy-in and adoption

### Typical Communication
- Stakeholder updates and review sessions
- Feedback summaries and decision records
- Acceptance or adoption validation

### Interactions
- Work with Product Managers to validate problems, priorities, and outcomes.
- Coordinate approvals and communication with Project Managers.
- Provide context to Business Analysts and UX representatives and clarify decisions for the delivery team.

---

## Selecting Personas

Teams should add personas based on project scope, risk, compliance, customer impact, and operational needs. A persona can be assigned to an individual or shared across people, and small projects may combine responsibilities. Ownership boundaries and final decision-makers should remain explicit even when roles are combined.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
