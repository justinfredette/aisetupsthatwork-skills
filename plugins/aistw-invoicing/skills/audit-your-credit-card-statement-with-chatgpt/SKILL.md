---
name: audit-your-credit-card-statement-with-chatgpt
description: "Audit Your Credit Card Statement with ChatGPT. Here's how I'd set this up in ChatGPT or Claude (not run by us yet). I'd download my last few statements, black out the card number, upload them, and have the chat flag duplicate charges, amounts I don't recognize, and refunds that never posted. Then I'd check each flag against my receipts and dispute only the real errors myself. Use when the user asks for help with this job."
---

# Audit Your Credit Card Statement with ChatGPT

## When to use

For anyone who skims their card statement, pays it, and moves on, and wants a careful second look without reading every line.

## Steps

1. Download the last 2 or 3 monthly statements as PDFs from your card issuer.
2. Black out the full card number and your address. Upload the statements with the prompt below.
3. Read the flags: the same amount from the same merchant close together, merchants you don't recognize, and returns that never showed up as a credit.
4. Check each flag against your receipts or order emails. An unfamiliar name can be a company's billing name, so look it up before you dispute.
5. Call the issuer about any charge that is still wrong. Then send a written billing error notice. Under the Fair Credit Billing Act, it has to reach the issuer within 60 days after the first statement with the error was sent to you.
6. Ask the chat to draft that notice from the confirmed errors only, and mail it to the billing inquiries address on your statement, not the payment address.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me audit my credit card statements for errors. Don't contact anyone for me.

Attached: my last few statements. I've blacked out the card number.

1. List every charge with date, merchant, and amount.
2. Flag possible duplicates (same merchant and amount within a few days), merchants I might not recognize, and any return or refund I mention below that doesn't appear as a credit.
3. For each flag, say why you flagged it and what I should check (receipt, order email, merchant's billing name).
4. Once I confirm which flags are real errors, draft a short billing error letter with my name, the charge date, the amount, and why it's wrong. Leave placeholders for my account number and address.

Returns I'm waiting on: [merchant, amount, date returned]

Rules: Don't invent charges or merchant details. If a line is hard to read, say "can't read". Only put confirmed errors in the letter.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The chat can't see your receipts or your issuer's records, so a flag is only a lead until you confirm it.
- A merchant name on a statement can be a parent company's billing name, which makes a real charge look unfamiliar.
- Some statements are scanned images, and small print can be misread. Check every flagged amount against the statement yourself.

## Source

https://www.aisetupsthatwork.com/setups/audit-your-credit-card-statement-with-chatgpt/ (AI Setups That Work)
