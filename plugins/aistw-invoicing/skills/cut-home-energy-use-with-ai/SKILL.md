---
name: cut-home-energy-use-with-ai
description: "Cut home energy use with AI. Give the AI your last few utility bills and basic facts about the house. It ranks where your energy is going and tells you which fixes to do first, cheapest first. Use when the user asks for help with this job."
---

# Cut home energy use with AI

## When to use

Homeowners with a painful utility bill who want to know what to fix first instead of guessing.

## Steps

1. Gather the bills. Three to six months of totals and usage history is enough; the AI needs the pattern, not your account numbers.
2. List the house facts: approximate age, square footage, heating system type and age, water heater type and temperature setting, thermostat type.
3. Ask for the energy ranking first: where is the energy most likely going, in order. The Department of Energy notes heating can be almost half of a winter bill and water heating 14 to 25 percent of a home’s energy.
4. Get the fix list ordered by cost, cheapest first. The DOE’s monthly checklist starts with: collect the bills and target the biggest consumer, insulate hot-water pipes and ducts in unheated areas, seal the largest air leaks, and set back a programmable thermostat at night.
5. Hunt the real leaks, not the obvious ones. Per the DOE, the worst air leaks are usually plumbing penetrations, gaps around chimneys and recessed lights, and unfinished spaces behind cupboards, not windows and doors. Small cracks can add up to the equivalent of an open window.
6. Do the free wins this weekend: set the water heater to 120 degrees, set back the thermostat at night, seal the biggest gaps you can find with caulk.
7. For the bigger question, get a real audit. Professional audits use blower-door tests and infrared cameras, deliver a prioritized report, and are often free through local utility companies.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me find where my home wastes energy and what to fix first.

Utility bills (last 6 months, totals and kWh/therms): [paste the numbers, NOT account numbers]
House: [e.g. "1970s colonial, 1800 sq ft, oil baseboard heat from the 90s, electric water heater, no programmable thermostat"]
What I have noticed: [e.g. "upstairs bedrooms are cold, basement is freezing, bills spike December to February"]

Give me:
1. A ranked list of where my energy is most likely going, with the DOE-type percentages where they apply.
2. Fixes ordered cheapest first: what to do, roughly what it involves, which ones are DIY.
3. What NOT to bother with for my house.

Rules:
- Do not paste or ask for account numbers, names, or addresses. Bills totals only.
- Flag anything you are estimating rather than calculating.

Review the list before spending money. Big-ticket items deserve a second opinion or a professional audit.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Replacing windows first. The DOE notes a typical home loses over a quarter of its heat through windows, but air sealing and insulation usually pay back faster for less money.
- Trusting AI savings figures. If the AI quotes dollar savings, ask what it is based on; generic percentages rarely match a specific house.
- Pasting full bills with account numbers into a chatbot. Totals and usage only. Account numbers never belong in a prompt.

## Source

https://www.aisetupsthatwork.com/setups/cut-home-energy-use-with-ai/ (AI Setups That Work)
