# Hi there 👋, I'm Egor Iakobson

[Русский](README.md) | **English**

**AI-Product Builder**

I help businesses and startups automate processes and build AI products for specific business needs. From idea to production — frontend, databases, integrations, and deployment.

🌍 Based in Riga, Latvia.

### 🛠️ Core Stack & Expertise

* **AI Models & APIs:** Claude, Anthropic API, OpenAI / GPT, Gemini, Ollama, Voyage AI.
* **RAG & Knowledge Retrieval:** RAG, ingest, chunking, embeddings, pgvector, hybrid search, semantic search, grounding, source attribution.
* **Agent & LLM Engineering:** MCP (Model Context Protocol), MCP servers, stdio and Streamable HTTP transports, AI agents, tool calling, system prompts, prompt engineering, structured output, JSON contracts, XML guardrails, state machines, routing, validation, deterministic logic, fallback flows, LangGraph.
* **Automation & Integrations:** Make.com, n8n, REST API, webhooks, Telegram Bot API, Notion API, Tavily API.
* **Backend & Data:** Node.js, Python, JavaScript, TypeScript, SQL, PostgreSQL, Neon, Supabase, Drizzle ORM.
* **Frontend & App Development:** React, Next.js, Tailwind CSS, shadcn/ui, PWA, Telegram Mini Apps.
* **Product Interfaces:** internal tools, admin panels, CRM dashboards, Kanban workflows, lead management interfaces.
* **Observability & Testing:** Langfuse, AI run logging, latency, confidence, retrieval tracing, run history, unit tests, smoke tests, QA scenarios, token cost monitoring.
* **Visual AI:** ComfyUI Node Workflows, Stable Diffusion pipelines.

### 🤖 AI Agents & Business Automation
 
*Products solving a concrete business problem: greet the client, answer from facts, convert to a booking.*
 
- **[Lord of the Rigs](https://github.com/NellasTerton/Lord-of-the-Rigs)** — a deployed fitness-club assistant grounded in a pgvector knowledge base: it answers strictly from retrieved facts and books real training sessions into Postgres via Claude tool calling. One shared agent core serves both a web chat widget and a Telegram bot.
- **[Medbot](https://github.com/NellasTerton/medbot)** — an AI concierge for a clinic. Intent routing into two modes: answering from the knowledge base via RAG, or collecting an appointment request and handing it off to Make.com, Telegram and Notion. Unit tests plus smoke and QA runs against production. It also ships an MCP server: the same operations are available to Claude Desktop as native tools, over two transports on top of a shared core — stdio locally and Streamable HTTP on Vercel. 
- **[FixFlow AI](https://github.com/NellasTerton/fixflow-ai)** — an AI dispatcher for field-service companies: Claude drives the whole conversation itself and books real availability into Postgres via tool calling, with atomic double-booking protection, handing the lead off to a CRM Kanban board and Make.com → Telegram. Unit tests plus live runs against the real model and database.
- **[Lex CRM](https://github.com/NellasTerton/accessiblelawtest)** — a LegalTech dashboard prototype: a React/TypeScript frontend wired to Make.com and the Telegram Bot API to automate lead notification pipelines.
- **[Corporate Booking](https://github.com/NellasTerton/AI-Booking-Prototype)** — a React scheduling service with strict business logic: interval overlap validation and double-booking prevention.
- **[Watching & Nitpicking](https://github.com/NellasTerton/tgchannelbot)** — an automated AI pipeline for a Telegram channel: takes a rough draft, routes movies/TV shows and games into separate workflows, enriches them with verified facts and ratings via TMDB, OMDb, RAWG, and Tavily, then uses Claude to turn the result into a polished post with a photo gallery. Make.com orchestrates the workflow, while Google Sheets serves as the queue and publishing audit log.
- **[Rehearsio](https://github.com/NellasTerton/rehearsio)** — a voice interview trainer: given a job post, an AI interviewer calls and holds a live spoken conversation (Groq + OpenAI TTS) instead of answering from a script — follows up on vague answers, ends the call itself, and produces a written report scored per question. Full billing loop: Auth.js, Neon Postgres, a Stripe subscription with an idempotent webhook, rate limiting.


### 🧠 LLM Architecture & Prompt Engineering
 
*Projects where the value is in designing model behaviour rather than the app around it.*
 
- **[Lifestorypage](https://github.com/NellasTerton/lifestorypage)** — a service that turns a chat export into a verified story: every key moment is backed by a quote and passes an independent verification pass by a separate model call, instead of just "sounding plausible."
- **[UniQee](https://github.com/NellasTerton/uniqee)** — a production LLM "Arbiter": a game-master agent processing simultaneous blind inputs from two users and driving a state machine. Strict XML guardrails force the model to return valid JSON for safe backend parsing.
- **[Telegram AI Companion Engine](https://github.com/NellasTerton/AI-pornbot)** — system prompts and state logic for a character-driven AI companion inside a Telegram Mini App.

### 🎮 Entertainment Products

*Built for the fun of it rather than for a business case. The first one is live; the rest are in progress.*

- **[UEFA Predict 26/27](https://github.com/NellasTerton/uefa-predictions)** — a football forecasting PWA for friends, covering the Champions League, Europa League and Conference League in one app across 396 fixtures. A shared leaderboard with a per-tournament breakdown of points. Results arrive on their own: a Deno Edge Function, scheduled by pg_cron every 10 minutes, reconciles fixtures against ESPN by id, rescores forecasts and rebuilds the standings. Supabase with Row Level Security, irreversible account deletion through a privileged function, and a hard kick-off time lock on forecasts. The repository carries both versions: the current club edition and the archived World Cup one.
- **Truth or Dare (ComfyUI):** an interactive visual novel with real-time face-swap and dynamic character clothing generation via automated ComfyUI workflows.
- **Mobile-UI Interactive Fiction:** a procedural narrative game where the entire gameplay happens through a simulated smartphone OS interface.
- **Myth & History Card Game:** a variable-driven collectible card game (MadFUT style) featuring historical figures and mythology.
- **Latvia Quiz (Unity):** a fast-paced educational trivia game built in Unity.

---
### 📫 Let's Connect
**[Telegram](https://t.me/egoriakobson)** | **[LinkedIn](https://linkedin.com/in/egoriakobson)** | **egoriakobson@gmail.com**
