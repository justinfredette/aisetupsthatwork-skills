---
name: one-source-of-truth-doc-every-bot-reads
description: "One source-of-truth doc every bot reads. Keep one short document with today's facts: prices, policies, open promises and recent decisions, each with a date. Tell every bot to read it before starting and to flag anything that contradicts it. Update the document, not each bot's memory. Use when the user asks for help with this job."
---

# One source-of-truth doc every bot reads

## When to use

Owners with several bots that forget decisions, miss watched items, or give different answers.

## Steps

1. Create one document with 4 headings: Current facts, Decisions, Open promises, Do not.
2. Date every line, for example: 'Nov 3: call-out fee is $95.'
3. Add the instruction from the prompt below to every bot.
4. When something changes, update the document, not each bot.
5. Keep it short. Move old decisions to an archive section monthly.
6. Grok Bot group owners described this as the fix that worked when bots kept forgetting; pair it with a promise log for watched items.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Add this to your standing instructions:

Before starting any task, read [DOCUMENT NAME/LOCATION].
- Treat it as the current truth for prices, policies, decisions and open promises.
- If your memory or a file disagrees with it, follow the document and tell me what disagreed.
- If the task creates a new decision or promise, propose a dated line for the document. Do not edit it yourself.
- If you cannot read the document, stop and tell me.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Letting every bot edit the document.
- Keeping facts in both memory and the document.
- A document so long bots skim it.

## Source

https://www.aisetupsthatwork.com/setups/one-source-of-truth-doc-every-bot-reads/ (AI Setups That Work)
