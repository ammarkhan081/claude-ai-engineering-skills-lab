# MCP Integration Engineer Documentation

## What It Does

This skill helps Claude design and review integrations built with Connectors or the Model Context Protocol. It emphasizes capability scoping, auth boundaries, tool contracts, failure modes, and rollout safety.

## Core Workflow

1. Define the business goal and required external systems.
2. Map each required capability to a connector or MCP tool.
3. Describe auth, permissions, and data sensitivity.
4. Produce a clear integration checklist and test plan.

## Example Prompt

```text
Use the mcp-integration-engineer skill to design a secure GitHub + Slack + internal docs workflow for release management.
```

## Why It Matters For AI Engineers

Modern AI systems are valuable when they can act on live tools and trusted data. That means integrations matter as much as prompting. This skill focuses on the engineering rigor needed to move from demos to reliable workflows.
