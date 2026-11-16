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

## QA/Test Leads

### Role Summary
QA/Test Leads own the test strategy and coordinate validation that delivered work meets acceptance criteria, the Definition of Done, and relevant quality expectations.

### Responsibilities
- Define test approaches, coverage expectations, and entry/exit criteria
- Coordinate functional, integration, regression, accessibility, and exploratory testing
- Track defects and quality risks through release readiness
- Confirm that acceptance criteria are testable and evidence is recorded
- Recommend readiness, mitigation, or delay when quality risks remain

### Interactions with Existing Roles
- Work with Product Managers and Business Analysts to refine acceptance criteria and examples
- Partner with Developers on testability, automation, defect triage, and fixes
- Report quality risks and readiness recommendations to Project Managers for the release plan and risk register

### Goals
- Detect important defects before release
- Provide transparent evidence for acceptance and release decisions
- Improve product quality without creating avoidable delivery delays

### Typical Communication
- Test plans, quality reports, and defect dashboards
- Readiness reviews with Developers, Product Managers, and Project Managers
- Risk-register updates and retrospective actions

---

## UX/UI Designers or Researchers

### Role Summary
UX/UI Designers or Researchers represent user needs through research, journeys, prototypes, visual designs, and usability validation.

### Responsibilities
- Plan and conduct user research and usability validation
- Document user journeys, workflows, interaction requirements, and design decisions
- Create prototypes and specifications that support implementation
- Identify accessibility and usability risks early
- Validate shipped experiences against intended user outcomes

### Interactions with Existing Roles
- Collaborate with Product Managers during discovery to connect user evidence to priorities
- Work with Business Analysts to turn user needs into clear requirements and acceptance criteria
- Partner with Developers and QA/Test Leads to make designs feasible, accessible, and testable
- Keep Project Managers informed of research dependencies and design milestones

### Goals
- Improve usability, accessibility, and customer outcomes
- Reduce rework by validating important assumptions early
- Give delivery teams a shared, testable understanding of the intended experience

### Typical Communication
- Research findings, journey maps, prototypes, and design specifications
- Design reviews and usability-test readouts
- Handoff notes and acceptance-criteria examples

---

## Business Analysts

### Role Summary
Business Analysts translate stakeholder needs into clear, traceable requirements and decisions that the delivery team can understand, estimate, and validate.

### Responsibilities
- Elicit and document business needs, constraints, and process impacts
- Break outcomes into requirements, user stories, and acceptance criteria
- Maintain traceability from goals through backlog items and delivered outcomes
- Identify ambiguity, assumptions, and requirement dependencies
- Record decisions and confirm shared understanding with stakeholders

### Interactions with Existing Roles
- Work with Product Managers on scope, priorities, and measurable outcomes
- Collaborate with UX/UI Designers or Researchers to incorporate user evidence
- Clarify requirements with Developers and QA/Test Leads so work is feasible and testable
- Provide Project Managers with estimates, dependencies, and decision impacts for planning

### Goals
- Reduce ambiguity and requirement-related rework
- Make scope and acceptance decisions visible and traceable
- Ensure stakeholder needs are represented in delivery artifacts

### Typical Communication
- Requirements briefs, user stories, process maps, and acceptance criteria
- Refinement sessions and decision logs
- Traceability reviews with Product Managers, Developers, and QA/Test Leads

---

## Technical Leads or Architects

### Role Summary
Technical Leads or Architects guide technical design, non-functional requirements, dependencies, and engineering trade-offs while keeping implementation aligned with product outcomes.

### Responsibilities
- Define or review solution architecture and technical standards
- Identify non-functional requirements such as performance, reliability, and scalability
- Surface technical dependencies, constraints, and implementation risks
- Facilitate engineering trade-offs and document significant decisions
- Support Developers with design guidance and unblock complex technical work

### Interactions with Existing Roles
- Partner with Developers on design, implementation sequencing, and code quality
- Work with Product Managers and Business Analysts to assess feasibility and trade-offs
- Coordinate with Project Managers on dependencies, risk mitigation, and milestone impacts
- Consult Security/Privacy Representatives and Release/Operations Leads on controls and operability

### Goals
- Deliver solutions that are secure, maintainable, and fit for purpose
- Make technical risks and trade-offs visible early
- Reduce architectural rework and fragile dependencies

### Typical Communication
- Architecture decision records, diagrams, and technical design reviews
- Dependency and risk updates in planning and status meetings
- Engineering guidance in backlog items and code reviews

---

## Release/Operations or Site Reliability Leads

### Role Summary
Release/Operations or Site Reliability Leads own deployment readiness, observability, rollback planning, and post-release verification.

### Responsibilities
- Define deployment, monitoring, alerting, and rollback requirements
- Coordinate environment readiness and release runbooks
- Verify operational acceptance criteria and post-deployment health
- Prepare incident response and escalation paths for release risks
- Capture operational learnings and follow-up actions after release

### Interactions with Existing Roles
- Work with Developers and Technical Leads on automation, observability, and operability
- Coordinate with QA/Test Leads on smoke tests, validation evidence, and release gates
- Partner with Project Managers on release plans, communications, and risk decisions
- Provide Product Managers with production-impact information for rollout decisions

### Goals
- Release changes safely and repeatably
- Detect and mitigate production issues quickly
- Maintain reliable service operations and actionable telemetry

