---
name: price-a-job-without-losing-money
description: "Price a job so you do not lose money on it. Give the AI your monthly costs, your tax estimate, and how many hours you can actually bill. It works out the lowest price you can accept, then builds a quote from there. Use when the user asks for help with this job."
---

# Price a job so you do not lose money on it

## When to use

A freelancer or contractor who prices by gut feel and ends up busy but broke

## Steps

1. List your monthly living costs and monthly business costs. Rough numbers are fine for round one.
2. Estimate your billable hours per month. Be honest: most freelancers bill 15 to 25 hours a week, not 40.
3. Paste the prompt below with your numbers.
4. The AI gives you a price floor: the rate below which the job costs you money.
5. Describe the job: scope, deliverables, revision rounds. The AI builds a project quote from the floor up.
6. Add a 15 to 20 percent buffer for scope creep and revisions.
7. Sanity-check the result against your market. The floor is math, the final price is positioning.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me price a freelance job. My monthly living costs are $[X]. My monthly business costs are $[Y] (software, insurance, etc). I can realistically bill [Z] hours per month. For taxes, use a planning rate of [T]%. First, calculate my minimum hourly rate: (monthly living costs + monthly business costs) divided by (1 - tax rate), divided by billable hours. Show the math. Then price this job: [DESCRIBE THE JOB, DELIVERABLES, REVISION ROUNDS]. Give me a project price with a 15% buffer, and tell me what my floor is so I know where I cannot go below.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Using 40 billable hours a week in the math. You do not bill 40 hours. Use your real number.
- Treating the tax planning rate as tax advice. It is a planning guess. Your accountant sets the real number.
- Forgetting unpaid work: proposals, admin, revisions. The buffer exists for exactly this.
- Pricing from a competitor's rate instead of your own costs. Their costs are not yours.

## Source

https://www.aisetupsthatwork.com/setups/price-a-job-without-losing-money/ (AI Setups That Work)
