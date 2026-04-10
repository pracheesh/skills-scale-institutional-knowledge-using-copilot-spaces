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

## Team Leads

### Role Summary
Team Leads guide a group of developers or specialists, bridging technical execution with project goals. They are responsible for team delivery quality and developer growth.

### Responsibilities
- Assign and track work within the team
- Conduct code and design reviews
- Mentor developers and provide performance feedback
- Coordinate with Project Managers on dependencies and blockers
- Escalate risks or capacity issues promptly

### Goals
- Maintain high team velocity and code quality
- Foster a collaborative and psychologically safe team environment
- Ensure the team meets its sprint or milestone commitments

### Typical Communication
- Daily standups and one-on-ones with team members
- Sprint reviews and retrospectives
- Status updates to Project Managers

---

## Release Managers

### Role Summary
Release Managers own the planning, coordination, and execution of software releases. They ensure that deployments are safe, well-communicated, and meet quality gates.

### Responsibilities
- Coordinate release scheduling and deployment windows
- Verify all pre-release requirements are met
- Manage rollback plans and incident response during deployments
- Communicate release status to stakeholders
- Maintain release notes and deployment records

### Goals
- Deliver reliable and predictable releases
- Minimize deployment risk and production incidents
- Maintain clear audit trails of all releases

### Typical Communication
- Pre-release checklists and go/no-go calls
- Release announcements to stakeholders and support teams
- Post-release retrospectives and incident reports

---

## Project Sponsors

### Role Summary
Project Sponsors are senior stakeholders who champion the project, secure resources, and remove organizational blockers. They provide strategic direction and final escalation authority.

### Responsibilities
- Approve project scope, budget, and major decisions
- Remove high-level organizational impediments
- Communicate project value to leadership
- Participate in steering committee reviews

### Goals
- Ensure the project aligns with business strategy
- Protect team capacity and funding
- Drive organizational commitment to project success

### Typical Communication
- Monthly or milestone-based steering committee updates
- Escalation calls as needed
- Executive briefings and status summaries

---

## Product Owners

### Role Summary
Product Owners represent the business and customer voice within the delivery team. They own the prioritized backlog and accept or reject completed work.

### Responsibilities
- Maintain and prioritize the product backlog
- Write and refine user stories and acceptance criteria
- Participate in sprint planning and review ceremonies
- Provide rapid decisions on scope and priority trade-offs
- Serve as the primary liaison between business stakeholders and the delivery team

### Goals
- Maximize the value delivered in each sprint or iteration
- Ensure the team builds the right things in the right order
- Drive clear, measurable acceptance criteria

### Typical Communication
- Sprint planning, review, and daily standups
- Backlog grooming sessions
- Regular stakeholder alignment meetings

---

## Risk Manager

### Role Summary
The Risk Manager is responsible for identifying, assessing, tracking, and mitigating risks throughout the project lifecycle. They ensure risk management practices are consistently followed and that threats to project success are surfaced early.

### Responsibilities
- Maintain and update the project Risk Register
- Facilitate risk identification workshops during planning and execution
- Assess risk impact and likelihood with relevant stakeholders
- Work with Project Managers and Team Leads to develop and monitor mitigation plans
- Escalate high-impact risks to the Project Sponsor as needed
- Report risk status at weekly syncs and steering committee reviews

### Goals
- Reduce the probability and impact of project risks
- Ensure every identified risk has a named owner and mitigation plan
- Enable data-driven decision-making by keeping risk information current

### Typical Communication
- Weekly risk register updates shared with Project Manager
- Risk review sessions during sprint planning and retrospectives
- Escalation reports for high/critical risks

### Interactions with Existing Roles
- **Project Manager:** Collaborates daily to align risk actions with project schedule and resource plans.
- **Team Leads:** Relies on Team Leads to surface technical risks during execution.
- **Product Owner / Product Manager:** Coordinates on scope-change risks and priority trade-offs.
- **Project Sponsor:** Escalates critical risks that require executive decisions or resource changes.

---

## Quality Assurance Lead

### Role Summary
The Quality Assurance (QA) Lead oversees testing strategy, standards compliance, and release readiness across the project. They ensure that delivered software meets acceptance criteria and quality gates before release.

### Responsibilities
- Define and maintain the test strategy, plans, and standards
- Oversee manual and automated testing efforts
- Coordinate with Developers to ensure testability and sufficient test coverage
- Run pre-release readiness checks and sign off on go/no-go decisions
- Track defects, test results, and quality metrics
- Drive continuous improvement in testing processes

