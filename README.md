# Claude AI Engineering Skills Lab

This repository was prepared as a team research assignment on the Claude ecosystem. It combines two deliverables in one place:

- Three custom Claude Skills designed for AI engineering workflows
- A standalone HTML presentation covering key Anthropic/Claude products and features

## Repository Goals

The repo is structured to be practical, easy to demo, and aligned with Anthropic's public Skills format. The included skills focus on tasks that matter to an AI engineer:

- `codebase-architect`: turn messy repositories into clear implementation and refactor plans
- `mcp-integration-engineer`: design and validate Claude connector and MCP-based integrations
- `llm-evals-guardrails`: plan evaluations, failure-mode checks, and rollout guardrails for LLM features

## Deliverables

- Skills index: [skills.md](./skills.md)
- Research notes and references: [research/sources.md](./research/sources.md)
- Standalone presentation: [presentation/claude-ecosystem-deep-dive.html](./presentation/claude-ecosystem-deep-dive.html)

## Skill Layout

Each skill lives in its own folder under `skills/` and includes a `SKILL.md` file with Anthropic-style frontmatter plus reusable resources.

```text
skills/
  codebase-architect/
    SKILL.md
    templates/architecture-review-template.md
  mcp-integration-engineer/
    SKILL.md
    checklists/integration-checklist.md
  llm-evals-guardrails/
    SKILL.md
    templates/eval-plan-template.md
```

## Recommended GitHub Repositories To Reference In The Presentation

- [anthropics/skills](https://github.com/anthropics/skills)
- [anthropics/claude-code](https://github.com/anthropics/claude-code)
- [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks)
- [anthropics/github-mcp-server](https://github.com/anthropics/github-mcp-server)

## Personal Take

The most important pattern across the Claude ecosystem is that Anthropic is moving beyond "chat" into reusable agent workflows. Skills package repeatable behavior, Connectors and MCP extend Claude with tools and data, and products like Claude Code and Cowork bring those capabilities into real engineering work.

## Disclaimer

This repository is an academic submission built from public Anthropic materials and hands-on ecosystem review. Product availability and feature scope can change over time, so official Anthropic documentation should always be treated as the source of truth.
