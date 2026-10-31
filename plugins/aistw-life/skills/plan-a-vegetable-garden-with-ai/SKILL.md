---
name: plan-a-vegetable-garden-with-ai
description: "Plan a vegetable garden with AI. Give the AI your zip code or last frost date and how much space you have. It builds a planting calendar: what to start indoors, what goes straight in the ground, and the order to plant it all. Use when the user asks for help with this job."
---

# Plan a vegetable garden with AI

## When to use

First-time or frustrated gardeners who plant at the wrong time and want a calendar that fits their actual location.

## Steps

1. Get your two anchor dates: the last spring frost and the first fall frost for your zip code. Every planting date is calculated from these.
2. Tell the AI your space: beds, containers, or square feet, plus sun hours. A 4x8 bed in full sun gets a different plan than a shady balcony.
3. Ask for the calendar split by timing. The standard rules: warm-season crops like tomatoes, peppers, cucumbers, beans, and zucchini go outdoors after the last frost; cool-season crops like lettuce, spinach, peas, and broccoli can go out 4 to 6 weeks before it.
4. Add the indoor starts. Slow warm-season crops get started indoors 6 to 10 weeks before the last frost, per planting-calendar guidance.
5. Plan the fall too. Count backward from the first fall frost: leafy greens go in 6 to 8 weeks before it, garlic 4 to 6 weeks before.
6. Sanity-check the calendar against a local source. The two most common timing mistakes are planting too early (cold soil and late frosts set plants back) and planting too late (crops run out of time before frost).
7. Print the calendar or save it where you will see it in March. A plan in a chat thread is a plan you will forget.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build me a vegetable planting calendar for my garden.

Location: [zip code or town, e.g. "05773"]
Space: [e.g. "two 4x8 raised beds, full sun, about 6 hours"]
Experience: [e.g. "beginner. Second year; last year everything went in too late"]
What I want to grow: [e.g. "tomatoes, peppers, lettuce, carrots, herbs"]

Rules:
- Base every date on my local last spring frost and first fall frost. State both dates up front so I can verify them.
- Split into: start indoors / direct sow after last frost / fall planting.
- For each crop: variety suggestion for a beginner, spacing, and one common mistake to avoid.
- Keep it to what fits my space. Do not plan 20 crops for two beds.

Review the dates against a local planting calendar before you buy seeds. Frost dates vary by microclimate.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI does not know your microclimate. A frost date is a regional average; low spots and windy corners run colder. Verify against a local calendar.
- Planting by the calendar while ignoring the soil. Cold wet soil rots seeds even after the "safe" date. If it is soggy, wait.
- Too many crops for the space. Crowded plants grow poorly and invite disease. Thin the plan before you thin the seedlings.

## Source

https://www.aisetupsthatwork.com/setups/plan-a-vegetable-garden-with-ai/ (AI Setups That Work)
