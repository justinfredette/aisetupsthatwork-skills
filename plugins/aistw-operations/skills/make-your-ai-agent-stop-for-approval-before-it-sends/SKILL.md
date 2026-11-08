---
name: make-your-ai-agent-stop-for-approval-before-it-sends
description: "Make your AI agent stop for approval. Tell the agent, in its standing instructions, to finish every outgoing action as a draft and show it to you with a one-line summary, then wait. Keep the tool's."
---

# Make your AI agent stop for approval

## When to use

Anyone whose AI assistant can send, book or post through connected apps, and who wants a human check on everything that leaves the business.

## Steps

1. Find where your agent keeps standing instructions: project instructions, custom instructions or the agent's settings.
2. Paste the approval rule from the prompt below. It turns every outgoing action into a draft plus a short summary of who, what and when.
3. Keep the tool's own approval setting on as a second lock. Anthropic says its Google Workspace connectors ask for approval before sending, replying or forwarding by default.
4. Test it: ask the agent to email yourself a fake quote. It should stop and show the draft, not send.
5. Approve with a clear word, such as SEND, so a vague reply like ok does not count as approval.
6. If it ever sends without asking, disconnect that app, tighten the instruction and test again.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Add this rule to your standing instructions and follow it every time:

Before anything leaves my business (email, message, booking, calendar invite, post, payment, refund):
1. Prepare it as a draft only.
2. Show me: who it goes to, the full text, and when it would go out.
3. Add one line: what could go wrong if this is wrong.
4. Wait. Only proceed when I reply with the word SEND for that item.
5. If I reply with anything else, treat it as an edit or a no.

If you are unsure whether something counts as leaving the business, treat it as if it does.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The instruction lives in one chat, so a new chat forgets it. Put it in project or custom instructions.
- Turning off the tool's own approval setting because the agent asks anyway. Keep both.
- Approving from your phone without reading the recipient line.

## Source

https://www.aisetupsthatwork.com/setups/make-your-ai-agent-stop-for-approval-before-it-sends/ (AI Setups That Work)
