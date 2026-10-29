## Engel Mandujano · AI Software Engineer

LLM systems, RAG and agentic workflows · 7 years delivering HW/SW programs at Bosch

I build and run production LLM systems: a RAG for technical requirements used by about 10 engineers, and a project-management agent used by a team of 8. Both run on Gemini. I work spec-first, let agents do long unattended runs, and put hard quality gates around the code they write (mypy strict, ruff, pytest, CI, an automated reviewer, security scans).

I studied Mechanical-Industrial Management Engineering. That degree taught me to think in systems, processes and bottlenecks, which is how I approach software too. My coding is recent (about a year) and AI-assisted, and my job is to specify, verify and own what ships.

Passionate about: art, ballet, music, AI, business and people.


#### Tools I've built with

**Languages**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=flat-square&logo=css&logoColor=white)
![Python](https://img.shields.io/badge/Python_(AI--assisted)-3776AB?style=flat-square&logo=python&logoColor=white)

**Frontend**

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![React Flow](https://img.shields.io/badge/React_Flow-1A192B?style=flat-square&logo=xyflow&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square&logo=react&logoColor=white)

**Backend & Data**

![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

**Testing & DevOps**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)

**Data & Visualization**

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![D3](https://img.shields.io/badge/d3-F9A03C?style=flat-square&logo=D3&logoColor=white)

**AI & Automation**

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claudecode&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![NotebookLM](https://img.shields.io/badge/NotebookLM-000000?style=flat-square&logo=notebooklm&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat-square)
![Ragas](https://img.shields.io/badge/Ragas-evals-4B32C3?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-Qwen-333333?style=flat-square)

**Project Management**

![Asana](https://img.shields.io/badge/Asana-F06A6A?style=flat-square&logo=asana&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-00AEEF?style=flat-square&logo=azuredevops&logoColor=white)


## Projects

| Project | What it does | Stack | Version | Status | Link |
|---|---|---|---|---|---|
| **Requirements RAG** (internal, at work) | Answers technical-requirement questions for about 10 engineers with source citations. Refuses when no source scores high enough. Failed queries feed a regression set | Python, Gemini Flash, PostgreSQL pgvector + FTS, Cohere rerank, Pydantic, Ragas, Langfuse, Docker Compose | | ![Live](https://img.shields.io/badge/in_production-success?style=flat-square) | Internal |
| **PM agent** (internal, at work) | Cron agent that turns daily meeting minutes and emails into timeline and to-do updates for an 8-person PM team | Gemini Flash-Lite | | ![Live](https://img.shields.io/badge/in_production_6_mo-success?style=flat-square) | Internal |
| **mise-en-place** | Quality-gate catalog for apps and web apps: token fuzzing, BOLA/RLS tests, secret scanning, dependency audits, prompt-injection red-teaming. Built to block PRs automatically | Python, TypeScript, GitHub Actions, gitleaks, Garak | | ![Dev](https://img.shields.io/badge/in--development-yellow?style=flat-square) | Private |
| **Batuta** | Claude Code plugin that applies program-management discipline to AI agents: classifies each task and routes it by model tier (Opus plans, Sonnet executes, Haiku reads), with delegation briefs, an escalation ladder and an independent verifier | Claude Code plugin (skills, subagents) | ![Version](https://img.shields.io/badge/version-0.1.0-blue?style=flat-square) | ![Stable](https://img.shields.io/badge/Published-success?style=flat-square) | [Repo](https://github.com/engelbertgm/Batuta) |
| **Demi** | Ballet musicality and exercise trainer. 22 paying users, 100% retention (5 mo) | React+Tailwind, JavaScript, Firebase, ESLint, Vite, shadcn/ui | ![Version](https://img.shields.io/badge/version-1.0-success?style=flat-square) | ![Stable](https://img.shields.io/badge/Deployed-success?style=flat-square) | [demi-ballet.web.app](https://demi-ballet.web.app) |
| **StackForge** | Visual technology-stack builder. 350-entry catalog where compatibility is declared as data, so the diagram is derived from rules rather than drawn by hand | React+TS+Tailwind, shadcn/ui, React Flow, Zustand, Vite | ![Version](https://img.shields.io/badge/version-0.3.0-blue?style=flat-square) | ![Local](https://img.shields.io/badge/Runs_locally-success?style=flat-square) | [Repo](https://github.com/engelbertgm/StackForge) |
| **Oikofi** | Personal finance tracker. Multi-account, MSI handling, Sankey cash-flow viz | TS+Tailwind+shadcn/ui, PostgreSQL, React via Next.js, D3 | ![Version](https://img.shields.io/badge/version-0.1.4-blue?style=flat-square)  ![Next](https://img.shields.io/badge/next-0.2.0--dev-yellow?style=flat-square) | ![Next](https://img.shields.io/badge/active--dev-success?style=flat-square) | Private |
| **Chord Ghost** | MuseScore 4 plugin. Roman-numeral analysis, cadence detection, custom canvas renderer | QML | ![Version](https://img.shields.io/badge/version-5.4.2-blue?style=flat-square) | ![Stable](https://img.shields.io/badge/Deployed-success?style=flat-square) | [Repo](https://github.com/engelbertgm/ChordGhost) |
| **Construction Ops Dashboard** | Full-stack ops dashboard. Cost, schedule, revenue, cash-flow, CRM. Self-hosted on a VPS with Docker Compose, Sentry alerts, Grafana KPIs | Next.js, TypeScript, PostgreSQL/Prisma, Clerk, D3 | ![Version](https://img.shields.io/badge/version-1.7-lightgrey?style=flat-square) | ![NDA](https://img.shields.io/badge/private%20%2F%20NDA-lightgrey?style=flat-square) | Private |
| **Risk-Neutral Density (Breeden-Litzenberger)** | Recovering implied risk-neutral density from options data | Python | | ![Next](https://img.shields.io/badge/in--progress-yellow?style=flat-square) | TBD |
<!--
## Upcoming

![Private](https://img.shields.io/badge/private-lightgrey?style=flat-square) ![Designing](https://img.shields.io/badge/designing%20full%20stack-yellow?style=flat-square)


| Use | Stack |
|---|---|
| **Frontend** | ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white) ![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white) ![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white) |
| **Data & Backend** | ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Auth](https://img.shields.io/badge/Auth-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![RLS](https://img.shields.io/badge/RLS-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![API](https://img.shields.io/badge/API-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Edge Functions](https://img.shields.io/badge/Edge_Functions-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Realtime](https://img.shields.io/badge/Realtime-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Cron](https://img.shields.io/badge/Cron-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **Application State** | ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square&logo=react&logoColor=white) |
| **Quality** | ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white) ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white) |
| **Infra** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **Business Integrations** | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Intercom](https://img.shields.io/badge/Intercom-1F8DED?style=flat-square&logo=intercom&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) |
-->
