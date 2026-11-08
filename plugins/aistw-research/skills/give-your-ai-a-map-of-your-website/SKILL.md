---
name: give-your-ai-a-map-of-your-website
description: "Give your AI a map of your website. When an AI assistant answers without your site's specifics, its SEO advice stays generic. Fix it with one markdown file: every important page, the search phrase."
---

# Give your AI a map of your website

## When to use

Owners who ask AI for SEO help and get generic advice that does not use what is actually on their site.

## Steps

1. Copy your page list: your sitemap address or the page list from your site builder. Ten to thirty pages is plenty.
2. Run the prompt below to draft the map: one section per page with its address, what it offers, the exact search phrase you want it found for, and two or three of your pages it should link to.
3. Check every line against the real page. Fix phrases that do not match what the page says, and cut pages you no longer want found.
4. Save the file as site-map.md. In Claude Code, put it in your project CLAUDE.md file, which Anthropic says loads at the start of every session. In ChatGPT, attach the file to the conversation when you ask for SEO help; OpenAI documents file uploads on free and paid plans.
5. Before any SEO request, tell the assistant to answer from the map first: which page should change, what phrase it targets, and which pages should link to it.
6. Update the file when you add or retire a page, and check it monthly against Search Console so the phrases stay real.

## What to ask the user for

- PASTE URLS OR PAGE TITLES

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Here is a list of my website's pages: [PASTE URLS OR PAGE TITLES]. Build a site map file in markdown with one section per page: the page address, what it offers in one line, the exact search phrase it should be found for, and two or three of my other pages it should link to, with the anchor text to use. Ask me about anything you cannot tell from the list. Do not invent pages or keywords.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Phrases nobody searches. Pull real queries from Search Console instead of guessing.
- Letting the file go stale after pages change, so the AI suggests edits to pages that no longer exist.
- Asking for advice without attaching the file, then getting generic answers again.

## Source

https://www.aisetupsthatwork.com/setups/give-your-ai-a-map-of-your-website/ (AI Setups That Work)
