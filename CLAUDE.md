# CLAUDE.md

This file provides guidance to Claude Code (and other AI assistants) when working in this repository.

## Current state

> **This repository is currently empty** — it has no source code, build files, or commit history yet. This document is a starter template establishing conventions for the project. **Update this file as soon as real code, tooling, or structure is added**, replacing the placeholder sections below with concrete, verified details.

When the codebase grows, this file should describe:

- **Project overview** — what the application/library does and who it's for.
- **Repository structure** — the top-level directories and what lives in each.
- **Tech stack** — languages, frameworks, and major dependencies.
- **Development workflow** — how to install dependencies, build, run, and test.
- **Key conventions** — code style, naming, commit message format, and architectural patterns.

## Getting started (to be filled in)

Document the real commands here once tooling exists. Typical examples:

```bash
# Install dependencies
# e.g. npm install  |  pip install -e .  |  go mod download

# Run the app
# e.g. npm run dev  |  python -m app

# Run tests
# e.g. npm test  |  pytest  |  go test ./...

# Lint / format
# e.g. npm run lint  |  ruff check .  |  gofmt -l .
```

## Repository structure (to be filled in)

```
.
└── CLAUDE.md   # This guidance file
```

Update this tree as directories are added (e.g. `src/`, `tests/`, `docs/`, `scripts/`).

## Git workflow

These conventions apply now and should be kept current:

- **Branching** — do feature work on a dedicated branch; never commit directly to the default branch without explicit permission.
- **Pushing** — push with `git push -u origin <branch-name>`.
- **Pull requests** — after pushing, open a pull request for the branch (as a draft when work is in progress).
- **Commits** — write clear, descriptive commit messages explaining the *why*, not just the *what*.

## Conventions for AI assistants

- **Keep this file accurate.** Whenever you change the build, test, or run process, or add significant structure, update the relevant section here in the same change.
- **Verify before documenting.** Don't describe commands or files that don't exist — check them first.
- **Match existing style.** Once code exists, follow the surrounding conventions (formatting, naming, patterns) rather than introducing new ones.
- **Prefer small, focused changes** with accompanying tests where a test setup exists.