### Typical Communication
- Release checklists, runbooks, dashboards, and incident channels
- Go/no-go reviews and post-release verification updates
- Incident reports and retrospective action tracking

---

## Customer/Support or Service Representatives

### Role Summary
Customer/Support or Service Representatives bring customer impact, support trends, and operational feedback into planning and release decisions.

### Responsibilities
- Share recurring customer issues, support trends, and service-impact evidence
- Identify customer-facing requirements and communication needs
- Help validate customer scenarios and rollout readiness
- Coordinate support enablement, FAQs, and escalation coverage
- Report post-release feedback and unresolved customer impact

### Interactions with Existing Roles
- Collaborate with Product Managers to prioritize customer problems and measure outcomes
- Work with UX/UI Designers or Researchers to explain real-world user needs
- Partner with Project Managers on rollout communications, stakeholder updates, and escalations
- Coordinate with QA/Test Leads and Release/Operations Leads on customer scenarios and incident response

### Goals
- Improve customer outcomes and support readiness
- Ensure customer impact informs scope and release decisions
- Shorten the path from reported issue to an actionable product or service response

### Typical Communication
- Support trend summaries, customer-impact assessments, and release FAQs
- Go-live readiness reviews and escalation channels
- Post-release feedback reports

---

## Security/Privacy Representatives

### Role Summary
Security/Privacy Representatives advise on security, privacy, compliance, threat assessment, and required controls throughout the project lifecycle.

### Responsibilities
- Identify security, privacy, and compliance requirements
- Perform or coordinate threat modeling and risk assessments
- Define required controls, approvals, and evidence
- Review designs, implementations, tests, and release plans for material risks
- Track findings and confirm remediation or documented acceptance

### Interactions with Existing Roles
- Partner with Technical Leads or Architects and Developers on secure design and implementation
- Work with QA/Test Leads to include security and privacy validation in the test approach
- Coordinate with Project Managers on risk-register entries, deadlines, and escalations
- Advise Product Managers and Business Analysts on requirements and customer trust implications

### Goals
- Reduce security and privacy risk before release
- Make compliance obligations and decisions traceable
- Enable delivery with proportionate, practical controls

### Typical Communication
- Threat models, risk assessments, security reviews, and approval records
- Findings tracked in the backlog and risk register
- Release gates and incident escalation notices

---

## Executive Sponsors or Decision Makers

### Role Summary
Executive Sponsors or Decision Makers provide strategic sponsorship, resolve escalated priority or resource conflicts, and confirm major decisions that exceed the delivery team's authority.

### Responsibilities
- Confirm the initiative's strategic purpose, sponsorship, and success measures
- Resolve escalated scope, priority, budget, or resource conflicts
- Make or approve major decisions when trade-offs cross team boundaries
- Review material risks, milestones, and outcome measures
- Remove organizational blockers and support stakeholder alignment

### Interactions with Existing Roles
- Receive status, risk, and decision updates from Project Managers
- Work with Product Managers on strategic outcomes, priority conflicts, and value trade-offs
- Rely on Technical Leads, QA/Test Leads, Security/Privacy Representatives, and Release/Operations Leads for specialist risk input
- Confirm escalated decisions while leaving day-to-day execution with the delivery team

### Goals
- Keep projects aligned with strategy and accountable outcomes
- Resolve escalations quickly and transparently
- Ensure resources and decisions support responsible delivery

### Typical Communication
- Executive status summaries, decision papers, and milestone reviews
- Escalation meetings for unresolved risks or conflicts
- Outcome and benefits reviews after release

---

## Persona Use Across the Project Lifecycle

Use the personas to assign explicit accountability for each stage and artifact. A single person may hold multiple roles in a small team, but each responsibility and decision right should still have a named owner.

| Lifecycle stage | Typical ownership and handoffs | Key artifacts |
| --- | --- | --- |
| Initiation | Executive Sponsor confirms purpose; Product Manager defines outcomes; Project Manager establishes coordination; UX/UI and Customer/Support Representatives provide user and service context. | Project Charter / One-pager, stakeholder map |
| Planning | Product Manager and Business Analyst refine scope; Technical Lead assesses feasibility; QA/Test Lead defines validation; Security/Privacy Representative identifies controls; Release/Operations Lead identifies deployment needs; Project Manager sequences dependencies. | Roadmap, backlog, acceptance criteria, risk register, release plan |
| Execution | Developers implement; UX/UI validates the experience; Business Analyst clarifies requirements; Technical Lead resolves design trade-offs; QA/Test Lead coordinates validation; Project Manager tracks delivery and risks. | PRs, design and decision records, test evidence, status updates |
| Release | QA/Test Lead recommends quality readiness; Security/Privacy and Release/Operations Leads confirm their gates; Project Manager coordinates the go/no-go decision and communications; Customer/Support Representative prepares customer readiness; Product Manager confirms value and rollout intent. | Release checklist, runbook, release notes, rollout communications |
| Retrospective | Project Manager facilitates; all delivery personas contribute evidence and actions; Executive Sponsor reviews material outcomes or escalations. | Retrospective notes, action items, outcome measures |

These assignments are a starting point, not a required organizational structure. Projects should name the accountable person for each responsibility, document handoffs in the project plan or backlog, and escalate unresolved ownership conflicts through the Project Manager and Product Manager.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
