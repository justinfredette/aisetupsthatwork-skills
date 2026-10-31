---
name: turn-messy-draft-into-polite-work-email
description: "Turn a messy draft into a clear, polite work email. Paste your rough or frustrated draft, name the recipient and tone, and ask ChatGPT or Claude for a concise rewrite under a word cap. Keeping your facts only, with no new deadlines or promises. Review for passive-aggressive phrasing, then paste into mail yourself; never grant send access for this job. Use when the user asks for help with this job."
---

# Turn a messy draft into a clear, polite work email

## When to use

Anyone who types a vent in Notes first, then stalls before sending a professional reply to a manager, client, or teammate.

## Steps

1. Paste your rough draft and state who receives it (role and relationship: manager, client, peer).
2. Ask for a polite, concise rewrite under a word cap (for example 120 words) in plain language.
3. Require in the prompt: do not invent facts, deadlines, or promises. Only rephrase what you provided.
4. Read the draft aloud; fix anything that sounds stiff, fake-urgent, or passive-aggressive.
5. Optional second pass: ask it to flag phrases that could read as snark or “as per my last email” energy.
6. Paste into Gmail, Outlook, or Slack yourself. Keep send and post permissions off in any connected agent.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are helping me rewrite a work message. Do not send email or post to Slack.

My role: [your role]
Recipient: [name or role: e.g. client PM, my manager]
Desired tone: [polite and direct / warm but firm / apologetic but clear]
Max length: [120] words

Rough draft:
[paste messy draft]

Rules:
- Keep my meaning and facts exactly; do not add new information, deadlines, or promises.
- Do not invent attachments, meetings, or approvals I did not mention.
- Use short paragraphs; no corporate filler or fake urgency.
- Show the rewrite only: do not send.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Models pad with fake urgency or commitments you never made. Delete anything not in your draft.
- Over-formal “as per my last email” phrasing can sound worse than your original. Ask for plain language.
- Pasting confidential names or deal terms into cloud chat may violate policy. Redact first.
- Never connect send or “act as me in Gmail” for this job; paste the final text yourself.

## Source

https://www.aisetupsthatwork.com/setups/turn-messy-draft-into-polite-work-email/ (AI Setups That Work)
