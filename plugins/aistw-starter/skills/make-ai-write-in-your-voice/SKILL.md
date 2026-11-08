---
name: make-ai-write-in-your-voice
description: "Make AI write in your voice. AI drafts sound generic because the bot has never seen how you write. Fix it in two parts. First, paste 10 to 20 pieces of your own writing and have the bot draft a."
---

# Make AI write in your voice

## When to use

Anyone whose AI drafts come back stiff and generic: owners writing customer emails, freelancers drafting proposals, anyone who rewrites every draft before sending.

## Steps

1. Gather 10 to 20 pieces of your own writing. Mix the kinds you write most: customer emails, posts, proposals. Use pieces you wrote yourself, not AI drafts.
2. Run the prompt below with your samples pasted in. It drafts a one-page voice profile: sentence habits, tone, words you lean on, words you never use, and the AI patterns to ban.
3. Edit the profile until it sounds like you. Cut anything vague ("friendly but professional" teaches nothing) and keep rules a bot can follow, like "sentences under 15 words" or "never start with I hope this finds you well". Then drop the quoted proof lines before saving, because they can push it past the 1,500-character limit on ChatGPT's Free and Go plans. If you want to keep them, ask for a version under 1,500 characters instead.
4. Test it in a new chat with only the profile in place: ask for a short draft on a real topic, then compare it against one of your samples. Add the misses to the profile as rules.
5. Save the profile where each bot reads standing instructions. ChatGPT: Settings, Personalization, Custom Instructions (OpenAI says up to 1,500 characters on Free and Go and up to 5,000 on Plus and other paid plans, so keep the profile tight). Claude: a skill, or account instructions under Settings, Your Claude. Grok Bot: paste it into your bot's standing instructions.
6. Re-read every draft before it goes anywhere. The profile gets you a closer first draft, not a finished one. Refresh it when your writing changes or drafts drift.

## What to ask the user for

- NUMBER
- PASTE SAMPLES

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Here are [NUMBER] pieces of my own writing: [PASTE SAMPLES]. Read them and draft a one-page voice profile I can save as standing instructions for an AI assistant. Use these sections: 1. Sentence habits (length, rhythm, fragments). 2. Tone (how I come across, with one quoted line as proof). 3. Words and phrases I use often. 4. Words, phrases and patterns I never use, including common AI habits like "it's not X, it's Y" and rule-of-three lists. 5. How I open and close messages. 6. Formatting habits (lists, length, sign-offs). Write it as rules a bot can follow, not adjectives. Quote my lines as evidence for each rule. Show me the draft profile first. Do not write anything else in my voice yet.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Pasting AI-written drafts in as samples. The profile then learns the bot's habits, not yours.
- Letting the profile go stale. When drafts start sounding generic again, add the new misses as rules.
- Trusting the profile to finish the job. It writes a closer first draft; you still check facts, names and tone before anything sends.
- Pasting a bot's reply straight into a public thread. Even with a voice profile, a reply that only echoes the post reads as AI. Add one real detail from your own work, or skip the reply.
- The first profile, with a quoted line behind every rule, was too long for the 1,500 characters ChatGPT allows. Cut the quotes before saving.

## Tested

Ran on Claude in a Claude Code session, Nov 5, 2026: 12 made-up writing samples gave a 6-part voice profile, which was cut to 1,498 characters after a test draft showed 3 misses. Saving it as standing instructions in ChatGPT, Claude or Grok Bot was simulated by pasting it into the chat.

The full receipt is on https://www.aisetupsthatwork.com/setups/make-ai-write-in-your-voice/

## Source

https://www.aisetupsthatwork.com/setups/make-ai-write-in-your-voice/ (AI Setups That Work)
