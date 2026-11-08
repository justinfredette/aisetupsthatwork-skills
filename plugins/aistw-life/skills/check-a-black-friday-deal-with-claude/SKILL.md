---
name: check-a-black-friday-deal-with-claude
description: "Check a Black Friday deal with Claude. Turn on web search from the + button in the chat, then paste the deal: store, exact model number, sale price and the \"was\" price. Ask Claude to find the same."
---

# Check a Black Friday deal with Claude

## When to use

Anyone using Claude who wants a second look at a Black Friday or Cyber Monday price before buying. Web search has to be on, and a Project keeps the season's checks together.

## Steps

1. In a Claude chat, click the + button and choose Web search. A checkmark shows it is on. On Team and Enterprise plans, an owner has to allow web search for the workspace first.
2. Optional: make a Project called Holiday shopping and paste the prompt's rules into the project instructions, so every deal you check there follows them.
3. Paste the prompt below with the deal details from the store page. Attach a price-history screenshot if you have one.
4. Check the table: the same model number in every row, a link for every price, and a date on each one. Remove rows for bundles or different models.
5. Read the verdict on the "was" price. If Claude says it could not confirm it, count the discount as unproven.
6. Open the cheapest links yourself and check the final price, shipping and return window on the store's page. Buy there yourself if it still looks right.

## What to ask the user for

- STORE
- PRODUCT NAME
- EXACT MODEL NUMBER
- PRICE
- DATE, if shown

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me check whether this holiday deal is real. Research only. Do not buy anything, add anything to a cart, or sign me up for anything.

Store: [STORE]
Product: [PRODUCT NAME]
Model or item number: [EXACT MODEL NUMBER]
Sale price: [PRICE]
"Was" or "compare at" price the store shows: [PRICE]
Sale ends: [DATE, if shown]
Price-history screenshot: [attached / none]

1. Use web search to find the same model number at other major stores and the maker's own site. Make a table: store, price today, link, and whether the model number matches mine exactly. Leave out bundles, refurbished items and different model numbers, and say which ones you left out. If a page shows no price, write "no price found" instead of estimating.
2. Tell me whether the "was" price looks like a price the item really sold for recently. Use the price-history screenshot if I attached one. If you cannot find evidence either way, say "could not confirm" and do not guess.
3. Give a one-line verdict: looks like a real discount, looks inflated, or could not confirm, with the reason.
4. List what I should check on the store page before buying: the final price with tax and shipping, the return window, and who the seller is.
Date every price you quote and say where it came from.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Claude finds the right product in a different size or color. Ask it to match the exact variant before comparing prices.
- A store page may not show its price to a search. Claude should then write "no price found", not guess one.

## Source

https://www.aisetupsthatwork.com/setups/check-a-black-friday-deal-with-claude/ (AI Setups That Work)
