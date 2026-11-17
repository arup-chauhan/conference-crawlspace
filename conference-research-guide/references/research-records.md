# Research records

Use these records for multi-step research, collection, and handoff. A short answer need not create files. Keep the records in the task workspace, separate from the installed skill. Filenames below are conventions, not required host paths.

## Research state

Maintain `research-state.json` with the event identity, user purpose, audience, confirmed preferences, assumptions, selection, requested outputs, and unresolved questions. Record the showcase choice as not yet asked, pending, included, or excluded, plus any product-research scope. Update relevant fields after a user decision or meaningful scope change. Do not store credentials or signed download tokens.

Example structure:

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

Use real user choices in actual records. `example.org` above is an illustrative placeholder, never a verified source.

## Source ledger

Maintain `sources.json` or a table with equivalent fields. Each source needs a stable local ID, title, source kind, canonical URL, event/edition if applicable, authors/speakers, access date, relevance, availability, and inspection status. Include local paths only after a file exists.

Useful source kinds: event session, presentation, recording, meeting minutes, agenda, maintainer documentation, engineering post, paper, exhibitor listing, sponsor demo, product announcement, release notes, or vendor technical documentation. Distinguish an agenda from minutes even when both share one document.

Use explicit statuses:

- `discovered`: link located, contents unchecked.
- `abstract_inspected`: abstract read, talk content unverified.
- `content_inspected`: the actual article, documentation, or minutes read.
- `downloaded`: file saved and its format verified, contents not yet inspected.
- `slides_inspected`: deck contents inspected.
- `recording_inspected`: relevant recording or transcript examined.
- `inaccessible`: the attempted resource could not be read.

Keep availability separate: slides linked, no slides located, recording linked, authentication required, or another specific observation. "No slides located" does not mean no deck exists.

For performance findings record the reported metric, unit, baseline, test conditions, versions, and source location. Use `not reported` when a condition is missing. Mark findings as `source_reported`, `inference`, or `proposed_experiment`. Never silently upgrade an advertised result into independently reproduced evidence.

For each important claim, retain enough information to trace it to one source section. Separate recommended talks from those the user actually selected.

## Output organization

A practical collection might contain:

```text
research-project/
  research-state.json
  sources.json
  originals/
  report.md
  presentation.html
```

Create only the files needed for the actual request. Use relative links for bundled originals and normal URLs for external sources. Verify that an exported archive preserves this directory structure. Resume from these records without repeating earlier onboarding.

## Product findings when showcase research is included

Keep product findings in the task workspace. Record product/vendor, event relationship, launch/update/demo/preview/unclear classification, dated novelty evidence, release availability, technical sources inspected, workload fit, tradeoffs, open questions, and proposed comparisons. Classify advertised benchmarks as source-reported unless independently reproduced. Keep the actual crawl status separate from whether the skill offers the option.
