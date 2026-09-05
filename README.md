<!-- <img src="./banner.svg" alt="Aftab Afridi — Full-stack developer in Dubai" width="100%" /> -->

### Hey, I'm Aftab 👋

I build production web applications and the backends that hold them up — schema design, API layers, authentication, real-time systems, and the third-party integrations that are usually the hardest part.

🔭 &nbsp;Currently building **[Foundly](https://foundly.ae)**, a bilingual lost-and-found community for the UAE<br/>
⚡ &nbsp;Most at home in Next.js, TypeScript and PostgreSQL — with six years of WordPress underneath<br/>
🌍 &nbsp;I ship English/Arabic products, and speak English, Urdu, Hindi and Pashto<br/>
📫 &nbsp;Reach me at **affiafridi.dev@gmail.com**

<br />

## 🧩 &nbsp;Foundly &nbsp;·&nbsp; founder & sole developer

<p>
  <a href="https://foundly.ae"><img src="https://img.shields.io/badge/live-foundly.ae-D99C4A?style=flat-square&labelColor=0F1B2D" alt="foundly.ae" /></a>
  <a href="https://foundly.pk"><img src="https://img.shields.io/badge/live-foundly.pk-D99C4A?style=flat-square&labelColor=0F1B2D" alt="foundly.pk" /></a>
  <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />
</p>

A bilingual English/Arabic lost-and-found community for the UAE. Built it, launched it, run it.

- **Bilingual at the schema level** — Arabic titles, descriptions and SEO fields are first-class columns, not a translation table
- **Deterministic matching engine** — scores lost↔found pairs 0–100 on token similarity with a custom stemmer, category and city hierarchy traversal, and date proximity
- **Notification fan-out** — matches reach in-app, web push and email, deduplicated by normalized pair key, off the moderation response path
- **Real-time chat** — Socket.IO authenticated by parsing NextAuth JWTs at handshake, with server-side room-membership verification
- **Two-tier caching** — in-flight request deduplication and twelve TTLs tuned per data volatility, from 10s to 12h
- **Self-hosted and operated** — PM2 cluster mode behind nginx on Ubuntu, DB-backed rate limiting that survives restarts, cron cleanup, nightly offsite backups

`83 endpoints` &nbsp;·&nbsp; `23 models` &nbsp;·&nbsp; `39 migrations` &nbsp;·&nbsp; `81 pages` &nbsp;·&nbsp; `537 commits`

<br />

## 💬 &nbsp;WhatsApp business operations platform

<p>
  <img src="https://img.shields.io/badge/private-employer_work-5E7C99?style=flat-square&labelColor=0F1B2D" alt="private" />
  <img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 15" />
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud Run" />
</p>

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

<p>
  <b>Languages</b><br/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=databricks&logoColor=white" alt="SQL" />
</p>
<p>
  <b>Frontend</b><br/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white" alt="Radix UI" />
  <img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
</p>
<p>
  <b>Backend & data</b><br/>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
</p>
<p>
  <b>Infrastructure</b><br/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="nginx" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu" />
  <img src="https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white" alt="PM2" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>
<p>
  <b>Integrations & AI</b><br/>
  <img src="https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp Cloud API" />
  <img src="https://img.shields.io/badge/Meta_Graph_API-0866FF?style=flat-square&logo=meta&logoColor=white" alt="Meta Graph API" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white" alt="Shopify" />
  <img src="https://img.shields.io/badge/Google_Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white" alt="Google Sheets" />
</p>
<p>
  <b>WordPress & automation</b><br/>
  <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress" />
  <img src="https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white" alt="WooCommerce" />
  <img src="https://img.shields.io/badge/Crocoblock_·_ACF-1B1B1B?style=flat-square" alt="Crocoblock and ACF" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/Make.com-6D00CC?style=flat-square&logo=make&logoColor=white" alt="Make.com" />
</p>

<br />

## 🔗 &nbsp;Elsewhere

<p>
  <a href="https://affiafridi.com"><img src="https://img.shields.io/badge/Portfolio-D99C4A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/affi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:affiafridi.dev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
