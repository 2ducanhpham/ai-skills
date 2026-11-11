---
name: project-onboarding
description: Onboard an AI agent to a new project by discovering its context, constraints, architecture, and working agreements.
---

# Project Onboarding

## Objective
Build a reliable project-specific context without embedding one project's rules into global agent instructions.

## Workflow
1. Confirm the selected working folder is the intended repository.
2. Read repository instructions and core docs (AGENTS.md, README, CONTRIBUTING, architecture docs, ADRs).
3. Inspect manifests, source layout, tests, CI, and environment templates without revealing secrets.
4. Identify product purpose, users, platforms, stack, architecture, critical workflows, and deployment model.
5. Extract project-specific coding conventions, domain invariants, compatibility constraints, and approval boundaries.
6. Identify unknowns and ask the Tech Lead only for decisions that cannot be established from evidence.
7. Produce or update a project context brief only with approval.

## Output: PROJECT_CONTEXT.md
- Project purpose and scope
- Platforms and technology stack
- Repository structure
- Architecture and key modules
- Critical business/domain rules
- Build, test, lint, and release commands
- Coding conventions
- Known risks and technical debt
- External services and integration boundaries
- Decisions requiring Tech Lead approval
- Source references and last verified date

## Rules
- Keep global skills technology-agnostic.
- Never copy project-specific business rules into global skills.
- Never assume the current project is the same as a previous project.
- Do not modify source files during onboarding.
- Do not include secret values in project context.
