---
name: check-if-chatgpt-recommends-your-business
description: "Check if ChatGPT recommends your business. Ask the AI assistants the exact questions a customer would, such as best roofer near Rutland, and write down who gets named and which pages they cite. Then."
---

# Check if ChatGPT recommends your business

## When to use

Local and small businesses wondering whether AI assistants mention them when customers ask for a recommendation.

## Steps

1. Write 5 questions a real customer would ask, with your town, like who is the best plumber in Rutland VT.
2. Ask each assistant every question in a fresh chat with search turned on. Record who is named, in what order, and the pages cited.
3. Check your site allows the search crawlers you want. OpenAI says OAI-SearchBot is used for ChatGPT search results and is set separately from GPTBot, its training crawler.
4. Compare your pages with the pages that got cited: do they state services, area, hours and prices plainly?
5. Make your business details clear and consistent. Google documents LocalBusiness structured data with name and address required.
6. Re-run the same 5 questions monthly and compare.

## What to ask the user for

- NAME
- SERVICE
- TOWN, STATE
- URL
- NAMES

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I want to see whether AI assistants recommend my business. Help me plan the check.

Business: [NAME], [SERVICE], [TOWN, STATE]
Website: [URL]
Competitors I know: [NAMES]

Give me:
1. Five questions a real customer would type, using my town.
2. A simple table to record, per assistant and question: who was named, in what order, and which pages were cited.
3. After I paste my results: the three most likely reasons I was missing, based only on what I pasted, and one fix for each.

Do not guess results you have not seen.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Asking with your business name in the question, which proves nothing.
- Blocking a search crawler in robots.txt by accident.
- Changing many things at once, so you cannot tell what helped.

## Source

https://www.aisetupsthatwork.com/setups/check-if-chatgpt-recommends-your-business/ (AI Setups That Work)
