# AI Terminology

AI concepts in plain language. No jargon without explanation.

## Terms

### Agent / AI Agent
An AI that can take actions, use tools, and complete multi-step tasks on its own, not just answer questions. Claude Code is an agent.

### MCP (Model Context Protocol)
A standard that lets AI tools connect to external services (GitHub, Slack, etc.). Think of it as a plugin system for AI.

### Context Window
The amount of text an AI model can hold in memory at once during a conversation. When the context window fills up, earlier messages get compressed or dropped.

### Prompt
The instructions or input you give to an AI. Good prompts are specific, include context, and tell the AI what format to use.

### Token
The unit AI models use to measure text. Roughly 1 token per word (a bit less). API costs are billed per token.

### Fine-tuning
Training an AI model further on specific data to change its behavior. Different from prompting.

### RAG (Retrieval-Augmented Generation)
A technique where an AI retrieves relevant documents before answering, so it can use up-to-date or specific information beyond what it was trained on.

### Subagent / Specialized Agent
A focused AI agent spawned by a parent agent to handle a specific type of task. Claude Code can spawn subagents.

### Hook
In Claude Code: a shell command that runs automatically on a trigger event (session start, tool use, etc.).

### CLAUDE.md
A special file Claude Code reads at the start of every session in a repo. Used to give Claude standing instructions and context.

## Add new terms here as Kristin encounters them.
