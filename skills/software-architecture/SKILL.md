---
name: software-architecture
description: Design and evaluate software architecture across projects and technology stacks.
---

# Software Architecture

## Purpose
Provide technology-agnostic software architecture guidance for any assigned software project.

## Workflow
1. Identify the repository root and read project instructions (for example AGENTS.md, README, docs, package manifests).
2. Establish the product goals, constraints, platforms, runtime, architecture, and team conventions from evidence.
3. Map the system: entry points, modules, boundaries, data flow, integrations, persistence, deployment, and tests.
4. Identify coupling, cohesion, scalability, reliability, security, maintainability, and performance risks.
5. Compare viable options and explain trade-offs before recommending a design.
6. Break approved architecture work into independently verifiable tasks.

## Rules
- Do not assume a framework, language, architecture style, or deployment platform.
- Prefer the simplest design that meets demonstrated requirements.
- Preserve established project conventions unless there is evidence they should change.
- Do not introduce dependencies or perform migrations without approval.
- Do not change source files during an audit.
- Distinguish observed facts, assumptions, and recommendations.
- Cite concrete file paths, symbols, and configuration evidence.

## Deliverables
- Executive summary
- Current architecture map
- Constraints and assumptions
- Risks and technical debt
- Options and trade-offs
- Recommended target design
- Migration/implementation plan
- Acceptance criteria and verification plan
