---
name: backwards-project-deadlines-from-launch
description: "Plan project deadlines backwards from launch. Give AI your launch date and the phases of the project. It works backwards, assigns real dates to each phase, and tells you when you must start. If that start date already passed, you have a scope problem, not a motivation problem. Use when the user asks for help with this job."
---

# Plan project deadlines backwards from launch

## When to use

Anyone running a project with a hard deadline: launches, events, renovations, client deliverables.

## Steps

1. Write down the launch date. Not a range. A date.
2. List every phase in reverse order, starting from launch: launch day, final review, build, draft, research, kickoff.
3. Estimate honest durations for each phase. Use past projects, not hopes.
4. Ask the chatbot to lay the phases backwards from launch, flag dependencies, and add buffer time between phases.
5. Read the resulting start date. If it is in the past or impossibly soon, cut scope or move the date now, not later.
6. Put the phase dates on a shared calendar or project board. Review weekly and re-plan when a phase slips.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build me a backwards plan from a fixed deadline.

DEADLINE: [date, and what "done" means]
PHASES (in reverse, starting from the deadline):
[phase, what it includes, your honest time estimate]
DEPENDENCIES: [what cannot start until something else finishes]
BUFFER: [how much slack you want between phases, e.g. 2 days]

Lay the phases backwards from the deadline with specific start and end dates for each. Flag any phase that lands on a weekend, holiday, or known busy period. Tell me the must-start date for the whole project. If the must-start date is before today, say so plainly and suggest what to cut.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Treating estimates as commitments. An estimate is a guess with a date on it. Update it when reality speaks.
- Forgetting dependencies. The design cannot start before the content exists, no matter what the calendar says.
- AI cannot know your team’s real capacity. It schedules from your numbers. Bad numbers in, fantasy plan out.

## Source

https://www.aisetupsthatwork.com/setups/backwards-project-deadlines-from-launch/ (AI Setups That Work)
