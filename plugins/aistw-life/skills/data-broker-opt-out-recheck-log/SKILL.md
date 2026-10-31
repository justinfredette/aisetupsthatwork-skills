---
name: data-broker-opt-out-recheck-log
description: "Data broker opt-out recheck log. This is not legal advice. Keep a log of each people search site and data broker you opted out of, with dates, and recheck it on a schedule you set. The FTC says your information can reappear when public records change. The sources give no recheck interval. California residents can also use the state's free DROP request. Use when the user asks for help with this job."
---

# Data broker opt-out recheck log

## When to use

People who get scam calls or texts with their real details in them and want a repeatable way to remove and recheck their listings. This is not legal advice. Do not paste your SSN, full address, account numbers or other identifying details into a chatbot.

## Steps

1. Search your own name, with your city, on a few people search sites. The FTC says people search sites compile public records and social media into reports they sell.
2. Start the log with columns for site, link to your listing, date you opted out, confirmation, and next check date. Keep private details out of it: site names, dates and status only.
3. Opt out on each site. The FTC says most people search sites have a way to opt out, you can do it one by one for free or pay a service, and some will ask for information to verify your identity.
4. If you live in California, also submit one request in DROP, the state's free Delete Request and Opt-out Platform. One request goes to over 600 registered data brokers. Brokers began processing requests August 1, 2026, and must check DROP at least every 45 days. Status updates can take up to 90 days.
5. On each recheck date you set, search your name again on the sites in your log and update it. The FTC says information can reappear for sale if your public records change, and can still show in relatives' or neighbors' reports. Re-submit any listing that came back.

## Prompt

Fill the [BRACKETED] parts with the user, then follow this prompt:

```
Help me keep a data broker opt-out log. This is not legal advice.

I will give you only site names, dates and status. I will not give you my SSN, full address or account numbers. If I paste any, tell me to remove it.

Sites I have checked: [site name, listing found yes or no, date opted out]
My recheck interval: [days, my choice]
Today's date: [DATE]

1. Turn this into a table: site, listing found, date opted out, confirmation received, next check date (my last check plus my interval).
2. List the sites due for a recheck now or soon.
3. Give me a short checklist for each recheck: search my name and city, note whether the listing is back, re-submit the opt-out if it is.

Show me the table first. Do not invent opt-out links. If I need a link, tell me to find it on the site itself.
```

## Guardrails

- Draft first and show the user. Never send, post, pay, book, cancel or delete without the user's explicit approval of that exact action.
- Use only facts the user gives you or that you can cite. If something is missing, ask instead of guessing.

## Common snags

- Treating the opt-out as permanent. The FTC says listings can come back, which is why the log has a next check date.
- Pasting private details into the chat. Keep to site names, dates and status.
- Expecting DROP to cover people search sites outside what registered data brokers do. DROP covers registered data brokers, and only California residents can use it.

## Source

https://www.aisetupsthatwork.com/setups/data-broker-opt-out-recheck-log/ (AI Setups That Work)
