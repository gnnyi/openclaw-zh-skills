---
name: idea-to-draft-zh
description: Convert a topic or rough idea into a focused Chinese outline and first draft with a clear audience, angle, and structure. Use when Codex needs to turn notes, source material, or a raw topic into a usable draft.
---

# Idea To Draft ZH

Use this skill when the user has a topic, a raw idea, or a pile of notes and
wants a first draft in Chinese.

## Trigger

Use this skill when the user asks for any of the following:

- turn a topic into an outline
- turn notes into a draft
- generate a first draft
- refine a content angle
- "帮我把这个想法写成初稿"
- "帮我做选题并起草"

## Outcome

Produce a markdown draft package with:

1. Audience
2. Core Promise
3. Angle Options
4. Chosen Outline
5. First Draft
6. Revision Notes

## Workflow

1. Clarify who the content is for.
2. State the single most important promise to the reader.
3. Generate 3 distinct angles before drafting.
4. Choose one angle and explain why it is strongest.
5. Build a tight outline.
6. Draft in Chinese using the template at
   `{baseDir}/templates/idea_to_draft_template.md`.
7. End with 3 to 5 revision suggestions instead of pretending the first draft is final.
8. If the request is close to a known pattern, read
   `{baseDir}/references/examples.md` first and reuse its structure.

## Rules

- Avoid generic motivational filler.
- Prefer concrete examples and claims over slogans.
- If source material is provided, preserve its strongest ideas but rewrite the expression.
- Match the requested format if the user specifies one.

## Output Standard

- The draft should be usable, not just brainstormy.
- The outline and the draft should clearly match.
- Keep the chosen angle sharper than the rejected angles.
