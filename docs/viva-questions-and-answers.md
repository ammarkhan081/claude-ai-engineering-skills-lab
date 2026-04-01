# Viva Questions and Answers

## 1. Why did you choose these three Claude Skills?

I chose `codebase-architect`, `mcp-integration-engineer`, and `llm-evals-guardrails` because they match core AI engineering work. One helps with understanding repositories, one helps with external-tool and connector design, and one helps with evaluation and release safety.

## 2. What is the main difference between Claude Code and Claude Skills?

Claude Code is the product experience for coding inside the terminal. Claude Skills are reusable instruction packages that make Claude better at a specific workflow. In simple terms, Claude Code is the working environment, while Skills are specialized capabilities that can be used inside that environment.

## 3. Why are Claude Connectors important?

Connectors matter because an AI assistant becomes much more useful when it can access real tools and trusted context. Instead of answering only from the prompt, Claude can work with connected systems such as repositories, documentation, or business tools.

## 4. What is MCP and why does it matter here?

MCP stands for Model Context Protocol. It provides a structured way for tools and services to expose capabilities to Claude. It matters because Connectors and external integrations become more standardized, safer, and easier to scale.

## 5. What did you learn from researching Claude Cowork?

The biggest insight was that Cowork is not just another chatbot interface. Anthropic is positioning it as a more agentic workflow system that can use tools, plugins, and recurring tasks. I also found that the most current public documentation presents it as a research preview in Claude Desktop.

## 6. Why did you mention the wording issue around "Cowork (Cloud)"?

I mentioned it to keep the research accurate. The assignment used the phrase "Cowork (Cloud)," but the latest public Anthropic documentation reviewed on April 1, 2026 describes Cowork differently. I treated official documentation as the source of truth and clarified that difference instead of hiding it.

## 7. What makes Claude in Chrome powerful but risky?

It is powerful because Claude can interact with live web pages directly inside the browser. It is risky because websites can contain hidden or malicious instructions, so prompt injection and permission misuse become more important security concerns.

## 8. Why are Skills useful for teams?

Skills make Claude more consistent across repeated tasks. Instead of every teammate writing prompts from scratch, a team can define a reusable workflow once and then apply it again with better structure and reliability.

## 9. Which official repositories are most useful from an engineering point of view?

The strongest ones are `anthropics/skills`, `anthropics/claude-code`, `anthropics/claude-cookbooks`, `anthropics/github-mcp-server`, and `anthropics/claude-code-action`. Together they show product usage, workflow patterns, and integration infrastructure.

## 10. What is your overall conclusion about the Claude ecosystem?

My conclusion is that Anthropic is building an ecosystem around agentic work, not only model chat. The strongest idea across the ecosystem is reusable, tool-connected, workflow-based AI that stays useful in real engineering and productivity settings.
