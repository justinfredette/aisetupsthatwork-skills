---
name: sync-an-obsidian-vault-on-a-computer-with-github
description: "Sync an Obsidian vault on a computer. Install GitHub Desktop, sign in through the browser, and clone the vault repo into a normal folder, not inside iCloud Drive, OneDrive or Dropbox. Open that."
---

# Sync an Obsidian vault on a computer

## When to use

Small-business owners who already sync the vault on a phone, or plan to, and want the same notes on a computer. GitHub Desktop handles the GitHub login, so there is no token to create on the computer.

## Steps

1. Install GitHub Desktop and sign in. Mac: GitHub Desktop menu, Settings, Accounts, Sign Into GitHub.com. Windows: File, Options, Accounts, Sign Into GitHub.com. Click Continue With Browser and approve in the browser. GitHub Desktop handles the login, so no token is needed.
2. On GitHub, open the vault repo, click Code, then Open with GitHub Desktop. Click Choose and pick a normal folder such as Documents, not inside iCloud Drive, OneDrive or Dropbox, then click Clone. Obsidian's help warns against syncing one vault with two services.
3. Install Git as well. The Git plugin's docs say GitHub Desktop alone is not enough, because the plugin runs the computer's own Git. Windows: install Git for Windows with the default settings; it includes Git Credential Manager. Mac: per GitHub Docs, install Git and Git Credential Manager with Homebrew.
4. Install Obsidian from obsidian.md/download. In the vault switcher, choose Open folder as vault and pick the folder GitHub Desktop cloned.
5. Open Settings, turn on community plugins, then Browse. Search for Git, install the plugin named Git, and enable it. In its settings, turn on Pull on startup and set Auto commit-and-sync interval (minutes) to 30.
6. Run Git: Commit-and-sync once from the command palette. The first time, Git Credential Manager opens a browser window to sign in to GitHub. Approve it once and Git remembers the login.
7. Day to day, GitHub is the hub. Pull before editing (pull on startup does this when Obsidian opens), let auto-sync push, and let one device finish syncing before editing the same note on another.
8. If a conflict is flagged, open source control view, use Keep both on each block, edit the two versions into one note by hand, select Mark resolved, then Commit. Never force push to get past it.
9. Fallback if the plugin cannot sign in: sync with GitHub Desktop instead. Click Fetch origin and Pull origin before editing, then commit and click Push origin when done.

## What to ask the user for

- TYPE OF BUSINESS
- BRACKETS

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I run a small [TYPE OF BUSINESS] and I keep my business second brain in an Obsidian vault that syncs between my phone, my computer and a private GitHub repo. Write a simple folder structure and starter notes I can paste in. Plain Markdown, short notes, no plugins needed.

Write:
1. A folder list with one line on what goes in each folder.
2. A Facts note: business name, services, hours, prices, service area and the tools I use, with [BRACKETS] for me to fill in.
3. A Decisions note: a table with date, decision, why, and what would change my mind.
4. A Log note: one dated line per entry, newest at the top.
5. An Inbox note for quick captures that I sort once a week.
6. A Wins and snags note: what worked, what broke, what to try next.
7. A short README for the top of the vault that says what each note is for, and a one-line habit: open Obsidian, let it pull, then edit.

Rules:
- Never ask me for passwords, tokens, card numbers or client personal details, and add a line to the README saying those stay out of the vault.
- Use file names with no spaces or special characters, so they work on an iPhone, a Mac and Windows.
- Show me the folder list first and wait for my OK before you write the notes.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- The plugin cannot run Git. GitHub Desktop alone is not enough; install Git for Windows, or Git on a Mac.
- The clone landed inside iCloud Drive, OneDrive or Dropbox. Move it out: clone again into a plain folder and open that one as the vault.
- Push rejected because the remote has newer commits. Pull first. The plugin's docs say a rejected push alone is not a conflict.
- A conflict after editing the same note on two devices. Use Keep both, merge the text by hand, Mark resolved, then Commit.

## Source

https://www.aisetupsthatwork.com/setups/sync-an-obsidian-vault-on-a-computer-with-github/ (AI Setups That Work)
