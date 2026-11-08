---
name: make-a-product-launch-video-with-claude-code-and-remotion
description: "Make a product launch video from code. Write a one-page brief with five parts: the goal, what to deliver, the layout, a timeline of named events by frame, and the motion rules. Give it to Claude."
---

# Make a product launch video from code

## When to use

Anyone announcing a feature, a tool or a page who wants a short video without an editing app or stock footage. You need Claude Code and Node.js on a computer, screenshots of the product, and the patience to look at three still images before each render.

## Steps

1. Write the brief first, not the video. One page with five parts: GOAL (the feature, who watches, an opening line of 8 words or fewer, and one closing action with where to do it), DELIVERY AND ASSETS (1080x1080 and 1080x1920, 30 fps, 600 frames, and the list of screenshots, logo and fonts), LAYOUT (safe area, type sizes, line limits, logo space, layer order), TIMELINE (named events at frame numbers: when the opening lands, the press, the result, the reading hold, the closing) and MOTION RULES (one spring, how far cards rise, how long fades take). Only claims the product really makes.
2. Count reading time from when the text is legible, not from when it starts to appear. Give each block at least 1 second for every 3 words, then write those windows into the timeline. If a block cannot get its time, cut words.
3. Start from a small Remotion project where every word, every event frame and every motion setting lives in its own file, so a change is one number in one place. The Video Editing Kit ships one; Remotion's own template works too. Every movement comes from the frame number with useCurrentFrame, interpolate and spring. No CSS transitions, and any randomness seeded.
4. Take the two screenshots at 2x (a phone or browser screenshot is fine), put them in the project's public folder, and note the button's position so the cursor lands on it.
5. Open Claude Code in the project folder and paste the prompt below with your brief. Ask for npx remotion studio to be running so you can scrub through the result.
6. Render 3 stills, not the video: the opening, the product result and the closing, with npx remotion still. Review in three stages, in order: anything missing or unreadable, then timing, then detail. Fix the first stage before looking at the next.
7. Send each fix as one bounded line: location | observed problem | change | what stays fixed. Render the same still again before the next fix.
8. Export both shapes with npx remotion render and check each with ffprobe: 1080x1080 or 1080x1920, 30/1, 600 frames, 20 seconds. Watch both on your phone before you post anything.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are building a 20-second product launch video with Remotion in this folder. Do not post or upload anything.

Here is the brief:
[PASTE YOUR BRIEF: GOAL, DELIVERY AND ASSETS, LAYOUT, TIMELINE, MOTION RULES]

Rules:
1. Every word on screen comes from the brief's GOAL section. Add no claims and no numbers that are not in it.
2. Every event frame comes from the brief's TIMELINE and lives in one timeline file. Every size from LAYOUT, every movement from MOTION RULES.
3. Animate only from useCurrentFrame() with interpolate() and spring(). No CSS transitions or animations. Any randomness uses Remotion's random() with a fixed seed.
4. Two compositions: Launch at 1080x1080 and LaunchVertical at 1080x1920, both 30 fps and 600 frames.
5. Before any full render, render 3 stills with npx remotion still: the opening, the product result and the closing. Open them and tell me what you see, in this order: anything missing or unreadable, then timing, then detail.
6. Each block of text must stay on screen at least 1 second per 3 words, counted from when it is fully legible. Show me the math for each block.

Each fix will come as one line: location | observed problem | change | what stays fixed. Make only that change, render the still again, and tell me whether the problem is gone.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- In the test, the first render started on a blank frame, because the opening faded in. A cover taken from frame 0 was empty. The fix was to let the opening start fully visible and only move into place.
- The closing card sat still for the last 6 seconds and looked frozen. A slow zoom from 100% to 103% fixed it.
- Remotion tries to download its own browser the first time it renders. On a network that blocks the download, point it at a Chrome or Chromium you already have with --browser-executable.
- A text block that wraps to one line more than planned covers what is under it. Set a line limit for each block and check the stills at phone size.

## Tested

Ran on Claude in a Claude Code session, Nov 5, 2026: a 20-second launch video for the site's free missed-call calculator was built with Remotion from a five-section brief, reviewed from 6 stills and a contact sheet, fixed with 3 bounded edits in fresh sessions, and rendered at 1080x1080 and 1080x1920, 30 fps, 600 frames, checked with ffprobe. The brief and scenes were written in the template session, not by a fresh one. Nothing was posted.

The full receipt is on https://www.aisetupsthatwork.com/setups/make-a-product-launch-video-with-claude-code-and-remotion/

## Source

https://www.aisetupsthatwork.com/setups/make-a-product-launch-video-with-claude-code-and-remotion/ (AI Setups That Work)
