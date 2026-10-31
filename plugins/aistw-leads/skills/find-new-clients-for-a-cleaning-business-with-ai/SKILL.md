---
name: find-new-clients-for-a-cleaning-business-with-ai
description: "How to use AI to find new clients for a small cleaning business. Paste your service area, services, and proof points into an AI bot, ask it to build a prospect table from public business listings (property managers, offices, short-term rentals, realtors), draft one short intro per row, and stop. You review every row and send each message yourself. Use when the user asks for help with this job."
---

# How to use AI to find new clients for a small cleaning business

## When to use

Owner-operators of residential or commercial cleaning companies who know their craft but do not have time to hunt leads by hand after a slow season.

## Steps

1. Write facts only: services (recurring, move-out, commercial), cities, crew size, what makes you different (insured, eco products, etc.).
2. Ask the bot for prospect types that fit. Property managers, dental offices, Airbnb hosts, realtors, not scraped personal emails from social media.
3. Require a table with a public source link per row (directory, company site, or licensed listing). No invented phone numbers.
4. For each approved row, request a 3–4 sentence intro in plain language; you personalize and send from your email or phone.
5. Track status in the sheet: researched, drafted, sent, replied, not a fit.
6. When someone replies, switch to the capture-leads setup for quotes and follow-up, not more cold drafts.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
LOCAL CLEANING CLIENT RESEARCH (draft-only outreach)

My business facts (use only these: do not invent credentials):
[paste services, cities, years in business, insurance/bonding if true, website]

Task:
1) List 15–25 prospect organizations in [city/region] that plausibly need cleaning: property managers, offices, short-term rental operators, realtors (for move-out cleans), etc.
2) Output a table: business name | type | city | public contact method | source URL | why they might fit | draft intro (3 sentences max).
3) Rules: public sources only; no scraping personal emails from social profiles; no sending mail or DMs: drafts for me only.
4) Flag rows where contact info is unclear so I verify manually.
5) End with 3 follow-up angles I can use when someone says "send your rates."

I will review every intro and send messages myself. Check local rules on commercial email/text before I contact anyone.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Bots hallucinate contacts. Delete any row without a source link you can open.
- Cold email and text rules vary by country and state; this setup does not auto-send and is not legal advice.
- One viral “find clients” prompt does not replace referrals; expect to send many reviewed intros for a few replies.
- Do not upload tenant lists or private client data into chat. Prospects are public businesses only.

## Source

https://www.aisetupsthatwork.com/setups/find-new-clients-for-a-cleaning-business-with-ai/ (AI Setups That Work)
