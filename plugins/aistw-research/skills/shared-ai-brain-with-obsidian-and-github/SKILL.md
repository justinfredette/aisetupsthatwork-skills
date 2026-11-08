---
name: shared-ai-brain-with-obsidian-and-github
description: "Shared AI brain: Obsidian and GitHub. Keep the notes in an Obsidian vault and back it up to a private GitHub repository with the Obsidian Git plugin. Claude Code reads CLAUDE.md files at the start."
---

# Shared AI brain: Obsidian and GitHub

## When to use

Small teams that already use Obsidian and want more than one assistant working from the same notes. It is the step-up from the single-bot memory setup. Keep passwords, client records and anything private out of the vault.

## Steps

1. Start with the single-bot setup linked from this page. Move to this one when a team or several assistants need the same notes.
2. Make a private GitHub repository for the vault. Do not put passwords, API keys or client records in it.
3. In Obsidian, install the Git community plugin. Its documentation says you can clone an existing remote repository, or start a new local repository and optionally push it to a remote.
4. Create three files at the top of the vault: an index of folders, a short rules file for how assistants should write notes, and a log of changes.
5. Claude Code reads CLAUDE.md files at the start of every session, per Anthropic's docs. Put a pointer to the rules file in CLAUDE.md so it follows the same rules.
6. For ChatGPT, Grok Bot and Muse, reading or writing the folder directly is Not stated in sources. Paste the rules file into each one's instructions by hand.
7. Back up on purpose. Obsidian's help says syncing is not a backup, so keep the GitHub copy as the backup and review what changed before you accept it.

## What to ask the user for

- FOLDER NAME

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
You are working in our shared notes folder. Read the rules file and the index first.

Task: [for example: add today's call notes to the right client folder]

Rules:
- Write only inside [FOLDER NAME].
- Do not delete or rewrite existing notes. Add a new note or append at the end.
- Add one line to the change log: date, file, what you did.
- Never write passwords, keys, account numbers or client records.
- Show me a list of the files you changed. I will review before it is committed.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Two assistants editing the same note. Give each its own folder to write in.
- Private information in a repository. Keep the repository private and the vault clean.
- Syncing mistaken for backup. Obsidian's own help warns they are different.

## Source

https://www.aisetupsthatwork.com/setups/shared-ai-brain-with-obsidian-and-github/ (AI Setups That Work)
