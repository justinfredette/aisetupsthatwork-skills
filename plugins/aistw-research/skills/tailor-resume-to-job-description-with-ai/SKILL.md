---
name: tailor-resume-to-job-description-with-ai
description: "ChatGPT Prompt for Tailoring Your Resume to a Job Description. I paste the job posting and my current resume into ChatGPT, ask for a gap table and bullet rewrites that use only my real experience, then I edit every line before I apply. No auto-submit to job boards. Use when the user asks for help with this job."
---

# ChatGPT Prompt for Tailoring Your Resume to a Job Description

## When to use

Job seekers who keep sending the same PDF and wonder why nothing sticks, or anyone applying to a role with a long requirements list.

## Steps

1. Paste the job description first and ask the model to list required vs nice-to-have requirements in a table.
2. Paste your resume and ask for a gap table: requirement → where you already prove it → what is missing → honest fix (reword vs skip).
3. Ask for rewritten bullets for roles you already list. Same employers and dates, stronger verbs, keywords from the posting where truthful.
4. Reject any invented certification, tool, or metric; tell it to mark TBD instead of guessing.
5. Optional: ask for a 3-sentence cover-letter hook that cites one real win from your resume.
6. You copy the final resume and application text into the employer site yourself. No connected agents with apply permissions.
7. Cover letter: collect the facts before you open the chat - 2 or 3 real achievements you can prove, 1 or 2 specific reasons this company interests you (from their site or the ad), and your name and the company name only. Leave phone numbers, addresses, and ID numbers out of the paste.
8. Cover letter: brief the model first with the role, your writing style, phrases to avoid (like 'I am writing to apply'), and a hard rule - do not invent skills, results, tools, or dates; ask instead. Then ask for a 250 to 350 word draft and ask it to list every claim against your notes so you can catch inventions. You review the output before it is used.
9. Career break: ask for a combination-style resume - skills and any freelance, volunteer, or coursework up top, work history below - with the break as one plain line (for example, 'Career break - caregiving, [years]'). Then ask it to translate the break into transferable skills (scheduling, budgeting, logistics) only where they map to the target job.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are helping me tailor my resume to one job. Do not submit applications or edit files on my computer.

Job description (full text):
[paste posting]

My current resume:
[paste resume]

Rules:
- Use only employers, dates, titles, and outcomes that appear in my resume unless I explicitly add new facts in chat.
- Do not invent skills, certifications, tools, or metrics. If something is missing, say "gap" and suggest honest wording or omit.
- Match keywords from the posting only where my experience supports them.
- Output: (1) requirements table, (2) gap table, (3) suggested bullet rewrites per job entry, (4) optional 3-sentence cover hook.
- Show drafts only: I approve before anything is sent or uploaded.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Models love to quietly add skills you do not have. Treat every bullet like a fact-check before you apply.
- Pasting your whole career into cloud chat may violate employer or recruiter policy. Redact client names if needed.
- One generic rewrite rarely beats a human read of the posting, if the gap table is mostly red, the role may be a stretch.
- Cover letter drafts invent flattering details you never gave - run a fabrication check (ask the model to list every claim not found in your notes) and delete anything you cannot defend in an interview.

## Source

https://www.aisetupsthatwork.com/setups/tailor-resume-to-job-description-with-ai/ (AI Setups That Work)
