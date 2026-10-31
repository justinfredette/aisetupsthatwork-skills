---
name: negotiate-a-medical-bill-with-chatgpt
description: "Negotiate a Medical Bill with ChatGPT. Here's how I'd set this up in ChatGPT or Claude (not run by us yet). I'd ask the hospital for an itemized bill, upload it with my ID and account numbers blacked out, have the chat flag charges to question and find the hospital's posted prices, then make the billing call myself with a short script. Use when the user asks for help with this job."
---

# Negotiate a Medical Bill with ChatGPT

## When to use

For anyone holding a hospital or clinic bill that looks too high, whether you're uninsured or owe a balance after insurance paid its part.

## Steps

1. Call the billing office and ask for an itemized bill with billing codes and dates of service.
2. Black out your Social Security number, member ID, and account numbers. Upload the bill and your Explanation of Benefits with the prompt below.
3. Read the flags: lines that look duplicated, services you don't remember, and charges that don't match your Explanation of Benefits. Mark the ones you can confirm.
4. Have the chat use web search to find the hospital's posted prices and its financial assistance policy. US hospitals must post prices online, and tax-exempt hospitals must publish a written financial assistance policy.
5. Ask for a short call script and a written request built only from the flags you confirmed.
6. Make the call yourself. Write down the date, the person's name, and what they agreed to, and ask for any reduction in writing.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me review a medical bill before I call the billing office. Don't contact anyone for me.

Attached: my itemized bill and, if I have one, my insurer's Explanation of Benefits. I've blacked out my ID and account numbers.

1. List every line with date, code, description, and charge.
2. Flag lines that look duplicated, that don't match the Explanation of Benefits, or that I should ask about. Say why for each one. Mark anything you can't read as "can't read".
3. Use web search to find this hospital's posted price list and its financial assistance policy. Link them. If you can't find them, say so.
4. Write a call script under 150 words: who I am, the account, the specific lines I'm disputing, and what I'm asking for.
5. Write a short written request I can send that covers the disputed lines and asks whether I qualify for financial assistance.

Rules: Don't invent prices, codes, or laws. If a posted price can't be matched to a line, say so. Only use lines I confirm.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Posted prices may not match the rate your insurer negotiated, so a gap alone doesn't prove an error.
- Billing codes are easy to misread. Check each flagged line against the bill yourself before you dispute it.
- A summary bill has no codes. Get the itemized version first.

## Source

https://www.aisetupsthatwork.com/setups/negotiate-a-medical-bill-with-chatgpt/ (AI Setups That Work)
