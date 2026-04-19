# Claude Code Settings

## Settings Files
- Project settings: `.claude/settings.json` in the repo root
- User settings: `~/.claude/settings.json` (global)
- Local overrides: `.claude/settings.local.json` (not committed)

## Key Settings
- `mcpServers` -- MCP server connections
- `hooks` -- automated hook commands
- `permissions` -- tool allow/deny lists
- `env` -- environment variables

## Permissions
- Tools can be allowed or denied in settings
- Use the `update-config` skill to add permissions
- Example: `"allow": ["Bash(npm:*)"]`

## CLAUDE.md
- Place at repo root for project-level instructions
- Claude reads it automatically at session start
- Use for coding standards, context, standing instructions

## Notes
- Add specific settings discoveries here
