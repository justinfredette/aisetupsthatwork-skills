---
name: team-review-response-playbook
description: "A Review Response Playbook Your Whole Team Can Follow. Write a one-page voice guide: tone, length, sign-off, escalation list, banned phrases. Make it the system prompt for AI drafts so everyone who replies sounds like one business. Use when the user asks for help with this job."
---

# A Review Response Playbook Your Whole Team Can Follow

## When to use

Marketing managers, ops leads, and multi-location owners where two or more people answer reviews and the tone swings wildly.

## Steps

1. Collect 20 recent team replies. Mark the 5 best and 5 worst, and note why in one line each.
2. Define the voice in plain words: formal or casual, first names or not, emoji or not, typical length.
3. Write the forbidden list: phrases nobody uses ("valued customer," "we regret any inconvenience"), plus anything legal or compliance bans.
4. Set the escalation list: health claims, legal threats, employee names, press mentions. Those always go to a named person.
5. Turn the guide into the system prompt for AI drafts: voice, length, sign-off, escalation triggers, forbidden phrases.
6. Name one approver for tricky replies. AI drafts, the owner or manager approves anything flagged.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Write a one-page review response playbook for my team. Concrete and enforceable, not motivational fluff.

Business: [name, locations]
Team: [who replies: e.g. 2 store managers, 1 marketing lead]
Voice: [e.g. warm but professional, first names, no emoji]
Regulated or sensitive topics: [e.g. HIPAA, financial advice, alcohol service / none]

Here are 5 of our best replies and why they worked:
[paste]

Here are 5 of our worst and what went wrong:
[paste]

Return the playbook:
1. Voice rules (5 bullets max).
2. Length rules: positive reviews, negative reviews, mixed reviews.
3. Sign-off format and who signs what.
4. Forbidden phrases list.
5. Escalation list: what always goes to [named approver] before posting.
6. The AI draft instructions block: paste-ready system prompt encoding all of the above.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- A guide nobody reads is decoration. Walk the team through it once with real examples.
- Over-automation: full auto-reply without human review eventually posts something tone-deaf. Keep a human on negatives.
- Regulated industries (health, finance, legal) need compliance review of the forbidden list, not just marketing.
- Templates pasted verbatim across locations get spotted. The guide should demand personalization, not just allow it.

## Source

https://www.aisetupsthatwork.com/setups/team-review-response-playbook/ (AI Setups That Work)
