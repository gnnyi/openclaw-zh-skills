---
name: source-to-weekly-brief-zh
description: Transform a set of weekly source updates into a Chinese brief with changes, signals, and concrete follow-up actions. Use when Codex needs to summarize a time window of updates into a decision-oriented weekly brief.
---

# Source To Weekly Brief ZH

Use this skill when the user wants recurring source material turned into a clean
weekly summary.

## Trigger

Use this skill when the user asks for any of the following:

- weekly brief
- update digest
- change summary
- source recap
- "帮我做周报"
- "帮我总结这周的信息变化"

## Outcome

Produce a weekly brief with:

1. Scope and Time Window
2. What Changed
3. Why It Matters
4. Action Queue
5. Watchlist

## Workflow

1. Confirm the time window if the user did not specify one.
2. Gather the provided sources for that window only.
3. Remove duplicates and collapse repeated facts.
4. Highlight what changed, not just what exists.
5. Separate signal from noise.
6. Write the result in Chinese using the template at
   `{baseDir}/templates/weekly_brief_template.md`.
7. If a similar recap already exists, check `{baseDir}/references/examples.md`
   to match the expected brevity and sectioning.

## Rules

- Prefer delta over repetition.
- Keep the brief decision-oriented.
- Use dates for material changes.
- If a source is unverified or low quality, mark it explicitly.

## Output Standard

- The brief should be readable in under five minutes.
- The action queue should contain only concrete next steps.
- The watchlist should contain unresolved items worth revisiting next week.
