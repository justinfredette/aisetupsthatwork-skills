---
name: business-subscription-audit
description: "Audit your business subscriptions in one afternoon. Export 12 months of card statements and the AI pulls every recurring charge into one list, flags duplicates and unused tools, and suggests what to cut or consolidate. Use when the user asks for help with this job."
---

# Audit your business subscriptions in one afternoon

## When to use

An office manager or owner who suspects the company pays for software nobody uses

## Steps

1. Export 12 months of statements from every business card and account as CSV.
2. Strip full account numbers before uploading anything to a chatbot.
3. Paste the prompt below and upload the CSVs.
4. The AI lists every recurring charge: vendor, amount, frequency, annual cost.
5. Go through the list and mark each tool: used weekly, used rarely, or not used at all.
6. Cancel or downgrade everything in the last category before the next renewal.
7. Group the keepers by job: if two tools do the same thing, consolidate to one.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Audit my business software subscriptions. I have attached 12 months of business card statements as CSV. Pull out every recurring charge: vendor name, amount, billing frequency, and annual cost. Group them by function (communication, accounting, marketing, etc) and flag anything that looks like a duplicate or overlap. For charges with cryptic merchant names, give me your best guess at the vendor and mark it uncertain. Total the annual spend.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Cryptic merchant names on statements. The AI guesses, sometimes wrong. Verify before canceling anything.
- Canceling a tool someone quietly depends on. Check with the team first.
- Forgetting annual plans. A $300 annual charge looks like nothing on a monthly statement review.
- Doing the audit once and never again. Put a 90-day reminder on your calendar.

## Source

https://www.aisetupsthatwork.com/setups/business-subscription-audit/ (AI Setups That Work)
