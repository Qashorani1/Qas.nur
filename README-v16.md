# Qas.nur v1.6 — Feature Update

Adds exam performance analytics (below), report-an-error copy workflow, light/dark theme, glossary, quick review, and topic sharing. No clinical chapter text changed.

## Analytics / private dashboard
No real analytics provider is connected and no server-side owner login is deployed. Do not publish an unsecured mock admin dashboard. Connect Cloudflare Web Analytics or a similar provider using its official website tracking script, then use the provider’s authenticated dashboard. For single-page topic-level events, implement privacy-conscious virtual page views.

## Error reports
The form validates and copies a report. It does NOT submit to a server. Set `qas16FeedbackEmail` in `features-v16.js` to an owner-approved published address to use mailto; a real backend is needed for automatic collection.

## QA
JS syntax checked; browser and clinical review still required.
