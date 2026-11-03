---
name: make-a-promo-reel-with-ai-from-code
description: "Make a promo reel with AI, from code. Ask a coding AI to draw every frame as a function of time in one HTML file, screenshot each frame with a headless browser, then join the frames and a music track with FFmpeg. Check still frames before the full render, and time the scenes to the music, not the other way round. Use when the user asks for help with this job."
---

# Make a promo reel with AI, from code

## When to use

Small business owners and builders who can run a command in a terminal, or who have someone who can. You need a coding AI that can write and run files, such as Claude Code. A chat-only AI can write the files for you to run yourself.

## Steps

1. Write the story in six beats: hook, the problem piling up, the turn (one word), your product's name, a short demo, and the call to action. Keep it to 45 seconds.
2. Give your coding AI the prompt below. It builds one HTML file at 1080 by 1920 where a function draws any moment of the video from the time alone, so every frame is exact and repeatable.
3. Ask it to render about 10 still frames, one per scene, and look at them together before rendering the whole video. Fix overlaps and cut-off text here; it is far cheaper than re-rendering.
4. Make the music. In ElevenLabs Music, describe the genre, tempo and where the drops land, and add short lyrics if you want vocals. ElevenLabs says songs can run from 3 seconds to 10 minutes. Make a few takes.
5. Pick the take whose drops land closest to your cuts. If it has vocals, transcribe it and retime the scenes so each line lands on its words. Move the video to the music, not the music to the video.
6. Add captions for the lyrics or voiceover. Many people scroll with the sound off, and without captions the reel says nothing.
7. Render all frames, join them with the track in FFmpeg, and watch the whole MP4 with sound before you post. Pick a cover frame that shows the problem, like the biggest number.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Build a 45-second vertical promo reel as code. Do not post anything.

Product: [WHAT YOU SELL, ONE LINE]
The job it does: [ONE JOB, E.G. CHASES LATE INVOICES]
Hook (what the customer types or says): [ONE SENTENCE]
The pile-up: [WHAT GROWS, E.G. INVOICES UNPAID] counting up to [NUMBER]
The result: [E.G. 12 OF 12 REMINDED]
Call to action and link: [TEXT AND URL]
Brand colors: [2 OR 3 HEX CODES]

Build it like this:
1. One HTML file, 1080x1920, with window.renderAt(t) that draws the frame for any time t in seconds from scratch. No timers, no animation that depends on real time.
2. Keep every scene start time in one object so I can retime the whole video in one place.
3. Scenes: hook typed in (0-6.7s), a black screen with the problem (6.7s), the count-up, one big word for the turn, the product name, a demo of the job with a draft I approve, then the end card.
4. Use only made-up names, numbers and companies in the demo.
5. Write a Node script that opens the page in Playwright, renders 30 frames per second as images, and joins them with an audio file using FFmpeg into an MP4 (H.264, AAC). Add a --frames option to render just a few still frames.
6. Render stills at 2.5, 7.5, 14, 17.5, 26 and 42 seconds and show me them before the full render. Check that no text overlaps or runs off the frame.
7. Add a captions layer driven by a list of [start, end, text] lines.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Previews in some apps play muted. Download the MP4 and play it with sound before deciding the audio is missing.
- Text that types in can still be mid-word when the scene cuts. Speed up the typing or give the scene more time.
- Only use music you made or have the rights to. Do not borrow a track from someone else's video.
- Download the MP4 and play it with sound before deciding the audio is missing.

## Source

https://www.aisetupsthatwork.com/setups/make-a-promo-reel-with-ai-from-code/ (AI Setups That Work)
