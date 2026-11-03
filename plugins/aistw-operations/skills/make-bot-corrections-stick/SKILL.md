---
name: make-bot-corrections-stick
description: "Make bot corrections stick. A correction in chat fixes that chat only. Each time you correct a bot, add one line to its written instructions covering the job, the rule and what done looks like. Every month, slim the instructions: keep core rules always loaded and move situational steps into separate saved procedures. Use when the user asks for help with this job."
---

# Make bot corrections stick

## When to use

Owners whose bot repeats a mistake after being corrected, or whose instructions have grown so long the bot ignores parts.

## Steps

1. When you correct a bot, ask it to write the correction as one instruction line using the prompt below.
2. Approve the line and add it to the bot's written instructions, not just the chat.
3. Monthly, back up the full instructions first.
4. Sort lines into core rules (always loaded) and situational steps (move into a saved procedure the bot opens when needed).
5. Test the slimmer version on 3 past tasks before switching.
6. Grok Bot group owners described both fixes: corrections that live only in chat come back, and long always-loaded instructions cost usage.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I just corrected you. Turn the correction into one line for your written instructions.

The mistake: [WHAT WENT WRONG]
The correction: [WHAT I SAID]

Write one line with: the job it applies to, the rule, and what done looks like. Under 30 words. Do not add it yourself; show it to me to approve.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Correcting in chat and assuming it is fixed.
- Instructions so long the bot ignores the end.
- Slimming without a backup.

## Source

https://www.aisetupsthatwork.com/setups/make-bot-corrections-stick/ (AI Setups That Work)
