---
name: track-holiday-returns-with-claude
description: "Track holiday returns with Claude. Connect Gmail and Google Calendar to Claude, then ask it to search the mail for holiday order confirmations and build a table of last return days, checked against."
---

# Track holiday returns with Claude

## When to use

Claude users whose holiday orders land in Gmail. Anthropic says the Gmail and Google Calendar connectors are available to all users; on Team and Enterprise an owner turns them on first.

## Steps

1. Connect Gmail and Google Calendar to Claude and sign in with the Google account. On Team and Enterprise plans, an owner has to enable the connectors first.
2. Turn on web search from the + button in the chat, so Claude can read each store's return policy page.
3. Paste the prompt below. For in-store receipts, add photos to a Project called Holiday returns, cropped so no card number shows, and run the prompt there.
4. Check the table. Any window Claude could not confirm from the store's page says "check store"; look those up yourself.
5. Read the list of calendar events Claude proposes: one all-day event on each last return day, titled with the store and item. Reply OK to add them, or edit the list first.
6. When an item goes back, delete its event, or ask Claude to. Nothing in this prompt starts a return or emails a store.

## What to ask the user for

- START DATE
- LIST, or "none yet"

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me track my holiday returns. Do not send, reply to or forward any email, do not start a return, and do not create calendar events until I reply OK. Never repeat card numbers.

1. Search my Gmail for order confirmations and receipts from [START DATE] to today. Skip newsletters and ads.
2. Make a table: store, item, order date, delivery date (if in the email), return window, last day to return, order number.
3. For each store, search the web for its return policy page and use that window, with a link. If you cannot confirm it, write "check store". Do not guess.
4. Sort by last day to return, soonest first.
5. Items I am keeping: [LIST, or "none yet"]. Leave them out.
6. List the Google Calendar events you would create: an all-day event on each last return day, titled "Return by: [store] [item]", with the order number in the description. Wait for my OK before creating any.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Gifts shipped by someone else are not in your mail. Add those from the gift receipt or the packing slip.
- A shipping notice can be mistaken for the order email. Check any row where the dates look off.

## Source

https://www.aisetupsthatwork.com/setups/track-holiday-returns-with-claude/ (AI Setups That Work)
