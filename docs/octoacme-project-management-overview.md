# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- Scrum Master: facilitates agile ceremonies and removes team impediments.
- UX/UI Designer: owns user experience, usability, and design quality.
- Business Analyst: clarifies requirements and bridges business-to-technical handoffs.
- DevOps Engineer: manages CI/CD, environments, deployment reliability, and operations readiness.
- Security Champion: embeds secure development practices and risk awareness in delivery.
- Data Analyst: defines success metrics, reporting, and outcome analysis.
- QA/Testing: validate quality and acceptance criteria.
- Stakeholders: provide inputs and approvals.

See `octoacme-roles-and-personas.md` for detailed persona definitions and `octoacme-cross-functional-collaboration.md` for role coordination and RACI guidance.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## When to involve each role
- **Project Manager**: from initiation through close for planning, delivery tracking, and stakeholder communication.
- **Product Manager**: at project inception and throughout delivery for prioritization, scope, and outcomes.
- **Developers**: during planning for estimates/feasibility and throughout execution for implementation.
- **Scrum Master**: when teams run iterative delivery and need ceremony facilitation or impediment removal.
- **UX/UI Designer**: during discovery and planning, then during implementation reviews for usability consistency.
- **Business Analyst**: during initiation and planning to capture requirements and process impacts.
- **DevOps Engineer**: during planning for environment/deployment needs and before releases for readiness.
- **Security Champion**: during design and implementation for risk reviews and secure-by-default decisions.
- **Data Analyst**: during planning to define metrics and after releases to evaluate impact.
- **QA/Testing**: from planning onward to shape acceptance criteria and validate release quality.
- **Stakeholders**: at initiation for alignment, at milestones for decisions, and at release for approvals.

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
