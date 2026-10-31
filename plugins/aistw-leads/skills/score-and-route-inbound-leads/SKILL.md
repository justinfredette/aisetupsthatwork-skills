---
name: score-and-route-inbound-leads
description: "Score inbound leads so the best ones reach you first. Define what a good lead looks like, assign points for each trait, and let the AI score every inquiry. Hot leads get your call today. Cold ones wait. Use when the user asks for help with this job."
---

# Score inbound leads so the best ones reach you first

## When to use

Small businesses getting enough inquiries that the good ones sometimes wait behind the bad ones.

## Steps

1. Look at your last 20 to 30 leads. Mark which ones became paying jobs.
2. List the traits the buyers shared: service area, job type, budget signals, how they contacted you, timeline.
3. Turn the traits into a rubric: each trait gets points, up to 100 total. Set a hot threshold (for example, 70+).
4. Put the rubric in a spreadsheet with one row per new lead.
5. For each new inquiry, paste the details plus the prompt below into the AI. It scores the lead against your rubric.
6. Hot leads get a call or quote the same day. Warm leads get the standard process. Cold leads get a polite, slow lane.
7. Review monthly: if hot leads are not buying, your rubric is scoring the wrong traits. Adjust it.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Score this inbound lead against my rubric. Show your work for each trait, then give the total and the routing decision.

My scoring rubric (total 100 points):
- In my service area: [POINTS, e.g. 20]
- Asking for work I actually do: [POINTS, e.g. 20]
- Budget signal present (mentions budget, asks about pricing tiers, commercial client): [POINTS, e.g. 15]
- Decision-maker contacting me directly: [POINTS, e.g. 15]
- Timeline under [X WEEKS]: [POINTS, e.g. 15]
- Repeat customer or referral: [POINTS, e.g. 15]
Hot threshold: [SCORE, e.g. 70]

New lead:
[PASTE THE INQUIRY: their message, source, anything you know]

Return:
1. Points per trait with one-line justification each. Score 0 for anything unknown: do not guess.
2. Total score and HOT / WARM / COLD.
3. Routing: HOT → call today and quote within 24h. WARM → standard quote process. COLD → polite reply, no rush.
4. If WARM or COLD, draft the reply.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Scoring on traits that do not predict buying. Review monthly against actual closes and cut dead traits.
- Letting hot leads sit because the system said hot but you got busy. The score is a promise to act, not a label.
- Overcomplicating it. Six traits and one threshold beats a 20-factor model you abandon in a week.

## Source

https://www.aisetupsthatwork.com/setups/score-and-route-inbound-leads/ (AI Setups That Work)
