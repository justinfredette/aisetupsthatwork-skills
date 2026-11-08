---
name: track-true-profit-per-order
description: "Track true profit per order. Export your orders, list your product costs, shipping, platform fees and ad spend, and have the AI calculate profit per order and per product with the math shown. Check."
---

# Track true profit per order

## When to use

Online sellers who know their revenue but not what they actually keep on each order.

## Steps

1. Export last month's orders as CSV. Remove customer names and addresses.
2. Write down your costs: product cost per item, average shipping, platform and payment fees as you are charged them, and total ad spend.
3. Upload the file and paste the costs into the prompt below. Anthropic says you can upload CSV files for analysis and have Claude create Excel files with working formulas.
4. Check two orders by hand against the result before trusting it.
5. Look at the products with the lowest profit per order first; those are your pricing or ad decisions.
6. Keep the spreadsheet it builds and drop in each month's export.

## What to ask the user for

- LIST
- PER ORDER OR AVERAGE
- EXACTLY AS I AM CHARGED
- TOTAL

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I uploaded last month's orders. Calculate true profit per order and per product. Use only my file and these costs:

Product cost per item: [LIST]
Shipping cost: [PER ORDER OR AVERAGE]
Platform and payment fees: [EXACTLY AS I AM CHARGED]
Ad spend for the month: [TOTAL]

1. Confirm the columns you used and how you matched products to costs.
2. Profit per order = revenue - product cost - shipping - fees - (ad spend / number of orders). Show it for 3 sample orders.
3. Table by product: orders, revenue, total profit, profit per order, sorted lowest first.
4. Build it as an Excel file with formulas I can reuse.
If a cost is missing, say so instead of guessing.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Leaving out payment fees, which makes every order look better than it is.
- Mixing up revenue with and without tax.
- Trusting totals without checking two orders by hand.

## Source

https://www.aisetupsthatwork.com/setups/track-true-profit-per-order/ (AI Setups That Work)
