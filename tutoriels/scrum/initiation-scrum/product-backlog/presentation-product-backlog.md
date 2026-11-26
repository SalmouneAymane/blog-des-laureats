---
marp: true
theme: default
paginate: true
size: 16:9
---

# Product Backlog
## Music Platform

---

## Why a Product Backlog?

- One evolving list of product work, ordered by value.
- The Product Owner owns ordering and clarity; the team adds technical insight.
- Refine it as feedback and knowledge change.

---

## Estimate relative size

**Story Points** compare effort, complexity, and uncertainty. They are not hours.

Use Fibonacci: **1 · 2 · 3 · 5 · 8**

Larger work carries more uncertainty, so the scale widens. Split or refine stories that are too large.

---

## Prioritize with MoSCoW

- **Must:** Essential for the agreed release; defines the MVP.
- **Should:** Important, with a workaround.
- **Could:** Useful if capacity allows.
- **Won't this release:** Explicitly deferred.

---

## Ordered backlog — Sprint 1 MVP

| Order | Story | Priority | Value | SP |
|---:|---|---|---|---:|
| 1 | Browse available tracks | Must | High | 3 |
| 2 | Search by title or artist | Must | High | 3 |
| 3 | Play and pause a track | Must | High | 5 |
| 4 | Add/remove favorites | Must | High | 5 |
| 5 | View saved favorites | Must | High | 3 |

---

## Backlog — after the MVP

| Order | Story | Priority | Value | SP |
|---:|---|---|---|---:|
| 6 | Filter tracks by genre | Should | Medium | 3 |
| 7 | Create and name playlists | Should | Medium | 5 |
| 8 | Get personalized suggestions | Could | Medium | 8 |
| 9 | Download for offline playback | Won't this release | Low* | 8 |

*Licensing and storage need investigation. Estimates are relative team estimates, not hours.

---

## Definition of Ready (entry)

Before Sprint Planning, confirm:

- Clear user value and bounded scope
- At least two testable acceptance criteria
- Dependencies and required track data identified
- Needed screen states understood
- Estimated on Fibonacci scale
- Small enough for one Sprint

---

## Definition of Done (exit)

Before a story joins the Increment, confirm:

- Acceptance criteria pass, including relevant edge states
- Feature works and respects agreed data/access rules
- Mobile and desktop layouts work; controls are labeled
- Relevant automated checks pass; no critical defect remains
- Integrated, starts without blocking error, and reviewed

---

## Planning guardrails

- DoR prepares a story; DoD verifies completed work.
- Developers select Sprint scope based on capacity during Sprint Planning.
- Confirm audio availability/rights and favorite persistence early.
- Reorder the backlog using feedback; points do not equal hours.
