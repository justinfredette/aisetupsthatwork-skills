---
name: time-block-your-week-with-ai
description: "Time-block your week with AI. Tell a chatbot your fixed commitments and your task list, and it drafts a time-blocked week: every task assigned to a real hour, with breaks and buffers. You review it Sunday night and copy it into your calendar. Use when the user asks for help with this job."
---

# Time-block your week with AI

## When to use

Anyone whose days get eaten by email and meetings while the real work slides into the evening.

## Steps

1. Dump everything: list this week’s fixed commitments (meetings, appointments, pickup times) and every task you need to do.
2. Estimate how long each task takes. Then add 25 percent. Everyone underestimates.
3. Tell the chatbot your working hours and when you do your best thinking.
4. Ask for a day-by-day plan with named blocks, breaks, and one buffer block per day for overflow.
5. Read the draft and fix anything that fights reality. Then create the blocks as calendar events, color-coded by type.
6. Each evening, spend five minutes adjusting tomorrow. A time-blocked plan is a draft, not a contract.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Here is my week. Build me a time-blocked plan.

FIXED COMMITMENTS (cannot move):
[meetings, appointments, school pickup, etc. with days and times]

TASKS TO FIT IN:
[task list with your honest time estimates]

MY WORKING HOURS: [e.g. 8:30am-5:30pm]
MY BEST FOCUS TIME: [e.g. mornings before 11am]

Rules:
- Assign every task to a specific block with a start and end time.
- Include a 10-minute break between blocks and one 30-minute buffer block per day.
- Label each block with the specific deliverable, not just "work on project."
- If everything does not fit, tell me what to cut or move to next week. Do not just pack it tighter.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Overstuffing the day. If the plan has no empty space, the first surprise breaks all of it. Keep the buffer.
- Time estimates from memory are fiction. Track actuals for two weeks and your estimates get honest fast.
- AI cannot see your real calendar, so it will happily schedule over a meeting you forgot to mention. Paste your real schedule in.
- Skipping the evening review. The plan rots in three days without it.

## Source

https://www.aisetupsthatwork.com/setups/time-block-your-week-with-ai/ (AI Setups That Work)
