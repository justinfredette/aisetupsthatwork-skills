---
name: cancel-subscriptions-and-get-refunds-with-chatgpt
description: "Cancel Subscriptions and Ask for Refunds with ChatGPT. Here's how I'd set this up in ChatGPT or Claude (not run by us yet). I'd paste the recurring charges from my card statement, have the chat sort them into keep and cancel, then get the cancel steps and short refund requests that I send myself. Use when the user asks for help with this job."
---

# Cancel Subscriptions and Ask for Refunds with ChatGPT

## When to use

For anyone who already knows which subscriptions should go and wants the cancel steps and refund requests written out.

## Steps

1. Copy every recurring charge from your statements: merchant, amount, and date. Remove card and account numbers first.
2. Paste the list into the chat with the prompt below, and mark each one keep or cancel.
3. For each cancel, check where it's billed: the company directly, Apple, or Google Play. The cancel and refund path is different for each.
4. Cancel each one yourself in the service's account settings or your app store's subscription page.
5. Send the refund requests the chat drafts, only for charges you didn't use or didn't mean to renew. For Apple, request it at reportaproblem.apple.com. For Google Play, Google says contacting the app's developer is often fastest.
6. Paste replies back into the same chat to update the tracker, and follow up on any request that's still open.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me cancel subscriptions and ask for refunds. Don't contact any company for me.

Here are my recurring charges (merchant, amount, date): [paste list]
Keep: [names]
Cancel: [names]

1. For each cancel, tell me whether it looks billed directly, through Apple, or through Google Play, based on how it shows on the statement. If you can't tell, say so.
2. Give me the cancel path for each in one line. Use web search to find the company's own help page and link it.
3. For charges I say I didn't use, draft a refund request under 80 words with the date and amount.
4. Make a tracker table: service, cancelled (yes/no), refund asked (yes/no), reply, next step.

Rules: Don't promise a refund will be granted. Don't invent policies. Use only the charges I pasted.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Refunds are up to each company and its terms. Apple and Google both say eligibility varies.
- Some services only cancel inside their own account settings or app, so you need each login.
- A charge can show under a payment service's name. Match the amount and date against the company's receipts.

## Source

https://www.aisetupsthatwork.com/setups/cancel-subscriptions-and-get-refunds-with-chatgpt/ (AI Setups That Work)
