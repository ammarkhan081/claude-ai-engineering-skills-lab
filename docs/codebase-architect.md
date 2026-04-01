# Codebase Architect Documentation

## What It Does

This skill helps Claude act like a senior engineer during repository onboarding. It identifies architecture boundaries, traces important execution paths, and converts those findings into an implementation plan that a team can actually follow.

## Core Workflow

1. Identify the stack, entrypoints, and project structure.
2. Trace the modules involved in the target feature or bug.
3. Call out coupling, risk areas, and likely regression points.
4. Produce a change plan with verification guidance.

## Example Prompt

```text
Use the codebase-architect skill to analyze this repository and explain the fastest safe way to add multi-tenant support.
```

## Why It Matters For AI Engineers

AI engineers often work across application code, orchestration logic, data access, prompt layers, and evaluation tooling. A skill that rapidly maps the codebase reduces onboarding time and prevents shallow changes that break hidden dependencies.
