# Conference Crawlspace

A reusable skill for turning conference talks into clear explanations and useful research.

This public repository contains the **Conference Research Guide skill** and generic usage examples. Research collections, downloaded slides, personal notes, questionnaires, decks and implementation plans belong in a separate workspace or repository with the visibility chosen by its owner.

## Install

Download or clone this repository, then copy `conference-research-guide/` into your agent’s supported skills directory. Keep `SKILL.md`, `agents/` and `references/` together. Back up an existing installation before replacing it.

For Codex, when `CODEX_HOME` is unset, run from this repository:

```sh
cp -R conference-research-guide ~/.codex/skills/conference-research-guide
```

See the [skill guide](conference-research-guide/README.md) and [skill instructions](conference-research-guide/SKILL.md).

## Start a conference crawl

```text
Use $conference-research-guide for [conference URL].
I want to learn about [topic] so I can [goal].
Help me choose relevant talks, inspect their slides, explain the mechanisms
with simple illustrations, and create a cited report or presentation.
```

Start with a conference, a topic, or supplied slides. The skill asks focused questions, offers grounded suggestions, and preserves your choices as the research expands. Say “choose for me” to delegate routine choices.

It can investigate related working-group discussions and optionally crawl a Solutions Showcase for relevant products and announcements. A showcase crawl requires an opt-in. Source claims, cross-source inferences and proposed experiments remain distinct.

## What is included

- Interactive conference and topic discovery.
- Source collection and inspection records.
- Explanations using simple models and illustrations.
- Optional product research and practical comparisons.
- Guidance for cited reports and presentations.

The skill is an instruction package, not a hosted crawler or background service. Live research and artifact formats depend on the tools available in the host. No personal account, production configuration or conference collection is bundled.

## Contribute

Improve the reusable workflow or add generic examples. Keep personal research, downloaded third-party decks, credentials and environment-specific configuration out of contributions.
