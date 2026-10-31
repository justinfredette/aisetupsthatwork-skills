---
name: write-a-job-description-with-ai
description: "AI to Write a Job Description (Copy-Paste Prompt for Hiring). I paste the role title, required skills, pay band, and company tone into ChatGPT, get a draft job post with responsibilities and requirements I can edit, then I publish it myself in our ATS or Indeed. No auto-posting. Use when the user asks for help with this job."
---

# AI to Write a Job Description (Copy-Paste Prompt for Hiring)

## When to use

Small team leads hiring their first role, or anyone recycling a five-year-old posting that still says “rockstar ninja.”

## Steps

1. Write facts only: team size, reporting line, tools used, outcomes for the first 90 days.
2. Separate required skills from nice-to-haves so the model does not merge them.
3. Paste tone (formal startup, trades shop, nonprofit) and forbidden fluff words.
4. Ask for sections: About us (short), Role summary, Responsibilities, Requirements, Nice-to-have, Benefits (only what you list), How to apply.
5. Add a note that EEO/disability/accommodation boilerplate is a placeholder. You or counsel review.
6. Copy into your ATS; you publish and answer candidates. No connected agents with post permissions.
7. Ask for a shortlist of interview questions tied to the role: paste the job description and ask for 8 to 10 questions, each mapped to one required skill, with most questions asking for a past example (what they did, what happened) rather than hypotheticals. Have the model show its output first and review every question before you use it.
8. Ask for a one-page scorecard table: columns for the skill being tested, the question, what a good answer sounds like, what a bad answer sounds like, and a 1 to 5 score. Score each candidate right after the interview, before you discuss them with anyone else.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You draft a job description for my company. Do not post to job boards or email candidates.

Role title: [title]
Location / remote policy: [details]
Comp range (if I provide it): [range or "do not invent salary"]
Company blurb (facts only):
[paste 2-4 sentences]

Day-to-day responsibilities:
[paste bullets]

Required:
[paste]

Nice-to-have:
[paste or "none"]

Benefits we actually offer:
[paste: if empty, say "benefits not listed; do not invent"]

Tone: [professional / casual / trades / nonprofit]

Rules:
- No discriminatory language; use inclusive "you" where natural.
- Do not invent stock, unlimited PTO, or tools we do not use.
- Mark EEO/legal footer as [REVIEW WITH COUNSEL] unless I paste approved text.
- Output draft only: I approve before anything is published or sent.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Models invent benefits and salary. Delete every perk you did not paste.
- Generic “fast-paced environment” lines attract the wrong applicants. Swap for concrete outcomes.
- Legal compliance varies by state and country. This is a writing aid, not HR counsel.
- The model can drift into questions about protected topics (age, family, health). Treat any such question as a hard fail: delete it and re-run with the lawful-questions rule stated up front.

## Source

https://www.aisetupsthatwork.com/setups/write-a-job-description-with-ai/ (AI Setups That Work)
