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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute quality assurance strategies, validate acceptance criteria, and ensure features meet quality standards before release.

### Responsibilities
- Draft and maintain test plans aligned with feature acceptance criteria
- Coordinate unit, integration, and end-to-end testing efforts
- Validate features in staging and production-like environments
- Identify and triage defects; collaborate on root cause analysis
- Ensure security and performance testing are included in release gates

### Goals
- Catch defects early and prevent production incidents
- Maintain test coverage and reduce manual regression testing
- Enable confident, rapid releases

### Typical Communication
- Weekly QA status in team standups
- Test plan reviews during sprint planning
- Defect reports and regression test results
- Pre-release smoke test sign-offs

### Interaction with Other Roles
- Works closely with **Developers** to define testability requirements and validate implementations
- Collaborates with **Product Managers** to understand acceptance criteria and validate feature completeness
- Partners with **Project Managers** to track quality metrics and report on release readiness
- Advises **Security Lead** on security and performance testing inclusion

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve investments, and ensure project alignment with organizational strategy and customer needs.

### Responsibilities
- Clarify business requirements and success criteria
- Approve project initiation, scope changes, and budget allocation
- Review progress against milestones and success metrics
- Escalate organizational blockers or priority shifts
- Validate that delivered outcomes meet business objectives

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between engineering and business priorities
- Reduce rework and scope creep through clear approval gates

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Kick-off and decision gate meetings
- Escalation communications for risks and scope changes
- Release announcements and impact assessment

### Interaction with Other Roles
- Provides strategic direction to **Product Leads** and **Product Managers**
- Reviews project charters and release plans with **Project Managers**
- Receives escalated risks and blockers from **Project Managers** at Level 3
- Validates delivered outcomes against business objectives with **Product Managers**

---

## Product Lead

### Role Summary
Product Leads own the strategic vision for a product area and guide cross-functional teams on prioritization, trade-offs, and long-term direction. They are distinct from Product Managers and focus on strategic alignment and escalation.

### Responsibilities
- Define product vision and strategic roadmap
- Mentor and guide Product Managers on prioritization
- Escalate Level 2 risks and dependency issues
- Align product strategy with organizational goals
- Review roadmap against customer and business outcomes

### Goals
- Ensure consistent product direction and quality
- Enable teams to make prioritization decisions aligned with strategy
- Accelerate cross-team collaboration and dependency resolution

### Typical Communication
- Bi-weekly syncs with PM and project leadership
- Strategic roadmap and vision updates
- Level 2 escalation resolution
- Quarterly product strategy reviews

### Interaction with Other Roles
- Mentors **Product Managers** on strategy and prioritization
- Escalates Level 2 risks from **Project Managers** to **Sponsors**
- Guides **Developers** and **QA/Testing Leads** on strategic priorities
- Resolves cross-team dependencies with other Product Leads

---

## Security Lead

### Role Summary
Security Leads ensure projects meet security and compliance requirements, manage vulnerability assessments, and guide incident response.

### Responsibilities
- Review security requirements and threat models for new features
- Ensure security scanning is integrated into CI/CD pipelines
- Conduct or oversee security code reviews and penetration testing
- Manage security incident response and post-incident reviews
- Advise on compliance and data protection requirements

### Goals
- Prevent security vulnerabilities from reaching production
- Reduce incident response time and blast radius
- Maintain customer trust and compliance posture

### Typical Communication
- Security requirements and architecture reviews during planning
- Automated security scan results and remediation tracking
- Incident response coordination and escalation
- Security-focused retrospective action items

### Interaction with Other Roles
- Partners with **Developers** on secure coding practices and code reviews
- Advises **QA/Testing Leads** on security and performance testing
- Collaborates with **Project Managers** on security-related risks and compliance
- Works with **Stakeholders** on security incidents and compliance matters

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
