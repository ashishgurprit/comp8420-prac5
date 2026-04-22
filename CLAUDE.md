# CLAUDE.md

> Project context for Claude Code. Auto-generated from Streamlined Development v1.58.0

## Project Overview

**Name**: comp8420-prac5
**Initialized**: 2026-01-25
**Master Version**: 1.58.0

[Add project description here]

## Quick Commands

```bash
# Development
pnpm run dev          # or your dev command

# Testing
pnpm test             # or your test command

# Build
pnpm run build        # or your build command
```

## Architecture

[Describe your architecture]

## Key Files

- `src/` - Main source code
- `tests/` - Test files
- `.claude/LESSONS.md` - Project-specific lessons

## Conventions

[Your coding conventions]

## Current Focus

[What you're working on]

---

## Streamlined Development Integration

This project uses the centralized learning system.

- **Master**: `/c/Users/ashis/Documents/Coding/streamlined-development`
- **Version**: 1.58.0
- **Sync**: `/project:sync` or `~/streamlined-development/scripts/sync-from-master.sh`
- **Contribute**: `/project:post-mortem` then `~/streamlined-development/scripts/contribute-lesson.sh`


## Cross-Platform Path Rules — MANDATORY

This project may be worked on from Windows, Mac, or Codespaces.
**Never hardcode absolute paths** in committed files.

- Use `{MASTER}` as a placeholder for the Streamlined-Development repo path in docs/skills
- In bash scripts use the `$HOME`-based fallback chain (see `~/.claude/CLAUDE.md`)
- In Python use the `pathlib.Path.home()` candidate list (see `~/.claude/CLAUDE.md`)
- Never write `/Users/<name>/`, `C:/Users/<name>/`, or single-OS tilde paths in committed files
- Exception: historical debriefs/plans/reports are read-only records — leave them as-is
