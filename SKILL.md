---
name: humanize-ai-writing
description: Evidence-guided revision of AI-assisted drafts for natural voice, factual grounding, reader fit, and meaningful human authorship. Use when asked to humanize AI writing, reduce a robotic or generic tone, preserve a writer's voice, audit AI-isms, or revise an AI draft into a credible email, article, report, statement, or essay. Do not use to conceal authorship, bypass AI detectors, remove watermarks, fabricate experience, or evade academic or workplace policies.
---

# Pantheon: Humanize AI Writing

Make AI-assisted prose sound authored, not merely altered. Humanization means a source-grounded editorial process that restores an author's real judgment, evidence, cultural context, and rhetorical purpose. It does not mean inserting mistakes, using slang, or trying to fool a detector.

## Core Position

- Treat no word, punctuation mark, or style feature as proof of AI authorship. Research shows that cues vary by genre, model, language, text length, and editing history.
- Treat a cluster of weak choices as an editing signal: vague claims, formulaic structure, generic detail, unsupported certainty, and a voice that does not fit the author or audience.
- Preserve the author's dialect, multilingual choices, regional language, and established style. Never "standardize" a voice merely because it differs from a default model style.
- Use only facts, experiences, opinions, and sources the user supplied or confirmed. Ask before adding personal perspective or cultural detail.
- Treat meaning, factual support, and required terminology as protected invariants. A more natural sentence is not an improvement if it changes a claim, source, quote, decision, or level of certainty.
- Start from a real voice source: a user sample, confirmed preferences, or a clear genre/audience brief. "Sound human" alone is not a sufficient target voice.
- Do not promise that a revision will pass or fail an AI detector. Evaluate quality, accuracy, and reader fit instead.

For sources and the evidence behind these rules, read [references/research-evidence.md](references/research-evidence.md). For a year-by-year research request, deep audit, or a full evidence trail, read the [140-paper research corpus (2020–2026)](references/research-corpus-2020-2026.md).

## Boundaries

- Decline requests to make text "undetectable", defeat a detector, remove provenance signals, or conceal AI use where disclosure is required.
- Offer the ethical alternative: help the user contribute their own position and evidence, revise for clarity and voice, verify claims, and follow the applicable policy.
- Do not add typos, broken grammar, fake citations, fake quotations, fabricated anecdotes, forced dialect, or random slang. These are not evidence of authentic authorship and can damage the text.

## Intake

Identify or infer the following before rewriting:

- Audience, purpose, format, and target genre.
- The author's preferred voice, ideally from a short user-provided sample.
- Facts, examples, decisions, and opinions the author can genuinely stand behind.
- Required citations, constraints, and disclosure rules.

Ask one focused question if a missing detail would materially change the claims or voice. Otherwise, state the assumption briefly and proceed.

## Revision Workflow

### 1. Diagnose substance before style

Mark only the problems that matter:

- Claims that are broad, inflated, unsupported, or detached from a consequence.
- Paragraphs that repeat a point, merely restate the prompt, or exist only to sound comprehensive.
- A missing point of view, missing reasoning, or a level of certainty the evidence does not support.
- Absent concrete anchors such as a named decision, time, place, example, source, constraint, or trade-off.
- A tone, structure, or formatting pattern that does not suit the intended reader.

Do not diagnose an isolated sophisticated word, em dash, bullet list, perfect grammar, or non-standard English as an AI tell.

### 2. Rebuild the argument or narrative

Revise from meaning outward:

1. **Document:** State the actual point and organize around the reader's need, not a generic template.
2. **Paragraph:** Give each paragraph one job: advance a claim, explain a mechanism, supply evidence, acknowledge a limit, or make a request.
3. **Evidence:** Replace unsupported emphasis with a verified example, number, source, decision, or qualification. Cut the claim if support is unavailable.
4. **Voice:** Restore the writer's real preferences, humor, uncertainty, directness, and level of formality. Use first person only where the author owns the experience or judgment.
5. **Sentence:** Use precise verbs and concrete nouns. Vary pace only when it improves emphasis, clarity, or the genre's rhythm. Prefer a local edit to a wholesale paraphrase when the original is already accurate.

## Word and Phrase Watch List

Use this as a **review list, never a ban list**. Keep a word when it is exact, necessary, and normal for the author's genre. Review it when several such words cluster, substitute for specificity, or make the prose sound more elevated than the underlying idea.

### Corpus-backed prompts to inspect

`delve`, `underscore`, `meticulous`, and `intricate` have shown marked post-ChatGPT overrepresentation in some academic corpora. In a given draft, ask what the word actually contributes:

- Replace an exploration verb with the exact action: `measure`, `compare`, `explain`, `trace`, `test`, or `describe`.
- Replace an importance adjective with the reason: explain why it changes a decision, result, or risk.
- Replace a vague descriptor with a bounded fact: scope, count, method, limitation, or relationship.
- Delete a modifier that does not change the claim.

### Reader-watch patterns to inspect

Public writing communities commonly flag repeated clusters of:

- Abstract metaphors: `tapestry`, `realm`, `landscape`, `paradigm`, `ecosystem`.
- Inflated evaluators: `pivotal`, `transformative`, `robust`, `comprehensive`, `multifaceted`, `profound`.
- Generic action verbs: `leverage`, `harness`, `foster`, `elevate`, `showcase`, `unravel`, `embark`.
- Over-signposting: `moreover`, `additionally`, `notably`, `in today's world`, `let's dive in`.
- Formulae: `It is not X; it is Y`, `serves as a testament to`, a rhetorical question followed by its immediate answer, or repeated neat lists of three.

Do not replace these mechanically. Replace them only with a more accurate action, a concrete relationship, a direct statement, or nothing at all.

## Human-Authored Detail

Add detail only when it is true and authorized:

- Name the relevant person, organization, place, date, constraint, decision, or outcome.
- State a real trade-off or uncertainty instead of presenting universal confidence.
- Explain how the evidence supports the conclusion rather than using labels such as `robust` or `compelling` without support.
- Preserve legitimate cultural, technical, and disciplinary language rather than flattening it into generic Standard English.

## Quality Check

Before delivering, confirm that the revision:

- Preserves the user's core position unless a substantive change was requested.
- Contains no invented facts, citations, quotations, experiences, or emotions.
- Fits the intended audience, genre, and formality.
- Has a clear line of reasoning or narrative movement.
- Uses evidence and uncertainty proportionately.
- Preserves source meaning, factual support, quotations, numbers, named entities, and required terminology.
- Avoids repetitive templates, unsupported emphasis, and cosmetic synonym swaps.
- Retains the author's legitimate vocabulary, dialect, and punctuation preferences.
- Respects disclosure, authorship, academic-integrity, and workplace requirements.

## Response Format

Provide the polished revision first. Then, when useful, give a short, substantive edit note: sharpened claim, restored author-supplied detail, reordered argument, verified citation, or removed unsupported language. For an AI-ism audit, label each flagged item `keep`, `replace`, or `cut` and give a short reason. Do not provide a detector score or an undetectability claim.
