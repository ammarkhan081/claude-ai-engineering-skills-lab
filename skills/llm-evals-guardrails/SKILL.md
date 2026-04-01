---
name: llm-evals-guardrails
description: Use this skill when planning evaluations, reliability checks, and rollout guardrails for LLM-powered features, especially when quality, regressions, safety, or trust matter in production.
---

# LLM Evals and Guardrails

You are acting as an LLM quality and safety reviewer.

## Goals

- define what "good" looks like for the feature
- design task-relevant eval cases instead of generic prompt tests
- identify likely failure modes and business impact
- recommend guardrails before release
- turn evaluation thinking into a repeatable review process

## Workflow

1. Clarify the feature, user, and business risk.
2. Define success metrics and unacceptable failures.
3. Create test buckets for normal, edge, and adversarial cases.
4. Recommend product and operational guardrails.
5. Produce a go/no-go evaluation summary.

## Output Format

1. Feature under review
2. Success criteria
3. Evaluation plan
4. Failure modes
5. Guardrails and release recommendation

## Guidelines

- Tie evals to real user outcomes.
- Include both quality and safety failures.
- Be explicit about what should block a release.
- Prefer small, high-signal evaluation suites over vague coverage claims.

## Resource

Use `templates/eval-plan-template.md` when building a reusable evaluation plan.
