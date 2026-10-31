---
name: car-maintenance-schedule
description: "Car Maintenance Schedule You Will Actually Follow. Tell ChatGPT your car’s year, make, model, and mileage. You get a maintenance schedule by interval: monthly checks you do yourself, mileage-based services, and seasonal prep, with your owner’s manual as the final word. Use when the user asks for help with this job."
---

# Car Maintenance Schedule You Will Actually Follow

## When to use

Car owners who only think about maintenance when a light comes on. Especially useful if you just bought used and have no service history.

## Steps

1. Write down your car’s year, make, model, mileage, and how you drive (short trips, highway, towing).
2. Check your owner’s manual for the manufacturer’s service intervals.
3. Paste the car details into the prompt and ask for a schedule by interval.
4. Compare the AI schedule against your manual. The manual wins every disagreement.
5. Ask for a simple service log template: date, mileage, what was done, cost.
6. Set calendar reminders for the monthly checks. A schedule you never look at is decoration.
7. Log every service. A documented history protects warranties and resale value.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build me a car maintenance schedule I will actually follow.

Vehicle: [year, make, model, e.g. "2021 Honda CR-V"]
Current mileage: [e.g. "62,000 miles"]
Driving: [e.g. "mostly short trips" / "highway commute" / "towing"]
Oil type if known: [conventional / synthetic blend / full synthetic / unknown]
Climate: [e.g. "New England winters"]

Rules:
- Organize by interval: monthly DIY checks, every 5k-10k miles, seasonal, annual.
- Monthly checks must be things I can do in 10 minutes: tire pressure, fluids, lights, wipers.
- Include tire rotation, brake inspection, battery, filters, belts, and coolant at sensible intervals.
- Add a winter-prep and summer-prep section for my climate.
- Give me a service log template: date, mileage, service, cost, shop.
- Note where my owner's manual overrides you. I will verify intervals against it.
- You do not diagnose car problems. If I describe a noise or leak, tell me to see a mechanic.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI may give intervals for the wrong engine or trim. Verify against your manual, especially for oil type and timing belts.
- It cannot diagnose noises, leaks, or warning lights. Those need a mechanic, not a longer prompt.
- Generic schedules ignore climate. Winter salt, summer heat, and dusty roads all change the plan.

## Source

https://www.aisetupsthatwork.com/setups/car-maintenance-schedule/ (AI Setups That Work)
