# Claude (Anthropic)

## Status: Active

## Versions Kristin Uses
- Claude Code (web): claude.ai/code -- browser-based, supports MCP servers, agents, repo management
- Claude Code (CLI): terminal-based, same capabilities, good for local automation
- Claude API: used to build custom AI systems (AI Chief of Staff, etc.)

## Models Available (as of April 2026)
- Opus 4.7: most capable, slower
- Sonnet 4.6: balanced speed and capability, Kristin's primary model
- Haiku 4.5: fastest, lowest cost

## Key Features
- MCP servers: connect Claude to external tools (GitHub, Slack, Google Calendar, etc.)
- Hooks: shell commands that run automatically on events (SessionStart, tool calls, etc.)
- Agents (subagents): Claude can spawn specialized sub-agents for parallel tasks
- CLAUDE.md: repo-level instructions file Claude reads automatically
- Slash commands / Skills: custom or built-in commands triggered with /
- TodoWrite: built-in task tracking during sessions

## Cost
- Claude plans include Claude Code web and CLI access
- API usage billed separately per token
