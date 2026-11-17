# Deeper research

Read the sections relevant to the user's questions. A track label should not prevent finding evidence in another track.

## Community and working-group material

Resolve the exact group and organization. A conference track, CNCF group, Kubernetes WG, SIG, and vendor community are different entities. Similar names do not establish identity.

Start from an official community directory or project repository and follow its agenda, minutes, recordings, proposals, and issue links. Check dates and document sections. For each useful item report the discussion topic, status, supporting material, and relevance to the user's goal.

Distinguish these states: proposed, discussed, accepted, implemented, released, and deprecated. A roadmap presentation or open issue does not establish a completed release. If meeting notes are inaccessible, say so and use inspected public proposals or conference abstracts with their actual evidence level. Do not describe those as conclusions from the unread meeting.

## Architecture and industry examples

For a company reference, search that company's engineering publications and its conference speakers. When several matches are plausible, show candidates and explain their differences. Do not silently pick one as the user's intended reference.

Describe each architecture option in terms of the existing bottleneck, the mechanism that changes it, required capabilities, expected tradeoff, and a way to test it. Distinguish mature patterns newly relevant to the workload from emerging proposals. Include current versions or feature gates only after verifying primary documentation.

Keep data/query serving, agent orchestration, and model inference conceptually separate. They may have different caches, consistency requirements, scaling controls, and metrics. Prefix/KV caching of model computation does not replace the backend's data freshness or authorization handling.

## Benchmark proposals

Turn relevant material into a falsifiable hypothesis rather than a list of technologies. Specify:

- The workload and comparison baseline.
- The architectural change or controller being evaluated.
- Independent variables and deliberately fixed conditions.
- Traffic shape, concurrency, dataset distribution, and warm/cold state.
- Throughput and latency distributions, correctness, recovery, resource use, and cost measures relevant to that workload.
- The decision the result will support and what would disprove the hypothesis.

Use identical input replay, comparable hardware and versions, and several repeated runs when appropriate. Record variance rather than relying on a single best run. Separate startup time, steady state, and recovery. Include preparation/indexing costs when moving work off the read path. Do not interpret cross-hardware speedups as software-only gains.

For autoscaling, identify the component being scaled. HPA, VPA, node autoscalers, engine-managed executors, job admission, and distributed-job scheduling are not interchangeable. Confirm supported combinations and version-specific semantics in primary documentation. Examine conflicts between controllers, scaling delay, oscillation, disruption, and downstream limits.

For agent-facing read workloads, consider reads and bytes per completed task, fan-out, retries, repeated reads, cache locality, changing data, and permission boundaries. Hold answer/task quality and freshness constraints constant when assessing cost improvements. Label workload multipliers and example traffic levels as illustrative test inputs rather than observed production measurements.

Prioritize a small set of experiments by fit to the user's workload, evidence quality, implementation effort, and likely decision value. Avoid unsupported numeric ranking or a claim that a suggested experiment is globally novel.
