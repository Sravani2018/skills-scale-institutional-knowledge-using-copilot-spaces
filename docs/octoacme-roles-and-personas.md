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

## Release Manager

### Role Summary
Release Managers own release readiness and coordinate approved deployments and stakeholder communication. This role may be assigned to a Project Manager or another designated team member for smaller projects.

### Responsibilities
- Maintain the release calendar and coordinate deployment windows
- Confirm that acceptance criteria, CI, security scans, and smoke tests are complete
- Coordinate approvals, rollback plans, release notes, and post-deployment verification
- Communicate release timing and status to stakeholders and support teams

### Goals
- Reduce release risk and deployment surprises
- Improve predictability, traceability, and operational readiness

### Decision Rights
- Recommend go/no-go decisions based on readiness evidence
- Escalate unresolved release blockers to the Project Manager or Sponsor

### Typical Communication
- Release readiness reviews with QA, Developers, and the Project Manager
- Deployment announcements and post-release status updates

### Interactions with Existing Roles
- Works with **Developers** and **QA/Testing** to verify implementation and test readiness.
- Works with the **Project Manager** on schedules, risk tracking, and escalation.
- Provides **Product Managers** and **Stakeholders** with release scope and status information.

---

## Support / Operations Representative

### Role Summary
Support and Operations Representatives ensure that operational needs and production experience inform project decisions. They provide triage coverage and a handoff between delivery and production support.

### Responsibilities
- Review operational readiness, monitoring, runbooks, and support coverage
- Validate that known issues and troubleshooting guidance are documented
- Triage production incidents and communicate impact and status
- Share recurring customer issues and operational feedback with delivery teams

### Goals
- Shorten time to detect and resolve production issues
- Improve operational readiness and customer support continuity

### Decision Rights
- Define support readiness recommendations and triage priorities
- Recommend operational mitigations or incident escalation

### Typical Communication
- Operational readiness reviews before release
- Production incident updates and post-release feedback

### Interactions with Existing Roles
- Works with **Developers** and **QA/Testing** on observability, testing, known issues, and troubleshooting.
- Works with the **Project Manager** on incident status, operational risks, and delivery impact.
- Works with the **Product Manager** to prioritize customer and operational improvements.

---

## UX/Design Lead

### Role Summary
UX/Design Leads represent customer usability and accessibility throughout planning and delivery. They translate customer and product needs into validated interaction patterns and design specifications.

### Responsibilities
- Define user flows, interaction patterns, and accessibility requirements
- Facilitate or incorporate user research and usability validation
- Resolve design trade-offs and maintain design consistency
- Provide implementable specifications and visual or interaction acceptance criteria

### Goals
- Improve usability and accessibility
- Reduce rework caused by unclear or inconsistent design decisions

### Decision Rights
- Approve design direction within agreed product and technical constraints
- Recommend changes when solutions do not meet usability or accessibility requirements

### Typical Communication
- Design reviews and usability validation sessions
- Product and implementation discussions with acceptance criteria

### Interactions with Existing Roles
- Works with the **Product Manager** to align customer needs, scope, and success metrics.
- Works with **Developers** to communicate constraints, specifications, and implementation trade-offs.
- Works with **QA/Testing** to define usability and accessibility acceptance checks.

---

## Security Lead

### Role Summary
Security Leads identify security requirements, assess project risks, and guide secure implementation and validation. They help teams integrate security decisions into normal delivery work rather than treating security as a late-stage review.

### Responsibilities
- Define applicable security requirements and threat assumptions
- Review architecture, dependencies, vulnerabilities, and mitigations
- Coordinate security testing and incident response requirements
- Track unresolved security risks and their acceptance or remediation

### Goals
- Reduce exposure from implementation, dependencies, and operational decisions
- Improve visibility and accountability for security risks

### Decision Rights
- Recommend whether security risks are acceptable or require remediation
- Escalate material or policy violations to the Sponsor or Security on-call

### Typical Communication
- Threat and risk reviews during planning and major design changes
- Security scan results and incident or remediation updates

### Interactions with Existing Roles
- Works with **Developers** on secure design, implementation, and remediation.
- Works with **QA/Testing** on security testing and verification.
- Works with the **Project Manager** to record risks, owners, and escalation paths.
- Escalates material decisions to the **Sponsor** or appropriate security authority.

---

## Data/Analytics Lead

### Role Summary
Data/Analytics Leads define how project outcomes will be measured and translate evidence into actionable recommendations. They help ensure that delivery work includes reliable instrumentation and reporting.

### Responsibilities
- Define metrics, measurement plans, and data quality expectations
- Coordinate event, telemetry, or reporting instrumentation
- Analyze experiments and post-release outcomes
- Recommend backlog or process adjustments based on evidence

### Goals
- Make outcomes measurable and comparable
- Improve prioritization and decision quality through reliable data

### Decision Rights
- Define measurement methods and validate metric interpretation
- Recommend whether an outcome is sufficiently supported by the available evidence

### Typical Communication
- Metric and instrumentation reviews during planning
- Analysis summaries and experiment or release outcome reports

### Interactions with Existing Roles
- Works with the **Product Manager** to align metrics with customer and business goals.
- Works with **Developers** to implement instrumentation and data quality controls.
- Works with the **Project Manager** on reporting, dependencies, and evidence-based status updates.

---

## Stakeholder/Decision Owner

### Role Summary
Stakeholder/Decision Owners provide timely business decisions, confirm approvals, and resolve priority or scope conflicts. This role includes Sponsors and named stakeholders who have decision authority for a project outcome.

### Responsibilities
- Define or confirm business constraints, priority, and success expectations
- Approve major scope, funding, schedule, or risk decisions
- Remove organizational impediments and resolve cross-team conflicts
- Provide sponsor-level direction when delivery risks exceed team authority

### Goals
- Reduce delayed decisions and ambiguous ownership
- Keep scope, funding, and outcomes aligned with organizational priorities

### Decision Rights
- Make or delegate decisions within their assigned authority
- Confirm approvals and accept or reject material risks presented by project leaders

### Typical Communication
- Milestone reviews and sponsor updates
- Decision requests with options, impacts, and recommendations

### Interactions with Existing Roles
- Works with the **Product Manager** on product value, prioritization, and trade-offs.
- Works with the **Project Manager** on schedules, risks, dependencies, and escalation.
- Provides direction to delivery teams through documented decisions and acceptance of outcomes.
- Coordinates with **Stakeholders** and existing leadership forums when broader alignment is needed.

---

## Role Selection and Accountability

Not every role is required to be a dedicated person on every project. The Project Manager and team should assign the roles needed for the project's size and risk, and document named owners in the project plan.

- Core personas such as Developers, Product Managers, and Project Managers should be identified for every project.
- QA/Testing responsibilities should be assigned when formal or release-specific validation is needed.
- Release Manager, Support/Operations, UX/Design, Security, and Data/Analytics roles may be dedicated, shared, or assigned to another qualified team member based on project scope and risk.
- Stakeholder/Decision Owners should be named whenever decisions or approvals are required outside the delivery team.
- Multiple personas may be assigned to one person, but one owner should remain accountable for each release-critical decision or activity.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

