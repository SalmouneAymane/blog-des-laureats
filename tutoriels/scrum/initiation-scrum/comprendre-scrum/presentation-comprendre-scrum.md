---
marp: true
theme: default
paginate: true
header: "T.351.111 — Scrum Agile Governance"
footer: "TaskFlow — Personal Web Task Manager"
---

# Understanding Agile & the Scrum Framework

---

# 1. Paradigm Shift

## V-Model vs. Agile

| Dimension | V-Model / Waterfall | Agile |
| :--- | :--- | :--- |
| Workflow | Linear and sequential | Iterative and incremental |
| Change | Rigid and costly | Welcomed continuously |
| Delivery | One final release | Frequent working increments |
| Risk | Validation occurs late | Issues detected early |

---

# 2. Agile Manifesto

## 4 Values

1. **Individuals and interactions** over processes and tools
2. **Working software** over comprehensive documentation
3. **Customer collaboration** over contract negotiation
4. **Responding to change** over following a plan

---

# 3. Scrum's Empirical Pillars

## Transparency
Everyone shares a clear view of work, progress, and goals.

## Inspection
Artifacts and progress are checked regularly to detect deviations.

## Adaptation
The process or product changes quickly when inspection reveals a problem.

---

# 4. Scrum Roles

| Role | Responsibility |
| :--- | :--- |
| **Product Owner** | Maximizes value, defines the vision, and prioritizes the Product Backlog |
| **Scrum Master** | Coaches Scrum, facilitates events, and removes blockers |
| **Developers** | Design, build, test, and deliver the Increment |

---

# 4. Scrum Roles — TaskFlow

- **Product Owner:** Prioritizes task creation and completion before dark mode or calendar sync
- **Scrum Master:** Keeps Daily Scrums under 15 minutes and removes environment blockers
- **Developers:** Build the database, API, and task-management UI

---

# 5. Scrum Events

| Event | Purpose |
| :--- | :--- |
| **Sprint** | Create a usable Increment in a fixed 1–4 week timebox |
| **Sprint Planning** | Decide why, what, and how for the Sprint |
| **Daily Scrum** | Synchronize progress and adapt the next 24 hours |
| **Sprint Review** | Demonstrate the Increment and gather feedback |
| **Sprint Retrospective** | Improve collaboration and the working process |

---

# 5. Scrum Event Timeboxes

- **Sprint:** 1–4 weeks
- **Sprint Planning:** Maximum 8 hours for a 1-month Sprint
- **Daily Scrum:** 15 minutes every day
- **Sprint Review:** Maximum 4 hours
- **Sprint Retrospective:** Maximum 3 hours

---

# 6. Increment

## A concrete stepping stone toward the Product Goal

- Builds upon all previous Increments
- Must be usable and potentially releasable
- Represents real, inspected progress

---

# 6. Definition of Done

## A formal quality checklist

- Code peer-reviewed
- Unit and feature tests passing
- Responsive UI verified
- Zero critical bugs
- Deployed to staging

**Only work meeting the DoD can be considered complete.**

---

# 7. TaskFlow — Sprint 1

## Product Goal

Deliver a clean, fast web application for organizing daily personal tasks.

## Sprint Goal

> “Allow a user to create, view, and mark tasks as completed.”

---

# 7. TaskFlow — Sprint Backlog

- **US1:** As a user, I can add a task with a title and priority.
- **US2:** As a user, I can view my active tasks in a list.
- **US3:** As a user, I can check off a task as completed.

---

# 7. TaskFlow — Sprint Outcome

At the **Sprint Review**, the team demonstrates:

- A live MVP
- Tasks added and saved in the database
- Tasks toggled from active to completed
- All Definition of Done criteria met

---

# Key Takeaway

> Scrum uses short iterations, regular inspection, and rapid adaptation to deliver valuable software incrementally.
