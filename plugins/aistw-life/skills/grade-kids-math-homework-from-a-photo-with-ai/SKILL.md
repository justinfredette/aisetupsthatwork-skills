---
name: grade-kids-math-homework-from-a-photo-with-ai
description: "How to grade your kid's math homework from a photo with AI. Snap a photo of the finished sheet. The bot reads each answer, marks it right or wrong, and writes a short note on what to fix. Use when the user asks for help with this job."
---

# How to grade your kid's math homework from a photo with AI

## When to use

Parents checking a stack of math worksheets at night, who need their kid to know which answers were wrong and why while it is still fresh.

## Steps

1. Grader bot: you snap a photo of the finished sheet. It reads each answer, marks it right or wrong, and writes a short note on what to fix.
2. Messenger (optional): sends each kid their score and fix list by text or chat. Use an account you control, and use first initials or a nickname.
3. Practice bot (optional): once a day it turns the mistakes into a short practice sheet as a PDF you can print.
4. Paste the starter prompt into your AI bot with a photo attached.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are grading a kid's math worksheet from the photo I attach.
1. Read every problem and the kid's written answer. If you can't read one, say "can't read #N" instead of guessing.
2. Work each problem yourself and mark it right or wrong.
3. Give a score like 18/20.
4. For each wrong answer, explain the fix in one short, kind sentence a [AGE]-year-old can follow.
5. Make a 5-problem practice set that targets the mistakes, plus an answer key on a separate page.
Call the kid "[NICKNAME]". Don't ask for or store their real name, school, or photo of their face.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- AI still misreads messy handwriting and can get a step wrong, so spot-check a few answers each week before trusting the scores.

## Source

https://www.aisetupsthatwork.com/setups/grade-kids-math-homework-from-a-photo-with-ai/ (AI Setups That Work)
