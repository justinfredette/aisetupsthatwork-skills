---
name: batch-appointments-dentist-doctor-car
description: "Batch your dentist, doctor, and car appointments. List every appointment your household needs this year. AI groups them by location and type so you book clusters on the same day instead of making twelve separate trips. Use when the user asks for help with this job."
---

# Batch your dentist, doctor, and car appointments

## When to use

Busy households making a separate trip across town every few weeks for appointments that could have shared a day.

## Steps

1. List every appointment the household needs: dentist, doctor, eye doctor, vet, car service, haircuts, all of it, for every person.
2. Note the location or area for each one, plus timing constraints (every 6 months, inspection due by a date).
3. Ask the chatbot to group them into the fewest possible outing days by location.
4. Call and book each cluster. Ask for back-to-back slots and say you are grouping errands. Offices do this all the time.
5. Put the booked appointments on the calendar immediately, with addresses and what to bring.
6. Set a reminder for two weeks before each cluster to confirm. One confirmation call beats three reschedules.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me batch our household appointments into the fewest outing days.

APPOINTMENTS NEEDED:
[person, appointment type, provider/location, how often, any deadline]

CONSTRAINTS:
[days we cannot do, school hours, work hours, anything fixed]

Group these into outing days by location so we make the fewest trips. For each outing day, list the appointments in a sensible order with rough times. Flag any that cannot be batched and say why.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Providers book out months ahead, so batching works best when you plan a season ahead, not next week.
- AI does not know real drive times or office hours. Sanity-check the clusters against a map.
- One cancellation can domino. Confirm the day before.

## Source

https://www.aisetupsthatwork.com/setups/batch-appointments-dentist-doctor-car/ (AI Setups That Work)
