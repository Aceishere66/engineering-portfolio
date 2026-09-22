# AI-Assisted Software Engineering

## Position

AI tools are used as engineering multipliers, not as substitutes for requirements, architecture or verification.

A typical workflow is:

```text
problem definition
      ↓
requirements + constraints
      ↓
relevant context selection
      ↓
task decomposition
      ↓
coding / analysis agent
      ↓
build + tests
      ↓
independent review when useful
      ↓
human validation
```

## Skills developed

### Context engineering

Selecting the architecture, files, prior decisions and constraints necessary for an agent to work accurately without flooding it with irrelevant material.

### Task decomposition

Turning a long project objective into independently verifiable slices.

### Model routing

Using different models according to task type, difficulty, latency/cost and review requirements.

### Structured continuation

Maintaining explicit handoff documents so a new model or session can recover project state, decisions, test evidence and remaining work.

### Verification

Treating builds, tests, diffs and platform validation as part of the task rather than trusting a model's completion statement.

### Multi-model review

Where useful, implementation and review are assigned to different models so the second model has an independent opportunity to find regressions, unsupported assumptions or scope violations.

## Human role

The human engineer remains responsible for objectives, architecture, trade-offs, acceptance criteria and the final decision to accept or reject the result.
