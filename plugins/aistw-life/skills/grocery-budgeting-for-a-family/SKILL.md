---
name: grocery-budgeting-for-a-family
description: "Grocery Budgeting for a Family (A Meal Plan That Fits the Number). Give ChatGPT your weekly grocery budget, family size, dietary limits, and store. You get a 7-day meal plan with a shopping list that stays under the number, built around staples and one leftover night. Use when the user asks for help with this job."
---

# Grocery Budgeting for a Family (A Meal Plan That Fits the Number)

## When to use

Families trying to hold a weekly grocery number without eating the same three meals. Works whether your budget is tight or just undefined.

## Steps

1. Set your number first. A budget you will not name is a budget you will not keep.
2. List what is already in your pantry, fridge, and freezer.
3. Note dietary limits, dislikes, and the store you shop at.
4. Paste it all into the prompt and ask for 7 dinners, lunches from leftovers, and a sectioned shopping list.
5. Shop from the list only. The list is the budget.
6. After the week, note what got wasted and tell the AI to adjust next week’s plan.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build me a 7-day family meal plan that stays under my grocery budget.

Budget: [amount per week, e.g. "$150/week"]
Family: [e.g. "2 adults, kids 8 and 5"]
Dietary limits: [e.g. "no seafood, one vegetarian"]
Store: [e.g. "Aldi and Walmart"]
Already have: [pantry/fridge/freezer staples, e.g. "rice, pasta, frozen chicken, canned tomatoes"]
Cooking skill/time: [e.g. "30 minutes max on weeknights"]

Rules:
- 7 dinners, each under 30 minutes unless I say otherwise.
- One leftover night built in (cook once, eat twice).
- Lunches come from dinner leftovers or simple staples.
- Shopping list organized by store section, with nothing I already have.
- Total estimated cost must stay under my budget. Show the math per meal.
- Favor staples: beans, rice, eggs, seasonal produce, store brands.
- Draft only. I check prices at my store; your estimates are a starting point.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI may plan meals your kids will not eat. List the three foods each kid refuses before generating.
- Portion math can be off for teenagers or big appetites. Scale up proteins if your family eats more than average.
- Sale prices change weekly. Re-check the plan against your store’s flyer before shopping.

## Source

https://www.aisetupsthatwork.com/setups/grocery-budgeting-for-a-family/ (AI Setups That Work)
