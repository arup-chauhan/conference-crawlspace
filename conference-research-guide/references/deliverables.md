# Deliverables

Choose the structure for the user's audience and intended outcome. Output formats are capabilities of the host, not capabilities installed by this skill.

## Reports

For explanatory reports, organize around the ideas taught by the source material: problem, simple model, mechanism, reported outcome, limits, and connections. Include substantive talk summaries and source locations. For decision reports, add comparisons and practical implications. Keep proposed experiments in a separate section when useful. Scale detail to the request. Full transcripts or slide reproductions are not a default deliverable.

When the host supports Word or PDF creation, use the relevant skill and its rendering/verification workflow. Otherwise produce a usable Markdown artifact with linked sources and explain any requested-format limitation. Cite substantive claims close to their text and provide a source index.

## Benchmark plans

For each experiment include the hypothesis, baseline, workload, configuration differences, fixed conditions, procedure, measurement definitions, acceptance criteria or decision rule, and limitations. Use user-provided targets when available. Do not invent measured outcomes or numeric success thresholds as if the user approved them.

An experiment matrix can compare controller type, traffic shape, dataset skew, cache state, or resource pressure. Avoid varying every factor simultaneously when that would obscure the cause of a result. Keep service workloads, batch engines, storage, and inference tests distinct where their controls differ.

## Presentations and animation

Check for live presentation sessions or supported authoring tools first. Follow the available presentation skill. Use a narrative suited to the intended outcome. For learning: concrete problem, illustrated mechanism, source example, tradeoff, and connection to other talks. For a decision: add architectural options and implications. For benchmark planning: make experiments central only when requested. Do not replace the content of talks with a list of research leads or future tests. Keep detailed sources in notes or an accessible references view. Make evidence limitations visible when needed to interpret a slide.

For animated output, determine what the actual format supports. Reveal steps to explain a process, sequence comparisons, or animate a clearly labeled illustrative workload. Animation must preserve readable content and usable navigation. Do not describe transitions as object animations or promise PowerPoint animations in a static PDF.

If native presentation animation is unavailable and the user has not required a particular format, a self-contained browser slide deck can be a useful fallback. Disclose the format, include keyboard/button navigation, a pause control for autoplay, reduced-motion behavior, and an accessible sources/notes view. Avoid external runtime dependencies if offline sharing matters. Check every slide at the intended viewport and make sources and illustrative assumptions easy to inspect.

If the user requires a specific unsupported format, explain the exact limitation instead of silently substituting an incompatible file. Preserve useful work and offer the closest available artifact.

## Delivery checks

Confirm event identity, selected scope, evidence coverage, source links, file readability, and accessible local paths. For decks inspect all slides and test navigation and animations in a supported viewer. Also compare the artifact with the source briefs and topic inventory: substantive mechanisms should be explained, key talks should be represented, and gaps should remain visible rather than filled with conjecture. For archives check that they contain the final files and exclude task-private data, caches, credentials, and personal filesystem paths.

Keep validation records out of the audience-facing content. Report relevant remaining gaps without claiming checks or reproduction work that did not happen.
