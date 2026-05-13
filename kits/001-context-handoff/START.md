# Copy-Paste Starter Prompt

Do not send this GitHub link to the AI by itself. Open this page and copy the entire text block below into OpenClaw, Cursor, Claude Code, Codex, or another AI coding tool.

If you are preparing a video pinned comment, use the shorter version first: [Pinned Comment Version](PINNED.md).

```text
Use this open-source kit to create an AI Handoff Card for my current project:

https://github.com/aaronyi97/ai-collaboration-playbook/tree/main/kits/001-context-handoff

Important:
- Do not write the handoff card now.
- In your first reply, only ask questions. Do not output short, full, explanation, or multiple document versions.
- If you only received a GitHub link but have not read the kit content, try to read the link first.
- If you cannot open the link, still start with Stage 1 and ask the 6 questions below. Do not invent a long handoff document.

You are running inside an AI coding tool or OpenClaw, not a normal web chatbot.

Your task:
1. Read the kit README and template.
2. Do not edit code yet.
3. First inspect the local project only if you have file access.
4. Guide me step by step. Do not output a long handoff document immediately.

Follow these stages exactly:

Stage 1: Ask me 6 questions
- Only output the question list. Do not generate the handoff card yet.
- Keep this first reply under 12 lines.
- Cover these questions:
  1. What is the goal of this project or task?
  2. Where are we now?
  3. What has already been completed?
  4. What is still unfinished?
  5. Which paths, files, or approaches should the next AI avoid?
  6. What should the next AI do first?

Stage 2: After I answer, output a user preview
- Keep it under 12 lines.
- Use plain language.
- Help me understand what the handoff card will say.
- End by asking: should I generate the final copy-paste version?

Stage 3: After I confirm, output only one final copy-paste version
- Put it in a single code block.
- Start with: "Copy everything below into the new AI session."
- Make it clear enough for the new AI to continue without seeing the old conversation.
- By default, output only the recommended version. Do not output short, full, and explanation versions at the same time.
- Keep the final copy-paste version under 40 lines when possible. Only make it longer for high-risk tasks.

Stage 4: Only output the full handoff card if I explicitly ask for "full version".
- If you cannot access the GitHub link, only ask me to paste template.md at this stage.

Rules:
- Separate verified facts from assumptions.
- Do not claim tests passed unless you actually ran or saw evidence.
- Do not include secrets, API keys, private tokens, or personal data.
- Do not make me understand the full template. You should turn my answers into a copy-paste-ready handoff card.
- Only ask me to paste the template file if I request the full version and you cannot access the GitHub link.
```
