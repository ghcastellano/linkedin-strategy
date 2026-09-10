# Portfolio Dossier — Built Assets for Business Viability Assessment

**Purpose:** Snapshot of what I've already built, so you can assess the viability of turning any of it into a business. Client names are anonymized (e.g., "Company in the energy sector"). Each item is tagged 🟢 **own IP (potentially sellable)** or 🟡 **client engagement (proves capability, IP not mine to sell)**.

**Builder profile:** Solo builder / consultant. Ships full-stack products fast — React/Next.js + Tailwind front ends, FastAPI/Node back ends, Postgres/Supabase/Firebase, OpenAI GPT-4o integrations, deployed on Vercel. Comfortable across web, mobile (Flutter), data, and AI agents.

---

## 🟢 Own IP — candidate products

### 1. Label & Traceability System ("Soo Tech / OOTech")
- **What it is:** Product control + traceability system with **label printing**. Web admin (PHP/Slim + Bootstrap, Dockerized) **plus a Flutter mobile app** that drives Niimbot Bluetooth label printers. Includes a local WebSocket print service for client machines.
- **Stage:** Most mature / real-world oriented — has web + mobile + on-prem print service. Looks like an actual operating product.
- **Sector:** Manufacturing / retail / logistics traceability.
- **Business angle:** Vertical SaaS for SMB traceability & labeling. Recurring revenue + hardware tie-in (printers). Clear B2B buyer.

### 2. Habit App for Women — "Florir"
- **What it is:** Habit-building / self-esteem app aimed at women. Next.js 14 + Supabase + Framer Motion.
- **Stage:** MVP-level web app.
- **Sector:** Consumer wellness / femtech.
- **Business angle:** Subscription consumer app; strong niche + brand. Needs growth/retention proof.

### 3. WealthPlanner Pro
- **What it is:** Wealth/financial planning app with **AI (OpenAI)** and **PDF report generation** (react-pdf / jsPDF), React 19 + Firebase + React Router.
- **Stage:** Early app, core stack in place.
- **Sector:** Fintech / personal finance / advisory.
- **Business angle:** Tool for independent financial advisors (white-label reports) or B2C planning. Regulatory care needed.

### 4. Sanitary Inspection System ("InspeçãoSanitária") — most iterated
- **What it is:** Web system that ingests sanitary-inspection PDF reports, uses **AI to generate corrective action plans**, and supports collaborative management across consultants, managers, and admins. **Three iterations exist:** v1 (Vertex AI + Google Drive + WeasyPrint PDF), a Flask + PostgreSQL/Neon + GPT-4o + Google Drive build deployed on **Google Cloud Run**, plus an MVP repo.
- **Stage:** Most-iterated of the consumer/vertical products — real backend, AI pipeline, PDF generation, role-based access, serverless deploy.
- **Sector:** GovTech / FoodTech / compliance.
- **Business angle:** SaaS for sanitary consultants, municipal health agencies, or food businesses managing inspections & corrective plans. The "PDF in → action plan out" loop is a concrete, sellable wedge.

---

## 🟢 Own-ish IP — built in a consulting context but generic/productizable

### 5. AI Proposal Generator
- **What it is:** Paste a client email or brief → get a complete **10-section commercial proposal in ~30s**. Extracts client/industry/challenge, industry-aware tone, win-probability scoring, benchmark vs past proposals, per-section regenerate, proposal history. FastAPI + GPT-4o + Postgres + React/Vite.
- **Stage:** **Deployed and demoable** (live in production).
- **Business case (from the build):** 3–5 days → 30 seconds per proposal; 3 people → 1.
- **Sector:** Sales enablement / professional-services automation.
- **Business angle:** Strong horizontal SaaS — every consultancy, agency, and B2B sales team writes proposals. Clear time-to-value pitch.

### 6. Autonomous Analytics Copilot (NL → SQL)
- **What it is:** Ask business questions in natural language → instant answers with **charts, the generated SQL, confidence, and data lineage**. GPT-4o agent generates SQL, self-corrects on errors. FastAPI + React + PostgreSQL ("Lakehouse" sim).
- **Stage:** Working PoC.
- **Sector:** Data analytics / BI / "talk to your data".
- **Business angle:** Hot category. Differentiator here = transparency (SQL + lineage + confidence), which enterprises demand. Crowded space — needs a wedge (vertical or governance angle).

### 7. JiraForge — Jira Project Config Platform
- **What it is:** Internal platform to **provision Jira projects across multiple client tenants** from a template library; encrypted credential storage (AES-256-GCM), Jira REST orchestration, roll-up rules, deploy wizard. Next.js 14 + Supabase + FastAPI roll-up microservice. Tests in place (Jest + RTL).
- **Stage:** **Deployed** (templates are the core feature).
- **Sector:** DevTools / PMO tooling / Atlassian ecosystem.
- **Business angle:** Atlassian Marketplace app or SaaS for agencies/PMOs that spin up standardized Jira setups repeatedly. Defined buyer, recurring need.

### 8. Scrum Maturity Dashboard
- **What it is:** Connects to **Jira Cloud** and scores team Scrum maturity across 3 pillars (Delivery Predictability, Flow & Quality, Team Ownership) with auto-classified levels and interactive charts. Node/Express + React/Tailwind.
- **Stage:** Functional dashboard.
- **Sector:** Agile/DevEx analytics.
- **Business angle:** SaaS for agile coaches / engineering leaders. Pairs naturally with JiraForge (same Jira ecosystem) — could be one product line.

---

