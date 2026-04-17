# OctoAcme Project Management Docs

This folder contains the process documentation for how OctoAcme plans, delivers, and continuously improves its projects. It is the single source of truth for project management practices used by all cross-functional teams.

## OctoAcme project management at a glance

OctoAcme follows a structured lifecycle that guides every project from idea to production. Work begins with an **Initiation** phase, where the team writes a lightweight Project One-pager that captures the problem statement, success metrics, stakeholder list, and a high-level timeline. A decision gate confirms stakeholder alignment and team availability before the project moves into **Planning**, where the backlog is prioritized and estimated, the Definition of Done is agreed upon, a release timeline is set, and cross-team dependencies are mapped. This ensures that every team member starts execution with a shared understanding of scope and acceptance criteria.

Day-to-day delivery is managed through the **Execution & Tracking** phase. Teams follow a pull-request workflow (small PRs, linked issues, automated CI checks, and at least one required approval), hold twice-weekly standups to surface blockers, and update the project board continuously. Quality is built in from the start: unit and integration tests accompany new logic, security scans run in CI, and end-to-end smoke tests validate critical flows before each release. When the work is ready to ship, the **Release & Deployment** guide standardizes the steps—staging verification, automated production pipeline, post-deploy checks, and stakeholder announcements—along with a rollback playbook for incidents.

Every project closes with a **Retrospective**. The team reflects on what went well and what could be improved, commits to a small number of high-priority action items, and tracks those items in the backlog to close the improvement loop. This discipline of continuous improvement, combined with data-informed metrics like velocity and burndown, keeps teams healthy and delivery predictable over time.

Clear **roles and communication cadences** underpin all phases. The Project Manager coordinates delivery, schedules, and risk. The Product Manager owns the roadmap and success metrics. Developers, QA, and Stakeholders each have defined responsibilities and communication touchpoints—from daily standups and PR reviews to weekly status updates, monthly stakeholder briefings, and a structured escalation path (Team → PM → Product Lead → Sponsor) for blockers and incidents.

## Docs index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)
- [Release and Deployment](./octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
