# Dmytro Dumka — AI & Automation Specialist

**30+ working builds · 7 years engineering background before automation**\
Building automation systems that replace manual work: lead pipelines, AI-filtered monitoring, content pipelines, CRM architecture.\
Architect-first, not task-first — I check the assumption before building the thing.\
Ukraine 🇺🇦 · based in Poland 🇵🇱 · working globally, async-first

---

## Stack

**Automation & Orchestration**\
![n8n](https://img.shields.io/badge/n8n_(self--hosted)-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4F00?style=flat-square&logo=zapier&logoColor=white)
![GoHighLevel](https://img.shields.io/badge/GoHighLevel-1E7FDB?style=flat-square&logoColor=white)
![Apify](https://img.shields.io/badge/Apify-97D700?style=flat-square&logo=apify&logoColor=black)
![REST/OAuth2](https://img.shields.io/badge/REST_·_OAuth_2.0-555555?style=flat-square&logoColor=white)

**AI & LLM**\
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic_Claude-D97706?style=flat-square&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logoColor=white)
![Retell AI](https://img.shields.io/badge/Retell_AI-3B82F6?style=flat-square&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-121142?style=flat-square&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-01CC26?style=flat-square&logoColor=white)

**Data & Backends**\
![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=flat-square&logo=airtable&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Softr](https://img.shields.io/badge/Softr-2B2358?style=flat-square&logoColor=white)

**Chatbots & Communication**\
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![ManyChat](https://img.shields.io/badge/ManyChat-0084FF?style=flat-square&logoColor=white)
![Voiceflow](https://img.shields.io/badge/Voiceflow-3D82F6?style=flat-square&logoColor=white)
![Mailgun](https://img.shields.io/badge/Mailgun-F06B66?style=flat-square&logo=mailgun&logoColor=white)
![SPF/DKIM/DMARC](https://img.shields.io/badge/SPF_·_DKIM_·_DMARC-555555?style=flat-square&logoColor=white)

**Content & Media**\
![Creatomate](https://img.shields.io/badge/Creatomate-6366F1?style=flat-square&logoColor=white)
![Replicate](https://img.shields.io/badge/Replicate-000000?style=flat-square&logo=replicate&logoColor=white)
![CloudConvert](https://img.shields.io/badge/CloudConvert-D63AFF?style=flat-square&logoColor=white)
![Heygen](https://img.shields.io/badge/Heygen-7E3AF2?style=flat-square&logoColor=white)

**Infrastructure & DevOps**\
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx_Proxy_Manager-009639?style=flat-square&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's_Encrypt-003A70?style=flat-square&logo=letsencrypt&logoColor=white)

**Languages & Documents**\
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pptxgenjs](https://img.shields.io/badge/pptxgenjs_·_OOXML-B7472A?style=flat-square&logoColor=white)
![Chart.js](https://img.shields.io/badge/HTML_briefings_·_Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

---

## What I Build

- **AI pipelines** — hybrid rule → LLM filtering, vision analysis, structured JSON output with resilient validation. Every AI decision has an explicit answer to "why isn't this a regex?"
- **Workflow automation** — n8n (self-hosted or cloud) and Make. Error handling, logging and dedup state built in from the first version, not bolted on after the first silent failure.
- **CRM architecture** — GoHighLevel workflow design, platform-limitation workarounds, deduplication, DNS-level email deliverability, multi-calendar sync.
- **Self-hosted infrastructure** — production n8n on Oracle Cloud Free Tier: Docker, Nginx Proxy Manager, Let's Encrypt. $0/month, no execution limits, full data control.
- **Web & funnels** — landing pages, business sites, multi-step animated forms; domains, hosting and SSL handled end-to-end.

---

## Selected Projects

**Government Tender Monitor**\
Per-minute polling of a public procurement API for a German B2B supplier: hybrid rule + gpt-4o-mini filter (~95% fewer LLM calls), cross-run dedup, 4 parallel outputs. Client's AI cost ~$10–15/month. → [n8n-tender-monitor](https://github.com/TrueSkillMaster/n8n-tender-monitor)

**AI Carousel Factory**\
Instagram carousel URL → Claude vision brief → AI image generation → branded templates → 7 PNGs in ~3.5 min at ~$0.30/post. Own product, piloted with an AI school. → [ai-carousel-factory](https://github.com/TrueSkillMaster/ai-carousel-factory)

**Service-Business SaaS Platform**\
UK bin-cleaning service turned into a productized system: WordPress front, GoHighLevel back office, messaging automation, payment and route workflows.

**RAG Proposal Engine**\
Self-hosted RAG system on Claude API that drafts tailored freelance proposals from a knowledge base of past builds and outcomes. Own internal product.

**Funnel Ecosystem for a Fitness Coach**\
Landing site + multi-step animated intake form + follow-up funnel — design, build, hosting and SSL end-to-end.

**CRM Pipeline Collision Fix**\
GHL sub-account where booked clients were cloned into the leads pipeline weekly: tag-proxy pattern, bulk-tag of 327 contacts, dedup by email → phone. → [ghl-architecture-patterns](https://github.com/TrueSkillMaster/ghl-architecture-patterns)

---

## How I Work

- **Calibration before building** — I verify the architectural assumption before writing the first node. If the work turns out unnecessary, the client hears that, not an invoice.
- **Cost-conscious AI** — cheap deterministic layer first, small model second, big model only on the shortlist. Total cost of ownership is a design decision, not a surprise bill.
- **Ranges, not fake precision** — an estimate range up front, then a Loom of the actual fix.
- **Async and written** — documentation in the client's channel, backups before every production change, rollback windows stated up front.

---

## Certifications & Background

n8n Level 1 & 2 · Make.com Basics → Advanced + AI Automation Explorer · AI Expert Program

Before automation: 7 years as the top specialist on industrial spring-coiling machinery — root-cause habits and systems thinking come from there. Languages: Ukrainian, Russian, Polish, English (all client work in English, written and async).

---

## Connect

[![Upwork](https://img.shields.io/badge/Upwork-Hire_me-14A800?style=flat-square&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/skillmaster)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dmytro_Dumka-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/skillmaster/)
[![Website](https://img.shields.io/badge/dumka.tech-Portfolio-8B5CF6?style=flat-square&logo=googlechrome&logoColor=white)](https://dumka.tech)
