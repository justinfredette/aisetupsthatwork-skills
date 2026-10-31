---
name: mileage-log-without-notebook
description: "Keep a mileage log without the notebook. Tell the AI your trips each week in plain words and it builds a dated mileage log with the date, destination, purpose, and miles the IRS asks for. Use when the user asks for help with this job."
---

# Keep a mileage log without the notebook

## When to use

Someone who drives for work and keeps meaning to log miles but never does

## Steps

1. At the end of each week, jot down your business trips: date, where you went, why, and the miles.
2. Paste the prompt below with your trips.
3. The AI formats them into a log: date, destination, business purpose, miles.
4. Add your odometer reading at the start and end of the year. The IRS wants both.
5. Save the log where you keep tax documents. Append weekly.
6. At tax time, multiply business miles by the IRS standard rate for that period.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build my mileage log for this week. Here are my trips in plain words: [LIST EACH TRIP: date, where I went, why, approximate miles]. Format them as a log with columns: date, destination, business purpose, miles. Flag any trip that looks like commuting (home to a regular workplace), since that does not count. Keep a running total of business miles. If a purpose is vague, ask me to clarify instead of guessing.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Reconstructing the whole year in April from memory. The IRS specifically rejects rebuilt logs.
- Logging commuting miles. They do not qualify, and including them poisons the whole log.
- Vague purposes like "business". Write what you actually did: "client meeting with Acme" counts.
- W-2 employees: you generally cannot deduct unreimbursed mileage on your federal return. This log is for reimbursement or for the self-employed.

## Source

https://www.aisetupsthatwork.com/setups/mileage-log-without-notebook/ (AI Setups That Work)
