# Awesome-AI-Agent-Frameworks

## Top AI Agent Frameworks Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Multi-Agent Orchestration, Tool-Using Agents, Stateful Workflows & Lightweight Agent Libraries*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Frameworks**. These libraries and platforms help developers build, orchestrate, and deploy single- and multi-agent systems that use tools, maintain state, call APIs, and complete complex tasks.



**Examples** include LangChain, Microsoft AutoGen, CrewAI Enterprise, Semantic Kernel, Haystack, Flowise, LangGraph Cloud, Dify, DSPy, and SuperAGI (the category leaders).



**Open-source emphasis**: The agent framework space is dominated by strong open-source projects. **smolagents**, **LangGraph**, **CrewAI**, **Microsoft Agent Framework**, **LlamaIndex**, **AutoGen**, and many others enable fully controllable agent development. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global AI Agent market is projected to grow from ~$8 billion in 2025 to over $50 billion by 2030 at a CAGR exceeding 45%. The market landscape is dual-structured: it remains **moderately to highly fragmented** across vertical-specific agent builders and workflow tooling startups, while remaining **highly concentrated** at the core enterprise infrastructure, orchestration, and foundational model layers dominated by major cloud hyperscalers.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Size | Starting Paid Tier Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft AutoGen / Azure AI Foundry Agent Service](https://learn.microsoft.com/en-us/azure/ai-studio/concepts/agent-service)** | $4.0+ Trillion Market Cap (Microsoft) | $0 platform fee (PAYGO compute at ~$0.05/container hr for custom hosted agents + model token consumption) | Free forever platform orchestration (No extra management fee; default quotas: up to 100k messages/thread, 128 tools/agent, 300GB storage; users bring own Azure credits or standard model quotas) | Enterprise-grade agent service supporting AutoGen and Microsoft Agent Framework with fully managed state, tool execution, and security. |
| **[Semantic Kernel / Azure AI](https://learn.microsoft.com/en-us/semantic-kernel/)** | $4.0+ Trillion Market Cap (Microsoft) | $0 SDK / Azure PAYGO model token consumption | 30-day Azure free trial with $200 credits; free SDK use with no seat fees (resource usage bounded only by Azure subscription quotas) | Enterprise SDK and cloud orchestration connecting LLM plugins, memories, and planner-driven agentic architectures. |
| **[Flowise](https://flowiseai.com/)** | ~$48 Billion Market Cap (Acquired by Workday) | $35/month (Starter tier) | Free forever plan: 2 flows/assistants, 100 predictions/month, 5 MB storage, and community support | Low-code / visual canvas interface to design and deploy agent chains, vector retrieval, and custom multi-agent logic. |
| **[LangChain / LangSmith](https://www.langchain.com/)** | $1.25 Billion Valuation (~$15M ARR) | $39/seat/month (Plus tier) | Free forever Developer plan: 1 user seat, 5,000 base traces/month (strictly hard-capped without credit card), 14-day data retention | Comprehensive LLMOps, evaluation, and observability control plane for AI agents and multi-agent chains. |
| **[LangGraph Platform](https://www.langchain.com/langgraph)** | $1.25 Billion Valuation (~$15M ARR; LangChain) | $39/seat/month (LangSmith Plus base + usage) | Free forever Developer plan: 1 user seat, 100,000 node executions/month, 1 local/self-hosted Lite deployment, 5,000 LangSmith traces | Managed cloud deployment, persistence layer, task queuing, and streaming server for cyclic, stateful multi-agent workflows. |
| **[Dify](https://dify.ai/)** | $180 Million Valuation ($30M Series Pre-A) | $59/workspace/month (Professional tier) | Free forever Sandbox plan: 1 team member, 200 system message credits, up to 5 apps, 50 MB knowledge base / 50 documents | Visual generative AI application platform and workflow builder for autonomous agents, RAG, and prompt management. |
| **[CrewAI Enterprise](https://www.crewai.com/)** | $50M - $100M Valuation ($18M funding) | $99/month (Starter / entry cloud tier; custom enterprise contracts from $6,000/year) | Free forever Basic plan: 1 user seat, 50 workflow executions/month, access to visual agent studio, guardrails, and templates | Managed orchestration workspace for defining, monitoring, and deploying role-based collaborative AI agent teams. |
| **[Haystack / deepset Studio](https://haystack.deepset.ai/)** | ~$46 Million Funding (~$12.5M ARR; deepset) | Custom enterprise licensing / AWS Marketplace contracts (contact sales) | Free forever Studio tier: 1 user, 1 workspace, 100 pipeline hours, 2 development pipelines, 50 files max (up to 10MB/file), 14-day logs | Enterprise platform and production suite built atop the open-source Haystack pipeline framework for RAG and agent systems. |
| **[SuperAGI Cloud](https://superagi.com/)** | $25M - $50M Valuation (~$12M funding) | $49/user/month (Pro plan) | Free forever plan: 100 AI credits/month, 2 outbound email agents, 20–25 prospects/day outreach cap, basic agentic CRM | Cloud-hosted autonomous agent workspace focused on self-directing workflow execution, sales prospecting, and tool-augmented agents. |



## Open-Source GitHub Projects

- **[smolagents](https://github.com/huggingface/smolagents)**  

  Library from Hugging Face to build lightweight agents in just a few lines of code — simple, flexible, and designed for quick experimentation and tool use.



- **[LangGraph](https://github.com/langchain-ai/langgraph)**  

  Low-level orchestration framework for building stateful, multi-actor applications with LLMs — supporting cycles, branching, checkpointing, and human-in-the-loop.



- **[CrewAI](https://github.com/crewAIInc/crewAI)**  

  Open-source multi-agent orchestration framework for defining agents with roles, goals, and tools, then running them as coordinated crews.



- **[Microsoft Agent Framework](https://github.com/microsoft/agent-framework)**  

  Open multi-language framework for production-grade AI agents and multi-agent workflows (evolution of ideas from AutoGen and Semantic Kernel).



- **[AutoGen](https://github.com/microsoft/autogen)**  

  Established multi-agent conversation framework (now largely in maintenance mode; many teams migrating to Microsoft Agent Framework).



- **[LlamaIndex](https://github.com/run-llama/llama_index)**  

  Data framework for LLM applications with strong agent and workflow abstractions for retrieval-augmented and tool-using systems.



- **[Haystack](https://github.com/deepset-ai/haystack)**  

  Open-source LLM framework focused on production RAG pipelines, agents, and composable NLP components.



- **[Dify](https://github.com/langgenius/dify)**  

  Open-source platform for building and deploying LLM applications, agents, and workflows with a visual studio and backend APIs.



- **[Flowise](https://github.com/FlowiseAI/Flowise)**  

  Open-source low-code tool for building LLM chains and agents via a drag-and-drop interface.



- **[DSPy](https://github.com/stanfordnlp/dspy)**  

  Open-source framework for compiling declarative LLM programs into efficient prompts and pipelines.



- **[Semantic Kernel](https://github.com/microsoft/semantic-kernel)**  

  Open-source SDK for integrating large language models into applications with planners, plugins, and agent-style orchestration.



- **[Documentation and framework comparison guides](https://langchain-ai.github.io/langgraph/)**  

  Official docs, tutorials, and community resources for choosing and combining open agent frameworks.



### Additional Strong Open-Source Options

- Starting simple with **smolagents** for lightweight, few-line agent prototypes.

- Building production stateful agents with **LangGraph** or role-based teams with **CrewAI**.

- Using **Microsoft Agent Framework** or **LlamaIndex** for enterprise-oriented or data-centric agents.

- Combining **Dify** or **Flowise** for visual development with underlying open frameworks.

- Exploring **DSPy** when you want programmatic optimization of prompts and pipelines.

- Accepting that commercial/hosted layers (LangSmith, CrewAI Enterprise, LangGraph Cloud, Dify Cloud, etc.) still lead in managed observability, scaling, and support.



**Frameworks for building custom systems**: Prototype with **smolagents** → orchestrate complex flows with **LangGraph** or **CrewAI** → add data/RAG via **LlamaIndex** or **Haystack** → deploy with open or self-hosted runtimes. Suitable for teams that want full control and transparency. Many organizations still use commercial platforms for SLAs, compliance, and integrated tooling.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Agent frameworks evolve rapidly; always review licenses, security practices, and maintenance status before production use. This list is not architecture or security advice.



---

**Made for AI engineers, agent builders, and open-source developers.**

Let's keep agent frameworks powerful, composable, and as open as practical.
