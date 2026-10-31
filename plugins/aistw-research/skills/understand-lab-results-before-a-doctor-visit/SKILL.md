---
name: understand-lab-results-before-a-doctor-visit
description: "Understand Lab Results Before Your Doctor Visit. This is not medical advice, and AI is not a doctor. Use AI to learn what a test generally measures and to build a question list for your visit. The interpretation of your results belongs to your provider. Use when the user asks for help with this job."
---

# Understand Lab Results Before Your Doctor Visit

## When to use

Patients who get lab results in a portal and want to walk into the appointment informed. This is not medical advice; do not paste full lab reports into a chatbot.

## Steps

1. Note the test names from your portal or paperwork. You do not need the numbers for this setup.
2. Ask the AI what each test generally measures and why doctors order it. Keep it general, not personal.
3. Ask what kinds of questions patients typically ask about these tests.
4. Write your own question list: what you want to understand, what worries you, and what happens next.
5. Bring the list to the appointment. Your provider interprets your results in the context of your overall health.
6. After the visit, use the AI to help you organize the doctor’s answers into notes. The doctor’s interpretation is the record, not the chatbot’s.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me prepare questions for my doctor visit. You are a preparation helper, NOT a doctor, and you do NOT interpret lab results.

Tests ordered: [test names only, no results, no personal health details]

Rules:
- Explain in plain language what each test generally measures and why doctors commonly order it.
- List 6 to 8 questions patients commonly ask about these tests.
- Do NOT interpret results, diagnose, or suggest what my results might mean. I have not given you results and you must not ask for them.
- Remind me that reference ranges vary by lab, age, and sex, and that only my provider can interpret my results.
- End with: "Take your questions to your provider. This is not medical advice."

Review the question list before your visit.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- AI is not a doctor and cannot interpret your lab results. A result outside the range may or may not indicate a problem; only your provider knows.
- Do not paste full lab reports or personal health details into a chatbot. Test names are enough for preparation.
- A result inside the reference range is not always a guarantee of good health, and "normal" can be misleading. Context matters.
- At-home test kits should never replace testing your provider orders. Bring questions about those to the visit too.

## Source

https://www.aisetupsthatwork.com/setups/understand-lab-results-before-a-doctor-visit/ (AI Setups That Work)
