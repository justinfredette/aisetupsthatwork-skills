---
name: write-home-assistant-automations-with-ai
description: "Write Home Assistant automations with AI. Describe the automation in plain words: what should trigger it, any conditions, and what should happen. The AI writes the YAML in the current format, and you test it in Home Assistant before trusting it. Use when the user asks for help with this job."
---

# Write Home Assistant automations with AI

## When to use

Home Assistant users who understand automations conceptually but dread writing YAML by hand.

## Steps

1. Know the three parts first. Home Assistant’s docs define every automation as: When (triggers, e.g. motion detected), And if (conditions, optional, e.g. someone is home), Then do (actions, e.g. turn on a light).
2. Look up your real entity IDs in Developer Tools, then States. The AI cannot know your devices; invented entity names are the number one reason AI-written automations fail silently.
3. Describe the automation in plain words with the three parts: the trigger, the condition, the action. Include the exact entity IDs.
4. Ask for YAML in the current format. Key names changed over releases: service became action, platform became trigger, and singular trigger/condition/action became plural. Old keys still work but cannot be mixed with new ones in the same automation.
5. Paste it where it belongs. Automations created in the UI live in automations.yaml, which is UI-managed; manual YAML goes in configuration.yaml, and you must reload automations after changes.
6. Test before trusting. Trigger it manually, watch what happens, and check the automation’s trace to see each step execute. A unique id on the automation enables renaming and stores debug traces.
7. Start with harmless automations: lights and notifications. Save locks, alarms, and anything with water or heat for after you trust the pattern.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Write a Home Assistant automation in YAML. I will test it before relying on it.

What I want in plain words: [e.g. "When motion is detected in the hallway after sunset and someone is home, turn on the hallway light to 50%, then turn it off after 5 minutes of no motion"]
Trigger entity: [exact entity ID, e.g. "binary_sensor.hallway_motion"]
Condition: [e.g. "sun below horizon AND someone home (person.you)"]
Action entities: [exact entity IDs, e.g. "light.hallway"]

Rules:
- Use the current YAML format: triggers, conditions, actions (plural keys), action instead of service.
- Use ONLY the entity IDs I gave you. Never invent device or entity names.
- Include a unique id so I can rename it and view traces.
- After the YAML, give me: where to paste it, how to reload, and how to test it step by step.

I will review the YAML and test the automation manually before trusting it.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Invented entity IDs. The AI will happily write light.living_room when yours is light.livingroom_lamp. It fails silently. Always paste real IDs.
- Mixed old and new key names. Old keys still work, but mixing service with actions in one automation breaks it. Pick the current format and stay in it.
- Trusting it on the first try for anything physical. Test with lights and notifications first; locks, garage doors, and water valves earn trust over time.

## Source

https://www.aisetupsthatwork.com/setups/write-home-assistant-automations-with-ai/ (AI Setups That Work)
