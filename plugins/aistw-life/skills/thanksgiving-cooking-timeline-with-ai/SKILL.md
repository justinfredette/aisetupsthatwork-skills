---
name: thanksgiving-cooking-timeline-with-ai
description: "Thanksgiving Cooking Timeline with AI: Free Prompt for a One-Oven Kitchen. Thanksgiving is Thursday, November 26 this year, and the hard part is timing. The turkey owns the oven all afternoon, three casseroles want 375°F at 4:30, and nobody remembered the bird has to start thawing days before. You can work backward from dinner by hand, but it's tedious, and one slip pushes everything late. Use when the user asks for help with this job."
---

# Thanksgiving Cooking Timeline with AI: Free Prompt for a One-Oven Kitchen

## When to use

Anyone hosting Thanksgiving dinner with one oven, several dishes, and a fixed sit-down time.

## Steps

1. Planner bot: you give it your menu, your oven and burners, how many people, and when you want to eat. It works backward from dinner and hands you one timeline with clock times, plus a list of what to make the day before.
2. Thaw-and-shop bot (optional): the same chat, second message. It tells you the day to move the turkey to the fridge, based on its weight, and turns the menu into a shopping list grouped by store section.
3. Reminder (optional): put the thaw day and the "turkey in" time on your phone. If you'd rather have AI ping you, see the scheduled reminders setup.
4. Paste the starter prompt into ChatGPT, Claude, or Gemini and fill in the bracketed fields.
5. Want the shopping list too? Send this next: "Now turn the menu into a shopping list for [NUMBER] people, grouped by store section, and mark anything you probably already have."

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I'm cooking Thanksgiving dinner and I want every dish hot at the same time.

Menu: [YOUR DISHES, e.g. turkey, stuffing, mashed potatoes, green bean casserole, rolls, pumpkin pie]
Turkey: [WEIGHT IN POUNDS], [FROZEN OR FRESH], [STUFFED OR UNSTUFFED]
Kitchen: [e.g. one oven, four burners, a slow cooker]
People: [NUMBER]
We eat at: [TIME]

1. Work backward from the time we eat. Give me one timeline, from the first prep job to sitting down: clock time, dish, what to do, and whether it uses the oven, a burner or the counter.
2. Plan around my oven. Never schedule two oven dishes at different temperatures at the same time. Use the turkey's rest time for side dishes that need the oven.
3. Build in at least 20 minutes of rest for the turkey before carving and a 15-minute buffer before we sit down.
4. List everything I can make the day before.
5. If the turkey is frozen, tell me the day to move it to the fridge to thaw, using about 24 hours per 4 to 5 pounds.
6. Remind me to check the turkey and any stuffing with a food thermometer for 165°F. Don't call it done by clock time alone.
If anything is missing, ask me up to 3 short questions before you start.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI guesses roast and bake times. It doesn't know your oven runs hot or that your bird is bigger than the label says. Treat the timeline as a plan to adjust, check the turkey with a thermometer, and if the bird runs late, push the casseroles back rather than serving it early.

## Source

https://www.aisetupsthatwork.com/setups/thanksgiving-cooking-timeline-with-ai/ (AI Setups That Work)
