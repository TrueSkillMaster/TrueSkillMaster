# Dmytro Dumka

AI & Automation Specialist — n8n · Make · GoHighLevel · Claude/OpenAI API

I build automation systems that replace manual work on repetitive tasks: lead pipelines, follow-up sequences, document workflows, AI-filtered data monitoring. 30+ working builds. Based in Poland, working globally.

## What I do

- **Workflow automation** — n8n (self-hosted or cloud) and Make, with error handling, logging, and deduplication state built in from the start
- **AI pipelines** — hybrid rule-based + LLM filtering, vision analysis, binary classification with cost-optimized model selection
- **CRM architecture** — GoHighLevel workflow design, platform-limitation workarounds, data hygiene, DNS-level email deliverability
- **Self-hosted infrastructure** — production n8n on a $0/month stack (Oracle Cloud Free Tier, Docker, Nginx, SSL)

## Selected production work

**Government tender monitor** — for a German B2B equipment supplier. Per-minute polling of a public procurement API, hybrid CPV/brand rule filter + gpt-4o-mini confirmation (cuts ~95% of LLM calls), cross-run deduplication state, 4 parallel Google Sheets outputs, instant alerts. Running in production.

**CRM pipeline collision fix** — for a UK fractional marketing director. Existing clients booking meetings were duplicated across two pipelines. Diagnosed the platform limitation, applied a tag-proxy pattern with a helper workflow, enabled contact deduplication. Weekly manual cleanup eliminated.

**AI content pipeline** — own product. A messaging-bot front end that turns any Instagram carousel into a branded one: scraping → Claude vision analysis → AI image generation with brand reference → template rendering. ~3.5 min and ~$0.30 per post, end to end.

## Certifications

n8n Level 1 & Level 2 · Make.com: Basics, Foundation, Intermediate, Advanced, AI Automation Explorer

## Contact

Available for automation projects via Upwork.
