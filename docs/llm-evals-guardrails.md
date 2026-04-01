# LLM Evals and Guardrails Documentation

## What It Does

This skill helps Claude act like a launch reviewer for LLM-powered features. It structures success criteria, builds focused evaluation buckets, identifies failure modes, and recommends release guardrails before a feature reaches users.

## Core Workflow

1. Define the feature, user, and business consequence of failure.
2. Specify measurable success criteria.
3. Create high-signal test buckets for normal, edge, and adversarial cases.
4. Identify release blockers and recommend safeguards.
5. Produce a clear go, no-go, or limited-rollout recommendation.

## Example Prompt

```text
Use the llm-evals-guardrails skill to review our support chatbot before launch and define what should block release.
```

## Why It Matters For AI Engineers

AI engineering is not only about building features. It is also about deciding whether a system is trustworthy enough to ship. This skill focuses on the evaluation discipline that helps teams avoid weak launches, hidden regressions, and safety oversights.
