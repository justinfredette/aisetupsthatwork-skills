---
name: check-your-agent-did-the-follow-up-it-promised
description: "Check your agent did the follow-up it promised. An agent saying it will watch for something is not the same as a scheduled job doing it. Turn every promise into a dated task, have a daily check list promises due today and their status, and treat anything not confirmed as not done. Use when the user asks for help with this job."
---

# Check your agent did the follow-up it promised

## When to use

Owners whose agent said it would watch for a reply or chase something later, and then missed it.

## Steps

1. Each time the agent promises a later action, have it write one line to a promise log: what, for whom, due date.
2. Do not rely on the agent remembering. OpenAI documents scheduled tasks in ChatGPT as one-time or recurring with notifications; use a real schedule or a calendar reminder for anything that must happen.
3. Each morning, paste the promise log and what actually happened, such as replies received and messages sent, into the prompt below.
4. Handle anything marked SLIPPED yourself, or tell the agent to draft it now for your approval.
5. If the same promise slips twice, remove it from the agent's job and put it on your own list.
6. Review the log weekly with the weekly agent review setup.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Here is my agent's promise log and what actually happened. Use only what I paste.

Promise log (what, for whom, due date): [PASTE]
What happened (replies received, messages sent, tasks done): [PASTE]
Today is: [DATE]

List:
1. DONE: promises with clear evidence they happened
2. SLIPPED: due today or earlier with no evidence
3. COMING UP: due in the next 3 days
For each SLIPPED item, draft the one-line next step. Treat anything without evidence as not done.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Trusting a chat promise with no schedule behind it.
- Logging promises without dates.
- Letting the agent mark its own work done without evidence.

## Source

https://www.aisetupsthatwork.com/setups/check-your-agent-did-the-follow-up-it-promised/ (AI Setups That Work)
