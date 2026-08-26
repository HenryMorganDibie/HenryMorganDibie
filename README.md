# Henry Dibie

**ML Systems Engineer · Backend & API Engineering · Agentic AI · Credit Risk & Quant Analytics**
*Open to remote & international engagements — Freelance · Contract · Full-time*

Production-grade ML and backend engineer with 5+ years building systems that run in the real world — not just notebooks. My work spans production APIs and service architecture, agentic pipelines, RAG backends, forecasting infrastructure, credit risk engines, and data platforms, serving clients across fintech, telecom, SaaS, and fixed income.

Top Rated on Upwork · 100% Job Success Score

---

## What I Build

**Backend & API Engineering**
Cloud Functions, FastAPI, and gRPC services — Firestore/PostgreSQL schema and security-rule design, auth flows, and CI pipelines built for production, not demos. Built the backend for a multi-vendor marketplace platform end-to-end: 120 Cloud Functions, an 811-line Firestore/Storage security-rules layer, a provider-agnostic subscription engine spanning three payment processors (Paystack, Flutterwave, Stripe) on one shared idempotent webhook core, a five-tier role-based admin system, a scored chat-moderation engine, and 491 acceptance tests across 14 suites with denial-path coverage — plus a security review that caught and fixed a Firestore rules privilege-escalation bug and a mobile-app auth bypass. Also built the vendor billing/subscription portal and the public marketing site + CMS that sit on top of it. Separately, refactored a gRPC monorepo at production scale (N+1 query elimination, bcrypt migration, unified error taxonomy, request tracing) and built AjoLedger's coordination backend for rotating savings groups and schema-watch, a local proxy that diffs API contract shape to catch breaking changes before they ship.

**Agentic AI & RAG Systems**
LangGraph multi-agent pipelines (supervisor + sub-agent architectures), production RAG backends with pgvector + BM25 + cross-encoder reranking, LLM-powered analytics assistants, Manuscript Companion Chat with Voice Drift Analytics, and GenAI workflows with structured outputs. Built across Groq/Llama, OpenAI, and custom fine-tuned models. Audited LoRA fine-tunes at production scale — diagnosed a ~50pp BFCL regression on a Qwen-2.5-7B model.

**ML Systems & Data Infrastructure**
End-to-end pipelines from raw ingestion to deployed inference. Real-time platforms with FastAPI, PostgreSQL/TimescaleDB, and Azure. Prophet and Darts forecasting. Load-tested at 30,000 subscribers — 5.4M records processed at 1,480 subscribers/second, 100% prediction success rate. Salary prediction pipelines, churn engines, and production ML assessments delivered under tight deadlines.

**Credit Risk & Quant Analytics**
Scorecard development, PD/LGD/EAD modelling, and portfolio analytics. XGBoost/Logistic Regression credit models (15% improvement in approval precision at Renmoney). MBS spec pool pay-up analyzers and CMO inventory matching engines for fixed income clients. Full corporate credit risk frameworks for structured lending.

**Data Engineering & Automation**
dbt, Prefect, PySpark, SFTP ingestion pipelines, Snowflake Semantic Layer + dbt MetricFlow, macroeconomic data extraction across 54 African countries. I connect pipelines to decision surfaces.

**Full-Stack Products**
Firebase multi-vendor marketplace backends, Chrome extensions, PWAs, and Android apps. I build products end-to-end when the problem demands it. On one private client engagement I owned the entire stack: the Firebase backend described above, a React Native/Expo marketplace app (customer + vendor, iOS/Android/Web) with real-time chat, cart/checkout, order lifecycle tracking, and subscription-gated feature tiers, plus a companion Next.js vendor billing portal and the public marketing site/CMS in front of it.

---

## Selected Projects

### Agentic AI & RAG

