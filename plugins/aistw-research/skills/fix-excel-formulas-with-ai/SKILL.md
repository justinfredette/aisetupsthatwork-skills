---
name: fix-excel-formulas-with-ai
description: "Fix and Write Excel Formulas With AI. Paste the broken formula and describe what it should do, and AI will usually spot the error or write the replacement. Validate every AI formula on a few rows first, and never paste sensitive data into the chat. Use when the user asks for help with this job."
---

# Fix and Write Excel Formulas With AI

## When to use

Anyone who uses spreadsheets at work but is not a formula expert.

## Steps

1. Copy the broken formula and note the error value: #VALUE!, #NAME?, #REF!, #DIV/0!, or similar. Microsoft documents each one with different causes.
2. Describe what the formula should do in plain words, naming exact columns and ranges. Example: "total sales in column C where values are above 500".
3. Ask AI to fix the formula or write a new one. Paste the formula text, not the whole spreadsheet.
4. Test the result on 3 to 5 sample rows before applying it to the full dataset.
5. Turn on Excel's built-in error checking too: File, Options, Formulas, then Enable background error checking. Cells with problems get a small triangle.
6. For recurring errors, learn the pattern. A common one: AVERAGE or SUM over cells containing #VALUE! returns #VALUE!, fixable with an IF and ISERROR wrapper.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me fix or write an Excel formula. Plain and practical.

What it should do: [e.g. total sales in column C where the value is above 500]
Broken formula (if any): [paste the formula text]
Error shown: [e.g. #VALUE!, #NAME?, none yet]
My columns: [e.g. A=Date, B=Product, C=Sales]

Write:
1. The corrected or new formula.
2. One sentence explaining what was wrong or how it works.
3. Any version notes (e.g. array formula entry with Ctrl+Shift+Enter on older Excel).

Rules:
- Use only standard Excel functions, nothing exotic.
- Keep it readable: I need to maintain this later.
- Do not ask for my data. The formula text and column names are enough.
- Show me the formula first. I will test it on sample rows before using it.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Pasting sensitive company data into the chat. Describe the structure; paste the formula, not the rows.
- Trusting the first answer. Validate on a small subset before applying to thousands of rows.
- More than 64 nested functions. Excel caps nesting: restructure with helper columns instead.
- Forgetting the equals sign. A formula typed without = displays as plain text.

## Source

https://www.aisetupsthatwork.com/setups/fix-excel-formulas-with-ai/ (AI Setups That Work)
