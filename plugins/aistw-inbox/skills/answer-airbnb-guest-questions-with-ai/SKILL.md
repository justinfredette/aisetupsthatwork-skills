---
name: answer-airbnb-guest-questions-with-ai
description: "Answer Airbnb guest questions with AI. Write a reply for each question guests ask most, such as check-in, house rules and parking. Save them as Airbnb quick replies. Airbnb's help center says you pick a reply in the thread, edit it, and click Send, so you approve each one. Use when the user asks for help with this job."
---

# Answer Airbnb guest questions with AI

## When to use

Airbnb hosts who answer the same guest questions again and again. Use it for questions only. Do not paste guest names, door codes or lockbox codes into a chatbot. Put codes in Airbnb's own details or check-in fields.

## Steps

1. List the 8 to 10 questions guests ask most, from your last month of messages with names removed.
2. Write down the true answer to each one: check-in steps, house rules, parking, Wi-Fi, checkout, quiet hours.
3. Use the prompt below to draft one short reply per question. Replace any code or password with a placeholder.
4. Read each draft against your real rules. Fix anything that adds a rule you do not have.
5. In Airbnb, click Messages, then Settings, then Manage quick replies, then Create. Name the template, write the message, choose the listing and click Save. Airbnb says you can insert details that fill in guest and listing information.
6. To use one, open the guest's thread, click the quick reply icon next to the message box, pick the reply, edit it and click Send. Do not schedule these. Scheduling is covered by the setup linked below.
7. Airbnb says messages have a 4,000 character limit, so split anything longer into two quick replies.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Write short Airbnb replies to common guest questions for my rental. Use only the facts I give. Do not add rules, amenities or promises.

Listing type: [for example: two-bedroom cabin]
Check-in steps (no codes): [STEPS]
House rules: [RULES]
Parking: [PARKING]
Checkout: [TIME AND STEPS]
Questions to answer: [LIST 6 TO 10]

Rules:
- One reply per question, 2 to 4 sentences, friendly and plain.
- Use [GUEST FIRST NAME] and [CHECK-IN DATE] as placeholders.
- Never write a door code, lockbox code or Wi-Fi password. Write [CODE] instead.
- If a fact is missing, write [HOST TO FILL IN].
- Do not send or schedule anything. I will review each reply.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- A reply that mentions a rule you do not have. Check each draft against your real rules.
- Codes in templates. Use the listing's own check-in details instead of pasting them into a chatbot.
- Details that show as unavailable because the listing field is empty.

## Source

https://www.aisetupsthatwork.com/setups/answer-airbnb-guest-questions-with-ai/ (AI Setups That Work)
