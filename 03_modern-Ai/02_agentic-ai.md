# Agentic AI

Agentic AI refers to systems that operate autonomously, making decisions and taking actions toward goals without constant human supervision. This is a core area of modern AI, where models like LLMs[...] 

## Learning Objectives

By the end of this module, you should be able to:

- Understand what AI agents are and how they differ from single-shot LLM usage
- Build agents that can use tools, retrieve data, and complete tasks across steps
- Understand frameworks like LangChain, Auto-GPT, and CrewAI
- Design multi-agent systems and task orchestration flows

## Why It’s Important

Agentic systems are key to making LLMs actually *useful* in real-world applications — from autonomous research assistants to customer service bots and AI co-pilots. They unlock continuous reason[...]


## Core Topics & Resources

### 1. What Are AI Agents?

- [LangChain: Agents & Tools Docs](https://docs.langchain.com/docs/components/agents/) — **Free**
- [What are AI Agents? – YouTube (AssemblyAI)](https://www.youtube.com/watch?v=JQkjhoq92JE) — **Free**
- [Agent Models in AI – A Short Introduction](https://www.microsoft.com/en-us/research/blog/the-emergence-of-agentic-ai/) — **Free**

Covers:
- Agent architecture: planning, memory, execution
- Task decomposition and multi-step workflows
- Reflection and self-healing behavior

### 2. Tool Use & Environments

- [Toolformer Paper (Meta AI)](https://arxiv.org/abs/2302.04761) — **Free**
- [OpenAI Function Calling Examples](https://platform.openai.com/docs/guides/gpt/function-calling) — **Free**
- [LangChain Tools + Agents Guide](https://python.langchain.com/docs/modules/agents/tools) — **Free**

Covers:
- How agents call external APIs, use calculators, web browsers, or code interpreters
- Multi-modal actions: text + code + tools
- Tool routing, fallback, and error handling

### 3. Agentic Frameworks

- [LangChain Agents](https://docs.langchain.com/docs/components/agents/) — **Free**
- [Auto-GPT (Torantulino)](https://github.com/Torantulino/Auto-GPT) — **Free, Open Source**
- [CrewAI (Multi-Agent Framework)](https://github.com/joaomdmoura/crewAI) — **Free**

Covers:
- Differences between scripted agents vs. LLM-driven agents
- Planning + memory modules (e.g., ReAct, BabyAGI, AutoGPT)
- Running agents locally or via API

### 4. Multi-Agent Systems & Advanced Topics

- [AutoGen (Microsoft)](https://github.com/microsoft/autogen) — Multi-agent orchestration with LLMs  
- [CAMEL: Communicative Agents Paper](https://arxiv.org/abs/2303.17760) — **Free**
- [Multi-Agent Simulations (Stanford)](https://crfm.stanford.edu/2023/04/19/ghost-in-the-machine.html) — **Free**

Covers:
- Role-based agents (e.g., planner, executor, verifier)
- Communication between agents
- Emergent behavior in simulated environments

### 5. Advanced Agentic AI Resources

- [Awesome AI Agents (GitHub)](https://github.com/veritable-tech/awesome-ai-agents) — **Curated list**
- [AgentBench: Benchmarking Foundation Model Agents](https://arxiv.org/abs/2308.07258) — **Free**
- [LLM Agents: Open Problems and Opportunities (arXiv)](https://arxiv.org/abs/2307.10169) — **Free**
- [OpenAgents (GitHub)](https://github.com/openagents/openagents) — **Open Source**

Covers:
- Benchmarks and evaluation for agentic systems
- Open-source agentic frameworks
- Research directions and challenges

### Hands-on Tutorials & Example Repos

- [ReAct: Synergizing Reasoning and Acting in Language Models (arXiv)](https://arxiv.org/abs/2210.03629) — Paper introducing the ReAct paradigm for combining reasoning and actions in LLMs — **Free**
- [langchain-ai/langchain-examples (GitHub)](https://github.com/langchain-ai/langchain-examples) — Example agent implementations, notebooks, and patterns for LangChain — **Free**
- [yoheinakajima/BabyAGI (GitHub)](https://github.com/yoheinakajima/babyagi) — Minimal agent loop implementation useful for prototyping ideas — **Free, Open Source**
- [Torantulino/Auto-GPT (GitHub)](https://github.com/Torantulino/Auto-GPT) — Autonomous agent that demonstrates goal-driven multi-step behavior — **Free, Open Source**
- [microsoft/autogen (GitHub)](https://github.com/microsoft/autogen) — Microsoft’s toolkit for multi-agent orchestration and simulations — **Free, Open Source**

Covers:
- Ready-to-run examples and templates to build agents quickly
- Minimal implementations for learning agent loops and memory
- Notebooks and tutorials that demonstrate tool use and function calling

## Suggested Projects & Practice

- Build a Research Agent: takes a question and returns summarized answers
- Create a multi-agent workflow (e.g., PM → Dev → Reviewer → Tester)
- Integrate an LLM agent with APIs (e.g., Notion, Google Search, Calculator)
- Use CrewAI or AutoGen to simulate a startup team

## Checkpoint: Before You Move On

You should now be able to:

- Explain and build LLM-based agents with memory, tools, and goals
- Use frameworks like LangChain, CrewAI, and AutoGen
- Design your own agent workflows or multi-agent systems

🔗 Next: [RAG →](./03_rag.md)
