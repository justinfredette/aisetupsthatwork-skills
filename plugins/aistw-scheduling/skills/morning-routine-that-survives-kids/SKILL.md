---
name: morning-routine-that-survives-kids
description: "Build a morning routine that survives kids. Tell AI your wake-up time, the kids’ ages, and what must happen before you leave. It builds a timed morning sequence with buffer time, plus a night-before prep list that does half the work while everyone sleeps. Use when the user asks for help with this job."
---

# Build a morning routine that survives kids

## When to use

Parents whose school mornings run on yelling, lost shoes, and a departure time that keeps slipping.

## Steps

1. Write down everything that must happen on a school morning, in order, with honest minutes for each.
2. Note the non-negotiables: wake times, bus or drop-off time, anything that cannot move.
3. Ask the chatbot to build a timed sequence working backwards from out-the-door time, with 15 minutes of buffer.
4. Split the sequence into a night-before list (clothes, bags, lunches) and a morning list. The night list is the real product.
5. Post the morning list where the kids can see it. Pictures for little ones, checkboxes for older kids.
6. Run it for a week, then adjust the times. The first version is always wrong about how long teeth-brushing takes.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build us a school-morning routine.

OUT THE DOOR BY: [time]
KIDS: [ages]
MUST HAPPEN EACH MORNING: [breakfast, dressed, teeth, hair, bags, etc.]
PARENTS ALSO NEED: [shower, coffee, work start time]
CURRENT WAKE-UP TIME: [time]

Work backwards from out-the-door time. Give me:
1. A timed morning sequence with minutes for each step and 15 minutes of buffer.
2. A night-before prep list that removes as much morning work as possible.
3. Who does what, if two parents are home.

Keep it realistic for the kids' ages. A 4-year-old does not do a 12-step routine.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Building the routine for ideal children. Plan for the slow version of each kid, not the fast one.
- Skipping the night-before list. The morning routine fails at 9pm, not 7am.
- Too many steps for little kids. Five steps they can do beats twelve they cannot.

## Source

https://www.aisetupsthatwork.com/setups/morning-routine-that-survives-kids/ (AI Setups That Work)
