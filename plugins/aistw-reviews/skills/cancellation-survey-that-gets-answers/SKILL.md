---
name: cancellation-survey-that-gets-answers
description: "Find Out Why Customers Cancel With a Short Exit Survey. Put a 1 to 2 question survey in your cancel flow with an \"Other\" write-in box, then match each answer to a save offer: price complaints get a cheaper plan, busy users get a pause. Review your reason list every quarter so it stays current. Use when the user asks for help with this job."
---

# Find Out Why Customers Cancel With a Short Exit Survey

## When to use

Subscription and membership businesses that see cancellations but never learn why.

## Steps

1. List the real reasons people cancel: price, not using it, too busy, missing feature, switched to a competitor, support issue.
2. Ask AI to turn that list into 1 to 2 multiple-choice questions plus an "Other" box. FunnelFox advises keeping it that short because a 20-question survey kills responses.
3. Write one matched save offer per reason: price complaint gets a cheaper plan or discount, "too busy" gets an account pause, "not using it" gets a pointer to a hidden feature.
4. Add a short "what you will lose" summary on the cancel screen: their data, history, and any setup they did.
5. Offer a downgrade before the final cancel button. Appcues points to Mailchimp, which kept exiting users with a pause option that preserved their lists and automations.
6. After someone leaves, tag their reason and wait a few weeks, then follow up with something tied to it: a new feature they asked for or a relevant offer.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me build a cancellation exit survey for my subscription business. Plain, no hype.

Business: [what you sell, monthly or annual plans]
Plans: [plan names and prices]
Save options I can offer: [e.g. cheaper plan, pause for 2 months, annual discount]

Write:
1. An exit survey: 2 multiple-choice questions max, plus an "Other" free-text box. Give me 6-8 reason options based on my business.
2. A matched save offer for each reason, in one sentence each.
3. A short "what you will lose" summary for the cancel screen.
4. A follow-up email for 3 weeks later, personalized to the stated reason.

Rules:
- Short and plain. No guilt trips.
- Never make canceling hard to find. The survey comes after they choose to cancel.
- Show me the draft first. I will review before using anything.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- A long survey gets skipped. Keep it to 1 to 2 questions or you learn nothing.
- Generic reasons ("Other") with no options give you unusable data. Seed the real reasons.
- Save offers only work if they are real: a discount you cannot honor burns trust.
- Do not hide the cancel button to force survey answers. That creates anger, not retention.

## Source

https://www.aisetupsthatwork.com/setups/cancellation-survey-that-gets-answers/ (AI Setups That Work)
