# Conference Research Guide

Research conference talks through short questions and useful suggestions. Understand the ideas, explore related material, and create reports or slides with sources.

## Install

Copy `conference-research-guide/` into your agent's supported skills directory. Keep `SKILL.md`, `agents/`, and `references/` together.

For Codex, use `$CODEX_HOME/skills`. When `CODEX_HOME` is unset, use `~/.codex/skills`.

Back up an existing skill with the same name before replacing it.

## Start

```text
Use $conference-research-guide for [conference URL].
I'm interested in [topic] because [goal].
Help me choose material and create [report or presentation].
```

You can also start with a topic or your own slides. Ask for tracks, compare talks, or add interests as you go.

Say “choose for me” to delegate decisions.

## Tools you need

Your agent must support skills. Live discovery needs browsing. Collecting originals needs download and file tools.

Word, PDF, and presentation output depend on the tools available. Markdown is a simple fallback.

This package provides instructions. It does not install an application or require a specific vendor account or API key.

## Learn from the talks

For a learning deck, ask:

> Explain the relevant talks with simple models and illustrations. Include source pages, reported outcomes, and limits.

The skill inspects source material and prepares a brief for each talk. It explains the ideas before adding recommendations or experiments.

## Optional Solutions Showcase research

The skill offers a separate question once the event and goal are known:

> Would you also like me to crawl the Solutions Showcase for relevant products and announcements?

Say **Yes** to include it or **No** to skip it. You can also request it directly.

Product findings distinguish launches, updates, existing demos, and previews. They explain how a product works, its possible fit, its tradeoffs, and what needs testing.

Advertised improvements remain claims until supported by suitable evidence.

## Sources and privacy

The skill records what it actually inspected. An abstract, a slide deck, and a reproduced result provide different evidence.

Keep research records and downloads in a separate task workspace. This shared package contains no personal research history, credentials, or private configuration.
