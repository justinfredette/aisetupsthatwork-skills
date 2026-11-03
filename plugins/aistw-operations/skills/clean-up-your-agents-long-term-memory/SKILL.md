---
name: clean-up-your-agents-long-term-memory
description: "Clean up your agent's long-term memory. Open the memory list and review it monthly. Delete anything outdated, rewrite facts that changed with a date, and keep task details out of memory entirely. Deleting a memory does not remove it from old chats, so start a fresh chat after cleaning up. Use when the user asks for help with this job."
---

# Clean up your agent's long-term memory

## When to use

Anyone whose AI assistant or agent keeps using an old price, an old rule or details from a past job.

## Steps

1. Open the memory list. In ChatGPT it is Settings, then Personalization, then Manage memories; other tools have a similar page or a memory file.
2. Copy the list into the prompt below and get it sorted into keep, update and delete.
3. Delete stale entries. OpenAI says deleting a saved memory stops it being used, but does not remove it from past chats, so delete or archive old chats that repeat the stale fact.
4. Rewrite facts that changed with a date, for example: 'As of Nov 2026, call-out fee is $95.'
5. Keep one-off task details, such as a client's job notes, in that task's project or file, not in memory.
6. Start a fresh chat after the cleanup, and repeat monthly.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Here is my AI assistant's memory list and my current facts. Use only what I paste.

Memory list: [PASTE]
Current facts (prices, policies, contacts, preferences): [PASTE]

Sort every memory into:
- KEEP: still true
- UPDATE: changed; write the new version with today's date
- DELETE: outdated, a one-off task detail, or a duplicate
Give a one-line reason for each. Flag any memory that contradicts my current facts.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Turning memory off and assuming that deleted everything; it does not.
- Keeping two versions of the same price.
- Saving client details in memory where they leak into other work.

## Source

https://www.aisetupsthatwork.com/setups/clean-up-your-agents-long-term-memory/ (AI Setups That Work)
