---
name: conference-research-guide
description: "Research conference talks interactively, explain ideas with simple models and illustrations, optionally investigate Solutions Showcase products, and produce cited reports or presentations. Use for conference research, practical takeaways, architecture comparisons, and benchmark ideas."
---

# Conference Research Guide

Turn a conference program into research that answers the user's questions. Support any event, discipline, and experience level. Start with the current conversation and supplied material. Examples in this package illustrate behavior, not default interests or assumed infrastructure.

## Start with the research question

Identify what is already known: event and edition, topics or tracks, purpose, intended audience, technical context if relevant, and requested outputs. For workload optimization, establish the actual system, whether it is already deployed or being evaluated, the desired improvement, and known constraints. Keep this workload at the center as topics expand. Distinguish learning what the talks explain from choosing an architecture or designing experiments. A request to explain talks calls for educational synthesis; practical interests alone do not turn the deliverable into a benchmark plan. Ask only for information needed next, usually one or two short questions per exchange.

If the user provides only an event name and year, identify its editions and resolve the relevant one before selecting talks or downloading material. You may show a clearly labeled edition's track list while asking. If they have only a topic, browse for suitable events and offer a few verified options with reasons. Never treat an example from earlier discussion as their real environment.

Use short, plain language. Offer two or three grounded choices and accept free text. Use the host's question controls if available, or a numbered list. Do not imply that text labels are clickable buttons.

Guided mode is the default. Pause at substantive choices about scope, selection, or output. Continue independent discovery when possible, but do not treat silence as consent. When the user delegates choices, asks for all relevant material, or requests immediate completion, state reasonable assumptions and finish without routine approval checkpoints. Existing authorization persists.

## Optional Solutions Showcase crawl

Once the event and research goal are known, offer a separate optional question if the event has a Solutions Showcase, expo, exhibitor program, or equivalent:

> Would you also like me to crawl the Solutions Showcase for relevant products and announcements?

Use Yes / No choices when the host supports them. Record the choice and do not ask again unless the user changes it. An explicit request to include the showcase already answers Yes; a request to add this option to the skill does not authorize an actual product crawl. Continue talk research independently while the choice is pending.

After an opt-in, read [references/solutions-showcase.md](references/solutions-showcase.md). Research the products against the same user goal as the talks. Distinguish new launches, feature updates, existing-product demos, and previews using dated evidence. Keep advertised claims separate from inspected technical capabilities and independently measured results.

## Available capabilities and portability

This is a conversational research workflow. It does not install a crawler, run a background service, or create a web application by itself.

- Use the host's browsing/search tools and connected sources where available. No vendor-specific connector or API key is a prerequisite.
- If live research is unavailable, work with supplied URLs, files, or extracts, and state the coverage limit. Do not imply you crawled an event you could not access.
- Use available document, PDF, and presentation skills for their respective formats. Do not assume any particular filesystem root, plugin installation, model, or rendering runtime exists.
- Keep task output in a user-selected workspace or a new task folder. Use portable relative paths within the research collection. Never write a user's research into the installed skill folder. Keep personal research collections separate from a shared skill repository. When improving the reusable skill, carry over generic workflow lessons and sanitized examples rather than a user's notes, configuration or artifacts.

## Maintain scope as the conversation evolves

Tracks are a starting point. When the user adds a goal that crosses tracks, follow that goal across the event's relevant sessions. Preserve earlier selections. Add adjacent events, community meetings, papers, or engineering posts when the user requests them or when a specific research gap warrants them. Label the expanded scope and source origin.

Prefer one focused clarification over making a consequential guess. For an ambiguous organization reference, find plausible matches and label them as candidates while asking for a title, speaker, project, or link. Expand familiar abbreviations when context makes the meaning likely and state the interpretation.

For a sustained or resumed task, maintain a compact research state and source ledger using [references/research-records.md](references/research-records.md). Keep confirmed choices separate from assumptions, and retain unresolved questions and coverage gaps.

## Discover, recommend, and refine

Browse the actual event schedule and individual talk pages. Prefer organizer, speaker, maintainer, and project sources. Verify the event edition and record the access date. A schedule page for another year or a redirect to another event does not verify the intended session.

