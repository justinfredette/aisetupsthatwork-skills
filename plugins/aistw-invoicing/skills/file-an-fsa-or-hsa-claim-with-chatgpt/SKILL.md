---
name: file-an-fsa-or-hsa-claim-with-chatgpt
description: "File an FSA or HSA Claim with ChatGPT. Here's how I'd set this up in ChatGPT or Claude (not run by us yet). I'd gather my medical receipts and explanation of benefits statements, black out my member IDs, upload them, and have the chat build a list of what I paid, what's already been reimbursed, and what I still need to claim. Then I'd check anything borderline against my plan and file the claims myself. Use when the user asks for help with this job."
---

# File an FSA or HSA Claim with ChatGPT

## When to use

For anyone with a health FSA or HSA who has a pile of receipts, isn't sure what they've already claimed, and doesn't want to lose FSA money at the end of the plan year.

## Steps

1. Collect itemized receipts and EOBs for the plan year. A card receipt with only a total usually isn't enough.
2. Black out member IDs, account numbers, and your Social Security number. Upload the files with the prompt below.
3. Read the claim list: date, provider, what it was for, what you paid after insurance, and whether it looks claimed already.
4. Check anything flagged as borderline against your plan's eligible expense list. Your plan decides what it covers.
5. File each claim in your FSA or HSA portal with the itemized receipt or EOB attached.
6. Keep the records. For an HSA, the IRS says you must keep records that show each withdrawal paid a qualified medical expense.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me sort my medical receipts for FSA or HSA claims. Don't file anything for me.

Account type: [health FSA or HSA]
Plan year: [dates]
Already claimed: [list, or "not sure"]
Attached: receipts and explanation of benefits statements. I've blacked out member IDs and account numbers.

1. Build a table: date of service, provider, what it was for, amount I paid after insurance, and the document it came from.
2. Match receipts to EOBs where you can, so I claim what I paid, not the full billed amount.
3. Mark rows that look like duplicates or already claimed.
4. Flag anything that might not be eligible or needs a closer look, and say why.
5. Total what still looks unclaimed.

Rules: Don't invent amounts or dates. If a document is hard to read, write "can't read". Don't decide eligibility for me; flag it.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Eligibility depends on your plan's rules, and the chat can't see them unless you upload them. Treat every flag as a question to check against your plan.
- Receipts that show only a card total don't list what was bought. Ask the provider or pharmacy for an itemized receipt.
- The chat can misread a scanned EOB. Check every amount against the original before you file.

## Source

https://www.aisetupsthatwork.com/setups/file-an-fsa-or-hsa-claim-with-chatgpt/ (AI Setups That Work)
