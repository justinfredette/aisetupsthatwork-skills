---
name: debug-a-python-script-with-ai
description: "Debug a Python script with AI. Paste the full error message plus the code around the failing line. The AI reads the traceback, names the likely cause in plain words, and suggests one fix. You test the fix before moving on. Use when the user asks for help with this job."
---

# Debug a Python script with AI

## When to use

Hobbyists and non-programmers with a Python script that broke and an error message they cannot read.

## Steps

1. Copy the entire traceback, not just the last line. The last line names the error, but the lines above show where it happened.
2. Learn the one skill that makes everything else work: read a traceback from bottom to top. The final line is the error message with the exception name; moving up shows the calls from most recent to least recent, each with filename, line number, and the code that ran.
3. Paste the traceback plus the surrounding code into the prompt. Ask for the cause in plain words first, then one fix.
4. Check the cause against the common list before accepting it. Typical culprits: NameError (undefined name), TypeError (wrong type for the operation, like 1 + "1"), ValueError (bad value, like int("a")), IndexError, KeyError, ZeroDivisionError, ImportError, AttributeError.
5. Apply exactly one fix and run the script again. If the error changes, you made progress; paste the new traceback and repeat.
6. If the AI’s fix does not work after two tries, ask it to explain what the code is trying to do line by line instead. Understanding beats guessing.
7. When it works, ask the AI to summarize what was wrong in one sentence and save it. Error patterns repeat, and your future self will thank you.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me debug my Python script. I am not a programmer, so explain in plain words.

The full traceback:
[paste the ENTIRE error output here]

The code around the failing line:
[paste about 20 lines, marking which line the traceback points to]

What the script is supposed to do: [e.g. "read a CSV of expenses and print monthly totals"]

Give me:
1. What the error means in one plain sentence.
2. The most likely cause, pointing at the specific line.
3. ONE fix to try. Just one.
4. How to check whether the fix worked.

Rules:
- Do not rewrite my whole script. One fix at a time.
- If you are not sure, say so and give me the two most likely causes.

I will test each fix before asking for the next step.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Pasting only the last line of the error. The AI needs the full traceback; the location lines above the message are where the diagnosis lives.
- Accepting a full rewrite. Rewrites introduce new bugs you cannot evaluate. One targeted fix, tested, then the next.
- The AI confidently naming the wrong cause. If two fixes fail, stop and ask for a line-by-line explanation instead of a third guess.

## Source

https://www.aisetupsthatwork.com/setups/debug-a-python-script-with-ai/ (AI Setups That Work)
