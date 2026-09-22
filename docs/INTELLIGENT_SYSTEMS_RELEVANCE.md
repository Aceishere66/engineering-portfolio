# Transferable Engineering Relevance

The projects in this portfolio are not presented as previous Formula Student or autonomous-driving implementations.

They demonstrate engineering patterns that transfer to intelligent and autonomous systems.

## Real-time-ish data paths

EDITH Overdrive requires live acquisition, bounded refresh work, caching and separation of hot-path telemetry from slower diagnostics.

Transferable themes:

- sampling cadence
- data freshness
- concurrency
- provider failure
- degraded operation
- performance budgets

## Heterogeneous sensor/device data

EDITH Fit works with data crossing device and provider boundaries.

Transferable themes:

- provenance
- normalization
- synchronization
- authoritative state
- revisioning
- hardware validation
- partial interoperability

## Multimodal research

EDITH Intake studies a pipeline combining IMU, RGB, depth/ToF and temporal evidence.

Transferable themes:

- complementary sensor roles
- confidence-aware fusion
- temporal reasoning
- sensor failure/contradiction handling
- experimental comparison against simpler baselines

## Engineering with AI tools

Aegis research develops structured workflows for using LLMs and coding agents while preserving deterministic policy, explicit scope and test evidence.

Transferable themes:

- complex-system decomposition
- reproducible engineering workflows
- independent review
- documentation/handoff quality
- controlled use of non-deterministic tools

## Current learning gap

This portfolio does not claim equivalent experience in a Formula Student autonomous stack.

Areas to deepen specifically for autonomous vehicles include:

- modern C++ in robotics-style systems
- Linux-first robotics tooling
- localization and state estimation
- path planning
- vehicle control
- simulation
- automotive sensor integration

The value of the existing work is the software/systems foundation from which those domain-specific skills can be developed.
