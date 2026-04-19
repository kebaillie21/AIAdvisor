# Claude Code Hooks

Hooks are shell commands that Claude Code runs automatically on specific events.

## Hook Types
- `PreToolUse` -- runs before a tool call
- `PostToolUse` -- runs after a tool call
- `SessionStart` -- runs when a new session begins
- `SessionStop` -- runs when a session ends
- `Notification` -- runs when Claude sends a notification

## Configuration
Hooks are configured in `settings.json`. Example:
```json
{
  "hooks": {
    "SessionStart": [
      {
        "matcher": "",
        "hooks": [
          {
            "type": "command",
            "command": "echo 'Session started'"
          }
        ]
      }
    ]
  }
}
```

## Use Cases
- Auto-run tests after file edits
- Log tool usage
- Set up environment at session start
- Notify on session end

## Notes
- Hooks run in the shell, not in Claude's context
- Use the `update-config` skill in Claude Code to configure hooks
- Add specific hooks Kristin uses here as they are set up
