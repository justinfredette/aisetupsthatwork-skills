---
name: track-sent-bids-and-follow-up
description: "Track the bids you sent and follow up. Have the AI build a simple spreadsheet with one row per bid: customer, job, amount, date sent, next follow-up date and status. A formula flags today's."
---

# Track the bids you sent and follow up

## When to use

Contractors and small crews who send bids from a phone or laptop and lose track of which ones never got an answer.

## Steps

1. List your recent bids: customer, job, amount and the date you sent each one.
2. Ask the AI to build the tracker with the prompt below. Anthropic says Claude can create Excel files with working formulas.
3. Paste in your bids and check every amount and date against what you actually sent.
4. Each morning, filter for rows marked FOLLOW UP TODAY. That is your list.
5. Draft each follow-up with the quote follow-up setup, approve it and send it yourself.
6. Update the status the moment you hear back, so won and lost bids drop off the list.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build me a bid tracker spreadsheet (Excel) with one row per bid and these columns:
Customer | Job | Amount | Date sent | Next follow-up | Status (Waiting, Won, Lost) | Notes

Rules:
- Next follow-up = Date sent + 2 days for the first follow-up; I will update it after each one.
- Add a column Action that shows FOLLOW UP TODAY when Next follow-up is today or earlier and Status is Waiting, otherwise blank.
- Add a summary at the top: bids waiting, total value waiting, won this month, lost this month.
- Leave the rows empty for me to fill in. Do not invent customers or amounts.
Explain each formula in one line.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Formulas break when someone types text in a date column. Ask the AI to add date checks.
- Forgetting to move the follow-up date after each touch.
- Tracking bids in two places.

## Source

https://www.aisetupsthatwork.com/setups/track-sent-bids-and-follow-up/ (AI Setups That Work)
