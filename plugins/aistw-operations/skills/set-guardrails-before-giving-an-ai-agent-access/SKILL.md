---
name: set-guardrails-before-giving-an-ai-agent-access
description: "Set guardrails before an AI agent gets access. Write down, before you connect anything, what the agent may read, what it may only draft, and what it may never do without you. Give it its own account or the narrowest access the tool offers, keep send, pay and delete behind your approval, and review its log weekly. Use when the user asks for help with this job."
---

# Set guardrails before an AI agent gets access

## When to use

Owners who want an AI agent on their inbox, calendar, store or files but are nervous about letting it loose. No coding needed.

## Steps

1. List every account the agent would touch: email, calendar, files, store, bank, social. Next to each, write the worst thing it could do there.
2. Sort every action into four buckets: read, draft for you, do after your approval, never. Sending, paying, deleting and changing settings start in the approval or never bucket.
3. OpenAI says ChatGPT agent, once signed into sites or apps, can access sensitive data like emails, files or account settings and perform actions. Treat every connection as access to that whole account.
4. Give the agent the narrowest access the tool offers. Anthropic says its Google Workspace connectors ask for approval before sending, replying or forwarding by default; keep that default on.
5. Use the prompt below to turn your buckets into a short rulebook, then paste it into the agent's instructions or project.
6. Test it on a harmless task and ask the agent to repeat back what it is not allowed to do.
7. Once a week, read what the agent did and move any action that surprised you one bucket stricter.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Turn my notes into a one-page rulebook for an AI agent that helps run my business. Use only what I list.

Accounts it will touch: [EMAIL, CALENDAR, FILES, STORE...]
Read only: [WHAT IT MAY READ]
Draft for me to review: [WHAT IT MAY DRAFT]
Only after I approve: [E.G. SEND, BOOK, REFUND]
Never: [E.G. DELETE, PAY, CHANGE PASSWORDS, POST PUBLICLY]

Format:
- 4 short sections with those headings
- A final rule: if a task is not covered, stop and ask me
- Plain sentences, under 250 words

Do not add permissions I did not list.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Connecting the agent to an account with more power than the job needs, like a shared admin login.
- Writing rules the agent never sees because they live in a doc it is not given.
- Forgetting to check the agent's actions after the first week.

## Source

https://www.aisetupsthatwork.com/setups/set-guardrails-before-giving-an-ai-agent-access/ (AI Setups That Work)
