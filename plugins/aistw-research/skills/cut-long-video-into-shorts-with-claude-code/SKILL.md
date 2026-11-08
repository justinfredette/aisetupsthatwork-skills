---
name: cut-long-video-into-shorts-with-claude-code
description: "Cut long video into shorts with Claude. Transcribe the long video with Whisper, which is free and runs on your computer. Give Claude Code the transcript and ask for 3 moments that stand on their."
---

# Cut long video into shorts with Claude

## When to use

Anyone with a podcast, webinar or talking video who wants shorts without paying for a clipping app. You need Claude Code and FFmpeg on a computer, plus Whisper for the transcript.

## Steps

1. Make sure anyone who appears in the video is okay with short clips of it being posted.
2. Ask Claude Code to install Whisper and FFmpeg if they are missing. Whisper's own page gives the install command, pip install -U openai-whisper, and says it needs FFmpeg.
3. Have Claude Code transcribe the video with Whisper and save the transcript with timestamps. Then give it the first prompt below.
4. Read the 3 picks it suggests. Each should make sense with no context and start on a full sentence. Swap any that do not.
5. For each approved pick, have Claude Code do what the Tested edit setup does: trim, make it vertical, burn in that clip's captions and export. Check 3 still frames per clip.
6. Watch every clip with sound before posting. Fix any caption Whisper got wrong, especially names and numbers.

## What to ask the user for

- TRANSCRIPT FILE
- AUDIENCE
- Reels / TikTok / Shorts

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Here is the transcript of my video with timestamps: [TRANSCRIPT FILE].
Who watches: [AUDIENCE]. Where the clips go: [Reels / TikTok / Shorts].

Pick 3 moments of 20 to 45 seconds each that make sense on their own.
For each one give me: start and end time, the first line said, why it works as a clip, and a 6-word on-screen hook.
Start and end on full sentences. Do not cut, export or post anything yet. Wait for me to approve the picks.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Clips that start mid-sentence. The prompt asks for full sentences, but check the first second of each clip.
- Captions with wrong names or numbers from the transcript. Fix the transcript lines before burning them in.
- Posting clips of people who did not agree to it.

## Source

https://www.aisetupsthatwork.com/setups/cut-long-video-into-shorts-with-claude-code/ (AI Setups That Work)
