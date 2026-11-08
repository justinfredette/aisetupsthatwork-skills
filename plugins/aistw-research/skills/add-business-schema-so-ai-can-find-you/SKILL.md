---
name: add-business-schema-so-ai-can-find-you
description: "Add business schema to your site. Google documents LocalBusiness structured data. name and address are required, and hours and other details are recommended. Test it with the Rich Results Test."
---

# Add business schema to your site

## When to use

Owners of a local business website with a physical address and set hours. Use only details that are true and shown on your site. Skip it if you cannot edit your page's code or ask your site manager.

## Steps

1. Write down your real details exactly as they appear on your site: business name, full address, phone, hours.
2. Ask the assistant to draft JSON-LD with the prompt below. Google's page lists name and address as required for LocalBusiness and hours as recommended.
3. Compare the draft with Google's example on its LocalBusiness page. Check every value against your own details.
4. Test the code before it goes live. Google says the Rich Results Test can check a code snippet, and supports JSON-LD, RDFa and Microdata.
5. Remove any comments from the JSON-LD before you publish. Google's help says the test ignores them but they can cause errors on a live page.
6. Add the code to your page, run the test on the live URL, and fix errors first and warnings second.
7. Google also recommends submitting a sitemap so it learns about changes. AI assistants using this markup: Not stated in sources.

## What to ask the user for

- NAME
- STREET
- CITY
- STATE
- ZIP
- COUNTRY
- PHONE
- URL
- DAYS AND TIMES

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Write LocalBusiness JSON-LD for my website. Use only the details below. Leave out any field I do not give you.

Business name: [NAME]
Business type: [for example: Plumber, Dentist, Restaurant]
Street: [STREET]
City: [CITY]
State or region: [STATE]
Postal code: [ZIP]
Country: [COUNTRY]
Phone: [PHONE]
Website: [URL]
Hours: [DAYS AND TIMES]

Rules:
- Output one JSON-LD script block and nothing else.
- Do not add reviews, ratings, prices, awards or geo coordinates unless I give them.
- No comments inside the code.
- After the code, list each field and the detail it came from.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Adding review or rating fields the page does not show. Leave them out.
- Hours that differ from the page text or your listings. Make them match.
- Pasting code that never got tested. Run the Rich Results Test first.

## Source

https://www.aisetupsthatwork.com/setups/add-business-schema-so-ai-can-find-you/ (AI Setups That Work)
