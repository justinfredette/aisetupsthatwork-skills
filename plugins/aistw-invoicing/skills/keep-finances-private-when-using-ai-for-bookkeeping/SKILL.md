---
name: keep-finances-private-when-using-ai-for-bookkeeping
description: "Keep finances private when using AI for books. Turn off the setting that lets your chats train the model, strip account numbers, names and tax IDs before pasting, and work from summaries or exports with only the columns you need. Keep originals in your accounting software. Use when the user asks for help with this job."
---

# Keep finances private when using AI for books

## When to use

Owners who want AI help categorizing transactions or reading statements but worry about sending confidential finances to the cloud.

## Steps

1. Turn off training on your chats. OpenAI says that on Free, Plus and Pro, data sharing is on by default and you can turn off Improve the model for everyone in Data controls and keep your chat history.
2. In Claude, change the model improvement setting. Anthropic says once it is off, new chats are not used for future model training.
3. Before pasting, delete columns you do not need: full account numbers, tax IDs, client addresses. Keep date, description, amount and category.
4. Use the prompt below so the AI works only from what you pasted and flags anything it is unsure about.
5. Keep the official record in your accounting software; use AI output as a draft you check.
6. Write a never-paste list: passwords, full card numbers, tax IDs and login codes.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Categorize these transactions for my bookkeeping. I removed account numbers and personal details.

My categories: [LIST]
Transactions (date, description, amount): [PASTE]

Rules:
- Use only my categories. If unsure, mark REVIEW and say why.
- Do not guess vendor details that are not in the description.
- Total each category and show the math.
- Do not ask me for account numbers or IDs.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Pasting a full bank statement with account numbers.
- Assuming the training setting is already off.
- Treating AI categories as final without review.

## Source

https://www.aisetupsthatwork.com/setups/keep-finances-private-when-using-ai-for-bookkeeping/ (AI Setups That Work)
