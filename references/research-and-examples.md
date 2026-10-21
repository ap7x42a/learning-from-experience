# Research and examples

Use this reference for the rationale and ambiguous cases. The examples below are
illustrative, not recorded project results. Apply the workflow to the current
project; no particular simulator, repository, or memory product is required.

## What the papers establish

### The Geometry of Empowerment

Ji, Myers, Levine, and Eysenbach,
[arXiv:2610.07796v1](https://arxiv.org/html/2610.07796v1), especially §§3–4
and Appendices F–H.

The paper distinguishes maximum attainable controllability from the mutual
information realized by a particular skill-conditioned policy. Its adaptation
bound uses a specified reward prior; greater empowerment does not generally rank
task performance. Continuous state spaces and uneven reward preferences expose
further gaps between distinguishable outcomes and valuable outcomes.

The operational implication we draw is to assess selection and task value
separately from the number or diversity of available options. This is our
application of the theory, not a retrieval-scoring algorithm supplied by it.

### Is this machine playing?

Cloos, Norelli, Durbin, Andreas, Rus, and Isola,
[arXiv:2610.07130v1](https://arxiv.org/html/2610.07130v1), especially §5
and Appendices C.8, E, and F.

The Eko agents use fixed-weight models and accumulate written memories while
exploring a simulated world. Subsequent task performance generally improves, and selected memory
interventions change outcomes: removing useful knowledge can impair performance,
removing a false belief can improve it, and a technique can help one goal while
hurting another. These interventions repeat tests of three selected memory
histories. They do not establish play's superiority over equally budgeted
alternative learning strategies or broad transfer beyond the studied setting.

The operational implication we draw is that memory contents can change the
deployed agent's capabilities and choices, including mistaken ones. Storage and
retrieval success alone do not demonstrate useful learning.

## Reading them together

Exploration can discover an option, memory can preserve it, and later use can
reveal its value. These are distinct steps with distinct failure modes. A finding
can deserve retention before its eventual application is known. Evidence of
delayed transfer is different from an assertion that every retained possibility
will pay off.

Under a fixed environment, start state, and unrestricted policy class, discovering
an existing technique does not automatically enlarge theoretical channel
capacity. It can improve what a particular deployed agent knows how to do. The
Eko study does not measure empowerment, so equating its behavioral gains with increased
mutual information would go beyond the evidence.

With perfect selection, adding an optional method cannot lower the best available
task reward. Real agents can choose poorly, become overconfident, or overuse a
salient technique. Assess both whether a capability is available and whether its
selection helps. A single label such as "verified" cannot answer both questions.

## Supplied premises and independent attempts: Mahler

OpenAI's [abridged Mahler reasoning summary](https://github.com/openai/math/blob/fd4aeeb2ee4fc729c18d98444fed42fd0529eeeb/reasoning_traces/symmetric-and-general-mahler-conjectures.pdf)
separates three attempts. Part I addresses the symmetric lower bound. Part II
receives that bound as a premise and investigates equality cases; it does not
identify its premise with Part I's particular proof. Part III develops a separate
general-body argument. This is a case study for organizing claims, not a
controlled evaluation of a workflow or independent confirmation of the proofs.

The following hypothetical correction illustrates how to preserve those distinctions:

| Record | What it establishes or assumes | Relationship to preserve |
|---|---|---|
| Attempt A | Offers a proof of P | A supplies proposed support for P. |
| Attempt B | Argues that Q follows if P holds | P was supplied; B's conditional argument has its own source and assumptions. |
| Attempt C | Investigates R through a separate argument | Record C's actual premises without inventing a dependency on A or B. |

Suppose a flaw defeats A's proof. Withdraw that proof's support for P; this does
not establish that P is false. B's conditional argument can remain useful if its
own reasoning is sound. An unconditional endorsement of Q that relied on A needs
reconsideration, including any other support for P. C is affected only if an
actual shared premise or dependency is implicated. Preserve a reusable technique
from A separately from its failed application, with its remaining limits.

In ordinary memory, state who supplied P, its scope, and whether a record asserts
Q or only the conditional argument. Use existing graph reasoning when explicit
alternatives and dependencies help the task. A dependency relationship says that
a conclusion relies on a premise; a support link merely identifies evidence. It does not establish that a source is
necessary or independent. When a correction could affect later notes, use the
store's supported reverse-reference lookup, or inspect linked notes manually.
State its coverage limits. Inspect each actual claim before revising it; do not
retract every citing note automatically.

Keep verification attached to the exact claim, assumptions, source version, and
check performed. The [Mahler formalization scope](https://github.com/openai/math/blob/fd4aeeb2ee4fc729c18d98444fed42fd0529eeeb/lean/docs/087.md)
excludes functional inequalities from the selected statements and does not assert
a symplectic embedding at capacity exactly four. A check of a selected statement
does not cover those extensions. Likewise, a storage system's quote validation or
fixed-rule execution does not establish the truth of a caller's interpretation.
Repeated self-review alone does not supply independent evidence.

## Three application examples

### A possibility with no immediate application

During an authorized exploration, a restart appears to resume an interrupted
transfer. There is one partial trace and no check of output completeness. The
current task does not require interruption recovery.

Preserve the trace and the tentative interpretation. Identify completeness and
repeatability as unresolved. Leave a possible later check discoverable without
claiming recovery is reliable or scheduling work that was not requested. Its
non-use on this task is not evidence against it.

### Accurate knowledge, different objective

A measured bulk-import comparison supports batching independent requests for
throughput. A later task concerns the first visible response in an interactive
screen.

Keep the original finding. Compare the new objective and workload with the test
conditions. Select an appropriate approach, or check the latency effect if that
uncertainty matters. Do not transfer the throughput conclusion directly into a
latency recommendation or mark the source false because another method fits.

### A remembered restriction meets contrary evidence

An old note says an operation cannot work, based on a failed attempt. A current
trace shows it succeeding with different input settings.

Inspect both records. The original failed attempt can remain true while its
universal interpretation is wrong. Record the successful conditions, narrow or
supersede the broad interpretation, and preserve the evidence for each case.
Neither result establishes behavior under conditions that were never checked.

## When evaluating the workflow itself

Use cases that can expose wrong decisions, including the examples above in new
forms. Inspect actual choices and saved claims rather than checking headings or
phrase matches. A worked example is not a controlled demonstration of improvement.

For a causal claim about a memory's benefit, compare relevant outcomes under
matched conditions with intact memory, the relevant claim removed or corrected,
and an unrelated edit when needed to distinguish a content effect from an editing
effect. Keep the task, execution opportunity, and budget comparable. This is an
optional experiment design, not a requirement for ordinary recording or reuse.
Report the evaluated cases and uncertainty; do not infer general reliability
from one successful example or treat a supplied correction as independent discovery.
