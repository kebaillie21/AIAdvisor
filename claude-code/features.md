# Claude Code Features

## Core Features

### CLAUDE.md
A file at the root of a repo that Claude reads automatically at session start. Use it to give Claude context about the project, coding standards, and standing instructions.

### MCP Servers
Model Context Protocol servers connect Claude to external tools and data sources. Configured in settings. See `mcp-servers.md`.

### Hooks
Shell commands that run automatically on specific events. See `hooks.md`.

### Subagents
Claude can spawn specialized agents to handle tasks in parallel. Useful for large or multi-step work. See `agents.md`.

### Skills (Slash Commands)
Built-in and custom commands triggered with /. Examples: /review, /init, /security-review, /simplify.

### TodoWrite
Built-in task tracking. Claude uses it during sessions to track progress on multi-step tasks.

### Compact Mode / Fast Mode
Fast mode uses Claude Opus 4.6 with faster output. Toggle with /fast. Only available on Opus 4.6.

## Add new features here as discovered.
