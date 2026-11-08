---
name: track-job-applications-from-your-inbox
description: "Track job applications from your inbox. Have the AI build a tracker with one row per application, then fill it from your application confirmation emails. Anything with no reply after 7 days gets."
---

# Track job applications from your inbox

## When to use

Job seekers with dozens of applications out who lose track of who replied and when to follow up.

## Steps

1. Ask the AI to build the tracker with the prompt below. Anthropic says Claude can create Excel files with working formulas.
2. Fill it from application confirmation emails. With a Gmail connector the AI can search them; otherwise paste them in.
3. Check each row against the email; fix company names and dates.
4. Each morning, filter for FOLLOW UP. Draft a two-line follow-up for each and send it yourself.
5. Update status as replies arrive: Replied, Interview, Rejected, Offer.
6. Each Friday, ask for the digest: sent, replies, interviews, and which resume version got replies.

## What to ask the user for

- PASTE CONFIRMATION EMAILS

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build a job application tracker (Excel) with one row per application:
Company | Role | Date applied | Contact | Resume version | Status (Applied, Replied, Interview, Rejected, Offer) | Last contact | Action

Rules:
- Action shows FOLLOW UP when Status is Applied and Last contact is 7 or more days ago.
- A summary at the top: applied this week, replies, interviews, reply rate by resume version.
- Then fill rows only from these emails, and leave a cell blank if the email does not say: [PASTE CONFIRMATION EMAILS]
Do not invent companies, dates or contacts.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Applying from several sites and missing confirmation emails.
- Following up more than once on the same application.
- Letting the AI mark rows as replied without seeing the reply.

## Source

https://www.aisetupsthatwork.com/setups/track-job-applications-from-your-inbox/ (AI Setups That Work)
