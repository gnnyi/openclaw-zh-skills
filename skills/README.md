# OpenClaw Chinese Skill Starter Kit

This workspace contains a first-pass OpenClaw starter kit focused on a simple
information-to-content pipeline:

1. `research-digest-zh`
2. `idea-to-draft-zh`
3. `source-to-weekly-brief-zh`

They are intentionally narrow. The goal is to get to a usable v0 quickly, then
publish improved versions to ClawHub after real usage.

## Layout

- `research-digest-zh/`
- `idea-to-draft-zh/`
- `source-to-weekly-brief-zh/`

Each skill contains:

- `SKILL.md`
- `templates/`

## Why this set

These three skills form one reusable chain:

- research -> structure -> recurring summary

That makes the kit easy to demo, easy to explain in policy language, and easy
to extend into a later content workflow product.

## How to use

OpenClaw loads workspace skills from `<workspace>/skills`, so this directory is
already in the right place for this repository.

Suggested test prompts:

- "Use `research-digest-zh` to turn these links into a research brief."
- "Use `idea-to-draft-zh` to turn this topic into a Chinese draft."
- "Use `source-to-weekly-brief-zh` to summarize this week's source updates."

## First upgrade path

After the first round of testing, improve in this order:

1. tighten triggers and output contracts in `SKILL.md`
2. add one real example artifact per skill
3. add evaluation prompts and a regression checklist
4. prepare a publishable version for ClawHub
