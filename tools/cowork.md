# CoWork

## Status: Active

## What It Is
An AI project workspace. Kristin uses it for professional work. It has its own AI model, skill system, task tracking, and project organization. It is separate from Claude Code and the two do not communicate.

## Model
Opus 4.7 (confirmed from UI)

## Projects Kristin Uses
- YPE Curriculum Edits
- Attendance Data
- Discipline Data Analysis
- SEBC Conference
- Conference Poster
- Navigating Risky Waters
- Organize Me
- Copyediting

## Key Features
- Projects: organized workspaces per project
- Tasks: new task, scheduled, recent
- Customize: sidebar option (explore for shortcut/template setup)
- Dispatch: feature not yet documented
- Progress panel: tracks steps in longer tasks
- Working folder: files created during a task
- Context panel: shows active skills
- Queue: for queuing responses
- Skill system: CoWork has its own skills (e.g., skill-creator). Custom skills can be built.

## Custom Skills in CoWork
CoWork has a `skill-creator` skill that can build custom shortcuts. Kristin asked CoWork to build a `/handoff` skill that:
1. Summarizes the current conversation
2. Saves the summary to a file
3. Produces a ready-to-paste context block for the next conversation

Status: in progress (skill-creator was running as of last session).

## Does NOT Communicate with Claude Code
Slash commands and skills created in Claude Code do not work in CoWork, and vice versa. Each tool's shortcuts must be set up within that tool.

## Context Continuity Workaround (before /handoff skill is ready)
Paste a prompt from `prompts/context-continuity.md` manually at the end of a CoWork chat.

## Resource
- https://dev.to/robiul_islam/i-migrated-years-of-chatgpt-conversations-to-claude-using-cowork-heres-how-plc
