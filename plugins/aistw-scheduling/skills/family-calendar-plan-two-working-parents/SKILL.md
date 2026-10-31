---
name: family-calendar-plan-two-working-parents
description: "Plan a family calendar with two working parents. Use AI to merge both parents’ schedules, school events, and kid activities into one shared calendar, with a 15-minute Sunday sync to keep it true. One calendar both parents trust beats two perfect ones nobody checks. Use when the user asks for help with this job."
---

# Plan a family calendar with two working parents

## When to use

Two working parents who keep double-booking, missing permission slips, or arguing about who is on pickup duty.

## Steps

1. Pick one shared calendar both parents can see and edit. Google Calendar or Apple Calendar both work.
2. Each parent dumps their next four weeks: work travel, late nights, appointments, kids’ activities, school events.
3. Ask the chatbot to merge the dumps into one clean list, flag conflicts, and assign an owner to every pickup, drop-off, and appointment.
4. Create the events on the shared calendar with the owner’s name in the title, like "Pickup - Maya (Mom)".
5. Set two reminders: 30 minutes before everyday events, 24 hours before anything needing prep (field trip, permission slip).
6. Hold a 15-minute Sunday sync. Walk the coming week, reassign what changed, done.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
We are two working parents merging our schedules into one family calendar. Here are our next 4 weeks:

PARENT 1 SCHEDULE:
[work hours, travel, late nights, personal appointments]

PARENT 2 SCHEDULE:
[work hours, travel, late nights, personal appointments]

KIDS' ACTIVITIES AND SCHOOL EVENTS:
[sports practices, games, concerts, half days, holidays]

Do three things:
1. List every scheduling conflict or tight handoff you see.
2. Propose who handles each pickup, drop-off, and appointment, balancing the load fairly.
3. Draft a simple weekly rhythm (which parent covers which recurring duty) we can reuse.

Flag anything that needs a backup plan, like both of us traveling the same week.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- One parent keeps a private mental calendar and the shared one goes stale. Both have to add things the moment they learn them.
- AI cannot reach into your actual calendars, so paste the real schedules in. It works from what you give it.
- Forgetting the 24-hour prep reminder. The dentist appointment is easy. The dentist appointment needing the insurance card is the one that bites.

## Source

https://www.aisetupsthatwork.com/setups/family-calendar-plan-two-working-parents/ (AI Setups That Work)
