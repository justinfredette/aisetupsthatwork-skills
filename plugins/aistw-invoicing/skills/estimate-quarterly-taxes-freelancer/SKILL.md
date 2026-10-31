---
name: estimate-quarterly-taxes-freelancer
description: "Estimate your quarterly taxes without the panic. Give the AI last year's total tax and this year's income so far. It figures your quarterly payment using the IRS safe harbor rule, which protects you from underpayment penalties. Use when the user asks for help with this job."
---

# Estimate your quarterly taxes without the panic

## When to use

A freelancer or self-employed person who owes estimated taxes and wants to avoid penalties

## Steps

1. Find last year's Form 1040. Write down line 24 (total tax) and line 11 (AGI).
2. If last year's AGI was over $150,000, your safe harbor is 110 percent of last year's tax. Otherwise 100 percent.
3. Paste the prompt below with your numbers.
4. The AI divides the safe harbor amount by four. That is your quarterly payment.
5. Mark the four deadlines: April 15, June 15, September 15, and January 15.
6. Pay through IRS Direct Pay or EFTPS. Keep the confirmation.
7. Remember: safe harbor avoids the penalty, but if you earned more this year, the balance is still due in April.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me calculate my quarterly estimated tax payments using the IRS prior-year safe harbor. Last year's total tax (Form 1040 line 24) was $[AMOUNT]. Last year's AGI (line 11) was $[AMOUNT]. I am [single / married filing jointly]. Calculate: 1) whether the 100% or 110% safe harbor applies, 2) my total required payments for the year, 3) my quarterly payment amount. List the four 2026 deadlines. Remind me that state estimated taxes are separate and that I should confirm everything with my accountant.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Thinking safe harbor means you owe nothing in April. It only avoids the penalty. The balance is still due.
- Forgetting state taxes. Most states with income tax want quarterly payments too.
- Missing a deadline. The penalty accrues per quarter from the due date, so pay late rather than never.
- Using the 100 percent rule when your AGI was over $150,000. That triggers the 110 percent rule.

## Source

https://www.aisetupsthatwork.com/setups/estimate-quarterly-taxes-freelancer/ (AI Setups That Work)
