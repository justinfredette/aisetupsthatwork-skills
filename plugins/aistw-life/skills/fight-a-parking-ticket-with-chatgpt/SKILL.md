---
name: fight-a-parking-ticket-with-chatgpt
description: "Fight a Parking Ticket with ChatGPT. Here's how I'd set this up in ChatGPT or Claude (not run by us yet). I'd photograph the ticket, the signs, and where my car was parked, upload the photos, and have the chat find my city's official dispute page and check the ticket for errors. Then I'd file the dispute myself before the deadline. Use when the user asks for help with this job."
---

# Fight a Parking Ticket with ChatGPT

## When to use

For anyone who got a parking ticket they think is wrong, like a missing or confusing sign, a paid meter, or a ticket with the wrong details on it.

## Steps

1. Before you leave the spot, take photos of the signs, the meter or curb markings, and where your car sits. Photograph both sides of the ticket.
2. Find the dispute deadline printed on the ticket. Rules and deadlines vary by city. In New York City, for example, you have 30 days from the ticket date to request a hearing and avoid late penalties.
3. Upload the photos with the prompt below. It uses web search to find your city's official dispute page and the defenses that city accepts.
4. Read what it finds on the ticket itself: a wrong plate, a wrong location, or a missing required detail can matter in some cities.
5. Have it draft a short statement that sticks to facts you can prove with your photos and receipts.
6. File the dispute yourself on the city's own site, app, or by mail, and keep the confirmation.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me dispute a parking ticket. Don't file anything for me.

City: [city, state]
Ticket date and number: [date, number]
What happened: [where I parked, what the signs said, why I think the ticket is wrong]
Attached: photos of the ticket, the signs, and my car's position.

1. Use web search to find my city's official page for disputing a parking ticket. Link it and tell me the deadline and the ways to file (online, app, mail, in person).
2. Read the ticket photo and list what it says: plate, location, violation, time. Flag anything that doesn't match my photos or my account of what happened.
3. Tell me whether the official page lists defenses it won't accept, and whether my reason fits any of those.
4. Draft a dispute statement under 150 words that sticks to facts my photos or receipts can prove.

Rules: Only use the city's official site for rules and deadlines. If you can't find it, say so. Don't invent rules, sign wording, or evidence.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Each city sets its own rules, deadlines, and accepted defenses, so the chat can only help once it finds your city's official page.
- The chat can misread a blurry ticket or sign photo. Check every detail it quotes against the photo yourself.
- A well-written statement doesn't change the facts. If the signs were clear and you were in the wrong, the ticket will likely stand.

## Source

https://www.aisetupsthatwork.com/setups/fight-a-parking-ticket-with-chatgpt/ (AI Setups That Work)
