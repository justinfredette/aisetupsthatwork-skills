---
name: summarize-a-long-report-into-a-one-pager
description: "Turn a long report into a one-page brief. Feed the report to the AI and ask for a one-page executive summary: purpose, key findings, numbers that matter, and recommended actions. You get the gist without reading forty pages. Use when the user asks for help with this job."
---

# Turn a long report into a one-page brief

## When to use

Anyone who gets handed long reports and needs the important parts before the meeting.

## Steps

1. Get the report into text the AI can read. Paste it in chunks if it is very long.
2. Tell the AI who the brief is for and what decision it needs to support.
3. Ask for a one-page structure: purpose, key findings, numbers that matter, recommendations.
4. Ask it to keep every claim tied to a page or section number so you can verify.
5. Read the brief, then spot-check two or three claims against the original.
6. If something looks wrong or invented, ask the AI to quote the exact passage it came from.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Summarize the following report into a one-page brief.

The brief is for: [AUDIENCE, e.g. my manager, the board]
The decision it needs to support: [DECISION]

Structure it as:
1. Purpose: why this report exists, in two sentences.
2. Key findings: the five most important points, each one sentence.
3. Numbers that matter: every important figure, with the page or section it came from.
4. Recommendations: what the report suggests doing next.
5. Open questions: anything important the report does not answer.

Keep it to one page. Do not add information that is not in the report. If a section of the report is vague, say so instead of filling in the gaps.

Report:
[PASTE REPORT TEXT]
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The AI can invent numbers that look right but are not in the report. Spot-check every figure that matters.
- Vague source text produces confident-sounding filler. Ask it to flag what the report does not say.
- Tables and charts often paste badly. Describe or retype key tables instead of pasting broken formatting.

## Source

https://www.aisetupsthatwork.com/setups/summarize-a-long-report-into-a-one-pager/ (AI Setups That Work)
