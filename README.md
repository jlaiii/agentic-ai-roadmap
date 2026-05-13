# Agentic AI Roadmap

**Live site:** https://jlaiii.github.io/agentic-ai-roadmap/

A human-friendly research guide to building and deploying agentic AI systems — from simple chatbots all the way to autonomous AI workers that manage themselves.

## What This Is

This is a living research project. It starts with the transformer engine that powers every agent, then breaks down the evolution of AI agents into 6 clear stages anyone can understand — from simple chatbots all the way to autonomous AI workers that manage themselves.

## The 6 Stages

1. **Chatbot** — Ask a question, get an answer. Passive.
2. **Copilot** — AI assists you while you stay in control.
3. **Agent** — AI picks a tool and completes a task on its own.
4. **Multi-Agent Team** — Specialized agents hand off work to each other.
5. **Agent Swarm** — Agents debate, review, and self-correct to find the best answer.
6. **Autonomous Organization** — AI workers manage other AI workers with minimal human oversight.

## Topics Covered

- **The Transformer Engine** — how LLMs actually work: attention mechanism, next-token prediction, parameters vs tokens, pre-training → fine-tuning → RLHF, and why this matters for agents

- **6 Stages** of agentic maturity with engineer and beginner paths
- **3 Orchestration Patterns**: Supervisor, Debate/Critic, Swarm
- **8 Frameworks** with live GitHub stats:
  - n8n (187,690 ★) — low-code automation
  - Dify (141,231 ★) — production platform
  - LangChain (136,637 ★) — foundational platform
  - Browser Use (93,725 ★) — web automation for agents
  - CrewAI (51,322 ★) — role-based teams
  - AutoGen (57,999 ★) — Microsoft multi-agent framework
  - LangGraph (31,955 ★) — graph-based workflows
  - OpenAI Agents SDK (26,272 ★) — minimal primitives
- **2 Protocols**: MCP ("USB-C for AI tools") + A2A (Agent-to-Agent Protocol)
- **3 Agent Harnesses** — full-suite systems that run your entire machine:
  - **Hermes Agent** (148,127 ★) — model-agnostic, self-improving, 40+ tools, multi-platform gateway, cron scheduling, subagents
  - **OpenClaw** (371,497 ★) — fastest-growing agent project, personal AI on any device, live Canvas, voice
  - **OpenManus** (56,233 ★) — MetaGPT team's open agent with RL training pipeline
- **The Black Box** — why we don't understand how LLMs work, emergent behavior, and how output filtering (RLHF, guardrails) is our duct-tape fix
- **Security & Adversarial Risks** — OWASP LLM Top 10 + Agentic AI Top 10, prompt injection, jailbreak techniques, sandbox escapes with real CVEs (CVSS 9+), defense tools (Garak, PyRIT, Promptfoo, LLM Guard), real company incidents (Samsung, Chevy, DPD)
- **AGI: Artificial General Intelligence** — what AGI actually means, why it's not about consciousness, why people conflate the two, and personal observations of emergent agent behavior
- **Memory & State Architecture** — RAG, vector databases (Pinecone, Weaviate, Chroma, Qdrant, pgvector), episodic/semantic/procedural memory, LangGraph/AutoGen state machines, MemGPT virtual memory, Mem0, persistence strategies
- **Agent Teaching & Context Engineering** — why you still need to understand the system you're automating, how skills work as "books" the agent reads, why specificity beats cleverness, and the teach-then-release loop
- **Human-in-the-Loop & Approval Workflows** — staged approvals, confidence thresholds, risk tiers (auto → notify → approve → multi-party), LangGraph interrupt nodes, anti-patterns like approval fatigue
- **5 Models I've Tested**:
  - **OpenAI Codex** (82,325 ★ repo) — terminal coding agent, April 2025
  - **Claude Code** (181,106 ★ resources) — Anthropic's terminal agent with Kairos memory
  - **Gemini CLI** (103,860 ★) — Google's open-source terminal agent, June 2025
  - **Kimi K2.6** — Moonshot AI trillion-parameter open model, April 2026
  - **DeepSeek R1/V3** — open-source reasoning, MIT licensed, runs on consumer GPUs
