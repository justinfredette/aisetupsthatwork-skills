---
name: make-a-family-cookbook-with-ai
description: "Make a family cookbook with AI. Collect the recipes however they exist: photos, handwritten cards, memory. AI transcribes and standardizes them into one consistent format, you add the stories behind the dishes, and you print one book the whole family gets. Use when the user asks for help with this job."
---

# Make a family cookbook with AI

## When to use

Anyone with a shoebox of recipe cards or a relative whose dishes only exist in their head.

## Steps

1. Gather everything first. Photograph the cards, scan the notebook pages, and for the recipes that only exist in someone’s head, record them explaining it or dictate it flat as plain words and numbers.
2. Have the AI transcribe and standardize. One documented real-world workflow: typed recipes through OCR, handwritten ones dictated plainly, then GPT-4 reformatted everything into clean Markdown, fixing typos and OCR errors along the way.
3. Enforce one format for every recipe. Cookbook guidance says to keep it identical throughout: title, ingredients, instructions, equipment, time, and servings, with metric or imperial used consistently, never both.
4. Test the important ones. Have someone cook the recipe exactly as written. If an ingredient is listed but never used in the steps, or a step references something not listed, fix it now.
5. Write the headnotes: a few lines per recipe on who made it, when it showed up, what it means. This is what makes it a family cookbook instead of a recipe file.
6. Plan the chapters before you assemble: by course, by occasion, or by who the recipes came from. Then lay it out with photos. Blurb recommends a layflat binding for cookbooks so pages stay open on the counter.
7. Print one copy first, or share the digital version with the family for corrections, before ordering the full batch.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me turn family recipes into a cookbook.

Here are my raw recipes: [paste transcribed or dictated recipes, e.g. "Grandma’s pot roast: a handful of this, cook till done, serves the whole crew"]

For each recipe, produce:
- Title
- Headnote: 2-3 sentences I will fill with the family story [leave a placeholder: FAMILY STORY]
- Ingredients: exact quantities, one per line
- Instructions: numbered steps, in order
- Time and servings: your best estimate, marked as ESTIMATE

Rules:
- Use [brackets] for anything you are guessing: quantities, temperatures, times.
- Flag any step that is vague ("cook till done") so I can ask the cook what they actually do.
- Keep one consistent format across all recipes.

Review every recipe with the person who makes it before this goes to print. Guessed quantities need a real cook’s sign-off.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Guessed quantities presented as fact. Bracket every estimate and get the cook to verify, or the book will not actually work in a kitchen.
- OCR errors in scanned cards: "1 tsp" becomes "7 tsp" more often than you would like. Read every transcribed recipe against the original.
- Scope creep into a 200-page epic. Start with the 20 recipes that matter most. A finished small book beats an abandoned big one.

## Source

https://www.aisetupsthatwork.com/setups/make-a-family-cookbook-with-ai/ (AI Setups That Work)
