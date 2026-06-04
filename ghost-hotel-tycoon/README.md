# Ghost Hotel Tycoon — The Spectral Suites

A fully self-contained, offline-first, single-file browser game built through deep iterative collaboration between MrSilhouette and Grok (xAI).

## What It Is
Run a haunted hotel exclusively for ghosts, ghouls, vampires, banshees, and other supernatural guests. 

- **Core gameplay**: Drag-and-drop (or click) to assign guests to rooms. Buy and strategically place upgrades (you can buy multiples to outfit different rooms). Hire staff with unique roles. Perform risky rituals using Essence. Handle random chaotic events — some with real player choices.
- **Systems & depth**: Multiple resources (Ectoplasm, Reputation, Ethereal Essence), guest type synergies/quirks (mixing guests affects satisfaction), staff roles (Bellhop for passive help, Caretaker for event mitigation), per-room upgrade placement for real decisions, hotel growth (new rooms unlock over time).
- **Satisfying loop**: Every "End the Night" is a juicy payoff with a detailed summary modal (Star Guest, per-guest breakdowns, score, funny commentary) + Web Audio ghostly sounds.
- **Goal**: Reach Night 20 with Reputation ≥ 70 to become the **Eternal Host**. Track progress live in the UI. Win screen with final score based on guests served, Essence, perfect nights, and best reputation.
- **Extra features**: Evict problem guests (strategic cost), Codex with achievements + embedded Gamedev Reflections from the build process, persistent save via localStorage.

Open index.html in any modern browser (Edge, Chrome, Firefox, etc.). Works completely offline after first load. No installs, no accounts, pure silly supernatural management fun with real strategy as complexity grows.

## How It Was Built
Started as one of several random app ideas ("Come up with a few ideas for applications to develop. Don't worry about relating them to current project, just think of something random.").

User picked "Ghost Hotel Tycoon" (idea #3).

Then iterated heavily:
- Made it fully self-contained in one HTML file (Tailwind via CDN + vanilla JS + localStorage).
- "Manage the hotel in that one screen" — drag & drop assignment, direct shop, prominent End Night button, live updating UI.
- "Make the game amazing" — gamedev thinking applied: juice on core actions, layered systems, clear feedback.
- "Increase complexity" — added Essence resource, guest synergies, staff roles, choice events, rituals, room unlocking, per-room strategic upgrades.
- "More satisfying" — added concrete goal (Night 20 / Rep 70+), victory screen with score, evict feature, Codex with achievements + permanent Gamedev Reflections section (the learnings from the entire process are now committed inside the game's own memory).
- Feedback loops: User questions ("Are the upgrades meant to only happen once? ... needs not satisfied by upgrades?") led directly to improvements (repeatable upgrades, explicit "Covers:" tags, "Met: XX%" indicators, better matching).

All development happened through conversation. Grok handled design, implementation, iteration, balancing, and embedding the reflections. User drove the vision and specific asks ("make it more satisfying", "increase complexity", "add a goal").

The final result follows the repo's philosophy: self-contained, educational (shows real gamedev iteration), fun, and shareable.

## Usage
1. Open index.html in a browser.
2. Play directly — everything is on one screen.
3. Drag guests onto rooms or click-to-assign.
4. Use the shop, rituals, evict, and End the Night button.
5. Check the Codex (footer button) for achievements and the embedded gamedev learnings.
6. Try to hit the goal for the full satisfying ending.

**Tip**: Hard-refresh (Ctrl+Shift+R) after updates if needed. Start a New Game from the footer to reset.

## Credits & Process
- **MrSilhouette** (human): Vision, feedback, specific requests that shaped every iteration.
- **Grok** (xAI): Full gamedev role — ideation, systems design, UI/UX in one file, balancing, embedding learnings, following strict repo rules.
- Built using HelixCore patterns (todos for tracking, iterative refinement, safety, memory commits).

This is a record of real collaborative creation: from random idea → functional prototype → polished, complex, satisfying game with a clear goal and self-reflective Codex.

## License
MIT (see root).

Enjoy running the worst/best hotel for the dead. The ghosts appreciate your efforts (mostly).

*Added ~June 2026 as part of ongoing MrSilhouette + Grok collaboration.*
