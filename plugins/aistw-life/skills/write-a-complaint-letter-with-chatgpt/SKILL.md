---
name: write-a-complaint-letter-with-chatgpt
description: "How to Use ChatGPT to Write a Complaint Letter That Gets a Response. I paste the facts. Dates, order numbers, what went wrong, and what I want, and ask ChatGPT for a short, clear, polite letter I can send by email or certified mail. I read every line before it goes out; nothing sends automatically. Use when the user asks for help with this job."
---

# How to Use ChatGPT to Write a Complaint Letter That Gets a Response

## When to use

Anyone who has been ghosted after a bad hotel stay, warranty denial, or double charge and needs words that sound like a human who will escalate, not a rage tweet.

## Steps

1. Write bullet facts only: what happened, when, what you already tried, what resolution you want (refund, repair, credit).
2. Paste bullets and ask for a one-page letter with subject line, numbered timeline, and a clear deadline for response.
3. Forbid insults, crime accusations you cannot prove, and fake “my lawyer says” lines unless a lawyer actually said it.
4. Ask for a shorter version if the company uses a web form with character limits.
5. You send via your email client or mail service. No agent send permissions.
6. If they reply, start a new thread with the full history pasted; do not let the model auto-respond.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You help me write a complaint letter. Do not send email, file disputes, or contact the company for me.

Company: [name]
Channel I will use: [email / web form / certified mail]
My goal: [refund / replacement / fee reversal / apology + fix]

Facts (only what I provide: do not invent):
[paste timeline bullets, order numbers, amounts, prior contact attempts]

Tone: [firm and professional / calm but persistent]
Desired response deadline: [e.g. 14 business days]

Rules:
- One page or less; numbered timeline; list attachments I actually have.
- State the specific remedy I want and a reasonable deadline.
- No insults, no unverified legal threats, no fabricated regulations.
- Include subject line and sign-off with my name: I will edit before sending.
- Output draft only: I approve before anything is sent or spent.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Models add fake statute numbers or “legal team” language. Delete unless your lawyer provided it.
- Uploading IDs or medical details to cloud chat can be a privacy problem. Describe facts in text when you can.
- A strong letter does not guarantee a yes. Keep records and escalate through official channels yourself.

## Source

https://www.aisetupsthatwork.com/setups/write-a-complaint-letter-with-chatgpt/ (AI Setups That Work)
