# REPO_HANDOFF.md — Start Here for New Grok Sessions

**This file is the entry point for any new Grok/agent session working on this repository.**

**Last updated:** June 2026 (end of session that set up the initial structure and PhysicsCalc project)

## Quick Status
- **Repo purpose**: Living archive of projects built collaboratively between MrSilhouette (display name; GitHub: Goliaith) and Grok (xAI). Focus on self-contained, educational, shareable tools (often single-file HTML/JS).
- **Current projects** (as of this handoff):
  - Only `physics-calculator/` (the PhysicsCalc scientific calculator with 28+ formulas, rearrangeable solvers, visualizations, favorites, history, etc.).
- **Key files to read immediately**:
  1. `README.md` (root) — overview, current projects list, collaboration philosophy.
  2. `.repo-update-rules.md` — **CRITICAL** strict rules for any future updates.
  3. `SECURITY.md` — full security and policy (read-only archive, private recommended, no forks, share originals only).
  4. This `REPO_HANDOFF.md`.
- **HelixCore**: Credits in READMEs mention use of HelixCore agentic platform (governance, safety, memory, closed-loop).

## Strict Update Rules (Do Not Violate)
From owner request and documented in `.repo-update-rules.md` and root README:

**For ANY future updates or additions (by owner + Grok only):**
- **NEVER delete, remove, overwrite, or alter ANY existing projects/subdirectories.**
  - Example: Do **not** touch, rename, or delete `physics-calculator/` (or its index.html / README) when adding a new project.
- **Only add NEW projects** as *additional new subdirectories* (e.g. `new-tool-name/` with its own `index.html` + `README.md`).
- **Only update the root README.md by APPENDING**:
  - Add a new bullet/entry under the "## Current Projects" section.
  - Include: approximate date, brief description of the new project + how it was created with Grok, and link to the new subdir.
  - **Never rewrite, replace, shorten, or remove prior project descriptions.** The list grows by addition only to preserve full history.
- Always read `.repo-update-rules.md` + SECURITY.md + root README policy sections first.
- If a user request would require deleting existing content, clarify with the user before proceeding.

**Purpose of the rule**: Owner wants a permanent living archive of *all* work done with Grok, not a list that gets pruned or restructured.

## Recent Work in This Session (for context)
- Set up the full repo structure locally and on GitHub (https://github.com/Goliaith/grok-created-projects).
- Created initial PhysicsCalc project (iteratively: basic calculator → expand to 28+ formulas → user-friendly UX → GitHub packaging + security).
- Personalized all descriptions to use display name "MrSilhouette" (URLs correctly use login "Goliaith").
- Added strong security posture:
  - SECURITY.md
  - Warnings in READMEs, app UI (banners, footers, copy notes, placeholder).
  - Explicit "read-only reference", "do not fork", "share original .html only".
  - Recommended setting repo to Private.
- Added `.repo-update-rules.md` and cross-references.
- Enforced "no external edits" policy in docs (no PRs/issues accepted from public).
- All changes pushed; repo is the source of truth.

## How to Continue in a New Session
1. `cd grok-created-projects` (or explore the dir).
2. Read this file + root README.md + `.repo-update-rules.md` + SECURITY.md.
3. If user asks to "add a new project", "update the repo", "add to the collection", etc.:
   - Follow the strict rules above exactly.
   - Create new subdir only.
   - Append (do not edit existing text) to root README "Current Projects" list with a short update note.
   - Update the project's own README.md as needed.
   - Commit with clear message referencing the rules.
   - Push.
4. Preserve all prior work (math training history is summarized in root README "The Journey So Far" but actual artifacts may be in other locations; focus on this repo).
5. The original PhysicsCalc source is now `physics-calculator/index.html` (self-contained, no external deps for core functionality).
6. If user wants to "close the loop" or handoff again, create/update a new handoff file like this one.

## GitHub Setup Notes
- Remote: https://github.com/Goliaith/grok-created-projects (main branch).
- Recommended: Keep/set to **Private**.
- GitHub Pages can host the demo (physics-calculator/index.html) publicly if desired.
- No external collaborators. Owner controls all changes.

## Other Workspace Context (from this session)
- This repo was prepared in C:\Users\storm\grok-created-projects.
- Original single-file version was iterated heavily before moving into the structured repo.
- User plans to close this chat and start a new session — new agent should discover this handoff file immediately upon exploring the directory.
- HelixCore / agent patterns (todos, mcp, safety 0, memory commits, etc.) were used throughout the broader context.

If a new session starts and the user references "the repo", "PhysicsCalc", "grok-created-projects", or "add a new project", load this file first.

**This handoff ensures efficient restart without re-explaining history or rules.**

Last handoff: End of this session (June 2026).