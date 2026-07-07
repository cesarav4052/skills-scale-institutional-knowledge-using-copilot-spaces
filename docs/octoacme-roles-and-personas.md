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

## Quality Assurance Lead

### Role Summary
QA Leads define and execute quality strategies, establish testing standards, and own acceptance validation. They partner with Product and Development teams to ensure features meet quality gates before release.

### Responsibilities
- Define testing strategy (unit, integration, E2E, security, performance)
- Establish quality metrics and acceptance criteria frameworks
- Design and maintain test automation and QA infrastructure
- Validate acceptance criteria before feature sign-off
- Triage and prioritize bug reports
- Coordinate production smoke testing and rollback procedures

### Goals
- Reduce production defects and regressions
- Enable fast, confident deployments
- Balance speed with quality standards

### Interaction with Other Roles
- **With Developers**: Collaborate on test coverage targets and automation strategies
- **With Product Managers**: Clarify acceptance criteria and edge cases
- **With Project Managers**: Report quality metrics and risks in weekly syncs
- **With DevOps**: Coordinate test automation in CI/CD pipelines

### Typical Communication
- Quality review gates in sprint planning and execution
- Test reports and automation updates
- Bug triage and release readiness assessments

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide system design, technical strategy, and architectural decisions. They ensure solutions are scalable, maintainable, and aligned with long-term technical vision.

### Responsibilities
- Lead technical design discussions and architectural reviews
- Mentor developers on design patterns and best practices
- Identify technical risks and propose mitigation strategies
- Advocate for technical debt paydown and refactoring
- Oversee integration points and cross-system dependencies
- Participate in sprint planning to estimate and scope technical work

### Goals
- Build scalable, maintainable systems
- Reduce technical complexity and future rework
- Enable team velocity through good architecture

### Interaction with Other Roles
- **With Developers**: Review designs, provide technical guidance in code review
- **With Product Managers**: Advise on feasibility and technical trade-offs
- **With Project Managers**: Flag technical risks and dependency impacts early
- **With DevOps**: Align on deployment architecture and infrastructure needs

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback on design decisions
- Architecture documentation and ADRs (Architecture Decision Records)

---

## Stakeholder / Sponsor

### Role Summary
Sponsors provide business context, secure resources, and make key go/no-go decisions. They represent business priorities and ensure alignment between projects and strategic goals.

### Responsibilities
- Define business goals and success metrics
- Approve project initiation and allocation of resources
- Make trade-off decisions on scope, timeline, and quality
- Escalate or remove organizational blockers
- Communicate project status to executive leadership
- Review and approve releases for customer-facing impact

### Goals
- Ensure projects deliver business value
- Remove organizational barriers to execution
- Maintain alignment with strategic priorities

### Interaction with Other Roles
- **With Project Managers**: Receive weekly status updates and escalations
- **With Product Managers**: Review roadmap alignment and business outcomes
- **With Developers**: Provide context in kickoff meetings, not day-to-day

### Typical Communication
- Monthly stakeholder updates and business reviews
- Approval gates at project initiation and release
- Escalation channels for org blockers

---

## DevOps / Infrastructure Lead

### Role Summary
DevOps engineers design and maintain deployment pipelines, infrastructure, and production support systems. They enable reliable, repeatable deployments and operational excellence.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage infrastructure-as-code and deployment automation
- Design monitoring, logging, and alerting
- Support incident response and rollback procedures
- Manage infrastructure scaling and performance
- Document runbooks and operational procedures

### Goals
- Enable fast, low-risk deployments
- Minimize time-to-recovery from incidents
- Maintain high system reliability and performance

### Interaction with Other Roles
- **With Developers**: Collaborate on test automation and deployment requirements
- **With QA**: Integrate security and performance tests into pipelines
- **With Project Managers**: Report on deployment readiness and infrastructure risks

### Typical Communication
- Pipeline status and deployment planning
- Infrastructure impact assessments for features
- Incident post-mortems and operational metrics

---

## Security Lead

### Role Summary
Security leads ensure projects meet compliance requirements, embed security practices, and minimize risk exposure. They review designs, code, and processes for vulnerabilities.

### Responsibilities
- Review designs and threat models for security risks
- Define and enforce security standards and compliance requirements
- Conduct or coordinate security testing and scanning
- Triage and prioritize security findings
- Advise on incident response for security events
- Support audit and compliance activities

### Goals
- Prevent security breaches and data exposure
- Maintain compliance with regulations and policies
- Embed security into development practices

### Interaction with Other Roles
- **With Developers**: Review PRs for security concerns, mentor on secure coding
- **With Product Managers**: Advise on features with security or privacy impact
- **With DevOps**: Ensure security scanning and secrets management in pipelines
- **With Project Managers**: Escalate security risks and compliance gaps

### Typical Communication
- Security design reviews and threat assessments
- Vulnerability scanning results and remediation tracking
- Security training and best practice guidance

---

## UX / Design Lead

### Role Summary
Design leads ensure products are usable, accessible, and delightful. They collaborate with product and engineering to translate customer needs into intuitive experiences.

### Responsibilities
- Conduct user research and synthesize insights
- Create wireframes, prototypes, and design specifications
- Ensure accessibility and usability standards are met
- Conduct design reviews and usability testing
- Advocate for user needs and pain points
- Partner with developers on implementation fidelity

### Goals
- Create products customers love to use
- Reduce support load through intuitive design
- Maintain consistent brand and UX patterns

### Interaction with Other Roles
- **With Product Managers**: Collaborate on user research and feature definitions
- **With Developers**: Review implementation against design specs, iterate on details
- **With Project Managers**: Communicate design milestones and dependencies

### Typical Communication
- Design kickoffs and spec reviews
- Usability testing results and design iterations
- Accessibility compliance reports

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and coach teams on agile practices. They enable continuous improvement and healthy team dynamics.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Help teams maintain sustainable pace and prevent burnout
- Identify and escalate organizational blockers
- Coach teams on agile practices and self-organization
- Maintain visibility into sprint progress and risks
- Foster psychological safety and open communication

### Goals
- Enable self-organizing teams
- Maintain consistent delivery velocity
- Continuously improve team processes

### Interaction with Other Roles
- **With Developers & All Delivery Team**: Facilitate daily collaboration and ceremonies
- **With Project Managers**: Escalate blockers and risks identified in standups
- **With Team**: Coach on agile principles and retrospective insights

### Typical Communication
- Facilitation of all agile ceremonies
- Blocker escalation and removal tracking
- Process improvement recommendations from retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-persona interactions are documented to help teams understand collaboration patterns.
