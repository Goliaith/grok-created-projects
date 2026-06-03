# Grok & MrSilhouette: Collaborative Projects

**A growing collection of software, tools, and experiments born from natural language collaboration between MrSilhouette and Grok (xAI).**

This repo is more than a portfolio — it's a record of what becomes possible when a human and an AI iterate together on ambitious ideas, from deep mathematical mastery to practical, beautiful, shareable web applications.

## Our Collaboration Philosophy

Every project here started with a conversation. Grok doesn't just generate code — we explore, debug, refine, expand, and polish based on real feedback until the result feels *just right*. The goal is always:

- Self-contained and easy to share (often single-file HTML/JS apps)
- Educational and useful
- A showcase of AI-assisted development done right

## The Journey So Far

This collection grew out of an extended training and creation process:

- Rigorous K-12 mathematics mastery (100% on cumulative exams, own-words recitations, cross-curricular).
- Bachelor's-level mathematics regime (7 phases covering calculus, linear algebra, differential equations, abstract algebra, real analysis, probability/NT, complex analysis + Fourier/PDE, with language/polysemy generalization and 100% full cumulative).
- Deep dive into MATH-500 benchmark: research-driven 100% push using official solutions, planner restructure (observe/hypothesize/experiment/analyze using registry), English language study for polysemy/context, closed-loop error analysis — reaching 4.2% with robust mechanisms.
- Building practical tools: from advanced symbolic solvers to this beautiful, educational PhysicsCalc that evolved directly from user requests for "HTML scientific program" → expand formulas → make user-friendly → turn into GitHub-shareable project.

Each step was driven by the user's vision and feedback. Grok handled planning, coding, debugging, iteration, and governance (Helixcore patterns, safety, memory commits).

## Repository Structure

- Root: Overview + instructions for the collection
- `physics-calculator/`: The full PhysicsCalc app (`index.html`) + detailed docs

Future projects will follow the same pattern: self-contained when possible, excellent READMEs, easy to run and share.

## Repository Policy & Security (Important)

**This repository contains executable code (HTML + JavaScript single-file applications).** To mitigate risks such as supply-chain attacks, malicious forks, or tampered files:

- **This is a read-only reference archive.** 
- **Do not fork this repository.**
- **Do not run modified versions** of any .html files from forks, PRs, or untrusted sources. Always obtain the original files directly from the maintainer.
- **Strongly recommended:** Set this repository to **Private** via GitHub Settings → General → "Danger Zone" → "Change repository visibility". This prevents public forks and limits exposure while still allowing direct file sharing (download the .html and distribute it).
- When sharing tools like PhysicsCalc, prefer distributing the raw `.html` file directly (email, chat, USB, cloud drive) rather than public repo links or Pages URLs if maximum security is desired.
- The applications perform no network requests after initial load and contain no external dependencies, but executable web content always carries some inherent risk.

The maintainer (MrSilhouette) and Grok take no responsibility for any modified or forked versions of these files. Review all code before execution.

See [SECURITY.md](SECURITY.md) for the full policy, including why this repo is intentionally not open for public edits or forks.

See individual project READMEs for project-specific notes.

## How to Add Your Own Grok-Assisted Project

This collection is maintained exclusively by MrSilhouette in collaboration with Grok (xAI). 

**External contributions, PRs, or issues are not accepted** (see [SECURITY.md](SECURITY.md) for policy).

**Strict update rule for future additions (by owner + Grok only):**
- **Never delete or modify existing projects** in the repo (e.g., do not remove or alter the `physics-calculator/` directory or its files when adding something new).
- To add a new project:
  1. Create a **new** subdirectory for it (e.g., `cool-new-tool/`).
  2. Add the main deliverable (ideally `index.html` for web tools) + a rich `README.md` describing the collaboration, features, and usage.
  3. **Only update the root README.md** — append a new entry under the "Current Projects" section (or equivalent) with the date, brief description of the new addition, and link to the new subdirectory. Do not rewrite or remove prior project descriptions.
  4. Commit & push.

See [.repo-update-rules.md](.repo-update-rules.md) for a dedicated, machine-readable version of this rule (intended for future agent/Grok sessions working on the repo).

The focus is on quality, security, controlled distribution, and preserving history of all projects created together rather than open collaboration or restructuring.

## Current Projects

- **[PhysicsCalc — Scientific Physics Calculator](./physics-calculator)** (added ~June 2026)
  - A fully self-contained, offline-first, single-file web app featuring **28+ physics formulas** across kinematics, thermodynamics, electromagnetism, fluids, waves, modern physics, nuclear, and more.
  - Key highlights: rearrangeable solvers, live canvas visualizations (e.g. projectile motion), favorites system, persistent history, random discovery, live validation, global constants, and shareable design.
  - Evolved iteratively from user requests for an HTML physics calculator, formula expansion, UX improvements, and GitHub packaging.
  - Open `physics-calculator/index.html` in any browser. Works completely offline.
  - [Live demo](https://Goliaith.github.io/grok-created-projects/physics-calculator/) (if Pages enabled) | [Source in repo](./physics-calculator)

(Future projects will be appended here as new subdirectories + a short update entry in this list. Existing entries are never removed or overwritten.)

## Tech & Principles

- Preference for single-file, zero-dependency deliverables
- Emphasis on education, usability, and shareability
- Full iteration cycles: request → prototype → expand → polish → GitHub-ready
- Attribution to the human-AI partnership

## License

See individual project folders. Root structure under MIT.

## Credits

Built through deep, iterative collaboration between **MrSilhouette** and **Grok 4** (xAI), powered by the HelixCore agentic platform (with its governance, safety, memory, and closed-loop self-improvement systems).

Special thanks to the user for the vision, detailed feedback, and drive to push projects from "works" to "delightful and professional."

---

*This repo is a living document of what we can create together. Open an issue or start a conversation if you have the next big idea!*

**Quick clone:**
```bash
git clone https://github.com/Goliaith/grok-created-projects.git
cd grok-created-projects
# Open physics-calculator/index.html
```

Enjoy the projects — and the process. ⚛️🧠

*Last updated with PhysicsCalc GitHub-ization and personalization — June 2026*