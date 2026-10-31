---
name: coordinate-team-volunteer-schedule
description: "Coordinate a volunteer or team schedule without the group-text chaos. Give AI your event dates, roles, and who is available when. It drafts a fair rotation, writes the call-for-volunteers message, and sets a reminder cadence, so you stop herding people over text. Use when the user asks for help with this job."
---

# Coordinate a volunteer or team schedule without the group-text chaos

## When to use

Volunteer coordinators, coaches, church organizers, and team leads drowning in scheduling group texts.

## Steps

1. List the events or shifts: dates, times, roles needed, how many people per role.
2. Collect availability. A simple form or group message works. Note skills and preferences too.
3. Ask the chatbot to build a rotation that spreads the load fairly and covers every shift.
4. Publish the schedule where everyone can see it: shared calendar, signup sheet, or a pinned post. Two to four weeks ahead.
5. Send the schedule with clear instructions: how to swap, who to tell, and the cutoff for changes.
6. Set reminders: one week out, then the day before. Keep an on-call backup list for no-shows.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build a volunteer schedule for our [event/season].

SHIFTS NEEDED:
[date, time, role, number of people per role]

VOLUNTEERS AND AVAILABILITY:
[name, when they can serve, skills or preferences, any dates they cannot do]

Create a fair rotation covering every shift. No one should be scheduled twice while someone else is scheduled zero times. Then draft:
1. A call-for-volunteers message I can send to recruit more help.
2. A confirmation message for each volunteer with their shifts.
3. A reminder schedule (when to nudge: 1 week out, day before).

Flag any shift we cannot cover and suggest how to handle it.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Building the perfect schedule and communicating it badly. The system must be obvious to a tired volunteer at 9pm.
- No swap process. Without one, people just no-show. Make swapping easy and visible.
- AI cannot contact your volunteers. It drafts the plan and the messages. You still send them.

## Source

https://www.aisetupsthatwork.com/setups/coordinate-team-volunteer-schedule/ (AI Setups That Work)
