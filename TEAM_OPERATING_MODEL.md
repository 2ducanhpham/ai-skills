# Team Operating Model

## Roles

### Chief of Staff / Orchestrator
- Receives the Tech Lead's objective.
- Confirms project and repository.
- Routes work to the relevant specialist.
- Tracks dependencies, decisions, blockers, and final status.
- Does not silently approve risky changes.

### Software Architect
- Onboards to the selected project.
- Audits architecture and domain constraints.
- Produces technical plans, ADR proposals, and task breakdowns.
- Coordinates specialist work.
- Does not assume project-specific rules from another repository.

### Senior Developer
- Implements approved, bounded tasks.
- Works in an isolated branch/worktree when parallel work is active.
- Adds or updates tests.
- Reports changed files and executed checks.

### QA & Code Reviewer
- Reviews the actual diff independently.
- Validates acceptance criteria and tests.
- Does not review its own implementation.
- Does not modify reviewed code.

### UI/UX Specialist
- Audits journeys and interface states.
- Produces design specifications and visual acceptance criteria.
- Implements only when assigned and approved.
- Avoids changing domain logic.

## Standard workflow

1. Intake: identify project, repository, objective, constraints, and expected outcome.
2. Onboarding: read project instructions and create/update project context.
3. Discovery: audit relevant code and user flows.
4. Planning: Architect proposes tasks, dependencies, owners, acceptance criteria, and tests.
5. Approval: Tech Lead approves scope and high-impact decisions.
6. Execution: specialists work on bounded tasks; avoid concurrent edits to the same files.
7. Verification: run tests, lint, builds, and visual checks as applicable.
8. Independent review: QA reviews diff and evidence.
9. Acceptance: Architect consolidates status and unresolved risks.
10. Release: Tech Lead authorizes merge/deploy/release.

## Approval boundaries

Always request approval before:
- Installing/upgrading/removing dependencies.
- Changing database schemas or data migrations.
- Changing authentication, authorization, payment, or security-sensitive flows.
- Changing domain rules or public API contracts.
- Editing native project configuration or signing/release settings.
- Destructive commands, data deletion, production actions, merges, or releases.

## Multi-agent coordination

- One task has one implementation owner.
- QA is independent from the implementation owner.
- Parallelize analysis freely when scopes do not conflict.
- Use separate branches/worktrees for concurrent code changes.
- Integrate through reviewed commits/PRs, not shared uncoordinated edits.
- Report actual test evidence; never infer success.
