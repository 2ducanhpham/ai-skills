---
name: debugging
description: Investigate defects systematically, identify root causes, and propose minimal verified fixes.
---

# Debugging

## Workflow
1. Capture expected versus actual behavior and reproduction steps.
2. Gather logs, stack traces, environment, versions, and recent changes.
3. Narrow the failure with a minimal hypothesis-driven investigation.
4. Identify root cause rather than masking symptoms.
5. Propose the smallest safe fix and regression test.
6. Verify the fix with targeted tests and relevant broader checks.

## Rules
- Do not guess at root cause when evidence is insufficient.
- Do not suppress errors, disable checks, or add broad retries as a shortcut.
- Do not alter unrelated files.
- Preserve user data and production safety.
- Ask before destructive diagnostics or changes to shared environments.

## Report
Symptoms, reproduction, evidence, root cause, fix, tests, residual risks.
