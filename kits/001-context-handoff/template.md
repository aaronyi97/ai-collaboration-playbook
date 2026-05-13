# AI Handoff Card Template

Use this template when a new AI session needs to continue a task without seeing the old conversation.

## 1. Goal

What are we trying to finish?

```text
<final goal>
```

## 2. Current State

- Current phase: `<planning / implementation / debugging / review / verification / release>`
- Current branch or workspace: `<branch/path if relevant>`
- Current status: `<what is true right now>`

## 3. Completed Work

List only work that is actually done.

- `<completed item>`  
  Evidence: `<file / commit / command / link>`

## 4. Key Decisions

- `<decision>`  
  Why: `<reason>`  
  Evidence: `<source if available>`

## 5. Changed Files

| File | Change | Status |
|---|---|---|
| `<path>` | `<what changed>` | `<done / pending / unverified>` |

## 6. Rejected Paths

These paths were tried, rejected, or replaced. Do not repeat them unless the user explicitly asks.

- `<rejected path>`  
  Reason: `<why it was rejected>`

## 7. Risks And Unknowns

### Verified Facts

- `<fact>`  
  Evidence: `<source>`

### Assumptions

- `<assumption>`  
  Confidence: `<high / medium / low>`  
  Why: `<reason>`

### Unknowns

- `<unknown>`  
  How to check: `<next check>`

## 8. Next Step

The next AI session should do this first:

```text
<first concrete action>
```

## 9. Files To Read First

Read these before acting:

1. `<file/link>` — `<why it matters>`
2. `<file/link>` — `<why it matters>`

## 10. Receiver Prompt

Paste this into the next AI session together with the handoff card:

```text
Read this handoff card first.
Do not assume you can see the old conversation.
Before acting, reply with:
1. the goal,
2. current state,
3. main risks,
4. what you will do first,
5. what you will not do.
If anything is unclear, ask before executing.
```

