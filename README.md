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

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[LangChain / LangSmith](https://www.langchain.com/)**  

  Ecosystem and commercial platform built around the open-source LangChain library, offering tracing, evaluation, deployment, and enterprise support for agent applications.



- **[Microsoft AutoGen / Agent Framework offerings](https://microsoft.github.io/autogen/)**  

  Microsoft’s multi-agent conversation framework and related enterprise tooling for building collaborative agent systems (with migration paths toward Microsoft Agent Framework).



- **[CrewAI Enterprise](https://www.crewai.com/)**  

  Hosted and enterprise offerings built on the open-source CrewAI multi-agent framework for role-based agent teams and production workflows.



- **[Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/)**  

  Microsoft’s open SDK and associated cloud/enterprise guidance for integrating LLMs into applications with planners, plugins, and agent patterns.



- **[Haystack](https://haystack.deepset.ai/)**  

  NLP and LLM framework from deepset with commercial support options; widely used for RAG pipelines and agent-style applications.



- **[Flowise](https://flowiseai.com/)**  

  Low-code / no-code platform for building LLM chains and agents with a visual interface (open-source core with hosted options).



- **[LangGraph Cloud / LangGraph Platform](https://www.langchain.com/langgraph)**  

  Managed offering for deploying and scaling stateful LangGraph agents with persistence, monitoring, and production features.



- **[Dify](https://dify.ai/)**  

  Open-source LLM application platform with visual workflow builder, agent support, and commercial cloud hosting options.



- **[DSPy](https://dspy.ai/)**  

  Framework for programming (not just prompting) language models; research-originated with growing tooling and community support.



- **[SuperAGI](https://superagi.com/)**  

  Open-source agent framework with commercial/cloud offerings focused on autonomous agents and tool-using workflows.



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
