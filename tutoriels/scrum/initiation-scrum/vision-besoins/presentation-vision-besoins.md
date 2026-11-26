---
marp: true
theme: default
paginate: true
size: 16:9
---

# Product Vision & User Stories

---

## Why express needs?

- A shared direction helps the team make consistent choices.
- Clear user needs reduce guesswork and unnecessary features.
- Testable outcomes make progress visible to users and the team.

---

## Five useful concepts

- **Product vision:** Who we serve, what problem we solve, and the value we offer.
- **Persona:** A realistic user profile with goals and constraints.
- **User Story:** A small feature described from the user's point of view.
- **Acceptance criteria:** Concrete checks that show when a story is done.
- **MVP:** The smallest usable product that delivers core value and supports learning.

---

## User Story format

> **As a** [type of user], **I want** [capability], **in order to** [benefit].

- Describes the user need and its reason.
- Acceptance criteria clarify what success looks like.
- Example: “As a listener, I want to search by artist, in order to find music I want to hear.”

---

## Product vision

**For people who want easy access to music, the Music Platform is a simple, responsive service to discover tracks, listen to them, and keep favorites together.**

Core value: discovery + playback + personal favorites.

---

## Persona 1 — Lina, casual listener

- Listens on her phone during commutes and breaks.
- Wants to find and play a song quickly.
- Needs simple navigation and clear controls.
- Constraint: short sessions and small screen.

---

## Persona 2 — Youssef, music enthusiast

- Explores music during longer sessions and revisits favorites.
- Wants reliable playback and quick access to saved tracks.
- Constraint: depends on available audio and a responsive catalog.
- MVP does not assume paid streaming or commercial licensing.

---

## Story 1 — Search

**As a listener, I want to search tracks by title or artist, in order to find music I want to hear.**

- Matching query displays tracks with title and artist.
- No match displays a clear “no results” message.

---

## Story 2 — Playback

**As a listener, I want to play and pause a selected track, in order to control my listening.**

- Play starts an available track and shows Pause.
- Pause stops playback; the track can be resumed.
- Unavailable audio produces a clear message.

---

## Story 3 — Favorites

**As a listener, I want to add or remove a track from my favorites, in order to return to music I enjoy.**

- Adding marks the track saved and lists it in favorites.
- Removing clears its saved state and removes it from the list.
- Saved state is retained when returning to favorites.

---

## MVP scope

### Build first

- Search by title or artist
- Play and pause available tracks
- Add/remove favorites
- Responsive screens and clear empty/error states

### Defer

Recommendations · social sharing · collaborative playlists · messaging · subscriptions · offline listening

---

## How we know it works

A listener can find a track, play or pause it, and save or remove it from favorites.

Use acceptance criteria to check each story; collect feedback before expanding the backlog.

