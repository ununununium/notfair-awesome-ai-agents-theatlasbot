# Awesome AI Agents

A curated list of AI agent frameworks, tools, and resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Contents

- [Frameworks & Platforms](#frameworks--platforms)
- [LLM Providers](#llm-providers)
- [Memory & Storage](#memory--storage)
- [Code Generation](#code-generation)
- [Multi-Agent Orchestration](#multi-agent-orchestration)
- [Voice & Multimodal](#voice--multimodal)
- [Infrastructure & Tooling](#infrastructure--tooling)
- [Business Applications](#business-applications)
- [Learning Resources](#learning-resources)
- [Community](#community)

---

## Frameworks & Platforms

- [OpenClaw](https://openclaw.ai) — Personal AI agent that lives on your machine. Controls browser, files, APIs, and paired devices with full autonomy.
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — One of the first autonomous agent projects. Chains LLM calls with memory and tool use to complete goals without hand-holding.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent framework. Define agents with backstories and goals, then orchestrate them on tasks. Clean API.
- [LangChain](https://github.com/langchain-ai/langchain) — The Swiss Army knife of LLM tooling. Chains, agents, retrieval, memory — massive ecosystem but can be over-engineered for simple tasks.
- [LangGraph](https://github.com/langchain-ai/langgraph) — State-machine approach to agent workflows from the LangChain team. Better for complex, branching agent logic than vanilla LangChain.
- [MetaGPT](https://github.com/geekan/MetaGPT) — Multi-agent framework that simulates a software company. Assigns PM, architect, engineer roles to agents.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's multi-agent conversation framework. Agents chat with each other to solve problems. Strong for research use cases.
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) — Open-source autonomous agent framework with a GUI. Supports concurrent agents, tool marketplace, and performance telemetry.
- [Phidata](https://github.com/phidatahq/phidata) — Build agents with memory, knowledge, and tools in Python. Clean, pragmatic API. Good for production use.
- [Letta (MemGPT)](https://github.com/letta-ai/letta) — Agents with long-term memory management. Pioneered the idea of LLMs managing their own memory like an OS.
- [Flowise](https://github.com/FlowiseAI/Flowise) — Drag-and-drop UI for building LLM apps and agents. Low-code, great for prototyping.
- [Dify](https://github.com/langgenius/dify) — Open-source LLM app development platform. Visual workflow builder, RAG pipeline, agent capabilities built in.
- [n8n](https://github.com/n8n-io/n8n) — Workflow automation with AI agent nodes. Not AI-native but its agent toolkit is surprisingly capable for business automation.
- [Rivet](https://github.com/Ironclad/rivet) — Visual IDE for building AI agent graphs. Great for teams that want to see and debug agent logic visually.
- [Julep](https://github.com/julep-ai/julep) — Stateful AI agents as a service. Handles sessions, memory, and tool execution server-side.
- [Composio](https://github.com/ComposioHQ/composio) — Tool integration layer for AI agents. 200+ pre-built integrations (GitHub, Slack, databases, etc.) so agents can actually do things.
- [E2B](https://github.com/e2b-dev/e2b) — Cloud sandboxes for AI agents. Gives agents a safe environment to run code, install packages, and interact with filesystems.
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) — Framework for creating collaborating agent swarms. Each agent gets its own tools and instructions.
- [ChatDev](https://github.com/OpenBMB/ChatDev) — Virtual software company powered by agents. Agents take on CEO, CTO, programmer, tester roles to build software through conversation.
- [Haystack](https://github.com/deepset-ai/haystack) — Production-ready NLP/LLM framework from deepset. Agent module supports tool use with a pipeline-first architecture.
- [Fixie](https://github.com/fixie-ai/fixie) — Platform for building natural language agents that connect to APIs and data sources.
- [Bee Agent Framework](https://github.com/i-am-bee/bee-agent-framework) — IBM's open-source framework for building production AI agents. TypeScript-first, structured outputs.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) — Microsoft's SDK for integrating LLMs into apps. Supports planners and agent patterns in C#, Python, and Java.
- [CAMEL](https://github.com/camel-ai/camel) — Communicative agents framework for research. Role-playing approach where agents collaborate through structured dialogue.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — OpenAI's lightweight Python SDK for multi-agent orchestration with handoffs, guardrails, and tracing.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Type-safe agent framework from the Pydantic team. Dependency injection, structured outputs, and multi-model support.
- [Agno](https://github.com/agno-agi/agno) — Lightweight multi-modal agent framework. Build agents with memory, knowledge, tools, and reasoning in Python.
- [Smolagents](https://github.com/huggingface/smolagents) — HuggingFace's minimal agent library. Code-first approach where agents write and execute Python to solve tasks.
- [Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder) — Google Cloud's managed platform for building and deploying agents with grounding, RAG, and tool use.
- [Amazon Bedrock Agents](https://aws.amazon.com/bedrock/agents/) — AWS managed agent service. Orchestrates multi-step tasks using foundation models with action groups and knowledge bases.
- [Cognitiv](https://github.com/cognitiv/cognitiv) — Framework for building AI agents with explicit task planning and verification steps.
- [TaskWeaver](https://github.com/microsoft/TaskWeaver) — Code-first agent framework from Microsoft Research. Converts user requests into Python code that agents execute.
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) — Open-source version of Devin. AI software engineer that writes, runs, and debugs code autonomously.
- [SWE-agent](https://github.com/princeton-nlp/SWE-agent) — Princeton's agent for solving GitHub issues automatically. State-of-the-art on SWE-bench.
- [Voyager](https://github.com/MineDojo/Voyager) — Lifelong learning agent in Minecraft. Explores, learns skills, and builds a library of reusable knowledge.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) — The original task-driven autonomous agent. Simple but influential architecture for iterative task management.
- [GPT-Engineer](https://github.com/AntonOsika/gpt-engineer) — Specify what you want, AI builds the entire codebase. Pioneered conversational software generation.
- [Devin](https://devin.ai) — Cognition AI's fully autonomous software engineer. Plans, codes, tests, and deploys.
- [Aide](https://github.com/codestoryai/sidecar) — AI-native IDE with agent capabilities built in. Not a plugin — the whole environment.
- [Vertex AI Reasoning Engine](https://cloud.google.com/vertex-ai/generative-ai/docs/reasoning-engine/overview) — Google Cloud's managed runtime for deploying LangChain and custom agent logic at scale.

## LLM Providers

- [Anthropic Claude](https://anthropic.com) — Best-in-class for long context (200K tokens), coding, and instruction following. Claude Opus 4 and Sonnet 4 are the go-to for complex agent tasks.
- [OpenAI GPT-4o](https://openai.com) — Strong all-rounder. Native multimodal (text, image, audio). Massive ecosystem and function calling support.
- [Google Gemini](https://deepmind.google/technologies/gemini/) — 1M+ token context window. Strong multimodal capabilities. Good for tasks requiring huge context.
- [Meta Llama 3](https://llama.meta.com) — Best open-weight model family. Run locally or on any cloud. 8B and 70B variants cover most use cases.
- [Mistral](https://mistral.ai) — European AI lab. Strong open models (Mixtral 8x22B) and commercial API. Good balance of capability and cost.
- [Cohere](https://cohere.com) — Enterprise-focused. Command R+ is solid for RAG and tool use. Good embeddings for retrieval.
- [Groq](https://groq.com) — LPU-based inference. Extremely fast token generation. Great for latency-sensitive agent loops.
- [Together AI](https://together.ai) — Open model hosting. Run Llama, Mixtral, and other open models via API. Competitive pricing.
- [Fireworks AI](https://fireworks.ai) — Fast inference for open models. Function calling support. Good for high-throughput agent workloads.
- [Perplexity](https://perplexity.ai) — Search-augmented LLM. Useful as a research tool within agent pipelines. Sonar API for programmatic access.
- [DeepSeek](https://deepseek.com) — Strong reasoning models at very low cost. DeepSeek-R1 competes with frontier models on math and code.
- [xAI Grok](https://x.ai) — Real-time access to X/Twitter data. Grok-2 is competitive on benchmarks with unique data advantages.
- [xAI Grok](https://x.ai) — Elon Musk's AI lab. Grok 2 and 3 competitive on reasoning and coding. Real-time web access.
- [Perplexity](https://perplexity.ai) — Search-augmented LLM. Strong for research agents that need real-time web grounding.
- [Cerebras](https://cerebras.ai) — Wafer-scale chip inference. Ultra-fast for large models. Good for latency-sensitive production agents.
- [Ollama](https://ollama.ai) — Run open models locally. Simple CLI for pulling and running Llama, Mistral, and others on your machine.
- [LM Studio](https://lmstudio.ai) — Desktop app for running local models. Good UI, OpenAI-compatible API for easy integration.
- [Jan](https://jan.ai) — Open-source alternative to LM Studio. Runs models locally, privacy-first.
- [Replicate](https://replicate.com) — Run open-source ML models via API. Thousands of models including Llama, SDXL, Whisper.
- [Hugging Face Inference API](https://huggingface.co/inference-api) — Serverless inference for 150,000+ models. Good for prototyping with open models.
- [Deepseek](https://deepseek.com) — Chinese AI lab with strong open models. DeepSeek-V3 and R1 are highly competitive at significantly lower API cost.
- [Qwen](https://github.com/QwenLM/Qwen) — Alibaba's model family. Strong on Chinese and multilingual tasks. 72B model is state-of-the-art for open weights.

## Memory & Storage

- [Mem0](https://github.com/mem0ai/mem0) — Memory layer for AI agents and assistants. Manages user preferences, session history, and learned context across conversations.
- [Zep](https://github.com/getzep/zep) — Long-term memory for AI assistants. Auto-summarizes conversations, extracts facts, and maintains temporal awareness.
- [ChromaDB](https://github.com/chroma-core/chroma) — Open-source embedding database. Simple API, runs embedded or as a server. The SQLite of vector databases.
- [Pinecone](https://pinecone.io) — Managed vector database. Zero ops, scales automatically. The default choice for production RAG.
- [Weaviate](https://github.com/weaviate/weaviate) — Open-source vector database with hybrid search (vector + keyword). GraphQL API, good for complex queries.
- [Qdrant](https://github.com/qdrant/qdrant) — High-performance vector database written in Rust. Advanced filtering, good for production workloads.
- [LanceDB](https://github.com/lancedb/lancedb) — Serverless vector database built on Lance format. Embedded, no server needed. Great for local-first agents.
- [PGVector](https://github.com/pgvector/pgvector) — Vector similarity search for Postgres. If you're already on Postgres, this avoids adding another database.
- [Milvus](https://github.com/milvus-io/milvus) — Cloud-native vector database. Handles billion-scale vectors. Overkill for small projects, essential for large ones.
- [Motorhead](https://github.com/getmetal/motorhead) — Memory and context management server for LLMs. Redis-backed, handles incremental summarization.
- [Redis Vector](https://redis.io/docs/interact/search-and-query/query/vector-search/) — Vector search built into Redis Stack. Fast, familiar, good if Redis is already in your stack.
- [Supabase pgvector](https://supabase.com/docs/guides/ai) — Managed Postgres with pgvector. Combines your app database and vector store in one place.
- [Mem0](https://github.com/mem0ai/mem0) — Intelligent memory layer for AI agents. Automatically extracts and retrieves relevant memories from conversation history.
- [Zep](https://github.com/getzep/zep) — Long-term memory for AI assistants. Extracts facts, entities, and summaries from conversations for fast retrieval.
- [Cognee](https://github.com/topoteretes/cognee) — Memory management via knowledge graphs. Structures agent memory as interconnected entities.
- [Agentmemory](https://github.com/daveshap/AgentMemory) — Simple, hierarchical memory system for agents. Implements working, episodic, and semantic memory layers.
- [Weaviate](https://weaviate.io) — Open-source vector database. Strong for hybrid search (dense + sparse vectors) in retrieval-augmented agents.
- [Qdrant](https://qdrant.tech) — High-performance vector search engine. Rust-based, production-ready, with payload filtering.
- [Milvus](https://milvus.io) — Scalable open-source vector database. Good for large-scale similarity search in enterprise settings.
- [ChromaDB](https://github.com/chroma-core/chroma) — The simplest vector database. Runs in-process for prototyping, scales to production. Agent-friendly API.
- [LanceDB](https://lancedb.github.io/lancedb/) — Serverless vector database built on Lance columnar format. No separate server needed.

## Code Generation

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) — Anthropic's agentic coding tool. Operates directly in your terminal, reads your codebase, runs commands, and makes edits. Best for complex, multi-file changes.
- [Cursor](https://cursor.sh) — AI-native code editor built on VS Code. Tab completion, inline edits, and chat with codebase context. The IDE most developers are switching to.
- [GitHub Copilot](https://github.com/features/copilot) — The original AI pair programmer. Integrated into VS Code, JetBrains, and CLI. Copilot Workspace adds agentic planning.
- [Windsurf](https://codeium.com/windsurf) — AI code editor from Codeium. Cascade feature handles multi-file edits with context awareness. Free tier is generous.
- [Aider](https://github.com/paul-gauthier/aider) — Terminal-based AI pair programmer. Works with any LLM. Excellent git integration — makes clean commits automatically.
- [Continue.dev](https://github.com/continuedev/continue) — Open-source AI code assistant for VS Code and JetBrains. Bring your own model. Highly customizable.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — Open-source AI software engineer (formerly OpenDevin). Full development environment with browser, terminal, and editor.
- [SWE-Agent](https://github.com/princeton-nlp/SWE-agent) — Princeton's agent for solving GitHub issues. Designed for the SWE-bench benchmark. Strong at bug fixes.
- [Devin](https://devin.ai) — Cognition's autonomous software engineer. Full development environment with browser and terminal. Commercial, invite-only.
- [Mentat](https://github.com/AbanteAI/mentat) — AI coding assistant that works with your whole codebase. Coordinates changes across multiple files.
- [Cody](https://sourcegraph.com/cody) — Sourcegraph's AI assistant. Understands your entire codebase through Sourcegraph's code graph. Great for large repos.
- [Replit Agent](https://replit.com) — Build full apps from natural language in Replit's cloud IDE. Handles frontend, backend, and deployment.
- [Codex CLI](https://github.com/openai/codex) — OpenAI's terminal coding agent. Reads your codebase, proposes changes, runs commands in a sandboxed environment.
- [Tabnine](https://tabnine.com) — AI code completion that can run locally. Privacy-focused, supports on-premise deployment.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) — AWS's AI coding assistant. Strong for AWS services, infrastructure code, and Java.
- [Continue](https://continue.dev) — Open-source AI code assistant for VS Code and JetBrains. Any model, full codebase context.
- [Aider](https://github.com/paul-gauthier/aider) — AI pair programmer in your terminal. Edit code across files in a git repo with GPT-4 or Claude.
- [Cline](https://github.com/clinebot/cline) — Autonomous coding agent in VS Code. Reads files, runs commands, uses the browser, and iterates until done.
- [Windsurf](https://codeium.com/windsurf) — Codeium's agentic IDE. Cascade feature lets the AI take multi-step actions across your codebase.
- [Bolt.new](https://bolt.new) — StackBlitz's AI-powered full-stack dev environment. Prompt to running app in the browser.
- [Lovable](https://lovable.dev) — AI-powered web app builder. Build and iterate on full-stack apps through natural language.
- [V0](https://v0.dev) — Vercel's UI generation tool. Generate React components from text or screenshots.
- [Replit Agent](https://replit.com/ai) — Build, run, and deploy apps in the browser. Agent handles the full development lifecycle.
- [Sweep AI](https://github.com/sweepai/sweep) — AI junior developer that resolves GitHub issues. Creates PRs from bug reports.
- [CodeRabbit](https://coderabbit.ai) — AI code reviewer. Reviews PRs with context-aware feedback and auto-approval for simple fixes.
- [Qodo (CodiumAI)](https://qodo.ai) — AI test generation and code integrity. Writes tests that catch edge cases humans miss.
- [Tabnine](https://tabnine.com) — AI code completion that runs locally for privacy. Team plans include codebase context.

## Multi-Agent Orchestration

- [CrewAI](https://github.com/crewAIInc/crewAI) — Define crews of agents with roles, goals, and backstories. Sequential or parallel task execution. Most popular multi-agent framework.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's conversational multi-agent framework. Agents negotiate and collaborate through structured chat.
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) — Create agencies of specialized agents that communicate through a structured hierarchy.
- [CAMEL](https://github.com/camel-ai/camel) — Role-playing framework for studying cooperative behaviors of multi-agent systems. Research-oriented.
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) — Autonomous agent for comprehensive online research. Spawns sub-agents for parallel search and synthesis.
- [Swarm (OpenAI)](https://github.com/openai/swarm) — Lightweight multi-agent orchestration from OpenAI. Educational framework demonstrating handoffs and routines.
- [Magentic-One](https://github.com/microsoft/autogen/tree/main/python/packages/autogen-magentic-one) — Microsoft's generalist multi-agent system. Orchestrator coordinates specialized agents (coder, browser, file surfer).
- [LangGraph](https://github.com/langchain-ai/langgraph) — Build multi-agent systems as state machines. Supports supervisor, hierarchical, and collaborative patterns.

### Patterns

- **Supervisor** — One agent delegates and reviews work from specialized agents. Simple, predictable.
- **Pipeline** — Agents process sequentially, each refining the previous output. Good for content creation workflows.
- **Debate** — Multiple agents argue positions, improving through adversarial refinement. Good for analysis tasks.
- **Hierarchical** — Tree of agents with managers and workers. Scales to complex tasks but adds latency.
- **Swarm** — Peer agents self-organize without central control. Flexible but harder to debug.
- [Swarm](https://github.com/openai/swarm) — OpenAI's experimental multi-agent orchestration framework. Lightweight, educational, handoff-based.
- [Magentic-One](https://github.com/microsoft/magentic-one) — Microsoft's generalist multi-agent system. Orchestrator + specialist agents (web browser, file manager, code executor).
- [Controlflow](https://github.com/PrefectHQ/ControlFlow) — Prefect's framework for structured agentic workflows. Integrates with Prefect orchestration.
- [Burr](https://github.com/dagworks-inc/burr) — Build stateful AI applications as state machines. Clear visualization of agent decision graphs.
- [Motleycrew](https://github.com/ShoggothAI/motleycrew) — Combines LangGraph, CrewAI, and LlamaIndex agents in one framework. Mix-and-match agent types.
- [AgentScope](https://github.com/modelscope/agentscope) — Multi-agent platform from Alibaba's ModelScope. Emphasizes distribution and fault tolerance.
- [Botpress](https://botpress.com) — Enterprise multi-agent platform. Visual flow builder with LLM integration for production deployments.
- [SuperAgent](https://github.com/superagent-ai/superagent) — Open-source agent deployment platform. REST API for running agents with memory, tools, and document retrieval.
- [Prefect](https://prefect.io) — Workflow orchestration for data and AI. Increasingly used to orchestrate agent pipelines in production.

## Voice & Multimodal

- [ElevenLabs](https://elevenlabs.io) — Industry-leading voice synthesis. Voice cloning, multilingual, low-latency streaming. The default for production voice agents.
- [PlayHT](https://play.ht) — Realistic text-to-speech with voice cloning. Good API for building voice-enabled agents.
- [Deepgram](https://deepgram.com) — Fast, accurate speech-to-text. Nova-2 model is excellent. Real-time streaming transcription for voice agents.
- [AssemblyAI](https://assemblyai.com) — Speech AI platform. Transcription, speaker diarization, sentiment analysis. LeMUR for applying LLMs to audio.
- [Whisper](https://github.com/openai/whisper) — OpenAI's open-source speech recognition. Run locally, no API costs. Great accuracy across languages.
- [Cartesia](https://cartesia.ai) — Ultra-low-latency voice synthesis. Sonic model streams speech fast enough for real-time conversation.
- [LMNT](https://lmnt.com) — Fast, expressive text-to-speech API. Voice cloning with minimal samples. Good for conversational AI.
- [Hume AI](https://hume.ai) — Empathic voice interface. Detects and responds to emotional cues in speech. Unique approach to voice agents.
- [Rime](https://rime.ai) — Low-latency TTS built for voice agents. Focuses on natural-sounding conversation at speed.
- [Fish Audio](https://fish.audio) — Open-source voice synthesis. Zero-shot voice cloning, multilingual. Fast and surprisingly good quality.
- [Hume AI](https://hume.ai) — Empathic voice interface API. Measures emotional expression in voice and responds accordingly.
- [Cartesia](https://cartesia.ai) — Ultra-low latency text-to-speech. Sub-100ms first audio byte. Built for real-time voice agents.
- [Deepgram](https://deepgram.com) — Fast, accurate speech recognition API. Real-time transcription with speaker diarization. Standard for voice agents.
- [AssemblyAI](https://assemblyai.com) — Speech AI platform. Transcription, speaker detection, summarization, sentiment analysis in one API.
- [Whisper](https://github.com/openai/whisper) — OpenAI's open-source speech recognition. Run locally or via API. Multilingual, robust to accents.
- [PlayHT](https://play.ht) — High-quality voice cloning and text-to-speech. Voice library with emotional control.
- [Resemble AI](https://resemble.ai) — Voice cloning API. Clone any voice with minimal samples.
- [Daily](https://daily.co) — WebRTC infrastructure for voice and video AI agents. SDKs for building real-time AI voice apps.
- [Pipecat](https://github.com/pipecat-ai/pipecat) — Open-source framework for voice and multimodal AI agents. Connects STT, LLM, TTS in a pipeline.
- [LiveKit](https://livekit.io) — Open-source real-time video and audio infrastructure. Powers many production AI voice agents.
- [Vapi](https://vapi.ai) — Voice AI platform for developers. Build, test, and deploy voice agents with one API.

## Infrastructure & Tooling

### Evaluation & Observability

- [Langfuse](https://github.com/langfuse/langfuse) — Open-source LLM observability. Traces, evals, prompt management. Self-host or cloud. The go-to for agent debugging.
- [Braintrust](https://braintrust.dev) — AI product evaluation platform. Logging, scoring, experiments. Good for systematic quality improvement.
- [Arize Phoenix](https://github.com/Arize-AI/phoenix) — Open-source observability for LLM apps. Trace visualization, embedding analysis, evaluation.
- [Weights & Biases](https://wandb.ai) — ML experiment tracking with LLM support. Traces, prompts, and evals integrated into their platform.
- [LangSmith](https://smith.langchain.com) — LangChain's observability platform. Deep integration with LangChain/LangGraph. Useful even without LangChain.
- [Helicone](https://helicone.ai) — LLM observability proxy. Drop-in logging for any LLM API. Simple setup, useful dashboards.

### Sandboxing & Execution

- [E2B](https://e2b.dev) — Cloud sandboxes for AI-generated code. Agents get isolated environments to run code safely.
- [Modal](https://modal.com) — Serverless compute for AI workloads. Spin up GPU containers on demand. Great for agent tools that need compute.
- [Fly.io Machines](https://fly.io/docs/machines/) — On-demand VMs that boot in milliseconds. Good for ephemeral agent sandboxes.
- [Daytona](https://github.com/daytonaio/daytona) — Open-source development environment manager. Provides standardized, reproducible sandboxes for coding agents.

### Deployment & SDKs

- [Vercel AI SDK](https://github.com/vercel/ai) — TypeScript SDK for building AI apps. Streaming, tool calling, multi-provider support. The React of AI SDKs.
- [LangServe](https://github.com/langchain-ai/langserve) — Deploy LangChain runnables as REST APIs. Quick way to serve agent endpoints.
- [LiteLLM](https://github.com/BerriAI/litellm) — Unified API for 100+ LLM providers. Proxy server with load balancing, fallbacks, and spend tracking.
- [Ollama](https://github.com/ollama/ollama) — Run LLMs locally with one command. Essential for local-first agent development.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for LLM applications. Ingestion, indexing, and querying of external data for agents.
- [Haystack](https://github.com/deepset-ai/haystack) — Production NLP pipelines with agent capabilities. Component-based architecture.
- [Instructor](https://github.com/jxnl/instructor) — Structured outputs from LLMs using Pydantic. Makes parsing LLM responses reliable.
- [Outlines](https://github.com/outlines-dev/outlines) — Structured text generation. Constrain model outputs to JSON schemas, regex patterns, or custom grammars.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) — Add guardrails to LLM outputs. Validate, filter, and correct responses before they reach production.
- [LLMGuard](https://github.com/protectai/llm-guard) — Security toolkit for LLM interactions. Detects prompt injection, PII, and harmful outputs.
- [Trulens](https://github.com/truera/trulens) — Evaluation and tracking for LLM apps. Measure quality, safety, and performance of agent outputs.
- [Langfuse](https://langfuse.com) — Open-source LLM observability. Trace agent runs, track costs, and evaluate output quality.
- [Helicone](https://helicone.ai) — LLM observability and analytics. Drop-in proxy that logs every call with latency, cost, and content.
- [Phoenix (Arize)](https://github.com/Arize-ai/phoenix) — ML observability for LLM and agent systems. Tracing, evals, and drift detection.
- [Weights & Biases Weave](https://wandb.ai/site/weave) — Toolkit for tracking and evaluating LLM and agent experiments.
- [OpenTelemetry for LLMs](https://opentelemetry.io) — Standard instrumentation for distributed tracing of agent pipelines.
- [DSPy](https://github.com/stanfordnlp/dspy) — Stanford's framework for programming (not prompting) language models. Compiles prompts from declarative modules.
- [LMQL](https://lmql.ai) — Query language for language models. Constrained generation with Python-like syntax.
- [Mirascope](https://github.com/mirascope/mirascope) — LLM abstractions that integrate with Pydantic. Clean interface for multi-provider agent code.
- [LiteLLM](https://github.com/BerriAI/litellm) — Single API for 100+ LLM providers. Unified interface with fallbacks, load balancing, and cost tracking.
- [PromptLayer](https://promptlayer.com) — Prompt versioning and observability. Track, test, and iterate on prompts in production.

## Business Applications

### Customer Support

- [Intercom Fin](https://intercom.com/fin) — AI agent built on Intercom's platform. Resolves support tickets using your help docs. Actually works.
- [Sierra](https://sierra.ai) — Conversational AI for customer experience. Founded by Bret Taylor. Enterprise-focused.
- [Decagon](https://decagon.ai) — AI customer support agents for enterprise. Handles complex workflows across systems.
- [Ada](https://ada.cx) — AI-powered customer service automation. No-code bot builder with agent escalation.

### Sales & GTM

- [Clay](https://clay.com) — Data enrichment and outbound automation. Not purely AI but integrates AI agents for research and personalization.
- [Artisan](https://artisan.co) — AI sales agent (Ava) that handles outbound prospecting end-to-end. Books meetings autonomously.
- [11x](https://11x.ai) — AI digital workers for sales. Alice (SDR) and Jordan (phone) handle outbound at scale.
- [Relevance AI](https://relevanceai.com) — Build and deploy AI agents for sales, support, and operations. No-code agent builder.

### Research & Analysis

- [Perplexity](https://perplexity.ai) — AI-powered search engine. Sonar API for programmatic access. Best for real-time research in agent pipelines.
- [Consensus](https://consensus.app) — AI search engine for scientific papers. Extracts findings and synthesizes evidence from research.
- [Elicit](https://elicit.com) — AI research assistant. Finds papers, extracts data, and synthesizes findings. Academic research focused.
- [Tavily](https://tavily.com) — Search API built specifically for AI agents. Optimized for LLM consumption, not human reading.

### Writing & Content

- [Jasper](https://jasper.ai) — AI content platform for marketing teams. Templates, brand voice, campaign workflows.
- [Copy.ai](https://copy.ai) — AI-powered GTM workflows. Sales copy, content generation, workflow automation.
- [Writer](https://writer.com) — Enterprise AI writing platform. Style guides, terminology, brand consistency at scale.

### Personal Assistants

- [Lindy](https://lindy.ai) — AI assistant that connects to your tools. Calendar, email, CRM automation.
- [Dot](https://new.computer) — Personal AI companion with long-term memory. Learns about you over time.
- [Rabbit r1](https://rabbit.tech) — Dedicated AI agent hardware. LAM (Large Action Model) for interacting with apps on your behalf.
- [Granola](https://granola.ai) — AI notepad for meetings. Listens, takes notes, and creates structured summaries.
- [Lindy](https://lindy.ai) — No-code AI agent builder for business workflows. Pre-built agents for email, calendar, and CRM.
- [Relevance AI](https://relevanceai.com) — No-code platform for building and deploying AI agents and tools for business teams.
- [Gumloop](https://gumloop.com) — AI workflow automation. Drag-and-drop builder for agents that process documents, send emails, and update CRMs.
- [Cassidy AI](https://cassidy.ai) — AI assistant connected to your company's knowledge base. Integrates with Notion, Slack, Google Drive.
- [Dust](https://dust.tt) — Deploy AI assistants to your company. Connect to internal tools and data sources.
- [Glean](https://glean.com) — Enterprise search and AI assistant. Connects to all company apps for unified knowledge retrieval.
- [Moveworks](https://moveworks.com) — Enterprise AI platform for IT support and employee self-service automation.
- [Leena AI](https://leena.ai) — HR and employee experience automation. Handles onboarding, policy questions, and HR workflows.
- [Cognigy](https://cognigy.com) — Conversational AI platform for enterprise contact centers. Voice and chat agents at scale.
- [Sierra](https://sierra.ai) — Customer experience AI agents for enterprise. Known for high-quality, branded conversational AI.
- [Intercom Fin](https://intercom.com/fin) — AI customer support agent from Intercom. Resolves 50%+ of tickets without human intervention.
- [Zendesk AI](https://zendesk.com/ai) — AI agents embedded in Zendesk workflows. Triage, draft, and resolve customer support tickets.
- [Clay](https://clay.com) — AI-powered GTM data enrichment. Enriches prospect lists with 50+ data sources via AI agents.
- [Amplemarket](https://amplemarket.com) — AI-powered sales platform. Automates prospecting, personalization, and outreach sequencing.
- [Artisan](https://artisan.co) — AI sales development rep. Ava handles prospecting, research, and outreach automatically.

## Learning Resources

- [AI Co-Founder Course](https://hireatlas.io/courses/ai-cofounder) — Build and operate an AI co-founder from scratch
- [Claude Code Guide](https://hireatlas.io/courses/claude-code) — Master Claude Code for real development work
- [OpenClaw Tutorial](https://hireatlas.io/blog/openclaw-tutorial-2026) — Set up your AI agent in 30 minutes
- [AI Agent for Business](https://hireatlas.io/blog/ai-agent-for-business) — Deploy an AI agent without an engineering team
- [Lilian Weng's Agent Survey](https://lilianweng.github.io/posts/2023-06-23-agent/) — Foundational blog post on LLM-powered autonomous agents. Required reading.
- [Harrison Chase on Agents](https://www.youtube.com/results?search_query=harrison+chase+langchain+agents) — LangChain founder's talks on agent architectures and patterns
- [Andrew Ng's AI Agentic Design Patterns](https://www.deeplearning.ai/the-batch/how-agents-can-improve-llm-performance/) — Four key agentic patterns: reflection, tool use, planning, multi-agent
- [Anthropic's Building Effective Agents](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/agent-guidelines) — Practical guide on building reliable agents with Claude
- [The AI Engineer Path](https://www.latent.space/p/ai-engineer) — Swyx's influential essay on the AI Engineer role
- [Prompt Engineering Guide](https://www.promptingguide.ai/) — Comprehensive guide to prompting techniques, including agent-specific patterns

## Community

- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) — Reddit's hub for running LLMs locally. Benchmarks, quantization tips, and model reviews.
- [r/MachineLearning](https://reddit.com/r/MachineLearning) — Academic ML discussion. Paper reviews, research trends.
- **Twitter/X**: [@AnthropicAI](https://x.com/AnthropicAI), [@OpenAI](https://x.com/OpenAI), [@LangChainAI](https://x.com/LangChainAI), [@hire_atlas](https://x.com/hire_atlas)
- **Discord Communities**: [LangChain](https://discord.gg/langchain), [OpenAI](https://discord.gg/openai), [CrewAI](https://discord.gg/crewai), [Ollama](https://discord.gg/ollama)
- [Latent Space Podcast](https://www.latent.space/podcast) — AI engineering podcast covering agents, models, and infrastructure
- [AI Engineer Summit](https://www.ai.engineer/) — Conference focused on AI engineering, heavy on agents and tooling

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[MIT](LICENSE)

## Evaluation & Benchmarks

- [SWE-bench](https://swebench.com) — Benchmark for evaluating AI agents on real GitHub issues. The standard for coding agents.
- [GAIA](https://huggingface.co/datasets/gaia-benchmark/GAIA) — General AI Assistants benchmark. Tests agents on real-world tasks requiring multi-step reasoning and tool use.
- [AgentBench](https://github.com/THUDM/AgentBench) — Benchmark for evaluating LLMs as agents across 8 environments (web, database, games, OS).
- [WebArena](https://webarena.dev) — Benchmark for autonomous web-browsing agents. Tasks in realistic simulated websites.
- [ToolBench](https://github.com/OpenBMB/ToolBench) — Benchmark for tool-using agents. 16,000+ real-world API calls across 49 categories.
- [HELM](https://crfm.stanford.edu/helm/latest/) — Stanford's holistic evaluation of language models. Covers accuracy, calibration, robustness, fairness, and efficiency.
- [MT-Bench](https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge) — Multi-turn conversation benchmark. Uses GPT-4 as judge for open-ended response quality.
- [Evals (OpenAI)](https://github.com/openai/evals) — OpenAI's framework for evaluating LLMs and agent behaviors. Community-contributed eval registry.
- [MMLU](https://github.com/hendrycks/test) — Massive Multitask Language Understanding. 57 subjects from elementary math to professional law.
- [HumanEval](https://github.com/openai/human-eval) — OpenAI's coding benchmark. Measures functional correctness on programming problems.

## Security & Safety

- [Garak](https://github.com/leondz/garak) — LLM vulnerability scanner. Tests for prompt injection, data leakage, hallucination, and more.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — NVIDIA's toolkit for adding safety rails to LLM-based agents. Programmable guardrails in colang.
- [LLM Attacks](https://github.com/llm-attacks/llm-attacks) — Research on adversarial attacks against aligned LLMs. Important for understanding agent vulnerabilities.
- [Rebuff](https://github.com/protectai/rebuff) — Prompt injection detector. API and self-hosted options.
- [PromptArmor](https://promptarmor.com) — Security scanning for LLM applications. Detects injection, jailbreaks, and data exfiltration attempts.
- [Lakera Guard](https://lakera.ai) — Real-time LLM security layer. Detects and blocks prompt injections and sensitive data exposure.

## Research & Papers

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — The transformer paper. Everything modern LLMs are built on.
- [ReAct](https://arxiv.org/abs/2210.03629) — Reasoning + Acting in language models. The foundational paper behind most tool-using agents.
- [Toolformer](https://arxiv.org/abs/2302.04761) — Meta's self-supervised approach to teaching LLMs to use tools.
- [HuggingGPT (JARVIS)](https://arxiv.org/abs/2303.17580) — Using ChatGPT to orchestrate HuggingFace models as tools.
- [Tree of Thoughts](https://arxiv.org/abs/2305.10601) — Deliberate problem solving by exploring multiple reasoning paths.
- [Chain of Thought](https://arxiv.org/abs/2201.11903) — Google Brain's paper showing step-by-step reasoning dramatically improves performance.
- [Self-Refine](https://arxiv.org/abs/2303.17651) — Agents that iteratively improve their own output through self-feedback.
- [Constitutional AI](https://arxiv.org/abs/2212.08073) — Anthropic's approach to training helpful, harmless AI via self-critique.
- [Generative Agents](https://arxiv.org/abs/2304.03442) — Simulating human behavior with LLM agents. The "Sims with GPT" paper.
- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) — Lilian Weng's comprehensive overview of LLM agent architecture. Required reading.

## Developer Tools & Utilities

- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) — Recipes and examples for building with OpenAI APIs. Practical agent patterns.
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) — Examples and guides for building with Claude. Agent patterns, tool use, multi-turn conversations.
- [Simon Willison's LLM](https://github.com/simonw/llm) — CLI tool for running prompts against LLMs from the terminal.
- [SGPT](https://github.com/tbckr/sgpt) — ShellGPT — use LLMs directly from your shell. Run commands described in natural language.
- [Fabric](https://github.com/danielmiessler/fabric) — Open-source framework for augmenting humans with AI. Pattern library for common tasks.
- [Marvin](https://github.com/PrefectHQ/marvin) — Lightweight AI engineering toolkit. Functions that call LLMs with type annotations.
- [Kor](https://github.com/eyurtsev/kor) — Extract structured data from text using LLMs. Prototype for information extraction agents.
- [Jsonformer](https://github.com/1rgs/jsonformer) — Reliable JSON generation from any LLM. Constrains token generation to valid JSON structure.
- [Guidance](https://github.com/guidance-ai/guidance) — Microsoft's library for controlling LLM generation. Interleave generation, conditionals, and loops.
- [ell](https://github.com/MadcowD/ell) — Language model programming library. Treats prompts as functions with versioning and visualization.

## Agent Hosting & Deployment

- [Modal](https://modal.com) — Run Python functions in the cloud with zero infrastructure. Popular for deploying agent workloads.
- [Render](https://render.com) — Simple cloud hosting for agents and APIs. Good alternative to Heroku.
- [Railway](https://railway.app) — Deploy any agent with git push. Automatic scaling, database provisioning.
- [Fly.io](https://fly.io) — Deploy agents close to users. Runs containers globally at the edge.
- [Cloudflare Workers AI](https://cloudflare.com/developer-platform/workers-ai/) — Run AI inference at the edge. Low latency, pay-per-request.
- [BentoML](https://bentoml.com) — Unified inference serving platform. Package AI models and agents as deployable services.
- [Baseten](https://baseten.co) — ML model deployment platform. Fast inference for any model with custom endpoints.
- [Together Inference](https://together.ai) — Serverless inference with fast cold starts. Deploy open models via API.

## Notable Agents (Demos & Products)

- [Devin](https://devin.ai) — Cognition's autonomous software engineer. Plans projects, writes code, runs tests, deploys.
- [Computer Use (Anthropic)](https://anthropic.com/computer-use) — Claude controlling a desktop computer. Moves mouse, clicks, types, browses.
- [Operator (OpenAI)](https://openai.com/operator) — OpenAI's browser-controlling agent. Completes web tasks autonomously.
- [Project Mariner (Google)](https://deepmind.google/technologies/project-mariner/) — Gemini-powered browser agent. Navigates and completes tasks in Chrome.
- [Rabbit R1](https://rabbit.tech) — Hardware AI agent with a "Large Action Model." Performs tasks in apps on your behalf.
- [Humane Ai Pin](https://humane.com) — Wearable AI agent. Voice and gesture interface, persistent context.
- [Perplexity Assistant](https://perplexity.ai/assistant) — AI assistant that takes actions on Android. Schedules, searches, shops.
- [NotebookLM](https://notebooklm.google) — Google's AI research assistant. Reads documents and answers questions with citations.
- [Elicit](https://elicit.com) — AI research assistant for academic papers. Finds, summarizes, and synthesizes literature.
- [Consensus](https://consensus.app) — AI search engine for scientific research. Finds evidence from peer-reviewed papers.
- [Tavily](https://tavily.com) — Search API optimized for AI agents. Returns clean, relevant results specifically designed for LLM consumption.
- [Firecrawl](https://firecrawl.dev) — Web scraping API for AI agents. Converts any URL into clean markdown suitable for LLMs.
- [Browserbase](https://browserbase.com) — Headless browser infrastructure for AI agents. Run browser automations at scale in the cloud.
- [Stagehand](https://github.com/browserbase/stagehand) — AI-native browser automation framework. Playwright-based with LLM fallback for dynamic web tasks.

## Newsletters & Podcasts

- [The Batch (deeplearning.ai)](https://www.deeplearning.ai/the-batch/) — Andrew Ng's weekly AI newsletter. Balanced coverage of research and applications.
- [TLDR AI](https://tldr.tech/ai) — Daily AI news digest. Fast, curated, no hype.
- [Import AI](https://jack-clark.net) — Jack Clark's newsletter on AI capabilities and policy. One of the most informed perspectives.
- [Latent Space](https://www.latent.space) — Podcast and newsletter for AI engineers. Deep technical content.
- [Lex Fridman Podcast](https://lexfridman.com/podcast/) — Long-form conversations with AI researchers and builders.
- [No Priors](https://www.youtube.com/@NoPriorsPodcast) — AI and tech podcast from Sequoia and Conviction partners.
- [Practical AI](https://practicalai.fm) — Podcast making AI accessible for practitioners. Focus on applied, production AI.
