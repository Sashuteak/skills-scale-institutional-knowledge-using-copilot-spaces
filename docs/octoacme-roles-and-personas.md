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
Leads quality assurance strategy, test planning, and validation. Ensures acceptance criteria are testable and quality gates are met before release.

### Responsibilities
- Develop test strategies aligned with project scope
- Define how acceptance criteria will be validated
- Lead manual and automated testing execution
- Identify quality risks and prioritize defects
- Collaborate with developers to improve testability

### Goals
- Ensure features meet acceptance criteria before release
- Reduce production defects through early testing
- Maintain clear quality metrics and visibility

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Daily standup updates on test status
- Blocker escalation when acceptance criteria are not met

### Interactions
- **Developers:** Collaborate on testability, test coverage, and reproducing defects.
- **Product Managers:** Confirm acceptance criteria are complete, testable, and aligned with intended outcomes.
- **Project Managers:** Share test progress, quality risks, and release readiness for project tracking and escalation.
- **Sponsors:** Communicate material quality risks and release confidence when a quality gate affects a decision.

---

## Sponsor/Executive Stakeholder

### Role Summary
The business owner and decision-maker who approves strategy, budget, and go/no-go decisions. Provides business context and priority alignment.

### Responsibilities
- Approve the project charter and major milestones
- Provide business context and strategic alignment
- Make go/no-go decisions at project gates
- Escalate organizational dependencies
- Review release impact and stakeholder communications

### Goals
- Deliver business value on schedule
- Minimize organizational risk
- Ensure strategic alignment with business objectives

### Typical Communication
- Monthly status reviews and milestone or escalation meetings
- Go/no-go decisions and major risk escalations
- Release announcements and stakeholder updates

### Interactions
- **Developers:** Share business context and receive concise updates on delivery constraints or decisions that affect outcomes.
- **Product Managers:** Align strategy, priorities, and success measures; resolve material scope or value trade-offs.
- **Project Managers:** Approve the charter and key decisions, and review schedule, budget, dependencies, and risks.
- **Sponsors:** Align with other executive stakeholders on priorities, decisions, and a consistent message to the organization.

---

## Scrum Master / Delivery Facilitator

### Role Summary
Removes impediments, facilitates ceremonies, and promotes team health and a sustainable delivery cadence.

### Responsibilities
- Facilitate sprint planning, standups, and retrospectives
- Identify blockers and help the team resolve them
- Monitor velocity, capacity, and sprint health
- Coach the team on Agile practices
- Track delivery metrics and continuous-improvement actions

### Goals
- Maintain a sustainable team pace and healthy collaboration
- Reduce cycle time and planning overhead
- Support continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospectives and follow-up on action items
- One-on-one coaching and blocker resolution

### Interactions
- **Developers:** Facilitate team collaboration, surface impediments, and support a sustainable pace without directing technical work.
- **Product Managers:** Coordinate backlog readiness and sprint goals, and surface scope or priority conflicts.
- **Project Managers:** Align delivery cadence, dependencies, and progress metrics while clarifying facilitation and reporting responsibilities.
- **Sponsors:** Escalate systemic impediments or decisions beyond the team's authority through the Project Manager.

---

## Security / Compliance Officer

### Role Summary
Ensures security, compliance, and risk mitigation throughout the project lifecycle.

### Responsibilities
- Review security design and architecture
- Configure and monitor security scanning in CI/CD
- Participate in risk assessment and mitigation planning
- Ensure compliance with regulatory and organizational standards
- Respond to security incidents and vulnerabilities

### Goals
- Prevent vulnerabilities and compliance violations
- Enable secure delivery practices
- Reduce organizational and customer risk exposure

### Typical Communication
- Design reviews and architecture discussions
- Risk register reviews and incident response
- Security scanning results and CI/CD gate participation

### Interactions
- **Developers:** Advise on secure implementation, review findings, and coordinate vulnerability remediation.
- **Product Managers:** Identify security and compliance requirements and explain their impact on scope and priorities.
- **Project Managers:** Record security risks, mitigations, and gate status; follow incident escalation and communication paths.
- **Sponsors:** Escalate material exposure, compliance concerns, and risk acceptance decisions that need executive approval.

---

## Tech Lead / Solutions Architect

### Role Summary
Defines technical direction, reviews design decisions, and ensures technical excellence and scalability.

### Responsibilities
- Lead technical design and architecture decisions
- Review code and designs for scalability and maintainability
- Identify technical risks and propose mitigations
- Guide developers on technical practices
- Evaluate build-versus-buy trade-offs

### Goals
- Deliver scalable, maintainable, and performant solutions
- Reduce technical debt and architectural risk
- Enable knowledge sharing and team growth

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and pull request feedback
- Planning sessions and trade-off discussions

### Interactions
- **Developers:** Provide technical direction, review designs and code, and support knowledge sharing.
- **Product Managers:** Explain feasibility, technical trade-offs, and implications for scope and priorities.
- **Project Managers:** Surface technical risks, estimates, and dependencies for plans, tracking, and escalation.
- **Sponsors:** Explain technical options and their business impact, including material risks and investment trade-offs.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
