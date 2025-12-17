# OctoAcme Roles & Responsibilities Quick-Check

## Purpose
A lightweight checklist to help teams clarify roles, responsibilities, and communication patterns during project planning and execution. Use this to audit role clarity and ensure accountability across the team.

## When to Use This
- During project initiation and kickoff
- At the start of each sprint or major milestone
- When onboarding new team members
- When blockers or confusion arise about ownership
- During retrospectives to identify gaps in role clarity

---

## Quick-Check: Are Roles Clear?

### Core Roles Defined
- [ ] **Project Manager** assigned and known to all team members
- [ ] **Product Manager** assigned and known to all team members
- [ ] **Developer(s)** identified with clear areas of ownership
- [ ] Additional roles assigned as needed (see specialized roles below)

### Responsibilities & Ownership
- [ ] Each work item has a clear owner
- [ ] Escalation paths are documented and understood
- [ ] Decision-making authority is clear (who approves what)
- [ ] Communication channels and cadences are established
- [ ] Handoff points between roles are defined

### RACI Quick-Reference

Use RACI to clarify who is **R**esponsible, **A**ccountable, **C**onsulted, and **I**nformed for key activities:

| Activity | PM | PdM | Dev | Scrum Master | UX | BA | DevOps |
|----------|----|----|-----|--------------|----|----|--------|
| Define project goals & success metrics | I | A/R | C | C | C | C | I |
| Prioritize backlog | C | A/R | C | C | C | C | I |
| Sprint planning | R | C | R | A | C | C | C |
| Daily execution & development | I | I | A/R | C | C | I | C |
| Remove blockers | R | C | I | A/R | I | I | C |
| Design user experience | C | C | C | I | A/R | C | I |
| Gather & document requirements | C | R | C | I | C | A/R | I |
| Code review & testing | I | I | A/R | I | C | I | C |
| CI/CD & deployment | C | I | C | I | I | I | A/R |
| Production monitoring | I | I | R | I | I | I | A/R |
| Risk management | A/R | C | C | C | C | C | C |
| Stakeholder communication | A/R | R | C | C | C | C | I |
| Retrospectives | R | R | R | A | R | R | R |

**Legend:**
- **R** (Responsible): Does the work
- **A** (Accountable): Ultimately answerable for completion (only one A per activity)
- **C** (Consulted): Provides input and expertise
- **I** (Informed): Kept in the loop

---

## Specialized Roles Assessment

### Do you need a Scrum Master?
**Consider if:**
- [ ] Team is new to agile practices
- [ ] Team struggles with velocity or impediments
- [ ] Cross-team dependencies require active coordination
- [ ] Team needs coaching on agile ceremonies

### Do you need a UX Designer?
**Consider if:**
- [ ] Project involves user-facing features or interfaces
- [ ] User experience is a key success factor
- [ ] Design research or usability testing is needed
- [ ] Design system consistency is critical

### Do you need a Business Analyst?
**Consider if:**
- [ ] Complex business requirements need translation
- [ ] Multiple stakeholders with varying needs
- [ ] Process changes or workflow redesign involved
- [ ] Benefits tracking and ROI measurement required

### Do you need a DevOps Engineer?
**Consider if:**
- [ ] CI/CD pipeline setup or optimization needed
- [ ] Infrastructure changes or scaling required
- [ ] Complex deployment or rollback scenarios
- [ ] Production monitoring and incident response critical

---

## Communication Audit

### Regular Touchpoints Established
- [ ] Daily standups scheduled (if using agile)
- [ ] Weekly PM + PdM sync on priorities and risks
- [ ] Sprint planning and retrospectives scheduled
- [ ] Stakeholder update cadence defined
- [ ] Ad-hoc communication channels clear (Slack, email, etc.)

### Cross-Role Collaboration
- [ ] Dev ↔ UX handoff process defined
- [ ] BA ↔ PdM requirements alignment process clear
- [ ] DevOps ↔ Dev deployment coordination process established
- [ ] Scrum Master ↔ PM escalation path documented
- [ ] All team members know how to reach each other

---

## Quick Actions When Clarity Gaps Found

1. **Missing role**: Discuss with Project Manager and stakeholders whether to assign role or distribute responsibilities
2. **Unclear ownership**: Update RACI matrix and communicate to team
3. **Communication gaps**: Add missing meetings or touchpoints to team calendar
4. **Overlapping responsibilities**: Clarify boundaries in team meeting and document
5. **Escalation confusion**: Document and share escalation paths

---

## Related Documentation

- **[Roles & Personas](https://github.com/mateuscarlos/skills-scale-institutional-knowledge-using-copilot-spaces/blob/2a71bd808c726a59a3c1e2a799b78a539b2a75e1/docs/octoacme-roles-and-personas.md)** - Detailed role definitions and responsibilities
- **[Project Management Overview](https://github.com/mateuscarlos/skills-scale-institutional-knowledge-using-copilot-spaces/blob/2a71bd808c726a59a3c1e2a799b78a539b2a75e1/docs/octoacme-project-management-overview.md)** - Core roles and communication cadence
- **[Risk Management & Communication](https://github.com/mateuscarlos/skills-scale-institutional-knowledge-using-copilot-spaces/blob/2a71bd808c726a59a3c1e2a799b78a539b2a75e1/docs/octoacme-risks-and-communication.md)** - Escalation paths and protocols

---

**Pro Tip:** Review this checklist during sprint planning and retrospectives to catch role clarity issues early. A quick 5-minute role audit can prevent hours of confusion later.
