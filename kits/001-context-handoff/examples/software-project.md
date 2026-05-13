# Example: Software Project Handoff

## Goal

Fix the export button loading state.

## Current State

- Phase: verification.
- Branch: `feature/export-loading`.
- Status: local changes exist, but full tests have not been run yet.

## Completed Work

- Added local `isExporting` state to the export button.  
  Evidence: `src/components/ExportButton.tsx`
- Added a test for recovery after failed export.  
  Evidence: `tests/export-button.test.tsx`

## Key Decisions

- Keep loading state local to the component.  
  Why: global loading state is too large for this task.

## Changed Files

| File | Change | Status |
|---|---|---|
| `src/components/ExportButton.tsx` | Disable button during export | unverified |
| `tests/export-button.test.tsx` | Add failure recovery test | unverified |

## Rejected Paths

- `setTimeout` fake loading state.  
  Reason: hides the real request state.
- Global loading store.  
  Reason: too much scope for a small component fix.

## Risks And Unknowns

### Verified Facts

- Two files were changed.  
  Evidence: source session summary. The next AI should re-check with `git status --short`.

### Unknowns

- Whether the focused test passes.  
  How to check: run the relevant test command.
- Whether button width shifts during loading.  
  How to check: browser or screenshot review.

## Next Step

```text
Run git status --short and confirm the change scope before editing anything.
```

## Files To Read First

1. `src/components/ExportButton.tsx` — component behavior.
2. `tests/export-button.test.tsx` — expected behavior.

