---
name: build-a-lead-gen-site-with-an-ai-bot
description: "Build a lead-gen site with an AI bot. Use an AI coding or copy assistant to draft a simple landing page and contact form for a local service business, then you approve hosting spend, publish, and wire leads to email or a sheet. No scraped lists and no texting leads without consent. Use when the user asks for help with this job."
---

# Build a lead-gen site with an AI bot

## When to use

Owner-operators who need a credible “request a quote” page without hiring a full agency first.

## Steps

1. Write honest proof points only (license, service area, real reviews you link to).
2. Run the prompt for outline + homepage copy + form fields.
3. Generate or paste HTML/components; remove any fake testimonials the model suggests.
4. You choose and pay for hosting; you click publish.
5. Connect the form to an inbox or sheet; send a test submission yourself.
6. Add privacy policy and sponsor/AI disclosure if the site mentions automated chat.
7. Optional: add a simple FAQ and service-area paragraph for local SEO. No keyword stuffing.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
I run a local [service type] business in [city/region]. Help me spec a simple lead-gen landing page and contact form. No automations that message leads without my approval.

Business: [name or working title]
Service in one sentence: [what you do]
Proof I can honestly claim: [license, insurance, years, review links. Only what I provide]
Form fields: [name, phone, email, job address, photos, preferred time, etc.]
Brand tone: [plain / friendly / professional]
Target host or stack: [Carrd / Framer / static HTML / other]

Deliver:
1) Page outline (hero, services, service area, proof, FAQ, form, privacy note).
2) Draft homepage copy I can paste into my builder.
3) Form labels + validation hints (required vs optional).
4) Pre-publish checklist: approve hosting cost, connect form to [email/CRM], privacy policy, test submit, no scraped lists, no cold SMS.

Guardrails: no fake testimonials, no purchased lead lists, no auto-texting visitors, no charging my card. I approve spend and publish.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Generated sites may include placeholder phone numbers or fake reviews. Delete before publish.
- Auto-deploy hooks can publish before you review. Keep staging and manual promote.
- Contact forms need spam protection (honeypot or CAPTCHA) you configure separately.
- Check the page at phone width before publishing.

## Source

https://www.aisetupsthatwork.com/setups/build-a-lead-gen-site-with-an-ai-bot/ (AI Setups That Work)