Inspect abstracts before bulk downloads. In guided selection, present a useful shortlist, usually three to five items. When asked for all relevant talks, build a coverage inventory across the agreed topics and do not treat the shortlist size as a coverage limit. For each candidate record:

- Exact title, speaker, edition, and a direct source link.
- A specific reason it addresses the user's purpose.
- Listed audience level, or a clearly labeled inference about depth.
- Evidence inspected and material availability, such as abstract only, slides linked but unchecked, slides inspected, or recording inspected.

Do not invent talks, sources, numeric relevance scores, access claims, or popularity claims. An advertised slide link does not mean the deck downloaded or opened successfully. Paraphrase long abstracts and retain the source attribution.

Offer actions that move research forward: include/exclude, compare, explain fit, find related material, or change focus. Convert feedback into criteria and show meaningful changes without repeating the full unchanged list. Explain why a complementary item fills a gap.

When working groups, SIGs, community meetings, benchmarking, or architectural upgrades matter, read [references/deeper-research.md](references/deeper-research.md). Do not force technical evaluation onto unrelated conference research.

## Collect and inspect selected material

Follow real download links for the selected scope. Preserve original files with readable, collision-safe names. Verify that downloaded bytes form a readable PDF or presentation, rather than a login page or error response. Record the source URL, local relative path, and actual inspection status.

If access fails, record the gap and continue other items. Offer a recording, transcript, abstract-only coverage, or supplied file where useful. Do not bypass access controls or keep retrying an unchanged failure.

Use the relevant file-handling capability to inspect slides and notes. Read charts and diagrams visually when their meaning matters. A recording description is not a transcript. An abstract describes intended coverage and does not establish delivered results. Preserve source-specific units, baselines, hardware, versions, and limitations when reporting performance claims.

## Explain the material and answer the research question

For teaching, talk summaries, and explanatory reports or decks, read [references/explain-talks.md](references/explain-talks.md). Build source briefs before drafting the final artifact. Explain the problem, starting system, mechanism, outcome, and limits using substantive source material. Abstracts support selection and advertised scope, not a reconstruction of the delivered talk.

Answer research questions using the material actually inspected. Associate substantive findings with their sources and slide/page/timestamp when reliable. Separate:

- What a speaker, author, or maintainer reports.
- What you infer across sources.
- What you propose the user should test or try.

Connect related talks after explaining their individual contributions. Use simple models and illustrations to show causal steps, with analogy boundaries where they matter. Keep proposed upgrades or experiments secondary unless those are the requested main output. Explain agreements, disagreements, prerequisites, and missing evidence when they affect understanding or a decision. Do not claim an idea is globally novel because it is new to the user. Compare a proposed upgrade against the user's baseline, or label the baseline as an assumption.

## Produce and deliver artifacts

Propose a brief editable outline in guided mode. If the user already asked for immediate creation or delegated the outline, proceed with a suitable structure. Honor requested format and audience. Without a format preference, offer a Word report or use Markdown as a lightweight preview.

Use [references/deliverables.md](references/deliverables.md) for reports, benchmark plans, and presentations. Check the available authoring and animation capabilities before promising a format. If a capability is unavailable, explain the limitation and provide a practical alternative that preserves the user's objective.

Deliver links to the completed artifacts and collected originals, with a short coverage statement and material limitations. Verify local files open and references resolve. Review semantic coverage as well as file validity: can the reader explain what each covered speaker did, how it works, and what remains uncertain? A polished artifact about future research does not satisfy a request to explain inspected talks. Describe only actions actually completed. Do not publish, message others, or create an external shared resource unless that action is authorized.

## Starting examples

- "Use $conference-research-guide for [event URL]. Help me choose talks about [topic] and make a concise report."
- "Use $conference-research-guide to find architecture ideas and benchmarks from [event and edition], including relevant working-group discussions."
- "Use $conference-research-guide on these supplied slides. Compare their approaches and make an animated presentation if the available tools support it."
- "Use $conference-research-guide. I am new to [topic]. Suggest conferences, explain the options, and guide me through the choices."

For realistic interaction examples, read [references/examples.md](references/examples.md) when adapting the workflow or checking its behavior.
