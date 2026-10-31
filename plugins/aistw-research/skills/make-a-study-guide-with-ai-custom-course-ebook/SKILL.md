---
name: make-a-study-guide-with-ai-custom-course-ebook
description: "How to make a study guide with AI: a custom course ebook on any topic. Tell it what you already know and your goal. It writes chapters with quizzes and sources, in Markdown you can turn into an EPUB or PDF. Use when the user asks for help with this job."
---

# How to make a study guide with AI: a custom course ebook on any topic

## When to use

Anyone whose courses on a topic are either too basic or skip the part they care about, and who wants one built around what they already know and why they are learning it.

## Steps

1. Research bot: gathers the source material. Give it the docs, articles, or projects you want covered.
2. Writer bot: turns that into chapters, from basics to the hard parts, with a short quiz after each one.
3. Formatter: exports it as an EPUB for your e-reader or a PDF. Pandoc is a free tool that can write both from a Markdown file.
4. If your bot can run commands, ask it to finish with pandoc course.md -o course.epub. PDF output needs a PDF engine such as LaTeX installed.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build me a personal course on [TOPIC] as a book of about [NUMBER] pages.
About me: I already know [WHAT YOU KNOW]. I'm learning this because [YOUR GOAL].
Also cover how [TOOL OR PROJECT 1] and [TOOL OR PROJECT 2] relate to it.
Structure:
- A one-page roadmap first.
- Chapters that go from basics to the hard parts, each with examples and a 5-question quiz.
- A "sources" list at the end of every chapter. Mark anything you're not sure is true.
Write it in Markdown with clear headings so I can turn it into an EPUB or PDF.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- A course written by AI can state wrong things with confidence. Check each chapter's sources against the official docs, especially on technical topics.

## Source

https://www.aisetupsthatwork.com/setups/make-a-study-guide-with-ai-custom-course-ebook/ (AI Setups That Work)
