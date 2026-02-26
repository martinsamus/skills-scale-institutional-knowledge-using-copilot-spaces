# OctoAcme — RACI Matrix & Decision Log Templates

## Purpose
Provide reusable templates to make ownership explicit across project activities and to maintain a clear record of key decisions. Use these templates throughout the project lifecycle to improve accountability, onboarding, and repeatability.

---

## RACI Matrix

**RACI key:**
- **R** — Responsible: Does the work
- **A** — Accountable: Owns the outcome; approves/signs off
- **C** — Consulted: Provides input before/during
- **I** — Informed: Notified of progress or outcomes

### How to use
Copy the table below into your project documentation and fill in R / A / C / I for each activity. Leave cells blank if a role has no involvement. Add or remove rows to match your project's activities.

### RACI Template

| Activity / Decision | Sponsor / Executive | Product Manager | Project Manager | Business Analyst | UX Designer | Developers | QA Lead | Scrum Master | Customer Support Lead |
|---|---|---|---|---|---|---|---|---|---|
| Project initiation & approval | A | C | R | C | — | — | — | — | — |
| Requirements definition | I | A | C | R | C | C | C | — | C |
| Backlog prioritization | I | A | C | R | C | — | I | I | C |
| UX design & review | — | C | I | C | R/A | C | I | — | I |
| Sprint planning | — | C | I | — | — | R | C | A | — |
| Development & implementation | — | I | I | — | C | R/A | I | — | — |
| Test strategy & execution | — | C | I | — | — | C | R/A | — | — |
| Release readiness sign-off | A | A | R | — | C | C | C | — | C |
| Release communication | I | C | R | — | — | — | I | — | A |
| Post-release retrospective | I | C | R | C | C | C | C | A | C |
| Risk escalation (team-level) | I | I | R | — | — | C | C | A | — |
| Risk escalation (org-level) | A | C | R | — | — | — | — | — | — |
| Major scope change decision | A | R | C | C | I | I | I | — | I |

> **Note:** Tailor this matrix to your project. Not every project uses all roles listed here. See [Roles & Personas](octoacme-roles-and-personas.md) for full role descriptions.

---

## Decision Log

### Purpose
Record key decisions made during the project lifecycle to preserve context, avoid re-litigating settled questions, and support onboarding of new team members.

### When to update
Add an entry whenever a significant decision is made — particularly during initiation, planning, scope changes, or risk response. Reference this log in status updates and retrospectives.

### Decision Log Template

| ID | Date | Decision | Context / Options Considered | Outcome | Decided By | Stakeholders Informed | Linked Doc / Issue |
|---|---|---|---|---|---|---|---|
| DEC-001 | YYYY-MM-DD | _Brief title of the decision_ | _What options were considered and why this was chosen_ | _Final decision and rationale_ | _Name / Role_ | _List of stakeholders notified_ | _Link to issue, PR, or doc_ |
| DEC-002 | | | | | | | |

### Tips
- Use a short, descriptive title in the **Decision** column so the log is scannable.
- Link to the relevant GitHub issue, PR, or meeting notes in **Linked Doc / Issue**.
- Archive resolved decisions rather than deleting them — they provide valuable onboarding context.

---

## Release Readiness Checklist

### Purpose
Confirm that all critical conditions are met before a release is promoted to production. Complete this checklist jointly with the Project Manager, QA Lead, and relevant stakeholders.

> Referenced from: [Release & Deployment Guide](octoacme-release-and-deployment.md)

### Checklist

**Code & Quality**
- [ ] All planned features and fixes merged and deployed to staging
- [ ] All acceptance criteria reviewed and signed off by Product Manager
- [ ] QA Lead sign-off: test strategy executed, no open critical/blocker defects
- [ ] Automated CI pipeline passing (tests, lint, security scans)
- [ ] Regression tests completed for impacted areas

**Documentation & Communication**
- [ ] Release notes drafted and reviewed
- [ ] Customer Support Lead briefed on changes and known issues
- [ ] Internal/external communication drafted (if applicable)
- [ ] User-facing documentation updated (if applicable)

**Operations & Rollback**
- [ ] Deployment window scheduled and stakeholders notified
- [ ] Rollback / mitigation plan documented and reviewed
- [ ] On-call and monitoring coverage confirmed for the release window
- [ ] Smoke test plan prepared for post-deploy verification

**Approvals**
- [ ] Project Manager confirms release readiness
- [ ] Product Manager confirms acceptance criteria met
- [ ] Sponsor/Executive notified (for major releases)

---

## Where These Templates Are Used

| Template | Referenced In |
|---|---|
| RACI Matrix | [Project Initiation](octoacme-project-initiation.md), [Project Planning](octoacme-project-planning.md) |
| Decision Log | [Project Initiation](octoacme-project-initiation.md), [Risk Management & Communication](octoacme-risks-and-communication.md) |
| Release Readiness Checklist | [Release & Deployment Guide](octoacme-release-and-deployment.md) |
