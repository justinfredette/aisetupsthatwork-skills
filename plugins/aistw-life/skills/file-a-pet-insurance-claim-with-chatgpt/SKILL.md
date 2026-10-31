---
name: file-a-pet-insurance-claim-with-chatgpt
description: "File a Pet Insurance Claim with ChatGPT. Here's how I'd set this up in ChatGPT or Claude (not run by us yet). After a vet visit, I'd upload the itemized invoice and my policy, black out my account details, and have the chat sort which charges look covered, list what the claim form asks for, and flag anything my policy excludes. Then I'd submit the claim myself through my insurer's app or site. Use when the user asks for help with this job."
---

# File a Pet Insurance Claim with ChatGPT

## When to use

For pet owners who pay the vet, mean to file the claim later, and then put it off because the invoice and the policy are hard to match up.

## Steps

1. Ask your vet for an itemized invoice and, if your insurer asks for them, the medical records for the visit.
2. Download your policy or coverage summary from your insurer's site or app.
3. Black out your policy number and address, then upload the invoice and policy with the prompt below.
4. Read the sorted list. Each charge should be marked as likely covered, likely not covered, or unclear, with the policy section it's based on.
5. Check the list against your policy yourself, especially waiting periods, pre-existing conditions, and exclusions.
6. Submit the claim through your insurer's app or site with the invoice and records. Save the claim number.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me prepare a pet insurance claim. Don't submit anything for me.

Attached: the itemized vet invoice and my policy or coverage summary. I've blacked out my account details.
Pet: [name, species, age]
Reason for the visit: [what happened]
Policy start date: [date]

1. List every line on the invoice with date, description, and amount.
2. For each line, say whether it looks covered, not covered, or unclear under my policy. Quote or name the section of the policy you're relying on.
3. Flag anything that could be affected by a waiting period, a pre-existing condition rule, or an exclusion.
4. List what the claim needs based on my policy (invoice, medical records, claim form fields) and any deadline the policy states.
5. Draft a short note to the insurer for any unclear line, asking how it's covered.

Rules: Don't invent policy terms or amounts. If the policy doesn't say, write "policy doesn't say". The insurer decides what's covered, not you.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Only your insurer decides what's covered. Use the chat's sorting as a filing guide. It can't promise a payout.
- Policies word waiting periods and pre-existing condition rules differently, and the chat can misread them. Check those sections yourself.
- A payment receipt without line items won't give the chat enough to sort. Ask the vet for the itemized invoice.

## Source

https://www.aisetupsthatwork.com/setups/file-a-pet-insurance-claim-with-chatgpt/ (AI Setups That Work)
