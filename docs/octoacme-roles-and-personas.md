# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interaction with Other Roles
- **Technical Lead**: Receive design guidance and code review feedback
- **QA Lead**: Collaborate on test design and acceptance criteria
- **Product Manager**: Clarify requirements and acceptance criteria
- **Security Officer**: Incorporate security guidance into implementation

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interaction with Other Roles
- **Project Manager**: Coordinate on timeline and resource allocation
- **Stakeholders**: Partner on prioritization and business alignment
- **Developers**: Define acceptance criteria and feature specifications
- **QA Lead**: Align on quality standards and acceptance criteria

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interaction with Other Roles
- **Product Manager**: Align on scope, timeline, and resource needs
- **Stakeholders**: Provide status updates and escalate business-impacting issues
- **Scrum Master**: Coordinate on team capacity and impediment removal
- **Technical Lead**: Escalate technical risks and dependencies

---

## Supporting/Cross-Functional Roles

### Stakeholder / Business Owner

#### Role Summary
Stakeholders represent customer, product, and business interests. They provide strategic direction, approve scope trade-offs, and ensure alignment with business objectives.

#### Responsibilities
- Approve project charter and success metrics
- Participate in key decisions (scope, timeline, budget trade-offs)
- Provide business context and customer perspective
- Escalate business-impacting risks and blockers
- Review and sign off on releases and outcomes
- Participate in gate reviews (Initiation, Planning, Release)

#### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with strategic objectives
- Minimize business disruption during delivery
- Maximize ROI on project investment

#### Typical Communication
- Monthly stakeholder updates and gate reviews
- Project charter reviews and approvals
- Escalation of business-critical issues

#### Interaction with Other Roles
- **Product Manager**: Partner on prioritization, success metrics, and value definition
- **Project Manager**: Receive status updates, participate in gate reviews, escalate business risks
- **Developers/Technical Lead**: Provide context on business constraints and dependencies
- **Scrum Master**: Participate in key milestone reviews

---

### Technical Lead / Architect

#### Role Summary
Technical Leads provide architectural guidance, technical risk assessment, and design oversight. They ensure technical decisions align with long-term platform strategy and quality standards.

#### Responsibilities
- Review technical design and architecture proposals
- Identify technical risks, dependencies, and mitigation strategies
- Mentor developers and guide technical decision-making
- Validate technical feasibility and estimate complexity
- Participate in code reviews and design decisions
- Champion best practices (testing, documentation, security)
- Lead technical design reviews and architecture discussions

#### Goals
- Ensure scalable, maintainable, and secure technical solutions
- Reduce technical debt and future rework
- Build team capability and technical excellence
- Align technical decisions with business objectives

#### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Technical risk escalation to Project Manager
- Design documentation and decision logs

#### Interaction with Other Roles
- **Product Manager**: Advise on technical feasibility of features and trade-offs
- **Developers**: Review designs, mentor technical decisions, provide code review feedback
- **Project Manager**: Escalate technical risks, dependencies, and timeline impacts
- **QA Lead**: Collaborate on test strategy, testability, and quality standards
- **Security Officer**: Partner on security architecture and threat modeling
- **Scrum Master**: Advise on technical impediments and process improvements

---

### QA / Testing Lead

#### Role Summary
QA Leads define quality standards, test strategies, and acceptance criteria validation. They ensure features meet quality and usability requirements before release.

#### Responsibilities
- Define testing strategy and quality acceptance criteria
- Design and maintain automated and manual test suites
- Validate acceptance criteria and feature completeness
- Identify quality risks and propose mitigations
- Coordinate with developers on test coverage and edge cases
- Lead testing during QA phase and pre-release verification
- Track and report quality metrics and defect trends

#### Goals
- Ensure high-quality, reliable releases
- Catch defects early and reduce production incidents
- Build test automation to improve efficiency and coverage
- Enable fast feedback cycles for developers

#### Typical Communication
- Acceptance criteria clarification with Product Manager
- Test plan reviews with developers and Technical Lead
- Quality status reports and metrics
- Pre-release verification and sign-off

#### Interaction with Other Roles
- **Product Manager**: Clarify acceptance criteria and business requirements
- **Developers**: Partner on test design, edge case coverage, and testability feedback
- **Technical Lead**: Collaborate on test infrastructure, strategy, and automation
- **Project Manager**: Report quality status, risks, and readiness for release
- **Security Officer**: Coordinate on security testing and compliance validation

---

### Scrum Master / Agile Coach

#### Role Summary
Scrum Masters facilitate agile ceremonies, remove process blockers, and coach teams on continuous improvement. They enable the team to execute efficiently within the agreed framework.

#### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove process blockers and impediments
- Coach team on agile practices and ceremonies
- Maintain sprint board and backlog health
- Escalate impediments to Project Manager when team cannot resolve
- Promote psychological safety and team collaboration
- Track team velocity and highlight trends

#### Goals
- Enable consistent, predictable team velocity
- Minimize distractions and context-switching
- Foster a culture of continuous improvement and psychological safety
- Improve team collaboration and communication

#### Typical Communication
- Daily standups and ceremony facilitation
- Impediment tracking and escalation
- Retrospective action items and follow-up
- Velocity trends and process metrics

#### Interaction with Other Roles
- **Project Manager**: Escalate impediments, coordinate on timeline and capacity
- **Developers**: Coach on process adherence, backlog refinement, and collaboration
- **Product Manager**: Support in backlog prioritization and refinement
- **Technical Lead**: Facilitate technical discussions and design reviews
- **All team members**: Foster psychological safety, feedback culture, and continuous improvement

---

### Security / Compliance Officer

#### Role Summary
Security Officers review designs for security implications, ensure compliance with policies and regulations, and validate security controls. They embed security into the project lifecycle.

#### Responsibilities
- Review feature designs for security risks and implications
- Ensure compliance with security policies and regulatory requirements
- Participate in threat modeling and security planning
- Validate security scanning and vulnerability assessment results
- Coordinate incident response and security testing before release
- Escalate security risks and remediation priorities
- Provide security guidance and best practices training to the team

#### Goals
- Reduce security vulnerabilities and compliance violations
- Build security awareness and culture across the team
- Enable fast, secure delivery without compromising quality
- Ensure compliance with regulatory and business requirements

#### Typical Communication
- Security design review feedback
- Vulnerability and compliance reports
- Security incident escalation and response
- Pre-release security verification

#### Interaction with Other Roles
- **Technical Lead**: Review architectures for security design, threat modeling
- **Developers**: Provide security guidance and code review feedback
- **Project Manager**: Escalate security risks and timeline impacts
- **QA Lead**: Coordinate on security testing and compliance validation
- **Product Manager**: Advise on security-related requirements and trade-offs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [RACI Matrix](./octoacme-raci-matrix.md) template to clarify decision rights and accountability across roles.
