---
name: ai-promise-tracker-for-your-business
description: "AI promise tracker for your business. Use a connected email account or pasted meeting notes, and ask the assistant for a weekly list of open promises with dates. ChatGPT's help center says scheduled tasks can run on a schedule and monitor Gmail. The list is for you only. Use when the user asks for help with this job."
---

# AI promise tracker for your business

## When to use

Owners and managers who lose track of 'I'll send that Thursday' across email and calls. Skip anything covered by a client confidentiality agreement unless you are allowed to share it with an AI service.

## Steps

1. Pick the window, such as the last 7 days of sent mail plus this week's meeting notes.
2. Connect Gmail to the assistant, or paste the week's notes. Claude's help center says Gmail search and read are supported. For notes, a connector is not required.
3. Run the prompt below. Check that each promise names who owes it and the date, if one was given.
4. Fix the list by hand. Cross out what is done and add anything it missed.
5. To repeat it, ask ChatGPT for a scheduled task. OpenAI's help says tasks can run once or on a schedule, and you choose Push or Email notifications. Scheduled tasks in Claude: Not stated in sources.
6. Send any nudge yourself. The assistant only writes the list.
7. After a month, count how many promises were missed before and after. Keep the count if it helps.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Find open promises in my email and notes from [DATE RANGE]. Read only. Do not send, reply or change anything.

For each promise, give one line:
- Who promised: me or [PERSON]
- What was promised
- Date promised and due date, or 'no date given'
- Where it came from (thread subject or meeting)
- Status: open, done, or unclear

Rules:
- List only promises that are in the text. Do not invent due dates.
- Put promises with dates in the next 7 days first.
- At the end, list the 3 I should chase first, with one sentence on why. Do not write messages to anyone.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The assistant can mistake a casual 'maybe' for a promise. Read the source line.
- Meeting notes that name no owner give a list with no owner. Add names when you take notes.
- Letting a nudge go out without reading it. This setup writes no messages.

## Source

https://www.aisetupsthatwork.com/setups/ai-promise-tracker-for-your-business/ (AI Setups That Work)
