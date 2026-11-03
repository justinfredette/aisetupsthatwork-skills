---
name: answer-order-status-emails-with-ai
description: "Answer order status emails with AI. Give the AI the customer's email plus the real order status and tracking from your store, and ask for a short reply that only uses those facts. It drafts; you check the order number and send. Use when the user asks for help with this job."
---

# Answer order status emails with AI

## When to use

Online stores and makers who get the same shipping question every day and want fast replies that never promise a date the carrier did not give.

## Steps

1. Copy the customer's email and the order's status, carrier, tracking link and last scan from your store or carrier page.
2. Paste both into the prompt below. The AI may only use what you pasted.
3. Check the draft's order number, tracking link and any date against the order page.
4. Send it from your own inbox.
5. If many orders are stuck at once, paste the list and ask for one reply template plus a line per customer.
6. Save your best reply as a template in your project so tone stays consistent.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Draft a reply to this customer about their order. Use only the facts below.

Customer email: [PASTE]
Order number: [#]
Status: [E.G. SHIPPED, LABEL CREATED, DELIVERED, DELAYED]
Carrier and tracking link: [PASTE]
Last scan: [DATE, PLACE]
Our policy if late or lost: [PASTE OR 'NONE']

Rules:
- Under 90 words, friendly and plain.
- Never promise a delivery date unless the carrier gave one; if so, say it is the carrier's estimate.
- Include the tracking link once.
- End with one clear next step for them.
- Show me the draft. Do not send.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI invents a delivery date. The prompt forbids it; still check before sending.
- Pasting the wrong order next to the customer's email.
- Promising a refund the policy does not offer.

## Source

https://www.aisetupsthatwork.com/setups/answer-order-status-emails-with-ai/ (AI Setups That Work)
