---
name: packing-list-for-any-trip
description: "Packing List for Any Trip (AI Builds It From Your Itinerary). Paste your destination, dates, activities, and luggage limits into ChatGPT. You get a packing list matched to the weather, the plan, and your bag size, with a do-not-forget section for documents and meds. Use when the user asks for help with this job."
---

# Packing List for Any Trip (AI Builds It From Your Itinerary)

## When to use

Anyone who overpacks “just in case” or has arrived somewhere missing chargers, swimwear, or a passport. Especially useful for family trips with kids.

## Steps

1. Gather the basics: destination, travel dates, who is going, and planned activities.
2. Note your luggage limit: carry-on only, one checked bag, or car trunk space.
3. Paste it all into the prompt below and ask for a categorized list with quantities.
4. Ask for a separate “do not forget” box: documents, medications, chargers, and kid essentials.
5. Check the weather yourself the night before and adjust layers. AI forecasts can be stale.
6. Save the list. Reuse it as your template for the next trip of the same type.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build me a packing list for this trip. Be specific with quantities.

Destination: [city/country]
Dates: [start to end]
Travelers: [e.g. "2 adults, kids 4 and 7"]
Activities: [e.g. "beach days, one nice dinner, hiking"]
Luggage: [carry-on only / one checked bag each / driving]
Laundry access: [yes/no]

Rules:
- Organize by category: documents, clothes, toiletries, electronics, medications, kids.
- Give quantities (e.g. "4 t-shirts," not "t-shirts").
- Add a "DO NOT FORGET" box at the top: passport/ID, tickets, medications, chargers.
- Flag anything I should buy at the destination instead of packing.
- Keep it to what fits the luggage I listed. Cut "just in case" extras.
- Draft only. I verify weather and travel documents myself before leaving.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI may ignore your luggage limit and list too much. Restate the bag size and ask it to cut.
- Seasonal advice can be wrong for the southern hemisphere or shoulder seasons. Check the forecast yourself.
- Medication and document reminders are generic. Your prescriptions and passport expiry are your job to verify.

## Source

https://www.aisetupsthatwork.com/setups/packing-list-for-any-trip/ (AI Setups That Work)
