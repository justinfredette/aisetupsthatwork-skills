---
name: share-a-client-portal-page-in-notion
description: "Share a client portal page in Notion. One Notion page per client, shared as a guest link, answers the what is happening emails before they are sent. Notion's permission levels let clients see or."
---

# Share a client portal page in Notion

## When to use

Freelancers and small agencies juggling a handful of clients. Check permission levels before you share; anything linked on a shared page itself is visible to its guests.

## Steps

1. Create a page per client with 4 blocks: current status, next steps with dates, files and links, and decisions made.
2. Run the prompt below to draft the first status update from your rough notes.
3. Share the page to the client as a guest. Notion's help says guests get access to the pages you share, not your whole workspace.
4. Choose the access level on purpose. Notion lists levels from full access down to comment and view only.
5. Update the page weekly, same day and time, so clients learn when to look.
6. When the project ends, remove the guest or stop sharing the page.

## What to ask the user for

- NAME
- WHAT
- PASTE ROUGH NOTES
- CHECK

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Turn my rough notes into a client status update.

Client: [NAME]
Project: [WHAT]
My notes: [PASTE ROUGH NOTES]

Write for the client page:
- Status in 2 sentences, plain words, no jargon
- Next steps with dates, oldest first
- Decisions made this week, one line each

Rules:
- Use only facts from my notes. If a date or detail is missing, write [CHECK] instead of guessing.
- No promises I did not make.
- Show me the update first. Do not send it to the client.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Guests see everything on the shared page itself, including comments. Keep internal notes on a separate private page.
- Inherited permissions can expose more than you meant. Check the parent page's access before sharing.
- A portal that goes stale is worse than none. Pick one update day and keep it.

## Source

https://www.aisetupsthatwork.com/setups/share-a-client-portal-page-in-notion/ (AI Setups That Work)
