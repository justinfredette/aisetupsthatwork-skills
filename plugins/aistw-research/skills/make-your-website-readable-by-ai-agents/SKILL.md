---
name: make-your-website-readable-by-ai-agents
description: "Make your website readable by AI. Two things matter most: your robots.txt must let the AI crawlers you want in, and your key pages should be plain readable text. The llms.txt file is a proposal: an."
---

# Make your website readable by AI

## When to use

Owners of a small business website who want AI assistants to be able to read it. You need to be able to edit robots.txt or ask whoever manages the site. Do not block a crawler you want without reading what it does.

## Steps

1. Run your address through the AI-ready check at /tools/ai-ready-check/ and keep the result as a before copy.
2. Open yoursite.com/robots.txt. Google says robots.txt manages crawler traffic and is not a way to keep a page out of Google, so read it as traffic rules.
3. Decide each crawler on purpose. OpenAI says OAI-SearchBot is for search results in ChatGPT, GPTBot is for training, and ChatGPT-User is for user actions, and the settings are independent. Anthropic lists ClaudeBot for training, Claude-User for user requests and Claude-SearchBot for search, and says blocking the last two may reduce your visibility in answers.
4. Ask the assistant to draft an llms.txt file with the prompt below. The proposal says the only required part is an H1 with the site name, followed by an optional summary and lists of links with short notes.
5. Upload it at yoursite.com/llms.txt. Check that every link in it opens and goes to a page with readable text.
6. The proposal also suggests a clean markdown version of key pages at the same address with .md added. Skip it if your site builder cannot do that.
7. Run the AI-ready check again and compare it with the before copy.

## What to ask the user for

- NAME
- WHAT YOU DO, WHERE, FOR WHOM
- PAGE NAME - URL - what it covers in a few words

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Draft an llms.txt file for my business website. Use only the facts I give you.

Business name: [NAME]
One-sentence summary: [WHAT YOU DO, WHERE, FOR WHOM]
My 5 to 8 most useful pages: [PAGE NAME - URL - what it covers in a few words]

Format:
- An H1 with the business name
- A blockquote with the summary
- One H2 section called Pages with a markdown list: [name](url): short note

Rules:
- Do not invent services, prices, awards or claims.
- Only list URLs I gave you.
- No marketing language. Plain sentences.
- Show me the file first. Do not publish anything.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Blocking all bots in robots.txt by accident. Test after any edit.
- Blocking a search crawler and then wondering why AI answers skip you. Anthropic says disabling its search and user bots may reduce visibility.
- Linking pages that need a login or are mostly images. Use pages with plain text.

## Source

https://www.aisetupsthatwork.com/setups/make-your-website-readable-by-ai-agents/ (AI Setups That Work)
