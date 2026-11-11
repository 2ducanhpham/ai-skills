---
name: code-review
description: Perform independent, evidence-based code reviews focused on correctness, regressions, security, and maintainability.
---

# Code Review

## Review priorities
1. Correctness and requirement compliance
2. Data loss, security, privacy, and authorization
3. Regressions and edge cases
4. Error handling and reliability
5. Performance and resource usage
6. Maintainability and consistency
7. Tests and observability

## Workflow
1. Read the task, acceptance criteria, and project instructions.
2. Inspect the complete diff and relevant surrounding code.
3. Trace affected call paths and data contracts.
4. Check tests and run safe targeted checks if authorized.
5. Report only actionable findings with file and line references.

## Finding format
- Severity: Blocker | High | Medium | Low
- Location:
- Problem:
- Impact:
- Reproduction or reasoning:
- Suggested fix:

## Rules
- Do not approve based only on passing tests.
- Do not report style preferences as defects.
- Do not modify the code being reviewed.
- If no findings are found, state review scope and checks performed; do not claim absolute correctness.
