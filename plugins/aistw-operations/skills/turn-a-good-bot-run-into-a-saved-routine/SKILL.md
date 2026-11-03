---
name: turn-a-good-bot-run-into-a-saved-routine
description: "Turn a good bot run into a saved routine. Right after a run that worked, ask the bot to write down exactly what it did as a step-by-step routine. Test that routine on a different input. If it works twice, schedule it, and keep anything that sends, buys, deletes or publishes behind approval. Use when the user asks for help with this job."
---

# Turn a good bot run into a saved routine

## When to use

Owners who get a great result from a bot once and cannot get it again next week.

## Steps

1. Right after a good run, use the prompt below to have the bot write the routine.
2. Read it and fix anything vague, especially what done looks like.
3. Run the routine on a different input, such as another week's emails or a different client.
4. If it works twice, schedule it.
5. Keep send, purchase, delete, publish and record changes behind approval. xAI documents approvals for these actions in Grok Bot.
6. Add the routine to your list so the monthly usage review covers it.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
That run worked. Write it down as a reusable routine.

Include:
1. Name and one-line purpose
2. Inputs it needs and where they come from
3. Numbered steps, exactly as you did them
4. What done looks like
5. Actions that need my approval (send, buy, delete, publish, change records)
6. What to do if a step fails: stop and tell me
Under 200 words. Do not schedule it yet.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Scheduling after one lucky run.
- Vague done-looks-like, so results drift.
- Scheduled routines that send without approval.

## Source

https://www.aisetupsthatwork.com/setups/turn-a-good-bot-run-into-a-saved-routine/ (AI Setups That Work)
