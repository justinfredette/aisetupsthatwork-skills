---
name: audit-your-calendar-with-ai
description: "Audit your calendar with AI and take hours back. Export two to four weeks of calendar data and let AI categorize every recurring meeting: keep, shorten, delegate, or kill. Most people find hours a week they did not know they were losing. Use when the user asks for help with this job."
---

# Audit your calendar with AI and take hours back

## When to use

People who end most days wondering where the time went, with a calendar full of recurring meetings nobody remembers starting.

## Steps

1. Export the last 2–4 weeks from Google Calendar or Outlook (settings, export, or copy the events into a sheet).
2. For recurring meetings, note the real purpose in one line each. "Weekly sync" is not a purpose.
3. Ask the chatbot to score every recurring meeting: does it still serve a current need, do you need to be there, could it be shorter or async?
4. Sort the results into four buckets: keep, shorten, delegate, kill.
5. Act on the easy kills first. Decline one meeting this week. Shorten one from 60 to 30 minutes.
6. Repeat quarterly. Calendars grow meetings like gardens grow weeds.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Audit my calendar. Find me hours I am wasting.

HERE ARE MY RECURRING MEETINGS (title, length, frequency, attendees, my best guess at purpose):
[paste your list]

And here is what a typical week looks like:
[paste or describe]

For each recurring meeting, give me:
1. A verdict: KEEP, SHORTEN, DELEGATE, or KILL, with one line of reasoning.
2. If SHORTEN: the new length and what to cut from the agenda.
3. If KILL: what to replace it with (async update, document, nothing).

Then total up the hours per week I could reclaim. Be blunt. If a meeting exists because "we have always had it," say so.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Auditing and not acting. The audit is step one. Declining the meeting is the setup.
- Killing meetings you secretly like. Be honest about which ones are social hours wearing a work costume.
- AI cannot see meeting quality. It scores from your descriptions. "Weekly sync, not sure why" will get flagged, and rightly so.

## Source

https://www.aisetupsthatwork.com/setups/audit-your-calendar-with-ai/ (AI Setups That Work)
