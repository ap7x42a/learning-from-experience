# Learning from Experience

An agent skill for turning observations into knowledge that can be reused,
checked, and revised. It helps an agent distinguish what happened, what the
evidence supports, and whether a finding applies to the current task.

Use it when an experiment reveals something reusable, a result is surprising,
or an old lesson meets new conditions. Routine retrieval or note-taking alone
does not require the workflow.

## What it helps with

- Preserve an observation with its source, conditions, and limits.
- Separate a plausible interpretation from an established result.
- Assess whether a technique transfers to a different goal or environment.
- Correct overbroad lessons while retaining the original evidence.
- Record an application's outcome without assuming the lesson caused it.

For example, a batch import can become faster while interactive response time
gets worse. The skill helps preserve the throughput finding without turning it
into a universal recommendation to batch every request.

## Install

The repository root is a self-contained skill directory. It includes `SKILL.md`,
UI metadata in `agents/`, and a supporting reference in `references/`.

For Codex, clone it into your personal skill directory:

```sh
git clone https://github.com/ap7x42a/learning-from-experience.git \
  "${CODEX_HOME:-$HOME/.codex}/skills/learning-from-experience"
```

If that destination already exists, clone elsewhere and compare it with your
existing copy before updating. Start a new session so the skill can be discovered.

For another agent that supports `SKILL.md` skills, place the whole directory in
that agent's skill location. The instructions have no runtime or storage-service
dependency; use an existing knowledge store or ordinary sourced notes.

## Use

```text
Use $learning-from-experience to examine this result, preserve what the evidence
supports, and assess whether it applies to the current task.
```

The skill can also be selected automatically when its description matches the
task. It does not schedule experiments, grant new permissions, or require
persistence for every action.

Read [the skill](SKILL.md) for the workflow and
[research and examples](references/research-and-examples.md) for its rationale,
limits, and worked cases. The workflow is a practical synthesis; the cited
research does not establish that this particular skill improves every agent.

## License

[MIT](LICENSE).
