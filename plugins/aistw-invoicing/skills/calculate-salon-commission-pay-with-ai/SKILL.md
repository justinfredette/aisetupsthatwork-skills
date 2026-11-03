---
name: calculate-salon-commission-pay-with-ai
description: "Calculate salon commission pay with AI. Have the AI build a weekly pay sheet: hours, hourly rate, service sales, service commission rate, retail sales and retail commission rate, with formulas. Paste in the week's numbers from your booking system, check two stylists by hand, and send the totals to your payroll provider. Ask your accountant how commissions affect overtime. Use when the user asks for help with this job."
---

# Calculate salon commission pay with AI

## When to use

Salon and barbershop owners who work out hourly-plus-commission pay by hand every week.

## Steps

1. Write down each pay rule: hourly rate, service commission %, retail commission %, and any minimum or tier.
2. Use the prompt below to build the sheet. Anthropic says Claude can create Excel files with working formulas.
3. Each week, paste hours and sales from your booking system report.
4. Check two people's pay by hand before sending anything.
5. Overtime: the Department of Labor says overtime is paid on the regular rate, and its releases say earned commissions can count toward it. Confirm your setup with your accountant or payroll provider.
6. Send the totals to your payroll provider. Booth renters are not on payroll; handle their 1099s separately.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build a weekly pay sheet (Excel) for my salon. Use only my rules.

Pay rules per person: [NAME OR INITIALS: hourly rate, service commission %, retail commission %, any tiers]

Columns: Person | Hours | Hourly pay | Service sales | Service commission | Retail sales | Retail commission | Total before taxes
Add a row of totals and a note column. Show the formula for each column in one line. Leave rows empty for me to fill. Do not calculate taxes or overtime; flag anyone over 40 hours for me to check.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Including tips in commission sales by mistake.
- Forgetting retail returns.
- Treating booth renters like employees.

## Source

https://www.aisetupsthatwork.com/setups/calculate-salon-commission-pay-with-ai/ (AI Setups That Work)
