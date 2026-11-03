---
name: check-your-resume-for-claims-you-cannot-back-up
description: "Check your resume for claims you cannot back up. Keep one master file with every role, project and result, with real numbers. Before sending a tailored resume or message, have the AI compare each line to the master file and flag anything not supported. Fix or delete every flag. Use when the user asks for help with this job."
---

# Check your resume for claims you cannot back up

## When to use

Job seekers using AI to tailor resumes who worry it is inflating titles, numbers or skills.

## Steps

1. Write a master file: every role with dates, projects and results with real numbers. Only what you could explain in an interview.
2. Save it in a Claude or ChatGPT project so each check starts from the same file.
3. Paste the tailored resume or message and run the prompt below.
4. Fix or delete every line marked NOT SUPPORTED or STRETCHED.
5. Re-run until everything is SUPPORTED.
6. Add new results to the master file as they happen, not when job hunting.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Compare this tailored resume to my master file. Check every line.

Master file: [IN PROJECT, OR PASTE]
Tailored resume or message: [PASTE]

For each line, mark:
- SUPPORTED: quote the matching master-file line
- STRETCHED: the claim is bigger than the master file (title, number, scope); show both
- NOT SUPPORTED: nothing in the master file backs it
Then list only the STRETCHED and NOT SUPPORTED lines with a fix that stays true.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- A master file that is itself vague, so everything looks supported.
- Accepting a stretched title because it sounds better.
- Checking the resume but not the cover letter or outreach note.

## Source

https://www.aisetupsthatwork.com/setups/check-your-resume-for-claims-you-cannot-back-up/ (AI Setups That Work)
