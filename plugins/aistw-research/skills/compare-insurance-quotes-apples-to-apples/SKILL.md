---
name: compare-insurance-quotes-apples-to-apples
description: "Compare insurance quotes apples to apples. Give the AI your current declarations page and each new quote, and ask it to line up identical coverage, limits, and deductibles. You find out which quote is actually cheaper for the same protection. Use when the user asks for help with this job."
---

# Compare insurance quotes apples to apples

## When to use

Anyone shopping insurance who has three quotes and no idea which one actually covers them.

## Steps

1. Find your current declarations page. It lists your drivers, vehicles, limits, deductibles, and premium.
2. Get quotes from at least two other carriers using the exact same limits and deductibles.
3. Paste your declarations page and each quote into the prompt below.
4. Ask the AI to build a table with identical rows: liability limits, deductibles, extras, fees, total premium.
5. Ask it to flag anywhere a quote is cheaper because the coverage is weaker, not because the price is better.
6. Check the financial strength rating (AM Best) and complaint index (NAIC) of any unfamiliar carrier before you switch.
7. This is not financial advice, and do not paste full medical records into a chatbot. Type only the plan's public numbers into your comparison: premium, deductible, copays, coinsurance, and out-of-pocket maximum.
8. For each plan, calculate two numbers: the expected year (premium times 12 plus your likely care costs) and the worst year (premium times 12 plus the full out-of-pocket maximum). Compare those two numbers across plans, not the premium alone.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I am comparing insurance quotes and want an apples-to-apples comparison.

My current policy (declarations page):
[PASTE DECLARATIONS PAGE DETAILS]

Quote 1 from [CARRIER]:
[PASTE QUOTE DETAILS]

Quote 2 from [CARRIER]:
[PASTE QUOTE DETAILS]

[ADD MORE QUOTES AS NEEDED]

Build a table with identical rows for each quote: liability limits, deductibles, uninsured motorist coverage, extras and endorsements, fees, discounts applied, and total premium. Flag every place where a quote looks cheaper only because the coverage is weaker. Ignore the phrase "full coverage" and compare the actual line items. Tell me which quote gives the most protection per dollar and what questions I should ask the agent before switching.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Quotes with different term lengths (6 months vs 12 months) are not directly comparable. Normalize them first.
- The AI can miss state-specific requirements. Confirm minimums with your state insurance department.
- A low premium with a deductible you cannot afford after a crash is not a good deal.
- Comparing only monthly premiums. The out-of-pocket maximum is the worst-case ceiling, and it is where the real comparison happens.

## Source

https://www.aisetupsthatwork.com/setups/compare-insurance-quotes-apples-to-apples/ (AI Setups That Work)
