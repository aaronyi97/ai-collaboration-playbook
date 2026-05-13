# Pinned Comment Version

Use this shorter version in a video pinned comment, description, newsletter, or community post. Viewers can paste the instruction plus the Raw link into OpenClaw, Cursor, Claude Code, Codex, or another AI coding tool.

If you want viewers to copy one complete prompt, use the block below. Reusable output is required to be placed in code blocks so the tool can show a copy button.

```text
Create a short AI Handoff Card directly from the current conversation and current project context, so I can copy it into a new AI session.

Use this open-source kit as the method:
https://github.com/aaronyi97/ai-collaboration-playbook/tree/main/kits/001-context-handoff

Important rules:
1. Do not ask me to fill a form first. Do not ask 6 questions first.
2. Extract the handoff from the old conversation, visible files, terminal output, and project state you can already see.
3. Mark uncertain information as "unconfirmed". Do not invent missing facts.
4. In the first reply, output only one short handoff table. Do not output a full version, explanation version, or multiple documents.
5. Put the handoff table in a single code block so I can copy it easily.
6. After the table, ask only one question: do you want the detailed handoff card?

The short handoff table must include these rows:
- Goal
- Current state
- Completed
- Unfinished
- Do not touch
- Risks / unknowns
- Next step
- Receiver instruction

Write "Receiver instruction" as one sentence: the new AI should restate the goal, state, risks, and first step before acting.
```
