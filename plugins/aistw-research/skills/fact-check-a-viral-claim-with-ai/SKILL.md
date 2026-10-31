---
name: fact-check-a-viral-claim-with-ai
description: "Fact-check a viral claim before you share it. Paste the claim into the AI and ask it to find the original source, check fact-checker sites, and rate the evidence. You get a verdict in a minute instead of falling for a screenshot. Use when the user asks for help with this job."
---

# Fact-check a viral claim before you share it

## When to use

Anyone with a group chat full of forwarded claims they are not sure about.

## Steps

1. Copy the exact claim text. If it is an image or video, describe what it shows and what it claims.
2. Ask the AI to search fact-checker sites (Snopes, FactCheck.org, PolitiFact) for this specific claim.
3. Ask it to trace the claim back to the original source, not just reposts of it.
4. Ask for a verdict: true, false, misleading, or unverified, with links you can open yourself.
5. Open at least one of those links yourself. Do not take the AI’s word for it on a contested claim.
6. If the verdict is unverified, do not share the claim. Unverified is not the same as true.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I saw this claim online and want to check it before I share it:

[PASTE THE CLAIM TEXT OR DESCRIBE THE IMAGE/VIDEO]

Please:
1. Search Snopes, FactCheck.org, and PolitiFact for this exact claim and report what they say, with links.
2. Try to trace the claim to its original source. Is it being quoted accurately and in context?
3. Give me a verdict: true, false, misleading, or unverified.
4. Tell me what evidence supports your verdict and what is still unknown.

If you cannot verify it, say so clearly. Do not guess.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI can hallucinate a fact-check that does not exist. Always open the link it gives you.
- On fast-moving news, the AI’s training data is out of date. Use web search, not memory.
- Satire and edited videos trip up AI the same way they trip up people. If it feels off, dig deeper yourself.

## Source

https://www.aisetupsthatwork.com/setups/fact-check-a-viral-claim-with-ai/ (AI Setups That Work)
