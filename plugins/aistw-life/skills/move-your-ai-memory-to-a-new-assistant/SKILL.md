---
name: move-your-ai-memory-to-a-new-assistant
description: "Move your AI memory to a new assistant. Claude's help center says you can bring memory from another AI service by running an export prompt there, then pasting the result into Settings > Your Claude > Start import. Claude calls memory imports experimental, so check what it kept. Use when the user asks for help with this job."
---

# Move your AI memory to a new assistant

## When to use

Anyone switching or adding an AI assistant who is tired of re-explaining their job, tone and preferences. Do not move anything you would not want stored in the new service.

## Steps

1. In ChatGPT, open Settings, then Personalization, then Memory, and look at what is stored. OpenAI says the controls you see can vary by plan, region and workspace.
2. Ask ChatGPT what it remembers about you. OpenAI says you can ask it directly. Use the prompt below so the answer comes back as one list you can copy.
3. Read the list and delete any line you do not want in the new service. Claude's help center says you can edit the export prompt to leave out sensitive information.
4. Save the cleaned list in a text file as your own backup.
5. In Claude, go to Settings > Your Claude and select Start import. Paste the list into the text box and click Add to memory.
6. Click See what Claude learned about you and read the answer. Fix anything wrong with the Tell Claude what to change or remove box, or ask in chat.
7. Grok Bot: import steps are Not stated in sources. Paste the cleaned list into its instructions by hand and check the result.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I am moving to another assistant and want a clean copy of what you know about me. List every saved memory and every preference you use about how I like answers written. Put them in one list, one line each, with the date saved if you have it.

Rules:
- Keep my wording where you can.
- Do not guess or add anything you do not actually store.
- Mark any line that mentions health, money, passwords, account numbers, children or other private details with [PRIVATE] so I can delete it.
- After the list, say whether it is complete.

Show me the list first. Do not send it anywhere.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Claude calls imports experimental, so some entries may not be stored. Check with the See what Claude learned about you button.
- ChatGPT may list only part of what it holds. The export is a summary, not a guaranteed full copy.
- Pasting private details into a new service. Delete [PRIVATE] lines before you import.

## Source

https://www.aisetupsthatwork.com/setups/move-your-ai-memory-to-a-new-assistant/ (AI Setups That Work)
