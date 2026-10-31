---
name: ai-meeting-notes-to-action-items
description: "Meeting notes to action items and follow-up email. Paste messy meeting notes or a transcript and get decisions, owners, due dates, and a follow-up email draft you send yourself, without the model inventing commitments that were not in the notes. Use when the user asks for help with this job."
---

# Meeting notes to action items and follow-up email

## When to use

People who leave calls with scattered bullets and need a consistent action-item table plus a ready-to-edit recap email.

## Steps

1. Redact client secrets or personal data you should not put in cloud chat.
2. Paste raw notes; say who was in the meeting only if that appears in the text.
3. Run the prompt; scan for TBD owners and dates. Fill those in yourself.
4. Edit the follow-up email for tone and accuracy.
5. Send from your mail client; do not grant the agent send access.
6. File the action table in your task tool or doc for the next standup.
7. Export two to four weeks of calendar events and ask the AI to run an agenda test table: one row per recurring meeting with columns for purpose (decision, status, other), agenda yes or no, essential attendees only, and could-this-be-async. Ask it to flag meetings that fail two or more checks. Show the output first and correct any meeting it miscategorized.
8. For flagged meetings, ask for a short decline-or-convert script: a polite decline asking for an agenda with the decision needed, or a proposal to move the update to a written thread. Try the 'no agenda, no attendance' rule for two weeks, then keep or reinstate each meeting based on whether anyone missed it.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I pasted meeting notes below. Extract structured output only. Do not invent attendees, decisions, or dates that are not supported by the text.

Meeting title / date (if stated): [optional]
Attendees (if stated): [optional]

---
[paste raw notes or transcript]
---

Deliver:
1) Decisions made (bullet list; tie each to a phrase from the notes).
2) Action items table: action | owner (or "TBD") | due date (or "TBD") | note line reference.
3) Open questions / parking lot (unresolved items).
4) A follow-up email draft (plain language, under [word cap] words) summarizing decisions and action items. To: [team / client / etc.]

Rules: If owner or due date is missing, mark TBD. Do not guess. Do not send email or create calendar events. Flag commitments I should verify before sending.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Models invent action owners or dates. Treat TBD rows as mandatory when notes are vague.
- Confidential deals belong in redacted notes, not full transcripts in shared chat accounts.
- Follow-up drafts can sound too formal. Edit voice before client send.
- Do not cut one-on-ones to fix overload; they carry coaching and trust. And give new recurring meetings an expiration or review date so the calendar does not refill by habit.

## Source

https://www.aisetupsthatwork.com/setups/ai-meeting-notes-to-action-items/ (AI Setups That Work)
