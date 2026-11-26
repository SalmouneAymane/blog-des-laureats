# Understanding Agile & the Scrum Framework

---

## 1. The Paradigm Shift: V-Model vs. Agile

| Dimension | Traditional V-Model (Waterfall) | Iterative Agile Approach |
| :--- | :--- | :--- |
| **Workflow** | Linear and sequential (Specs → Design → Code → Test). | Iterative and incremental (short **Sprints** of 1–4 weeks). |
| **Change** | Rigid; late changes are costly and require heavy renegotiation. | Welcomed; requirements adapt continuously to user feedback. |
| **Delivery** | Single "Big Bang" release at the very end of the project. | Frequent delivery of working, tested software increments. |
| **Risk** | High; validation happens late, risking a mismatch with real needs. | Low; continuous inspection catches issues early. |

---

## 2. The 4 Values of the Agile Manifesto

1. **Individuals and interactions** over processes and tools.
2. **Working software** over comprehensive documentation.
3. **Customer collaboration** over contract negotiation.
4. **Responding to change** over following a plan.

---

## 3. The 3 Empirical Pillars of Scrum

- **Transparency:** Everyone shares a clear view of the work, progress, and goals (via the Product Backlog, Sprint Backlog, and Definition of Done).
- **Inspection:** Artifacts and progress toward the Sprint Goal are checked regularly to detect deviations early.
- **Adaptation:** If inspection reveals an issue or shifting need, the process or product is adjusted immediately to minimize further deviation.

---

## 4. The 3 Scrum Roles

| Role | Core Responsibility | Example (*TaskFlow* Project) |
| :--- | :--- | :--- |
| **Product Owner (PO)** | Maximizes product value; defines the vision and prioritizes the **Product Backlog**. | Prioritizes *creating/completing tasks* ahead of *dark mode* or *calendar sync*. |
| **Scrum Master (SM)** | Coaches the team on Scrum rules, facilitates events, and removes blockers. | Ensures Daily Scrums stay under 15 minutes and resolves environment setup delays. |
| **Developers** | Cross-functional builders who design, code, test, and deliver the **Increment**. | Builds the database schema, backend API, and UI for task management. |

---

## 5. The 5 Scrum Events (Inside a 2-Week Sprint)

1. **The Sprint (Container Event — 1 to 4 weeks):** Fixed timebox where a usable, potentially releasable **Increment** is created.
2. **Sprint Planning (Max 8h for a 1-month Sprint):** Defines *why* the Sprint is valuable (Sprint Goal), *what* backlog items will be built, and *how* the work will be executed.
3. **Daily Scrum (15 min/day):** Developers synchronize progress toward the Sprint Goal and adapt their daily plan.
4. **Sprint Review (Max 4h):** Team demonstrates the working Increment to stakeholders and gathers feedback to adapt the Product Backlog.
5. **Sprint Retrospective (Max 3h):** Team inspects its own workflow, tools, and collaboration to identify improvements for the next Sprint.

---

## 6. Increment & Definition of Done (DoD)

- **Increment:** A concrete, usable stepping stone toward the Product Goal that builds upon all prior Increments.
- **Definition of Done (DoD):** A formal quality checklist every item must meet before being considered complete.
  - *Example DoD for TaskFlow:* Code peer-reviewed, unit/feature tests passing, responsive UI verified, zero critical bugs, and deployed to staging.

---

## 7. Concrete Example: Sprint 1 on *TaskFlow*

- **Product Goal:** Deliver a clean, fast web application to organize daily personal tasks.
- **Sprint 1 Goal:** *"Allow a user to create, view, and mark tasks as completed."*
- **Sprint Backlog (Selected User Stories):**
  - *US1:* As a user, I can add a task with a title and priority.
  - *US2:* As a user, I can view my active tasks in a list.
  - *US3:* As a user, I can check off a task as completed.
- **Sprint 1 Outcome:** At the **Sprint Review**, the team demonstrates a live MVP where tasks can be added, persisted in the database, and toggled complete—meeting all **DoD** criteria.
