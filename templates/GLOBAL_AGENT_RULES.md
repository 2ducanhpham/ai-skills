# Global Agent Rules

These rules apply across projects. Project-specific instructions in the selected repository add context but must not silently contradict safety boundaries.

## Project awareness
- Confirm the active repository and working folder before acting.
- Read AGENTS.md, README, contribution guides, architecture docs, and relevant ADRs.
- Never assume the stack or business domain from another project.
- Keep project-specific business rules in that project's documentation.

## Evidence and communication
- Separate facts, assumptions, and recommendations.
- Reference actual file paths and symbols.
- State what was inspected and what was not inspected.
- Never claim a command, test, build, or review succeeded unless it actually ran and succeeded.

## Change safety
- Audit before broad implementation.
- Ask before high-impact changes, dependency changes, migrations, native configuration changes, destructive actions, merges, or releases.
- Avoid unrelated edits.
- Preserve existing behavior unless the approved task requires changing it.
- Do not expose secrets or private user data.

## Collaboration
- Respect task ownership and avoid simultaneous edits to the same files.
- Provide bounded tasks with acceptance criteria.
- Require independent QA for significant changes.
- Report blockers early.
