---
name: ask-ai-questions-about-your-spreadsheet
description: "Ask AI questions about your spreadsheet. Export the sheet as CSV or Excel, upload it, and ask one plain question at a time. Ask the AI to show the rows and math behind each answer, and spot-check one number yourself before you act on it. Use when the user asks for help with this job."
---

# Ask AI questions about your spreadsheet

## When to use

Owners with sales, ad, expense or job data in a spreadsheet who want answers without building formulas.

## Steps

1. Export the sheet as CSV or Excel. Remove columns with personal or payment details you do not need for the question.
2. Upload it. Anthropic says you can upload CSV and other files for data analysis and charts.
3. Ask it to describe the columns first and confirm what each one means. Fix any wrong guesses before asking real questions.
4. Ask one question at a time with the prompt below, and require the rows and math behind each answer.
5. Spot-check one answer by hand in the sheet. If it is wrong, tell it which number is wrong and why.
6. Ask for a small chart or a cleaned table you can paste back into your sheet.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I uploaded a spreadsheet. First, list each column and what you think it means, then wait for me to confirm.

After I confirm, answer this question: [YOUR QUESTION, E.G. WHICH AD CAMPAIGN COST THE MOST PER LEAD LAST MONTH?]

Rules:
- Show the exact rows and the math you used.
- Say how many rows you included and why any were left out.
- If the data cannot answer the question, say so and say what column is missing.
- Do not round money until the final answer.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Dates in mixed formats get misread. Ask it to list any dates it could not read.
- Totals that include a summary row double-count. Remove summary rows before uploading.
- Trusting a chart without checking one number.

## Source

https://www.aisetupsthatwork.com/setups/ask-ai-questions-about-your-spreadsheet/ (AI Setups That Work)
