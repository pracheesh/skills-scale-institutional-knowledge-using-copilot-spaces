# OctoAcme — Change Control Process

## Purpose
Define the process for requesting, reviewing, approving, and implementing changes to project scope, architecture, timelines, or key deliverables. This process ensures changes are evaluated for risk and impact before implementation and maintains a clear audit trail.

---

## What Requires a Change Request?

A formal change request is required when a proposed change affects any of the following:

- Project scope (adding, removing, or significantly modifying deliverables)
- Approved architecture or technology stack
- Project timeline or key milestones
- Budget or resource allocation
- Agreed acceptance criteria or Definition of Done
- External commitments or contractual obligations

> **Note:** Minor clarifications, bug fixes within existing scope, and small technical implementation decisions do not require a formal change request.

---

## Change Request Lifecycle

```
Submitted → Under Review → CCB Decision → [Approved / Rejected / Deferred]
                                              ↓
                                         Implemented → Verified → Closed
```

### Stages

1. **Submitted**: A team member or stakeholder submits a Change Request form (see template below).
2. **Under Review**: The CCB Representative reviews the request for completeness and schedules a CCB review.
3. **CCB Decision**: The Change Control Board reviews the request and decides to Approve, Reject, or Defer.
4. **Implemented**: If approved, the change is incorporated into project plans, backlog, and documentation.
5. **Verified**: The Project Manager confirms the change has been successfully implemented.
6. **Closed**: The Change Request is marked closed in the change log.

---

## Change Request Form Template

Use this template when submitting a change request. Submit completed forms to the CCB Representative.

---

**Change Request ID:** CR-[NNN] *(assigned by CCB Representative)*
**Submitted By:** [Name / Role]
**Date Submitted:** [YYYY-MM-DD]
**Priority:** Low / Medium / High / Critical

### Change Description
[Provide a clear, concise description of the proposed change.]

### Business Justification / Rationale
[Explain why this change is needed. What problem does it solve or what opportunity does it address?]

### Scope Impact
[Describe what deliverables, features, or components will be affected.]

### Schedule Impact
[Describe the estimated impact on project timeline or milestones. Provide revised dates if applicable.]

### Resource / Cost Impact
[Describe any changes to team capacity, budget, or tooling requirements.]

### Risk Assessment
[List any risks introduced by this change and proposed mitigations.]

### Dependencies
[List any other changes, tasks, or decisions this change depends on.]

### Rollback Plan
[Describe how this change can be reversed if problems arise after implementation.]

### Requested By Approval Date
[Date by which a decision is needed, if applicable.]

---

## Change Log

Maintain a change log to track all submitted change requests and their status.

| CR ID | Title | Submitted By | Date Submitted | Priority | Status | CCB Decision Date | Decision | Implemented Date |
|---|---|---|---|---|---|---|---|---|
| CR-001 | Example: Add new reporting module | Jane Smith | 2026-01-15 | Medium | Closed | 2026-01-18 | Approved | 2026-02-01 |
| CR-002 | Example: Extend project deadline by 2 weeks | Bob Jones | 2026-02-10 | High | Closed | 2026-02-12 | Approved | 2026-02-12 |

---

## Change Control Board (CCB) Review Process

### CCB Membership
- CCB Representative (Chair)
- Project Manager
- Project Sponsor (for high/critical changes)
- Product Owner or Product Manager
- Technical Lead (for architecture or technical changes)

### Review Criteria
The CCB evaluates each change request against the following criteria:

1. **Necessity**: Is this change truly required, or can the need be met within existing scope?
2. **Impact**: What is the impact on scope, schedule, budget, and quality?
3. **Risk**: What risks does the change introduce, and are mitigations sufficient?
4. **Alignment**: Does the change align with project objectives and business strategy?
5. **Feasibility**: Can the change be implemented with available resources and within acceptable timeframes?

### Decision Options
- **Approved**: Change is accepted and will be incorporated into the project plan.
- **Rejected**: Change is not accepted. Reason must be documented and communicated to submitter.
- **Deferred**: Decision is postponed pending additional information or to a future planning cycle.

### CCB Meeting Cadence
- **Regular changes**: Reviewed at the next scheduled weekly CCB session.
- **High/Critical changes**: An ad-hoc CCB review is convened within 48 hours of submission.

---

## Roles & Responsibilities

| Role | Responsibility |
|---|---|
| **Change Requestor** | Completes and submits the Change Request form with sufficient detail. |
| **CCB Representative** | Facilitates CCB review, documents decisions, communicates outcomes, and maintains the change log. |
| **Project Manager** | Incorporates approved changes into project plans and ensures implementation is tracked. |
| **Project Sponsor** | Provides final approval for high-impact or budget-affecting changes. |
| **Product Owner / Manager** | Assesses business value and priority of proposed changes. |
| **Team Leads / Developers** | Provide technical feasibility input during CCB review. |

---

## Communication of CCB Decisions

- CCB decisions are documented in the Change Log within 24 hours of the review meeting.
- The CCB Representative notifies the change requestor and relevant stakeholders of the decision by email.
- Approved changes are communicated to the delivery team by the Project Manager at the next standup or planning session.
- The Communications Specialist includes significant approved changes in the next stakeholder status update.
