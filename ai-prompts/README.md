# AI Prompts Repository

## Purpose
This repository stores structured, reusable prompts and related context for building controlled, production-grade prompt systems.

## Structure Overview
- `prompts/` — reusable and domain-specific prompts.
- `context/` — shared templates and contextual assets.
- `experiments/` — exploratory drafts and tests.
- `STYLE_GUIDE.md` — strict formatting and naming rules.

## Principles
- Minimal change: prefer the smallest necessary modification.
- Reusability: design prompts as modular building blocks.
- Explicit constraints: define rules and priorities clearly.

## How to Add New Prompts
1. Choose placement:
   - reusable prompts → `prompts/universal/`
   - domain-specific prompts → `prompts/domain/<domain-name>/`
2. Create a folder in kebab-case.
3. Add a strict prompt file (for constrained execution) and a short `usage.md`.
4. Keep prompt logic, context, and usage instructions separated.
5. Follow `STYLE_GUIDE.md` before committing.
