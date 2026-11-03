---
name: fix-wrong-answers-from-your-own-documents
description: "Fix wrong answers from your own documents. Before switching models, check the files: old versions, two documents that disagree, or a long file where the rule is buried. Remove outdated files, put the key rules in one short cheat sheet, tell it to quote the file it used, and re-test with questions you know the answers to. Use when the user asks for help with this job."
---

# Fix wrong answers from your own documents

## When to use

Owners using a Claude or ChatGPT project, or a support bot, that answers from their own documents and sometimes gets a policy or price wrong.

## Steps

1. Ask the wrong question again and require it to quote the exact file and passage it used.
2. If it quotes an old or different file, delete or rename the outdated one. Two price lists in one project is the most common cause.
3. Anthropic says Claude switches to a retrieval mode when project knowledge gets large, so it pulls the passages that look most relevant. Put your key rules (refunds, prices, service area) in one short cheat sheet at the top.
4. Add the instruction from the prompt below so it quotes its source and says when files disagree.
5. Re-test with your 5 known questions, including the one it got wrong.
6. Only consider a different model after the files and instructions are clean.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Add to the project instructions:

When you answer:
1. Quote the exact sentence you used and name its file.
2. If two files disagree, show both quotes, say which file is newer, and do not pick one silently.
3. If no file answers the question, say: Not in our documents.
4. For prices, refunds and deadlines, use the cheat sheet file first.

Now answer this test question using those rules: [THE QUESTION IT GOT WRONG]
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Swapping models when the real problem is an outdated file.
- Burying the refund rule on page 30 of a manual.
- Fixing the answer in one chat instead of in the project files.

## Source

https://www.aisetupsthatwork.com/setups/fix-wrong-answers-from-your-own-documents/ (AI Setups That Work)
