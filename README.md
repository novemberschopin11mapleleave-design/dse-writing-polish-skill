# DSE Writing Polish Skill

A platform-agnostic skill for polishing HKDSE English writing through **tone-aware rewriting** and **contextual vocabulary replacement**.

## Features

- Rewrite sentences and paragraphs for a specified genre and audience
- Adjust formality, tone, and register without changing the original meaning
- Replace weak or repetitive words with contextual alternatives
- Preserve facts, opinions, examples, and the student's voice
- Support articles, letters, emails, reports, speeches, proposals, reviews, blogs, leaflets, and essays

## Repository structure

```text
.
├── README.md
├── SKILL.md
├── references/
│   └── style-notes.md
└── examples/
    └── article-rewrite.md
```

## Installation

### Claude Code

Place `SKILL.md` under a Claude Code skills directory, for example:

```text
.claude/skills/dse-writing-polish/SKILL.md
```

Rename the skill directory or package as your harness requires.

### Codex

Place the skill in your Codex-compatible skills directory, for example:

```text
.agents/skills/dse-writing-polish/SKILL.md
```

Then load or invoke the skill with the user's target genre, tone, audience, and source text.

### DeepSeek and other harnesses

Use `SKILL.md` as a dedicated system/developer instruction, or copy it into the harness-specific skill or prompt configuration.

## Example prompt

```text
Please rewrite this paragraph for a formal school proposal.
Audience: school principal and teachers
Tone: polite, practical, and direct
Keep all facts and opinions exactly as they are.
Do not add research or invented examples.

[Paste paragraph]
```

## Future work

This project currently focuses on rewriting and vocabulary assistance. The following features are planned:

- HKDSE Writing assessment and band estimation
- Task-response analysis
- Word-count-aware compression and expansion
- Genre structure checker
- DSE-specific revision exercises
- Optional official-source grounding
- Multiple-platform example configurations

## Scope

This skill does not provide exam marking or an official HKEAA score. It is a writing assistance tool and is not affiliated with or endorsed by HKEAA.
