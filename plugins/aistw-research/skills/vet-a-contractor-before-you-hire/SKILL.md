---
name: vet-a-contractor-before-you-hire
description: "Vet a contractor before you hire them. Give the AI the contractor’s name, license number, and quote details. It builds a vetting checklist covering license, insurance, reviews, and red flags, and drafts the questions you should ask before signing. Use when the user asks for help with this job."
---

# Vet a contractor before you hire them

## When to use

Homeowners getting bids for roofing, remodeling, or repairs who do not want to learn about contractor fraud the hard way.

## Steps

1. Get the contractor’s full business name, license number, and a written quote. No quote, no hire.
2. Look up the license yourself on your state’s contractor board site. Confirm it is active and matches the business name.
3. Ask the AI to build a vetting checklist for your state and project type: license, insurance, bond, reviews, references.
4. Paste the quote in and ask the AI to flag vague line items, missing materials, and payment terms that favor the contractor.
5. Ask the AI to draft reference-check questions and red-flag questions for the final interview.
6. Call two references yourself and ask about communication, timeline, and surprise charges.
7. Never pay a large deposit up front. Progress payments tied to completed work protect you.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I am thinking about hiring this contractor. Help me vet them.

Contractor: [BUSINESS NAME]
License number: [NUMBER]
State: [STATE]
Project: [e.g. roof replacement, kitchen remodel]
Quote total: [AMOUNT]

Their written quote:
[PASTE QUOTE]

Please:
1. Build a vetting checklist for hiring a contractor in [STATE]: license verification, insurance (liability and workers comp), bond, reviews, references, and contract terms.
2. Review the quote and flag vague line items, missing materials or brands, unrealistic timelines, and payment terms that put me at risk.
3. List red flags I should watch for with this contractor specifically.
4. Draft ten questions I should ask before signing, including reference-check questions.

Be direct about anything that looks risky. Do not soften bad news.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI may describe licensing rules for the wrong state. Always confirm on your own state board site.
- AI-drafted contracts are a starting point, not legal advice. For big jobs, have a real person review the contract.
- A contractor with no online presence is not automatically a scam, but it means your reference calls matter more.

## Source

https://www.aisetupsthatwork.com/setups/vet-a-contractor-before-you-hire/ (AI Setups That Work)
