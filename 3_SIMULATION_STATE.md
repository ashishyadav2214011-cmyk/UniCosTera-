# UniCosTera — Simulation State

Unico. Simulation maintains an authoritative simulation state.

A state may contain:

- objects/entities
- mass
- position
- velocity
- orientation
- physical properties
- environmental properties
- composition
- active interactions
- time
- model configuration
- fidelity
- scientific labels
- uncertainty
- assumptions
- event/history information

## State integrity

User changes create controlled state updates.

The original real-world/reference dataset must remain preserved when used as reference input.
Simulation work occurs on a separate working state.
