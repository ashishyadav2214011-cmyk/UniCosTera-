# UniCosTera — Consequence Engine

When a user changes a parameter, Unico. Simulation determines which dependent variables and interactions must be recalculated.

Example:

Mass ↑
→ gravitational field changes
→ applicable orbital/trajectory effects change
→ dependent interactions may change
→ affected state is recalculated

The exact dependency graph is model-specific.

## Rules

1. Do not change unrelated parameters without scientific dependency.
2. Recalculate affected state.
3. Preserve unaffected state where valid.
4. Record the user-originated change.
5. Label approximation or uncertainty when applicable.
6. Do not silently fabricate a consequence.
