---
name: edit-a-video-for-social-with-claude-code
description: "Edit a video for social with Claude. Claude in the chat app can plan your edit but cannot hand you an edited video file. Claude Code can, because it runs tools on a computer. Install FFmpeg, put."
---

# Edit a video for social with Claude

## When to use

Anyone with a video to post who tried asking Claude in chat and got instructions instead of a file. You need Claude Code and FFmpeg on a computer, and you should be okay running one command to install FFmpeg.

## Steps

1. Know why chat alone gets stuck. Claude in the chat app can plan an edit, but it cannot hand you an edited video file. Claude Code can, because it runs tools like FFmpeg on a computer. Its docs say it edits files and runs commands.
2. Install FFmpeg, or ask Claude Code to check whether it is installed and to install it for you. It is free.
3. Make a folder with your video in it. If you have captions, put the .srt file there too. Your phone, CapCut or a transcription tool can make one. No captions yet? See the next setup to make them.
4. Open Claude Code in that folder and paste the prompt below. Fill in the start and end times you want and where the video will be posted.
5. Let it make one short test cut first, then save 3 still frames from it. Look at them before the full export: captions covering faces or text are the most common problem.
6. When the stills look right, have it export the final MP4 at 1080x1920. Watch the whole clip with sound on your phone before you post it.

## What to ask the user for

- FILE NAME
- SRT FILE NAME, or "none"
- START TIME
- END TIME
- Reels / TikTok / Shorts

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are editing a video with FFmpeg in this folder. Do not post or upload anything.

Video: [FILE NAME]
Captions: [SRT FILE NAME, or "none"]
Keep: [START TIME] to [END TIME]
Post to: [Reels / TikTok / Shorts]

1. Check FFmpeg is installed. Tell me the video's size, length and whether it has sound.
2. Trim to the times above.
3. Make it 1080x1920 vertical. Keep the whole frame visible: center it over a blurred copy of itself. Do not crop people out.
4. If there is a caption file, keep only the lines inside my trim, move their times so the clip starts at 0, and burn them in: white, bold, black outline, in the lower part of the frame, never over the video's own text or faces.
5. Fade the sound in and out over about half a second.
6. Export H.264 video with AAC audio, 30 fps, with the fast-start flag for web.
7. Save 3 still frames from the start, middle and end, and show me the file's size, length and resolution.
Do not delete or overwrite my original file.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- In the test, captions that wrapped to three lines covered the bottom of the video. Moving them lower and shrinking the font fixed it.
- A hyphenated word can break across two caption lines. Shorten the line or ask for the break before the word.
- Asking Claude in the chat app for the edited file. It can plan the edit, but only Claude Code can run FFmpeg and hand you the MP4.
- On the first export, captions that wrapped to three lines covered the bottom of the video.
- Keep each caption line short, or ask for a line break before a long hyphenated word.

## Tested

Ran with Claude Code, Nov 4, 2026: a 31-second 16:9 video trimmed to 16.5 seconds, reframed to 1080x1920 over a blurred background, with 8 caption lines from an existing transcript burned in and the audio faded, all with FFmpeg. Transcription was not re-run. Nothing was posted.

The full receipt is on https://www.aisetupsthatwork.com/setups/edit-a-video-for-social-with-claude-code/

## Source

https://www.aisetupsthatwork.com/setups/edit-a-video-for-social-with-claude-code/ (AI Setups That Work)
