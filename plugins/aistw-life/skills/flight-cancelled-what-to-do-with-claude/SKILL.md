---
name: flight-cancelled-what-to-do-with-claude
description: "Flight cancelled? Next steps, Claude. Check the airline's app first; it may already show a new flight. Then ask Claude, with web search on and Gmail connected, to find the cancellation email and."
---

# Flight cancelled? Next steps, Claude

## When to use

Claude users whose holiday flight was just cancelled or badly delayed, who want a clear ask ready while waiting for the airline.

## Steps

1. Open the airline's app and email first. Note any new flight it already offered, and any deadline it gives to accept or change it.
2. Get in the airline's queue (app chat, phone or counter) before starting in Claude, so the place in line is not lost.
3. Turn on web search from the + button. If Gmail is connected, Claude can find the notice; otherwise paste it.
4. Paste the prompt below, in the trip Project if there is one. Leave out payment details and passport numbers.
5. Talk to the airline yourself. Before accepting a voucher or a new flight, ask what refund applies if you decline it, and get the answer in writing.
6. Keep every receipt and a screenshot of the notice. For a refund or compensation claim later, the claim setup on this site walks through the official US and EU rules.

## What to ask the user for

- AIRLINE, FLIGHT NUMBER, DATE
- FROM, TO, any connection
- DETAILS / none
- DATE, TIME, and why
- LIST
- ADULTS, KIDS

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
My flight was just cancelled and I need to know what to ask for. Do not send any email, contact the airline, or book, change or cancel anything for me.

Airline and flight: [AIRLINE, FLIGHT NUMBER, DATE]
Route: [FROM, TO, any connection]
What the airline said: [PASTE THE NOTICE, or "find the latest email from the airline in my Gmail"]
New flight it offered, if any: [DETAILS / none]
Must arrive by: [DATE, TIME, and why]
Other airports I could use: [LIST]
Who is traveling: [ADULTS, KIDS]

1. List my options in order of which gets me there by my deadline: the offered flight, other flights on the same airline today or tomorrow, nearby airports, and a refund if I decide not to travel. Use web search on the airline's site and link the schedules. Mark anything you could not confirm.
2. Write a short, polite script I can read to the agent: my flight, what I am asking for, and two backup asks.
3. Write three questions to ask before I accept anything, including what refund I can get if I turn the new flight down.
4. List what to keep: receipts, screenshots, and the time of each call or chat.
5. Do not tell me what the law says from memory. If I ask about my rights, search for and quote the US Department of Transportation's page or the EU's official air passenger rights page, with the date on the page.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Claude suggests a flight that is already full or gone. Check the airline's app before asking for it.
- It states a rule from memory. Ask for the official page and its date, or use the claim setup.

## Source

https://www.aisetupsthatwork.com/setups/flight-cancelled-what-to-do-with-claude/ (AI Setups That Work)
