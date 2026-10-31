---
name: file-a-warranty-claim-with-chatgpt
description: "File a Warranty Claim with ChatGPT. Here's how I'd set this up in ChatGPT or Claude (not run by us yet). When something breaks, I'd upload the warranty, my receipt, and photos of the problem, and have the chat check whether the issue looks covered and how the claim process works. Then I'd send the claim myself and keep copies. Use when the user asks for help with this job."
---

# File a Warranty Claim with ChatGPT

## When to use

For anyone whose appliance, gadget, or furniture broke while it might still be under warranty, and who doesn't want to dig through the fine print to find out.

## Steps

1. Find the written warranty. If you lost it, search the manufacturer's website for the product's warranty page.
2. Upload the warranty, the receipt, and photos of the problem with the prompt below. Black out card numbers on the receipt.
3. Read what the chat finds: how long coverage lasts, what's covered, what's excluded, and what you have to do to make a claim.
4. Check any exclusion it flags against the warranty text yourself. If a part or repair isn't listed as covered, the FTC says to assume it isn't.
5. Start with the seller. If the seller won't fix it, send the claim to the manufacturer at the address on the warranty. Certified mail with a return receipt gives you proof it arrived.
6. Keep copies of everything you send and note the date of every call.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me file a warranty claim. Don't contact anyone for me.

Product: [brand, model]
Bought on: [date] from [store]
What's wrong: [describe the problem and when it started]
Attached: the warranty, my receipt (card number blacked out), and photos of the problem.

1. Tell me how long the warranty lasts and whether my purchase date is inside it.
2. Quote the parts of the warranty that cover this problem, and any exclusions that might apply.
3. List what the warranty says I have to do: who to contact, proof needed, shipping or labor costs, registration.
4. Draft a short, factual claim message with the product, purchase date, problem, and what I'm asking for (repair, replacement, or refund, per the warranty).

Rules: Only use what the warranty actually says. If it doesn't cover something, say so plainly. Don't invent terms or deadlines.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Warranties exclude a lot, like misuse or wear and tear, and the chat can't force a company to honor a claim.
- The chat can misread fine print or miss a registration requirement. Check the sections it quotes against the warranty yourself.
- An extended warranty or service contract is a separate contract with its own terms. Upload that contract too if you have one.

## Source

https://www.aisetupsthatwork.com/setups/file-a-warranty-claim-with-chatgpt/ (AI Setups That Work)
