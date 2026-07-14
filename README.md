# Senior LLM & Agentic AI & Full-Stack Engineer

LangGraph · LangChain · PyTorch · OpenCV · FastAPI · React/Next.js · Multi-Tenant SaaS · GCP/AWS

10+ years designing and shipping production systems across autonomous multi-agent AI, LLM-powered applications, machine learning, and computer vision, backed by high-performance backend APIs and modern full-stack, multi-tenant SaaS platforms.

Comfortable owning a project end-to-end: agent orchestration and RAG pipelines, model training and evaluation, real-time video/data pipelines, API and data-model design, and production-grade React/Next.js frontends, with the testing, observability, and security discipline to run it all reliably at scale.

**Contents:** [What I Build](#what-i-build) · [Core Stack](#core-stack) · [Best Practices](#best-practices) · [Projects](#projects)

---

## What I Build

- **Agentic AI Systems** - Multi-agent orchestration, autonomous workflows, tool-calling agents, agent memory & state management with LangGraph, CrewAI & AutoGen
- **LLM Applications** - RAG pipelines (95%+ accuracy), hybrid semantic search, prompt engineering, LLM observability & tracing, vector databases at scale
- **ML & Forecasting Systems** - Time-series forecasting (Temporal Fusion Transformer), model training pipelines, hyperparameter optimization, experiment tracking
- **Computer Vision** - Real-time image/video processing, classification models, gesture recognition, webcam/WebRTC video pipelines
- **High-Performance Backend APIs** - FastAPI + async Python, 10k+ req/min, sub-200ms semantic search over 100GB+ datasets, microservices, gRPC, WebSockets
- **Full-Stack Applications** - React/Next.js 14+ (App Router, RSC), TypeScript, Tailwind CSS frontends backed by scalable Python/Node microservices
- **SaaS & Multi-Tenant Platforms** - Tenant-isolated data models, org/workspace-scoped RBAC, usage-based billing integrations, self-serve onboarding flows

---

## Core Stack

**Agentic AI** - LangGraph · CrewAI · AutoGen · Tool-Calling · Agent Memory · Multi-Agent Orchestration
**LLM & Search** - LangChain · OpenAI GPT-4o/o1 · Anthropic Claude · Hugging Face · RAG Pipelines · Qdrant · Pinecone · Weaviate · Elasticsearch
**Machine Learning** - PyTorch · PyTorch Lightning · PyTorch Forecasting (Temporal Fusion Transformer) · scikit-learn · Optuna · TensorBoard · pandas · NumPy
**Computer Vision** - OpenCV · Image Classification · Gesture Recognition · Real-Time Video Processing · WebRTC (aiortc)
**Backend** - Python · FastAPI · Django · Flask · Node.js · NestJS · GraphQL · REST · gRPC · PostgreSQL · MongoDB · Redis
**Frontend** - React · Next.js · TypeScript · Tailwind CSS · Shadcn/ui · Vue.js · Redux · Zustand
**Cloud & DevOps** - GCP · AWS · Kubernetes · Docker · Terraform · ArgoCD · GitHub Actions · Datadog · Grafana
**SaaS & Multi-Tenancy** - Tenant Isolation (schema/row-level) · Org & Workspace Scoping · RBAC per Tenant · Stripe/Usage-Based Billing · Feature Flags · Self-Serve Onboarding
**Testing** - Pytest · Jest · Cypress · Playwright · TDD/BDD · 90%+ coverage enforced

---

## Best Practices

- **Architecture** - Clean Architecture, SOLID principles, dependency injection, async patterns, type safety (Pydantic V2, mypy strict, TypeScript strict)
- **Agentic AI** - Bounded autonomy, fallback mechanisms, dynamic tool selection, agent observability, safety guardrails, cost controls
- **Machine Learning** - Reproducible training pipelines, hyperparameter tuning with Optuna, experiment tracking with TensorBoard, train/validation/test discipline
- **Computer Vision** - Real-time frame processing under latency budgets, model inference optimization, robust webcam/stream capture handling
- **Multi-Tenancy** - Tenant data isolation, per-tenant rate limiting and quotas, tenant-aware caching, safe cross-tenant migrations
- **Security** - OAuth2, JWT, input validation, rate limiting, encryption
- **Observability** - Structured logging, distributed tracing, metrics, alerts

---

## Projects

### Featured

- **[AI Interview Assistant](https://github.com/PowerInterviewAI/client-app)** - Privacy-first Electron app with live transcription and real-time AI suggestions for interviews and coding challenges. *Stack: Electron · React 19 · TypeScript · Vite · Zustand · TanStack Query · Radix UI · Tailwind CSS*
- **[Grammar AI](https://github.com/vectorleap-pulse/grammar-ai)** - Free lightweight desktop app for AI-powered grammar correction and text polishing. *Stack: Python · OpenAI API · Pydantic · pywebview · React · TypeScript · Vite · Tailwind CSS · shadcn/ui*
- **[Startup Validator Agent](https://github.com/vectorleap-pulse/startup-validator-agent)** - Full-stack multi-agent system that validates startup ideas. *Stack: FastAPI · Pydantic · OpenAI API · Tavily Search · SSE-Starlette · Next.js · React · Zustand · Framer Motion · Tailwind CSS*
- **[Portfolio Research Agent](https://github.com/vectorleap-pulse/portfolio-research-agent)** - Multi-agent system that autonomously plans, searches, retrieves, summarizes, and synthesizes research reports, streamed live to a dashboard UI. *Stack: FastAPI · LangChain · LangGraph · Qdrant · Next.js · TypeScript · Docker Compose*
- **[Healthy Meal Copilot API](https://github.com/alpha5611331/fastapi-prototype-healtymeal-copilot-api)** - AI-powered meal planning backend combining multiple LLMs for personalized recommendations. *Stack: FastAPI · Pydantic V2 · MongoDB (PyMongo) · Qdrant · OpenAI/Gemini/Claude APIs · JWT Auth (python-jose) · Pytest · Ruff · Mypy*
- **[Travel Planner Agent](https://github.com/vectorleap-pulse/travel-planner-agent)** - Multi-agent travel planning tool where five agents research in parallel and synthesize a complete trip package via real-time streaming. *Stack: FastAPI · OpenAI API · Tavily Search · SSE-Starlette · Next.js · React · Leaflet · Framer Motion · Zustand · Tailwind CSS*
- **[Healthcare RBAC Platform](https://github.com/alpha5611331/healthcare-RBAC)** - HIPAA-conscious Provider Operations Platform demo replacing manual billing approval with an auditable, role-based system. *Stack: FastAPI · MongoDB (Motor, async) · Pydantic V2 · JWT Auth (python-jose, bcrypt) · Next.js · React · Tailwind CSS · Docker*

<details>
<summary><strong>Additional Projects</strong> - earlier freelance and exploratory work spanning AI tooling, browser automation, blockchain, and full-stack development</summary>

<br>

**AI & Machine Learning**

- [ai-assist](https://github.com/alpha5611331/ai-assist) - Desktop ChatGPT-like chatbot UI with configurable API key and model selection. *Stack: C# · WinForms*
- [ai-assist-py](https://github.com/alpha5611331/ai-assist-py) - Python desktop AI chat assistant. *Stack: Python · OpenAI API · Pydantic · NiceGUI · pywebview · SQLAlchemy*
- [fastapi-websocket-chatroom](https://github.com/alpha5611331/fastapi-websocket-chatroom) - Real-time multi-client chatroom. *Stack: FastAPI · WebSockets · Uvicorn*
- [tft-model-training](https://github.com/alpha5611331/tft-model-training) - Temporal Fusion Transformer model training pipeline for crypto price forecasting. *Stack: PyTorch · PyTorch Lightning · PyTorch Forecasting · Bittensor · CCXT · Optuna · scikit-learn*
- [meta-face-py](https://github.com/alpha5611331/meta-face-py) - Real-time virtual camera app with live video/audio processing pipeline. *Stack: Python · OpenCV · aiortc (WebRTC) · PyVirtualCam · Pillow*
- [msg-bin-analyze](https://github.com/alpha5611331/msg-bin-analyze) - Binary structure analysis and JSON parsing tool. *Stack: Python · Tkinter*

**Web Scraping & Browser Automation**

- [stealth-chrome-automation](https://github.com/alpha5611331/stealth-chrome-automation) - Undetectable Chrome automation via raw DevTools Protocol. *Stack: Node.js · Chrome DevTools Protocol (ws)*
- [stealth-chrome-automation-py](https://github.com/alpha5611331/stealth-chrome-automation-py) - Python port of the stealth Chrome automation engine. *Stack: Python · Chrome DevTools Protocol*
- [scrap-rapidapi.com](https://github.com/alpha5611331/scrap-rapidapi.com) - RapidAPI marketplace scraper/indexer. *Stack: Python · Playwright · Loguru*
- [scrap-capterra.com](https://github.com/alpha5611331/scrap-capterra.com) - Capterra scraper with automated captcha solving. *Stack: Python · Chrome DevTools Protocol (WebSocket) · PyAutoGUI*
- [scrap-fiverr.com](https://github.com/alpha5611331/scrap-fiverr.com) - Fiverr profile and listing scraper. *Stack: Python · Chrome DevTools Protocol (WebSocket)*
- [scrap-shopee.tw-puppeteer](https://github.com/alpha5611331/scrap-shopee.tw-puppeteer) - Shopee Taiwan scraper. *Stack: Node.js · Chrome DevTools Protocol (ws)*
- [scrap-apps.shopify.com](https://github.com/alpha5611331/scrap-apps.shopify.com) - Shopify App Store downloader. *Stack: Node.js*
- [scrap-www.cde.ca.gov](https://github.com/alpha5611331/scrap-www.cde.ca.gov) - California Dept. of Education directory scraper. *Stack: Python · Chrome DevTools Protocol (WebSocket)*
- [scrap-www.floridabar.org](https://github.com/alpha5611331/scrap-www.floridabar.org) - Florida Bar member directory scraper. *Stack: Python · Chrome DevTools Protocol (WebSocket)*
- [crawl_www.hwk-mittelfranken.de](https://github.com/alpha5611331/crawl_www.hwk-mittelfranken.de) - Cloudflare-bypassing crawler. *Stack: Python · Chrome DevTools Protocol (WebSocket)*
- [autodiler.me-scraper](https://github.com/alpha5611331/autodiler.me-scraper) - Vehicle listing scraper. *Stack: Python · Playwright · BeautifulSoup*
- [mauwi.wycokck.org](https://github.com/alpha5611331/mauwi.wycokck.org) - Public records scraper. *Stack: Python · Chrome DevTools Protocol (WebSocket)*
- [html-parser](https://github.com/alpha5611331/html-parser) - Retailer HTML parsing utility (Walmart, Costco, Best Buy, Home Depot, Overstock, Sam's Club). *Stack: Python*
- [api-tunnel](https://github.com/alpha5611331/api-tunnel) - Backend API service with JWT auth. *Stack: FastAPI · MongoDB (PyMongo) · Alembic · python-jose*
- [google_form_test_auto](https://github.com/alpha5611331/google_form_test_auto) - Automated Google Forms submission with Telegram bot control. *Stack: Python · Pyrogram (Telegram) · Chrome DevTools Protocol*
- [gen-shopify-csv](https://github.com/alpha5611331/gen-shopify-csv) - Shopify product CSV generator. *Stack: Python · Requests*
- [shuffle.com-signup](https://github.com/alpha5611331/shuffle.com-signup) - Automated signup flow with Telegram verification. *Stack: Python · Pyrogram (Telegram) · Chrome DevTools Protocol*

**Blockchain / Solana**

- [solana-staking-app](https://github.com/alpha5611331/solana-staking-app) - Solana staking program. *Stack: Rust · Solana SDK*
- [anchor-staking-app](https://github.com/alpha5611331/anchor-staking-app) - Solana staking dApp. *Stack: Rust · Anchor · TypeScript*
- [fullstack-mysolanaapp](https://github.com/alpha5611331/fullstack-mysolanaapp) - Full-stack Solana dApp. *Stack: Rust · Anchor · React · TypeScript*
- [solana-tic-tac-toe](https://github.com/alpha5611331/solana-tic-tac-toe) - On-chain tic-tac-toe game. *Stack: Rust · Anchor · TypeScript*

**Full-Stack Web Apps**

- [ge-crm-front](https://github.com/alpha5611331/ge-crm-front) - CRM frontend. *Stack: Next.js 15 · React 19 · Tailwind CSS · AG Grid · React Hook Form*
- [ge-crm-back](https://github.com/alpha5611331/ge-crm-back) - CRM backend. *Stack: FastAPI · MongoDB (PyMongo) · Twilio · PyOTP · JWT Auth (python-jose)*
- [api-plugin-frontend](https://github.com/alpha5611331/api-plugin-frontend) - API plugin platform frontend. *Stack: Next.js · TypeScript*
- [api-plugin-backend](https://github.com/alpha5611331/api-plugin-backend) - API plugin platform backend. *Stack: FastAPI · MongoDB (PyMongo) · BeautifulSoup · APScheduler*
- [creed-dekaron-user-frontend](https://github.com/alpha5611331/creed-dekaron-user-frontend) - Game community frontend with captcha, PayPal, and datatable integration. *Stack: React 18 · Ant Design · Material Tailwind · PayPal SDK*
- [creed-dekaron-admin-frontend](https://github.com/alpha5611331/creed-dekaron-admin-frontend) - Admin panel for the Creed Dekaron platform. *Stack: React 18 · Ant Design · Material Tailwind*
- [visionui-react-admin-panel](https://github.com/alpha5611331/visionui-react-admin-panel) - VisionUI-based admin panel. *Stack: React 18 · Ant Design · Flowbite · Express.js*
- [nextjs-self-tech](https://github.com/alpha5611331/nextjs-self-tech) - Tech blog. *Stack: Next.js · MongoDB · react-markdown*
- [checker_board_webpage](https://github.com/alpha5611331/checker_board_webpage) - Real-time board game web app. *Stack: Express.js · Socket.io · MySQL · JWT*
- [ta-v00](https://github.com/alpha5611331/ta-v00) - Document processing application. *Stack: Laravel 13 · PHP 8.2 · PHPWord · Vite*
- [analysi-importer](https://github.com/alpha5611331/analysi-importer) - Audio transcription and analysis pipeline. *Stack: FastAPI · OpenAI API · Azure Cognitive Speech · PostgreSQL (SQLAlchemy) · AWS S3 (boto3) · APScheduler*

**Utilities**

- [parse-bitcoin-addresses](https://github.com/alpha5611331/parse-bitcoin-addresses) - Bitcoin address parser and validator. *Stack: Python · base58 · bech32 · pycryptodome*
- [concurrent-tcp-server-client](https://github.com/alpha5611331/concurrent-tcp-server-client) - Concurrent TCP server/client with multi-threaded connection handling. *Stack: Python · sockets · threading*

</details>

---

Open to contract, consulting, and full-time roles in Agentic AI, LLM systems, backend, and full-stack development.
