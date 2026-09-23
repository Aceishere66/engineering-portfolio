# Simone Ferrari — Engineering Portfolio

**Software Engineering · AI · Intelligent Systems**

I study **Computer, Electronic and Telecommunications Engineering at the University of Parma** and develop personal software and technology projects through **EDITH Dev Studio**, my personal software-development studio for applications, prototypes and technical experimentation.

This repository is the index for a curated set of engineering projects. Full development repositories remain private where they contain personal data, configuration, internal planning or proprietary work; the linked public editions expose representative architecture, code and verification evidence.

## Selected engineering projects

### 1. EDITH Overdrive — Performance Cockpit

**Systems engineering · telemetry · concurrency · performance**

Windows performance cockpit built around low-overhead live telemetry, shared snapshots, asynchronous acquisition, diagnostics, benchmark integration and graceful degradation.

Evidence highlights:

- fast/slow path separation
- TTL-based snapshot reuse
- concurrency control around expensive refreshes
- performance-regression guardrails
- representative C# source
- source revision records 201 passing C# tests

Repository: https://github.com/Aceishere66/EDITH-Overdrive-Showcase

---

### 2. EDITH Fit

**Android · wearable data · synchronization · real-device validation**

Android health/workout platform using Health Connect, Samsung Health, Wear OS, Kotlin coroutines, Room and persistent synchronization.

Evidence highlights:

- source/device provenance preserved through normalization
- incremental synchronization and idempotent state handling
- phone-authoritative Wear OS protocol with monotonic revisions
- physical Android instrumentation
- 8 protocol + 191 app + 34 wear unit tests recorded passing at the showcased source snapshot
- 54 physical-phone instrumented tests recorded passing

Repository: https://github.com/Aceishere66/EDITH-Fit-Showcase

---

### 3. EDITH Aegis — AI Engineering & Model Lab

**LLM evaluation · coding agents · context engineering · multi-model workflows**

Public research subset focused on structured use of LLMs and coding agents.

Evidence highlights:

- task/role-specific model routing
- frozen benchmark holdout
- precommitted acceptance criteria
- evaluation-scorer correction after detecting a methodology flaw
- independent implementation/review workflows
- structured model/session handoffs

A real 12-case critic holdout compared two finalist local models: both reached 12/12 verdict correctness with zero FP/FN, while the selected model achieved 0.9722 evidence recall against 0.8889 for the faster finalist.

Repository: https://github.com/Aceishere66/EDITH-Aegis-Research

---

### 4. EDITH Intake — Multimodal Sensing Research

**Computer vision · IMU · RGB · depth · temporal inference**

Research project exploring event-triggered wearable sensing and multimodal inference.

Evidence highlights:

- local DINOv2 perception experiments
- 72-image multi-prototype reference bank
- Depth Anything V2 Small local execution
- temporal signal-processing pipeline
- 4-state hysteresis intake state machine
- physical-IMU capture/import foundation
- timing/jitter/gap auditing
- strict separation between software/simulation evidence and future physical-product validation

Repository: https://github.com/Aceishere66/EDITH-Intake-Research

---

## Technical profile

### Software engineering

- Python
- C
- C#
- Kotlin / Android
- JavaScript / TypeScript
- Git / GitHub
- SQL
- automated testing
- debugging
- asynchronous and concurrent programming

### Systems and data

- telemetry pipelines
- normalization of heterogeneous data
- synchronization
- state management
- API/device integration
- Windows and Android platform work
- real-hardware validation
- performance-aware architecture

### AI-assisted software engineering

I use LLMs and coding agents inside structured development workflows rather than treating generated code as automatically correct.

Typical practices include:

- explicit requirements and acceptance criteria
- context engineering
- task decomposition
- model selection based on task type
- structured handoffs between models/sessions
- implementation/review separation
- build/test evidence
- human-controlled architecture and final validation

See [AI-assisted engineering](docs/AI_ASSISTED_ENGINEERING.md).

## Relevance to intelligent and autonomous systems

These projects are **not** presented as prior autonomous-driving implementations.

The transferable engineering foundation includes:

- asynchronous/concurrent software
- live telemetry and sensor-data pipelines
- hardware/API integration
- partial-data and failure handling
- performance-sensitive systems
- state synchronization
- automated validation
- multimodal AI research
- reproducible Git-based development

See:

- [Transferable engineering relevance](docs/INTELLIGENT_SYSTEMS_RELEVANCE.md)
- [Project evidence matrix](docs/PROJECT_EVIDENCE_MATRIX.md)

## Additional experience

Other projects include:

- **Upscaler Studio** — local AI multimedia processing with FFmpeg and upscaling models
- **STEAM Lab / Arduino** — earlier prototyping and physical-computing experience
- web/application projects across TypeScript, Python and database-backed systems
- 3D modelling
- video editing

## Website

**Engineering portfolio:** https://edithdevstudio.com/engineering

## Portfolio policy

Every linked repository is a curated showcase/research edition.

The objective is to make representative engineering work inspectable while keeping private:

- personal data
- credentials/configuration
- complete private-product source
- internal planning material
- sensitive research content
