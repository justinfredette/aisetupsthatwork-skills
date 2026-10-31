---
name: summarize-long-email-thread-decision
description: "Turn a Long Email Thread Into a Decision Summary. Copy the email thread into ChatGPT or Claude and ask for three things: what was decided, what is still open, and who owns what. You get the thread's point in seconds instead of reading every reply. Use when the user asks for help with this job."
---

# Turn a Long Email Thread Into a Decision Summary

## When to use

An office worker who gets looped into long reply-all threads and needs the outcome fast

## Steps

1. Open the email thread in your mail app. Select all the text in the conversation and copy it.
2. If the thread is very long, trim it: delete signature blocks, quoted disclaimers, and duplicate replies. Keep the actual messages in order.
3. Open ChatGPT or Claude and paste the thread, then paste the prompt below above it.
4. Read the summary. Focus on the 'Still open' and 'Owners' sections, since those tell you what needs action.
5. Verify the summary against the thread before you act on it. AI can mix up who said what when many people share a first name.
6. Do not paste threads with confidential company data, customer details, or legal matters into a free chatbot. Use your company's approved AI tool for those.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Read this email thread and give me a short summary in exactly three sections. 1. DECIDED: what was decided, one bullet per decision. 2. STILL OPEN: questions or disagreements that are not resolved. 3. OWNERS: who agreed to do what, and by when if mentioned. Keep it under 200 words. Here is the thread: [PASTE THREAD]
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI invents a decision nobody made. Always verify every claim in the summary against the actual thread before forwarding it.
- The thread is too long to paste. Summarize each message separately first, then paste those summaries and ask for one combined recap.
- Names get mixed up. When two people have the same first name or reply inline, tell the AI to quote the speaker with each bullet.
- Confidential threads. Free chatbots may use your input for training. Strip or redact sensitive details, or use your company's approved AI instead.

## Source

https://www.aisetupsthatwork.com/setups/summarize-long-email-thread-decision/ (AI Setups That Work)
