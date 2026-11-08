---
name: holiday-travel-backup-plan-with-claude
description: "Holiday travel plan B with Claude. Make a Claude Project for the trip, add the confirmations to its knowledge, and turn on web search. Optionally connect Google Calendar so Claude can read the trip."
---

# Holiday travel plan B with Claude

## When to use

Claude users traveling to family over the holidays by plane, train or car, especially with a connection, kids or a fixed arrival time.

## Steps

1. Make a Project named for the trip and add the confirmations to its knowledge. Crop out payment details first.
2. Turn on web search from the + button in the chat. Optional: connect Google Calendar so Claude can read the trip events.
3. Paste the prompt below into a chat in the Project.
4. Check every plan B on the airline, rail or rental site yourself. The prompt marks anything Claude could not confirm.
5. Save the key numbers outside the chat: the airline's phone number, the hotel's number and the confirmation codes.
6. The evening before, open the Project and paste the check in the last line of the prompt. If a flight is cancelled on the day, use the flight cancelled setup.

## What to ask the user for

- WHO, with ages for kids
- DATE, TIME, and why
- LIST
- FLIGHT NUMBERS

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Plan my holiday travel day with a backup for every leg. Research and planning only: do not book, change, cancel or pay for anything, and do not create or change calendar events.

Travelers: [WHO, with ages for kids]
Legs: [e.g. drive to airport, flight 1, connection, flight 2, ride to family] (confirmations are in this Project; trip events are in my Google Calendar, if connected)
Must arrive by: [DATE, TIME, and why]
Home airport and other airports I could use: [LIST]
Willing to drive instead? [yes, up to X hours / no]

1. Make a travel-day timeline: leave-by time, each leg with times, and the buffer at each connection.
2. For each leg, give a plan B if it is delayed 2 or more hours or cancelled: later flights the same day on the same airline, nearby airports, a train, or driving time. Use web search on the airline's or rail company's site and link the schedules. Mark anything you could not confirm as "check".
3. Tell me the point of no return: the latest time I can switch to a plan B and still arrive by my deadline.
4. Give me a short carry-on list for a long delay: chargers, snacks, medicine, kids' things.

EVENING-BEFORE CHECK (I will paste this later):
Search the current status of flights [FLIGHT NUMBERS] and the weather at each airport for tomorrow. Tell me what changed since the plan above and whether any plan B should move up.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Claude lists a later flight that does not run on your date. Check plan B flights on the airline's site for the exact day.
- The calendar event has a different time than the confirmation. Trust the airline's confirmation and fix the calendar.

## Source

https://www.aisetupsthatwork.com/setups/holiday-travel-backup-plan-with-claude/ (AI Setups That Work)
