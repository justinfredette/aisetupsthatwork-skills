---
name: make-feed-versions-and-a-thumbnail-with-claude-code
description: "Make feed versions and a thumbnail. Ask Claude Code to make a 1080x1920 (9:16), a 1080x1350 (4:5) and a 1080x1080 (1:1) version of your video with FFmpeg, using a blurred copy of the video behind it."
---

# Make feed versions and a thumbnail

## When to use

Anyone who posts the same video to several apps and resizes it by hand each time. You need Claude Code and FFmpeg on a computer, and a finished video.

## Steps

1. Make a folder with a copy of your finished video, and its caption file if it has one. Use a video without burned-in captions if you can, so each size gets captions placed for it.
2. Check each app's help center for the sizes and the upload limit you need. They change often, so this page does not list them.
3. Open Claude Code in that folder and paste the prompt below. Choose crop, blurred background, or test both.
4. If you said test both, look at the two stills it shows you. A crop keeps only the middle of a wide video, so text or people near the sides get cut off.
5. Let it export all three sizes, the thumbnail picks and the smaller copy. Look at the stills it saves from each size: captions should sit inside the picture.
6. Watch each file once on your phone before you post it.

## What to ask the user for

- FILE NAME
- SRT FILE NAME, or "none"
- SIZE

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are making feed versions of a finished video with FFmpeg in this folder. Do not post or upload anything. Never change or delete my original file.

Video: [FILE NAME]
Captions: [SRT FILE NAME, or "none"]
Fit: [crop / blurred background / test both]
Smaller copy: under [SIZE] MB

1. Check FFmpeg is installed. Tell me the video's size, length, frame rate and whether it has sound.
2. If I said test both, make a 5-second test of each fit at 1080x1920, save a still from each, look at them, and tell me what the crop cuts off. Wait for me to pick.
3. Make three versions: 1080x1920 (9:16), 1080x1350 (4:5) and 1080x1080 (1:1), H.264 with AAC sound and fast start.
4. If there is a caption file, burn the captions into each version separately, sized for that frame: white, bold, black outline, inside the picture and clear of the bottom edge, where apps put their own buttons. Save a still from each version with a caption showing and check that no caption is cut off or covers a face or text.
5. Thumbnail: save 3 sharp, well-lit frames as JPG files, look at them, and recommend one.
6. Make a smaller copy of the 9:16 version under my size limit. Tell me the size before and after, and check a still for blocky patches.
7. Check every file (size in pixels, length, frame rate, sound, fast start, file size) and show me a table.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Six full-length versions take a while to encode. If the session stops partway, say "Carry on from where you stopped" and it picks up without redoing finished files.

## Tested

Ran on Claude in a Claude Code session, Nov 5, 2026: a 60-second made-up talking clip became 9:16, 4:5 and 1:1 versions with captions, 3 thumbnails and a 9:16 copy cut from 20.4 MB to 14.3 MB, every file checked for size, length, sound and fast start. Nothing was posted.

The full receipt is on https://www.aisetupsthatwork.com/setups/make-feed-versions-and-a-thumbnail-with-claude-code/

## Source

https://www.aisetupsthatwork.com/setups/make-feed-versions-and-a-thumbnail-with-claude-code/ (AI Setups That Work)
