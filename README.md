# humanpp-skills

Skills and workflow assets for implementing Human++.

## What Human++ is

Human++ is a Shift42 project. It is a human-centered orchestration layer for structured AI collaboration in real execution workflows.

Principle: `Human + AI, not - human, + AI.`

## Purpose of this repository

This repository contains reusable skills and workflow assets for applying Human++ across projects.

## Current workflow focus

The current reference workflow is:

`Analysis -> Strategy -> Implementation <-> Review -> Result`

## Repository scope

This repository is focused on:

- capturing working patterns from real projects;
- turning recurring work into explicit skill contracts;
- keeping skills provider-neutral where practical;
- adding provider-specific adapters only when necessary.

## What this repository is not

This repository is not:

- an autonomous agent platform;
- a replacement for human judgment;
- a finished workflow framework;
- a provider lock-in package.

## Current status

Early foundation. The content is intentionally small, practical, and meant to evolve from real usage.

## Structure overview

- `skills/`: core Human++ skills and reusable assets.
- `adapters/`: placeholder provider-specific integration notes.
- `examples/`: examples to be added after workflows stabilize.
- `GEMINI.md`: Gemini-compatible context guidance.
- `gemini-extension.json`: minimal extension manifest.
