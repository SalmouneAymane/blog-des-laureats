# Workshop Technical Sheet — Product Vision & User Needs

## Project
**Music Platform** — an individual technical project for discovering and listening to music.

## 1. Core concepts

- **Product vision:** A short statement of whom the product serves, what need it addresses, and the value it provides. It guides priorities and keeps the team focused on outcomes.
- **Persona:** A realistic, evidence-informed profile representing a key user group. Goals, habits, and constraints help the team make decisions for real needs rather than for an abstract “user.”
- **User Story:** A small description of desired value from the user's perspective, using: **As a [user], I want [capability], in order to [benefit].** It describes the need, not a technical implementation.
- **Acceptance criteria:** Observable conditions that must be true for a story to be accepted. They make scope clear and allow the team and user to verify the result.
- **Minimum Viable Product (MVP):** The smallest usable product that delivers the main value and lets the team learn from users. Prioritize essential outcomes; defer useful but nonessential features.

## 2. Product vision

**For people who want easy access to music, the Music Platform is a simple, responsive service to discover tracks, listen to them, and keep favorites together. Unlike a static catalog, it connects discovery, playback, and personal selection in one place.**

## 3. Target personas

### Lina — casual listener
- **Context:** Listens on her phone during commutes and breaks; has limited time to find a track.
- **Goals:** Find a song by title or artist, start listening quickly, save tracks she likes.
- **Constraints:** Small screen, short sessions, and little patience for complicated navigation.

### Youssef — music enthusiast
- **Context:** Explores artists and tracks across longer listening sessions; returns to favorite music often.
- **Goals:** Search the catalog, listen without friction, and build a personal set of favorite tracks.
- **Constraints:** Wants predictable playback and easy access to saved tracks; the MVP does not assume paid streaming or licensed commercial catalog access.

## 4. MVP user stories and acceptance criteria

### US1 — Find music
**As a listener, I want to search tracks by title or artist, in order to find music I want to hear.**

- Given a matching title or artist exists, when I submit a search, then matching tracks are displayed.
- Given no track matches, when I submit a search, then I see a clear “no results” message.
- Search results show each track's title and artist.

### US2 — Listen to a track
**As a listener, I want to play and pause a selected track, in order to control my listening.**

- When I select Play on an available track, playback starts and the control changes to Pause.
- When I select Pause during playback, the track stops and can be resumed.
- If a track cannot be played, I see a clear error or unavailable state.

### US3 — Keep favorites
**As a listener, I want to add or remove a track from my favorites, in order to return to music I enjoy.**

- When I add a track to favorites, it appears in my favorites list and is marked as saved.
- When I remove a favorite, it no longer appears in that list and is marked as unsaved.
- The saved state remains available after I leave and return to the favorites view (for the same account/session supported by the MVP).

## 5. MVP boundary

**Included:** searchable track catalog (title and artist), track details in results, play/pause for available audio, add/remove favorites, responsive interface, clear empty/error states.

**Deferred:** recommendations, social sharing, collaborative playlists, comments, messaging, subscriptions/payments, offline listening, and advanced personalization. These can be prioritized after feedback and technical feasibility checks.

## 6. Validation

The MVP is useful when a listener can find a track, play or pause it, and save or remove it from favorites. Acceptance criteria above provide the checks for the first increment. Confirm audio source and persistence constraints with the project scope before implementation.
