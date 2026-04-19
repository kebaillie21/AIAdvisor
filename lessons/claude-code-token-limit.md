# Claude Code Output Token Limit

**Date noted:** April 2026

## The Problem
Claude Code hits a ~64,000 token output limit mid-task. Work stops and context is lost.

## What Did NOT Work
- `export CLAUDE_CODE_MAX_OUTPUT_TOKENS=100000` -- this env var had no effect.

## Resources
- https://blog.stackademic.com/when-claude-code-hits-the-wall-solving-the-64-000-token-limit-89259b681f97
- https://limitededitionjonathan.substack.com/p/ultimate-guide-fixing-claude-hit

## Workaround: Context-Continuity Prompts
Before hitting the limit (or when starting a new session), use one of the prompts in `prompts/context-continuity.md` to create a handoff document. Then paste it into the new session.

## Status
Open issue. No confirmed fix found yet. Add updates here if a solution is discovered.
