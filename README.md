# Pantheon

> A research-grounded skill for turning AI-assisted drafts into writing that is accurate, personal, and appropriate for its reader.

Pantheon helps an AI assistant revise text that feels generic, robotic, overly polished, or unlike its author. It is built around a simple rule: **make the writing more genuinely yours, not merely different.**

It uses a 140-paper research corpus (20 papers for every year from 2020–2026) to guide practical editing. The skill protects facts, quotations, citations, required terminology, and the writer's real viewpoint while improving clarity, rhythm, reasoning, and reader fit.

## What Pantheon does

- Finds generic claims, template-like structure, repeated transitions, weak reasoning, and inflated language.
- Rebuilds the draft around the writer's own facts, examples, choices, uncertainty, and tone.
- Preserves meaning, factual support, quotations, numbers, names, citations, and legitimate dialect or regional language.
- Treats words such as `delve`, `robust`, and `transformative` as prompts for review—not forbidden words.
- Gives a polished revision first, then a short note explaining substantive edits when useful.

## What Pantheon will not do

Pantheon does not promise a detector score or teach ways to evade AI detection, remove watermarks, hide authorship, invent personal experiences, fabricate citations, or violate academic and workplace policies. A detector result is not a measure of writing quality or proof of authorship.

## Install in one step (recommended)

This method works with **Codex, Claude Code, Hermes Agent, and OpenClaw**. It needs Node.js, which many developer tools already install. Open a terminal, paste this command, and press Enter:

```bash
npx skills add bunnyputih/pantheon --skill humanize-ai-writing --global --agent codex --agent claude-code --agent hermes-agent --agent openclaw --copy
```

When asked, choose **Copy** and confirm the installation. Close and reopen your AI tool afterwards.

Want it in only one tool? Replace the four `--agent …` parts with one of these:

| Tool | Use this part |
| --- | --- |
| Codex | `--agent codex` |
| Claude Code | `--agent claude-code` |
| Hermes Agent | `--agent hermes-agent` |
| OpenClaw | `--agent openclaw` |

For example, to install only in Codex:

```bash
npx skills add bunnyputih/pantheon --skill humanize-ai-writing --global --agent codex --copy
```

The command uses the open-source [Skills CLI](https://github.com/vercel-labs/skills). It downloads the skill from this repository and places it in the correct folder for the selected tool.

## No-terminal installation

If you do not want to run a command, use this method instead.

1. On this GitHub page, click the green **Code** button, then choose **Download ZIP**.
2. Open the downloaded ZIP file. You will see a folder named `pantheon`.
3. Copy the whole `pantheon` folder into the matching folder below. If the parent folders do not exist, create them.
4. Rename the copied `pantheon` folder to `humanize-ai-writing`.
5. Close and reopen your AI tool.

| Tool | Folder to open on Mac/Linux | Folder to open on Windows |
| --- | --- | --- |
| Codex | `~/.codex/skills/` | `C:/Users/YourName/.codex/skills/` |
| Claude Code | `~/.claude/skills/` | `C:/Users/YourName/.claude/skills/` |
| Hermes Agent | `~/.hermes/skills/` | `C:/Users/YourName/.hermes/skills/` |
| OpenClaw | `~/.openclaw/skills/` | `C:/Users/YourName/.openclaw/skills/` |

On a Mac, you can open a hidden folder in Finder by pressing **Command + Shift + G**, pasting the folder path, and pressing Enter. On Windows, paste the path into the File Explorer address bar; replace `YourName` with your Windows account name.

After copying, check that this file exists:

```text
humanize-ai-writing/SKILL.md
```

## Use Pantheon

Start a new chat in your AI tool and write a request such as:

```text
Use the humanize-ai-writing skill to revise this client email.
Keep the facts and my direct tone. Make the request clearer without adding anything I did not say.

[paste your draft]
```

Other useful requests:

- “Audit this article for generic AI-style writing. Mark each item keep, replace, or cut.”
- “Make this project update sound like me. Here are two past updates as voice samples.”
- “Improve the flow of this academic paragraph, but preserve every citation and claim.”
- “Turn these notes into a clear announcement for parents. Ask before adding personal details.”

The more real context you provide—audience, purpose, a short voice sample, facts you can stand behind—the better Pantheon can help.

## Updating Pantheon

Run the same command again whenever a new version is published:

```bash
npx skills update humanize-ai-writing --global
```

For OpenClaw's native installer, you can also run:

```bash
openclaw skills install git:bunnyputih/pantheon@main --global
```

OpenClaw's Git installs are intentionally not tracked by `openclaw skills update`; reinstall the Git source when you want a newer version.

## Inside this repository

```text
pantheon/
├── SKILL.md                          The instructions the AI follows
├── agents/openai.yaml                Codex display metadata
└── references/
    ├── research-evidence.md          Applied research guidance
    └── research-corpus-2020-2026.md  140-paper source corpus
```

## Research basis

Pantheon draws from research on text style transfer, factuality, human evaluation, authorship attribution, detector limits, and human–AI co-writing. The full, linked [140-paper corpus](references/research-corpus-2020-2026.md) records 20 relevant sources per year from 2020 through 2026.

Key implications for practice:

- Human writing cannot be reduced to a blacklist of words or punctuation marks.
- Voice is strongest when it comes from an author's real evidence, choices, and context.
- The safest revision protects semantic and factual fidelity before changing style.
- Detector scores are unstable across genres, languages, models, and degrees of editing.

## Safety and privacy

Only install skills from sources you trust. Before using Pantheon with private material, check your AI tool's privacy settings and your organization's policy. Do not paste confidential, regulated, or personal information into any service unless you are authorized to do so.

## Contributing

Suggestions and corrections are welcome. Please open an issue with the text type, the problem you noticed, and a short example with sensitive information removed.
