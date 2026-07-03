# OctoAcme — RACI Matrix

## Purpose
Clarify decision rights, accountability, and communication channels across roles using a RACI (Responsible, Accountable, Consulted, Informed) framework.

## RACI Definitions
- **Responsible (R)**: Does the work; executes the task or decision
- **Accountable (A)**: Has final authority; approves or sign-offs
- **Consulted (C)**: Provides input or expertise; asked for advice before decision
- **Informed (I)**: Kept in the loop; notified after decision is made

## Project Management RACI Matrix

| Activity | PM | PdM | Tech Lead | Developers | QA Lead | Scrum Master | Stakeholder | Security Officer |
|----------|----|----|-----------|------------|---------|--------------|-------------|------------------|
| **Initiation** |
| Develop project one-pager | C | A | C | I | I | I | A | C |
| Stakeholder alignment | A | C | I | I | I | I | C | I |
| Define success metrics | C | A | I | I | C | I | C | I |
| Identify initial risks | R | C | C | I | I | I | C | C |
| **Planning** |
| Create project kickoff | R | C | C | I | I | C | C | I |
| Prioritize backlog | C | A | C | C | C | I | C | C |
| Estimate scope/effort | C | C | A | R | C | R | I | I |
| Define acceptance criteria | C | A | C | R | C | I | I | C |
| Design technical architecture | C | I | A | R | C | I | I | C |
| Identify dependencies | R | C | A | C | I | C | C | I |
| Create test plan / QA approach | C | C | C | C | A | I | I | C |
| Review security requirements | I | C | A | I | C | I | I | A |
| **Execution** |
| Sprint planning | C | C | C | R | I | A | I | I |
| Daily standups | I | I | I | R | I | A | I | I |
| Code review / design review | I | I | A | R | C | I | I | C |
| Write tests | I | I | C | A | C | I | I | I |
| Execute QA testing | I | I | I | C | A | I | I | C |
| Security scanning / validation | I | I | C | C | C | I | I | A |
| Update risk register | R | C | C | I | I | I | C | C |
| Escalate blockers | R | C | C | I | I | A | I | I |
| **Release** |
| Prepare release notes | C | A | C | R | C | I | I | C |
| Run smoke tests | I | I | C | C | A | I | I | C |
| Security sign-off | I | I | C | I | I | I | I | A |
| Stakeholder approval / sign-off | A | C | I | I | I | I | A | I |
| Deploy to production | I | I | A | R | I | C | I | I |
| Post-deployment verification | I | I | A | C | A | I | I | I |
| **Close & Retrospective** |
| Run retrospective | A | C | C | R | C | R | I | I |
| Capture action items | R | C | C | I | I | A | I | I |
| Document learnings | R | C | C | I | C | I | I | I |
| Metrics review / success validation | C | A | C | I | C | I | C | I |

## Legend
- **R** = Responsible (executes)
- **A** = Accountable (approves/signs off)
- **C** = Consulted (provides input)
- **I** = Informed (kept in the loop)

## How to Use This Matrix

1. **Clarify decision rights**: When ambiguity arises about who owns a decision, reference the RACI matrix.
2. **Onboard new team members**: Highlight their row(s) to show where they're Responsible, Accountable, Consulted, or Informed.
3. **Plan communications**: Use the matrix to determine who should attend meetings, be copied on emails, or receive updates.
4. **Customize per project**: Organizations may adjust the matrix based on team size, structure, or specific project needs.

## Tips
- Avoid having too many **A** (Accountable) designations per activity — clarity comes from single ownership.
- Balance **C** (Consulted) across roles to ensure the right expertise is included without creating decision paralysis.
- Ensure everyone understands their role — clarify during project kickoff.
- Review and update the matrix if roles or responsibilities change mid-project.
