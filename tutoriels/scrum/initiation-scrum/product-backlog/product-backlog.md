# Workshop Technical Sheet — Product Backlog

## Project: Music Platform

A responsive platform for discovering tracks, listening to available audio, and keeping favorites. This backlog is an initial, ordered plan; the Product Owner reorders it as feedback, value, and technical knowledge change.

## 1. Core concepts

- **Product Backlog:** The single, evolving, ordered list of work that may improve the product. The Product Owner owns its ordering and clarity; the team contributes technical insight. It is refined continuously.
- **Story Points:** A relative estimate of the total size of a story, considering effort, complexity, and uncertainty. They compare work items; they are not hours and do not promise a delivery date.
- **Fibonacci estimates (1, 2, 3, 5, 8):** As work grows, uncertainty grows too. The widening gaps discourage false precision. A story estimated above the team's agreed range should be split or refined.
- **MoSCoW:** **Must** is essential for the agreed release; **Should** is important but has a workaround; **Could** is useful if capacity allows; **Won't (this release)** is explicitly deferred. The Must items define the MVP boundary.
- **Definition of Ready (DoR):** Entry check: a story is clear and prepared enough for the team to consider in Sprint Planning.
- **Definition of Done (DoD):** Exit check: shared, mandatory quality conditions for work to count as complete and join the Increment. DoR prepares work; DoD verifies the result.

## 2. Ordered Product Backlog

Story Points are relative team estimates, not hours. Business value is a planning judgment (High / Medium / Low) and can be revised with user feedback. Order is the current proposed sequence within each MoSCoW tier.

| Order | ID | User story | MoSCoW | Business value | Story Points |
|---:|---|---|---|---|---:|
| 1 | MUS-1 | As a listener, I want to browse the available track catalog, in order to discover music to play. | Must | High — enables discovery | 3 |
| 2 | MUS-2 | As a listener, I want to search tracks by title or artist, in order to find a specific track quickly. | Must | High — core discovery | 3 |
| 3 | MUS-3 | As a listener, I want to play and pause an available track, in order to control my listening. | Must | High — core product value | 5 |
| 4 | MUS-4 | As a listener, I want to add and remove tracks from my favorites, in order to return to music I enjoy. | Must | High — personal value and retention | 5 |
| 5 | MUS-5 | As a listener, I want to view my saved favorites, in order to find them again easily. | Must | High — completes favorite flow | 3 |
| 6 | MUS-6 | As a listener, I want to filter tracks by genre, in order to narrow my discovery. | Should | Medium — improves discovery | 3 |
| 7 | MUS-7 | As a listener, I want to create and name playlists, in order to organize tracks by mood or activity. | Should | Medium — deeper organization | 5 |
| 8 | MUS-8 | As a listener, I want track suggestions based on my listening, in order to discover relevant music. | Could | Medium — discovery enhancement | 8 |
| 9 | MUS-9 | As a listener, I want to download tracks for offline playback, in order to listen without a connection. | Won't (this release) | Low for MVP; licensing and storage need investigation | 8 |

### Sprint 1 MVP proposal

Commit to **MUS-1 through MUS-5** only if the team confirms capacity and each story meets the DoR. Together they support the essential flow: browse/search → play/pause → save and revisit favorites. Sprint commitment is decided by the Developers during Sprint Planning; this ordered backlog is not a guarantee of velocity. Track availability, playback rights, and how favorites persist must be confirmed before implementation.

## 3. Definition of Ready (DoR)

A story can be considered for Sprint Planning when every applicable check is satisfied.

| Check | Verifiable criterion |
|---|---|
| User value | Story follows “As a…, I want…, in order to…” and identifies a user benefit. |
| Scope | One clear outcome; boundaries and exclusions are understood. |
| Acceptance criteria | At least two observable, testable conditions, including relevant empty/error states. |
| Dependencies | Required catalog, audio source, account/session behavior, and external dependencies are identified. |
| Design/data | Required screen states and track fields (such as title, artist, audio availability) are known or agreed. |
| Estimate | Team has discussed the story and assigned a Fibonacci estimate from 1, 2, 3, 5, 8. |
| Size | Story is small enough to complete within a Sprint; oversized work is split. |

## 4. Definition of Done (DoD)

A story is Done only when all applicable checks pass.

| Check | Verifiable criterion |
|---|---|
| Acceptance | Every acceptance criterion is demonstrated and passes. |
| Functionality | Browse/search, playback, or favorite behavior works for the agreed cases, including errors and empty results. |
| Data and access | Favorite state follows the agreed persistence and access rules; no user's data is exposed to another user. |
| Responsive and accessible UI | Relevant views work at mobile and desktop widths; controls have labels and visible focus. |
| Quality | Relevant automated checks pass; no known critical defect remains in the story. |
| Integration | Changes are integrated into the shared branch and the increment starts without a blocking error. |
| Review | Code and user-facing changes are reviewed; documentation or help text is updated when needed. |

## 5. Planning note

Story Points are relative and should be calibrated by the actual team. Re-estimate after learning more; do not convert points into hours. Revisit MoSCoW order after Sprint Review feedback and validate audio/catalog rights and persistence assumptions early.
