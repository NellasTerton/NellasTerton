# Привет 👋 Я Егор Якобсон
 
**Русский** | [English](README.en.md)

**AI-Product Builder**

Помогаю бизнесу и стартапам автоматизировать процессы и собирать AI-продукты под конкретную задачу. От идеи до продакшена — фронтенд, база данных, интеграции и деплой.

🌍 Рига, Латвия.

### 🛠️ Основной стек и экспертиза

* **AI Models & APIs:** Claude, Anthropic API, OpenAI / GPT, Gemini, Ollama, Voyage AI.
* **RAG & Knowledge Retrieval:** RAG, ingest, chunking, embeddings, pgvector, hybrid search, semantic search, grounding, source attribution.
* **Agent & LLM Engineering:** AI agents, tool calling, system prompts, prompt engineering, structured output, JSON contracts, XML guardrails, state machines, routing, validation, deterministic logic, fallback flows, LangGraph.
* **Automation & Integrations:** Make.com, n8n, REST API, webhooks, Telegram Bot API, Notion API, Tavily API.
* **Backend & Data:** Node.js, Python, JavaScript, TypeScript, SQL, PostgreSQL, Neon, Supabase, Drizzle ORM.
* **Frontend & App Development:** React, Next.js, Tailwind CSS, shadcn/ui, PWA, Telegram Mini Apps.
* **Product Interfaces:** internal tools, admin panels, CRM dashboards, Kanban workflows, lead management interfaces.
* **Observability & Testing:** Langfuse, AI run logging, latency, confidence, retrieval tracing, run history, unit tests, smoke tests, QA scenarios, token cost monitoring.
* **Visual AI:** ComfyUI Node Workflows, Stable Diffusion pipelines.

### 🤖 AI-агенты и бизнес-автоматизация

*Продукты, решающие конкретную бизнес-задачу: встретить клиента, ответить по фактам, довести до записи.*

- **[Lord of the Rigs](https://github.com/NellasTerton/Lord-of-the-Rigs)** — задеплоенный ассистент фитнес-клуба, работающий на базе знаний pgvector: отвечает строго на основе найденных фактов и записывает на реальные тренировки в Postgres через tool calling Claude. Одно общее ядро агента обслуживает и веб-виджет чата, и Telegram-бота.
- **[Medbot](https://github.com/NellasTerton/medbot)** — AI-консьерж для клиники. Роутинг интента на два режима: ответ по базе знаний через RAG или сбор заявки на приём с передачей в Make.com, Telegram и Notion. Юнит-тесты, а также smoke- и QA-прогоны против продакшена.
- **[Lex CRM](https://github.com/NellasTerton/accessiblelawtest)** — прототип LegalTech-дашборда: React/TypeScript фронтенд, связанный с Make.com и Telegram Bot API для автоматизации уведомлений о лидах.
- **[Corporate Booking](https://github.com/NellasTerton/AI-Booking-Prototype)** — сервис бронирования на React со строгой бизнес-логикой: валидация пересечения интервалов и защита от двойного бронирования.
- **[Смотрю, душню](https://github.com/NellasTerton/tgchannelbot)** — автоматизированный AI-пайплайн для Telegram-канала: принимает сырой черновик, роутит фильмы/сериалы и игры в разные ветки, собирает проверяемые факты и рейтинги через TMDB, OMDb, RAWG и Tavily, а Claude превращает их в готовый пост с фотогалереей. Make.com оркестрирует весь процесс, а Google Sheets используется как очередь и аудит-лог публикаций.


### 🧠 LLM-архитектура и промпт-инжиниринг

*Проекты, где ценность — в проектировании поведения модели, а не в приложении вокруг неё.*

- **[Lifestorypage](https://github.com/NellasTerton/lifestorypage)** — сервис, который превращает экспорт переписки в проверенную историю: каждый ключевой момент подтверждён цитатой и проходит независимую верификацию отдельным проходом модели, а не просто «звучит правдоподобно».
- **[UniQee](https://github.com/NellasTerton/uniqee)** — production LLM-«Арбитр»: агент-гейммастер, обрабатывающий одновременные скрытые инпуты двух пользователей и управляющий машиной состояний. Строгие XML-guardrails заставляют модель отдавать валидный JSON для безопасного парсинга бэкендом.
- **[Telegram AI Companion Engine](https://github.com/NellasTerton/AI-pornbot)** — системные промпты и логика состояний для персонажного AI-компаньона внутри Telegram Mini App.

### 🧪 R&D Lab

*Что я строю параллельно:*

- **[FixFlow AI](https://github.com/NellasTerton/fixflow-ai)** 🚧 *в активной разработке* — AI-диспетчер для выездных сервисных компаний.
- **Truth or Dare (ComfyUI):** интерактивная визуальная новелла с real-time face-swap и генерацией одежды персонажей в реальном времени через автоматизированные workflow ComfyUI.
- **Mobile-UI Interactive Fiction:** процедурная нарративная игра, где весь геймплей проходит через симулированный интерфейс смартфона.
- **Myth & History Card Game:** коллекционная карточная игра на переменных (в стиле MadFUT) с историческими фигурами и мифологией.
- **Latvia Quiz (Unity):** динамичная образовательная викторина, созданная на Unity.

### 📫 Давайте на связь

**[Telegram](https://t.me/egoriakobson)** | **[LinkedIn](https://linkedin.com/in/egoriakobson)** | **egoriakobson@gmail.com**
