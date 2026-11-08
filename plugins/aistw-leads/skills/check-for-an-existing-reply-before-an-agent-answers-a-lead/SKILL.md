---
name: check-for-an-existing-reply-before-an-agent-answers-a-lead
description: "Check for an existing reply before an agent answers. Add one rule before every lead reply: search sent mail and the lead's notes for anything sent in the last 7 days. If a teammate already answered."
---

# Check for an existing reply before an agent answers

## When to use

Teams where both people and an agent answer leads from email, forms and other channels.

## Steps

1. Decide where replies can live: sent mail, a shared inbox, CRM notes.
2. Add the check from the prompt below to the agent's instructions, before any drafting step.
3. Keep approval on. Anthropic says its Google Workspace connectors ask before sending by default.
4. Test it: answer a test lead yourself, then ask the agent to handle the same lead. It should stop.
5. Ask teammates to log phone and text replies in the notes, since the agent cannot see those otherwise.
6. Review the log of stopped drafts weekly to see where leads are coming in twice.

## What to ask the user for

- PASTE LEAD

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Before drafting any reply to a lead, do this check:

1. Search my sent mail and the lead notes for this person's name, email and phone from the last 7 days.
2. If anything was sent: STOP. Do not draft. Log: lead name, what was sent, by whom, when.
3. If nothing was sent: draft a reply for my approval and say which places you searched.
4. If you cannot search one of the places, say so and do not draft.

Lead: [PASTE LEAD]
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The agent can see email but not the CRM, so it misses replies logged there.
- Searching by name only and missing a different spelling.
- Turning off approval once it seems to work.

## Source

https://www.aisetupsthatwork.com/setups/check-for-an-existing-reply-before-an-agent-answers-a-lead/ (AI Setups That Work)