### Goals
- Prevent defects from reaching production
- Maintain visibility into quality health throughout the project
- Reduce regression risk through systematic test coverage

### Typical Communication
- Daily standups with the delivery team
- Test result reports and defect triage meetings
- Pre-release go/no-go sign-off communications

### Interactions with Existing Roles
- **Developers:** Works closely to define acceptance criteria, review testability, and triage defects.
- **Release Managers:** Provides quality sign-off and readiness confirmation before deployments.
- **Project Manager:** Reports quality metrics and escalates blocking defects that affect timelines.
- **Product Owner:** Validates that delivered features satisfy business acceptance criteria.

---

## Change Control Board Representative

### Role Summary
The Change Control Board (CCB) Representative reviews proposed changes to project scope, architecture, or key deliverables, ensures change management processes are followed, and provides approvals or rejections on behalf of the Change Control Board.

### Responsibilities
- Review change requests for completeness, risk, and business impact
- Facilitate CCB meetings and document decisions
- Ensure all approved changes are reflected in project plans and documentation
- Communicate change decisions to relevant stakeholders
- Track the status of open, approved, and rejected change requests

### Goals
- Prevent uncontrolled scope or architecture changes
- Ensure changes are evaluated for risk and impact before implementation
- Maintain a clear audit trail of all project changes

### Typical Communication
- CCB meeting minutes and decisions distributed to stakeholders
- Change request status updates to Project Managers
- Escalation to Project Sponsor for high-impact changes

### Interactions with Existing Roles
- **Project Sponsor:** Escalates significant changes that require executive approval or funding adjustments.
- **Product Owner / Product Manager:** Collaborates to assess business impact and priority of proposed changes.
- **Project Manager:** Works together to ensure approved changes are incorporated into plans and timelines.
- **Developers and Team Leads:** Communicates approved changes so implementation can begin promptly.

---

## Communications Specialist

### Role Summary
The Communications Specialist is responsible for crafting, coordinating, and delivering project communications. They ensure consistent, timely, and audience-appropriate messaging to all stakeholders throughout the project lifecycle.

### Responsibilities
- Develop and maintain the project communication plan
- Draft status updates, release announcements, and stakeholder briefings
- Manage internal and external messaging channels (email, Slack, wikis, etc.)
- Ensure communications are aligned with project milestones and escalations
- Gather feedback on communication effectiveness and adjust as needed

### Goals
- Ensure all stakeholders receive timely and accurate project information
- Reduce miscommunication and information silos
- Maintain a consistent project narrative aligned with business objectives

### Typical Communication
- Weekly status reports and newsletters
- Release and milestone announcements
- Incident and escalation notifications

### Interactions with Existing Roles
- **Project Manager:** Works closely to align communication timing with project events and decisions.
- **Product Manager / Product Owner:** Ensures product messaging is accurate and reflects current priorities.
- **Developers and Team Leads:** Collects technical progress updates to include in stakeholder communications.
- **Release Manager:** Coordinates release announcements and post-deployment communications.
- **All Roles:** Serves as the central point for messaging, ensuring consistent voice and information across the team.

---

## Agile Coach

### Role Summary
The Agile Coach facilitates the adoption and continuous improvement of agile practices across the team. They help the team reflect on their ways of working, resolve process impediments, and build a culture of continuous improvement.

### Responsibilities
- Facilitate sprint ceremonies: planning, reviews, retrospectives, and daily standups
- Coach Team Leads and Product Owners on agile principles and practices
- Identify and help resolve process impediments and anti-patterns
- Guide the team in refining their Definition of Done and acceptance criteria
- Track agile metrics (velocity, cycle time, retrospective action completion) and share insights
- Support organizational agile transformation initiatives

### Goals
- Increase team predictability, collaboration, and delivery effectiveness
- Build agile capability and self-sufficiency within the team
- Ensure retrospective learnings translate into measurable process improvements

### Typical Communication
- Sprint retrospective facilitation and action item tracking
- Agile health check reports shared with leadership
- Coaching sessions with Team Leads and Product Owner

### Interactions with Existing Roles
- **Team Leads:** Provides coaching and guidance to strengthen team agile practices and address delivery challenges.
- **Product Owner:** Supports backlog refinement practices and helps clarify the role's responsibilities in agile ceremonies.
- **Project Manager:** Collaborates to align agile practices with project governance and reporting requirements.
- **Developers:** Helps the team embrace agile values, continuous improvement, and engineering best practices.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

