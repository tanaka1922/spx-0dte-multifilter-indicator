# Development History (Portfolio Edition)

Last updated: 2026-02-20

## Scope
This document summarizes major revisions that led to the current portfolio release.

## Timeline
- v10: Introduced layered architecture (multi-TF SuperTrend, session gate, quality filters, exits, dashboard).
- v10 final/tuned: Parameter tuning and stability improvements for practical usage.
- v11 cycle: Added deeper diagnostics and multiple session/time handling refinements.
- v11 final3: Reworked NY session boundary logic using timestamp-based daily boundaries.
- v12 concept: Simplified over-constrained signal stack to improve practical signal cadence.
- v12.1: Hardened exit ordering, confirmed-bar signal behavior, and dashboard scope clarity.
- Portfolio v1.0: Client-specific references removed.
- Portfolio page (2026-11): source code removed (client deliverable). Only this history and the README description remain.

## Notes
- Pine table widgets are last-bar UI by design.
- Historical verification should use per-bar debug/Data Window plots.
