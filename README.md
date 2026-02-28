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
