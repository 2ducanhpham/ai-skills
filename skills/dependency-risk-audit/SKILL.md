---
name: dependency-risk-audit
description: Assess dependency health, compatibility, licensing, security, and upgrade risks without changing dependencies.
---

# Dependency Risk Audit

## Workflow
1. Inspect package manifests, lockfiles, platform manifests, and dependency update policy.
2. Identify direct and important transitive dependencies.
3. Check version constraints, duplicate packages, deprecated packages, native modules, and platform requirements.
4. Assess compatibility with the project's actual runtime, language version, OS targets, and build tooling.
5. Identify security advisories and license concerns when authoritative data is available.
6. Rank risks and propose staged remediation.

## Rules
- Never install, remove, or upgrade packages during an audit.
- Do not recommend upgrades solely because a newer version exists.
- Verify claims against current authoritative sources when web access is available.
- Distinguish known vulnerabilities from general maintenance concerns.
- Include rollback and regression-test recommendations for proposed upgrades.

## Output
Dependency, current version, evidence, risk, compatibility impact, recommendation, validation plan.
