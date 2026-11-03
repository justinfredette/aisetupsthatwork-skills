---
name: pick-your-first-ai-agent-job
description: "Pick your first AI agent job. List your repetitive weekly tasks, score each for hours spent, how often it repeats and how bad a mistake would be, and start with the one that is frequent, slow and low risk, usually drafting replies or sorting the inbox. Run it with approval on for 30 days before adding a second job. Use when the user asks for help with this job."
---

# Pick your first AI agent job

## When to use

Owners who keep hearing about AI agents but do not know which job to hand over first.

## Steps

1. Write down every task you do more than once a week, with rough minutes each time.
2. Paste the list into the prompt below. It scores each task for time saved, repetition and risk.
3. Pick the top task that is low risk. Drafting, sorting and summarizing are safer first jobs than sending, paying or deleting.
4. Before connecting anything, remember OpenAI says a signed-in agent can access sensitive data and perform actions. Keep approval on for anything that leaves the business.
5. Run it for 30 days. Track minutes saved and every mistake.
6. Add a second job only after the first one runs a month without surprises.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me pick the first job to hand to an AI agent.

My weekly tasks (task, minutes each time, times per week): [PASTE LIST]

For each task, score 1 to 5:
- Time it eats per week
- How repetitive it is
- Risk if the AI gets it wrong (5 = very risky)

Then:
1. Rank the tasks by (time + repetition) minus risk.
2. Recommend one first job and say why.
3. Write a 30-day test plan: what the agent does, what I approve, and what I measure each week.

Use only my list. Do not suggest tools I did not mention.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Starting with something risky, like payments, because it saves the most time.
- Connecting every account at once.
- Skipping the measuring, then not knowing if it helped.

## Source

https://www.aisetupsthatwork.com/setups/pick-your-first-ai-agent-job/ (AI Setups That Work)
