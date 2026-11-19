---
name: learning-from-experience
description: Use when a user corrects an agent's work, an exploratory trial reveals a reusable finding, a result is surprising, or remembered knowledge needs reassessment under changed conditions. Routine retrieval or recording alone does not require this workflow.
---

# Learning from Experience

Turn experience into usable, revisable knowledge. Keep what happened, what it
suggests, and whether to use it for the present goal distinguishable. A retained
possibility is an option; its application is a decision made in context.

Use the relevant parts during the user's current work, including open-ended
exploration they requested. Discoveries may have value for later tasks; recording
a lesson does not assign future work.

## When a user corrects your work

A correction calls for learning and mitigation by default. Fix the affected
answer or deliverable and carry forward the rest of the user's request. Use the
authorization already given. If the user tells you to stop a particular action,
honor that boundary while carrying out any corrective work they still request.

Trace the mistake to the decision that produced it. Compare the instructions
or inputs available at that point with the action you took. If a prompt, skill,
or code path was wrong, repair the source that future runs actually use, within
the scope of the task. If the instruction was already clear, find where it was
skipped and change how it gets applied there.

Check the corrected result against the user's request. To assess whether a
change prevents recurrence, look at the next relevant decision or exercise the
affected behavior on a comparable case. Report what you fixed, what you checked,
and what remains unverified. A written lesson preserves the finding. Evidence
of better behavior comes from what the agent subsequently does.

## Explore and notice

Follow the current task or exploration brief. An eventual application need not
be known, and every exploratory action need not start with a hypothesis. When a
surprise or recurring difficulty matters, identify the uncertainty and what
observation could distinguish plausible explanations.

Use an existing source, a direct observation, or a small comparison as the
question warrants. Match effort to the consequence of being wrong. More options,
more notes, and more activity do not themselves establish useful progress.

## Preserve a finding with its limits

For knowledge worth carrying forward, capture enough context for a future agent
to understand the claim without inheriting your assumptions:

- **Observation and source:** what was done or reported, what actually happened,
  and where the evidence can be inspected. Name whose observation or claim it is.
- **Interpretation:** the explanation, technique, or possibility the evidence
  suggests. Identify untested explanations and competing explanations that matter.
- **Conditions and limits:** the environment, inputs, version, or timing relevant
  to the result; what was not checked and what could change the conclusion.
- **Possible use:** when this might help, if known. Future usefulness can remain
  unresolved; lack of an application today does not make the finding false.

These are content distinctions, not mandatory separate records or a form for
every action. Link an interpretation to its source observation when they are
stored separately. Use the project's existing record format.
Match the conclusion to what was measured: a latency percentile, for example,
does not establish that every request meets a deadline.

For example, an illustrative finding could read: "Batching independent requests
completed the bulk import faster in the compared runs. Interactive latency and
dependent requests were not tested. Candidate technique for similar imports;
see the linked run measurements." This does not establish a general batching rule.

Keep an unsuccessful attempt scoped to what it tested. A failure under condition
C does not establish that the method can never work. Likewise, a successful
case does not establish reliability outside its evidence. Treat an agent's
inferred restriction as a claim to examine, not as an owner instruction. When
authorship is unknown, record the provenance gap instead of attributing the
restriction to the owner.

## Decide whether the finding transfers

When using remembered knowledge, inspect its evidence and compare its tested
conditions with the present goal. Keep these questions separate:

1. Is the claim supported, and how uncertain is it?
2. Do the relevant conditions match, or is this an untested extension?
3. Can the technique be executed here, and does it suit this goal better than
   the available alternatives?

Choose to apply it, adapt it with a bounded check, use another approach, or leave
it unused. Proceed within existing task authority; recalling a technique adds
neither permission to act nor an extra approval requirement. A condition mismatch
means applicability needs assessment; it does not by itself refute the original
finding or prohibit the new use.

In the batching example, a throughput result alone does not settle a decision
about interactive response time. Assess that objective before recommending the
technique. Even accurate knowledge can bias selection toward an unsuitable method.

## Record outcomes and revise interpretations

After a meaningful application or test, preserve the action, relevant conditions,
observed outcome, and how it compares with the expectation. Distinguish a reported
improvement from an observed one. Record inconclusive results as inconclusive;
non-use or lack of opportunity is not a failed trial.
A measured rejection for one objective is an outcome for that objective; it need
not refute a finding about another objective.

When evidence conflicts, examine whether the conditions differ, the original
observation was misread, or the interpretation was too broad. Keep conditionally
compatible findings together. When an interpretation is disproved or narrowed,
make the correction explicit, link its evidence, and revise or supersede the
active guidance through the existing store's supported mechanism. Preserve the
historical observation and make its corrected interpretation discoverable.

A useful technique can help one task and hurt another. Feedback about a use
should retain the task and conditions instead of becoming a universal verdict
on the technique. Keep source support, applicability, and observed usefulness
distinct even when a store also exposes a confidence score.

## Persistence and deeper checks

Use the current task's memory or knowledge system, if one is available. Follow
its documented operations for observations, evidence links, corrections, and
outcome recording. A local note with source links is sufficient when no dedicated
store is in use. Do not create a new storage system just to apply this skill.

Before relying on guidance, inspect relevant prior applications when they can
inform the present decision, checking conditions and corrected accounts. After a
meaningful use, connect the task, action, result, and contribution assessment to
the exact guidance version used. An explicitly unassessed contribution is valid.
Open full reports before relying on previews. Correct an application report by
linking or superseding the original account through the store's supported
mechanism, preserving its history.

Findings without a canonical guidance record or a known application still fit
ordinary sourced observations. Conditions and possible uses can remain in their
content. Recording is selective, not required for every action or unused result.
An application report does not automatically revise a lesson, establish causal
benefit, or enforce applicability; those judgments remain evidence-dependent.

When a contested effectiveness claim needs a designed comparison, use an
available experiment-design workflow. A routine finding does not require a
benchmark, another agent, or a fixed number of repetitions. Use the current store's
documented operations and a proportionate comparison within the task; do not
invent missing capabilities.

Read [Research and examples](references/research-and-examples.md) when evaluating
the scientific rationale, distinguishing delayed transfer from demonstrated
improvement, or working through an ambiguous application. Its Mahler example
separates a supplied premise, a conditional argument, and a failed proof's support.
The operating guidance above is a practical synthesis, not a guarantee established
by the papers.
