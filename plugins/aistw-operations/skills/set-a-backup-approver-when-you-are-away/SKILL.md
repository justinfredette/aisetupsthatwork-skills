---
name: set-a-backup-approver-when-you-are-away
description: "Set a backup approver when you are away. Decide in advance who approves what while you are away, what simply waits, and what the customer hears in the meantime. Put it in the agent's instructions, keep money and refunds with a named person, and have the agent send a holding message instead of going silent. Use when the user asks for help with this job."
---

# Set a backup approver when you are away

## When to use

Owners who approve their agent's drafts and worry about refunds, quotes or replies stalling when they are on a job, sick or on vacation.

## Steps

1. List what normally waits for your approval: replies, quotes, refunds, bookings.
2. For each, pick one: a named backup may approve, it waits until you are back, or the customer gets a holding message.
3. Keep money decisions with a named person. Anthropic says its Google Workspace connectors ask before sending by default; keep that on while you are away too.
4. Use the prompt below to turn your choices into an away plan, and paste it into the agent's instructions before you leave.
5. Test it: send yourself a fake refund request and check the agent sends the holding message, not a decision.
6. When you are back, ask the agent for a list of everything that waited.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Write an away plan for my AI agent. Use only my choices.

I am away: [DATES]
Backup person (or none): [NAME, ROLE]
For each item, my choice (backup approves / waits for me / holding message):
- Customer replies: [CHOICE]
- Quotes: [CHOICE]
- Refunds and credits: [CHOICE]
- Bookings and changes: [CHOICE]

Include:
1. A short rule list the agent follows while I am away
2. A holding message under 50 words that tells the customer when they will hear back, with no promises about the outcome
3. A rule: anything not listed waits for me
Do not give the backup any permission I did not list.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Letting the agent decide refunds because no one is around.
- Promising a resolution date the backup cannot keep.
- Forgetting to switch the plan off when you return.

## Source

https://www.aisetupsthatwork.com/setups/set-a-backup-approver-when-you-are-away/ (AI Setups That Work)
