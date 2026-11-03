---
name: review-what-your-ai-agent-did-each-week
description: "Review what your AI agent did each week. Once a week, export or copy what the agent did, from sent drafts and bookings to edits and errors, and have an AI sort it into done well, needed fixing and should not have happened. Tighten one rule for every problem. Use when the user asks for help with this job."
---

# Review what your AI agent did each week

## When to use

Anyone running an AI agent on email, calendar or a store who wants to stop babysitting it daily without losing control.

## Steps

1. Pick a fixed 15 minutes each week.
2. Gather what the agent touched: sent folder, drafts, calendar changes, order notes or the agent's activity history.
3. Remove personal details you do not need, then paste it into the prompt below with your rulebook.
4. Read the should-not-have-happened list first. OpenAI says a signed-in agent can access sensitive data and perform actions, so treat these seriously.
5. For each problem, change one thing: tighten a rule, remove an app connection, or move the action behind approval.
6. Keep the weekly reports. Fewer problems over time is how you know you can trust it with more.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Review what my AI agent did this week. Use only what I paste.

My rulebook: [PASTE RULES]
Agent activity this week: [PASTE ACTIONS, DRAFTS, SENT ITEMS, CHANGES]

Sort every action into:
1. Fine
2. Needed fixing (what was wrong)
3. Should not have happened (which rule it broke)

Then give me:
- The one rule change that would have prevented the most problems
- Anything that looks like it acted outside its permissions

Keep it under 300 words.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Reviewing only what the agent reports about itself; check the real sent folder too.
- Fixing problems in a chat instead of in the agent's standing rules.
- Skipping weeks once things look fine.

## Source

https://www.aisetupsthatwork.com/setups/review-what-your-ai-agent-did-each-week/ (AI Setups That Work)
