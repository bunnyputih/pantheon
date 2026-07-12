# Pantheon Research Evidence

Use this reference to explain Pantheon's editing choices. Do not turn it into a detector recipe or a word blacklist.

## What the evidence supports

- Humanization is a quality and authorship process: grounded content, real editorial judgment, rhetorical fit, and voice.
- Individual words and punctuation marks are weak evidence. Signals depend on genre, language, writer, model, length, and the amount of human revision.
- A word cluster can still be a useful editing prompt when it corresponds to vagueness, inflated importance, or a generic template.
- Expert human editing improves flow, coherence, and factual correctness in realistic mixed-authorship writing. Mechanical paraphrase can damage fidelity and fluency.

## Corpus-wide synthesis

Pantheon's [140-paper corpus](research-corpus-2020-2026.md) adds four durable rules to the applied guidance:

- Preserve verified meaning and factual support before changing style. Style-transfer research repeatedly treats semantic preservation as a separate, difficult objective.
- Anchor voice in an actual author sample or a confirmed audience-and-genre brief. Genre, language, topic, and model can explain apparent “AI-like” patterns as much as source does.
- Audit clusters of generic reasoning, not isolated tokens. Lexical, syntactic, structural, and discourse signals vary sharply by context.
- Judge a revision along separate axes—fidelity, factuality, reader fit, coherence, and voice—and never optimize it for a detector score.

## Research, 2020–2026

| Year | Source | Finding relevant to Pantheon |
| --- | --- | --- |
| 2020 | [Ippolito et al., ACL](https://aclanthology.org/2020.acl-main.164/) | Human raters and automated detectors use different cues; even experts can be fooled. Do not equate a surface impression with proof of authorship. |
| 2021 | [Uchendu et al., TURINGBENCH](https://aclanthology.org/2021.findings-emnlp.172/) | Human-versus-machine classification varies across generators, supporting model- and context-specific evaluation. |
| 2022 | [Dugan et al., RoFT](https://arxiv.org/abs/2212.12672) | Genre, model, and sentence-level features influence human detection of human-to-machine boundaries. Revise for the actual genre, not a generic idea of “human.” |
| 2023 | [Herbold et al.](https://arxiv.org/abs/2304.14276) | In argumentative essays, ChatGPT text had fewer discourse and epistemic markers but more nominalizations and lexical diversity. Add genuine reasoning and warranted stance; do not add decorative vocabulary. |
| 2024 | [Doughman et al.](https://arxiv.org/abs/2406.11073) | Detection is highly sensitive to style and reading difficulty. A detector score is not a reliable revision target. |
| 2024 | [Juzek & Ward](https://arxiv.org/abs/2412.11385) | Their method identified 21 focal words whose rising use in scientific abstracts is likely linked to LLM use. This supports reviewing lexical clusters, not banning words. |
| 2024 | [Yakura et al.](https://arxiv.org/abs/2409.01754) | ChatGPT-associated vocabulary increased in academic talks and spontaneous podcasts after ChatGPT's release, raising concerns about reduced linguistic diversity. Preserve legitimate personal and regional language. |
| 2025 | [Liang et al., Nature Human Behaviour](https://www.nature.com/articles/s41562-025-02273-8) | Population-level word-frequency shifts across over one million papers show widespread LLM modification in scientific writing; such shifts are not an authorship verdict for an individual paper. |
| 2025 | [Bagdasarov & Alves](https://aclanthology.org/2025.lm4dh-1.4/) | In their scientific-text corpus, human writers showed more syntactic-resource variability, while LLMs showed higher lexical variability. Revise structure and rhetorical choices, not just words. |
| 2025 | [Artemova et al., Beemo](https://aclanthology.org/2025.naacl-long.357/) | Expert edits for natural flow, coherence, and factual correctness model realistic hybrid authorship; LLM-only edits were less likely to be recognized as human-written. Use human editorial judgment. |
| 2025 | [Masrour, Emi & Spero, DAMAGE](https://arxiv.org/pdf/2501.03437) | Automated humanizers often damage fluency or faithfulness; the better outputs preserve tone, vocabulary level, complexity, and meaning. |
| 2026 | [Georgiou, rapid review](https://www.mdpi.com/2504-2289/10/2/55) | No single stable AI signature exists. Surface, discourse, content, probabilistic, and provenance cues are conditional on context and revision. |
| 2026 | [Rallapalli et al.](https://arxiv.org/abs/2604.14111) | Genre has a stronger stylistic effect than source, and model choice matters more than decoding choices. Use a genre and author sample rather than a generic “sound human” prompt. |
| 2026 | [El Attar et al.](https://arxiv.org/abs/2606.04177) | Across 27 models and 10 domains, most proposed signals were context-dependent; lexical richness was the main robust family-level signal. Do not infer authorship from a single term. |

## Evidence-backed lexical watch points

The strongest corpus-supported terms to review in academic writing are `delve`, `underscore`, `meticulous`, and `intricate`. They are not forbidden words. Retain one when it is the clearest, genre-appropriate word; revise a cluster when it replaces a precise action, scope, or reason.

Examples of substance-first alternatives:

| Instead of an unexamined phrase | Prefer when accurate |
| --- | --- |
| `delve into the results` | `compare the results`, `analyze the results`, or state the specific activity |
| `this underscores the importance of X` | State the finding and why it affects a decision or conclusion |
| `a meticulous analysis` | Name the method, checks, sample, or criterion |
| `an intricate relationship` | Name the interacting variables or mechanism |
| `a robust framework` | Define the coverage, limits, or evidence supporting robustness |

## Community evidence: useful but not scientific proof

Public discussion repeatedly reports fatigue with generic metaphor clusters, inflated evaluators, heavy signposting, formulaic contrasts, and rigid list structures. It also repeatedly warns that em dashes, polished grammar, and a single word such as `delve` are not reliable tells. Use these observations to prioritize reader-experience edits, never to infer authorship or target a detector.

- [WritingWithAI community discussion](https://www.reddit.com/r/WritingWithAI/comments/1mqse0s/megathread_what_aiisms_give_away_aigenerated/)
- [Writer discussion on individual words and patterns](https://www.reddit.com/r/WritingWithAI/comments/1u3kyhq/how_obviously_is_this_ai_generated/)
