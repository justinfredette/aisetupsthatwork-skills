---
name: costco-price-adjustment-watch
description: "Costco price adjustment watch. Costco's price match page for costco.com orders says a purchase that drops in price within 30 days can be eligible, for non-resale members. For a warehouse purchase it only says to ask at the Returns counter and gives no rule. Log purchases, check prices weekly, and ask early. Use when the user asks for help with this job."
---

# Costco price adjustment watch

## When to use

Costco members who buy electronics, appliances or other big items and want a simple way to catch a price drop after purchase. This is not financial advice. Do not paste your membership number or card details into a chatbot.

## Steps

1. Copy the item name, price paid, purchase date and where you bought it (warehouse or costco.com) from each receipt or order email. Leave out your membership number and card details.
2. Ask the chat for a table with each item's last day to ask. For a costco.com order, Costco's price match page states a 30-day window, so count purchase date plus 30 days. For a warehouse purchase it states no window, so ask at the Returns counter early.
3. Each week, look up the current price of every item still inside its window, in the warehouse or on costco.com, and tell the chat what you found. The chat cannot check live prices for you.
4. If a price is lower, ask the chat to draft the request. For a costco.com purchase, Costco's page points you to its price match request form. For a warehouse purchase, it says to inquire at the Returns counter at the warehouse where you bought the item. The page gives no eligibility rule for warehouse purchases, so the answer is up to the warehouse.
5. Log the request date. For costco.com requests, Costco says credits are typically issued within 5 to 10 business days to the original form of payment. If the window has passed, Costco's page says requests made after a promotion ends may be denied.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me track Costco price adjustments. Costco's price match policy for costco.com orders: for members other than resellers, a purchase that drops in price within 30 days of the purchase date is eligible. Items with specific sale dates also need the request inside the promotion dates. For warehouse purchases, the policy only says to ask at the Returns counter and states no window. Costco can deny a request.

My purchases: [item, price paid, purchase date, warehouse or costco.com]
Today's date: [DATE]

1. Make a table: item, price paid, last day to ask (30 days after purchase for costco.com orders; write "ask early" for warehouse purchases), weekly check date. Put the items closest to the deadline first.
2. When I give you a current price, say whether it is lower than what I paid, by how much, and whether the window is still open today.
3. If it is lower, draft the request. For costco.com: the details to put in the price match form. For a warehouse purchase: two sentences to say at the Returns counter.

Do not guess prices or dates. Ask me. Show me the table first. I send every request myself.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Asking after day 30 on a costco.com order. The window is counted from the purchase date, so set the reminder before the last day.
- Costco.com and warehouse purchases follow different routes: the online form versus the Returns counter.
- Items with specific sale dates need the request inside the promotion dates as well as the 30 days.

## Source

https://www.aisetupsthatwork.com/setups/costco-price-adjustment-watch/ (AI Setups That Work)
