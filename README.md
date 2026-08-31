# Dmytro Dumka

**AI & Automation Specialist** — n8n · Make · GoHighLevel · Claude / OpenAI API

I build automation systems that replace manual work on repetitive tasks: lead pipelines, follow-up sequences, document workflows, AI-filtered data monitoring, content pipelines. Architect-first, not task-first — I check the assumption before building the thing, and I say so when the thing doesn't need building.

30+ working builds (client work, own products, training simulations). Based in Poland, working globally, async-first.

---

## Repositories

| Repo | What it is |
|---|---|
| [automation-patterns](https://github.com/TrueSkillMaster/automation-patterns) | Production patterns for n8n/Make: cross-run dedup state, AI input sanitization, hybrid rule → LLM filtering |
| [n8n-tender-monitor](https://github.com/TrueSkillMaster/n8n-tender-monitor) | Government procurement monitor — per-minute API polling, hybrid AI filter, 4 parallel outputs. Production system for a B2B supplier |
| [ai-carousel-factory](https://github.com/TrueSkillMaster/ai-carousel-factory) | 16-node n8n pipeline: Instagram carousel URL → Claude vision → AI images → branded templates → 7 PNGs in ~3.5 min |
| [ghl-architecture-patterns](https://github.com/TrueSkillMaster/ghl-architecture-patterns) | GoHighLevel deep fixes: tag-proxy for pipeline collisions, email deliverability, multi-source calendar sync, data hygiene |
| [n8n-selfhosted-setup](https://github.com/TrueSkillMaster/n8n-selfhosted-setup) | Production n8n on a $0/month stack — Oracle Cloud Free Tier, Docker, Nginx Proxy Manager, Let's Encrypt |
| [portfolio](https://github.com/TrueSkillMaster/portfolio) | All 11 builds with architecture, decisions and results — client work, own products, training simulations |

---

## What I do

**Workflow automation** — n8n (self-hosted or cloud) and Make. Error handling, logging and deduplication state built in from the first version, not bolted on after the first silent failure.

**AI pipelines** — hybrid rule-based + LLM filtering, vision analysis, binary classification with cheap models, structured JSON output with resilient validation. Every AI decision has an explicit answer to "why isn't this a regex?"

**CRM architecture** — GoHighLevel workflow design, platform-limitation workarounds, contact/opportunity deduplication, DNS-level email deliverability (SPF/DKIM/DMARC), multi-calendar sync.

**Self-hosted infrastructure** — production n8n on Oracle Cloud Free Tier with Docker, Nginx Proxy Manager and Let's Encrypt. $0/month, no execution limits, full data control.

**Executive deliverables** — programmatic PowerPoint (pptxgenjs + OOXML post-processing), interactive HTML briefings, multilingual variants (EN / UA / Mandarin Chinese).

---

## Selected production work

**Government tender monitor** — for a German B2B equipment supplier. Per-minute polling of a public procurement API (200–300 new records/day), rule filter on category codes + brand keywords, gpt-4o-mini YES/NO confirmation on what survives (~95% fewer LLM calls than model-on-everything), cross-run dedup state, 4 parallel Google Sheets outputs (tenders, buyer CRM, preliminary tracking, supplier intelligence), instant alerts. Client's AI cost: ~$10–15/month. Later extended into a market-intelligence briefing: 5,535 tenders analysed, $36.2M market sizing, 15-slide deck in EN + Mandarin. → [n8n-tender-monitor](https://github.com/TrueSkillMaster/n8n-tender-monitor)

**CRM pipeline collision fix** — for a UK fractional marketing director running a web-design franchise sub-account. Existing clients booking meetings were cloned into the leads pipeline every week. GHL conditions can't check opportunity location, so: helper workflow auto-tags live clients, bulk-tag of 327 existing contacts, If/Else on the tag before opportunity creation, contact dedup by email → phone. Checked the second sub-account before replicating — different architecture, fix not needed, said so. → [ghl-architecture-patterns](https://github.com/TrueSkillMaster/ghl-architecture-patterns)

**Email deliverability + calendar sync** — same client, earlier engagement. Every email failing DMARC (sending domain belonged to franchise HQ, SPF missing), booking pages ignoring blocked days (linked to Google while the client blocks time in iCloud), 24 calendars accumulated over years. DNS records extracted for HQ, linked calendar switched to iCloud with 6 conflict calendars, 24 → 11 calendars. → [ghl-architecture-patterns](https://github.com/TrueSkillMaster/ghl-architecture-patterns)

**Form → AI → PDF pipeline** — same client, first engagement. Jotform sent nested arrays that broke Make's mapping; AI scoring always returned 75/100. Fixed the parsing, rebuilt the scoring prompt, moved polling to webhook, added personalised PDF generation with a booking CTA.

**AI carousel factory** — own product, piloted with an AI school. Drop an Instagram carousel URL into a bot → scrape → Claude vision writes a brief in the client's structure → gpt-image-1.5 generates 6 images with brand-reference fidelity → Creatomate renders branded templates → 7 PNGs back. ~3.5 min and ~$0.30 per post. → [ai-carousel-factory](https://github.com/TrueSkillMaster/ai-carousel-factory)

---

## Stack

| Area | Tools |
|---|---|
| Automation | n8n (self-hosted), Make, Zapier, GoHighLevel, Apify, webhooks, REST/OAuth 2.0, API polling with dedup state |
| AI | OpenAI (GPT-4o, gpt-4o-mini, gpt-image-1.5, Whisper, Vision), Claude (Sonnet 4.6 vision + JSON), Retell AI, ElevenLabs |
| AI patterns | Hybrid rule → AI filtering, input sanitization, resilient validation (truncate, don't throw), binary classification with minimal `max_tokens`, per-configuration cost modelling |
| Chatbots | ManyChat, Voiceflow, ChatBase, Chipp.AI, Telegram Bot API |
| Data | Airtable, Google Sheets, Supabase, Softr, Pinecone, Weaviate |
| GHL | Pipelines/stages architecture, workflow conditions, tag-proxy patterns, helper workflows, Smart Lists, native Manage Duplicates, dedup preferences, execution-log debugging, multi-sub-account |
| Email / infra | SPF/DKIM/DMARC, dedicated sending domains, Mailgun, LeadConnector, domain warmup |
| Content / media | Creatomate, Replicate (Flux/SD), Supadata, CloudConvert, Photoshop, Heygen, Vizard |
| Documents | pptxgenjs, OOXML post-processing, HTML briefings with Chart.js/Recharts, HTML-to-PDF |
| DevOps | Docker, Nginx Proxy Manager, Oracle Cloud (OCI), Cloudflare R2, Ubuntu, Let's Encrypt, DuckDNS, IPTables |
| Languages | JavaScript (n8n Code nodes, Node.js scripts), Python (data analysis, scripts) |

---

## How I work

- **Calibration before building.** I verify the architectural assumption before writing the first node. If the work turns out unnecessary, the client hears that — not an invoice.
- **Cost-conscious AI.** Cheap deterministic layer first, small model second, big model only on the shortlist. The client sees total cost of ownership as a design decision, not a surprise bill.
- **Ranges, not fake precision.** "$80–100, but I want to see the actual setup before confirming" — and then a Loom of the fix.
- **Async and written.** Documentation in the client's messages, backups before every production change, rollback windows stated up front.

---

## Certifications

n8n Level 1 (#8525) · n8n Level 2 (#3729) · Make.com Basics, Foundation, Intermediate, Advanced, AI Automation Explorer · AI Expert Program (Marketing Automation School)

## Background

Before automation: 7 years as the top specialist on spring-coiling machinery in a narrow industrial niche — trained staff, translated between shop floor and management. The systems thinking and the habit of finding the actual root cause came from there. Before that: 2 years building and coaching a sales structure.

Languages: Ukrainian (native), Russian, Polish (9 years in Poland), English — all client work runs in English, written and async.

## Contact

Available for automation projects — [Upwork profile](https://www.upwork.com/freelancers/skillmaster).
