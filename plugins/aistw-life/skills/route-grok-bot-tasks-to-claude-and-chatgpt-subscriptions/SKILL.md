---
name: route-grok-bot-tasks-to-claude-and-chatgpt-subscriptions
description: "Route Grok Bot tasks to your Claude and ChatGPT subscriptions. Install Claude Code and OpenAI Codex CLIs on Grok Bot’s shared cloud computer, sign in with your own Anthropic and OpenAI subscriptions, then set routing rules so writing, coding, and browser-heavy jobs hit the model you already pay for, without pasting the setup into Codex or Claude Code directly. Use when the user asks for help with this job."
---

# Route Grok Bot tasks to your Claude and ChatGPT subscriptions

## When to use

Grok Bot users who already pay for Claude and/or ChatGPT and want Bots to delegate coding or drafting to those CLIs instead of defaulting back to Grok every time.

## Steps

1. Read each provider’s terms for automated or agent use of a consumer or team subscription. You are routing usage through CLIs on a shared cloud machine.
2. Run the Grok Bot shared-computer security audit setup first; every Bot on your account shares that computer, browser sessions, and credential files.
3. Open one Grok Bot chat (any Bot you trust for setup). Paste the prompt below here, not into Claude Code or Codex terminals.
4. When the Bot offers sign-in links or codes for Claude Code or Codex, complete OAuth or device login yourself; do not paste passwords or API keys into chat.
5. After login, have the Bot run a short smoke test in each CLI (one harmless command each) and confirm which subscription usage pool each draw affects.
6. Set default models in each CLI if prompted, then add explicit routing rules to every Bot’s instructions (e.g. “use Codex for repo edits, Claude Code for refactors, Grok for browser research”).
7. Save the same routing block to shared memory or a /workspace file all Bots are told to read so rules persist across chats. Otherwise Bots tend to revert to Grok-only.
8. Re-test after a day: ask a coding task and a writing task and confirm the Bot names which CLI it used.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
SUBSCRIPTION CLI ROUTING SETUP (run in this Grok Bot chat only, not inside Claude Code or Codex)

Goal: On my Grok Bot shared cloud computer, install and authenticate Claude Code CLI and OpenAI Codex CLI with MY subscriptions, then document routing rules so my Bots use the right tool per job.

Safety and scope:
- Complete the shared-computer security audit mindset first: one computer per user; all Bots share files and CLI logins. Prefer an isolated host or separate Cursor user if I need hard credential separation.
- I will approve every sign-in link, device code, and OAuth screen myself. Never store tokens in plain text files other Bots can read (no committing .env with secrets to /workspace).
- If a CLI is unavailable, not installed, or a usage limit is hit, say so clearly and do the task yourself in Grok instead of failing silently.
- Ask before changing any other Bot's instructions or shared memory.
- When finished, report which Bots you updated and which CLIs authenticated successfully.

Tasks:
1) Check whether Claude Code CLI and Codex CLI are installed; install per official docs if missing.
2) Guide me through subscription login for each CLI I want (I perform login; you verify with a read-only version or status command).
3) Explain whose rate limits and terms apply for each CLI call (Anthropic vs OpenAI vs Grok usage pool). In plain language, citing what you can see from CLI output only.
4) Draft a ROUTING RULES block I can paste into each Bot's instructions, for example:
   - Long-form writing / editing → [Claude Code or Codex per my preference]
   - Repo coding / tests → [Codex or Claude Code]
   - Browser research, connectors, email → Grok Bot native tools
   - If limit hit → notify me and fall back to Grok with a short note
5) Save the ROUTING RULES to shared memory (or a agreed /workspace path) and confirm how other Bots should load it each session.
6) Run one tiny test task per CLI and show me the command output summary (no secrets).

Do not revoke connectors or delete files unless I explicitly approve after this setup.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Paste the setup prompt into Grok Bot chat, not into Codex or Claude Code. Public threads ask “where do I paste this?”
- Bots revert to Grok unless routing rules live in each Bot’s instructions plus shared memory or a file they re-read.
- Subscription usage limits and rate limits are per provider; heavy coding can eat Claude or OpenAI allowance faster than Grok-only work.
- CLI login sessions expire; you may need to re-authenticate on the shared computer after updates or idle timeouts.
- CLI login on a shared cloud computer exposes credentials to every Bot on the account. Isolate the host or audit first.

## Source

https://www.aisetupsthatwork.com/setups/route-grok-bot-tasks-to-claude-and-chatgpt-subscriptions/ (AI Setups That Work)
