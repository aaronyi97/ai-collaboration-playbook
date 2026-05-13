# Copy-Paste Starter Prompt

Do not send this GitHub page link to the AI by itself. Open this page and copy the entire text block below into OpenClaw, Cursor, Claude Code, Codex, or another AI coding tool.

If you are preparing a video pinned comment, use the shorter version first: [Pinned Comment Version](PINNED.md).

```text
Use this open-source kit to directly create a short AI Handoff Card for my current project:

https://github.com/aaronyi97/ai-collaboration-playbook/tree/main/kits/001-context-handoff

Important:
- Do not ask me to fill a form first.
- In your first reply, directly output one short handoff table.
- If you only received a GitHub link but have not read the kit content, try to read the link first.
- If you cannot open the link, still follow this prompt and output the short handoff table. Do not invent a long handoff document.

You are running inside an AI coding tool or OpenClaw, not a normal web chatbot.

Your task:
1. Read the kit README and template.
2. Do not edit code yet.
3. Extract the handoff from the current conversation, visible files, terminal output, and project state.
4. If information is missing, write "unconfirmed". Do not invent facts and do not ask me a long list of questions first.

First reply requirements:
- Output only one short handoff table in a single code block so I can copy it easily.
- After the table, ask only one question: do you want the detailed handoff card?
- Do not output a short version, full version, explanation version, or multiple documents at the same time.
- Keep the short handoff table under 20 lines when possible.

The short handoff table must include these rows:
| Item | Content |
|---|---|
| Goal | ... |
| Current state | ... |
| Completed | ... |
| Unfinished | ... |
| Do not touch | ... |
| Risks / unknowns | ... |
| Next step | ... |
| Receiver instruction | The new AI should restate the goal, state, risks, and first step before acting. |

Follow-up rules:
- Only output the full handoff card if I explicitly ask for "detailed version" or "full version".
- Put the detailed version in a code block too.
- If you cannot access the GitHub link, only ask me to paste template.md at the detailed-version stage.

Rules:
- Separate verified facts from assumptions.
- Do not claim tests passed unless you actually ran or saw evidence.
- Do not include secrets, API keys, private tokens, or personal data.
- Do not make me understand the full template. You should turn my answers into a copy-paste-ready handoff card.
- Put all reusable output in code blocks so the tool UI can show a copy button.
```
