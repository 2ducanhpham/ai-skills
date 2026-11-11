---
name: codebase-audit
description: Systematically inspect an unfamiliar repository and produce an evidence-based codebase map and risk report.
---

# Codebase Audit

## Workflow
1. Confirm repository root, branch, working tree status, and project-specific instructions.
2. Inspect manifests, lockfiles, build scripts, CI, tests, source layout, and documentation.
3. Identify application entry points, architectural layers, module ownership, external services, and data stores.
4. Trace important flows end to end where feasible.
5. Inspect error handling, logging, configuration, secrets handling, accessibility, and platform-specific code.
6. Run only safe, non-mutating inspection commands unless execution is approved.
7. Record findings with severity, evidence, impact, and suggested next action.

## Rules
- Audit before proposing broad refactors.
- Never infer that a feature exists solely from a filename.
- Do not expose secret values; report only the presence and location of possible secret exposure.
- Do not modify files, install packages, or run destructive commands during an audit.
- Separate confirmed defects from hypotheses and follow-up questions.

## Output
1. Repository overview
2. Technology and dependency inventory
3. Architecture and module map
4. Key data and execution flows
5. Test/build/CI status (only if actually checked)
6. Risks ranked Critical/High/Medium/Low
7. Recommended next steps
