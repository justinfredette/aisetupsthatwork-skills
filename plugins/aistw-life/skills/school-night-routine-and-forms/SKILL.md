---
name: school-night-routine-and-forms
description: "School night routine and forms. Work backward from the wake-up time to a bedtime that fits the sleep range for your child's age: the CDC, citing the American Academy of Sleep Medicine, lists 9 to 12 hours for ages 6 to 12 and 8 to 10 hours for ages 13 to 18. Keep a short list of forms, due dates and signers. Use when the user asks for help with this job."
---

# School night routine and forms

## When to use

Parents who juggle school emails, paper forms and a bedtime. For turning long school emails into a summary, see the school email setup. Do not paste your child's full name, ID number, medical details or home address into a chatbot.

## Steps

1. Write the wake-up time for school days and the time you need to leave.
2. Look up the sleep range for the child's age. The CDC, citing the American Academy of Sleep Medicine, lists 9 to 12 hours per 24 hours for ages 6 to 12, and 8 to 10 hours for ages 13 to 18.
3. Ask the chat to count back from the wake-up time to a bedtime in that range, then add the steps before it: dinner, homework, bag packed, bath, wind down. Change the times to fit your home.
4. Copy the form details from this week's emails and flyers into the chat: the form, the due date, the cost if any, who signs and how it goes back. Use first names or initials only.
5. Ask for a list sorted by due date: tonight, this week, later. Check each date against the original message.
6. Each night, check the list and the bag. Tick off what was signed and sent back.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me plan school nights and keep track of school forms.

I will use first names or initials only. I will not paste ID numbers, medical details or my home address. If I paste any, tell me to remove them.

Child's age: [age]
Wake-up time: [time]
Leave-the-house time: [time]
Steps we need each evening: [dinner, homework, bag, bath, reading]

Forms this week: [form, due date, cost, who signs, how it goes back]
Today's date: [DATE]

1. Count back from the wake-up time to a bedtime. Tell me which sleep range for my child's age you used, and remind me to check it with the pediatrician if I am unsure.
2. Build an evening checklist with a time for each step.
3. Sort the forms: tonight, this week, later.

Show me the evening checklist first. Do not guess due dates or costs. Ask me. I sign and send everything myself.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Setting a bedtime without counting back from the wake-up time, then missing the sleep range.
- Trusting a due date the chat inferred. Confirm it in the school's message.
- Pasting a full child's name or ID into the chat. Use first names or initials.

## Source

https://www.aisetupsthatwork.com/setups/school-night-routine-and-forms/ (AI Setups That Work)
