---
name: connect-your-bot-to-a-crm-the-safe-way
description: "Connect your bot to a CRM the safe way. Pick the safest route your app offers: an official connector or API, then a scheduled export, then a limited user login for the bot. Never paste your own admin password into chat. Start read-only, test on 3 records, and only then allow drafts. Use when the user asks for help with this job."
---

# Connect your bot to a CRM the safe way

## When to use

Trades and service businesses whose bot cannot get into the CRM, dispatch or messaging app it was set up for.

## Steps

1. Check what your app offers, in this order: an official connector or integration, an API key with limited scope, a scheduled export, a separate limited user for the bot.
2. Avoid giving the bot your own admin login. xAI notes that the bot's computer shares its browser, files and credentials, so anything signed in there is reachable.
3. Set up the safest route available and give it read-only access first.
4. Test with the prompt below on 3 records you can check by hand.
5. Only after the test passes, allow drafts, and keep sends and changes behind approval.
6. If sign-in keeps failing, switch to the export route rather than retrying; repeated failed logins can lock the account.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me connect my bot to [APP NAME] safely. Use only what I tell you.

What the app offers (connector, API keys, exports, user roles): [WHAT I FOUND IN SETTINGS]
What I need the bot to do: [e.g. read new leads, draft follow-ups]

1. Rank the connection options from safest to least safe for this job, with one line why.
2. For the safest workable option, list the setup steps and the smallest permission it needs.
3. Write a 3-record test I can check by hand.
Never ask me for my admin password.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Retrying failed logins until the account locks.
- Admin access when read-only would do.
- Connecting before deciding what the bot is actually for.

## Source

https://www.aisetupsthatwork.com/setups/connect-your-bot-to-a-crm-the-safe-way/ (AI Setups That Work)
