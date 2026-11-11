# Global AI Development Team — Skills Pack

Reusable, project-agnostic skills for a multi-project AI engineering team.

## Repository layout

```text
global-ai-development-team/
├── README.md
├── TEAM_OPERATING_MODEL.md
├── templates/
│   ├── GLOBAL_AGENT_RULES.md
│   ├── PROJECT_CONTEXT_TEMPLATE.md
│   └── TASK_TEMPLATE.md
└── skills/
    ├── software-architecture/SKILL.md
    ├── codebase-audit/SKILL.md
    ├── technical-planning/SKILL.md
    ├── architecture-decision-records/SKILL.md
    ├── dependency-risk-audit/SKILL.md
    ├── code-review/SKILL.md
    ├── testing-strategy/SKILL.md
    ├── debugging/SKILL.md
    ├── security-review/SKILL.md
    ├── performance-optimization/SKILL.md
    ├── ui-ux-design/SKILL.md
    ├── documentation/SKILL.md
    └── project-onboarding/SKILL.md
```

## Suggested bot-to-skill mapping

| Agent | Skills |
|---|---|
| Software Architect | software-architecture, codebase-audit, technical-planning, architecture-decision-records, dependency-risk-audit, project-onboarding |
| Senior Developer | debugging, testing-strategy, documentation (plus stack-specific skills added later) |
| QA & Code Reviewer | code-review, testing-strategy, security-review |
| UI/UX Specialist | ui-ux-design, performance-optimization |

Skills are reusable capabilities. Bot instructions define role and authority. Project context belongs in each project's repository, not in this global pack.

## Add a skill in MausBot

Use the GitHub folder URL for an individual skill, not the skill name alone. For example:

`https://github.com/OWNER/REPOSITORY/tree/main/skills/software-architecture`

If MausBot accepts a repository/folder URL, add the folder containing `SKILL.md`. If it asks for a raw file URL, use the corresponding `raw.githubusercontent.com` URL.

## Recommended GitHub setup

1. Create a private repository named `global-ai-development-team`.
2. Upload the contents of this folder to the repository root.
3. Test importing one skill into MausBot before importing the rest.
4. Keep the repository private if you later add internal workflows or proprietary information.

## Safety

- These skills do not grant permissions by themselves.
- Keep agents on approval-required permissions until workflows are proven.
- Do not put API keys, tokens, credentials, customer data, or private project secrets in this repository.
- Review community or third-party skills before installing them.
