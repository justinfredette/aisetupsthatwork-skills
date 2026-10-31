---
name: compare-colleges-side-by-side-with-ai
description: "Compare colleges side by side: cost, grad rates, and outcomes. Give the AI your shortlist of schools plus your family income range, and ask for a table of net price, graduation rate, median debt, and earnings. You compare real outcomes instead of brochure gloss. Use when the user asks for help with this job."
---

# Compare colleges side by side: cost, grad rates, and outcomes

## When to use

Parents and students narrowing a college list who want numbers, not viewbook photos.

## Steps

1. Narrow your list to 3 to 6 schools you are seriously considering.
2. Note your family income range. Net price depends heavily on it, and sticker price means little.
3. Ask the AI to build a comparison table from College Scorecard data: net price for your income, graduation rate, median debt, and median earnings 10 years out.
4. Verify the two or three most important numbers on the College Scorecard site yourself.
5. Ask the AI to flag which schools are strong or weak on value: low debt plus decent earnings beats prestige alone.
6. Add your non-number factors: distance, size, programs, campus feel. Numbers narrow the list; visits decide it.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me compare these colleges using federal College Scorecard data:

Schools: [LIST 3 TO 6 SCHOOLS]
Family income range: [e.g. 75,000 to 110,000]
Intended major, if known: [MAJOR OR "undecided"]

Build a table with one row per school:
- Average net price for our income range
- Graduation rate
- Median student debt at graduation
- Median earnings 10 years after entry
- Acceptance rate

Then tell me:
1. Which schools look strongest on value (low debt, solid earnings)?
2. Which ones have red flags in the data?
3. What questions should we ask on a campus visit or with the financial aid office?

Use College Scorecard figures where possible. If a number is unavailable or you are unsure, say so instead of guessing.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- AI college data goes stale. Verify the key numbers on the Scorecard site before any decision.
- The AI can mix up similarly named schools. Check that each row is the right campus.
- Rankings optimize for prestige, not your wallet. Keep the table focused on cost and outcomes.

## Source

https://www.aisetupsthatwork.com/setups/compare-colleges-side-by-side-with-ai/ (AI Setups That Work)
