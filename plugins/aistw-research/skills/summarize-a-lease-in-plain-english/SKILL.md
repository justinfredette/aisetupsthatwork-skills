---
name: summarize-a-lease-in-plain-english
description: "Understand Your Lease in Plain English. This is not legal advice. Photograph or scan your lease, have AI pull out the key terms in plain language, then check the warning signs yourself before you sign. A local attorney answers the close calls. Use when the user asks for help with this job."
---

# Understand Your Lease in Plain English

## When to use

Renters staring at a lease full of legal language. This is not legal advice; a local attorney handles anything you are unsure about.

## Steps

1. Photograph or scan every page of the lease so the AI can read the full text.
2. Ask the AI to extract the key terms using the prompt below: rent, fees, term, deposit, rules, and exit terms.
3. Read the plain-English summary and compare it against the warning-sign list: automatic rent increases, shared utility meters, blank spaces, and one-sided terms.
4. Write down your questions: pet policy, subletting, maintenance split, renewal terms, and what happens if you need to break the lease.
5. Ask the landlord about anything unclear, and get answers in writing.
6. If anything looks off or you do not understand a clause, talk to a local attorney before signing.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Summarize this lease in plain English. You are summarizing, NOT giving legal advice.

[Paste the lease text here]

Rules:
- Extract: parties, property address, lease term and dates, rent amount and due date, late fees and grace period, security deposit amount, pet policy, occupancy limits, subletting rules, maintenance responsibilities, renewal terms, early termination terms, and landlord entry notice rules.
- Use plain language a non-lawyer understands. Define any legal term you quote.
- Flag anything that looks one-sided or unusual with "[review carefully]": automatic rent increases, shared utility meters, blank spaces, "hold harmless" clauses, unrestricted landlord entry, waivers of legal rights.
- List 8 questions I should ask the landlord before signing.
- End with: "This is a summary, not legal advice. Have a local attorney review anything you are unsure about."

Review the summary against the actual lease before you rely on it.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- AI summarizes; it does not give legal advice and may miss state-specific rules. A local attorney handles the close calls.
- AI can misread scanned text. Verify every extracted number against the actual lease.
- Warning signs AI should flag but you must judge: automatic rent increases, shared meters, and clauses waiving your rights.
- Lease terms cannot override state or federal law, including fair housing protections. An illegal clause is not enforceable just because you signed it.

## Source

https://www.aisetupsthatwork.com/setups/summarize-a-lease-in-plain-english/ (AI Setups That Work)
