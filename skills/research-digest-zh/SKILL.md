---
name: research-digest-zh
description: Turn scattered materials into a structured Chinese research digest with source-aware findings and open questions. Use when Codex needs to summarize sources, interpret policy or market information, or convert multiple inputs into a concise brief.
---

# Research Digest ZH

Use this skill when the user wants to turn scattered sources into a clean,
decision-oriented Chinese brief.

## Trigger

Use this skill when the user asks for any of the following:

- research summary
- source digestion
- competitive scan
- trend brief
- policy interpretation from multiple sources
- "帮我整理资料"
- "帮我做调研摘要"

## Outcome

Produce a markdown digest with five sections:

1. Objective
2. Key Findings
3. Evidence and Sources
4. Implications
5. Open Questions

## Workflow

1. Restate the research goal in one sentence.
2. Identify the minimum source set needed to answer the question.
3. Read only the most relevant materials first. Do not bulk-load everything.
4. Extract dated facts, claims, and uncertainty signals.
5. Group findings into 3 to 5 themes.
6. Separate verified facts from inference.
7. Write a concise Chinese digest using the template at
   `{baseDir}/templates/research_digest_template.md`.
8. If you need a worked pattern, read `{baseDir}/references/examples.md` and
   mirror the sectioning style without copying wording.

## Rules

- Prefer primary sources when available.
- Include source links or file references for important claims.
- Use exact dates whenever freshness matters.
- Do not overquote long passages.
- If evidence is weak or mixed, say so directly.

## Output Standard

- Keep the final structure compact and scannable.
- Use plain Chinese unless the user asks for bilingual output.
- End with a short "next action" suggestion if the research is action-oriented.
