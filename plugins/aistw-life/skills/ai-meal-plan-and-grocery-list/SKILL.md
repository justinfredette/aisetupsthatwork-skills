---
name: ai-meal-plan-and-grocery-list
description: "AI meal plan and grocery list. Turn “what should we eat this week?” into a written meal plan and a grocery list grouped by store section, using diet, budget, household size, and what you already have in the pantry, without the agent ordering groceries for you. Use when the user asks for help with this job."
---

# AI meal plan and grocery list

## When to use

Households that re-plan meals in their head every week and want one reusable prompt instead of a new chat each Sunday.

## Steps

1. List household size, days to cover, and hard diet rules (allergies, vegetarian, gluten-free, etc.).
2. Add a weekly food budget only if you will verify prices yourself. Do not trust invented line-item prices.
3. Paste pantry and fridge items so the list skips what you already own.
4. Name your store (or generic sections) so the list sorts by Produce, Protein, Dairy, Pantry, Frozen, etc.
5. Run the prompt; save the meal table and grocery list to your notes app.
6. Shop yourself; adjust quantities when you walk the aisles.
7. Optional second pass: paste recipes or blog links and ask for a list only, grouped the same way.
8. List what is actually on hand by category (grains, proteins, vegetables, flavor bases, fats), plus your time limit, equipment, and diet rules. Ask for several meal options that use only what you listed, with substitution ideas for anything missing.
9. Pick the winners, then ask the model to order them: cook what spoils first in the first two days, shift to shelf-stable pantry meals later in the week.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are helping me plan meals for my household. Use the details below. Do not invent foods I cannot eat or items I did not list unless you ask first.

Household: [number] adults, [number] children (ages if relevant)
Days to plan: [e.g. 5 dinners + lunches, or Mon–Sun all meals]
Diet and restrictions: [e.g. vegetarian, gluten-free, nut allergy]
Weekly food budget (optional): [amount or "flexible. No invented prices"]
Pantry and fridge on hand: [list what you already have]
Preferred store or layout: [store name, or "group by: Produce, Meat/Seafood, Dairy, Bakery, Pantry/Dry goods, Frozen, Household"]

Deliver:
1) A meal plan table (day, meal slot, dish name, note if using leftovers).
2) One consolidated grocery list grouped by the store sections above. Mark items that likely match my pantry list as "check pantry first."
3) Do not claim exact prices unless I paste a price list. Do not order delivery or check out online. I shop in person.

Ask one clarifying question only if a restriction or household detail is missing.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Models may guess prices or package sizes. Treat dollar amounts as unreliable until you check shelves.
- Allergy mistakes are high stakes. Re-read every ingredient line before you cook.
- Very long pantry lists can blow the context window; split into “plan meals” then “list only.”
- The model may quietly add ingredients you do not own. Check each option against your actual shelves before you start cooking.

## Source

https://www.aisetupsthatwork.com/setups/ai-meal-plan-and-grocery-list/ (AI Setups That Work)
