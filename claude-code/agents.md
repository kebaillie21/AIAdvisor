# Claude Code Agents and Subagents

## What Are Subagents
Claude can spawn specialized agents to handle tasks in parallel or in sequence. Each agent type has specific tools available.

## Built-in Agent Types
- `Explore` -- fast codebase exploration, file search, keyword search
- `Plan` -- software architecture and implementation planning
- `general-purpose` -- research, multi-step tasks, broad searches
- `claude-code-guide` -- questions about Claude Code features, API, SDK
- `statusline-setup` -- configure Claude Code status line

## When to Use Agents
- Parallel independent work (spawn multiple agents at once)
- Protecting main context window from large outputs
- Specialized tasks that match an agent type

## Agent Teams (AI Chief of Staff Context)
- Kristin is building an AI Chief of Staff system that uses agent teams
- See the AIChiefofStaff repo for implementation details

## Notes
- Add patterns and discoveries here as Kristin works with agents
