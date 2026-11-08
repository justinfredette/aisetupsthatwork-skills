---
name: add-captions-from-speech-with-claude-code
description: "Add captions from speech with Claude. Install Whisper, a free speech-to-text tool that runs on your computer, and ask Claude Code to transcribe your video into a caption file (.srt). Give it the."
---

# Add captions from speech with Claude

## When to use

Anyone posting talking videos who wants captions without paying for a captions app. You need Claude Code, FFmpeg and Python on a computer, and Whisper downloads its speech model the first time it runs.

## Steps

1. Make a folder with a copy of your video in it. Write down the names, brand words and places said in it, spelled the way you want them.
2. Open Claude Code in that folder and paste the prompt below. Fill in the file name, the names list and whether you want the captions burned in or kept as a file.
3. If Whisper is missing, Claude Code gives you the install command and waits. Whisper's own page gives pip install -U openai-whisper and says it needs FFmpeg. The first run downloads the speech model, so it needs the internet once.
4. Read the list of names, numbers, prices and dates it flags, and check each one against the sound. Speech-to-text gets these wrong most often. Tell it what to fix.
5. Pick the finish. Burned-in captions show everywhere, including on apps that play muted. A separate .srt file can be uploaded next to the video where an app accepts one, and viewers can switch it off.
6. Watch the captioned video once with the sound on, reading along, before you post it.

## What to ask the user for

- FILE NAME
- LANGUAGE
- NAMES, BRANDS, PLACES

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are making captions for a video in this folder. Do not post or upload anything. Never change or delete my original file.

Video: [FILE NAME]
Language: [LANGUAGE]
Names and words to spell right: [NAMES, BRANDS, PLACES]
Finish: [burn them in / keep them as a file / both]

1. Check that FFmpeg and Whisper (openai-whisper or faster-whisper) are installed. If Whisper is missing, tell me the install command and wait for my yes.
2. Transcribe the talking with the small model into a new .srt file next to the video. Give Whisper my names list as its initial prompt so it spells them right.
3. Keep each caption to 2 short lines at most.
4. List every name, number, price and date in the captions with its time, and flag any word that looks misheard. Fix spellings from my names list. Show me the list and wait for my OK.
5. To burn them in: make a new MP4 with the captions drawn on: white, bold, black outline, near the bottom but inside the picture. Save 3 still frames with a caption showing and look at them.
6. To keep them as a file: keep the .srt, and also make a copy of the video with the captions as a track viewers can switch on and off, without re-encoding the picture.
7. Tell me the files you made, how many captions there are, and the video's length.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Source

https://www.aisetupsthatwork.com/setups/add-captions-from-speech-with-claude-code/ (AI Setups That Work)
