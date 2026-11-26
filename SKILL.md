---
name: dse-writing-polish
description: Rewrite HKDSE English writing by genre and tone, preserve the student's meaning, and provide contextual vocabulary alternatives.
---

# DSE Writing Polish Skill

## Purpose

Help students improve HKDSE English Language writing through:

- genre-appropriate rewriting;
- tone and register adjustment;
- contextual vocabulary replacement;
- concise explanations of important changes;
- preservation of facts, opinions, examples, and voice.

Do not assess, score, or estimate exam levels. Do not claim that a rewrite is guaranteed to receive an official grade.

## Required inputs

Ask for, or extract from context:

1. the original text;
2. the target genre;
3. the intended audience;
4. the desired tone;
5. the requested scope: sentence, paragraph, or whole text;
6. whether the rewrite may add transition sentences or must keep the same structure;
7. whether the task asks for replacements, rewrite options, or both.

Useful optional inputs include a word limit and the original task prompt.

If critical context is missing:

- preserve the text's existing genre and purpose;
- choose a clear, natural, appropriately formal tone;
- avoid inventing facts or readers;
- state that the text was rewritten under a neutral assumption.

## Core rules

### Preserve meaning

Keep the student's original:

- stance;
- facts;
- examples;
- people and places;
- causal relationships;
- overall emphasis;
- level of confidence;
- personal voice, unless a genre requires more formal language.

Do not add:

- invented statistics;
- invented experiences;
- quotations or sources;
- stronger conclusions than the original;
- unstated consequences;
- a different recommendation or opinion.

### Adapt by genre

#### Article or blog

Use an engaging but clear style. A title may be useful. Address the reader when appropriate, while avoiding slang unless the original context is informal.

#### Formal letter or email

Use courteous, direct language. Match the recipient and purpose. Avoid unnecessary contractions or casual openings. Do not create an invented name, address, or signature unless the user supplies or requests one.

#### Speech

Retain spoken readability. Use measured repetition and direct audience references only when useful. Avoid making a speech read like a formal report.

#### Report or proposal

Emphasize purpose, findings, problems, reasons, and actionable recommendations. Keep headings and paragraphs clear. Do not present suggestions as completed actions or invent evidence.

#### Essay

Keep claims and supporting examples clear. Use transitions only where they show a real relationship. Avoid template sentences that are unrelated to the argument.

#### Review

Balance description and evaluation. Keep subjective opinions recognizably subjective. Support judgments with specific details already in the original.

#### Leaflet

Use clear headings and concise sections. Make calls to action practical and relevant. Avoid rewriting it into a long essay.

### Adjust tone deliberately

Common tone options:

- **Formal:** precise, polite, and restrained.
- **Semi-formal:** clear and courteous, suitable for staff or teachers.
- **Friendly:** warm and direct, without heavy slang.
- **Persuasive:** emphasizes reasons and benefits without exaggeration.
- **Neutral:** objective, low-emotion, and information-focused.
- **Critical:** identifies weaknesses and evidence, without personal attacks.
- **Enthusiastic:** positive and energetic while remaining credible.
- **Sympathetic:** acknowledges concerns gently and avoids melodrama.

A user may request a combination, such as “formal but approachable.”

### Improve vocabulary contextually

A replacement must be explained in context. Give more than a synonym list.

For each replacement, where useful, include:

- the original expression;
- the recommended expression;
- why it fits;
- any change in formality or intensity;
- a short example in the source sentence;
- a warning about incorrect collocation.

For example:

- **good** → **effective**: suitable when evaluating whether something works.
- **good** → **high-quality**: suitable for objects or services, but not every positive judgment.
- **bad** → **poor**: neutral and suitable for general formal writing.
- **bad** → **damaging**: stronger and suitable when an action causes harm.
- **interesting** → **thought-provoking**: suitable for ideas or discussion, not every physical object.

Do not equate rare words with good writing. Prefer accurate, natural, reusable language.

## Workflow

### Single-sentence or paragraph rewrite

1. Identify the genre, audience, and tone.
2. Identify the core claim or purpose.
3. Preserve all facts and the relative strength of the opinion.
4. Resolve only genuinely unclear or unnatural phrasing.
5. Present the rewritten version.
6. Explain 2–5 important changes, especially changes that affect tone or genre.

### Full-text rewrite

1. Preserve paragraph count unless the user requests restructuring.
2. Preserve the central argument and examples.
3. Correct grammar and collocation.
4. Improve transitions where the relationship is unclear.
5. Avoid turning the passage into a perfect model essay.
6. Mark substantial restructuring explicitly.

### Vocabulary-only request

Do not rewrite the whole sentence unless asked.

Provide alternatives with distinctions in:

- formality;
- emphasis;
- connotation;
- register;
- collocation;
- suitability for the stated audience.

## Default response format

Use this structure unless the user requests otherwise:

### Rewritten text

```text
[rewritten sentence or paragraph]
```

### Vocabulary alternatives

| Original | Alternative | Context and distinction |
|---|---|---|
| ... | ... | ... |

### Main changes

- ...
- ...
- ...

If the rewrite is based on assumptions, state them explicitly.

## Output language

Use Chinese for explanations unless the user requests another language. Keep rewritten English text in English. Do not translate the whole piece unless requested.

## Quality checks

Before responding, check:

- Did any fact or opinion change?
- Did the tone match the audience?
- Does the result fit the requested genre?
- Are alternatives natural in the exact sentence?
- Did the rewrite become more difficult or less clear?
- Is a replacement an appropriate intensity, not merely a bigger synonym?
- Is every invented or uncertain assumption disclosed?

## Limitations

- This skill assists writing; it does not mark HKDSE papers.
- It does not copy or reproduce HKEAA level descriptors or marking tables.
- It cannot verify task requirements without the original prompt or sufficient context.
- It should not invent materials that a student may later present as evidence.
