---
name: catch-up-months-of-books-before-your-bookkeeper
description: "Catch up months of books before your bookkeeper. Export each month of bank and card transactions as CSV, remove account numbers, and have the AI suggest categories, flag duplicates and list what needs a receipt. Fix the flags yourself, then give your bookkeeper the sorted file and the questions list. Less mess usually means fewer billable hours. Use when the user asks for help with this job."
---

# Catch up months of books before your bookkeeper

## When to use

Owners months behind on books, often across several businesses, facing a catch-up or clean-up bill.

## Steps

1. Export each month as CSV per account. Delete account numbers and keep date, description and amount.
2. If you run several businesses, keep each one's files separate and say which business they belong to.
3. Upload one month at a time with the prompt below.
4. Work the flags: find receipts, answer the questions, split mixed personal and business charges.
5. Keep records. The IRS says to keep records that show income and expenses, generally at least 3 years, and employment tax records at least 4.
6. Give your bookkeeper the sorted file and the open questions, and ask for a quote on the remaining work.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I uploaded [MONTH] bank and card transactions for [BUSINESS NAME]. Account numbers removed. Use only this file.

My categories: [LIST]

1. Suggest a category for each transaction with a one-line reason.
2. Mark REVIEW where unsure, DUPLICATE where it appears twice, PERSONAL? where it looks personal.
3. List transactions over [$75] that need a receipt.
4. List questions for my bookkeeper.
Do not guess vendor details that are not in the file.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Uploading a year at once and getting sloppy results.
- Mixing two businesses in one file.
- Treating AI categories as final; your bookkeeper still reviews.

## Source

https://www.aisetupsthatwork.com/setups/catch-up-months-of-books-before-your-bookkeeper/ (AI Setups That Work)
