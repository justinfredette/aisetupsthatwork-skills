---
name: set-up-a-voice-file-in-claude
description: "Set up a voice file in Claude. Paste 10 to 20 pieces of your own writing into Claude and have it draft a voice profile. Then make a Project: open Projects, select + New Project, click Set project."
---

# Set up a voice file in Claude

## When to use

Claude users who rewrite every draft to sound like themselves and want one place that holds the profile and the samples behind it.

## Steps

1. Gather 10 to 20 pieces of your own writing. Mix the kinds you write most, such as customer emails, posts and proposals. Leave out anything AI drafted, and anything with client-confidential details.
2. Open Projects in the left-side panel (or go to claude.ai/projects) and select + New Project. Name it, for example Voice profile. Anthropic says Claude does not see the name or description.
3. Add your samples: on the project's main page, find the knowledge base on the right side, click the + button and upload them as files. Anthropic says Claude uses project knowledge as context in that project's chats.
4. Start a chat in the Project and run the first part of the prompt below. Edit the profile until every rule is one a bot can follow, then click Set project instructions, paste it in and select Save instructions. Anthropic says Claude uses these instructions for all the chats within the project.
5. Test it: start a new chat in the Project and ask for a short draft on a real topic. Compare it with one of your samples, add each miss to the instructions as a rule, and save again.
6. Optional, for drafts outside the Project: run the second part of the prompt and paste the short version under Settings, Your Claude, Instructions, which Anthropic says apply to all conversations. Or save it as a skill: a folder holding a skill.md file that starts with a name and a description, zipped and turned on in Customize, Skills.

## What to ask the user for

- NUMBER
- PASTE SAMPLES OR SAY "use the project files"

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
PART 1:
Here are [NUMBER] pieces of my own writing, in this Project's knowledge and pasted below: [PASTE SAMPLES OR SAY "use the project files"]. Read them and draft a one-page voice profile I can save as project instructions. Use these sections: 1. Sentence habits (length, rhythm, fragments). 2. Tone (how I come across, with one quoted line as proof). 3. Words and phrases I use often. 4. Words, phrases and patterns I never use, including common AI habits like "it's not X, it's Y" and rule-of-three lists. 5. How I open and close messages. 6. Formatting habits (lists, length, sign-offs). Write it as rules a bot can follow, not adjectives. Quote my lines as evidence for each rule. Show me the draft profile first. Do not write anything else in my voice yet.

PART 2 (optional, for drafts outside this Project):
Now write a short version of that profile for my account instructions: the rules that change a draft the most, with no quoted evidence. Then write the same rules as a skill.md file that starts with this header:
---
name: my-writing-voice
description: Use when drafting emails, posts or other writing for me, so the draft follows my voice profile.
---
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Asking for a draft in an ordinary chat and getting no voice. Project instructions apply only inside that project; start the chat in the Project.
- Pasting AI-written drafts in as samples. The profile then learns the bot's habits, not yours.
- The skill does not show up. Anthropic says skills need code execution switched on, and the ZIP must hold the skill folder at its root.
- Letting the profile go stale. When drafts start sounding generic again, add the new misses as rules.

## Source

https://www.aisetupsthatwork.com/setups/set-up-a-voice-file-in-claude/ (AI Setups That Work)
