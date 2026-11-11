---
name: technical-planning
description: Turn product goals and architecture decisions into small, dependency-aware engineering tasks.
---

# Technical Planning

## Workflow
1. Restate the objective and measurable outcome.
2. Inspect project documentation and relevant implementation before planning.
3. Identify constraints, dependencies, unknowns, and decisions requiring Tech Lead approval.
4. Split work into small tasks with one clear owner and bounded scope.
5. Define prerequisites, affected areas, acceptance criteria, tests, and rollback considerations.
6. Identify parallelizable tasks and explicitly flag shared-file or shared-resource conflicts.
7. Present the plan for approval before implementation.

## Task format
- ID and title
- Objective
- Context/evidence
- Scope (in/out)
- Dependencies
- Suggested owner/agent
- Files or modules likely affected (mark as estimates until verified)
- Acceptance criteria
- Test/verification plan
- Risks and rollback

## Rules
- Do not invent requirements.
- Do not assign overlapping edits to agents at the same time.
- Keep tasks independently reviewable.
- Do not begin implementation until required approvals are given.
