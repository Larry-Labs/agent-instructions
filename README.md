# Larry-Labs Agent Instructions

A personal, reusable instruction set for Codex and other coding agents.

This repository contains the current global `AGENTS.md` used to guide agent behavior across projects.

## What it covers

- Evidence-led investigation before implementation
- Minimal, scoped changes
- Honest validation and reporting
- Secret handling and destructive-action boundaries
- Production and external-system safety
- Clear Chinese replies when the user writes Chinese

## Install for Codex

Copy `AGENTS.md` to the global Codex instruction path:

```bash
mkdir -p ~/.codex
cp AGENTS.md ~/.codex/AGENTS.md
```

Start a new Codex session after updating the file so the instruction chain is loaded again.

## Project-specific guidance

Keep project commands, architecture, deployment details, and local constraints in the project repository's own `AGENTS.md`. Use Skills for repeatable workflows such as code review, frontend design, document handling, or release work.

## Maintenance

Keep the global file concise and update it when a repeated mistake or recurring correction justifies a durable rule. Review changes against the actual Codex behavior before adopting them as defaults.

See `LICENSE` for licensing information.
