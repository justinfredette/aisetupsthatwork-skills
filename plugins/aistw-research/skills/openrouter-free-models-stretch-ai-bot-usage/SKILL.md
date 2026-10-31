---
name: openrouter-free-models-stretch-ai-bot-usage
description: "How to use OpenRouter free models to stretch your AI bot's usage. Keep planning on your main bot. Hand summaries, sorting, boilerplate, and first drafts to Pi on an OpenRouter free model and to OpenCode. Use when the user asks for help with this job."
---

# How to use OpenRouter free models to stretch your AI bot's usage

## When to use

People whose bot hits its usage limit right when they need it. A lot of what it does is grunt work: summarizing, sorting, first drafts. Grunt work does not need the top model.

## Steps

1. Main bot: keeps the planning and the final call. It decides what to hand off.
2. Helper 1, Pi on OpenRouter: Pi is an open-source coding agent you run in a terminal. Log in with an OpenRouter key and pick a model whose ID ends in :free.
3. Helper 2, OpenCode: another terminal coding agent. Its Zen catalog lists some models as free for a limited time.
4. Radar (optional): once a week it checks which free models are new and ranks them for the jobs you hand off most.
5. Give the starter prompt to your main bot.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You have two helpers for cheap work: Pi (using an OpenRouter :free model) and OpenCode (using one of its free models).
Before you start a task, sort it:
- Hand off: summaries, file sorting, boilerplate code, first drafts, reformatting.
- Keep: anything with passwords, keys, personal data, client data, or a final decision.
When you hand off, send only the text the helper needs. Check its result before you use it.
If a helper returns a rate-limit error (429), wait and retry once, then do the task yourself.
Once a week, list any new free models and rank the top 3 for my hand-off jobs. Ask me before switching.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Last checked: Oct 20, 2026. The free tiers have limits. OpenRouter's docs cap :free models at 20 requests a minute and 50 a day, or 1,000 a day once you've bought at least 10 credits. OpenCode marks its free models as limited-time, so the lineup changes.

## Source

https://www.aisetupsthatwork.com/setups/openrouter-free-models-stretch-ai-bot-usage/ (AI Setups That Work)
