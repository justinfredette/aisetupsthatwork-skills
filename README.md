# AI Setups That Work: Claude skills

297 Claude skills for small business, work and home, grouped by job. Each one is a setup from [aisetupsthatwork.com](https://www.aisetupsthatwork.com/): when to use it, the steps, the prompt, guardrails and known snags. Skills marked Tested were run for real; the rest are researched.

This repo is generated from the site. Please open issues here, but changes land on the site first.

## The Small Business OS

Think of this repo as a small business with 9 departments. Each department is a plugin, and each skill is one job with the steps, the prompt and the guardrails.

```
aisetupsthatwork-skills/
|-- aistw-starter/       5 skills   Five Tested jobs: missed-call texts, quotes, quote follow-ups, who owes you what, and writing in your voice.
|-- aistw-leads/        32 skills   Capture leads, follow up on quotes, and win back cold prospects.
|-- aistw-invoicing/    29 skills   Chase late invoices, sort bills and receipts, and track spend.
|-- aistw-inbox/        14 skills   Triage email, draft replies, and turn messages into action lists.
|-- aistw-scheduling/   16 skills   Appointment reminders, meeting prep, and calendar cleanup.
|-- aistw-operations/   44 skills   Status updates, call summaries, SOPs, and day-to-day business admin.
|-- aistw-life/         57 skills   Household paperwork, weekly briefs, trips, and personal admin.
|-- aistw-research/     87 skills   Research briefs, comparisons, and content drafts with sources.
`-- aistw-reviews/      18 skills   Ask for reviews, reply to them, and spot patterns in feedback.
```

Install one department or all of them (below). Nothing sends, posts or pays without your approval.

## Start here: the Small Business Starter

`aistw-starter` holds 5 Tested jobs for a small business: missed-call texts, quotes, quote follow-ups, who owes you what, and writing in your voice. Each one was run for real, and its known snags are in the skill. The same skills also sit in their job plugins, so you only need one copy.

```
/plugin marketplace add justinfredette/aisetupsthatwork-skills
/plugin install aistw-starter@aisetupsthatwork
```

No Claude Code? The Starter is also a free download for the Claude app, plus a paste-in version for any plan: https://www.aisetupsthatwork.com/claude/#add-starter

## Install in Claude Code

Add the marketplace once:

```
/plugin marketplace add justinfredette/aisetupsthatwork-skills
```

Then install the jobs you want, for example:

```
/plugin install aistw-leads@aisetupsthatwork
```

Or all of them:

```
/plugin install aistw-starter@aisetupsthatwork
/plugin install aistw-leads@aisetupsthatwork
/plugin install aistw-invoicing@aisetupsthatwork
/plugin install aistw-inbox@aisetupsthatwork
/plugin install aistw-scheduling@aisetupsthatwork
/plugin install aistw-operations@aisetupsthatwork
/plugin install aistw-life@aisetupsthatwork
/plugin install aistw-research@aisetupsthatwork
/plugin install aistw-reviews@aisetupsthatwork
```

## Install in the Claude app

Every setup page has a **Download skill (.zip)** button. In Claude, turn on code execution in Settings > Capabilities, then go to Customize > Skills, click +, choose Create skill, then Upload a skill, and pick the .zip. Steps from Claude's help center: https://support.claude.com/en/articles/12512180-use-skills-in-claude. Browse them all at https://www.aisetupsthatwork.com/library/?type=skill

## Plugins

| Plugin | Skills | What it covers |
| --- | --- | --- |
| `aistw-starter` | 5 | Five Tested jobs: missed-call texts, quotes, quote follow-ups, who owes you what, and writing in your voice. |
| `aistw-leads` | 32 | Capture leads, follow up on quotes, and win back cold prospects. |
| `aistw-invoicing` | 29 | Chase late invoices, sort bills and receipts, and track spend. |
| `aistw-inbox` | 14 | Triage email, draft replies, and turn messages into action lists. |
| `aistw-scheduling` | 16 | Appointment reminders, meeting prep, and calendar cleanup. |
| `aistw-operations` | 44 | Status updates, call summaries, SOPs, and day-to-day business admin. |
| `aistw-life` | 57 | Household paperwork, weekly briefs, trips, and personal admin. |
| `aistw-research` | 87 | Research briefs, comparisons, and content drafts with sources. |
| `aistw-reviews` | 18 | Ask for reviews, reply to them, and spot patterns in feedback. |

## Skills

### aistw-starter

- [Text back missed callers with a booking link](https://www.aisetupsthatwork.com/setups/text-back-missed-callers-with-a-booking-link/) (Tested): `text-back-missed-callers-with-a-booking-link`
- [Turn messy job notes into a clean quote](https://www.aisetupsthatwork.com/setups/write-a-quote-from-messy-notes/) (Tested): `write-a-quote-from-messy-notes`
- [Follow up on quotes that went cold](https://www.aisetupsthatwork.com/setups/follow-up-on-quotes-gone-cold/) (Tested): `follow-up-on-quotes-gone-cold`
- [Track who owes you what, every week](https://www.aisetupsthatwork.com/setups/track-who-owes-you-what/) (Tested): `track-who-owes-you-what`
- [Make AI write in your voice](https://www.aisetupsthatwork.com/setups/make-ai-write-in-your-voice/) (Tested): `make-ai-write-in-your-voice`

### aistw-leads

- [Answer customers with Shopify Inbox](https://www.aisetupsthatwork.com/setups/answer-customers-with-shopify-inbox/): `answer-customers-with-shopify-inbox`
- [Ask happy customers for referrals](https://www.aisetupsthatwork.com/setups/ask-happy-customers-for-referrals/): `ask-happy-customers-for-referrals`
- [Batch a week of social posts in one sitting](https://www.aisetupsthatwork.com/setups/batch-a-week-of-social-posts-with-ai/): `batch-a-week-of-social-posts-with-ai`
- [Build a lead-gen site with an AI bot](https://www.aisetupsthatwork.com/setups/build-a-lead-gen-site-with-an-ai-bot/) (Tested): `build-a-lead-gen-site-with-an-ai-bot`
- [Build a local prospect list with AI help](https://www.aisetupsthatwork.com/setups/build-a-local-prospect-list-with-ai/): `build-a-local-prospect-list-with-ai`
- [Check a Client Request Against Your Contract](https://www.aisetupsthatwork.com/setups/check-a-client-request-against-your-contract/): `check-a-client-request-against-your-contract`
- [Check for an existing reply before an agent answers](https://www.aisetupsthatwork.com/setups/check-for-an-existing-reply-before-an-agent-answers-a-lead/): `check-for-an-existing-reply-before-an-agent-answers-a-lead`
- [Etsy listing titles, tags, and descriptions with AI](https://www.aisetupsthatwork.com/setups/etsy-listing-titles-tags-and-descriptions-with-ai/): `etsy-listing-titles-tags-and-descriptions-with-ai`
- [How to use AI to find new clients for a small cleaning business](https://www.aisetupsthatwork.com/setups/find-new-clients-for-a-cleaning-business-with-ai/): `find-new-clients-for-a-cleaning-business-with-ai`
- [Find warm leads from job posts with AI](https://www.aisetupsthatwork.com/setups/find-warm-leads-from-job-posts-with-ai/): `find-warm-leads-from-job-posts-with-ai`
- [Find your first customers with AI research](https://www.aisetupsthatwork.com/setups/find-your-first-customers-with-ai-research/): `find-your-first-customers-with-ai-research`
- [Follow up on quotes that went cold](https://www.aisetupsthatwork.com/setups/follow-up-on-quotes-gone-cold/) (Tested): `follow-up-on-quotes-gone-cold`
- [Build a freelance portfolio with no clients](https://www.aisetupsthatwork.com/setups/freelance-portfolio-with-no-clients/): `freelance-portfolio-with-no-clients`
- [Land Your First Upwork Client](https://www.aisetupsthatwork.com/setups/land-your-first-upwork-client/): `land-your-first-upwork-client`
- [Never drop a networking contact again](https://www.aisetupsthatwork.com/setups/networking-follow-up-system/): `networking-follow-up-system`
- [Make a one-page leave-behind for pitches](https://www.aisetupsthatwork.com/setups/one-page-leave-behind-for-pitches/): `one-page-leave-behind-for-pitches`
- [Plan a seasonal promotion without the scramble](https://www.aisetupsthatwork.com/setups/plan-a-seasonal-promotion/): `plan-a-seasonal-promotion`
- [Practice a sales call with AI](https://www.aisetupsthatwork.com/setups/practice-a-sales-call-with-ai/): `practice-a-sales-call-with-ai`
- [Build a pricing sheet that answers objections](https://www.aisetupsthatwork.com/setups/pricing-sheet-that-answers-objections/): `pricing-sheet-that-answers-objections`
- [Qualify leads with five questions](https://www.aisetupsthatwork.com/setups/qualify-leads-with-five-questions/) (Tested): `qualify-leads-with-five-questions`
- [Review a Freelance Contract with ChatGPT or Claude](https://www.aisetupsthatwork.com/setups/review-a-freelance-contract-with-chatgpt/): `review-a-freelance-contract-with-chatgpt`
- [Say no to scope creep without losing the client](https://www.aisetupsthatwork.com/setups/say-no-to-scope-creep-without-losing-the-client/): `say-no-to-scope-creep-without-losing-the-client`
- [Score inbound leads so the best ones reach you first](https://www.aisetupsthatwork.com/setups/score-and-route-inbound-leads/): `score-and-route-inbound-leads`
- [Spot a fake client inquiry with AI](https://www.aisetupsthatwork.com/setups/spot-a-fake-client-inquiry-with-ai/): `spot-a-fake-client-inquiry-with-ai`
- [Text back missed callers with a booking link](https://www.aisetupsthatwork.com/setups/text-back-missed-callers-with-a-booking-link/) (Tested): `text-back-missed-callers-with-a-booking-link`
- [Track the bids you sent and follow up](https://www.aisetupsthatwork.com/setups/track-sent-bids-and-follow-up/): `track-sent-bids-and-follow-up`
- [Sort trade show leads before they go cold](https://www.aisetupsthatwork.com/setups/triage-trade-show-leads-fast/): `triage-trade-show-leads-fast`
- [Turn a finished job into a case study](https://www.aisetupsthatwork.com/setups/turn-a-finished-job-into-a-case-study/): `turn-a-finished-job-into-a-case-study`
- [Welcome email sequence in Kit](https://www.aisetupsthatwork.com/setups/welcome-email-sequence-in-kit/): `welcome-email-sequence-in-kit`
- [Win back past customers with email](https://www.aisetupsthatwork.com/setups/win-back-past-customers-with-email/): `win-back-past-customers-with-email`
- [Turn messy job notes into a clean quote](https://www.aisetupsthatwork.com/setups/write-a-quote-from-messy-notes/) (Tested): `write-a-quote-from-messy-notes`
- [Write a services page that converts](https://www.aisetupsthatwork.com/setups/write-a-services-page-that-converts/): `write-a-services-page-that-converts`

### aistw-invoicing

- [Audit Your Credit Card Statement with ChatGPT](https://www.aisetupsthatwork.com/setups/audit-your-credit-card-statement-with-chatgpt/): `audit-your-credit-card-statement-with-chatgpt`
- [Audit your business subscriptions in one afternoon](https://www.aisetupsthatwork.com/setups/business-subscription-audit/): `business-subscription-audit`
- [Calculate salon commission pay with AI](https://www.aisetupsthatwork.com/setups/calculate-salon-commission-pay-with-ai/): `calculate-salon-commission-pay-with-ai`
- [Cancel Subscriptions and Ask for Refunds with ChatGPT](https://www.aisetupsthatwork.com/setups/cancel-subscriptions-and-get-refunds-with-chatgpt/): `cancel-subscriptions-and-get-refunds-with-chatgpt`
- [Decide whether to take cards, cash, or checks](https://www.aisetupsthatwork.com/setups/cash-vs-card-vs-check-fees/): `cash-vs-card-vs-check-fees`
- [Catch up months of books before your bookkeeper](https://www.aisetupsthatwork.com/setups/catch-up-months-of-books-before-your-bookkeeper/): `catch-up-months-of-books-before-your-bookkeeper`
- [Chase late payments without the awkward email](https://www.aisetupsthatwork.com/setups/chase-late-payments-with-ai/) (Tested): `chase-late-payments-with-ai`
- [Set Up Contractor W-9s and 1099s Without the Scramble](https://www.aisetupsthatwork.com/setups/contractor-w-9-and-1099-setup/): `contractor-w-9-and-1099-setup`
- [How to Use AI to Create a Budget (Copy-Paste Prompt)](https://www.aisetupsthatwork.com/setups/create-a-budget-with-ai/): `create-a-budget-with-ai`
- [Cut home energy use with AI](https://www.aisetupsthatwork.com/setups/cut-home-energy-use-with-ai/): `cut-home-energy-use-with-ai`
- [Estimate your quarterly taxes without the panic](https://www.aisetupsthatwork.com/setups/estimate-quarterly-taxes-freelancer/): `estimate-quarterly-taxes-freelancer`
- [Estimate to invoice in QuickBooks](https://www.aisetupsthatwork.com/setups/estimate-to-invoice-in-quickbooks/): `estimate-to-invoice-in-quickbooks`
- [Sort your expenses into tax-ready categories](https://www.aisetupsthatwork.com/setups/expense-categories-for-tax-time/): `expense-categories-for-tax-time`
- [File an FSA or HSA Claim with ChatGPT](https://www.aisetupsthatwork.com/setups/file-an-fsa-or-hsa-claim-with-chatgpt/): `file-an-fsa-or-hsa-claim-with-chatgpt`
- [Find Unclaimed Money in Your Name with ChatGPT](https://www.aisetupsthatwork.com/setups/find-unclaimed-money-with-chatgpt/): `find-unclaimed-money-with-chatgpt`
- [Build an invoice template that gets paid faster](https://www.aisetupsthatwork.com/setups/invoice-template-that-gets-paid-faster/): `invoice-template-that-gets-paid-faster`
- [Keep finances private when using AI for books](https://www.aisetupsthatwork.com/setups/keep-finances-private-when-using-ai-for-bookkeeping/): `keep-finances-private-when-using-ai-for-bookkeeping`
- [Limit what staff and bots can see in your books](https://www.aisetupsthatwork.com/setups/limit-what-staff-and-bots-can-see-in-your-books/): `limit-what-staff-and-bots-can-see-in-your-books`
- [Keep a mileage log without the notebook](https://www.aisetupsthatwork.com/setups/mileage-log-without-notebook/): `mileage-log-without-notebook`
- [Do a month of bookkeeping in one sitting](https://www.aisetupsthatwork.com/setups/monthly-bookkeeping-one-sitting/): `monthly-bookkeeping-one-sitting`
- [Negotiate a Lower Internet Bill with ChatGPT](https://www.aisetupsthatwork.com/setups/negotiate-a-lower-internet-bill-with-chatgpt/): `negotiate-a-lower-internet-bill-with-chatgpt`
- [Negotiate a Medical Bill with ChatGPT](https://www.aisetupsthatwork.com/setups/negotiate-a-medical-bill-with-chatgpt/): `negotiate-a-medical-bill-with-chatgpt`
- [Pay yourself first as a solo operator](https://www.aisetupsthatwork.com/setups/pay-yourself-first-solo-operator/): `pay-yourself-first-solo-operator`
- [Write payment terms that actually protect you](https://www.aisetupsthatwork.com/setups/payment-terms-that-protect-you/): `payment-terms-that-protect-you`
- [Price a job so you do not lose money on it](https://www.aisetupsthatwork.com/setups/price-a-job-without-losing-money/): `price-a-job-without-losing-money`
- [Ask Better Retirement Questions With AI](https://www.aisetupsthatwork.com/setups/retirement-planning-questions-with-ai/): `retirement-planning-questions-with-ai`
- [Separate your business and personal money for good](https://www.aisetupsthatwork.com/setups/separate-business-and-personal-money/): `separate-business-and-personal-money`
- [Track who owes you what, every week](https://www.aisetupsthatwork.com/setups/track-who-owes-you-what/) (Tested): `track-who-owes-you-what`
- [Build your year-end tax document checklist](https://www.aisetupsthatwork.com/setups/year-end-tax-document-checklist/): `year-end-tax-document-checklist`

### aistw-inbox

- [AI promise tracker for your business](https://www.aisetupsthatwork.com/setups/ai-promise-tracker-for-your-business/): `ai-promise-tracker-for-your-business`
- [Answer Airbnb guest questions with AI](https://www.aisetupsthatwork.com/setups/answer-airbnb-guest-questions-with-ai/): `answer-airbnb-guest-questions-with-ai`
- [Answer order status emails with AI](https://www.aisetupsthatwork.com/setups/answer-order-status-emails-with-ai/): `answer-order-status-emails-with-ai`
- [Answer repeat customer questions automatically](https://www.aisetupsthatwork.com/setups/answer-repeat-customer-questions-automatically/): `answer-repeat-customer-questions-automatically`
- [Write Cold Outreach That Does Not Sound Like Spam](https://www.aisetupsthatwork.com/setups/cold-outreach-that-doesnt-sound-like-spam/): `cold-outreach-that-doesnt-sound-like-spam`
- [Condense a 50-Message Thread Before a Meeting](https://www.aisetupsthatwork.com/setups/condense-50-message-thread-before-meeting/): `condense-50-message-thread-before-meeting`
- [Connect notes, tasks and email to AI](https://www.aisetupsthatwork.com/setups/connect-notetaker-tasks-and-email-to-ai/): `connect-notetaker-tasks-and-email-to-ai`
- [Draft the Hard Emails: Saying No and Following Up Twice](https://www.aisetupsthatwork.com/setups/draft-difficult-emails-with-ai/): `draft-difficult-emails-with-ai`
- [Give each AI agent its own email](https://www.aisetupsthatwork.com/setups/give-each-ai-agent-its-own-mailbox/): `give-each-ai-agent-its-own-mailbox`
- [Build a Template Bank for Repeat Business Emails](https://www.aisetupsthatwork.com/setups/small-business-email-templates/): `small-business-email-templates`
- [Turn a Long Email Thread Into a Decision Summary](https://www.aisetupsthatwork.com/setups/summarize-long-email-thread-decision/): `summarize-long-email-thread-decision`
- [Turn a Week of School Emails Into One Summary](https://www.aisetupsthatwork.com/setups/summarize-school-emails-for-parents/): `summarize-school-emails-for-parents`
- [Turn a messy draft into a clear, polite work email](https://www.aisetupsthatwork.com/setups/turn-messy-draft-into-polite-work-email/): `turn-messy-draft-into-polite-work-email`
- [Triage Your Newsletters Once a Week](https://www.aisetupsthatwork.com/setups/weekly-newsletter-triage/): `weekly-newsletter-triage`

### aistw-scheduling

- [Meeting notes to action items and follow-up email](https://www.aisetupsthatwork.com/setups/ai-meeting-notes-to-action-items/): `ai-meeting-notes-to-action-items`
- [Write appointment reminder texts for your small business](https://www.aisetupsthatwork.com/setups/appointment-reminder-texts-small-business/): `appointment-reminder-texts-small-business`
- [Audit your calendar with AI and take hours back](https://www.aisetupsthatwork.com/setups/audit-your-calendar-with-ai/): `audit-your-calendar-with-ai`
- [Plan project deadlines backwards from launch](https://www.aisetupsthatwork.com/setups/backwards-project-deadlines-from-launch/): `backwards-project-deadlines-from-launch`
- [Batch your dentist, doctor, and car appointments](https://www.aisetupsthatwork.com/setups/batch-appointments-dentist-doctor-car/): `batch-appointments-dentist-doctor-car`
- [Book quote calls with Calendly](https://www.aisetupsthatwork.com/setups/book-quote-calls-with-calendly/): `book-quote-calls-with-calendly`
- [Coordinate a volunteer or team schedule without the group-text chaos](https://www.aisetupsthatwork.com/setups/coordinate-team-volunteer-schedule/): `coordinate-team-volunteer-schedule`
- [Plan a family calendar with two working parents](https://www.aisetupsthatwork.com/setups/family-calendar-plan-two-working-parents/): `family-calendar-plan-two-working-parents`
- [Build a morning routine that survives kids](https://www.aisetupsthatwork.com/setups/morning-routine-that-survives-kids/): `morning-routine-that-survives-kids`
- [Plan a month of social media on one calendar](https://www.aisetupsthatwork.com/setups/plan-a-month-of-social-media-with-ai/): `plan-a-month-of-social-media-with-ai`
- [Schedule bill payments so nothing is late](https://www.aisetupsthatwork.com/setups/schedule-bill-payments-with-ai/): `schedule-bill-payments-with-ai`
- [Schedule deep-work blocks that actually hold](https://www.aisetupsthatwork.com/setups/schedule-deep-work-blocks-with-ai/): `schedule-deep-work-blocks-with-ai`
- [Time-block your week with AI](https://www.aisetupsthatwork.com/setups/time-block-your-week-with-ai/): `time-block-your-week-with-ai`
- [Let only urgent calls through mid-appointment](https://www.aisetupsthatwork.com/setups/triage-calls-while-you-are-with-a-client/): `triage-calls-while-you-are-with-a-client`
- [Plan a wedding or big event timeline with AI](https://www.aisetupsthatwork.com/setups/wedding-event-timeline-with-ai/): `wedding-event-timeline-with-ai`
- [Build a year-long home maintenance calendar](https://www.aisetupsthatwork.com/setups/yearly-home-maintenance-calendar/): `yearly-home-maintenance-calendar`

### aistw-operations

- [Barber Client Cut Record, ChatGPT](https://www.aisetupsthatwork.com/setups/barber-client-cut-preference-record-with-chatgpt/): `barber-client-cut-preference-record-with-chatgpt`
- [Barbershop Walk-In Register, ChatGPT](https://www.aisetupsthatwork.com/setups/barbershop-appointment-walk-in-register-with-chatgpt/): `barbershop-appointment-walk-in-register-with-chatgpt`
- [Chair Rental Register, ChatGPT](https://www.aisetupsthatwork.com/setups/barbershop-chair-rental-agreement-register-with-chatgpt/): `barbershop-chair-rental-agreement-register-with-chatgpt`
- [Barbershop Sanitation Log, ChatGPT](https://www.aisetupsthatwork.com/setups/barbershop-tool-station-sanitation-log-with-chatgpt/): `barbershop-tool-station-sanitation-log-with-chatgpt`
- [Build a knowledge base your AI answers from](https://www.aisetupsthatwork.com/setups/build-a-business-knowledge-base-your-ai-answers-from/): `build-a-business-knowledge-base-your-ai-answers-from`
- [Cap what your AI agent can spend](https://www.aisetupsthatwork.com/setups/cap-what-your-ai-agent-can-spend/): `cap-what-your-ai-agent-can-spend`
- [Catch a long agent run drifting off course](https://www.aisetupsthatwork.com/setups/catch-a-long-agent-run-drifting-off-course/): `catch-a-long-agent-run-drifting-off-course`
- [Check your agent did the follow-up it promised](https://www.aisetupsthatwork.com/setups/check-your-agent-did-the-follow-up-it-promised/): `check-your-agent-did-the-follow-up-it-promised`
- [Clean up your agent's long-term memory](https://www.aisetupsthatwork.com/setups/clean-up-your-agents-long-term-memory/): `clean-up-your-agents-long-term-memory`
- [Connect your bot to a CRM the safe way](https://www.aisetupsthatwork.com/setups/connect-your-bot-to-a-crm-the-safe-way/) (Tested): `connect-your-bot-to-a-crm-the-safe-way`
- [Find which bot routine burns your usage](https://www.aisetupsthatwork.com/setups/find-which-bot-routine-burns-your-usage/) (Tested): `find-which-bot-routine-burns-your-usage`
- [Fix an App Store rejection with AI](https://www.aisetupsthatwork.com/setups/fix-an-app-store-rejection-with-ai/): `fix-an-app-store-rejection-with-ai`
- [Fix wrong answers from your own documents](https://www.aisetupsthatwork.com/setups/fix-wrong-answers-from-your-own-documents/): `fix-wrong-answers-from-your-own-documents`
- [Give each staff member their own bot safely](https://www.aisetupsthatwork.com/setups/give-each-staff-member-their-own-bot-safely/) (Tested): `give-each-staff-member-their-own-bot-safely`
- [Gym Equipment Service Log, ChatGPT](https://www.aisetupsthatwork.com/setups/gym-equipment-maintenance-inspection-log-with-chatgpt/): `gym-equipment-maintenance-inspection-log-with-chatgpt`
- [Gym Cleaning Log, ChatGPT](https://www.aisetupsthatwork.com/setups/gym-facility-cleaning-log-with-chatgpt/): `gym-facility-cleaning-log-with-chatgpt`
- [Gym Check-in Register, ChatGPT](https://www.aisetupsthatwork.com/setups/gym-membership-check-in-register-with-chatgpt/): `gym-membership-check-in-register-with-chatgpt`
- [Gym Payments Status Register, ChatGPT](https://www.aisetupsthatwork.com/setups/gym-membership-payments-freeze-cancel-register-with-chatgpt/): `gym-membership-payments-freeze-cancel-register-with-chatgpt`
- [HVAC Startup Record Log, ChatGPT](https://www.aisetupsthatwork.com/setups/hvac-installation-startup-record-log-with-chatgpt/): `hvac-installation-startup-record-log-with-chatgpt`
- [HVAC Maintenance Tracker, ChatGPT](https://www.aisetupsthatwork.com/setups/hvac-maintenance-visit-tracker-with-chatgpt/): `hvac-maintenance-visit-tracker-with-chatgpt`
- [HVAC Refrigerant Parts Log, ChatGPT](https://www.aisetupsthatwork.com/setups/hvac-refrigerant-parts-usage-log-with-chatgpt/): `hvac-refrigerant-parts-usage-log-with-chatgpt`
- [HVAC Service Call Log, ChatGPT](https://www.aisetupsthatwork.com/setups/hvac-service-call-job-log-with-chatgpt/): `hvac-service-call-job-log-with-chatgpt`
- [Keep your agent from getting your account locked](https://www.aisetupsthatwork.com/setups/keep-your-agent-from-getting-your-account-locked/): `keep-your-agent-from-getting-your-account-locked`
- [Law Firm Deadline Entry Log, ChatGPT](https://www.aisetupsthatwork.com/setups/law-firm-deadline-calendar-entry-log-with-chatgpt/): `law-firm-deadline-calendar-entry-log-with-chatgpt`
- [Law Firm Document Request Log, ChatGPT](https://www.aisetupsthatwork.com/setups/law-firm-document-request-receipt-log-with-chatgpt/): `law-firm-document-request-receipt-log-with-chatgpt`
- [Law Firm Intake Status Log, ChatGPT](https://www.aisetupsthatwork.com/setups/law-firm-intake-conflict-status-log-with-chatgpt/): `law-firm-intake-conflict-status-log-with-chatgpt`
- [Law Firm Time and Billing Log, ChatGPT](https://www.aisetupsthatwork.com/setups/law-firm-time-billing-record-log-with-chatgpt/): `law-firm-time-billing-record-log-with-chatgpt`
- [Make bot corrections stick](https://www.aisetupsthatwork.com/setups/make-bot-corrections-stick/): `make-bot-corrections-stick`
- [Make your AI agent stop for approval](https://www.aisetupsthatwork.com/setups/make-your-ai-agent-stop-for-approval-before-it-sends/): `make-your-ai-agent-stop-for-approval-before-it-sends`
- [Measure the real time AI drafts save](https://www.aisetupsthatwork.com/setups/measure-the-real-time-ai-drafts-save/): `measure-the-real-time-ai-drafts-save`
- [One source-of-truth doc every bot reads](https://www.aisetupsthatwork.com/setups/one-source-of-truth-doc-every-bot-reads/): `one-source-of-truth-doc-every-bot-reads`
- [Organize your bots like an org chart](https://www.aisetupsthatwork.com/setups/organize-your-bots-like-an-org-chart/): `organize-your-bots-like-an-org-chart`
- [Pick your first AI agent job](https://www.aisetupsthatwork.com/setups/pick-your-first-ai-agent-job/): `pick-your-first-ai-agent-job`
- [Review what your AI agent did each week](https://www.aisetupsthatwork.com/setups/review-what-your-ai-agent-did-each-week/): `review-what-your-ai-agent-did-each-week`
- [Salon Appointment Register, ChatGPT](https://www.aisetupsthatwork.com/setups/salon-appointment-service-register-with-chatgpt/): `salon-appointment-service-register-with-chatgpt`
- [Salon Product SDS Register, ChatGPT](https://www.aisetupsthatwork.com/setups/salon-chemical-product-sds-register-with-chatgpt/): `salon-chemical-product-sds-register-with-chatgpt`
- [Salon Client Formula Log, ChatGPT](https://www.aisetupsthatwork.com/setups/salon-client-formula-history-register-with-chatgpt/): `salon-client-formula-history-register-with-chatgpt`
- [Salon Cleaning Log, ChatGPT](https://www.aisetupsthatwork.com/setups/salon-sanitation-cleaning-log-with-chatgpt/): `salon-sanitation-cleaning-log-with-chatgpt`
- [Screen job applicants against your instructions](https://www.aisetupsthatwork.com/setups/screen-job-applicants-against-your-instructions/): `screen-job-applicants-against-your-instructions`
- [Set a backup approver when you are away](https://www.aisetupsthatwork.com/setups/set-a-backup-approver-when-you-are-away/): `set-a-backup-approver-when-you-are-away`
- [Set guardrails before an AI agent gets access](https://www.aisetupsthatwork.com/setups/set-guardrails-before-giving-an-ai-agent-access/): `set-guardrails-before-giving-an-ai-agent-access`
- [Share a client portal page in Notion](https://www.aisetupsthatwork.com/setups/share-a-client-portal-page-in-notion/): `share-a-client-portal-page-in-notion`
- [Turn a good bot run into a saved routine](https://www.aisetupsthatwork.com/setups/turn-a-good-bot-run-into-a-saved-routine/) (Tested): `turn-a-good-bot-run-into-a-saved-routine`
- [Weekly contractor report from your job app export](https://www.aisetupsthatwork.com/setups/weekly-contractor-report-from-your-crm-export/): `weekly-contractor-report-from-your-crm-export`

### aistw-life

- [AI Chore Chart Generator for Kids (Printable Weekly Chart)](https://www.aisetupsthatwork.com/setups/ai-chore-chart-for-kids/): `ai-chore-chart-for-kids`
- [AI meal plan and grocery list](https://www.aisetupsthatwork.com/setups/ai-meal-plan-and-grocery-list/): `ai-meal-plan-and-grocery-list`
- [Appeal a Denied Health Insurance Claim with ChatGPT](https://www.aisetupsthatwork.com/setups/appeal-a-denied-health-insurance-claim-with-chatgpt/) (Tested): `appeal-a-denied-health-insurance-claim-with-chatgpt`
- [Appeal a property tax assessment](https://www.aisetupsthatwork.com/setups/appeal-property-tax-assessment/): `appeal-property-tax-assessment`
- [Build a Baby or Toddler Sleep Schedule With AI](https://www.aisetupsthatwork.com/setups/baby-and-toddler-sleep-schedule-with-ai/): `baby-and-toddler-sleep-schedule-with-ai`
- [Bedtime Routine That Actually Winds Kids Down](https://www.aisetupsthatwork.com/setups/bedtime-routine-that-winds-kids-down/): `bedtime-routine-that-winds-kids-down`
- [Plan a Kid’s Birthday Party on a Budget](https://www.aisetupsthatwork.com/setups/birthday-party-on-a-budget/): `birthday-party-on-a-budget`
- [Car Maintenance Schedule You Will Actually Follow](https://www.aisetupsthatwork.com/setups/car-maintenance-schedule/): `car-maintenance-schedule`
- [Check a Black Friday deal with Claude](https://www.aisetupsthatwork.com/setups/check-a-black-friday-deal-with-claude/): `check-a-black-friday-deal-with-claude`
- [Claim Flight Delay Compensation with ChatGPT](https://www.aisetupsthatwork.com/setups/claim-flight-delay-compensation-with-chatgpt/) (Tested): `claim-flight-delay-compensation-with-chatgpt`
- [Claude Projects for small business repeat work](https://www.aisetupsthatwork.com/setups/claude-projects-for-small-business/): `claude-projects-for-small-business`
- [Claude vs ChatGPT for everyday writing (honest comparison)](https://www.aisetupsthatwork.com/setups/claude-vs-chatgpt-for-writing/): `claude-vs-chatgpt-for-writing`
- [Costco price adjustment watch](https://www.aisetupsthatwork.com/setups/costco-price-adjustment-watch/): `costco-price-adjustment-watch`
- [Data broker opt-out recheck log](https://www.aisetupsthatwork.com/setups/data-broker-opt-out-recheck-log/): `data-broker-opt-out-recheck-log`
- [Declutter One Room With a Keep / Toss / Donate Plan](https://www.aisetupsthatwork.com/setups/declutter-one-room-keep-toss-plan/): `declutter-one-room-keep-toss-plan`
- [Build a Dog Training Plan With AI](https://www.aisetupsthatwork.com/setups/dog-training-plan-with-ai/): `dog-training-plan-with-ai`
- [Write an IEP Evaluation Request Letter](https://www.aisetupsthatwork.com/setups/draft-an-iep-request-letter-with-ai/): `draft-an-iep-request-letter-with-ai`
- [Family recurring charges tracker](https://www.aisetupsthatwork.com/setups/family-recurring-charges-tracker/): `family-recurring-charges-tracker`
- [Fight a Parking Ticket with ChatGPT](https://www.aisetupsthatwork.com/setups/fight-a-parking-ticket-with-chatgpt/): `fight-a-parking-ticket-with-chatgpt`
- [File a Pet Insurance Claim with ChatGPT](https://www.aisetupsthatwork.com/setups/file-a-pet-insurance-claim-with-chatgpt/): `file-a-pet-insurance-claim-with-chatgpt`
- [File a Warranty Claim with ChatGPT](https://www.aisetupsthatwork.com/setups/file-a-warranty-claim-with-chatgpt/): `file-a-warranty-claim-with-chatgpt`
- [Flight cancelled? Next steps, Claude](https://www.aisetupsthatwork.com/setups/flight-cancelled-what-to-do-with-claude/): `flight-cancelled-what-to-do-with-claude`
- [Garage Cleanout Plan (One Weekend, Four Piles)](https://www.aisetupsthatwork.com/setups/garage-cleanout-plan/): `garage-cleanout-plan`
- [Get Your Security Deposit Back with ChatGPT](https://www.aisetupsthatwork.com/setups/get-your-security-deposit-back-with-chatgpt/): `get-your-security-deposit-back-with-chatgpt`
- [How to grade your kid's math homework from a photo with AI](https://www.aisetupsthatwork.com/setups/grade-kids-math-homework-from-a-photo-with-ai/): `grade-kids-math-homework-from-a-photo-with-ai`
- [Grocery Budgeting for a Family (A Meal Plan That Fits the Number)](https://www.aisetupsthatwork.com/setups/grocery-budgeting-for-a-family/): `grocery-budgeting-for-a-family`
- [Plan Holiday Gifts Without the January Debt Hangover](https://www.aisetupsthatwork.com/setups/holiday-gifts-without-debt/): `holiday-gifts-without-debt`
- [Holiday travel plan B with Claude](https://www.aisetupsthatwork.com/setups/holiday-travel-backup-plan-with-claude/): `holiday-travel-backup-plan-with-claude`
- [Home Inventory for Insurance (Photo Walkthrough in an Afternoon)](https://www.aisetupsthatwork.com/setups/home-inventory-for-insurance/): `home-inventory-for-insurance`
- [Journal With AI and Know Where to Stop](https://www.aisetupsthatwork.com/setups/journal-with-ai-with-limits/): `journal-with-ai-with-limits`
- [Laid off: first-week plan](https://www.aisetupsthatwork.com/setups/laid-off-first-week-plan/): `laid-off-first-week-plan`
- [Learn a new skill with an AI study plan](https://www.aisetupsthatwork.com/setups/learn-a-new-skill-with-ai-study-plan/): `learn-a-new-skill-with-ai-study-plan`
- [Make a family cookbook with AI](https://www.aisetupsthatwork.com/setups/make-a-family-cookbook-with-ai/): `make-a-family-cookbook-with-ai`
- [Move your AI memory to a new assistant](https://www.aisetupsthatwork.com/setups/move-your-ai-memory-to-a-new-assistant/): `move-your-ai-memory-to-a-new-assistant`
- [New Baby Prep Checklist (The Short List That Actually Matters)](https://www.aisetupsthatwork.com/setups/new-baby-prep-checklist/): `new-baby-prep-checklist`
- [Organize Elder Care: Appointments, Meds, and Paperwork](https://www.aisetupsthatwork.com/setups/organize-elder-care-with-ai/): `organize-elder-care-with-ai`
- [Organize Family Photos (A Folder System You Will Keep Up)](https://www.aisetupsthatwork.com/setups/organizing-family-photos/): `organizing-family-photos`
- [Packing List for Any Trip (AI Builds It From Your Itinerary)](https://www.aisetupsthatwork.com/setups/packing-list-for-any-trip/): `packing-list-for-any-trip`
- [Pet Care Instructions for Your Sitter (One Sheet, No Panic Texts)](https://www.aisetupsthatwork.com/setups/pet-care-instructions-for-sitter/): `pet-care-instructions-for-sitter`
- [Plan a vegetable garden with AI](https://www.aisetupsthatwork.com/setups/plan-a-vegetable-garden-with-ai/): `plan-a-vegetable-garden-with-ai`
- [Points or Cash for Travel? Decide with ChatGPT](https://www.aisetupsthatwork.com/setups/points-or-cash-for-travel-with-chatgpt/): `points-or-cash-for-travel-with-chatgpt`
- [Route Grok Bot tasks to your Claude and ChatGPT subscriptions](https://www.aisetupsthatwork.com/setups/route-grok-bot-tasks-to-claude-and-chatgpt-subscriptions/) (Tested): `route-grok-bot-tasks-to-claude-and-chatgpt-subscriptions`
- [Scam text checklist before you click](https://www.aisetupsthatwork.com/setups/scam-text-checklist-before-you-click/): `scam-text-checklist-before-you-click`
- [School night routine and forms](https://www.aisetupsthatwork.com/setups/school-night-routine-and-forms/): `school-night-routine-and-forms`
- [Screen spam calls with a trust ladder](https://www.aisetupsthatwork.com/setups/screen-spam-calls-trust-ladder/): `screen-spam-calls-trust-ladder`
- [Sell Your Stuff Online with ChatGPT](https://www.aisetupsthatwork.com/setups/sell-your-stuff-online-with-chatgpt/): `sell-your-stuff-online-with-chatgpt`
- [Target price adjustment watch](https://www.aisetupsthatwork.com/setups/target-price-adjustment-watch/): `target-price-adjustment-watch`
- [Break an Overwhelming Task Into Small Steps With AI](https://www.aisetupsthatwork.com/setups/task-breakdown-with-ai-for-adhd/): `task-breakdown-with-ai-for-adhd`
- [Thanksgiving Cooking Timeline with AI: Free Prompt for a One-Oven Kitchen](https://www.aisetupsthatwork.com/setups/thanksgiving-cooking-timeline-with-ai/): `thanksgiving-cooking-timeline-with-ai`
- [Track holiday returns with Claude](https://www.aisetupsthatwork.com/setups/track-holiday-returns-with-claude/): `track-holiday-returns-with-claude`
- [Weekly Home Reset Checklist (A Plan You Will Actually Follow)](https://www.aisetupsthatwork.com/setups/weekly-home-reset-checklist/): `weekly-home-reset-checklist`
- [Will Checklist: Get Your Documents Ready Before You See a Lawyer](https://www.aisetupsthatwork.com/setups/will-checklist-with-ai/): `will-checklist-with-ai`
- [How to Use ChatGPT to Write a Complaint Letter That Gets a Response](https://www.aisetupsthatwork.com/setups/write-a-complaint-letter-with-chatgpt/): `write-a-complaint-letter-with-chatgpt`
- [How to Use ChatGPT to Write a Letter of Recommendation](https://www.aisetupsthatwork.com/setups/write-a-letter-of-recommendation-with-chatgpt/): `write-a-letter-of-recommendation-with-chatgpt`
- [Write holiday cards with Claude](https://www.aisetupsthatwork.com/setups/write-holiday-cards-in-your-voice-with-claude/): `write-holiday-cards-in-your-voice-with-claude`
- [Write a Rental Listing That Gets Replies](https://www.aisetupsthatwork.com/setups/writing-a-rental-listing/): `writing-a-rental-listing`
- [Writing Difficult Texts: Boundaries and Apologies That Sound Like You](https://www.aisetupsthatwork.com/setups/writing-difficult-texts/): `writing-difficult-texts`

### aistw-research

- [Add business schema to your site](https://www.aisetupsthatwork.com/setups/add-business-schema-so-ai-can-find-you/): `add-business-schema-so-ai-can-find-you`
- [Add captions from speech with Claude](https://www.aisetupsthatwork.com/setups/add-captions-from-speech-with-claude-code/): `add-captions-from-speech-with-claude-code`
- [How to use AI for business plan research: locations, costs and funding](https://www.aisetupsthatwork.com/setups/ai-business-plan-research-locations-costs-funding/): `ai-business-plan-research-locations-costs-funding`
- [AI chief of staff bot](https://www.aisetupsthatwork.com/setups/ai-chief-of-staff-bot/): `ai-chief-of-staff-bot`
- [Ask AI questions about your spreadsheet](https://www.aisetupsthatwork.com/setups/ask-ai-questions-about-your-spreadsheet/): `ask-ai-questions-about-your-spreadsheet`
- [Clip long videos into shorts](https://www.aisetupsthatwork.com/setups/auto-clip-long-videos-into-shorts-with-ai/): `auto-clip-long-videos-into-shorts-with-ai`
- [Build a reading ladder to learn a complex topic fast](https://www.aisetupsthatwork.com/setups/build-a-reading-ladder-for-a-complex-topic/): `build-a-reading-ladder-for-a-complex-topic`
- [Turn Class Notes Into Anki Flashcards With AI](https://www.aisetupsthatwork.com/setups/build-anki-flashcards-from-notes-with-ai/): `build-anki-flashcards-from-notes-with-ai`
- [Build your case for a raise or promotion](https://www.aisetupsthatwork.com/setups/build-your-case-for-a-raise-or-promotion/): `build-your-case-for-a-raise-or-promotion`
- [Build your first project with AI as a non-coder](https://www.aisetupsthatwork.com/setups/build-your-first-project-with-ai-as-a-non-coder/) (Tested): `build-your-first-project-with-ai-as-a-non-coder`
- [Certificate Register with ChatGPT](https://www.aisetupsthatwork.com/setups/certificate-of-insurance-register-with-chatgpt/) (Tested): `certificate-of-insurance-register-with-chatgpt`
- [Check Etsy listings against the new AI rules](https://www.aisetupsthatwork.com/setups/check-etsy-listings-against-the-new-ai-rules/): `check-etsy-listings-against-the-new-ai-rules`
- [Check if ChatGPT recommends your business](https://www.aisetupsthatwork.com/setups/check-if-chatgpt-recommends-your-business/): `check-if-chatgpt-recommends-your-business`
- [Check your resume for claims you cannot back up](https://www.aisetupsthatwork.com/setups/check-your-resume-for-claims-you-cannot-back-up/): `check-your-resume-for-claims-you-cannot-back-up`
- [Get College Essay Feedback From AI Without Losing Your Voice](https://www.aisetupsthatwork.com/setups/college-essay-feedback-with-ai/): `college-essay-feedback-with-ai`
- [Compare a big purchase with a saved research brief](https://www.aisetupsthatwork.com/setups/compare-big-purchases-with-research-brief/) (Tested): `compare-big-purchase`
- [Compare colleges side by side: cost, grad rates, and outcomes](https://www.aisetupsthatwork.com/setups/compare-colleges-side-by-side-with-ai/): `compare-colleges-side-by-side-with-ai`
- [Compare insurance quotes apples to apples](https://www.aisetupsthatwork.com/setups/compare-insurance-quotes-apples-to-apples/): `compare-insurance-quotes-apples-to-apples`
- [Compare phone and internet plans without the fine-print headache](https://www.aisetupsthatwork.com/setups/compare-phone-and-internet-plans-with-ai/): `compare-phone-and-internet-plans-with-ai`
- [Compare software tools for your team without the sales calls](https://www.aisetupsthatwork.com/setups/compare-software-tools-for-your-team/): `compare-software-tools-for-your-team`
- [Cut long video into shorts with Claude](https://www.aisetupsthatwork.com/setups/cut-long-video-into-shorts-with-claude-code/): `cut-long-video-into-shorts-with-claude-code`
- [Cut silences from a talking video](https://www.aisetupsthatwork.com/setups/cut-silences-from-a-talking-video-with-claude-code/) (Tested): `cut-silences-from-a-talking-video-with-claude-code`
- [Debug a Python script with AI](https://www.aisetupsthatwork.com/setups/debug-a-python-script-with-ai/): `debug-a-python-script-with-ai`
- [Design a flyer with Canva Magic Design](https://www.aisetupsthatwork.com/setups/design-a-flyer-with-canva-magic-design/): `design-a-flyer-with-canva-magic-design`
- [Turn Handwritten Notes Into Searchable Text](https://www.aisetupsthatwork.com/setups/digitize-handwritten-notes-with-ai/): `digitize-handwritten-notes-with-ai`
- [Draft a Privacy Policy and Terms Page for Your Site](https://www.aisetupsthatwork.com/setups/draft-a-privacy-policy-and-terms-page/): `draft-a-privacy-policy-and-terms-page`
- [Do due diligence on a job offer before you sign](https://www.aisetupsthatwork.com/setups/due-diligence-on-a-job-offer-with-ai/): `due-diligence-on-a-job-offer-with-ai`
- [Edit a video for social with Claude](https://www.aisetupsthatwork.com/setups/edit-a-video-for-social-with-claude-code/) (Tested): `edit-a-video-for-social-with-claude-code`
- [Build an exam study schedule with AI quizzes](https://www.aisetupsthatwork.com/setups/exam-study-schedule-and-quizzes-with-ai/): `exam-study-schedule-and-quizzes-with-ai`
- [How to extract data from a PDF to Google Sheets with an AI bot](https://www.aisetupsthatwork.com/setups/extract-data-from-pdf-to-google-sheets-with-ai/): `extract-data-from-pdf-to-google-sheets-with-ai`
- [Fact-check a viral claim before you share it](https://www.aisetupsthatwork.com/setups/fact-check-a-viral-claim-with-ai/): `fact-check-a-viral-claim-with-ai`
- [Find the long questions people search to find you](https://www.aisetupsthatwork.com/setups/find-long-questions-people-search-in-search-console/): `find-long-questions-people-search-in-search-console`
- [Fix and Write Excel Formulas With AI](https://www.aisetupsthatwork.com/setups/fix-excel-formulas-with-ai/): `fix-excel-formulas-with-ai`
- [Fix your LinkedIn headline for recruiters](https://www.aisetupsthatwork.com/setups/fix-your-linkedin-headline-for-recruiters/): `fix-your-linkedin-headline-for-recruiters`
- [Give your AI a map of your website](https://www.aisetupsthatwork.com/setups/give-your-ai-a-map-of-your-website/): `give-your-ai-a-map-of-your-website`
- [Client Communication Log with ChatGPT](https://www.aisetupsthatwork.com/setups/insurance-client-communication-log-with-chatgpt/) (Tested): `insurance-client-communication-log-with-chatgpt`
- [Policy Renewal Register with ChatGPT](https://www.aisetupsthatwork.com/setups/insurance-policy-renewal-register-with-chatgpt/) (Tested): `insurance-policy-renewal-register-with-chatgpt`
- [Make a product launch video from code](https://www.aisetupsthatwork.com/setups/make-a-product-launch-video-with-claude-code-and-remotion/) (Tested): `make-a-product-launch-video-with-claude-code-and-remotion`
- [Make a promo reel with AI, from code](https://www.aisetupsthatwork.com/setups/make-a-promo-reel-with-ai-from-code/) (Tested): `make-a-promo-reel-with-ai-from-code`
- [How to make a study guide with AI: a custom course ebook on any topic](https://www.aisetupsthatwork.com/setups/make-a-study-guide-with-ai-custom-course-ebook/): `make-a-study-guide-with-ai-custom-course-ebook`
- [Make AI write in your voice](https://www.aisetupsthatwork.com/setups/make-ai-write-in-your-voice/) (Tested): `make-ai-write-in-your-voice`
- [Make feed versions and a thumbnail](https://www.aisetupsthatwork.com/setups/make-feed-versions-and-a-thumbnail-with-claude-code/) (Tested): `make-feed-versions-and-a-thumbnail-with-claude-code`
- [Make your website readable by AI](https://www.aisetupsthatwork.com/setups/make-your-website-readable-by-ai-agents/): `make-your-website-readable-by-ai-agents`
- [Mock behavioral interview with AI](https://www.aisetupsthatwork.com/setups/mock-behavioral-interview-with-ai/): `mock-behavioral-interview-with-ai`
- [Negotiate a job offer with AI](https://www.aisetupsthatwork.com/setups/negotiate-a-job-offer-with-ai/): `negotiate-a-job-offer-with-ai`
- [Start a Business: LLC or Sole Proprietor Setup Checklist](https://www.aisetupsthatwork.com/setups/new-business-setup-checklist/): `new-business-setup-checklist`
- [Onboard your first employees](https://www.aisetupsthatwork.com/setups/onboard-your-first-employees/): `onboard-your-first-employees`
- [How to use OpenRouter free models to stretch your AI bot's usage](https://www.aisetupsthatwork.com/setups/openrouter-free-models-stretch-ai-bot-usage/): `openrouter-free-models-stretch-ai-bot-usage`
- [Claim Status Log with ChatGPT](https://www.aisetupsthatwork.com/setups/organize-an-insurance-agency-claim-status-log-with-chatgpt/) (Tested): `organize-an-insurance-agency-claim-status-log-with-chatgpt`
- [Can I Use AI to Organize My Computer Files? (Safe Draft-Only Plan)](https://www.aisetupsthatwork.com/setups/organize-computer-files-with-ai/): `organize-computer-files-with-ai`
- [Outline a novel with AI and keep continuity](https://www.aisetupsthatwork.com/setups/outline-a-novel-with-ai/): `outline-a-novel-with-ai`
- [Plan a career change in 90 days](https://www.aisetupsthatwork.com/setups/plan-a-career-change-in-90-days/): `plan-a-career-change-in-90-days`
- [Plan a Home Renovation With AI: Scope, Budget, and Contractor Quotes](https://www.aisetupsthatwork.com/setups/plan-a-home-renovation-with-ai/): `plan-a-home-renovation-with-ai`
- [Plan Facebook ads with AI and cap the spend](https://www.aisetupsthatwork.com/setups/plan-facebook-ads-with-ai-and-cap-the-spend/): `plan-facebook-ads-with-ai-and-cap-the-spend`
- [Practice a New Language With AI Conversation](https://www.aisetupsthatwork.com/setups/practice-a-language-with-ai-conversation/): `practice-a-language-with-ai-conversation`
- [Prep a D&D session with AI](https://www.aisetupsthatwork.com/setups/prep-a-dnd-session-with-ai/): `prep-a-dnd-session-with-ai`
- [Research a company before you apply](https://www.aisetupsthatwork.com/setups/research-a-company-before-you-apply/): `research-a-company-before-you-apply`
- [Research a medical procedure before your appointment](https://www.aisetupsthatwork.com/setups/research-a-medical-procedure-before-your-appointment/): `research-a-medical-procedure-before-your-appointment`
- [Research a neighborhood before you move](https://www.aisetupsthatwork.com/setups/research-a-neighborhood-before-you-move/): `research-a-neighborhood-before-you-move`
- [Research a used car before you buy: reliability, price, and scams](https://www.aisetupsthatwork.com/setups/research-a-used-car-before-buying-with-ai/): `research-a-used-car-before-buying-with-ai`
- [Research competitors through your customer’s eyes](https://www.aisetupsthatwork.com/setups/research-competitors-with-ai/): `research-competitors-with-ai`
- [Research grants and assistance programs you actually qualify for](https://www.aisetupsthatwork.com/setups/research-grants-and-assistance-programs/): `research-grants-and-assistance-programs`
- [Resignation letter and exit conversation](https://www.aisetupsthatwork.com/setups/resignation-letter-and-exit-conversation/): `resignation-letter-and-exit-conversation`
- [Self-Publish a Book With AI Help](https://www.aisetupsthatwork.com/setups/self-publish-a-book-with-ai-help/): `self-publish-a-book-with-ai-help`
- [Set up a voice file in Claude](https://www.aisetupsthatwork.com/setups/set-up-a-voice-file-in-claude/): `set-up-a-voice-file-in-claude`
- [Shared AI brain: Obsidian and GitHub](https://www.aisetupsthatwork.com/setups/shared-ai-brain-with-obsidian-and-github/): `shared-ai-brain-with-obsidian-and-github`
- [Understand Your Lease in Plain English](https://www.aisetupsthatwork.com/setups/summarize-a-lease-in-plain-english/): `summarize-a-lease-in-plain-english`
- [Turn a long report into a one-page brief](https://www.aisetupsthatwork.com/setups/summarize-a-long-report-into-a-one-pager/): `summarize-a-long-report-into-a-one-pager`
- [Sync an Obsidian vault on a computer](https://www.aisetupsthatwork.com/setups/sync-an-obsidian-vault-on-a-computer-with-github/): `sync-an-obsidian-vault-on-a-computer-with-github`
- [Sync an Obsidian vault on iPhone](https://www.aisetupsthatwork.com/setups/sync-an-obsidian-vault-on-iphone-with-github/): `sync-an-obsidian-vault-on-iphone-with-github`
- [ChatGPT Prompt for Tailoring Your Resume to a Job Description](https://www.aisetupsthatwork.com/setups/tailor-resume-to-job-description-with-ai/): `tailor-resume-to-job-description-with-ai`
- [Test short video hooks like experiments](https://www.aisetupsthatwork.com/setups/test-short-video-hooks-like-experiments/): `test-short-video-hooks-like-experiments`
- [Track job applications from your inbox](https://www.aisetupsthatwork.com/setups/track-job-applications-from-your-inbox/): `track-job-applications-from-your-inbox`
- [Track true profit per order](https://www.aisetupsthatwork.com/setups/track-true-profit-per-order/): `track-true-profit-per-order`
- [Turn a stack of documents into one brief](https://www.aisetupsthatwork.com/setups/turn-a-stack-of-documents-into-one-brief/): `turn-a-stack-of-documents-into-one-brief`
- [Turn book notes into decisions instead of a highlight graveyard](https://www.aisetupsthatwork.com/setups/turn-book-notes-into-decisions/): `turn-book-notes-into-decisions`
- [Turn how you work into a written SOP](https://www.aisetupsthatwork.com/setups/turn-how-you-work-into-a-written-sop/) (Tested): `turn-how-you-work-into-a-written-sop`
- [Turn your day into a build-in-public post](https://www.aisetupsthatwork.com/setups/turn-your-day-into-a-build-in-public-post/): `turn-your-day-into-a-build-in-public-post`
- [Understand Lab Results Before Your Doctor Visit](https://www.aisetupsthatwork.com/setups/understand-lab-results-before-a-doctor-visit/): `understand-lab-results-before-a-doctor-visit`
- [Validate a Side Hustle Idea in One Week](https://www.aisetupsthatwork.com/setups/validate-a-side-hustle-idea-in-a-week/): `validate-a-side-hustle-idea-in-a-week`
- [Vet a contractor before you hire them](https://www.aisetupsthatwork.com/setups/vet-a-contractor-before-you-hire/): `vet-a-contractor-before-you-hire`
- [Write a Eulogy or Toast With AI Without Losing Your Voice](https://www.aisetupsthatwork.com/setups/write-a-eulogy-or-toast-with-ai/): `write-a-eulogy-or-toast-with-ai`
- [AI to Write a Job Description (Copy-Paste Prompt for Hiring)](https://www.aisetupsthatwork.com/setups/write-a-job-description-with-ai/): `write-a-job-description-with-ai`
- [Write a short note to the hiring manager](https://www.aisetupsthatwork.com/setups/write-a-short-note-to-the-hiring-manager/): `write-a-short-note-to-the-hiring-manager`
- [Write Home Assistant automations with AI](https://www.aisetupsthatwork.com/setups/write-home-assistant-automations-with-ai/): `write-home-assistant-automations-with-ai`
- [Write Song Lyrics That Work in Suno](https://www.aisetupsthatwork.com/setups/write-song-lyrics-for-suno/): `write-song-lyrics-for-suno`
- [Write your self review from your notes](https://www.aisetupsthatwork.com/setups/write-your-self-review-from-your-notes/): `write-your-self-review-from-your-notes`

### aistw-reviews

- [Ask for LinkedIn Recommendations (and Get Yeses)](https://www.aisetupsthatwork.com/setups/ask-for-linkedin-recommendations/): `ask-for-linkedin-recommendations`
- [Ask Happy Customers for Reviews at the Right Moment](https://www.aisetupsthatwork.com/setups/ask-happy-customers-for-reviews/): `ask-happy-customers-for-reviews`
- [Find Out Why Customers Cancel With a Short Exit Survey](https://www.aisetupsthatwork.com/setups/cancellation-survey-that-gets-answers/): `cancellation-survey-that-gets-answers`
- [Write a Short Customer Survey People Actually Finish](https://www.aisetupsthatwork.com/setups/customer-survey-that-gets-responses/): `customer-survey-that-gets-responses`
- [Dispute a Fake or Unfair Review (and Know When to Let It Go)](https://www.aisetupsthatwork.com/setups/dispute-fake-or-unfair-reviews/): `dispute-fake-or-unfair-reviews`
- [Reply to an unreasonable refund request](https://www.aisetupsthatwork.com/setups/reply-to-an-unreasonable-refund-request/): `reply-to-an-unreasonable-refund-request`
- [How to Use AI to Reply to Google Reviews (Even the Bad Ones)](https://www.aisetupsthatwork.com/setups/reply-to-google-reviews-with-ai/): `reply-to-google-reviews-with-ai`
- [Reply to 1-Star Reviews Without Sounding Like a Robot](https://www.aisetupsthatwork.com/setups/reply-to-one-star-reviews-with-ai/): `reply-to-one-star-reviews-with-ai`
- [Your Reputation Command Center: Monitor, Respond, Improve](https://www.aisetupsthatwork.com/setups/reputation-command-center-small-business/): `reputation-command-center-small-business`
- [Restaurant Review Replies: Templates for Yelp, Google, and TripAdvisor](https://www.aisetupsthatwork.com/setups/restaurant-review-response-templates/): `restaurant-review-response-templates`
- [Make a Review QR Card Customers Actually Scan](https://www.aisetupsthatwork.com/setups/review-qr-card-that-gets-scanned/): `review-qr-card-that-gets-scanned`
- [Read 100 Reviews in 20 Minutes: Find What Customers Really Complain About](https://www.aisetupsthatwork.com/setups/summarize-reviews-to-find-complaints/): `summarize-reviews-to-find-complaints`
- [A Review Response Playbook Your Whole Team Can Follow](https://www.aisetupsthatwork.com/setups/team-review-response-playbook/): `team-review-response-playbook`
- [Thank-You Replies for 5-Star Reviews That Do Not Sound Canned](https://www.aisetupsthatwork.com/setups/thank-you-replies-for-five-star-reviews/): `thank-you-replies-for-five-star-reviews`
- [Turn Good Reviews Into Social Media Posts](https://www.aisetupsthatwork.com/setups/turn-reviews-into-social-posts/): `turn-reviews-into-social-posts`
- [One Weekly Brief for Reviews Across Google, Yelp, and Facebook](https://www.aisetupsthatwork.com/setups/weekly-review-monitoring-brief/): `weekly-review-monitoring-brief`
- [Write Reviews That Actually Help People](https://www.aisetupsthatwork.com/setups/write-helpful-reviews-with-ai/): `write-helpful-reviews-with-ai`
- [Write a Rental Reference Letter With AI](https://www.aisetupsthatwork.com/setups/write-rental-reference-letter-with-ai/): `write-rental-reference-letter-with-ai`

## Safety

Every skill drafts first. None of them sends, posts, pays, books, cancels or deletes anything without your approval of that exact action.

## License

Free to use for yourself, your job or your business, and to edit your own copies. Not for resale or republishing. The rights stay with AI Setups That Work. Full terms in [LICENSE](LICENSE).
