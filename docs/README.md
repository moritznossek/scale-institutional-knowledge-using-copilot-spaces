# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management docs hub. This folder contains the processes, templates, and guidance used to plan, execute, and deliver projects at OctoAcme.

## Overview: How OctoAcme Manages Projects

OctoAcme follows a structured lifecycle approach to managing cross-functional projects, spanning five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During initiation, teams validate business needs and create a lightweight Project One-pager that defines the problem statement, success metrics, stakeholders, and initial timeline. Once approved at a decision gate, projects move into planning where work is broken into shippable increments with clear acceptance criteria, estimates, and dependencies. This iterative, customer-first approach emphasizes delivering small, testable increments and maintaining psychological safety throughout the team.

Execution and delivery are coordinated through a structured team rhythm and clear role definitions. OctoAcme defines four core personas—**Project Managers** (who coordinate schedules and risks), **Product Managers** (who define outcomes and prioritize backlog), **Developers** (who implement features with quality standards), and **Stakeholders** (who provide inputs and approvals). The team operates with daily 15-minute standups, weekly delivery syncs, and sprint-based planning using GitHub Projects with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible) and require at least one approval, with automated CI/CD testing and linting before review. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, and security scanning.

Risk management and transparent communication are cornerstones of OctoAcme's approach. The team maintains a Risk Register tracking impact, likelihood, owners, and mitigation plans, reviewed weekly at syncs. A three-level escalation path moves blockers from team-level triage through the PM and Product Lead to sponsor-level escalation when needed. Stakeholders receive regular status updates using a consistent template (progress, next steps, risks, decisions needed), and any incidents trigger blameless retrospectives. Once features are ready for release, teams follow a pre-release checklist including smoke tests, rollback plans, and post-deploy verification before announcing to stakeholders.

Finally, OctoAcme embeds continuous improvement through structured retrospectives held after sprints, releases, or significant milestones. These sessions capture what went well and what could improve, generating 2–3 prioritized action items with clear owners and due dates. By treating retrospective insights as backlog items and tracking their impact, OctoAcme ensures learnings are converted into tangible process and product improvements, reinforcing a culture of iterative refinement and psychological safety.

## Quick Links to Processes

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate ideas, align stakeholders, create a lightweight plan
- [Project Planning](./octoacme-project-planning.md) — Turn initiatives into actionable backlogs and timelines
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery, standups, quality, and metrics
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize releases and deployments
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and improve
- [Roles & Personas](./octoacme-roles-and-personas.md) — Core roles (PM, PdM, Developers, QA) and responsibilities

## OctoAcme Project Lifecycle at a Glance

1. **Initiation** — Problem statement, stakeholder alignment, high-level timeline
2. **Planning** — Scope, resources, milestones, dependencies, backlog prioritization
3. **Execution** — Build, test, review, iterate with regular standups and demos
4. **Release** — Deploy to production with pre-release checks and rollback plans
5. **Close & Retrospective** — Capture learnings and action items for next cycle

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a 10-minute primer on roles and lifecycle
- **Starting a new project**: Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to kick off with stakeholder alignment
- **In active delivery**: Use [Execution & Tracking](./octoacme-execution-and-tracking.md) and the project board for daily coordination
- **Managing risks**: Refer to [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation and communication templates
- **Improving processes**: After a milestone or sprint, use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture improvements
