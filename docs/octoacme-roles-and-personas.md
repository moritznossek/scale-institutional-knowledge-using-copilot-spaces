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

## QA / Testing

### Role Summary
QA and Testing roles validate that delivered features meet acceptance criteria, quality standards, and user expectations before release.

### Responsibilities
- Define and execute test plans for features and releases
- Validate acceptance criteria and report defects
- Perform regression, exploratory, and smoke testing
- Maintain test environments and test automation suites
- Provide sign-off for release readiness

### Goals
- Prevent defects from reaching production
- Maintain a consistent, high-quality bar across releases
- Accelerate feedback loops between QA and development

### Typical Communication
- Bug reports and test result summaries
- Participation in sprint reviews and release readiness discussions
- Close collaboration with Developers on reproduction steps and fixes

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in project outcomes — including business owners, executive sponsors, and end-user representatives. They provide inputs, approvals, and guidance to keep delivery aligned with organizational goals.

### Responsibilities
- Review and approve project charters, scope, and milestones
- Provide timely decisions on trade-offs and priorities
- Surface business constraints, regulatory requirements, or strategic context
- Validate that outcomes meet intended business value

### Goals
- Ensure project investments deliver expected returns
- Maintain visibility into progress, risks, and decisions
- Provide strategic direction without creating delivery bottlenecks

### Typical Communication
- Monthly or milestone-based status updates
- Decision review meetings and approvals
- Executive summaries and risk escalations

---

## Engineering Manager

### Role Summary
Engineering Managers ensure the development team is staffed, healthy, and equipped to deliver on project commitments. They bridge organizational concerns with delivery realities.

### Responsibilities
- Manage team capacity planning and staffing decisions
- Coach and support developers through delivery challenges and skill development
- Escalate and help resolve organizational blockers affecting delivery
- Monitor team health, morale, and sustainable pace
- Coordinate hiring, onboarding, and resource allocation across projects

### Goals
- Build and maintain a high-performing, sustainable delivery team
- Remove systemic blockers that impede velocity and quality
- Align team capacity with product and project roadmap commitments

### Typical Communication
- Regular 1:1s with team members and delivery leads
- Capacity and headcount planning conversations with leadership
- Cross-functional escalations when resource constraints affect commitments

### Collaboration With Existing Roles
- **Project Managers**: partners on timeline feasibility, resource risk identification, and resolving delivery blockers
- **Product Managers**: aligns on trade-offs when capacity constraints affect scope or priority
- **Developers**: provides coaching, removes organizational blockers, and supports career development
- **QA**: ensures QA capacity is planned alongside development capacity
- **Stakeholders**: communicates resource constraints that may affect project commitments

---

## UX / UI Designer

### Role Summary
UX/UI Designers ensure that features are usable, accessible, and aligned with user expectations. They translate product requirements into concrete interaction patterns and visual designs ready for implementation.

### Responsibilities
- Create user flows, wireframes, and interactive prototypes
- Conduct or synthesize usability research to validate designs
- Produce design specifications and assets for developer handoff
- Participate in sprint planning to ensure design readiness ahead of development
- Review implemented features for design fidelity and usability

### Goals
- Deliver clear, implementable designs that meet acceptance criteria
- Reduce rework caused by design ambiguity during development
- Improve end-user satisfaction and feature adoption

### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Prototype walkthroughs and usability test readouts
- Annotated design specs shared before implementation begins

### Collaboration With Existing Roles
- **Product Managers**: refines requirements and acceptance criteria through design exploration; aligns on user outcomes
- **Developers**: ensures designs are implementable and provides clarification during build; reviews implementation fidelity
- **QA**: shares expected UX behaviors and interaction patterns to inform test cases
- **Project Managers**: flags design readiness gaps that may affect sprint commitment
- **Stakeholders**: presents design concepts for feedback and approval at key milestones

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers own the reliability, automation, and observability of the delivery pipeline and production environment. They reduce friction in the release process and maintain the infrastructure that teams depend on.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Ensure environment readiness (dev, staging, production) for each release
- Define and enforce deployment guardrails and release standards
- Implement observability tooling (logging, metrics, alerting)
- Support incident response with rollback capabilities and runbooks

### Goals
- Enable fast, safe, and repeatable deployments
- Minimize deployment-related incidents and recovery time
- Provide development and QA teams with reliable, stable environments

### Typical Communication
- Release readiness updates and deployment schedules
- Incident notifications and post-incident summaries
- Pipeline health dashboards and environment status reports

### Collaboration With Existing Roles
- **Developers**: partners on build and release automation; provides guidance on CI integration and environment usage
- **Project Managers**: communicates deployment schedules, environment constraints, and release readiness status
- **Product Managers**: surfaces infrastructure or platform constraints that affect release feasibility or timeline
- **QA**: provides stable staging environments and supports automated test execution in the pipeline
- **Stakeholders**: ensures operational readiness is factored into release communications and go-live planning

---

## Security / Compliance Lead

### Role Summary
The Security/Compliance Lead ensures that security requirements are embedded throughout the delivery lifecycle, regulatory obligations are met, and the team is prepared for security incidents.

### Responsibilities
- Conduct threat modeling and security risk reviews during planning
- Define security requirements and acceptance criteria for features
- Facilitate compliance checkpoints (e.g., data privacy, regulatory audits)
- Provide guidance on secure coding and architecture practices
- Lead or support security incident response and post-incident review

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance obligations are met without blocking delivery
- Build a security-aware culture within the team

### Typical Communication
- Security review sign-offs at key milestones (planning, pre-release)
- Threat model summaries and compliance status reports
- Incident response communications and post-mortems

### Collaboration With Existing Roles
- **Product Managers**: advises on security and compliance requirements during discovery and planning; flags regulatory constraints that affect scope
- **Developers**: provides guidance on secure implementation practices, reviews code changes with security implications
- **Project Managers**: partners on risk escalation for security issues; contributes to the risk register and governance reporting
- **QA**: coordinates on security testing (e.g., penetration testing, dependency scanning) as part of release readiness
- **Stakeholders**: reports on compliance status, audit readiness, and security posture at milestone reviews

---

## Customer Success / Support Representative

### Role Summary
Customer Success and Support Representatives bring the voice of the customer into the delivery process. They surface user pain points, communicate feature readiness to customers, and ensure the support team can handle post-release volume.

### Responsibilities
- Communicate recurring user issues, pain points, and feature requests to the product team
- Assess support team readiness for each release (training, documentation, tooling)
- Provide reproduction context for customer-reported bugs
- Manage release communications and enablement for end users and support staff
- Track and report post-release user feedback and support impact

### Goals
- Reduce customer-facing friction and support ticket volume after releases
- Ensure customers are informed and enabled to use new features effectively
- Close the feedback loop between users and the delivery team

### Typical Communication
- Pre-release enablement sessions with support staff
- Post-release feedback summaries shared with Product Managers
- Escalation of high-impact customer issues to the delivery team

### Collaboration With Existing Roles
- **Product Managers**: informs prioritization with customer outcome data and support trend signals; validates that features address real user needs
- **Project Managers**: coordinates on release communication plans, rollout timing, and support readiness milestones
- **Developers**: provides issue trends and reproduction steps to help diagnose and fix customer-reported defects
- **QA**: shares real-world usage patterns to improve test coverage for high-impact user flows
- **Stakeholders**: communicates customer sentiment, adoption metrics, and support impact to business stakeholders

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

