---
name: yearly-home-maintenance-calendar
description: "Build a year-long home maintenance calendar. Tell AI your home’s age, heating system, and climate. It builds a month-by-month maintenance calendar with reminders, so the furnace filter, gutters, and smoke alarms get handled on schedule instead of during a crisis. Use when the user asks for help with this job."
---

# Build a year-long home maintenance calendar

## When to use

Homeowners who only think about maintenance when something breaks, usually at the worst time.

## Steps

1. List the facts: home age, heating type (oil, gas, heat pump), water heater age, roof age, septic or sewer, climate.
2. Ask the chatbot to build a 12-month maintenance calendar with specific tasks per month and time estimates.
3. Review it against reality. Delete what does not apply, add what is unique to your house (pool, wood stove, sump pump).
4. Put each month’s tasks on your calendar as recurring annual events with the task list in the event notes.
5. Set a reminder for the first weekend of each month: "Do this month’s home tasks." Most months take under two hours.
6. Once a year, update the calendar. Systems age, and the list should age with them.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build me a 12-month home maintenance calendar.

HOME: [age, stories, square footage]
HEATING: [oil/gas/heat pump/pellet]
WATER HEATER: [age and type]
ROOF: [age and material]
OTHER SYSTEMS: [septic/sewer, well/city water, wood stove, sump pump, pool]
CLIMATE: [e.g. Vermont: cold winters, mud season]

For each month, list 3-5 specific maintenance tasks with rough time estimates. Mark which tasks need a pro (roof, electrical, gas) versus DIY. Put safety items (smoke alarms, CO detectors, fire extinguisher) on a schedule I cannot ignore. Note anything seasonal I should book ahead, like chimney sweeping or furnace service.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- A generic list that ignores your house. A Florida checklist will not help a Vermont winter. Customize for climate and systems.
- Skipping the "boring" months. The quiet months are when small things get caught.
- AI cannot inspect your house. It does not know your roof is 25 years old unless you tell it.

## Source

https://www.aisetupsthatwork.com/setups/yearly-home-maintenance-calendar/ (AI Setups That Work)
