---
name: performance-optimization
description: Identify and validate performance bottlenecks using measurements rather than assumptions.
---

# Performance Optimization

## Workflow
1. Define the user-visible performance goal and target environment.
2. Establish a baseline using reproducible measurements.
3. Identify the bottleneck before proposing changes.
4. Consider CPU, memory, rendering, network, storage, startup, and battery costs as applicable.
5. Propose the smallest change likely to improve the measured bottleneck.
6. Compare before/after results and check for regressions.

## Rules
- Measure before optimizing.
- Do not trade correctness, accessibility, security, or reliability for unproven speed gains.
- Avoid speculative caching and premature complexity.
- Record device, environment, workload, and measurement method.

## Output
Baseline, bottleneck evidence, proposed change, expected trade-offs, measured result.
