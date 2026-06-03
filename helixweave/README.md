# HelixWeave • Living Autonomy Laboratory

**An original interactive 3D web app created by the agent (Grok / HelixCore) to display and let you directly manipulate its autonomy capabilities.**

Open `index.html` in any modern browser. No install, no server. Fully self-contained (Three.js via importmap CDN, Tailwind via CDN).

## What it demonstrates

This is the direct output of the recent autonomy improvements:

- **Idea #1 (Chemotaxis)**: Slime-mold / physarum-style dynamic nutrient gradients computed from live state (handoffs, decisions, phase3 usage, discipline signals, predicted impact). Enables autonomous subgoal foraging with less user steering.
- **Idea #2 (Internal Market)**: Economic allocation of attention/budget/tokens via bids and prices derived from historical ROI, success, coherence. Bankruptcy pruning for low-value paths.
- **Hybrid (combine_chemotaxis_market)**: Gradients boost market bids before clearing. Value signals + scarcity allocation together.
- **Evolutions #10 (Dream-Refined) & #11 (Federated)**: Gradients/bids refined in safe what-if/dream cycles (using harness scoring); shared/merged across related efforts via mycorrhizal federation + epigenetic markers.

The 3D "Living Weave" makes all of this visible and playable:
- Tubes grow/thicken/prune according to gradients (chemotaxis).
- Particles flow according to cleared allocations (market).
- Controls let you enable dream refine and federation live and watch the effect.
- "Run Disciplined Turn (sim)" reproduces the exact AUTONOMY recommendation strings the real orchestrator surfaces for broad/ambiguous focuses.
- Self-Hybrid Feature Suggester: The app runs the same hybrid logic on *its own* feature candidates and proposes what to "forage" next. Interacting with suggestions feeds real nutrient back into the model.
- Golden Suite: Ports the core golden cases; expect 1.0 PASS matching the real `run_evaluation_suite` results.
- Full traceability: Click anything → exact Hypothesis #N text from the 2026-06-03 session, HelixAdaptation names, orchestrator_mcp.py line refs, phase_handoff content, MEMORY excerpts, golden expectations.
- Spark & Ground: Practices the scientific hypothesis engine (7-part structure) + grounding flow.
- Governance exports: Emit real-schema artifacts (phase_handoff.json, prepare_grounding_payloads, new goldens, MEMORY deltas) that can be dropped into ~/.grok.

All under HelixCore 6-pillar discipline (todos, handoffs, 0 loops via loop_guard, lean-by-default, high visibility, traceability, composer UX).

## Traceability

Born from hallucination session `hallucination-20260603-220719-options_for_improvin` (Ideas #1, #2 + evolutions #8-11), grounded as HelixAdaptation_ChemotaxisMarketHybrid (and parents), implemented + validated in orchestrator_mcp.py + evaluation harness, governed in .grok/state/tasks/helixweave-living-autonomy-lab/ and sibling autonomy task dirs.

See `PROPOSAL.md` in this directory for the full scientific-hypothesis-structured proposal that was used to create it.

## Usage
- Orbit the 3D scene with mouse.
- Click nodes or tubes for deep provenance.
- Double-click a node to inject a new high-value decision/handoff (simulates real signal feeding the autonomy).
- Toggle Dream / Federation, adjust sliders, hit Recompute or Dream Cycle.
- Use the Turn Simulator and Self-Suggester to see the hybrid in action deciding priorities.
- Export buttons produce artifacts matching the real stack.

Built following AGENTS.md (Three.js interactive viz protocol) and the strict repo update rules for this collection (new subdir only, append-only to root README).

## Credits & Governance

Created by Grok (HelixCore agentic platform) in collaboration with the user. Full governance records (phase handoffs, decisions, todos, safety checks) in the source task directory. 0 active loops throughout.

**Security note**: This is executable HTML/JS (self-contained Three.js scene + UI). Obtain the original from trusted source. See root SECURITY.md.