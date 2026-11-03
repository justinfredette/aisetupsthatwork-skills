---
name: find-long-questions-people-search-in-search-console
description: "Find the long questions people search to find you. In Search Console, open Performance, add a Query filter, choose Custom (regex) and paste ^(?:\\S+\\s+){7,}\\S+$ to see searches of 8 words or more. Export them, have AI group them, and answer the high-impression, low-click questions at the top of the page that already shows up. Use when the user asks for help with this job."
---

# Find the long questions people search to find you

## When to use

Small business and content sites that get impressions in Google but few clicks.

## Steps

1. Open Search Console, then Performance, then Search results. Set the date to the last 3 months.
2. Add a filter: Query, then Custom (regex). Google added regex filters to Performance reports. Paste ^(?:\S+\s+){7,}\S+$ to match searches of 8 or more words.
3. Export the table with queries, pages, impressions, clicks and position.
4. Upload it and run the prompt below to group the questions and pick the best ones.
5. For each pick, add a short direct answer near the top of the page that already ranks, in plain words.
6. Check the same filter in 4 weeks to see if clicks moved.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I uploaded a Search Console export of searches with 8 or more words. Use only this file.

1. Group the queries into questions that mean the same thing.
2. For each group: total impressions, total clicks, average position, and the page that shows up.
3. Pick the 10 groups with the most impressions and fewest clicks.
4. For each, draft a 2 to 3 sentence answer for the top of that page, using only facts I confirm.
Do not invent numbers or claims about my business.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Too short a date range, so the list is empty.
- Writing a new page instead of improving the one that ranks.
- Answers that bury the question under an introduction.

## Source

https://www.aisetupsthatwork.com/setups/find-long-questions-people-search-in-search-console/ (AI Setups That Work)
