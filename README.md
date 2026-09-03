<img src="./banner.svg" alt="Aftab Afridi — Full-stack developer in Dubai" width="100%" />

### Hey, I'm Aftab 👋

I build production web applications and the backends that hold them up — schema design, API layers, authentication, real-time systems, and the third-party integrations that are usually the hardest part.

🔭 &nbsp;Currently building **[Foundly](https://foundly.ae)**, a bilingual lost-and-found marketplace for the UAE
⚡ &nbsp;Most at home in Next.js, TypeScript and PostgreSQL — with six years of WordPress underneath
🌍 &nbsp;I ship English/Arabic products, and speak English, Urdu, Hindi and Pashto
📫 &nbsp;Reach me at **affiafridi.dev@gmail.com**

<img src="./stats.svg" alt="6+ years · 2 production platforms · 259 API endpoints · 46 data models · 740+ commits in 2026" width="100%" />

<br />

## 🧩 &nbsp;Foundly &nbsp;·&nbsp; founder & sole developer

<a href="https://foundly.ae"><img src="https://img.shields.io/badge/🔴_live-foundly.ae-D99C4A?style=flat-square&labelColor=0F1B2D" alt="foundly.ae" /></a>
<a href="https://foundly.pk"><img src="https://img.shields.io/badge/🔴_live-foundly.pk-D99C4A?style=flat-square&labelColor=0F1B2D" alt="foundly.pk" /></a>
<img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
<img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />

A bilingual English/Arabic lost-and-found marketplace for the UAE. Built it, launched it, run it.

- **Bilingual at the schema level** — Arabic titles, descriptions and SEO fields are first-class columns, not a translation table
- **Deterministic matching engine** — scores lost↔found pairs 0–100 on token similarity with a custom stemmer, category and city hierarchy traversal, and date proximity
- **Notification fan-out** — matches reach in-app, web push and email, deduplicated by normalized pair key, off the moderation response path
- **Real-time chat** — Socket.IO authenticated by parsing NextAuth JWTs at handshake, with server-side room-membership verification
- **Two-tier caching** — in-flight request deduplication and twelve TTLs tuned per data volatility, from 10s to 12h
- **Self-hosted and operated** — PM2 cluster mode behind nginx on Ubuntu, DB-backed rate limiting that survives restarts, cron cleanup, nightly offsite backups

`83 endpoints` &nbsp;·&nbsp; `23 models` &nbsp;·&nbsp; `39 migrations` &nbsp;·&nbsp; `81 pages` &nbsp;·&nbsp; `537 commits`

<br />

## 💬 &nbsp;WhatsApp business operations platform

<img src="https://img.shields.io/badge/private-employer_work-5E7C99?style=flat-square&labelColor=0F1B2D" alt="private" />
<img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 15" />
<img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud Run" />

A team inbox, visual bot-flow builder, campaign engine, order management and customer CRM behind one internal application.

- **Real-time multi-agent inbox** — Server-Sent Events over PostgreSQL `LISTEN/NOTIFY` with heartbeats and clean unlisten
- **Campaign queue** — claims work with `FOR UPDATE SKIP LOCKED` so overlapping cron runs can't double-send
- **Custom session auth** — opaque tokens SHA-256 hashed at rest, five roles, dual-key per-IP and per-email rate limiting, role-scoped data masking applied in SQL
- **Nine integrations** — Meta WhatsApp Cloud API, Instagram, OpenAI, Shopify, WooCommerce, CCAvenue, Google Sheets, Cloud Storage
- **Cryptography against vendor specs** — RSA-OAEP/AES-GCM for Meta's encrypted Flows endpoint, AES-128-CBC for payment gateway callbacks
- **AI intent pipeline** — GPT-4o-mini classification, GPT-4o vision, Whisper transcription, with response caching and atomic SQL-enforced daily usage caps
- **Companion bot** — separate Python/FastAPI service on Cloud Run driving the customer-facing conversational flow

`176 handlers` &nbsp;·&nbsp; `23 models` &nbsp;·&nbsp; `36 migrations` &nbsp;·&nbsp; `5 roles` &nbsp;·&nbsp; `~45k lines`

<br />

## 🛠 &nbsp;Stack

|  |  |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Infrastructure** | ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white) |
| **Integrations & AI** | ![WhatsApp](https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=flat-square&logo=whatsapp&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Shopify](https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white) ![Meta](https://img.shields.io/badge/Meta_Graph_API-0866FF?style=flat-square&logo=meta&logoColor=white) |
| **WordPress** | ![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white) ![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white) ![Crocoblock](https://img.shields.io/badge/Crocoblock_·_ACF-1B1B1B?style=flat-square) |
| **Automation** | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Make](https://img.shields.io/badge/Make.com-6D00CC?style=flat-square&logo=make&logoColor=white) |

<br />

## 🔗 &nbsp;Elsewhere

<a href="https://affiafridi.com"><img src="https://img.shields.io/badge/Portfolio-affiafridi.com-D99C4A?style=for-the-badge&labelColor=0F1B2D" alt="Portfolio" /></a>
<a href="https://linkedin.com/in/affi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:affiafridi.dev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
