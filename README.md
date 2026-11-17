# Conference Crawlspace

Find useful conference talks. Understand their ideas. Create notes, reports, or slides with sources.

This repository shares the **Conference Research Guide skill**. It includes instructions and generic examples anyone can use.

## What it helps you do

- Find talks about a topic or goal.
- Choose useful sessions through short questions and suggestions.
- Inspect slides and other available sources.
- Understand ideas through simple explanations and illustrations.
- Explore related community and working-group discussions.
- Optionally research Solutions Showcase products and announcements.
- Create reports or presentations that link back to the evidence.

The skill separates speaker claims, its own conclusions, and ideas to test.

## Install

Download or clone this repository. Copy `conference-research-guide/` into your agent's supported skills directory.

Keep `SKILL.md`, `agents/`, and `references/` together. Back up an existing installation before replacing it.

For Codex, run this command from the repository when `CODEX_HOME` is unset:

```sh
cp -R conference-research-guide ~/.codex/skills/conference-research-guide
```

If `CODEX_HOME` is set, use its `skills/` directory instead.

Read the [skill guide](conference-research-guide/README.md) or [skill instructions](conference-research-guide/SKILL.md) for more detail.

## Start a conference crawl

```text
Use $conference-research-guide for [conference URL].
I want to learn about [topic] so I can [goal].
Help me choose useful talks and inspect their slides.
Explain the ideas with simple illustrations.
Create a report or presentation with sources.
```

You can start with a conference, a topic, or your own slides. Add interests as you go.

The skill asks short questions and suggests useful options. Say “choose for me” to delegate routine choices.

It asks separately before researching a Solutions Showcase. Adding that option to the skill does not start a product crawl.

## Tools you need

Your agent must support skills. Live research needs browsing tools. Downloads and file creation depend on your agent's available tools.

The package provides instructions. It does not install a crawler or run a background service.

## Keep research separate

Keep your decks, notes, questionnaires, and downloaded sources in a separate workspace. Choose that workspace's visibility yourself.

This public repository contains the reusable skill and generic examples.

## Contributing

Contributions are welcome. Fork the repository and submit a pull request.
