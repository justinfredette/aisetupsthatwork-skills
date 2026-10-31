---
name: build-anki-flashcards-from-notes-with-ai
description: "Turn Class Notes Into Anki Flashcards With AI. Have AI rewrite your notes as question-answer pairs in a tab-separated format, then import the file through Anki's File menu. Keep cards atomic: one fact per card, and use cloze deletion for fill-in-the-blank style cards. Use when the user asks for help with this job."
---

# Turn Class Notes Into Anki Flashcards With AI

## When to use

Students and self-learners who take notes but never turn them into something they can drill.

## Steps

1. Paste a section of notes into the chat and ask for question-answer pairs, one fact per card, in tab-separated format.
2. For definitions and sequences, ask for cloze deletions instead: the AI wraps hidden text like {{c1::mitochondria}}.
3. Save the output as a plain .txt file in UTF-8. Anki imports comma, semicolon, or tab-separated files; it guesses the separator and you can override it.
4. In Anki, go to File, then Import. Pick the deck, check the field mapping, and import. Duplicates are judged by the first field, so make the first field unique.
5. For cloze cards, make sure the note type is set to Cloze. Cloze tags only work with the Cloze note type, not regular ones.
6. Review the new cards once and fix any bad splits before you start studying. Garbage cards waste every future review.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Turn my study notes into Anki flashcards. Plain and practical.

Notes:
[paste your notes here, one section at a time]

Write the flashcards as tab-separated lines: question[TAB]answer.
Rules:
- One fact per card. Split anything with two facts into two cards.
- Short questions, short answers. No paragraphs on cards.
- For definitions, also give me a cloze version using {{c1::hidden text}} syntax.
- Skip anything that is opinion or filler.
- Show me the cards first. I will review before importing.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Pasting a whole textbook chapter. The AI compresses instead of atomizing. Go section by section.
- Cloze syntax in a Basic note type. It silently will not work: switch the note type to Cloze.
- Encoding issues on import. Save as UTF-8 plain text; Anki recommends LibreOffice over Excel for clean CSV export.
- Two facts on one card. You will mark it "hard" forever. Split it.

## Source

https://www.aisetupsthatwork.com/setups/build-anki-flashcards-from-notes-with-ai/ (AI Setups That Work)
