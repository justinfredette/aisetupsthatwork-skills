---
name: claim-flight-delay-compensation-with-chatgpt
description: "Claim Flight Delay Compensation with ChatGPT. Here's how I'd set this up in ChatGPT or Claude (not run by us yet). I'd paste my booking and what went wrong, have the chat check whether EU rules or the US refund rule apply, then file the claim it drafts on the airline's own form myself. Use when the user asks for help with this job."
---

# Claim Flight Delay Compensation with ChatGPT

## When to use

For anyone whose flight was delayed, cancelled, or rescheduled and who isn't sure whether to ask for compensation, a refund, or both.

## Steps

1. Collect the booking email, the delay or cancellation notice, and your receipts.
2. Paste the facts into the chat with the prompt below. Leave out passport and payment numbers.
3. Read which rules it thinks apply and why. EU rules cover flights within the EU, flights leaving the EU, and flights into the EU on an EU airline.
4. Under EU rules, arriving 3 or more hours late earns a fixed amount by distance unless the airline can show extraordinary circumstances such as bad weather. Under the US rule, you get a full refund if the flight was cancelled or significantly changed and you turn down the alternative. A significant change means 3 or more hours for a domestic trip or 6 or more for an international one.
5. Have the chat draft the claim text for the airline's own claim form, plus a list of receipts to attach.
6. File it yourself with the airline that operated the flight. In the EU, if the airline doesn't reply within 2 months, you can complain to the national authority.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me claim compensation or a refund for a disrupted flight. Don't file anything or contact the airline for me.

Booking: [airline that sold the ticket, airline that operated each flight, flight numbers, route, scheduled departure and arrival]
What happened: [delay, cancellation, or schedule change; actual arrival time; when I was told]
What I spent because of it: [meals, hotel, transport, with amounts]
Did I accept a rebooking, voucher, or refund? [yes/no, which]

1. Tell me which rules may apply: EU air passenger rights (Regulation 261/2004), the US DOT refund rule, both, or neither. Explain why in two lines each.
2. If EU rules may apply, estimate the flight distance, show your estimate, and say which compensation band it falls in.
3. If the US refund rule may apply, say whether my facts fit a cancellation or a significant change.
4. Draft the claim text for the airline's own claim form, under 150 words, with dates, flight numbers, and what I'm asking for.
5. List the receipts and documents to attach.

Rules: Use web search to check the official EU or DOT page before you state any amount or threshold, and link it. Don't invent facts about my flight. If extraordinary circumstances might apply, say so.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Extraordinary circumstances such as weather or air traffic control decisions can rule out EU compensation, and the airline has to prove them.
- The US rule covers refunds, and only if you turn down the rebooking or voucher the airline offers.
- The chat's distance estimate can be off. Check the band against the official EU table before you file.

## Source

https://www.aisetupsthatwork.com/setups/claim-flight-delay-compensation-with-chatgpt/ (AI Setups That Work)
