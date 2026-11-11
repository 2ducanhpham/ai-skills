---
name: architecture-decision-records
description: Create and maintain concise Architecture Decision Records with context, options, consequences, and status.
---

# Architecture Decision Records (ADR)

## When to use
Create an ADR for decisions that materially affect system structure, technology choices, data contracts, security, deployment, compatibility, or long-term maintenance.

## Required structure
# ADR-NNN: Title
- Status: Proposed | Accepted | Superseded | Deprecated
- Date:
- Decision owners:

## Context
Describe the problem, constraints, evidence, and forces at play.

## Options considered
List realistic alternatives and their trade-offs.

## Decision
State the chosen option and why it best fits the project constraints.

## Consequences
Describe positive, negative, operational, migration, and maintenance consequences.

## Verification
Explain how the decision will be validated.

## Rules
- Do not mark a proposal Accepted without authorized approval.
- Link related ADRs and implementation tasks.
- Do not rewrite history; supersede old decisions with a new ADR.
