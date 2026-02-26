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

## UX Designer

### Role Summary
UX Designers are responsible for understanding user needs and translating them into clear, usable experiences. They work across research, wireframing, prototyping, and design handoff to ensure that software is both functional and intuitive.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity mockups
- Document user flows, design rationale, and accessibility considerations
- Collaborate on design handoff with developers to ensure accurate implementation
- Review implemented features for UX fidelity before release

### Goals
- Reduce friction and confusion in the user experience
- Advocate for user needs in product and engineering decisions
- Ensure designs meet accessibility and usability standards

### Typical Communication
- Design reviews and critique sessions
- Figma/design tool comments and annotations
- UX acceptance notes in sprint review and release readiness checks

### Interactions with Existing Roles
- **Developers**: Provide design specifications and assets; review implementations; iterate on feasibility
- **Product Managers**: Align on user problems, personas, and acceptance criteria; co-create feature briefs
- **Project Managers**: Communicate design progress and flag dependencies on research or tooling
- **QA Lead**: Review UI/UX test cases for alignment with design intent

---

## QA Lead

### Role Summary
The QA Lead defines and oversees the quality assurance strategy for the project. They coordinate manual and automated testing efforts to ensure features meet acceptance criteria and performance standards before release.

### Responsibilities
- Define the test strategy, test plan, and testing standards for the project
- Coordinate manual and automated testing across sprints and releases
- Maintain regression test suites and ensure coverage of critical flows
- Validate acceptance criteria with the Product Manager before sign-off
- Communicate quality status and release readiness to the Project Manager
- Document and track defects through to resolution

### Goals
- Ensure software quality meets the Definition of Done before release
- Reduce post-release defects through proactive testing practices
- Improve testing repeatability and automation coverage over time

### Typical Communication
- QA status updates in weekly delivery syncs and sprint reviews
- Defect reports and test result summaries
- Release readiness sign-off to the Project Manager and Product Manager

### Interactions with Existing Roles
- **Developers**: Coordinate on test environments, defect reproduction, and fix verification
- **Product Managers**: Confirm acceptance criteria and participate in feature sign-off
- **Project Managers**: Report quality status, testing timelines, and release readiness (see [Release Readiness Checklist](octoacme-raci-and-decision-log.md#release-readiness-checklist))
- **UX Designer**: Validate UI implementation against design specifications

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical delivery. They analyze problems, document requirements, and help refine the backlog to ensure the team is solving the right problems in the right order.

### Responsibilities
- Elicit, analyze, and document business and functional requirements
- Work with the Product Manager to refine and prioritize the backlog
- Create use cases, process flows, and data models as needed
- Validate that delivered features address the underlying business need
- Support stakeholder communication and change management

### Goals
- Ensure requirements are complete, unambiguous, and traceable
- Reduce rework caused by misunderstood or missing requirements
- Bridge communication between technical and non-technical stakeholders

### Typical Communication
- Requirements documents, use cases, and process diagrams
- Backlog refinement sessions with Product Managers and Developers
- Stakeholder updates and gap analysis reports

### Interactions with Existing Roles
- **Product Managers**: Co-own backlog refinement; provide requirement detail and business context
- **Project Managers**: Align on scope changes, dependencies, and documentation milestones
- **Developers**: Clarify requirements and acceptance criteria during implementation
- **Sponsor/Executive**: Translate business goals into documented requirements and success metrics

---

## Sponsor/Executive

### Role Summary
The Sponsor or Executive champion provides strategic direction, funding, and organizational support for the project. They approve major milestones and help remove blockers that cannot be resolved at the team level.

### Responsibilities
- Approve project initiation, major scope changes, and budget decisions
- Provide strategic guidance and ensure alignment with organizational goals
- Remove organizational-level blockers and prioritization conflicts
- Review and accept milestone deliverables and phase gates
- Communicate project value and progress to senior leadership

### Goals
- Ensure the project delivers measurable business value
- Protect the team from organizational noise and competing priorities
- Make timely decisions that unblock execution

### Typical Communication
- Milestone and phase-gate reviews (not day-to-day)
- Executive status summaries from the Project Manager
- Escalation when team-level or PM-level resolution is insufficient

### Interactions with Existing Roles
- **Project Managers**: Primary point of contact for escalations, milestone approvals, and status reporting (see [RACI Matrix](octoacme-raci-and-decision-log.md#raci-matrix))
- **Product Managers**: Align on roadmap priorities, business outcomes, and go/no-go decisions
- **Developers**: Rarely direct; primarily engaged through milestone demos
- **Business Analyst**: Receives translated requirements and outcome metrics

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master or Agile Coach facilitates agile ceremonies, promotes team health, and coaches the team on agile best practices. They help protect team focus, surface and remove impediments, and drive continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and sprint reviews
- Coach the team on agile practices and help embed a continuous improvement mindset
- Identify and help remove impediments blocking team progress
- Track and report team velocity, capacity, and process health metrics
- Protect the team from scope creep and interruptions during sprints
- Support the Project Manager in maintaining an accurate, up-to-date project board

### Goals
- Enable the team to deliver consistently at a sustainable pace
- Reduce impediments and increase team autonomy
- Foster a culture of transparency and retrospective improvement

### Typical Communication
- Facilitation of all agile ceremonies (standups, planning, retros)
- Impediment logs and process improvement tracking
- Team health and velocity reports to Project Manager

### Interactions with Existing Roles
- **Developers**: Daily facilitation; help unblock and protect focus time
- **Product Managers**: Align on sprint goals and backlog readiness; ensure ceremonies are productive
- **Project Managers**: Share process health and velocity data; coordinate dependency and risk visibility
- **Sponsor/Executive**: Escalate impediments that require organizational intervention

---

## Customer Support Lead

### Role Summary
The Customer Support Lead represents the voice of the customer within the project team. They surface user feedback, communicate upcoming changes to support staff, and coordinate the documentation and training needed to support releases.

### Responsibilities
- Aggregate and communicate customer feedback and pain points to the Product Manager
- Review release notes and feature changes for customer impact
- Coordinate internal support documentation and training for new features
- Represent customer needs in sprint reviews and release readiness discussions
- Track and report on support ticket trends related to in-flight features

### Goals
- Ensure customers have a smooth experience with new and changed features
- Minimize support escalations caused by inadequate documentation or communication
- Bridge the gap between delivery and customer-facing teams

### Typical Communication
- Release previews and change briefings for support staff
- Customer feedback summaries shared with Product Manager
- Post-release support impact report

### Interactions with Existing Roles
- **Product Managers**: Share customer feedback and validate feature usability from a support perspective
- **Developers**: Raise recurring defects or friction points surfaced through support channels
- **Project Managers**: Coordinate release communication timelines and support readiness (see [Release Readiness Checklist](octoacme-raci-and-decision-log.md#release-readiness-checklist))
- **QA Lead**: Align on known issues and workarounds communicated to customers pre-release

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

