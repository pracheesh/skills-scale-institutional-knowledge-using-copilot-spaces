# OctoAcme — Risk Management Checklist & Templates

## Purpose
Provide a repeatable checklist and templates to help Risk Managers, Project Managers, and Team Leads identify, assess, mitigate, and monitor project risks consistently.

---

## Risk Identification Checklist

Use this checklist at project kickoff, sprint planning, and major milestone reviews to proactively surface risks.

### Scope & Requirements
- [ ] Are requirements fully defined and agreed upon by stakeholders?
- [ ] Are there ambiguous or rapidly changing requirements?
- [ ] Is the scope at risk of uncontrolled growth (scope creep)?

### Schedule & Resources
- [ ] Are milestones and deadlines realistic given available capacity?
- [ ] Are key team members at risk of unavailability (leave, turnover)?
- [ ] Are there external dependencies that could delay delivery?

### Technical
- [ ] Are there unfamiliar technologies or architectures in use?
- [ ] Are there integration or compatibility risks with existing systems?
- [ ] Is technical debt at a level that could slow delivery?

### Quality & Testing
- [ ] Is test coverage sufficient for critical functionality?
- [ ] Are automated quality gates in place and passing?
- [ ] Are known defects or regressions tracked and prioritized?

### Communication & Stakeholders
- [ ] Are stakeholder expectations aligned with current scope and timeline?
- [ ] Are decision-makers accessible and responsive?
- [ ] Are there gaps in communication that could cause misalignment?

### Compliance & Security
- [ ] Are there regulatory or compliance requirements that need to be met?
- [ ] Have security risks and threat models been reviewed?
- [ ] Are data handling and privacy requirements addressed?

---

## Risk Register Template

Maintain a risk register in your project repository or project management tool. Update it weekly or when new risks are identified.

| ID | Description | Category | Impact | Likelihood | Risk Score | Owner | Mitigation Plan | Contingency Plan | Status | Last Updated |
|----|-------------|----------|--------|------------|------------|-------|-----------------|------------------|--------|--------------|
| R-001 | Example: Key developer unavailable during critical sprint | Resource | High | Medium | High | Project Manager | Cross-train a second developer; document critical knowledge | Redistribute work across team | Open | YYYY-MM-DD |
| R-002 | Example: Third-party API changes breaking integration | Technical | High | Low | Medium | Team Lead | Monitor API changelog; pin to stable version | Implement fallback logic | Monitoring | YYYY-MM-DD |

### Risk Score Matrix

| | **Low Likelihood** | **Medium Likelihood** | **High Likelihood** |
|---|---|---|---|
| **High Impact** | Medium | High | Critical |
| **Medium Impact** | Low | Medium | High |
| **Low Impact** | Low | Low | Medium |

---

## Risk Assessment Guide

### Impact Definitions
- **High**: Could cause project failure, major delay (>2 weeks), or significant quality degradation.
- **Medium**: Could cause a moderate delay (1–2 weeks) or require significant rework.
- **Low**: Minor inconvenience; resolvable within the sprint with minimal impact.

### Likelihood Definitions
- **High**: Very likely to occur (>70% probability) based on current conditions.
- **Medium**: Possible but not certain (30–70% probability).
- **Low**: Unlikely but worth monitoring (<30% probability).

---

## Risk Mitigation Actions

For each identified risk, document the following:

1. **Preventive Actions**: Steps to reduce the likelihood of the risk occurring.
2. **Contingency Plans**: Actions to take if the risk materializes.
3. **Owner**: Named individual responsible for monitoring and acting on the risk.
4. **Review Cadence**: How often the risk will be reviewed (e.g., weekly, per sprint).

---

## Risk Escalation Criteria

Escalate a risk to the next level when:
- The risk score is **Critical** or **High** and mitigation actions are insufficient.
- A risk has materialized and is causing project impact.
- A risk requires a decision beyond the current team's authority (budget, scope, or timeline changes).

### Escalation Path
1. **Team Level** → Team Lead resolves or escalates to Project Manager.
2. **Project Level** → Project Manager works with Risk Manager and stakeholders.
3. **Executive Level** → Project Sponsor is engaged for critical or business-impacting risks.

---

## Weekly Risk Review Agenda

Use this agenda at weekly project syncs to review the risk register:

1. Review status of open risks (5 min)
2. Identify new risks from the past week (5 min)
3. Update mitigation plan progress for high/critical risks (5 min)
4. Confirm owners for any newly identified risks (2 min)
5. Decide on any escalations needed (3 min)
