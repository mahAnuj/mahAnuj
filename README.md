# Anuj Mahajan

**[anujmahajan.com](https://anujmahajan.com)** — case studies, and writing on AI engineering and architecture.

One client engagement at a time: AI product engineering, AI agent workflows, and AI security and governance reviews.

Staff-level software engineer, 15 years. Distributed systems, cloud-native backends, and — for the last while — building complete products solo with AI coding tools.

Currently in-house at a large software company, on serverless backend services and a cross-platform player. Before that, backend systems at two e-commerce companies and seven years at a consumer electronics manufacturer.

### Things I've shipped solo

Three production platforms, built end-to-end by one person using AI-assisted development. Architecture, data pipelines, and infrastructure are mine; Claude Code did a lot of the typing.

**[VivaTrades](https://vivatrades.in)** — Structured analysis for the NIFTY 500. A nightly pipeline ingests fundamentals, technicals, and news for 500 NSE-listed stocks and synthesises each into a written report — snapshot, strengths, weaknesses, peer ranking, risk flags. Also houses a strategy backtesting engine over 20 years of data with walk-forward validation for out-of-sample testing. Free, no signup.

**[Shubh Bhagya](https://shubhagya.com)** — Vedic astrology, computed properly. Sidereal Lahiri chart math on Swiss Ephemeris, driving Janma Kundli generation, Vimshottari Dasha periods, daily Panchang, Ashtakoot matching, and a classical muhurat finder that applies tithi, nakshatra, Panchak, Chaturmas and Nitya Yoga rules. 76 explainers, cited to source texts.

**[VeoCabs](https://veocabs.com)** — Intercity cab lead generation across 150+ Indian cities. Instant fare estimates from Google Routes, enquiries pushed to Telegram, and an admin CRM the business runs on daily. Built and still maintained by me; run day to day by the business itself.

### AI agents that run a product, and the governance around them

Shubh Bhagya is built and maintained by fifteen Claude Code agents on GitHub Actions. They read the analytics, file the work, build it, put it through a separate QA agent and ship it, then score each change against the growth objective it claimed to serve. Over 25 days their cycles produced 43 merged pull requests, and QA failed 44% of first submissions. A workflow, not an agent, does the merge.

- [The autonomous growth loop behind shubhagya.com](https://anujmahajan.com/blog/autonomous-growth-loop): how it works, its ops dashboard, and what still breaks
- [The agent cycle, interactive](https://anujmahajan.com/agent-cycle): 15 agents, 18 workflows
- [Who holds merge authority over agent pull requests](https://anujmahajan.com/blog/merge-authority-in-a-workflow)

AI security and governance writing, from audits of my own systems:

- [OWASP LLM Top 10, explained for startup teams](https://anujmahajan.com/blog/owasp-llm-top-10): all ten risks with real incidents
- [Governance theatre: auditing an AI support bot](https://anujmahajan.com/blog/governance-theatre-ai-support-bot)
- [From read-only to governed: auditing my own MCP server](https://anujmahajan.com/blog/from-read-only-to-governed)

### Open source

- **[mcp-multi-db](https://github.com/mahAnuj/mcp-multi-db)** — Read-only MCP server for querying PostgreSQL, MySQL, and SQLite from AI agents. Multi-database, safe by default.
- **[prompteval](https://github.com/mahAnuj/prompteval)** — LLM eval framework with first-class token-cost tracking. Did that prompt change save money without losing quality?
- **[multi-agent-blog](https://github.com/mahAnuj/multi-agent-blog)** — Blog platform written by cooperating agents: gather context, draft, critique, revise against the critique. A human still approves before anything publishes.
- **[ai-support-bot](https://github.com/mahAnuj/ai-support-bot)** — Upload your documents, get a RAG-backed support assistant you can embed on any site as a widget.
- **[mcp-zerodha](https://github.com/mahAnuj/mcp-zerodha)** — Read-only MCP server putting Zerodha broker data — prices, portfolio, history — in front of AI agents.

### Interests

LLM pipelines that do real work rather than demos — retrieval, synthesis, evaluation. Agent tooling and MCP. The engineering question I find most interesting right now is how far one experienced engineer can go with these tools, and where the ceiling actually is.

📫 mahajananuj07@gmail.com · [anujmahajan.com](https://anujmahajan.com) · [Start a project](https://anujmahajan.com/contact)
