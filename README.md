# Hi, I'm Hasnain 👋

**Applied AI engineer & compulsive builder.** I ship working AI tools — not slide decks, not strategy. Give me an ambiguous, unscoped brief and I'll come back with a thing that runs.

I care as much about *whether it actually worked* — measured against a baseline — as about building it. I move fast across unfamiliar domains and leave an artefact trail behind me. Most of what's below started because I wanted a tool that didn't exist yet.

### Things I've built

- **[ai-rag-evaluation-platform](https://github.com/Hasnain91169/ai-rag-evaluation-platform)** — because "the RAG feels better now" isn't good enough. An eval + observability harness for RAG: retrieval hit-rate, faithfulness, hallucination rate, and a failure-diagnosis matrix that separates retrieval vs prompting vs ranking failures.
- **[LangStuff](https://github.com/Hasnain91169/LangStuff)** — a LangGraph multi-agent incident-resolution engine: a durable state machine, tool-calling with human-in-the-loop approval gates, policy guardrails, and a full audit trail. Runs deterministically offline; drops in a real LLM when configured.
- **[DevLoop](https://github.com/Hasnain91169/DevLoop)** — an agentic senior/junior developer loop: Claude API reasons and reviews, a local model executes, with planning, critique and retry. The local executor is provider-agnostic (MLX default, Ollama supported) — I moved my own stack to MLX when Ollama broke on the M5 Tahoe beta.
- **[ATLAS](https://github.com/Hasnain91169/ATLAS)** — a personal "operating company" assistant I built for myself: department-head agents produce reports, an orchestrator synthesises them, and it proposes actions I approve. CLI-first, SQLite-backed, with a proper test suite.
- **[CounterWatch](https://github.com/Hasnain91169/CounterWatch)** — a counter-pick engine for a game I actually play. A small rules-and-overrides matchup engine — because the weekend project is usually the tool nobody had built yet.
- **Real-time voice agents** — fully local STT → LLM → TTS (Whisper · Piper), full-duplex echo control, sub-1.5s response latency.
- **SME builds** — websites and automation shipped fast for real clients (barbers, mosques, clinics).

### What I do

At my last role I designed and owned production AI systems running compliance workflows across **75+ countries**, cutting manual review effort by **~70%**. Regulated environment (ISO 27001, GDPR) — so reliability, grounding and auditability aren't optional for me.

**Stack:** Python · FastAPI · n8n · Azure OpenAI · Claude API · MLX · Docker · RAG (chunking, embeddings, vector search) · agentic tool-calling

I'm most interested in agentic systems, eval-driven development, and dropping into a domain nobody's cracked yet and shipping something useful by the end of the sprint.
