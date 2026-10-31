---
name: cash-vs-card-vs-check-fees
description: "Decide whether to take cards, cash, or checks. Tell the AI your average sale size and monthly volume. It does the fee math for cards, ACH, and checks so you can decide what to accept based on numbers, not vibes. Use when the user asks for help with this job."
---

# Decide whether to take cards, cash, or checks

## When to use

A small business owner wondering if credit card fees are eating their margin

## Steps

1. Write down your average sale size and roughly how much you take in cards per month.
2. Note how you get paid today: cards, checks, bank transfer, cash.
3. Paste the prompt below with your numbers.
4. The AI compares the real cost of each method at your volume, including the flat per-transaction fees.
5. Look at the speed tradeoff too: cards cost 2 to 3 percent but get you paid days or weeks sooner.
6. Decide your mix: many businesses take cards for speed and push big invoices to ACH.
7. If you pass fees to customers, check your state's surcharge rules first. Some states restrict them.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me decide which payment methods to accept. My average transaction is $[AMOUNT]. I process roughly $[VOLUME] per month. Currently I accept [cards / checks / bank transfer / cash]. Compare the true cost of: 1) credit cards at typical small-business rates, 2) ACH bank transfer, 3) paper checks including my time to deposit them, 4) cash including handling. Show the math for my volume. Then recommend a payment mix and tell me when it makes sense to steer a client toward ACH instead of card. Note any state surcharge rules I should check.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Comparing only the headline percentage and ignoring the per-transaction flat fee.
- Forgetting that checks cost your time: trips to the bank, waiting for clearance, chasing bounced ones.
- Surcharging debit cards. You cannot surcharge debit under card network rules.
- Assuming your state allows surcharging. A few states restrict it. Check before you implement.

## Source

https://www.aisetupsthatwork.com/setups/cash-vs-card-vs-check-fees/ (AI Setups That Work)
