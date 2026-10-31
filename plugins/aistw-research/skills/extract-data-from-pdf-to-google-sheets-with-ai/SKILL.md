---
name: extract-data-from-pdf-to-google-sheets-with-ai
description: "How to extract data from a PDF to Google Sheets with an AI bot. Give an AI bot the file and a list of fields, and ask for one row per record with the page number. Spot-check rows against the PDF before you use the sheet. Use when the user asks for help with this job."
---

# How to extract data from a PDF to Google Sheets with an AI bot

## When to use

People with big PDFs and Word files full of numbers they need in a spreadsheet, who then have to type the same data into web forms.

## Steps

1. Extractor bot: reads the PDF or Word files on your computer and pulls the fields you name into rows.
2. Sheets step: puts those rows in a Google Sheet, one row per record, with a column for the source file and page.
3. Form helper (optional): fills a web form from a row, then stops and shows you a screenshot. You check it and click submit yourself.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Read the files in [FOLDER] (PDF and Word).
Pull these fields from each record: [FIELD 1], [FIELD 2], [FIELD 3].
Put one record per row in a Google Sheet called [SHEET NAME], with two extra columns: source file and page number.
If a value is unclear or missing, leave the cell blank and add a note. Don't guess.
When done, give me a count of rows and a list of anything you skipped.

Web forms: fill [FORM URL] from row [N] only after I say go. Stop before submitting, show me a screenshot of the filled form, and wait for me to approve. Never submit on your own.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Scanned PDFs and tables that cross pages are where extraction slips. Check a sample of rows against the source page numbers before you use the sheet for anything that matters.

## Source

https://www.aisetupsthatwork.com/setups/extract-data-from-pdf-to-google-sheets-with-ai/ (AI Setups That Work)
