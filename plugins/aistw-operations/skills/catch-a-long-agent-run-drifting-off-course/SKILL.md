---
name: catch-a-long-agent-run-drifting-off-course
description: "Catch a long agent run drifting off course. Write the goal and what done looks like in 3 lines before the run. Every few steps, have the agent restate the goal, list what it changed, and compare."
---

# Catch a long agent run drifting off course

## When to use

Owners running agents on long tasks, such as cleaning a list, building a report or updating many records, who find the final result is not what they meant.

## Steps

1. Before the run, write the goal, what done looks like, and what must not change, in 3 lines.
2. Add the checkpoint rules from the prompt below to the task.
3. Set a stopping condition, such as a maximum number of steps. Anthropic's guide to building agents describes checking progress against real results at each step, pausing for human feedback at checkpoints, and using stopping conditions like iteration limits.
4. At each checkpoint, read the agent's goal check. If it has drifted, stop and restate the goal.
5. When a tool or setting changed recently, run a small test task first and compare with a past result.
6. Keep the 3-line goal with the output so you can check the end result against it.

## What to ask the user for

- ONE LINE
- 30

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Add these rules to this task:

Goal: [ONE LINE]
Done looks like: [ONE LINE]
Must not change: [ONE LINE]

1. Every [5] steps, stop and report: the goal in your own words, what you changed since the last check, and whether each change serves the goal (yes or no, with a reason).
2. If any answer is no, or you are unsure, pause and ask me before continuing.
3. Stop after [30] steps in total and report, even if not finished.
4. Before anything that cannot be undone, stop and ask.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- No written goal, so there is nothing to check against.
- Reading only the final output.
- Letting the agent judge its own drift without evidence of what it changed.

## Source

https://www.aisetupsthatwork.com/setups/catch-a-long-agent-run-drifting-off-course/ (AI Setups That Work)
