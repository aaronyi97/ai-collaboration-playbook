# Kit 001: Context Handoff

[中文说明](README.zh-CN.md)

## Problem

You work with an AI agent for a while. It understands the project, the decisions, the files, the dead ends, and the next step.

Then you open a new session.

The new AI starts from zero.

This is not just a memory problem. It is a handoff problem.

## Solution

Use an **AI Handoff Card**: a short structured handoff document that lets a new AI session continue without reading the full old conversation.

The handoff card captures:

- goal,
- current state,
- completed work,
- decisions,
- changed files,
- rejected paths,
- risks,
- next step,
- files to read first.

## Start Here

If you are using OpenClaw, Cursor, Claude Code, Codex, or another AI coding tool:

[Copy the pinned comment starter](PINNED.md)

Open that file and copy the full text block. Do not send the GitHub link to the AI by itself.

The starter prompt runs in **guided mode**: it asks six questions first, shows a plain-language preview, and only generates the final copy-paste handoff after you confirm. It does not dump a long document immediately.

If you want the fuller starter prompt:

[Full starter prompt](START.md)

If you want to fill the template manually:

[Handoff template](template.md)

## When To Use This Kit

Use it when:

- a chat is getting too long,
- you switch AI tools,
- you switch models,
- you need another agent to continue the task,
- an AI coding task has many decisions and file changes,
- the next AI must know what not to repeat.

## The Lightweight Workflow

```text
Old session
-> Generate handoff card
-> New session reads handoff card
-> New session repeats goal, risks, and next step
-> User confirms
-> New session continues
```

## What Not To Do

Do not paste the entire old chat history into the new session.

Raw chat logs contain:

- noise,
- trial and error,
- outdated plans,
- decisions that were later reversed,
- tool output that no longer matters.

A handoff card keeps the useful context and removes the noise.

## Example Use Cases

- Continue a coding task in a new AI session.
- Move from ChatGPT to an AI coding tool.
- Move from one coding agent to another.
- Send a project state summary to a teammate.
- Save a checkpoint before a risky refactor.
