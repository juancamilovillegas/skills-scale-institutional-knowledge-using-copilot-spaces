# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

See also:
- [RACI Responsibility Matrix](./octoacme-raci-matrix.md) — who is Responsible, Accountable, Consulted, or Informed at each lifecycle phase.
- [Role Handoff Checklist](./octoacme-role-handoff-checklist.md) — step-by-step handoffs between roles across the project lifecycle.

---

## Table of Contents

1. [Developers](#developers)
2. [Product Managers (PdM)](#product-managers-pdm)
3. [Project Managers (PM)](#project-managers-pm)
4. [QA / Testing](#qa--testing)
5. [Stakeholders](#stakeholders)
6. [Scrum Master / Delivery Lead](#scrum-master--delivery-lead)
7. [UX/UI Designer](#uxui-designer)
8. [Business Analyst](#business-analyst)
9. [QA Lead / Test Lead](#qa-lead--test-lead)
10. [Engineering Manager / Tech Lead](#engineering-manager--tech-lead)
11. [SRE / Release Manager](#sre--release-manager)
12. [Security Champion](#security-champion)
13. [Support / Customer Success Liaison](#support--customer-success-liaison)
14. [How these personas are used in the exercise](#how-these-personas-are-used-in-the-exercise)

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

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Consult on feasibility and technical constraints with PM and PdM |
| Planning | Estimate stories with BA and PdM; align on Definition of Done with QA Lead |
| Execution | Collaborate with UX Designer on design handoff; pair with Security Champion on secure coding; raise blockers to Scrum Master |
| Release | Coordinate deployment steps with SRE/Release Manager; support smoke tests with QA Lead |
| Retrospective | Surface improvement ideas with PM and Scrum Master |

---

## Product Managers (PdM)

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

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Define problem statement with PM; socialize vision with Stakeholders; brief UX Designer on discovery goals |
| Planning | Groom backlog with BA; review designs with UX Designer; confirm acceptance criteria with QA Lead |
| Execution | Answer scope questions raised by Developers and BA; review demos with Stakeholders |
| Release | Approve release notes and stakeholder communications; confirm success metrics with Support/CS Liaison |
| Retrospective | Evaluate outcome metrics with PM; feed learnings back into roadmap |

---

## Project Managers (PM)

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

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Co-author Project One-pager with PdM; identify Stakeholders; confirm Engineering Manager for staffing |
| Planning | Set milestones with Engineering Manager; align on dependency map with BA and SRE/Release Manager |
| Execution | Escalate impediments surfaced by Scrum Master; track risks with Security Champion; run status updates for Stakeholders |
| Release | Coordinate go/no-go decision with QA Lead and SRE/Release Manager; communicate release to Support/CS Liaison |
| Retrospective | Facilitate retrospective with Scrum Master; track action items to closure |

---

## QA / Testing

### Role Summary
QA / Testing team members validate that features meet acceptance criteria and quality standards. They partner with Developers and the QA Lead to build quality in throughout the lifecycle rather than testing at the end.

### Responsibilities
- Write and execute test cases aligned to acceptance criteria
- Perform exploratory, regression, and integration testing
- Triage and document defects with clear reproduction steps
- Participate in sprint reviews and pre-release verification
- Contribute to the Definition of Done

### Goals
- Catch defects as early as possible in the lifecycle
- Ensure the product meets acceptance criteria before release
- Reduce regression risk through systematic test coverage

### Typical Communication
- Defect reports and test result summaries
- Sprint review participation and UAT coordination with Stakeholders
- Close collaboration with Developers on bug resolution

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Review problem statement for testability concerns |
| Planning | Collaborate with QA Lead to define test strategy; review acceptance criteria with BA |
| Execution | Execute tests daily; raise blockers to Scrum Master; verify fixes with Developers |
| Release | Run release regression and smoke tests; report readiness to QA Lead and PM |
| Retrospective | Report on defect trends; suggest process improvements |

---

## Stakeholders

### Role Summary
Stakeholders are business owners, sponsors, or users who have a vested interest in project outcomes. They provide strategic direction, approve scope and budget, and validate that delivered solutions meet business needs.

### Responsibilities
- Provide business context, priorities, and constraints
- Review and approve project scope and key decisions
- Participate in User Acceptance Testing (UAT)
- Receive and act on regular project status updates
- Escalate issues to executive sponsors when needed

### Goals
- Ensure the project delivers measurable business value
- Stay informed on progress, risks, and scope changes
- Provide timely feedback and approvals to avoid blockers

### Typical Communication
- Monthly (or milestone-based) status briefings from PM
- UAT participation during Execution and pre-release phases
- Ad-hoc escalation for major scope or budget decisions

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Align on problem statement and success metrics with PdM and PM; approve Project One-pager |
| Planning | Review roadmap and release timeline; flag business constraints to PM |
| Execution | Participate in demos and UAT facilitated by PdM and BA |
| Release | Receive release announcements from PM and Support/CS Liaison; validate business outcomes |
| Retrospective | Provide business outcome feedback to PdM and PM |

---

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master (or Delivery Lead in non-Scrum contexts) is accountable for the team's adoption of agile practices and the health of delivery ceremonies. They protect the team from outside interruptions, remove process impediments, and coach the team toward continuous improvement.

### Responsibilities
- Facilitate agile ceremonies: sprint planning, daily standup, sprint review, and retrospective
- Identify and actively remove process impediments that block the team
- Coach the team on agile principles and practices
- Shield the team from unplanned scope additions and context switching
- Track team health metrics (velocity, cycle time, WIP) and surface trends to PM and Engineering Manager
- Foster a psychologically safe and collaborative team culture

### Goals
- Maximize team flow and predictability
- Drive continuous improvement sprint over sprint
- Ensure ceremonies add value rather than overhead

### Typical Communication
- Daily standups and sprint events
- Impediment log shared with PM and Engineering Manager
- Team health check-ins and retrospective facilitation

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Advise PM on sprint structure and team capacity |
| Planning | Facilitate sprint zero; help Developers and BA decompose stories to sprint-ready size |
| Execution | Run daily standups; escalate impediments to PM and Engineering Manager; protect sprint scope |
| Release | Facilitate release retrospective mini-ceremony; ensure team has capacity for release tasks |
| Retrospective | Facilitate retrospective; own action item tracking with PM |

---

## UX/UI Designer

### Role Summary
UX/UI Designers champion the user experience. They conduct discovery research, create wireframes and prototypes, and produce design specifications that guide development. They are involved from early discovery through design handoff and usability validation.

### Responsibilities
- Conduct user research and synthesize insights into design direction
- Create wireframes, mockups, and interactive prototypes
- Produce and maintain design specifications for Developer handoff
- Collaborate with PdM on user story acceptance criteria related to UX
- Facilitate usability testing and incorporate feedback into designs
- Maintain a shared design system or component library (if applicable)

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by resolving UX ambiguity before development begins
- Ensure design consistency across features and releases

### Typical Communication
- Design reviews with PdM and Developers during Planning and Execution
- Usability testing readouts with Stakeholders
- Handoff notes and annotated specs in the design tool (e.g., Figma)

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Partner with PdM to frame the problem from a user perspective; conduct initial discovery |
| Planning | Deliver wireframes and prototypes for backlog stories; review designs with BA for acceptance criteria alignment |
| Execution | Provide design clarifications to Developers during implementation; conduct design QA with QA team |
| Release | Review release-ready UI against design specs; support UAT facilitation with Stakeholders |
| Retrospective | Collect usability feedback loops from Support/CS Liaison to inform future design iterations |

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical delivery. They capture, analyze, and document requirements, translate stakeholder needs into actionable user stories, and ensure acceptance criteria are clear before development begins.

### Responsibilities
- Elicit and document functional and non-functional requirements
- Write and refine user stories with clear acceptance criteria
- Facilitate backlog grooming sessions with PdM and Developers
- Map current and future business processes to identify gaps
- Manage requirements traceability to ensure all needs are addressed
- Support UAT planning and execution with QA and Stakeholders

### Goals
- Eliminate ambiguity in requirements before Execution begins
- Ensure stories are sprint-ready with testable acceptance criteria
- Maintain requirements alignment between business and technical teams

### Typical Communication
- Backlog grooming sessions with PdM and Scrum Master
- Requirements walkthroughs with Developers and QA
- Requirements status updates to PM

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Document problem statement and initial scope with PM and PdM; identify stakeholder needs |
| Planning | Write user stories and acceptance criteria; collaborate with UX Designer on experience requirements; refine estimates with Developers |
| Execution | Clarify requirements for Developers in real time; review in-progress work against acceptance criteria |
| Release | Support UAT coordination with QA Lead and Stakeholders; validate release scope completeness |
| Retrospective | Document requirements gaps or ambiguities that caused rework; propose process improvements |

---

## QA Lead / Test Lead

### Role Summary
The QA Lead owns the overall test strategy, quality standards, and release readiness for the project. They lead the QA team, coordinate test planning, track quality metrics, and serve as the authoritative voice on whether a release meets the bar for production.

### Responsibilities
- Define and maintain the test strategy (scope, approach, tools, environments)
- Set and track quality metrics (defect density, test coverage, escape rate)
- Lead defect triage and prioritization with Developers and PM
- Coordinate User Acceptance Testing (UAT) with Stakeholders and BA
- Make the release readiness recommendation to PM and SRE/Release Manager
- Mentor and guide QA team members

### Goals
- Ensure releases meet quality standards before reaching production
- Build quality in early through shift-left testing practices
- Provide data-driven quality metrics to inform PM and PdM decisions

### Typical Communication
- Test plan and strategy docs shared with PM and Developers
- Quality metrics dashboards reviewed with PM and PdM
- Release readiness reports to PM and SRE/Release Manager

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Review project scope for testing complexity and risk with PM |
| Planning | Publish test strategy; define Definition of Done with Developers and BA; estimate QA effort |
| Execution | Track defect trends; coordinate bug fixes with Developers; escalate quality blockers to PM |
| Release | Sign off on release readiness; coordinate final regression with SRE/Release Manager |
| Retrospective | Report on quality outcomes; drive test process improvement items |

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager (or Tech Lead on smaller teams) provides technical direction, manages engineering capacity and staffing, and ensures the team has the skills and architecture guidance to deliver. They partner closely with PM on planning and with Developers on technical risk.

### Responsibilities
- Set technical direction and review architectural decisions
- Manage staffing, skill gaps, and Developer onboarding
- Identify and mitigate technical risks and dependencies
- Conduct or oversee code review standards and engineering practices
- Partner with Security Champion on secure design and threat modeling
- Represent engineering in cross-functional planning and escalation meetings

### Goals
- Enable the team to deliver with high quality and low technical debt
- Maintain a healthy, skilled, and well-structured engineering team
- Reduce technical risk through proactive architecture and review practices

### Typical Communication
- Technical design reviews and architecture decision records (ADRs)
- Engineering capacity updates to PM
- One-on-ones with Developers and cross-functional syncs with PdM

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Assess technical feasibility with PdM and PM; flag architecture concerns early |
| Planning | Define technical milestones; identify cross-team dependencies with PM; scope security review with Security Champion |
| Execution | Unblock Developers on technical decisions; review critical PRs; monitor technical debt |
| Release | Approve technical readiness with QA Lead and SRE/Release Manager |
| Retrospective | Identify engineering process improvements with Scrum Master |

---

## SRE / Release Manager

### Role Summary
The SRE (Site Reliability Engineer) or Release Manager owns deployment readiness, infrastructure reliability, and observability. They ensure that releases can be safely deployed, monitored, and rolled back, and that the production environment remains stable.

### Responsibilities
- Define and maintain the deployment pipeline and release runbooks
- Validate environment readiness (staging and production) before release
- Set and monitor SLOs/SLIs and alerting thresholds
- Coordinate the production deployment with PM, QA Lead, and Developers
- Own the rollback plan and execute it in case of an incident
- Ensure post-deploy observability (dashboards, alerts, on-call rotation)

### Goals
- Enable safe, repeatable, and low-ceremony deployments
- Minimize time to detect and recover from production incidents
- Maintain agreed service reliability targets (SLOs)

### Typical Communication
- Deployment runbooks and release checklists shared with PM and Developers
- Go/no-go status communicated to PM and QA Lead before production push
- Incident reports and post-mortems shared with PM and Stakeholders

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Flag infrastructure or reliability constraints to PM and Engineering Manager |
| Planning | Identify deployment dependencies and environment requirements with PM and Engineering Manager |
| Execution | Validate CI/CD pipeline; collaborate with Security Champion on deployment security checks |
| Release | Lead go/no-go process; execute deployment; own post-deploy verification with QA Lead |
| Retrospective | Present reliability metrics and incident learnings; drive runbook improvements |

---

## Security Champion

### Role Summary
The Security Champion advocates for secure design and development practices within the team. They are a developer or engineer with security expertise who performs security reviews, integrates security checks into the workflow, and serves as the first point of contact for security concerns and incidents.

### Responsibilities
- Conduct threat modeling for new features and architecture changes
- Review code and infrastructure changes for security vulnerabilities
- Ensure security scanning tools are integrated into the CI/CD pipeline
- Serve as the escalation point for security questions from Developers
- Coordinate with Engineering Manager and SRE on security-related incidents
- Track and prioritize security findings in the backlog with PM and PdM

### Goals
- Prevent security vulnerabilities from reaching production
- Build a security-aware engineering culture
- Minimize time to remediate discovered vulnerabilities

### Typical Communication
- Security review findings shared with Engineering Manager and PM
- CI/CD security scan reports reviewed with Developers
- Security incidents communicated to PM and SRE/Release Manager

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Identify security requirements and threat surfaces with Engineering Manager and PdM |
| Planning | Perform threat modeling; add security stories to backlog with BA; align on secure-by-default standards |
| Execution | Review security-sensitive PRs with Developers; validate SAST/DAST scan results |
| Release | Confirm no critical/high security findings are open with QA Lead and PM before release |
| Retrospective | Report on security posture and drive remediation of recurring vulnerability patterns |

---

## Support / Customer Success Liaison

### Role Summary
The Support or Customer Success (CS) Liaison represents the voice of the customer inside the delivery team. They surface real-world customer feedback, communicate upcoming changes to support teams, and ensure the team understands customer impact when making scope and priority decisions.

### Responsibilities
- Gather and synthesize customer feedback to inform PdM's roadmap decisions
- Communicate upcoming releases to support teams so they can prepare
- Track customer-reported bugs and feature requests in the backlog with PM and PdM
- Facilitate customer interviews or beta feedback sessions as needed
- Prepare customer-facing release notes and announcements with PM
- Monitor post-release customer sentiment and escalate issues to PM

### Goals
- Ensure the product team understands and acts on customer needs
- Reduce customer-facing incidents through proactive support enablement
- Close the feedback loop between customers and the product team

### Typical Communication
- Customer feedback summaries shared with PdM and PM
- Release communication drafts coordinated with PM
- Post-release customer sentiment reports to PM and PdM

### Lifecycle Interactions
| Phase | Interactions |
|---|---|
| Initiation | Provide customer context and pain points to PdM to inform the problem statement |
| Planning | Review planned scope and flag customer impact areas to PdM and BA |
| Execution | Participate in demos and provide customer perspective; surface edge cases from real usage |
| Release | Prepare support team and draft release communications with PM |
| Retrospective | Share customer outcome feedback with PdM and PM; feed learnings into the next cycle |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-reference the [RACI Responsibility Matrix](./octoacme-raci-matrix.md) to understand decision rights across roles at each lifecycle phase.
- Use the [Role Handoff Checklist](./octoacme-role-handoff-checklist.md) when onboarding new team members or transitioning work between roles.

