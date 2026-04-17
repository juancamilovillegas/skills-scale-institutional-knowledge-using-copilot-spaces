# OctoAcme RACI Responsibility Matrix

This template maps each project lifecycle phase to the roles that are **R**esponsible, **A**ccountable, **C**onsulted, or **I**nformed for key activities. Copy and customize this for each project.

**Key:**
- **R** — Responsible: does the work
- **A** — Accountable: owns the outcome; there should be exactly one **A** per activity
- **C** — Consulted: provides input before or during the activity
- **I** — Informed: receives updates after the activity

> **Roles abbreviation key:**
> PM = Project Manager · PdM = Product Manager · Dev = Developers · QA = QA/Testing ·
> SM = Scrum Master/Delivery Lead · UX = UX/UI Designer · BA = Business Analyst ·
> QL = QA Lead/Test Lead · EM = Engineering Manager/Tech Lead · SRE = SRE/Release Manager ·
> SC = Security Champion · CS = Support/CS Liaison · SH = Stakeholders

---

## Phase 1 — Initiation

| Activity | PM | PdM | Dev | QA | SM | UX | BA | QL | EM | SRE | SC | CS | SH |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Write Project One-pager / Charter | R | C | — | — | C | C | C | — | C | C | C | C | I |
| Define problem statement & success metrics | C | **A** | — | — | — | C | C | — | C | — | — | C | C |
| Identify stakeholders and project sponsors | **A** | C | — | — | — | — | C | — | C | — | — | C | R |
| Assess technical feasibility | C | C | R | — | — | — | — | — | **A** | C | C | — | I |
| Identify security requirements | C | C | — | — | — | — | C | — | C | C | **A** | — | I |
| Stakeholder alignment and charter approval | R | C | — | — | — | — | — | — | I | — | — | I | **A** |

---

## Phase 2 — Planning

| Activity | PM | PdM | Dev | QA | SM | UX | BA | QL | EM | SRE | SC | CS | SH |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Prioritize and groom backlog | C | **A** | C | — | C | C | R | — | C | — | — | C | I |
| Write user stories and acceptance criteria | C | C | C | C | C | C | **A** | C | — | — | C | C | I |
| Create wireframes and prototypes | — | C | C | — | — | **A** | C | — | — | — | — | — | I |
| Define test strategy | C | C | C | R | C | — | C | **A** | C | C | C | — | I |
| Set milestones and release timeline | **A** | C | C | C | C | — | C | C | C | C | — | I | I |
| Identify cross-team dependencies | **A** | C | C | — | C | — | R | — | C | C | — | — | I |
| Threat modeling and security planning | C | C | C | — | — | — | C | — | C | C | **A** | — | I |
| Infrastructure and environment planning | C | — | C | — | — | — | — | C | C | **A** | C | — | I |

---

## Phase 3 — Execution

| Activity | PM | PdM | Dev | QA | SM | UX | BA | QL | EM | SRE | SC | CS | SH |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Implement features | I | I | **A** | — | — | C | C | — | C | — | C | — | — |
| Design handoff and clarification | — | I | R | — | — | **A** | C | — | — | — | — | — | — |
| Code review | — | — | R | — | — | — | — | — | **A** | — | C | — | — |
| Execute test cases | — | — | C | **A** | — | — | C | R | — | — | — | — | — |
| Defect triage and resolution | C | I | R | R | — | — | — | **A** | C | — | — | — | — |
| Facilitate daily standup | I | — | R | R | **A** | R | R | R | I | — | — | — | — |
| Impediment removal | **A** | I | I | I | R | I | I | I | C | I | I | — | — |
| Stakeholder demos and UAT | C | **A** | R | C | — | R | R | C | I | — | — | C | R |
| Security scan review | C | — | C | — | — | — | — | — | C | C | **A** | — | — |
| Status reporting | **A** | C | I | I | C | I | I | I | I | I | I | I | I |

---

## Phase 4 — Release

| Activity | PM | PdM | Dev | QA | SM | UX | BA | QL | EM | SRE | SC | CS | SH |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Go/no-go decision | **A** | C | I | C | I | — | — | R | C | R | C | I | I |
| Production deployment | C | — | C | — | — | — | — | C | C | **A** | C | I | I |
| Post-deploy verification | C | — | C | R | — | — | — | **A** | C | R | — | — | — |
| Release announcement / comms | **A** | C | I | I | — | — | — | I | I | I | I | R | I |
| Rollback execution (if needed) | **A** | I | C | C | I | — | — | C | C | R | C | I | I |
| Update release notes | C | C | C | C | — | — | R | — | — | — | — | **A** | I |

---

## Phase 5 — Retrospective

| Activity | PM | PdM | Dev | QA | SM | UX | BA | QL | EM | SRE | SC | CS | SH |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Facilitate retrospective | C | I | R | R | **A** | R | R | R | R | R | R | I | — |
| Capture and assign action items | **A** | C | C | C | R | C | C | C | C | C | C | C | I |
| Evaluate outcome metrics | C | **A** | I | I | I | I | I | I | I | I | I | C | C |
| Update process documentation | R | C | C | C | C | C | C | C | C | C | C | C | I |

---

## How to use this matrix

1. **Copy this file** into your project folder at the start of each project.
2. **Confirm ownership** for each **A** cell — every activity should have exactly one accountable owner.
3. **Adjust roles** to match your actual team composition (some roles may be combined or omitted on smaller teams).
4. **Review at each phase gate** to keep the matrix accurate as the project evolves.

---

*See also: [Roles and Personas](./octoacme-roles-and-personas.md) · [Role Handoff Checklist](./octoacme-role-handoff-checklist.md)*
