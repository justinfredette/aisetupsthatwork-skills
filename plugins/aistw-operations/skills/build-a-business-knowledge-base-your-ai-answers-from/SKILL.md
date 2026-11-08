---
name: build-a-business-knowledge-base-your-ai-answers-from
description: "Build a knowledge base your AI answers from. Create one project, upload your real documents (prices, policies, service areas, how-tos), and add instructions that it must answer only from those files."
---

# Build a knowledge base your AI answers from

## When to use

Owners and small teams who keep answering the same internal questions, or who want a reliable starting point before an AI drafts anything for customers.

## Steps

1. Gather the 5 to 15 documents people ask about most: price list, policies, service areas, warranty, how-tos. Remove anything private you would not want quoted.
2. Create a project. Anthropic says projects have their own knowledge base and instructions and are available on free accounts; OpenAI says Projects keep chats, files and instructions together.
3. Upload the documents to the project's files or knowledge, not to a single chat, so every new chat can use them.
4. Paste the instructions from the prompt below so it answers only from your files and names the file it used.
5. Test it with five questions you already know the answers to, including one that is not in the files. It should say it does not know.
6. When a price or policy changes, replace the file the same day. Old files are the main source of wrong answers.

## What to ask the user for

- BUSINESS NAME

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Project instructions:

You answer questions about [BUSINESS NAME] using only the files in this project.
Rules:
- Answer in 2 to 5 sentences, then name the file you used.
- If the answer is not in the files, say: Not in our documents. Do not guess.
- Quote prices, dates and policy terms exactly as written.
- If two files disagree, show both and say which is newer.
- Never promise discounts, refunds or deadlines that are not in the files.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Uploading files to one chat instead of the project, so the next chat cannot see them.
- Old price lists left in the project next to new ones.
- Asking it about something it was never given, and trusting a confident guess.

## Source

https://www.aisetupsthatwork.com/setups/build-a-business-knowledge-base-your-ai-answers-from/ (AI Setups That Work)
