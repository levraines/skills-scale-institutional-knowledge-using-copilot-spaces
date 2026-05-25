# OctoAcme — Cross-Functional Collaboration

## Purpose
Define how delivery roles collaborate across the project lifecycle to improve alignment, ownership, and outcomes.

## When to use
Use this guide when initiating a project, planning cross-functional work, or clarifying ownership during execution.

## Roles in scope
- Project Manager (PM)
- Product Manager (PdM)
- Developers
- Scrum Master
- UX/UI Designer
- Business Analyst
- DevOps Engineer
- Security Champion
- Data Analyst
- QA/Testing
- Stakeholders

## Collaboration Checklist
- Confirm role coverage at project kickoff and document named owners.
- Align on goals, success metrics, and acceptance criteria before sprint execution.
- Hold recurring cross-functional syncs for dependency, risk, and blocker review.
- Track decisions, assumptions, and changes in a shared source of truth.
- Validate release readiness across quality, operations, security, and communication.
- Run retrospectives with action owners and due dates.

## RACI Matrix (key activities)
| Activity | PM | PdM | Dev | SM | UX/UI | BA | DevOps | Sec Champ | Data | QA | Stakeholders |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Project kickoff and delivery plan | A | C | I | C | I | C | I | I | I | I | R |
| Requirements and acceptance criteria | C | A | C | I | C | R | I | C | C | C | I |
| UX discovery and solution design | I | A | C | I | R | C | I | I | C | C | I |
| Sprint planning and agile ceremonies | C | C | R | A | I | I | I | I | I | I | I |
| Implementation and code review | I | I | A/R | I | C | C | C | C | I | C | I |
| Test strategy and validation | I | C | C | I | C | C | I | C | I | A/R | I |
| CI/CD, release, and deployment | C | I | C | I | I | I | A/R | C | I | C | I |
| Security review and remediation | C | I | C | I | I | I | C | A/R | I | C | I |
| Post-release metrics and impact review | C | A | I | I | I | C | I | I | R | C | C |

Legend: **R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed.

## Conflict Resolution Guidance
1. **Clarify decision ownership**: Use the RACI matrix to identify accountable role(s).
2. **Start with shared goals**: Re-anchor discussion to customer outcomes, delivery risk, and scope.
3. **Use evidence**: Bring design artifacts, requirement notes, metrics, or technical constraints.
4. **Escalate quickly when blocked**: Route unresolved issues to PM + PdM, then sponsor/stakeholder if needed.
5. **Document decisions**: Capture final decisions, rationale, and follow-up actions in project records.

## Best Practices for Multi-Role Coordination
- Involve UX/UI Designer and Business Analyst early in discovery and planning.
- Involve DevOps Engineer and Security Champion before implementation is complete to avoid release bottlenecks.
- Involve Data Analyst during planning to define instrumentation before development starts.
- Time-box cross-functional reviews and define clear decision deadlines.
- Keep handoffs lightweight with shared templates, explicit owners, and due dates.
