---
name: cap-what-your-ai-agent-can-spend
description: "Cap what your AI agent can spend. Give each agent its own project or workspace with its own key, set a monthly spend limit below what you can afford to lose, and add an alert at half. Anthropic and."
---

# Cap what your AI agent can spend

## When to use

Owners and builders running agents on pay-as-you-go API keys, especially for clients.

## Steps

1. List every agent and which API key it uses. Shared keys make one runaway task hit everything.
2. Create one project or workspace per agent and give each its own key.
3. Set a monthly spend limit. Anthropic says you can set your own limit below your tier cap on the Billing page in the Claude Console; OpenAI documents per-project spend limits and notification thresholds.
4. Set an alert at about half the limit so you hear before it stops.
5. Use the prompt below to write a short clause for client work on usage limits and who pays for overruns.
6. Check spend weekly for the first month and adjust.

## What to ask the user for

- DESCRIPTION
- AMOUNT
- CLIENT OR ME

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Write a short clause for my client agreement about AI usage costs. Plain English, under 120 words.

What I run for the client: [DESCRIPTION]
Monthly usage cap I set: [AMOUNT]
What happens at the cap: [e.g. the agent pauses and I notify the client]
Who pays above the cap, and only with written approval: [CLIENT OR ME]

Also list the 3 settings I should confirm before starting: spend limit, alert threshold, separate key. This is a draft for my lawyer to review, not legal advice.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Leaving keys in a default workspace that cannot have its own limit.
- Setting a limit higher than you can afford.
- Forgetting subscriptions and plan overages are billed separately from the API.

## Source

https://www.aisetupsthatwork.com/setups/cap-what-your-ai-agent-can-spend/ (AI Setups That Work)
