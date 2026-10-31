---
name: write-song-lyrics-for-suno
description: "Write Song Lyrics That Work in Suno. Use Suno's Custom mode: enter your own lyrics, and (in the Suno app) put the genre, mood, and instruments in the Styles entry. Tip: mark sections like [Verse] and [Chorus] in your lyrics and keep the chorus short and repeatable. Use when the user asks for help with this job."
---

# Write Song Lyrics That Work in Suno

## When to use

Hobbyists making AI music who want songs with real structure instead of mush.

## Steps

1. Decide the song's arc first. A common one is intro, verse, pre-chorus, chorus, verse, bridge, final chorus, outro. Suno's glossary defines the verse, chorus, bridge, and pre-chorus sections.
2. Ask AI for lyrics with each section labeled in square brackets, such as [Intro], [Verse 1], [Chorus], [Bridge], and [Outro]. Tip to try: listen to the result and adjust.
3. Tip to try: keep the chorus short and repeatable and put your strongest line first in each section. Treat this as a starting point and adjust after you listen.
4. Tip to try: add short delivery cues in parentheses, such as (whispered) or (harmonized), only where delivery matters. Remove any cue the song ends up singing.
5. Write the style details separately: genre, mood, vocal style, instruments, and tempo. In the Suno app, Custom mode has a separate place to enter your Styles.
6. In Custom mode, enter the lyrics, enter the styles, add a title, and create. You can enter your own lyrics, or in the Suno app have Suno generate them. Suno's help says the app's Custom mode follows the same steps as the web workflow. Listen, then revise. Tip: if a direction gets sung instead of followed, move it to the style details.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Write Suno-ready song lyrics. Plain and practical.

Theme: [what the song is about]
Genre and mood: [e.g. indie folk, bittersweet]
Perspective: [e.g. first person, looking back]

Write:
1. Full lyrics, with each section named clearly (verse, chorus, bridge).
2. Separate style details for the Styles entry in Suno's Custom mode (in the Suno app): genre, mood, vocal style, instruments, tempo. Keep it short.
3. Keep the lyrics singable: short lines, real rhymes, no tongue-twisters.

Tips to try (adjust after listening):
- Label sections in [square brackets], such as [Verse 1] and [Chorus].
- Keep the chorus short and repeatable, with the strongest line first in each section.
- Add brief cues in (parentheses) only where delivery matters.
- Keep directions that should not be sung out of the lyrics and put them in the style details.

Show me the lyrics first. I will revise before generating.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- A label that gets sung. Try putting each section label on its own line above its lyrics.
- Style notes mixed into the lyrics. Try moving genre, mood, and instrument notes to the Styles entry.
- A direction that becomes sung words, like "make the bridge quieter." Try moving it to the style details.
- A very long chorus that loses its hook. Try shortening it.

## Source

https://www.aisetupsthatwork.com/setups/write-song-lyrics-for-suno/ (AI Setups That Work)