## 🟢 More own-IP repos (pulled from private GitHub)

### A. "Chama no Site" — web lead/contact tool (2 versions)
- Vite + React + shadcn/ui (built via Lovable). Two iterations of the same product.
- **Sector:** MarTech / SMB websites / lead capture.
- **Business angle:** Small embeddable tool/widget play; needs a clear single job-to-be-done to stand out.

### B. Personal Finance Manager ("Controle Mensal Financeiro")
- React + TypeScript + Vite front end with a FastAPI/SQLAlchemy back end.
- **Sector:** Personal finance / fintech (B2C). Sibling to WealthPlanner — could merge.
- **Business angle:** B2C budgeting app; crowded, but pairs with WealthPlanner toward one finance suite.

### C. Subscripify Growth Hub
- Vite + React + shadcn/ui (Lovable). Subscription/growth-focused app.
- **Sector:** SaaS growth / subscription management.
- **Business angle:** Tooling for subscription businesses; validate the specific pain it solves.

### D. Soo Tech "Neural" sandbox
- Next.js (App Router) experiment, part of the **Soo Tech** product family (see #1 Traceability/Labeling).
- **Business angle:** R&D arm of the traceability product — relevant as evidence Soo Tech is an active product line, not a one-off.

### E. "Next-Gen Operations Strategy" microsite (thought leadership — *my own content*)
- A polished strategy microsite authored by me: Executive Summary, Market Shift, "The Engine", deep dives (Cognitive Finance, Resilient Supply Chain).
- **Sector:** Thought leadership / consulting positioning.
- **Business angle:** Not a product — but strong **personal-brand / authority asset** (directly relevant to a LinkedIn strategy and to selling consulting).

### F. Booking/Listing template base ("escort-next-replica")
- A purchased Next.js 13 booking/listing/real-estate theme (Chisfis) — a **starter base**, not original IP. Low originality; only relevant if pointed at a specific booking vertical.

## 🟡 Client engagements — prove capability, IP not mine to sell

> These show I can deliver enterprise-grade work, but the IP belongs to the client. Useful as *proof of skill / case studies* (anonymized), not as sellable products.

### 9. Application Portfolio Management / Application Assessment Platform — *Company in the energy sector* ⭐ strong product candidate
- AI-powered APM: upload questionnaires + meeting transcripts → GPT-4 extracts answers, suggests scores across 8 "synergy blocks", strategic 2×2 matrix (BVI vs THI), insights, NL Q&A. Streamlit + SQLAlchemy/Postgres + OpenAI.
- **Proof of:** AI-assisted enterprise portfolio analysis / application rationalization.
- **⭐ Product angle (clean-room):** The *engagement* is client IP (not sellable), BUT the **methodology + tool are highly productizable** as a generic SaaS: "AI-powered Application Portfolio Assessment / rationalization". App rationalization is a recurring pain for nearly every large enterprise; clear buyer (CIO / Enterprise Architecture office). A from-scratch generic version (no client data/branding) would be one of the strongest standalone bets here — pairs well with the consulting motion (land an assessment engagement, upsell the tool).

### 10. Demand & Portfolio Flow Canvas — *Company in the energy sector*
- Visual swimlane canvas (Intake → Classification → Prioritization → Portfolio → Delivery) to co-design AS-IS flow live in discovery sessions. 86 pre-built drag-drop components, animated edges, Supabase autosave, PNG export, presentation mode. Next.js 16 + @xyflow/react.
- **Proof of:** Facilitation tooling + real-time collaborative canvases.

### 11. Bugs & Capacity Dashboard — *Company in the energy sector*
- Jira bug analysis with sprint trends, test-case tracking, team analytics. Node/Express + Supabase.
- **Proof of:** Jira analytics at team scale.

### 12. Product Management Dashboard — *Company in the online-recruitment sector*
- Epic intelligence, prioritization & portfolio dashboard. (Hosted on the client's internal GitLab.)
- **Proof of:** PM/portfolio analytics.

### 13. Organizational Transformation Board Game — *Consulting firm (IT services sector)*
- Interactive virtual board game for org transformation (drag-drop patterns, agents of change, "Mobius cycle"). Express + Postgres.
- **Proof of:** Gamified enterprise change tooling.

### 14. "Intelligence at Scale" — Data & Analytics offering microsite + decks — *Consulting firm (IT services sector)*
- A client-facing microsite plus offering decks and a technical reference guide for a Data & Analytics evolution offering.
- **Proof of:** Packaging and presenting enterprise D&A offerings (sales/marketing assets).

---

## How to read this for viability

- **Strongest standalone product bets:** #5 Proposal Generator, #7 JiraForge, and **#9 Application Portfolio Assessment (clean-room generic version)** — clear B2B buyers, recurring need; #5 and #7 are demoable today, #9 has a proven engagement behind it and an obvious enterprise buyer (CIO/EA office).
- **Most "real business" feel:** #1 Traceability/Labeling — full product (web + mobile + hardware), tangible SMB market.
- **Hottest market, hardest to win:** #6 Analytics Copilot — needs a sharp wedge.
- **Natural product line:** #7 JiraForge + #8 Scrum Maturity + #11 Bugs Dashboard all live in the Jira/agile ecosystem and could combine into one "engineering operations" suite.
- **Reusable across all of the above:** a proven ability to ship AI-infused full-stack SaaS solo, fast.

**Open questions for you (the assessor):** Which of these has real users or revenue today? Which am I most motivated to run as a business? What's my target market and how do I reach the first 10 paying customers?
