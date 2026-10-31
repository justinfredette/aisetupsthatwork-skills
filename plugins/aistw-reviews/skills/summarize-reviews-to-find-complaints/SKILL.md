---
name: summarize-reviews-to-find-complaints
description: "Read 100 Reviews in 20 Minutes: Find What Customers Really Complain About. Paste 50 to 100 reviews into Claude or ChatGPT and ask for the top complaint themes with counts and example quotes. Fix the pattern, not the review. Use when the user asks for help with this job."
---

# Read 100 Reviews in 20 Minutes: Find What Customers Really Complain About

## When to use

Owners who feel reviews blur together and want to know the actual top three problems instead of reacting to the loudest one.

## Steps

1. Copy 50 to 100 recent reviews into a doc. Include the star rating with each one. Mix 5-star and 1-star.
2. Paste them into chat in chunks if needed, and ask for the top 5 complaint themes and top 3 praise themes, each with a count and 2 example quotes.
3. Ask which themes are getting worse in the last 3 months, if dates are included.
4. Spot-check the counts. Read 5 reviews per theme yourself to confirm the AI grouped them sensibly.
5. Pick the top 2 complaint themes you can actually fix. Write one action per theme.
6. Share the summary with your team. One page. No blame, just the pattern.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Analyze these customer reviews for my business and find the real patterns. Do not flatter me.

Business: [name, type]
Reviews (with star ratings):
[paste reviews]

Return:
1. Top 5 complaint themes, ranked by how often they appear. For each: theme name, count, and 2 short example quotes.
2. Top 3 praise themes, same format.
3. Any theme that appears more in recent reviews vs older ones.
4. One sentence on what the single most fixable problem looks like.

Rules:
- Count only what is actually in the text. Do not inflate.
- Keep quotes short and exact.
- If a review mentions two issues, count it under both.
- Tell me if the sample is too small to trust any theme.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- AI miscounts. Always spot-check the numbers against the raw reviews before acting.
- Small samples mislead. Twenty reviews can make one grumpy regular look like a movement.
- Do not confuse correlation with cause. "Slow service on Fridays" might be a staffing problem, not a speed problem.
- Ignoring the praise themes. Your strengths are marketing copy waiting to happen.

## Source

https://www.aisetupsthatwork.com/setups/summarize-reviews-to-find-complaints/ (AI Setups That Work)
