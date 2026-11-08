---
name: connect-notetaker-tasks-and-email-to-ai
description: "Connect notes, tasks and email to AI. Both Claude and ChatGPT let you connect apps such as Gmail, Google Calendar and Google Drive. Claude's help center says it asks for your approval by default."
---

# Connect notes, tasks and email to AI

## When to use

Busy owners and managers who keep pasting emails and meeting notes into a chat. Connect only accounts you are allowed to share with an AI service. Skip client mail that is under a confidentiality agreement.

## Steps

1. Write down the three jobs you want help with, such as finding a thread, drafting a reply, or listing next week's meetings.
2. In ChatGPT, open Settings > Plugins, select the app, choose Install plugin if shown, then Connect. Sign in to the account that has the information and review the permissions it asks for.
3. In Claude, connect Gmail, Google Calendar or Google Drive from its connectors. On Team and Enterprise plans, Claude's help center says an Owner must turn the connectors on first.
4. If your notetaker or task app is not in either list, paste the notes or task export into the chat instead. A listed connector for them: Not stated in sources.
5. Start with read-only questions, such as find the last email from a client about a quote. Check that the answer matches your inbox.
6. Ask for drafts only. Claude's help center says it asks for approval before it sends, replies or forwards by default. Keep that on.
7. Review connections now and then. ChatGPT says you can manage a connected account from Settings > Plugins.

## What to ask the user for

- CLIENT NAME

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Use my connected email and calendar to help with this. Read only what you need.

Task: [for example: find the latest email thread with [CLIENT NAME] and list what they asked for]
Time range: [for example: the last 14 days]

Rules:
- Search and read only. Do not send, reply, forward, delete or change anything.
- If I ask for a reply, write a draft and show it to me. I will send it myself.
- Say which threads or events you used.
- If you could not find something, say so. Do not guess.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The connector for your notetaker or task app may not exist. Paste the text instead.
- On a work account, an administrator may have to approve the connector first.
- Letting the assistant send mail without a look. Keep the approval prompt on.

## Source

https://www.aisetupsthatwork.com/setups/connect-notetaker-tasks-and-email-to-ai/ (AI Setups That Work)