| Project | What it does |
|---|---|
| [`deal-intelligence-agent`](https://github.com/HenryMorganDibie/deal-intelligence-agent) | 8-node LangGraph pipeline — M&A, credit risk, distressed asset signals across SEC EDGAR, African exchanges, global news |
| [`nigerian-fintech-agent`](https://github.com/HenryMorganDibie/nigerian-fintech-agent) | 7-layer fraud intelligence platform — agentic reasoning over transaction signals, CBN/EFCC/NFIU regulatory citations, Nigerian language routing, NDPA 2023 audit logging |
| [`knowledge-rag-api`](https://github.com/HenryMorganDibie/knowledge-rag-api) | Production RAG backend — pgvector + BM25 + RRF fusion, cross-encoder reranking, ACL filtering, atomic chunk publishing |
| [`snowflake-semantic-agent`](https://github.com/HenryMorganDibie/snowflake-semantic-agent) | Conversational analytics agent over Snowflake — dbt MetricFlow, Semantic Layer API, Horizon Catalog integration |
| [`pulse-agent`](https://github.com/HenryMorganDibie/pulse-agent) | LangGraph multi-agent system built for DSN × BCT Hackathon — real-time signal orchestration across multiple sub-agents |
| [`querymind`](https://github.com/HenryMorganDibie/querymind) | AI business analyst — ask questions in plain English, get charts, insights, and decisions straight from your SQL database |

### Backend & APIs

| Project | What it does |
|---|---|
| **Multi-vendor marketplace backend** *(private client project)* | 120 Cloud Functions, an 811-line Firestore/Storage security-rules layer, a 3-provider subscription/payment engine (Paystack/Flutterwave/Stripe) on one shared idempotent webhook core, 5-tier role-based admin access, scored chat moderation, 491 acceptance tests across 14 suites with denial-path coverage |
| **Multi-vendor marketplace app** *(same private client, full stack)* | React Native/Expo customer + vendor app on top of the backend above: real-time chat across 4 conversation types, catalog/cart/checkout, order lifecycle tracking, subscription-gated feature tiers, vendor analytics dashboards, plus a Next.js vendor billing portal and public marketing site/CMS |
| [`chirp-api-refactoring`](https://github.com/HenryMorganDibie/chirp-api-refactoring) | Production audit & refactor of a Python gRPC monorepo — N+1 query elimination, bcrypt migration, unified error taxonomy, CI with affected-detection |
| [`ajoledger-api`](https://github.com/HenryMorganDibie/ajoledger-api) | FastAPI + PostgreSQL backend for rotating savings groups (ajo/esusu/adashe) — tracks contributions, rotation, and disputes without ever holding funds |
| [`mvno-intelligence-hub`](https://github.com/HenryMorganDibie/mvno-intelligence-hub) | Azure-deployed subscriber analytics API — Prophet forecasting, TimescaleDB, FastAPI, live SFTP ingestion every 15 mins |
| [`schema-watch`](https://github.com/HenryMorganDibie/schema-watch) | Local proxy that diffs API response shape (not values) to catch breaking contract changes before they ship — CI enforcement, cloud monitoring, AI coding-agent context |
| [`compliance-tracker`](https://github.com/HenryMorganDibie/compliance-tracker) | Multi-tenant compliance/regulatory-filing tracker — Expo app + Supabase backend |

### ML, Credit Risk & Research

| Project | What it does |
|---|---|
| [`churn-intelligence-platform`](https://github.com/HenryMorganDibie/churn-intelligence-platform) | End-to-end churn prediction platform with explainability and intervention routing |
| [`corporate-credit-risk-framework`](https://github.com/HenryMorganDibie/corporate-credit-risk-framework) | Structured credit risk framework for corporate lending — PD/LGD/EAD modelling, scorecard calibration |
| [`narrative-harm-classifier`](https://github.com/HenryMorganDibie/narrative-harm-classifier) | NLP classifier — Precision 1.000, FPR 0.000 on held-out test set |
| [`nexus-quant-framework`](https://github.com/HenryMorganDibie/nexus-quant-framework) | Quantitative analytics framework for financial modelling and strategy backtesting |
| [`worldmodel-dreamer`](https://github.com/HenryMorganDibie/worldmodel-dreamer) | From-scratch Dreamer-style RSSM world model — latent dynamics, imagined rollouts, actor-critic trained via value gradients |

### Data Infrastructure & Engineering

| Project | What it does |
|---|---|
| [`talentpulse-salary-ml`](https://github.com/HenryMorganDibie/talentpulse-salary-ml) | End-to-end ML salary prediction pipeline — feature engineering, model training, inference API |

### Products & SaaS

| Project | What it does |
|---|---|
| [`the-scribe`](https://github.com/HenryMorganDibie/the-scribe) | AI writing assistant for Christian authors — FastAPI + PostgreSQL + pgvector, RAG-powered Manuscript Companion Chat, Voice Drift Analytics, mobile-responsive |
| [`ajoledger-web`](https://github.com/HenryMorganDibie/ajoledger-web) | PWA frontend for AjoLedger — phone+email sign-in, group creation, invitations, payment matrix, proof-of-payment upload |
| [`scrollbreak`](https://github.com/HenryMorganDibie/scrollbreak) | Full-stack doomscrolling intervention — Chrome extension, PWA, Android app, Express backend |
| [`subscription-manager`](https://github.com/HenryMorganDibie/subscription-manager) | Track and manage recurring subscriptions |
| [`Ecclesia-CheckIn`](https://github.com/HenryMorganDibie/Ecclesia-CheckIn) | QR-based fraud-proof attendance system — live deployment to a real church community |

---

## Stack

**Languages:** Python · R · SQL · JavaScript
**Backend & APIs:** FastAPI · Express · gRPC · PostgreSQL · SQLAlchemy · REST/GraphQL · Auth & Session Design · CI/CD
**ML/Forecasting:** XGBoost · LightGBM · Prophet · Darts · Scikit-Learn · PyTorch · SHAP
**Agentic & AI:** LangGraph · LangChain · pgvector · FAISS · OpenAI · Groq/Llama · Whisper · RAG pipelines
**Data Engineering:** TimescaleDB · Snowflake · BigQuery · dbt · PySpark · Prefect · GitHub Actions
**Infrastructure & Cloud:** Azure · AWS · GCP · Docker · Firebase · Supabase
**Visualization:** Power BI · Plotly/Dash · Streamlit · Metabase · Recharts

---

## Background

- **ML Systems & Backend Engineer (Freelance)** — MVNO subscriber analytics, production APIs, RAG backends, agentic pipelines, credit risk systems, quant tools, full-stack products
- **Data Research Analyst, Automation & AI** — Stears
- **Credit Risk Analyst (Data Science)** — Renmoney Microfinance Bank
- **Data Scientist** — Nupat Technologies
- **Education:** Data Analytics — Turing College (Digital Explorers II Scholar) · BSc Business Administration

---

## Let's Work Together

Open to freelance, contract, and full-time roles (Remote · Hybrid · Onsite) — ML systems, backend & API engineering, agentic AI, credit risk modelling, and data infrastructure.

📬 [LinkedIn](https://www.linkedin.com/in/kinghenrymorgan/) · [Medium](https://medium.com/@KingHenryMorgansDiary)
