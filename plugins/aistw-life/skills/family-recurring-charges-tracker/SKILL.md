---
name: family-recurring-charges-tracker
description: "Family recurring charges tracker. Make one shared list of every recurring charge in the family: what it is, who uses it, the amount, the renewal date and how to cancel. Review it on a set day each month. Stopping a bank payment is separate from cancelling the service: cancel with the company, and tell your bank if the company debits your account. Use when the user asks for help with this job."
---

# Family recurring charges tracker

## When to use

Families where several people have subscriptions, apps and renewals spread across cards and accounts. For inbox hunting see the inbox setup, and for software spend see the software spend setup. This is not financial advice. Do not paste card or account numbers into a chatbot.

## Steps

1. Open the last two or three statements. For each recurring charge, copy the name, the amount and the date. Leave out card and account numbers.
2. Ask the chat for a table with these columns: charge, who uses it, amount, how often, next renewal date, paid from (card or bank account), how to cancel.
3. Fill the gaps by hand. The chat cannot see your accounts, so it cannot know who uses a charge or how to cancel it.
4. Pick one review day each month. Ask the chat to list what renews in the next 30 days and what nobody in the family still uses.
5. Work out who you authorized. If you told your bank to make the payment to the company, HelpWithMyBank.gov says you revoke it with the bank: notify the bank at least three business days before the scheduled date. Oral notice works, but the bank may ask you to confirm in writing, and an oral request stops being effective after 14 days if you do not.
6. If you authorized the company to take the payment from your account, the CFPB says to call the company, take back your permission, and follow up in writing. HelpWithMyBank.gov adds to keep a copy of the notice or a cancellation number and to tell your bank. Your bank may suggest a stop payment order too, and the CFPB says banks generally charge fees for those.
7. Cancel the service itself as well. The CFPB says cancelling an automatic payment does not cancel what you owe: cancel a contract with the company too, and a loan still has to be paid another way.
8. Watch the next statement. The CFPB says payments a company starts after you revoked permission would be errors, and you can ask your bank for a refund. HelpWithMyBank.gov says you can dispute the charges with your bank.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me build a family list of recurring charges. This is not financial advice.

I will paste only the charge name, amount and date from statements. I will not paste card or account numbers. If I paste any, tell me to remove them.

My charges: [name, amount, date seen, who uses it]
Today's date: [DATE]

1. Make a table: charge, who uses it, amount, how often, next renewal date, paid from, how to cancel (write "ask me" if you do not know).
2. List what renews in the next 30 days.
3. List charges nobody in the family is marked as using.
4. For any charge I want to stop, draft a short note to the company withdrawing permission for automatic payments.

Show me the table first. Do not guess renewal dates or cancel steps. Ask me. I send every note myself.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Stopping the payment but not the service. The CFPB says cancelling an automatic payment does not cancel what you owe, so cancel the contract with the company too.
- Missing the three business day cutoff. If you authorized your bank to send the payment, HelpWithMyBank.gov says to notify it at least three business days before the scheduled transfer.
- Not keeping proof. Both sources say to keep track of your requests. HelpWithMyBank.gov says to keep a copy of your written notice or a cancellation number, and a written stop payment order often expires after six months.

## Source

https://www.aisetupsthatwork.com/setups/family-recurring-charges-tracker/ (AI Setups That Work)
