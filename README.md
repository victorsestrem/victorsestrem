# Hi, I'm Victor Sestrem 👋

**Head of Technology · Senior AI Engineer (LLM) · Full Stack** · São Paulo, Brazil · Open to relocating to the U.S.

I build LLM products end to end: **tool-using agents, RAG, evaluation (evals with a simulated customer and blind rubrics) and real-time voice**, on OpenAI, Anthropic, Gemini and local models. I ship the full stack in **TypeScript and Python** (React/Next.js, Node.js/NestJS, FastAPI, PostgreSQL), and I've led engineering teams as Head of Technology and CTO, so I care about architecture, security and delivery as much as the code.

Most of my work is proprietary, so the code stays private. The repositories below are **case studies** covering the problem, what I built, the architecture and my role. I'm happy to walk you through any of them on a call.

## Featured case studies

### AI & agents

| Project | What it is | Stack |
|---|---|---|
| [WhatsApp AI Sales Agent](https://github.com/victorsestrem/whatsapp-ai-sales-agent) | Proprietary events CRM with a guarded, human-in-the-loop LLM sales agent on WhatsApp: router/doer/reviewer, grounded facts, evals with a simulated client | NestJS · Next.js · OpenAI · Anthropic |
| [AI Engineering Operating System](https://github.com/victorsestrem/ai-engineering-operating-system) | How I run many AI coding agents in parallel: coordinator sessions, task briefs, skills per task type, an independent reviewer agent and fail-closed hooks | Claude Code · Cursor · Bash · Next.js |
| [Agent Ops Kit](https://github.com/victorsestrem/agent-ops-kit) | The reusable kit behind it: role-specific subagents, 78 skills, fail-closed hooks with 1,850 tests, a load gatekeeper for parallel agents and a measured token budget (rules cut from 22.6k to 8.5k tokens) | Claude Code · Bash · Python · PostgreSQL |
| [Voice English Tutor](https://github.com/victorsestrem/voice-english-tutor) | Spoken English practice in the browser with real-time interruption, a model fallback chain ending in a local LLM, lessons, pronunciation scoring and spaced review *(personal project)* | Python · Pipecat · Whisper · Kokoro · Ollama |
| [Local Voice Assistant](https://github.com/victorsestrem/local-voice-assistant) | Brazilian Portuguese home voice assistant that runs entirely on the owner's machine, with memory across conversations *(personal project)* | Home Assistant · faster-whisper · Piper · openWakeWord |
| [AI Deal Monitoring Agents](https://github.com/victorsestrem/ai-deal-monitoring-agents) | Scheduled AI agents that browse real travel sites, decide each deal's state by explicit rules, publish a versioned dashboard and alert on Telegram only on change *(personal project)* | Claude Code · Chrome automation · Node.js · Python |
| [Private AI Assistant with RAG](https://github.com/victorsestrem/private-ai-assistant-rag) | On-premise assistant with local embeddings, semantic search and model routing | NestJS · Next.js · Transformers.js · Ollama · Gemini |
| [Car Rental System with AI Customer Service](https://github.com/victorsestrem/car-rental-management-ai) | Rental management with official WhatsApp API inbox and an AI agent that answers customers | Next.js · Drizzle · PostgreSQL · WhatsApp API |
| [AI Guest Concierge on a Tablet](https://github.com/victorsestrem/ai-guest-concierge-tablet) | iPad assistant for venue guests: grounded answers, room control, concierge calls *(in development)* | Next.js · React · Home Assistant · LLM |
| [Meeting Transcription](https://github.com/victorsestrem/meeting-transcription) | Self-hosted Google Meet recording that becomes Word minutes with speaker names, at zero monthly cost *(in development)* | Python · FastAPI · Whisper · pyannote |
| [Smart TV Book Streaming](https://github.com/victorsestrem/smart-tv-book-streaming) | A "Netflix for books" for Smart TV browsers, driven only by the remote control | React · TypeScript · Vite · Cloudflare Pages |

### Products & systems

| Project | What it is | Stack |
|---|---|---|
| [Contract Generation System](https://github.com/victorsestrem/contract-generation-system) | Generates legal contracts from the lawyer's Word templates, Word + PDF | NestJS · Next.js · docxtemplater · Gotenberg |
| [Real Estate Auction Search](https://github.com/victorsestrem/real-estate-auction-search) | São Paulo real estate auctions from banks, auctioneers and court gazettes in one database: 25 polite collectors, total-cost rules, lawsuit stages, map and alerts *(demo)* | Next.js · PostgreSQL/PostGIS · BullMQ · TypeScript |
| [Buffet Management System](https://github.com/victorsestrem/buffet-management-system) | Management product for party venues: sales funnel, visits, proposals, PDF contracts, calendar with conflict locking, installments and roles *(in development)* | Next.js 16 · Drizzle · PostgreSQL |
| [Dental Clinic Management System](https://github.com/victorsestrem/dental-clinic-management-system) | Scheduling, patients, professionals and finance for dental clinics *(in development)* | Next.js · Drizzle · PostgreSQL · Better Auth |
| [Private Chauffeur Booking Platform](https://github.com/victorsestrem/private-chauffeur-booking-platform) | Requests, quotes, rides, driver portal and online booking for a chauffeur company in Paris *(in development)* | Next.js · Prisma · PostgreSQL · Docker |
| [HVAC ERP](https://github.com/victorsestrem/hvac-erp-saas) | Sales, maintenance plans, finance, HR, inventory, client portal | Next.js · Prisma · BullMQ |
| [Mental Health Assessment SaaS](https://github.com/victorsestrem/mental-health-assessment-saas) | Multi-tenant SaaS for mental health assessments | React · Express · Drizzle |
| [PDF Catalog Generator](https://github.com/victorsestrem/pdf-catalog-generator) | Django system that syncs a B2B distributor's products from its ERP and renders branded PDF catalogs; outage diagnosis, security review and ERP migration package *(pilot)* | Python · Django · xhtml2pdf · SQLite |
| [IT Asset Management & Help Desk](https://github.com/victorsestrem/it-asset-helpdesk-system) | Equipment lifecycle, inspections with QR codes, tickets with SLA | NestJS · React · PostgreSQL |
| [NPS & Guest Feedback Platform](https://github.com/victorsestrem/nps-feedback-platform) | Tablet-first NPS at events with QR codes, results and exports; migrated from WordPress | NestJS · Next.js · PostgreSQL |
| [Contract-first ERP Foundation](https://github.com/victorsestrem/event-erp-foundation) | OpenAPI-generated clients, layered API, AI-agent definition of done | Express · React · Drizzle · Playwright |
| [Virtual Wardrobe](https://github.com/victorsestrem/virtual-wardrobe-outfit-planner) | Privacy-first digital closet: background removal that never redraws the garment, dynamic categories, outfit builder and a deterministic recommendation engine with zero AI cost *(personal project, in development)* | Next.js 16 · Prisma · PostgreSQL · Docker |

### Data, infrastructure & tools

| Project | What it is | Stack |
|---|---|---|
| [CRM Backup and Sales Dashboards](https://github.com/victorsestrem/crm-backup-and-sales-dashboards) | Complete re-importable backup of a hosted CRM (API plus a Playwright browser session) into PostgreSQL, SDR/closer dashboards and an auditable lead score | Node.js · PostgreSQL · Playwright · OpenAI |
| [Growth Analytics Dashboard](https://github.com/victorsestrem/growth-analytics-dashboard) | Campaign and messaging metrics from the Kommo API, Excel export | NestJS · Next.js · ExcelJS |
| [WordPress Incident Recovery](https://github.com/victorsestrem/wordpress-incident-recovery) | Response to a website compromise: root cause, clean rebuild, about 470 images reconstructed in a local Docker clone, surgical deploy, hardening and a memory incident | WordPress · Nginx · Docker · AWS · Python |
| [Branded URL Shortener](https://github.com/victorsestrem/branded-url-shortener) | Private team link shortener on YOURLS: UTM catalog, paid traffic guard, audit log, 30 day trash | YOURLS · PHP · MariaDB · Docker |
| [Investor Academy Storefront](https://github.com/victorsestrem/investor-academy-storefront) | Storefront widget live on a news publisher's WordPress, plus the UI design of its subscription platform | HTML · CSS · JavaScript · Elementor |
| [Notch Companion for macOS](https://github.com/victorsestrem/macos-notch-companion) | Privacy-first notch app forked from open source Atoll: notifications, system load and shortcuts, no network | Swift · SwiftUI · AppKit · Accessibility API |

## Stack

`TypeScript` `Node.js` `NestJS` `React` `Next.js` `Angular` `Vue` `React Native (Expo)` `Python` `FastAPI` `Django` `PostgreSQL` `PostGIS` `Prisma` `Redis` `BullMQ` `Playwright` `Docker` `Nginx` `AWS` `OpenAI / Anthropic APIs` `Gemini` `Ollama` `Whisper` `RAG` `AI agents` `LLM evals` `Voice AI (Pipecat)` `Claude Code` `Cursor`

## Contact

[LinkedIn](https://www.linkedin.com/in/victor-sestrem/) · victor-sestrem@hotmail.com
