# Project Evidence Matrix

This matrix distinguishes demonstrated engineering work from future/experimental scope.

| Project | Demonstrated evidence | Explicit boundary |
|---|---|---|
| **EDITH Overdrive** | C#/.NET systems architecture, telemetry caching, concurrent refresh control, Windows integrations, automated guardrails, local performance measurement | Desktop performance cockpit; not an automotive real-time system |
| **EDITH Fit** | Health/wearable data normalization, provenance, incremental sync, Room/Supabase, Wear OS protocol, Android physical-device tests | Full paired phone/watch gate was still pending at showcased source snapshot |
| **EDITH Aegis** | Model Lab, role-specific LLM benchmarks, frozen holdout, model routing, agent workflow design, structured handoffs, verification discipline | Public edition excludes operational security-research details |
| **EDITH Intake** | DINOv2/depth model work, temporal signal pipeline, state machine, IMU capture/import tooling, timing-quality auditing, multimodal architecture | Core physical wearable accuracy and end-to-end product hypothesis not yet validated |

## Why this matrix exists

A portfolio becomes less credible when architecture plans, simulations and physical validation are blended together.

The public editions therefore label evidence according to what it actually proves.

Examples:

- an AI model executing locally proves the model integration path, not final product accuracy;
- a simulated power budget supports architecture exploration, not battery-life claims;
- unit tests can prove state-machine behavior, not RF/Bluetooth reliability on a real paired watch;
- a desktop telemetry architecture demonstrates systems-engineering skills, not prior Formula Student experience.

## Transferable themes

Across the four projects, recurring engineering themes include:

- explicit system boundaries
- provenance
- deterministic state where possible
- asynchronous/concurrent execution
- failure handling
- testable interfaces
- real-device validation
- measured evidence over assumed behavior
