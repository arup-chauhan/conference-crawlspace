# Conference Research Guide

A portable Agent Skill for guided conference research. It helps an assistant recommend talks, inspect available material, investigate related community discussions, explain the ideas using simple models and illustrations, and produce cited research artifacts.

## Install

Copy the `conference-research-guide` folder in your agent's supported skills directory. For Codex, use `$CODEX_HOME/skills`, or `~/.codex/skills` when `CODEX_HOME` is unset. Preserve `SKILL.md`, `agents/`, and `references/` together. If a skill with the same name already exists, back it up before replacing it.

## Start

```text
Use $conference-research-guide for [conference URL].
I'm interested in [topic] because [goal].
Help me choose material and create [report or presentation].
```

You can start with just a topic, ask to list tracks, or supply your own slides. Say "choose for me" to delegate decisions. Add interests during the conversation without restarting.

## Requirements

The host needs to support loading Agent Skills. Browsing is needed for live discovery. Local file/download capabilities are needed to collect originals. Word, PDF, and presentation outputs depend on the host's installed authoring tools. Markdown is the lightweight fallback. The package contains instructions, not a standalone crawler or application, and requires no particular vendor account or API key.

## Explanatory output

For a learning deck, ask: “Explain the relevant talks with simple models and illustrations. Include source pages, reported outcomes and limits.” The workflow builds source briefs before storyboarding. Suggestions and benchmark plans follow the explanations when requested.

## Optional Solutions Showcase research

After identifying the event and goal, the skill offers a separate question: “Would you also like me to crawl the Solutions Showcase for relevant products and announcements?” Say Yes to include it or No to keep product discovery out of scope. You can also request it directly.

Included research distinguishes new launches, feature updates, existing demos, previews and unclear cases. Findings explain the mechanism, relevance to your workload, technical evidence, tradeoffs and possible benchmarks. Product claims are not treated as measured improvements.

## Evidence and privacy

The workflow distinguishes abstracts from inspected slides, source claims from reproduced results, and proposed experiments from measurements. Keep research state and downloaded material in a task workspace. This shared package contains no research history, credentials, or personal configuration.