- **Multimodal Agents** — GPT-4V, Claude 3 Vision, Gemini; Browser Use, OSWorld, CogAgent; document understanding (Docling, Marker); vision benchmarks (MMMU, MathVista); cost reality of vision tokens
- **Fine-Tuning & Domain Adaptation** — LoRA, QLoRA, PEFT methods, synthetic data generation, adapter serving in production, when to fine-tune vs. prompt
- **Evaluation** — benchmarking what actually works:
  - LM Evaluation Harness (12,540 ★) — 200+ tasks, powers HuggingFace leaderboard
  - SWE-bench (8,566 ★) — real GitHub issue resolution for coding agents
- **Observability & Debugging** — LangSmith/Langfuse/OpenTelemetry tracing, token burn tracking, evaluation pipelines (Promptfoo, Garak, PyRIT), SRE for agents, time-travel debugging with checkpointing
- **Production Reality** — cost, safety, observability, latency, context limits
- **Legal, Compliance & Liability** — EU AI Act (Aug 2026 deadline), GDPR Article 22, risk categories, deployer liability, copyright training data lawsuits, 6-point compliance checklist
- **History** — full timeline from GPT-1 (Jun 2018) to Kimi K2.6 (Apr 2026)
- **Community & Resources** — key papers (Attention, ReAct, CoT, MemGPT, Toolformer, SWE-bench, GAIA), people to follow (Karpathy, Mollick, Willison, Swyx, Weng, Ng), newsletters, Discord/Reddit communities, model comparison tools
- **Interactive Framework Picker** — answer one question, get a recommendation

## Stats (May 2026)

### Frameworks

| Framework | Stars | Best For |
|-----------|-------|----------|
| n8n | 187,690 | Business automation, visual workflows |
| Dify | 141,231 | Production apps, teams |
| LangChain | 136,637 | Custom architectures, deep control |
| Browser Use | 93,725 | Web automation, scraping |
| AutoGen | 57,999 | Conversational agents, debates |
| CrewAI | 51,322 | Quick prototypes, role-based crews |
| LangGraph | 31,955 | Stateful flows, cyclic logic |
| OpenAI Agents SDK | 26,272 | Learning internals, OpenAI shops |

### Harnesses

| Harness | Stars | Best For |
|---------|-------|----------|
| OpenClaw | 371,497 | Personal AI, any device, fastest growing |
| Hermes Agent | 148,127 | Full PC control, any model, self-improving |
| OpenManus | 56,233 | Research, custom behavior, RL training |

### Models Tested

| Model | Provider | Best For |
|-------|----------|----------|
| Codex | OpenAI | Terminal coding, IDE integration |
| Claude Code | Anthropic | Complex reasoning, multi-file editing |
| Gemini CLI | Google | Long context, Google Cloud integration |
| Kimi K2.6 | Moonshot AI | Agent swarms, self-hosting, coding |
| DeepSeek R1/V3 | DeepSeek | Local inference, reasoning, cost-saving |

### Evaluation

| Tool | Stars | Best For |
|------|-------|----------|
| LM Evaluation Harness | 12,540 | Standardized model benchmarking |
| SWE-bench | 8,566 | Real-world coding agent evaluation |

## Agent Harnesses Explained

**Hermes Agent** (Nous Research) is what this roadmap was researched with. It's a full-suite system you install on a Linux box, server, or VPS. Point it at any LLM — OpenRouter (200+ models), OpenAI, Claude, local Llama, Kimi, MiniMax, whatever — and it becomes an autonomous worker.

It has 40+ built-in tools, MCP server support, custom skills, terminal access, file management, web browsing, code execution, cron scheduling, voice memos, and a gateway that bridges Telegram, Discord, Slack, WhatsApp, Signal, and Email. The self-improving skill system means it gets better the longer it runs.

**OpenClaw** is the viral predecessor that Hermes migrated from. 371K stars in weeks — the fastest-growing AI agent project in GitHub history. Personal AI assistant on any device with live Canvas and voice.

You don't need to be a coder. You just need to understand how your system is laid out and what you want done. The agent handles the rest.

## The Black Box Problem

Modern LLMs have hundreds of billions of parameters. We can observe inputs and outputs, but nobody — not the researchers who built them, not the companies shipping them — can fully trace what happens in between. Capabilities like in-context learning and chain-of-thought reasoning *emerge* at scale; they weren't explicitly programmed.

Since we can't understand the internal reasoning, we put filters on the **output**: RLHF trains a reward model that scores outputs as "good" or "bad." System prompts, guardrails, and content policies are all duct-taped controls on a system we don't fundamentally understand. This is the defining engineering challenge of the field.

## Contributing

This is just the beginning. Research notes, data, and new findings will be added here as the field evolves. Open an issue or PR with new frameworks, updated stats, or corrections.
