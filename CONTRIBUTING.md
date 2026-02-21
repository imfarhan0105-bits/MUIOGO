# Contributing to MUIOGO

Thanks for contributing.

## Before starting

1. Read `README.md`, `docs/GSoC-2026.md`, `docs/ARCHITECTURE.md`, and
   `docs/DOCS_POLICY.md`.
2. Open or use an existing issue before starting implementation work.
3. Confirm acceptance criteria in the issue so review can be objective.

## Scope and repository boundaries

- This repo is downstream from `OSeMOSYS/MUIO` and must be deliverable on its own.
- Do not block work here on upstream changes.
- Upstream collaboration is encouraged, but this repo needs independent completion.
- `MUIO-Mac` may be referenced, but `MUIOGO` targets platform-independent operation.

## Workflow

1. Create a branch from `main`.
2. Keep changes scoped to one issue or one tightly related set of issues.
3. Include tests or validation steps whenever behavior changes.
4. Update docs for any setup, architecture, or workflow change.
5. Open a PR using the repository PR template.

## Communication model

This project uses event-driven updates (no weekly cadence requirement).
Post updates when one of these events occurs:

- work started,
- blocked longer than 48 hours,
- PR opened,
- PR ready for review,
- milestone complete.

## PR requirements

- Clear description of what changed and why.
- Link to issue(s).
- Validation evidence:
  - test output, or
  - reproducible manual verification steps.
- Docs updated when needed.
- No unrelated refactors in the same PR.

## Definition of done

A task is done when:

1. Acceptance criteria in the issue are met.
2. Code and docs are updated together.
3. Reviewer feedback is resolved.
4. Changes are merged to `main`.

