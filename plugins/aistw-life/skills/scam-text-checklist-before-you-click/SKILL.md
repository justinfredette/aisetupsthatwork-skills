---
name: scam-text-checklist-before-you-click
description: "Scam text checklist before you click. The FTC says not to click links in an unexpected text that asks for personal or financial information, because legitimate companies will not ask for account details by text. If it might be real, contact the company with a phone number or website you already know. Forward scam texts to 7726. Use when the user asks for help with this job."
---

# Scam text checklist before you click

## When to use

Anyone who gets texts that claim to be from a bank, a delivery service or a store and is not sure which are real. This is not security advice for a hacked account. Do not paste your passwords, codes or account numbers into a chatbot.

## Steps

1. Do not tap the link, and do not call the number in the text. Our suggestion: do not reply either. Copy only the wording of the text into the chat, and leave the link out.
2. Ask the chat which patterns from the FTC's list the text matches: a prize, gift card or coupon, a low interest credit card, help with student loans, suspicious activity on your account, a problem with your payment information, a fake invoice, or a package delivery notice.
3. Ask what the text wants from you. The FTC says scammers ask for personal or financial information, or push you to click a link that may lead to a spoofed website or install malware.
4. Ask yourself the FTC's question: do I have an account with this company or know this person? If not, it could be phishing. If yes, contact the company with a phone number or website you know is real, not the information in the text.
5. If it looks fake, report it. The FTC says to forward the text to 7726 (SPAM), use the report option in your messaging app, and report it at ReportFraud.ftc.gov. Then delete it.
6. If you already gave out your Social Security, credit card or bank account number, the FTC points you to IdentityTheft.gov for the steps. If you think you tapped a link that downloaded something harmful, update your security software and run a scan.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me check a text I got before I click anything. This is a safety check, not a guarantee.

I will paste only the wording of the text. I will not paste the link, passwords, codes or account numbers. If I paste any, tell me to remove them.

The text: [paste the words]
Who it says it is from: [company or person]
Do I have an account with them: [yes or no]

1. Which of these common scam patterns does it match, if any: prize, gift card or coupon, low interest card, student loan help, suspicious account activity, payment problem, fake invoice, package delivery notice?
2. What does it ask me to do or give?
3. Give me a safe way to check: contact the real company with a phone number or website I already have, not anything in the text.
4. If it looks fake, list how to report it: forward to 7726, report in my messaging app, ReportFraud.ftc.gov.

Show me the answer first. Do not tell me a link is safe. You cannot check links.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Calling the number in the text. Use a number you already know instead.
- Asking the chat whether a link is safe. It cannot open or check links, so leave the link out.
- Thinking a real logo or a message that looks fine means it is real. The FTC notes phishing messages can look real at first glance.

## Source

https://www.aisetupsthatwork.com/setups/scam-text-checklist-before-you-click/ (AI Setups That Work)
