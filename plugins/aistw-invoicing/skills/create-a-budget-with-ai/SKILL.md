---
name: create-a-budget-with-ai
description: "How to Use AI to Create a Budget (Copy-Paste Prompt). I paste my monthly take-home, fixed bills, and debt minimums into ChatGPT, ask for a zero-based or 50/30/20 draft with line items I can edit in a spreadsheet, then I move money myself; the AI does not touch my bank. Use when the user asks for help with this job."
---

# How to Use AI to Create a Budget (Copy-Paste Prompt)

## When to use

Households that know their paycheck but lose track after rent, subscriptions, and card minimums, or anyone restarting a budget after a life change.

## Steps

1. Gather take-home income and fixed monthly bills. Round if you want, but do not let the model invent missing amounts.
2. Paste the numbers and pick a framework (50/30/20, zero-based, or envelope-style categories).
3. Ask for a table: category, planned amount, notes, and “verify in bank” flags where you were unsure.
4. Ask what to cut first if expenses exceed income. Require tradeoffs, not magic.
5. Copy the table into Sheets or your app; you assign dollars and pay bills yourself.
6. Re-run monthly with updated totals. Treat chat as a planner, not a bank feed.
7. Export a CSV from your bank and redact account numbers. Summarize it into category totals yourself in a spreadsheet, or use an offline tool that runs locally with no upload. The chatbot should only ever see totals, never raw transactions.
8. Paste the category totals into the prompt and ask: which three categories grew most this month, and what is one cut per category? Check every number against your sheet before you act on it.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are my budget drafting assistant. Do not connect to my bank, move money, or pay bills.

Monthly take-home income (after tax): [amount]
Fixed bills (list each with amount):
[paste rent, utilities, insurance, debt minimums, subscriptions, childcare, etc.]
Savings goal (optional): [amount or "none"]
Budget style: [50/30/20 / zero-based / envelope categories]

Rules:
- If a number is missing, ask me: do not guess balances or income.
- Show income minus expenses; if negative, list three realistic cuts in priority order.
- Output a markdown table: Category | Planned $ | Notes | Verify? (yes/no)
- Add a short "three moves this month" list I can act on without automation.
- Draft only: I approve before any payment or transfer.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Chat guesses subscription amounts. Replace every line with numbers from your statement.
- Pasting full bank exports can leak account numbers. Summarize categories yourself first.
- A pretty table does not change spending. You still need a weekly check-in habit.
- Trusting auto-categorized totals without checking them. Import tools guess your columns and categories, and a misread column can double your spending in one category.

## Source

https://www.aisetupsthatwork.com/setups/create-a-budget-with-ai/ (AI Setups That Work)
