---
name: answer-repeat-customer-questions-automatically
description: "Answer repeat customer questions automatically. Write down the ten questions you answer over and over, put the approved answers in one place, and let a simple chatbot or FAQ page handle them. You only step in when it cannot answer confidently. Use when the user asks for help with this job."
---

# Answer repeat customer questions automatically

## When to use

Small business owners answering the same five questions daily who cannot hire support yet.

## Steps

1. Find your real top ten. Search your sent mail and messages for the questions you have answered more than five times: hours, pricing, shipping, returns, booking.
2. Write one approved answer per question. Short, plain, with the exact facts: no "it depends" without saying what it depends on.
3. Publish the answers as an FAQ page on your site first. This alone deflects a share of repeat questions before anyone messages you.
4. Add a simple chatbot for the rest. HubSpot’s chatbot builder is free with no credit card required and no coding, and it can live on your site or Facebook Messenger.
5. Point the bot at your approved answers only. HubSpot’s documented pattern: a searchable knowledge base plus an AI agent that answers from synced articles and transfers the conversation when it cannot answer confidently.
6. Set the handoff rule in plain words: billing disputes, cancellations, angry customers, and anything security-related go to a human immediately.
7. Start narrow. HubSpot advises starting with a small set of high-volume questions, syncing only current approved sources, and testing answers and handoff behavior before expanding.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me build a self-service FAQ that answers repeat customer questions.

My business: [e.g. "mobile dog grooming in Rutland VT"]
The 10 questions I answer constantly: [paste them, e.g. "Do you come to my town? How much for a large dog? Do I need to be home?"]

For each question, draft:
- A short approved answer (2-4 sentences, plain words, exact facts only)
- A follow-up question to ask if the answer does not resolve it
- A handoff line for when a human is needed

Rules:
- Use only the facts I give you. Mark anything you are unsure about with [VERIFY].
- Keep answers under 60 words each.
- Write the handoff so the customer feels helped, not bounced.

Review every answer before publishing. These go out under my business name, so each fact must be one I would defend on the phone.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Letting the bot guess at facts you never gave it. Sync only approved sources; anything else gets a handoff, not an invention.
- No handoff path. A bot that cannot reach a human on billing disputes or angry customers will cost you the customer.
- Automating edge cases first. Start with the boring high-volume questions; the weird ones stay human.

## Source

https://www.aisetupsthatwork.com/setups/answer-repeat-customer-questions-automatically/ (AI Setups That Work)
