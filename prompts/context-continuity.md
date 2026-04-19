# Context Continuity Prompts

Use these when Claude Code is about to hit its context limit, or when starting a new session and needing to pick up where you left off.

---

### Project Progress Summary
**Context:** Use mid-task when you need a snapshot of where things stand before context runs out.
**Tool:** Claude Code (any session)

**Prompt:**
```
Create a summary of the project's progress and current roadblocks.
```

**Notes:** Simple and fast. Good for a quick status check.

---

### Comprehensive Conversation Memory Log
**Context:** Use at the end of a long session or before expected context cutoff. Creates a detailed handoff document.
**Tool:** Claude Code (any session)

**Prompt:**
```
Create a comprehensive conversation memory log capturing:
- The original problem and how it evolved
- Key insights and solutions we developed
- My working style and preferences you observed
- Our collaboration approaches that worked well
- Any clarifications or corrections I made
- Project context and examples we used
- Templates or processes we established
- Next steps we identified

Make it detailed enough that a new conversation can pick up exactly where we left off.
```

**Notes:** Best for complex, multi-session projects. Captures working style and preferences, not just tasks. Paste the output at the start of the next session.

---

### Structured Session Handoff
**Context:** Use to summarize work done so a new Claude session can continue without repeating explanations.
**Tool:** Claude Code (any session)

**Prompt:**
```
Summarize all our work, decisions, and codebase changes into a structured document for a new session.
```

**Notes:** More concise than the memory log. Good for codebase-heavy work where decisions and changes matter most.

---

## How to Use These
1. Paste the chosen prompt into Claude Code before the session ends.
2. Copy the output.
3. Start a new Claude Code session.
4. Paste the output at the top of the new conversation before any instructions.
