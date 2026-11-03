---
name: check-etsy-listings-against-the-new-ai-rules
description: "Check Etsy listings against the new AI rules. Etsy now requires at least one unedited photo of the actual item on a real background, photos that match what the buyer gets, an AI disclosure in the description when AI made the item, and no AI-generated patterns, recipes or instructions. Paste each listing and have the AI check it against those rules, then fix it yourself. Use when the user asks for help with this job."
---

# Check Etsy listings against the new AI rules

## When to use

Etsy sellers who used AI anywhere in a listing, from photos and mockups to descriptions, patterns or the item itself, and want to stay within the new rules.

## Steps

1. Copy the listing title, description and a one-line note for each photo: unedited, edited, AI background or AI mockup.
2. Paste them into the prompt below with what you sell.
3. Fix anything marked missing. Etsy says each listing needs at least one unedited photo of the actual item against a real background, with exceptions for some item types.
4. If AI helped create the item itself, add a plain disclosure in the description. Etsy says seller-prompted AI creations must be disclosed there.
5. If you sell patterns, recipes or instructions, make sure the instructions are your own work and show a real result. Etsy no longer allows AI-generated functional guides.
6. Check the exceptions on Etsy's Listing Image Requirements page for your item type before changing photos.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Check this Etsy listing against Etsy's AI rules. Use only what I paste.

What I sell: [E.G. PHYSICAL CANDLES / DIGITAL PLANNER / KNITTING PATTERN]
Title: [PASTE]
Description: [PASTE]
Photos (one line each): [E.G. 1 unedited on table, 2 AI background, 3 mockup]
Did AI help create the item itself? [YES/NO, HOW]

Check each rule and mark OK, MISSING or CHECK:
1. At least one unedited photo of the actual item on a real background
2. Photos accurately show what the buyer receives
3. AI use disclosed in the description, if AI helped create the item
4. Patterns, recipes or instructions are the seller's own work, with a real result shown
5. The listing was written and reviewed by a person, not posted by a bot

For each MISSING, write the exact fix. Do not rewrite my listing unless I ask.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Assuming an AI background is fine everywhere. Check the image rules and exceptions for your item type.
- Disclosing AI in tags but not in the description.
- Selling an AI-written pattern or recipe; those are no longer allowed.

## Source

https://www.aisetupsthatwork.com/setups/check-etsy-listings-against-the-new-ai-rules/ (AI Setups That Work)
