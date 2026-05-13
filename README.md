# AI Collaboration Playbook

[中文说明](README.zh-CN.md)

Reusable AI collaboration kits for coding tools, OpenClaw, and long-running AI workflows.

This repository is a companion library for videos and essays about practical AI collaboration. Each kit turns one recurring AI workflow problem into:

- a short explanation,
- a reusable template,
- examples,
- and a copy-paste starter prompt for AI coding tools.

The goal is not to build another framework. The goal is to make useful AI workflow patterns easy to reuse.

## Available Kits

| Kit | Problem | Use this when |
|---|---|---|
| [001 Context Handoff](kits/001-context-handoff/) | A new AI session cannot continue the old task | You need to switch chats, models, tools, or coding agents without losing project context |

## Quick Start

If you use OpenClaw, Cursor, Claude Code, Codex, or another AI coding tool, start with the first kit:

[Copy-paste starter prompt](kits/001-context-handoff/START.md)

If you prefer to read the full guide:

[Context Handoff Kit](kits/001-context-handoff/)

## Repository Structure

```text
.
├── README.md
├── README.zh-CN.md
├── kits/
│   └── 001-context-handoff/
│       ├── README.md
│       ├── README.zh-CN.md
│       ├── START.md
│       ├── START.zh-CN.md
│       ├── template.md
│       ├── template.zh-CN.md
│       └── examples/
└── docs/
    ├── how-to-use.md
    └── how-to-use.zh-CN.md
```

## What This Is For

This repo is for people who use AI to do serious work across multiple sessions:

- software projects,
- research,
- product planning,
- content production,
- audits and reviews,
- long-running agent workflows.

It is especially useful when AI starts to forget:

- what the project is,
- what has already been decided,
- what was tried and rejected,
- what files changed,
- what the next step is,
- and what should not be touched.

## Design Principles

1. **One video, one reusable kit.** Each kit should solve one concrete problem.
2. **Coding-tool first.** Copy-paste prompts are written for OpenClaw and AI coding tools, not normal web chat.
3. **Bilingual by default.** English is the default GitHub entry. Chinese files use `.zh-CN.md`.
4. **Useful before complete.** A small template people actually use is better than a large system they never try.
5. **No private workflow leakage.** Public kits explain reusable patterns without exposing private governance files, personal data, or internal project state.

## License

MIT.

