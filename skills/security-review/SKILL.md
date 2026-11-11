---
name: security-review
description: Review application and infrastructure changes for common security and privacy risks.
---

# Security Review

## Review areas
- Authentication and session management
- Authorization and tenant/data isolation
- Input validation and output encoding
- Secrets and configuration handling
- Sensitive data storage, transport, and logging
- File upload/download handling
- Network and API boundaries
- Dependency and supply-chain risks
- Build, CI/CD, and deployment permissions

## Rules
- Never print, copy, or expose secret values.
- Do not perform intrusive testing against systems without explicit authorization.
- Distinguish exploitable findings from hardening suggestions.
- Include impact, prerequisites, evidence, and remediation.
- Follow least privilege and data minimization.

## Output
Severity-ranked findings, affected assets, attack scenario, remediation, and verification steps.
