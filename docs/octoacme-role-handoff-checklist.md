# OctoAcme Role Handoff Checklist

This checklist captures the key handoffs between roles as a project moves through the OctoAcme lifecycle. Use it to ensure nothing falls through the cracks when work transitions from one function to another.

> **How to use:** At each handoff point, the outgoing role confirms all items are complete and the receiving role acknowledges readiness before work proceeds. Mark each item ✅ when done.

---

## Handoff 1: Initiation → Planning
**From:** PM + PdM · **To:** BA + UX Designer + Engineering Manager

| # | Item | Owner |
|---|---|---|
| 1 | Project One-pager / Charter is approved by Stakeholders | PM |
| 2 | Problem statement and success metrics are documented | PdM |
| 3 | Initial stakeholder list is complete and roles confirmed | PM |
| 4 | High-level timeline and milestone targets are set | PM |
| 5 | Technical feasibility assessment is complete | Engineering Manager |
| 6 | Security requirements and threat surface identified | Security Champion |
| 7 | Discovery brief is handed to UX Designer | PdM |
| 8 | BA kickoff meeting is scheduled with PdM and PM | BA |

---

## Handoff 2: PdM → UX Designer (Discovery to Design)
**From:** Product Manager (PdM) · **To:** UX/UI Designer

| # | Item | Owner |
|---|---|---|
| 1 | Problem statement and target user personas are documented | PdM |
| 2 | User research goals and constraints are agreed | PdM + UX Designer |
| 3 | Competitive or benchmark reference materials are shared | PdM |
| 4 | Design success criteria (usability goals) are defined | PdM + UX Designer |
| 5 | Access to design tools and brand assets confirmed | UX Designer |
| 6 | Design review schedule is agreed with PdM and Developers | UX Designer |

---

## Handoff 3: UX Designer → BA (Design to Requirements)
**From:** UX/UI Designer · **To:** Business Analyst

| # | Item | Owner |
|---|---|---|
| 1 | Approved wireframes / prototypes are shared with BA | UX Designer |
| 2 | Key user flows and edge cases are documented | UX Designer |
| 3 | Design constraints and assumptions are noted | UX Designer |
| 4 | BA has reviewed designs and asked clarifying questions | BA |
| 5 | Acceptance criteria drafts reference specific design screens | BA |

---

## Handoff 4: BA → Developers + QA (Requirements to Development)
**From:** Business Analyst · **To:** Developers + QA Lead

| # | Item | Owner |
|---|---|---|
| 1 | User stories are written in agreed format (As a / I want / So that) | BA |
| 2 | Acceptance criteria are unambiguous and testable | BA |
| 3 | Non-functional requirements (performance, security, accessibility) documented | BA |
| 4 | Stories are estimated and sprint-ready (Definition of Ready met) | Developers + BA |
| 5 | QA Lead has reviewed acceptance criteria and confirmed testability | QA Lead |
| 6 | Design specs are linked to corresponding stories | UX Designer |
| 7 | Story walkthroughs completed with the development team | BA |

---

## Handoff 5: Developers → QA (Development to Testing)
**From:** Developers · **To:** QA / QA Lead

| # | Item | Owner |
|---|---|---|
| 1 | Feature is deployed to test environment | Developers |
| 2 | Unit and integration tests are passing | Developers |
| 3 | PR is merged and CI pipeline is green | Developers |
| 4 | Developer smoke test confirms feature is functional end-to-end | Developers |
| 5 | Known issues / deferred items are documented in defect tracker | Developers |
| 6 | QA Lead is notified and test environment access confirmed | QA Lead |
| 7 | Security scans in CI are passing (no critical/high findings) | Security Champion |

---

## Handoff 6: QA → PM + SRE/Release Manager (Testing to Release)
**From:** QA Lead · **To:** PM + SRE/Release Manager

| # | Item | Owner |
|---|---|---|
| 1 | All planned test cases executed; results documented | QA Lead |
| 2 | All critical and high defects are resolved or risk-accepted | QA Lead + PM |
| 3 | UAT completed and signed off by Stakeholders | BA + PM |
| 4 | Release readiness report shared with PM and SRE | QA Lead |
| 5 | Regression test suite passed on release candidate | QA Lead |
| 6 | Definition of Done verified for all stories in release scope | QA Lead |

---

## Handoff 7: PM + SRE → Production (Go/No-Go to Deploy)
**From:** PM + QA Lead + SRE/Release Manager · **To:** SRE/Release Manager

| # | Item | Owner |
|---|---|---|
| 1 | Go/no-go decision recorded (date, attendees, outcome) | PM |
| 2 | Deployment runbook reviewed and validated | SRE/Release Manager |
| 3 | Rollback plan is documented and rehearsed | SRE/Release Manager |
| 4 | Monitoring dashboards and alerts are confirmed active | SRE/Release Manager |
| 5 | On-call rotation is confirmed for post-deploy window | SRE/Release Manager |
| 6 | Support team briefed on changes and known issues | Support/CS Liaison |
| 7 | Release communications drafted and queued | PM + Support/CS Liaison |

---

## Handoff 8: Release → Retrospective (Post-Deploy to Close)
**From:** PM + SRE/Release Manager · **To:** Scrum Master + PM

| # | Item | Owner |
|---|---|---|
| 1 | Post-deploy verification complete; all checks passed | QA Lead + SRE |
| 2 | Release announcement sent to Stakeholders | PM + Support/CS Liaison |
| 3 | Production metrics and SLO compliance confirmed (24–48 h window) | SRE/Release Manager |
| 4 | Any production incidents documented with root cause | SRE/Release Manager |
| 5 | Retrospective is scheduled within one sprint of release | Scrum Master |
| 6 | Outcome metrics collected and shared with PdM | PM + Support/CS Liaison |

---

## Notes on combining roles

On smaller teams, roles are often combined. When that happens:
- **PM + Scrum Master**: Ensure impediment tracking and status reporting are explicitly owned.
- **BA + PdM**: Confirm acceptance criteria receive dedicated review before sprint start.
- **QA + QA Lead**: One person makes all release readiness calls — document this explicitly in the RACI.
- **SRE + Developer**: Separate deployment approval from the developer who wrote the code to preserve a check-and-balance.

---

*See also: [Roles and Personas](./octoacme-roles-and-personas.md) · [RACI Responsibility Matrix](./octoacme-raci-matrix.md)*
