---
name: conference-research-guide
description: "Find conference talks, explain their ideas simply, and create reports or slides with sources. Use for conference research, practical takeaways, architecture comparisons, and benchmark ideas. Includes optional Solutions Showcase research."
---

# Conference Research Guide

Turn conference material into answers to the user's questions. Support any event, subject, or experience level.

Start with the conversation and supplied material. Examples show how to work; they do not define the user's interests or infrastructure.

## Start with the research question

Establish what is already known:

- Event and edition.
- Topics or tracks.
- Goal and audience.
- Relevant technical context.
- Requested output.

For optimization work, establish the actual system and whether it is already deployed. Identify the desired improvement and known constraints. Keep that workload central as the topic expands.

Distinguish learning from architecture decisions and experiment planning. A request to explain talks needs explanations of the source material. Practical interests alone do not make it a benchmark plan.

Ask only for information needed next. Usually ask one or two short questions per exchange.

If given only an event name and year, identify its editions. Resolve the edition before choosing talks or downloading material. You may show one edition's track list while asking, with its edition clearly labeled.

If given only a topic, find suitable events. Offer a few verified options and explain their fit. Never treat an earlier example as the user's real environment.

Use short sentences, familiar words, and clear spacing. Offer two or three grounded choices and accept free text. Use the host's question controls when available, or a numbered list. Do not present plain text labels as clickable buttons.

Use guided mode by default. Pause for meaningful choices about scope, selection, or output. Continue independent discovery where possible; silence is not consent.

When the user delegates choices or requests immediate completion, state reasonable assumptions and finish. Do the same when they ask for all relevant material. Avoid routine approval checkpoints. Existing authorization still applies.

## Offer an optional Solutions Showcase crawl

Once the event and goal are known, check for a showcase, expo, or exhibitor program. If one exists, ask separately:

> Would you also like me to crawl the Solutions Showcase for relevant products and announcements?

Use Yes / No choices when supported. Record the answer. Ask again only if the user changes it.

A direct request to include the showcase already means Yes. A request to add this option to the skill does not authorize a product crawl. Continue talk research while the choice is pending.

After an opt-in, read [solutions-showcase.md](references/solutions-showcase.md). Apply the same research goal to products and talks.

Use dated evidence to distinguish launches, updates, existing demos, and previews. Keep advertised claims separate from inspected capabilities and independently measured results.

## Use the tools available

This skill provides a conversational research workflow. It does not install a crawler, run a background service, or create an application.

Use the host's browsing tools and connected sources where available. No specific vendor connector or API key is required.

If live research is unavailable, use supplied links, files, or extracts. Explain the coverage limit. Do not claim to have crawled an inaccessible event.

Use available document, PDF, and presentation skills for those formats. Do not assume a particular local path, plugin, model, or rendering tool exists.

Keep outputs in the user's chosen workspace or a new task folder. Use relative paths within the research collection.

Keep research separate from the installed skill and shared skill repository. Improve the shared skill using generic lessons and examples with personal details removed.

## Follow changes in scope

Tracks are a starting point. Follow added goals across relevant sessions while preserving earlier selections.

Include nearby events, community meetings, papers, or engineering posts when requested. Also use them to fill a specific research gap. Label the expanded scope and each source's origin.

Ask a focused question before making a consequential guess. For an ambiguous company reference, find plausible matches and label them as candidates. Ask for a title, speaker, project, or link while continuing independent work.

Expand abbreviations when their meaning is reasonably clear. State your interpretation.

For sustained or resumed work, read [research-records.md](references/research-records.md). Keep a compact research state and source ledger. Separate confirmed choices from assumptions. Retain open questions and coverage gaps.

## Discover and refine the selection

Browse the actual schedule and individual talk pages. Prefer organizer, speaker, maintainer, and project sources.

Verify the event edition and record the access date. Another year's schedule or an unrelated redirect does not verify a session.

Inspect abstracts before bulk downloads. In guided mode, offer a useful shortlist, usually three to five items. For requests covering all relevant talks, build a broader coverage inventory. The shortlist size is not a coverage limit.

For each candidate record:

- Exact title, speaker, edition, and direct source link.
- Why it serves the user's goal.
- Listed audience level, or a labeled estimate of depth.
- Available material and what was actually inspected.

Use clear evidence labels: abstract only, slides linked but unchecked, slides inspected, or recording inspected.

Do not invent talks, sources, relevance scores, access claims, or popularity claims. A slide link does not prove the file downloaded or opened. Paraphrase long abstracts and preserve attribution.

Offer useful next actions: include, exclude, compare, explain fit, or find related material. Turn feedback into selection criteria. Show meaningful changes without repeating an unchanged list.

Explain the gap filled by a complementary source. When working groups, SIGs, architecture upgrades, or benchmarking matter, read [deeper-research.md](references/deeper-research.md). Avoid forcing technical evaluation onto unrelated research.

## Collect and inspect material

Follow real download links for the selected scope. Save originals with readable names that avoid collisions.

Verify that each download is a readable PDF or presentation. A login page or error response is not a deck. Record the URL, relative local path, and inspection status.

If access fails, record the gap and continue with other material. Where useful, offer a recording, transcript, abstract-only coverage, or a supplied file. Do not bypass access controls or repeat an unchanged failure.

Use the relevant tools to inspect slides and notes. Read diagrams and charts visually when their meaning matters.

A recording description is not a transcript. An abstract describes planned coverage, not verified talk content.

For performance claims, preserve units, baselines, hardware, versions, and limitations.

## Explain the ideas and answer the question

For teaching, summaries, reports, or decks, read [explain-talks.md](references/explain-talks.md). Build source briefs before drafting the output.

Use substantive source material to explain the problem, starting system, mechanism, outcome, and limits. Abstracts support selection; they cannot reconstruct a delivered talk.

Link substantive findings to reliable source pages, slides, or timestamps. Keep these distinct:

- What the speaker or author reports.
- What you infer across sources.
- What you propose testing or trying.

Explain each source's contribution before connecting talks. Use simple models and illustrations to show how the mechanism works. State where an analogy stops being accurate.

Keep upgrades and experiments secondary unless they are the requested main output. Explain disagreements, prerequisites, and missing evidence when they affect understanding or decisions.

An idea new to the user is not necessarily globally novel. Compare upgrades with the user's baseline. If that baseline is assumed, label it.

## Create and deliver the output

In guided mode, propose a brief outline the user can edit. If they requested immediate creation or delegated the outline, proceed.

Honor the requested format and audience. Without a format preference, offer Word or use Markdown for a simple preview.

Read [deliverables.md](references/deliverables.md) for reports, benchmark plans, and presentations. Check available authoring and animation tools before promising a format.

If a tool is unavailable, explain the limit. Provide a practical alternative that serves the same goal.

Deliver links to completed outputs and collected originals. Include a short coverage statement and material limitations. Verify that local files open and references resolve.

Check meaning as well as file validity. Can the reader explain what each covered speaker did, how it works, and what remains uncertain? A polished plan for future research does not replace explanations of inspected talks.

Report only completed actions. Publish, message others, or create an external shared resource only when authorized.

## Starting examples

- “Use $conference-research-guide for [event URL]. Help me choose talks about [topic] and make a concise report.”
- “Use $conference-research-guide for [event and edition]. Find architecture ideas, benchmark approaches, and relevant working-group discussions.”
- “Use $conference-research-guide on these slides. Compare the approaches and make an animated presentation.”
- “Use $conference-research-guide. I am new to [topic]. Suggest conferences and guide me through useful choices.”

Read [examples.md](references/examples.md) when adapting the workflow or checking its behavior.
