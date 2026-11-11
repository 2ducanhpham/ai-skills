---
name: testing-strategy
description: Design and evaluate unit, integration, end-to-end, regression, and platform testing strategies.
---

# Testing Strategy

## Workflow
1. Understand critical user journeys, domain invariants, interfaces, and failure modes.
2. Inspect existing test framework, conventions, fixtures, CI, and coverage.
3. Choose the lowest test level that reliably verifies each behavior.
4. Prioritize boundary conditions, invalid input, time/date boundaries, concurrency, persistence, and platform differences where relevant.
5. Define test data, deterministic setup, cleanup, and isolation.
6. Separate existing failures from failures introduced by the current change.
7. Report exact commands and actual results.

## Rules
- Never claim tests passed unless they were executed successfully.
- Avoid brittle tests tied to implementation details.
- Do not change production code just to make a test pass without explaining why.
- Do not delete or weaken tests to obtain a green build.
- Treat flaky tests as defects requiring investigation.

## Output
Risk-based test matrix, coverage gaps, recommended test cases, execution evidence, unresolved risks.
