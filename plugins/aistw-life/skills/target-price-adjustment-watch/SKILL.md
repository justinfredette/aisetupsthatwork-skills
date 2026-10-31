---
name: target-price-adjustment-watch
description: "Target price adjustment watch. Target's policy matches a lower price at Target (Target.com, Target stores or a Target Circle deal), not at other retailers. Ask at purchase or within 14 days, with the original receipt and proof. Clearance and closeout are excluded. For purchases from Nov 1, 2026, a holiday policy applies if the price drops on or before Dec 24, 2026. Use when the user asks for help with this job."
---

# Target price adjustment watch

## When to use

Target shoppers who buy items that go on sale soon after and want to claim the lower price within the policy window. This is not financial advice. Do not paste card numbers or account details into a chatbot.

## Steps

1. Copy the item name, price paid, purchase date and whether you bought in store or online from each receipt or order email. Leave out card numbers.
2. Ask the chat for a table with each item's last day to ask (purchase date plus 14 days) and two check dates. Target's policy page says price matches can be requested at the time of purchase or within 14 days after purchase.
3. Look up the current price at Target: Target.com, a Target store or a Target Circle deal. Other retailers do not count. The item must be the identical item: same brand, size, weight, color, quantity and model number. The chat cannot check live prices.
4. Skip items Target excludes, such as clearance, closeout, liquidation, open package, refurbished and pre-order items. The full exclusion list is on Target's policy page.
5. If the price is lower, ask the chat to draft your request and a proof checklist. For a store purchase, take proof of the current lower price and the original receipt (physical or digital) to the store. Target's help pages name Guest Services and also say store adjustments can be done on any lane. For a Target.com or Target app purchase, chat with Target online or call Guest Services.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me track Target price adjustments. Target's policy: if I buy an item at Target and later find the identical item for less at Target (Target.com, a Target store or a Target Circle deal), I can ask at purchase or within 14 days after purchase. Other retailers do not count. The item must be identical (brand, size, weight, color, quantity, model number). The original receipt is required. Clearance, closeout, liquidation, open package, refurbished and pre-order items are excluded. For purchases from November 1, 2026, a separate holiday policy covers a lower Target price on or before December 24, 2026; tell me to read it on Target's page.

My purchases: [item, price paid, purchase date, store or online]
Today's date: [DATE]

1. Make a table: item, price paid, last day to ask (purchase date plus 14 days), two check dates.
2. When I give you a current price, say whether it is lower, by how much, and whether I am still inside 14 days today.
3. If it is lower, draft a short request and a proof checklist: receipt, the current price shown on Target.com or the app, and the item details.

Do not guess prices or dates. Ask me. Show me the table first. I make every request myself.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Asking for clearance items. Clearance and closeout are on Target's exclusion list.
- A lookalike item. The model number has to match, not only the brand and the size.
- Missing the receipt. Target says original receipts, physical or digital, or packing slips are required for adjustments up to 14 days after purchase.

## Source

https://www.aisetupsthatwork.com/setups/target-price-adjustment-watch/ (AI Setups That Work)
