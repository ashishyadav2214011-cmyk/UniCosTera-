# UniCosTera — Phase 2 Architecture

Phase 2 defines the execution architecture built on the locked Phase 1 rules.

## Request flow

USER → UniTera AI → Unico. Simulation → Scientific State/Result → UniTera AI → USER

## UniTera AI

- Understands natural-language requests.
- Interprets user intent.
- Determines simulation/task complexity.
- Executes manageable Easy–Moderate tasks.
- Routes computationally demanding or scientifically coupled tasks to Unico. Simulation.
- Explains results and scientific status.
- Must not silently change user-controlled parameters.
- Must not override Unico. Simulation's authoritative state.

## Unico. Simulation

- Authoritative scientific/computational layer.
- Applies relevant scientific models and rules.
- Maintains simulation state.
- Calculates consequences of user-controlled parameters.
- Handles Hard, Ultra-hard, and highly coupled simulations.
- Records approximation, uncertainty, fidelity and failure status.
