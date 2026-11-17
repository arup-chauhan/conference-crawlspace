# Research records

Use these records for sustained research, source collection, and handoff. A short answer need not create files.

Keep records in the task workspace, separate from the installed skill. The filenames below are conventions, not required host paths.

## Research state

Maintain `research-state.json` with:

- Event identity, user goal, and audience.
- Confirmed preferences and assumptions.
- Selected sources and requested outputs.
- Open questions and coverage gaps.

Record the showcase choice as not yet asked, pending, included, or excluded. Include any product-research scope.

Update the record after a user decision or meaningful scope change. Never store credentials or signed download tokens.

Example:

```json
{
  "schema_version": 1,
  "event": {"name": "Example Conference", "edition": "2026 North America", "url": "https://example.org/event"},
  "goal": "Compare scaling approaches for a streaming ingestion service",
  "audience": "Platform engineers",
  "confirmed": {"topics": ["data processing", "autoscaling"], "mode": "guided"},
  "assumptions": [],
  "selected_source_ids": [],
  "outputs": [{"format": "markdown", "depth": "concise"}],
  "open_questions": ["Which workload is the primary benchmark target?"],
  "coverage_gaps": [],
  "updated_at": "2026-11-15"
}
```

Use real choices in actual records. The `example.org` address is illustrative, not a verified source.

## Source ledger

Maintain `sources.json` or an equivalent table. For each source, record:

- Stable local ID, title, and source kind.
- Canonical URL, event and edition if relevant, and authors or speakers.
- Access date and relevance.
- Available material and actual inspection status.

Add a local path only after the file exists.

Useful source kinds include sessions, presentations, recordings, minutes, agendas, documentation, engineering posts, papers, exhibitor listings, demos, announcements, and release notes.

Distinguish an agenda from minutes, even within the same document.

Use explicit statuses:

- `discovered`: link found; contents unchecked.
- `abstract_inspected`: abstract read; talk content unverified.
- `content_inspected`: article, documentation, or minutes read.
- `downloaded`: file saved and format verified; contents not yet inspected.
- `slides_inspected`: deck contents inspected.
- `recording_inspected`: relevant recording or transcript examined.
- `inaccessible`: attempted source could not be read.

Record availability separately: slides linked, no slides located, recording linked, or authentication required. “No slides located” does not mean no deck exists.

For performance findings, record the metric, unit, baseline, test conditions, versions, and source location. Use `not reported` for missing conditions.

Label findings as `source_reported`, `inference`, or `proposed_experiment`. Do not turn an advertised result into independently reproduced evidence.

Keep enough detail to trace each important claim to a source section. Distinguish recommended talks from those the user selected.

## Output organization

A collection might contain:

```text
research-project/
  research-state.json
  sources.json
  originals/
  report.md
  presentation.html
```

Create only files needed for the request. Use relative links for bundled originals and normal URLs for external sources.

Check that exported archives preserve the directory structure. Resume from these records without repeating earlier setup questions.

## Product findings after showcase opt-in

Keep product findings in the task workspace. Record:

- Product, vendor, and connection to the event.
- Launch, update, demo, preview, or unclear classification.
- Dated evidence of what is new and when it is available.
- Technical sources inspected and their links.
- Workload fit, tradeoffs, open questions, and proposed comparisons.

Label advertised benchmarks as source-reported unless independently reproduced. Record actual crawl progress separately from whether the skill offers a showcase option.
