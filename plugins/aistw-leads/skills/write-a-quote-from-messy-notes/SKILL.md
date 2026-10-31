---
name: write-a-quote-from-messy-notes
description: "Turn messy job notes into a clean quote. Paste your rough notes into a chat AI along with your prices and terms. It hands back a clean, itemized quote you check and send. Use when the user asks for help with this job."
---

# Turn messy job notes into a clean quote

## When to use

Tradespeople, cleaners, landscapers, and freelancers who price jobs from scribbled notes and phone calls.

## Steps

1. After the site visit or call, dump everything into one note: what the customer asked for, measurements, materials, timeline.
2. Put your price next to each line item, or give the AI your hourly rate and estimated hours so it can do the math.
3. Paste the notes plus the prompt below into ChatGPT or Claude.
4. Read the draft line by line. Fix any number the AI guessed at instead of using yours.
5. Add your business name, contact details, and a quote expiry date. Fourteen to thirty days is standard.
6. Save it as a PDF and send. Keep your original notes in case the scope changes later.
7. For a contracting bid, ask the AI to lay the notes out as a bid sheet: scope of work in plain tasks, then cost lines grouped as labor, materials, subcontractors, and equipment, ending with one total.
8. Add the fields a bid needs: bid number, bid date, expiry date, payment schedule, and how change orders get priced. Tell the AI to write 'TBD - confirm' for any price it does not know, and show you the draft first.
9. For a client proposal, open by restating their problem in their own words, then your plan in concrete steps. Keep it to 150 to 300 words so it reads in under two minutes.
10. End the proposal with one clear next step, like 'Reply YES and I will send the contract.' Ask the AI for the draft, then read it once and cut anything that sounds generic.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Turn my rough job notes into a clean, professional quote.

My business: [BUSINESS NAME]
Customer: [CUSTOMER NAME]
My hourly rate: [RATE] / My per-item prices: [LIST]

Job notes:
[PASTE YOUR NOTES HERE]

Rules:
- List every item as its own line with a short description, quantity, unit price, and line total.
- Use ONLY the prices I gave you. If a price is missing, write "TBD: confirm" instead of guessing.
- Add a subtotal, any tax, and a grand total.
- Include these terms: [DEPOSIT TERMS], payment due [WHEN], quote valid until [DATE].
- Keep the tone plain and professional. No sales fluff.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI invents prices for items you did not price. The "TBD: confirm" rule in the prompt prevents this.
- Scope creep after the quote goes out. Put a line in your terms about how changes get priced.
- Sending the quote as plain email text instead of a PDF. PDF keeps the record clean and uneditable.
- Letting the AI blur labor and materials into one lump sum. A bid with no breakdown looks like a guess.
- Starting the proposal with your bio. Clients hire the fix for their problem, not the story of your business.

## Source

https://www.aisetupsthatwork.com/setups/write-a-quote-from-messy-notes/ (AI Setups That Work)
