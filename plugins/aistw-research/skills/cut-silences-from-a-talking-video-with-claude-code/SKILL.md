---
name: cut-silences-from-a-talking-video-with-claude-code
description: "Cut silences from a talking video. Ask Claude Code to find the pauses with FFmpeg's silencedetect filter and list them before it cuts anything. Approve the list, then have it cut the video and sound."
---

# Cut silences from a talking video

## When to use

Anyone who records talking videos, tutorials or updates and spends time trimming the gaps by hand. You need Claude Code and FFmpeg on a computer. Nothing else to install.

## Steps

1. Make a folder with a copy of your video in it. Cutting changes every time after the first cut, so cut pauses before you add captions.
2. Decide how long a pause has to be before it goes, and how much quiet to keep on each side of a cut. The prompt starts at 1 second and 0.2 seconds.
3. Open Claude Code in that folder and paste the prompt below. It lists every pause it found, with times, and waits.
4. Read the list. Keep a pause that is there on purpose, like a beat before a punchline, by telling it which one to leave in.
5. Say OK. It cuts the pauses and checks that the video and the sound are still the same length.
6. Listen to the first few cuts it points you to. If a word sounds clipped, ask for more quiet around the cuts and run it again. The new file is re-encoded, so a long video takes a few minutes to write.

## What to ask the user for

- FILE NAME
- 0.2

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are cutting the pauses out of a talking video with FFmpeg in this folder. Do not post or upload anything. Never change or delete my original file.

Video: [FILE NAME]
Cut pauses longer than: [1] second
Keep this much quiet on each side of a cut: [0.2] seconds

1. Check FFmpeg is installed. Tell me the video's length, frame rate and whether it has sound.
2. Find the pauses with FFmpeg's silencedetect filter, starting at noise=-30dB. List each pause with its start, end and length, and the total time that would come out. If it finds none, or pauses inside sentences, adjust the noise level and tell me why. Wait for my OK.
3. Cut the pauses, keeping the quiet on each side so no word is clipped. Take the video and the sound from the same time ranges in one FFmpeg command so they stay in sync. Write a new MP4 (H.264, AAC, fast start).
4. Check the result: the length before and after, the video and sound stream lengths (they should match), and where each cut lands in the new file. Save a still frame just after the first 3 cuts and look at them.
5. Tell me which cuts to listen to, for example any that land close to a word.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Claude Code may refuse its own command when it uses a shell variable. It rewrites it with full file paths; no action needed.

## Tested

Ran on Claude in a Claude Code session, Nov 5, 2026: a 60-second made-up talking clip with 5 written-in pauses was checked with silencedetect, the 5 pauses were listed and approved, and one FFmpeg command cut 11.8 seconds with the video and sound streams matching to 0.001 s. Nothing was posted.

The full receipt is on https://www.aisetupsthatwork.com/setups/cut-silences-from-a-talking-video-with-claude-code/

## Source

https://www.aisetupsthatwork.com/setups/cut-silences-from-a-talking-video-with-claude-code/ (AI Setups That Work)
