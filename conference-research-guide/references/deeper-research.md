# Deeper research

Read the sections relevant to the user's questions. Look across tracks when the evidence requires it.

## Community and working-group material

Identify the exact group and organization. A conference track, CNCF group, Kubernetes WG, SIG, and vendor community are different entities. Similar names do not prove they are the same group.

Start with an official community directory or project repository. Follow links to agendas, minutes, recordings, proposals, and issues.

Check dates and document sections. For each useful item, report the topic, status, supporting material, and relevance.

Keep these states distinct: proposed, discussed, accepted, implemented, released, and deprecated. A roadmap or open issue does not prove a feature shipped.

If meeting notes are inaccessible, say so. Use inspected proposals or abstracts at their actual evidence level. Do not present them as conclusions from an unread meeting.

## Architecture and industry examples

For a company reference, search its engineering publications and conference speakers. If several matches fit, show the candidates and explain their differences. Do not silently choose the intended reference.

Explain each architecture option through:

- The existing bottleneck.
- The mechanism that changes it.
- Required capabilities.
- Expected tradeoffs.
- A way to test it.

Distinguish established patterns from emerging proposals. A mature pattern may become useful for a new workload.

Verify current versions and feature gates in primary documentation before including them.

Keep data serving, agent orchestration, and model inference distinct. Their caches, consistency needs, scaling controls, and metrics may differ.

Model prefix or KV caching does not replace backend data freshness or access controls.

## Benchmark proposals

Turn relevant findings into a hypothesis that a test could disprove. Specify:

- Workload and comparison baseline.
- Architecture change or controller being tested.
- Variables to change and conditions to keep fixed.
- Traffic shape, concurrency, data distribution, and warm or cold state.
- Relevant measures of throughput, latency, correctness, recovery, resource use, and cost.
- The decision the result supports and what would disprove the hypothesis.

Use the same input replay and comparable hardware and versions. Repeat runs when appropriate and report variance. Do not rely on one best run.

Separate startup, steady state, and recovery. Include preparation or indexing costs when moving work off the read path. Hardware differences prevent attributing a speedup solely to software.

For autoscaling, identify the component being scaled. HPA, VPA, node autoscalers, engine executors, job admission, and job scheduling serve different purposes.

Verify supported combinations and version-specific behavior in primary documentation. Examine controller conflicts, delays, oscillation, disruption, and downstream limits.

For agent-facing read workloads, consider:

- Reads and bytes per completed task.
- Fan-out, retries, and repeated reads.
- Cache locality and changing data.
- Permission boundaries.

Hold task quality and freshness constraints constant when comparing costs. Label example traffic levels and workload multipliers as illustrative test inputs. They are not observed production measurements.

Prioritize a few experiments by workload fit, evidence, effort, and decision value. Avoid unsupported scores or claims of global novelty.
