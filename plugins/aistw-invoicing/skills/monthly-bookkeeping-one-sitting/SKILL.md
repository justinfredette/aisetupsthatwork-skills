---
name: monthly-bookkeeping-one-sitting
description: "Do a month of bookkeeping in one sitting. Once a month, export your transactions and let the AI categorize them, flag the odd ones, and summarize the month. You review and approve everything. Use when the user asks for help with this job."
---

# Do a month of bookkeeping in one sitting

## When to use

A small business owner whose bookkeeping is 3 months behind and dreads tax time

## Steps

1. Export last month's transactions from your bank and cards as CSV. Most banks have an export button.
2. Remove or mask full account numbers before uploading anything to a chatbot.
3. Paste the prompt below and upload the CSV files.
4. The AI categorizes each transaction and flags ones it is unsure about.
5. Review every flagged transaction yourself. This is the part you cannot skip.
6. Ask the AI for a month summary: total income, total expenses, biggest categories, anything unusual.
7. Save the categorized file and the summary in a folder named for the month. Done until next month.
8. After categorizing, run the reconciliation pass: match each transaction in your books to the same entry on the bank statement, line by line, and mark what matches. List everything left over on either side.
9. For the leftovers, add bank fees and interest you missed to your books, and keep a short list of outstanding checks and deposits in transit that explain the gap. The adjusted balances must match to the cent before you close the month.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I am doing my monthly bookkeeping. I have attached CSV exports of last month's business bank and credit card transactions. Categorize each transaction into these buckets: [LIST YOUR CATEGORIES, or use: advertising, supplies, software, travel, meals, rent, utilities, contractors, other]. Flag any transaction you are unsure about and tell me why. Then give me a summary: total income, total expenses, net for the month, the three biggest expense categories, and anything that looks unusual compared to a normal month.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI miscategorizes ambiguous transactions, like a big-box store run that was half supplies, half personal. Review the flags.
- Uploading statements with full account numbers. Strip them first.
- Skipping the review and trusting the AI completely. It is a draft, not a bookkeeper.
- Doing it quarterly instead of monthly. Small errors compound. Monthly takes an hour; quarterly takes a weekend.
- Closing the month with an unexplained gap. An unresolved difference is a signal, not a rounding error. Go back through the unmatched items.

## Source

https://www.aisetupsthatwork.com/setups/monthly-bookkeeping-one-sitting/ (AI Setups That Work)
