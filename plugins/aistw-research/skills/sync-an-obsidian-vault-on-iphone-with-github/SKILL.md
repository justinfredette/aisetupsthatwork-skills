---
name: sync-an-obsidian-vault-on-iphone-with-github
description: "Sync an Obsidian vault on iPhone. Install Obsidian, create an empty vault stored on the iPhone (not in iCloud), add the community plugin named Git, and give it a fine-grained GitHub token that."
---

# Sync an Obsidian vault on iPhone

## When to use

Small-business owners who keep notes on the phone and want the same notes in a private GitHub repo, with no computer needed. Expect some trial and error: Git on a phone is the weak spot.

## Steps

1. In Safari, sign in to GitHub and create a private repo for the vault: the plus menu, then New repository. Tick the option to add a README so the repo is not empty. GitHub says a private repo is open only to you and people you share it with.
2. Install Obsidian from the App Store and open it. Tap Create new vault, give it a name, and leave Store in iCloud switched off. The Git plugin's docs say not to pick Store in iCloud, and Obsidian's help warns against syncing one vault with two services.
3. In Obsidian, open Settings and tap Turn on community plugins, then Browse. Search for Git, install the plugin named Git, and tap Enable. Obsidian warns that community plugins run third-party code, so add only what the job needs.
4. Back in Safari on GitHub: tap the profile picture, then Settings, Developer settings, Personal access tokens, Fine-grained tokens, Generate new token. Name it after the vault and set Expiration about 90 days out.
5. Under Repository access, pick Only select repositories and choose the vault repo only. Under Permissions, set Contents to Read and write, and Commit statuses to Read and write, the two the plugin's docs list. GitHub adds read access to Metadata by itself. Leave everything else off, then tap Generate token.
6. Copy the token and paste it only into the plugin, in the next step. Never paste it into a chat, a note, an email or a file in the repo.
7. In Obsidian, open Settings, then the Git plugin's options at the bottom under Community plugins. Under Identity, type the GitHub username in Username on your Git server, then create a secret for Git server password or access token and paste the token there. Leave the Advanced settings alone.
8. Open the command palette and run Git: Clone an existing remote repo. Enter the repo's https address with .git on the end, such as https://github.com/your-username/your-vault.git, not the address in the browser bar. Choose the vault root as the folder, then wait for the popup asking to restart Obsidian and restart it.
9. In the plugin settings, fill in Repository author name and Repository author email (mobile Git has no default for them). Turn on Pull on startup and set Auto commit-and-sync interval (minutes) to 30.
10. Test it: write a short note, run Git: Commit-and-sync from the command palette, and check that the note appears in the repo on GitHub. Then paste the prompt below into ChatGPT or Claude for a starter folder layout.
11. Fallback if the clone crashes or never finishes: close Obsidian, clone the repo in the Working Copy app with the same https address, the username, and the token as the password. In the Files app, copy that folder over the empty vault, reopen Obsidian, enable the Git plugin and run Git: Pull. Pushing from inside Working Copy needs its paid Pro upgrade.

## What to ask the user for

- TYPE OF BUSINESS
- BRACKETS

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I run a small [TYPE OF BUSINESS] and I am setting up an Obsidian vault as my business second brain. It syncs to a private GitHub repo from my iPhone, so keep it small: plain Markdown, short notes, no plugins needed.

Write:
1. A simple folder list with one line on what goes in each folder.
2. A Facts note: business name, services, hours, prices, service area and the tools I use, with [BRACKETS] for me to fill in.
3. A Decisions note: a table with date, decision, why, and what would change my mind.
4. A Log note: one dated line per entry, newest at the top.
5. An Inbox note for quick captures that I sort once a week.
6. A Wins and snags note: what worked, what broke, what to try next.
7. A short README for the top of the vault that says what each note is for.

Rules:
- Never ask me for passwords, tokens, card numbers or client personal details, and add a line to the README saying those stay out of the vault.
- Use file names with no spaces or special characters, so they work on an iPhone, a Mac and Windows.
- Show me the folder list first and wait for my OK before you write the notes.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Store in iCloud switched on when the vault was made. Make a new vault stored on the iPhone and clone again.
- Pasting the browser address. The clone needs the https address ending in .git.
- Obsidian crashes or hangs during the clone. The plugin's docs say this depends on the device and free memory; use the Working Copy clone instead.
- Sync stops after about 90 days. The token expired; make a new one with the same settings and replace the secret.
- A conflict after editing the same note on two devices. Open source control view, use Keep both, edit the note into one version, select Mark resolved, then commit.

## Source

https://www.aisetupsthatwork.com/setups/sync-an-obsidian-vault-on-iphone-with-github/ (AI Setups That Work)
