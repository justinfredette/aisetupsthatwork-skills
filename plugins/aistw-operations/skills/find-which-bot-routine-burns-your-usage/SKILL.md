---
name: find-which-bot-routine-burns-your-usage
description: "Find which bot routine burns your usage. Most usage goes to a few routines: browser clicking loops, long always-loaded instructions, retries and bots sharing big context. List every scheduled routine, note how often it runs and whether anyone used its output, then trim, merge or retire the worst. Set a spend cap so nothing burns silently. Use when the user asks for help with this job."
---

# Find which bot routine burns your usage

## When to use

Owners running several bots whose plan runs out early and who cannot tell which routine is to blame.

## Steps

1. List every scheduled routine and bot: what it does, how often it runs, and when you last used its output.
2. Mark the usual heavy hitters: anything that clicks through websites, retries on failure, runs every few minutes, or loads long instructions every time.
3. Run the prompt below on your list and usage export.
4. Act on the calls: retire what nobody used, merge duplicates, slow down frequent runs, swap browser clicking for a connector or export.
5. Set caps and approvals for spend. xAI documents spend and purchase approvals for Grok Bot; for API keys, set a monthly limit per key.
6. Repeat the review monthly. Grok Bot group owners reported plans used up within an hour; a monthly review catches the routine before it does that.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Here is my list of bot routines and my usage data. Use only what I paste.

Routines (name, what it does, how often, last time I used its output): [PASTE]
Usage export or notes: [PASTE]

For each routine:
1. Likely usage: high, medium or low, with the reason (browser clicking, retries, frequency, long instructions)
2. Call: KEEP, TRIM (how), MERGE (with what) or RETIRE
3. A cheaper way to do the same job, if one exists, such as a connector, an export or a less frequent schedule
Then list the top 3 changes that would save the most. Do not change any bot; this is a proposal for me to approve.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Cutting the routine people rely on because it looks expensive.
- No list of routines, so nothing to review.
- Letting a bot rewrite other bots instead of proposing changes.

## Source

https://www.aisetupsthatwork.com/setups/find-which-bot-routine-burns-your-usage/ (AI Setups That Work)
