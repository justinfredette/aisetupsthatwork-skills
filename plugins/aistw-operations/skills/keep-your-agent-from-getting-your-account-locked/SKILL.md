---
name: keep-your-agent-from-getting-your-account-locked
description: "Keep your agent from getting your account locked. Platforms watch for automated activity. Meta's terms forbid collecting data by automated means without permission, even when logged in. Use official apps, APIs or exports instead of having an agent click through a site, limit how often it runs, and make it stop and tell you at any login check or warning. Use when the user asks for help with this job."
---

# Keep your agent from getting your account locked

## When to use

Owners whose agent logs into social, ad or marketplace accounts to read insights or post, and who cannot afford a locked account.

## Steps

1. List every account the agent logs into and what it does there.
2. Check each platform's terms. Meta's say you may not access or collect data from its products by automated means without prior permission.
3. Switch to an official route where one exists: a connector, the platform's own export, or its API.
4. Add the rules from the prompt below to the agent's instructions.
5. Turn on two-factor sign-in and keep a recovery method you control, in case of a lock.
6. If an account gets flagged, stop the agent on that account before appealing.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Add these rules to your standing instructions for any website account:

1. Use only the connections I list: [OFFICIAL APPS, APIS, EXPORTS].
2. Do not click through a site page by page to collect data.
3. Run each account task at most [N] times a day. Never loop a task that fails; stop after 2 tries and tell me.
4. At any captcha, security check, new-device prompt or warning: stop immediately and tell me. Never try to get past it.
5. Never change account settings, names or security options.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Letting an agent retry a failing login.
- Using the agent on a personal profile tied to a business page.
- No recovery email or phone you still control.

## Source

https://www.aisetupsthatwork.com/setups/keep-your-agent-from-getting-your-account-locked/ (AI Setups That Work)
