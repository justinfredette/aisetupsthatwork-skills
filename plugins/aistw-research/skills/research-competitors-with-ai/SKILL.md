---
name: research-competitors-with-ai
description: "Research competitors through your customer’s eyes. Build a competitor comparison from public websites, ads, and reviews. Positioning, pricing, strengths, and the one question they answer better than you, then turn it into copy and one test. Use when the user asks for help with this job."
---

# Research competitors through your customer’s eyes

## When to use

Small business owners who know they should watch competitors but never find a free afternoon to do it properly.

## Steps

1. Write down your business in two sentences: who you help, your offer, one thing you want to improve.
2. Pick 1–3 competitors a customer would realistically consider instead of you.
3. Paste the master prompt and answer its setup questions; let it search the web.
4. For blocked pages, upload screenshots with the URL and capture date.
5. Ask it to compare the sites through three customer perspectives: first-time visitor, price shopper, skeptic.
6. End with one table: positioning, pricing, strengths, weaknesses, and your single biggest opening.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I own [business name]: [two sentences on who I help and what I sell]. One thing I want to improve: [e.g., homepage headline, pricing page].

Competitors to research: [1-3 names + website URLs].

For each competitor, find from public sources: positioning (who they claim to serve), pricing or pricing signals, 3 strengths, 3 weaknesses, and anything new in the last 90 days. Then compare all of them against my business through the eyes of three customers: a first-time visitor, a price shopper, and a skeptic.

Deliver: a comparison table, the ONE question each competitor answers more clearly than I do, and my single biggest opportunity plus my single biggest threat. Cite the source URL for every factual claim. Do not invent prices, reviews, or news, if you cannot verify it, say so.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Simulated customer perspectives are not real interviews. Use the output to choose what to test, not as proof.
- Public ads and pages do not show profit; a competitor can look strong online and be weak underneath.
- Models will confidently fill gaps when sources are thin; the "cite every claim" line is load-bearing.

## Source

https://www.aisetupsthatwork.com/setups/research-competitors-with-ai/ (AI Setups That Work)
