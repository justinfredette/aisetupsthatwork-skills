---
name: build-a-local-prospect-list-with-ai
description: "Build a local prospect list with AI help. Search your trade plus town on Google Maps, export the listings, and let the AI research each one and draft a personalized first line. Fifty real prospects in an afternoon. Use when the user asks for help with this job."
---

# Build a local prospect list with AI help

## When to use

Web designers, marketers, and service providers who pitch local businesses like landscapers, cleaners, and contractors.

## Steps

1. Pick one trade and one town. "Landscapers in Rutland" beats "businesses in Vermont."
2. Search Google Maps for that trade plus town. Open the listings that look active.
3. For each business, note: name, phone, website (or "no website"), and review count. Aim for 50.
4. Paste the list in batches plus the prompt below into the AI. It researches each website and flags what is missing.
5. Review the flags. Delete anyone who is not actually a fit, no matter what the AI says.
6. For your top 20, have the AI draft one personalized opener each, based on the specific thing it found.
7. Work the list in order. Log every contact: date, channel, response. One follow-up max for non-responders.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Research these local businesses for my outreach list. Be factual and skeptical. If you cannot verify something, say so.

My service: [WHAT YOU SELL, e.g. "websites for trades businesses"]
My filter: I only want businesses that [CRITERIA, e.g. "have no website or a clearly outdated one, and look active with recent reviews"]

Businesses (batch of 10):
1. [NAME]: [WEBSITE OR "NO WEBSITE LISTED"]: [REVIEW COUNT IF KNOWN]
[ADD MORE]

For each business, return:
- What they do, in one line (from their site or listing).
- Online presence check: website? How old does it look? Active social profiles? Recent reviews?
- Fit verdict: GOOD FIT / MAYBE / SKIP, with one-line reason.
- If GOOD FIT: one personalized opener (two sentences max) referencing the specific thing you found. Factual and verifiable only: no invented details.

Rules: never invent a website, a review count, or a business detail. Mark anything unverified as unverified. Skip chains and franchises unless I say otherwise.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Pitching from the list without verifying. An AI-hallucinated "outdated website" in your opener destroys trust instantly.
- Scraping at scale without checking the rules. Google Maps data has terms of service, and cold outreach has spam laws. Keep it manual-sized and honest.
- Using only public contact info is the line. Never buy or scrape personal emails or phone numbers.
- Targeting businesses that already have what you sell. Check their site before you claim they need one.

## Source

https://www.aisetupsthatwork.com/setups/build-a-local-prospect-list-with-ai/ (AI Setups That Work)
