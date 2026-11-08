---
name: text-back-missed-callers-with-a-booking-link
description: "Text back missed callers with a booking link. Turn on your phone system's missed-call auto-reply and use AI to write a short text: your business name, sorry we missed you, a booking link and a reply."
---

# Text back missed callers with a booking link

## When to use

Salons, barbers, groomers and trades who cannot pick up mid-appointment and lose callers to the next business on the list.

## Steps

1. Check whether your phone system has a missed-call auto-reply. RingCentral, for example, documents a missed call auto-response with custom text.
2. Get your direct booking link, the page that opens the calendar, not your home page.
3. Write 3 versions of the text with the prompt below and pick one.
4. Turn on the auto-reply with that text and test it by calling from another phone.
5. Between appointments, read replies and answer anything the booking link does not cover.
6. After two weeks, compare missed calls to bookings from the link.

## What to ask the user for

- NAME
- LINK

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Write 3 versions of a text my phone system sends automatically when I miss a call.

Business name: [NAME]
Booking link: [LINK]
When I usually call back: [e.g. within 2 hours]

Rules: under 160 characters, friendly, says who we are, gives the booking link and says they can reply here. No promises about prices or availability.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.
- The missed-call text is the one message that goes out on its own. The user approves its exact wording once, when they set it up in their phone system. Claude only drafts the options and never turns it on.

## Common snags

- Texting landlines and business lines that cannot receive texts.
- A booking link that needs a login.
- Auto-replies going out at 2 AM to spam calls; pair it with call screening.
- These texts ran 144 to 156 characters. If your phone system adds "Reply STOP to opt out", each one goes past 160, so shorten the text or the link.

## Tested

Ran on Claude in a fresh chat, Nov 7, 2026: a made-up plumbing business got 3 missed-call texts of 156, 144 and 145 characters, each with the business name, the booking link and a reply option, and no price or open-slot promise. No phone system was set up and no text was sent.

The full receipt is on https://www.aisetupsthatwork.com/setups/text-back-missed-callers-with-a-booking-link/

## Source

https://www.aisetupsthatwork.com/setups/text-back-missed-callers-with-a-booking-link/ (AI Setups That Work)
