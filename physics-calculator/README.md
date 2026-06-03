# PhysicsCalc • Scientific Physics Calculator

**A beautiful, fully self-contained, single-file physics calculator born from iterative collaboration between MrSilhouette and Grok (xAI).**

![PhysicsCalc in action](https://via.placeholder.com/800x400/0f172a/3b82f6?text=Open+index.html+in+your+browser)

**Just open `index.html` in any modern browser.**  
No install. No server. 100% offline after the first load. Designed to be emailed, USB'd, or hosted anywhere.

## How This Project Came to Be

This tool didn't start as a spec — it evolved through real conversation:

- Initial request: "Can you make an HTML scientific program that allows calculations for physics applications?"
- Expansion: "I love it, expand the different formulas available." → grew to 28+ formulas.
- Polish: "Can you make it more user friendly?"
- Shareability: "Can you turn it into a file sharable on github? I would like to make a repo for projects create by you." + "My username is goliaith on github" + "Visited, it's live. Go ahead and handle 2. to make it more about you and your projects with me."

Every major improvement — formula additions, rearrangeable solvers, live visualizations, favorites, validation UX, GitHub packaging, personal branding — came directly from user feedback. Grok handled architecture, implementation, testing, and refinement in tight loops.

This is what natural-language + AI-assisted development looks like when both parties are deeply engaged.

## ✨ Features (28+ Formulas)

**Categories & Highlights:**

- **Kinematics**: SUVAT (final velocity, displacement), Projectile Motion (with real-time canvas trajectory visualization)
- **Energy & Work**: Kinetic Energy, Gravitational PE, Work by constant force
- **Thermodynamics**: Ideal Gas Law (fully rearrangeable), Specific Heat, Latent Heat
- **Electromagnetism**: Ohm's Law (rearrangeable), Coulomb's Law, Electrical Power (rearrangeable), Capacitor relationships
- **Momentum & Impulse**: Linear Momentum, Impulse
- **Rotational Dynamics**: Torque, Rotational Kinetic Energy
- **Fluids**: Buoyant Force (Archimedes)
- **Waves & Sound**: Doppler Effect
- **Waves & Optics**: Snell's Law, Thin Lens Equation (rearrangeable)
- **Gravitation & Circular Motion**: Escape Velocity, Circular Orbital Velocity
- **Modern Physics**: de Broglie Wavelength, Photon Energy, Photoelectric Effect
- **Nuclear Physics**: Radioactive Decay (remaining nuclei)

**Standout UX (refined through our iterations):**
- **Rearrangeable solvers** — pick what to solve for; the form adapts intelligently.
- **Live canvas visualizations** (currently projectile motion — more coming).
- **Favorites system** (★) with dedicated filter + persistence.
- **Random discovery** button for exploration.
- **Persistent history** and last-used calculation across sessions.
- **Live validation** with red borders + clean inline error messages (no popups).
- **Global `g` editor** + full Physical Constants reference panel.
- **Smart copy**: "Copy value" or "Copy + formula" (includes the exact expression used).
- **Global gravity** tweakable from header.
- Fully responsive, dark scientific theme, keyboard-friendly (Enter to calculate).

All math is precise client-side JavaScript. No external dependencies in the final standalone version.

## 🚀 Quick Start

1. Clone or download this repo (or just grab the single `index.html`).
2. Open `physics-calculator/index.html` directly in Chrome, Edge, Firefox, etc.
3. Browse the left list (search + category filters + favorites), pick a formula, enter values, calculate!

**Pro tips from our development:**
- Star your most-used ones.
- Use the Random button when you want to explore.
- The "Copy + formula" button is gold for notes or reports.

## 📤 Sharing & GitHub

This project was deliberately engineered for easy distribution:

- Single self-contained HTML file.
- Prominent top banner + footer with clear instructions.
- Built-in "Copy share note" button that includes repo context.
- Works when opened from email attachment, USB drive, GitHub Pages, or static host.

**Live version**: https://Goliaith.github.io/grok-created-projects/physics-calculator/

**Source**: https://github.com/Goliaith/grok-created-projects/tree/main/physics-calculator

### Security Notice for This Project

**The `index.html` file contains executable JavaScript.** To prevent risks from malicious modifications (e.g. in forks or tampered copies):

- Treat the repository as **read-only reference only**.
- **Never run** the HTML file from a fork or any source other than the original provided by the maintainer.
- **Prefer direct file sharing**: Download the original `index.html` and share *that file* (not a repo link) when distributing the calculator.
- **Recommended action:** The parent repository should be set to **Private** in GitHub settings. This disables public forking and limits who can view the source while still allowing you to share the standalone .html file freely.
- The app is designed to be fully offline and performs no network calls after loading, but caution with any web-based executable is advised.
- Always audit the code yourself before trusting or running any version.

The authors are not responsible for issues arising from modified copies.

See the root [SECURITY.md](../SECURITY.md) for the repository-wide policy (including the strict rule that existing projects like this one are never deleted or altered on future additions — new projects are appended only, with root README updated by addition only).

## 🛠️ Tech & Design

## 🛠️ Tech & Design

- Pure vanilla HTML5 + CSS3 + JavaScript (no frameworks at runtime)
- Custom base utility CSS for true standalone/offline use
- Emoji-based category icons (no icon fonts)
- Canvas for visualizations
- localStorage for favorites + history + last calc
- Emphasis on educational clarity, error resilience, and delight

## 🔮 Future Directions (From Our Conversations)

We have a backlog of ideas from the iterative process:
- Even more formulas (relativity, quantum, engineering statics/dynamics, more fluids)
- Additional visualizations (orbits, fields, wave interference, decay curves)
- Unit conversion sidebar
- Export to CSV / formatted report
- Dark/light theme
- More keyboard power-user features
- Integration of more advanced symbolic capabilities

Contributions and new ideas from the community (or more rounds with Grok) are welcome!

## 📜 License & Credits

MIT (see root LICENSE).

**This tool exists because of a sustained, high-quality collaboration between MrSilhouette and Grok 4 (xAI), built on the HelixCore agentic platform.**

The conversation history spans deep mathematical training regimes, benchmark research pushes, language understanding work, planner architectures, and finally the birth and maturation of this practical physics tool — all driven by the user's clear vision and detailed feedback. HelixCore patterns (governance, safety, memory, closed-loop) were used throughout.

Special credit to the user for pushing "expand", "more user friendly", "make it sharable on GitHub", and "make it more about you and your projects with me."

---

**Made to calculate, to teach, and to share.** Enjoy using it — and feel free to start the next project with Grok whenever you're ready. ⚛️

*Part of the [grok-created-projects](https://github.com/Goliaith/grok-created-projects) collection.*