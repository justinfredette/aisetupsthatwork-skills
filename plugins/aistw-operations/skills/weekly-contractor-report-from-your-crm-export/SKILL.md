---
name: weekly-contractor-report-from-your-crm-export
description: "Weekly contractor report from your job app export. Export jobs, quotes and invoices as CSV from your field-service or CRM app once a week. Upload them and ask for a one-page report: revenue, jobs done, open quotes by age, unpaid invoices and customers who are due for repeat work. Check two numbers against the app before trusting it. Use when the user asks for help with this job."
---

# Weekly contractor report from your job app export

## When to use

Contractors and trades using a job or CRM app who never look at its reports because they take too long.

## Steps

1. Find the export in your job app for jobs, quotes and invoices. Most apps offer CSV.
2. Remove customer phone numbers and addresses you do not need for the report.
3. Upload the files and run the prompt below. Anthropic says Claude can analyze uploaded CSV files and create Excel files with formulas.
4. Check two numbers, such as total invoiced and unpaid total, against the app.
5. Act on the lists: follow up on old quotes, chase unpaid invoices, contact repeat customers.
6. Ask for the same layout every week so you can compare.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I uploaded last week's exports from my job app: jobs, quotes and invoices. Use only these files.

Give me one page:
1. Revenue invoiced, revenue collected, jobs completed
2. Open quotes by age: under 7 days, 7 to 30, over 30, with customer and amount
3. Unpaid invoices over 14 days, with customer and amount
4. Customers whose last job was 10 to 14 months ago (possible repeat work)
5. Anything odd: duplicates, jobs with no invoice
Say which columns you used. If a number cannot be worked out, say so.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Exports with different date formats; tell the AI which format your app uses.
- Trusting totals without a check.
- Uploading full customer records when names and amounts are enough.

## Source

https://www.aisetupsthatwork.com/setups/weekly-contractor-report-from-your-crm-export/ (AI Setups That Work)
