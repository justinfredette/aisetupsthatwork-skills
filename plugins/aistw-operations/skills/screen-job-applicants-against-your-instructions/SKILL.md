---
name: screen-job-applicants-against-your-instructions
description: "Screen job applicants against your instructions. List only job-related must-haves and the instructions in your post, such as a code word or answering one question. Have the AI check each application against those, quote the evidence, and sort into meets, missing info and does not meet. You read every shortlisted application and make every decision. Use when the user asks for help with this job."
---

# Screen job applicants against your instructions

## When to use

Small business owners hiring for one role who get dozens of applications at once.

## Steps

1. Write 3 to 5 must-haves that are about the job only: a license, availability, a skill, and any instruction from the post.
2. Leave out anything about age, family, health, nationality or other personal traits. The AI should never see or score those.
3. Upload the applications and run the prompt below. Anthropic says you can upload files to Claude for analysis.
4. Read every application in MEETS and MISSING INFO yourself. Spot-check a few in DOES NOT MEET.
5. You decide who gets an interview. The AI only sorts and quotes evidence.
6. Keep the must-haves list with your hiring records.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Check these job applications against my must-haves only. Use only what each application says.

Job post: [PASTE]
Must-haves (job-related only): [LIST, e.g. valid driver's license; weekends available; answered the question in the post]

For each applicant (use their initials only):
- each must-have: YES (quote the evidence), NO, or NOT STATED
- overall: MEETS, MISSING INFO, or DOES NOT MEET
Do not rank, score or comment on anything outside my must-haves. Do not guess.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Letting the AI rank people on vague things like culture fit.
- Rejecting MISSING INFO applicants without asking.
- Pasting full personal details when initials would do.

## Source

https://www.aisetupsthatwork.com/setups/screen-job-applicants-against-your-instructions/ (AI Setups That Work)
