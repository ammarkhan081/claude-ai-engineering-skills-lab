# Claude AI Engineering Skills Lab

This repository was prepared as a team research assignment on the Claude ecosystem. It combines two deliverables in one place:

- Three custom Claude Skills designed for AI engineering workflows
- A standalone HTML presentation covering key Anthropic/Claude products and features

## Submission Status

This repository is structured to satisfy the assignment requirements directly:

- GitHub repository link for the submission
- Three assigned Claude Skills with working `SKILL.md` files
- A clear top-level `skills.md`
- Documentation for multiple skills
- A self-contained HTML presentation
- Official Anthropic references and official GitHub ecosystem links

## Repository Goals

The repo is structured to be practical, easy to demo, and aligned with Anthropic's public Skills format. The included skills focus on tasks that matter to an AI engineer:

- `codebase-architect`: turn messy repositories into clear implementation and refactor plans
- `mcp-integration-engineer`: design and validate Claude connector and MCP-based integrations
- `llm-evals-guardrails`: plan evaluations, failure-mode checks, and rollout guardrails for LLM features

## Deliverables

- Skills index: [skills.md](./skills.md)
- Research notes and references: [research/sources.md](./research/sources.md)
- Standalone presentation: [presentation/claude-ecosystem-deep-dive.html](./presentation/claude-ecosystem-deep-dive.html)
- Viva preparation: [docs/viva-questions-and-answers.md](./docs/viva-questions-and-answers.md)
- Assignment checklist: [docs/assignment-compliance-checklist.md](./docs/assignment-compliance-checklist.md)

## Direct GitHub Skill Links

These are the direct repository links for the assigned skill folders:

- Codebase Architect:
  [skills/codebase-architect](https://github.com/ammarkhan081/claude-ai-engineering-skills-lab/tree/main/skills/codebase-architect)
- MCP Integration Engineer:
  [skills/mcp-integration-engineer](https://github.com/ammarkhan081/claude-ai-engineering-skills-lab/tree/main/skills/mcp-integration-engineer)
- LLM Evals and Guardrails:
  [skills/llm-evals-guardrails](https://github.com/ammarkhan081/claude-ai-engineering-skills-lab/tree/main/skills/llm-evals-guardrails)

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
- [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action)

## Research Coverage

The presentation and notes cover all six requested topics:

- Claude Cowork
- Claude Code
- Claude Connectors
- Claude Skills
- Claude Desktop
- Claude in Chrome

The research is based primarily on official Anthropic documentation reviewed on April 1, 2026. Where the assignment wording and the current public product wording differ, the submission calls that out explicitly instead of hiding the mismatch.

## Personal Take

The most important pattern across the Claude ecosystem is that Anthropic is moving beyond "chat" into reusable agent workflows. Skills package repeatable behavior, Connectors and MCP extend Claude with tools and data, and products like Claude Code and Cowork bring those capabilities into real engineering work.

## Disclaimer

This repository is an academic submission built from public Anthropic materials and hands-on ecosystem review. Product availability and feature scope can change over time, so official Anthropic documentation should always be treated as the source of truth.
