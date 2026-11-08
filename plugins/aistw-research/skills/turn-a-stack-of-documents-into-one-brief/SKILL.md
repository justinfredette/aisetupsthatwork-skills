---
name: turn-a-stack-of-documents-into-one-brief
description: "Turn a stack of documents into one brief. Upload the files to one chat or project and ask for a brief that cites which document each point came from, lists conflicts between documents, and keeps."
---

# Turn a stack of documents into one brief

## When to use

Anyone who has to read ten documents to make one decision or write one summary for a boss, client or board.

## Steps

1. Collect the documents and give each a clear file name, like vendor-a-proposal.pdf.
2. Upload them to one chat, or to a project if you will come back to them. Anthropic says files can go in a chat or in a project's Files section.
3. Paste the prompt below and say what the brief is for, such as choosing a vendor.
4. Read the conflicts section first. That is where the decision usually is.
5. Check every number in the brief against the file it cites.
6. Ask for a second version in the format you need, such as one page for your boss or a table.

## What to ask the user for

- NUMBER
- E.G. CHOOSE A VENDOR, BRIEF MY BOSS

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I uploaded [NUMBER] documents. Write one brief for this purpose: [E.G. CHOOSE A VENDOR, BRIEF MY BOSS].

Format:
1. One paragraph: the answer to my purpose, if the documents support one.
2. Each document in 2 to 3 bullet points, labeled with its file name.
3. Where documents agree.
4. Where they conflict, quoting each side with its file name.
5. What is missing that I would need to decide.

Rules: keep numbers and dates exactly as written, cite the file name for every point, and say Not stated rather than guessing.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- A scanned PDF with no text layer reads as empty. Ask it to list any file it could not read.
- Numbers drift between the documents and the brief. Check each one.
- Asking for a recommendation before reading the conflicts.

## Source

https://www.aisetupsthatwork.com/setups/turn-a-stack-of-documents-into-one-brief/ (AI Setups That Work)
