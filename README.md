# Agentic AI Roadmap

**Live site:** https://jlaiii.github.io/agentic-ai-roadmap/

A human-friendly research guide to building and deploying agentic AI systems — from simple chatbots all the way to autonomous AI workers that manage themselves.

## What This Is

This is a living research project. It breaks down the evolution of AI agents into 6 clear stages anyone can understand, then shows you exactly how to build and deploy each level — whether you're a beginner or an engineer.

## The 6 Stages

1. **Chatbot** — Ask a question, get an answer. Passive.
2. **Copilot** — AI assists you while you stay in control.
3. **Agent** — AI picks a tool and completes a task on its own.
4. **Multi-Agent Team** — Specialized agents hand off work to each other.
5. **Agent Swarm** — Agents debate, review, and self-correct to find the best answer.
6. **Autonomous Organization** — AI workers manage other AI workers with minimal human oversight.

## Topics Covered

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
- **2 Agent Harnesses** — full-suite systems that run your entire machine:
  - **Hermes Agent** (148,127 ★) — model-agnostic, self-improving, 40+ tools, multi-platform gateway, cron scheduling, subagents
  - **OpenManus** (56,233 ★) — MetaGPT team's open agent with RL training pipeline
- **Evaluation** — benchmarking what actually works:
  - LM Evaluation Harness (12,540 ★) — 200+ tasks, powers HuggingFace leaderboard
  - SWE-bench (8,566 ★) — real GitHub issue resolution for coding agents
- **Production Reality** — cost, safety, observability, latency, context limits
- **Timeline** — from ChatGPT (Nov 2022) to A2A (Apr 2025)
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
| Hermes Agent | 148,127 | Full PC control, any model, self-improving |
| OpenManus | 56,233 | Research, custom behavior, RL training |

### Evaluation

| Tool | Stars | Best For |
|------|-------|----------|
| LM Evaluation Harness | 12,540 | Standardized model benchmarking |
| SWE-bench | 8,566 | Real-world coding agent evaluation |

## Agent Harnesses Explained

**Hermes Agent** (Nous Research) is what this roadmap was researched with. It's a full-suite system you install on a Linux box, server, or VPS. Point it at any LLM — OpenRouter (200+ models), OpenAI, Claude, local Llama, Kimi, MiniMax, whatever — and it becomes an autonomous worker.

It has 40+ built-in tools, MCP server support, custom skills, terminal access, file management, web browsing, code execution, cron scheduling, voice memos, and a gateway that bridges Telegram, Discord, Slack, WhatsApp, Signal, and Email. The self-improving skill system means it gets better the longer it runs.

You don't need to be a coder. You just need to understand how your system is laid out and what you want done. The agent handles the rest.

## Contributing

This is just the beginning. Research notes, data, and new findings will be added here as the field evolves. Open an issue or PR with new frameworks, updated stats, or corrections.
