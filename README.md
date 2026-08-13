# Hi, I'm Ish

Vice President & Lead Software Engineer at a top global financial services firm. 12+ years building backend systems, microservices, and automation frameworks, with the last year and a half increasingly spent on AI: wrapping models in production-grade services, and building the eval and testing infrastructure that makes agentic workflows safe to ship.

Background is Java and Python, distributed systems, and test automation at scale, so I still think like an SDET about anything I put into production: what breaks it, how you'd know, how you'd roll it back. That's the lens I bring to AI work too. Less "look what the model can do," more "here's how you'd know if it stopped working."

## What I'm working on

- **[llm-eval-harness](https://github.com/byte-ish/llm-eval-harness)**: a versioned, CI-gated eval suite for LLM features. Treats a model or prompt change like a code change, regression-tested against a fixed dataset version before it ships.
- **[langgraph-sidekick](https://github.com/byte-ish/langgraph-sidekick)**: a multi-agent assistant (LangGraph + Playwright) that does a task, evaluates its own output against success criteria, and loops until it's actually done or needs clarification.
- **[smart-enterprise-ai-copilot](https://github.com/byte-ish/smart-enterprise-ai-copilot)**: a multi-agent orchestration platform for enterprise workflows (Jira, Outlook), with memory and tool integration.
- **[ai_agent_platform](https://github.com/byte-ish/ai-agents/tree/main/langchain/projects/ai_agent_platform)**: a code-review / test-generation agent built two different ways (plain LangChain vs. LangGraph) so I could compare them directly instead of taking anyone's word for it.

## Recent writing

I write up technology decisions as evidence-based comparisons instead of opinions. Versions checked against primary sources, pricing verified, claims tagged by confidence, and the weighted scorecard published so a reader who disagrees with a priority can re-weight it and watch the answer move.

| Report | The decision it settles |
|---|---|
| **[LLM observability & evaluation platforms](https://github.com/byte-ish/llm-observability-eval-platforms)** | LangSmith vs Langfuse vs Arize Phoenix vs Braintrust vs MLflow 3, for multi-team agent workloads |
| **[Ray Serve in the MDLC](https://github.com/byte-ish/ray-serve-inference-mdlc)** | Where Ray Serve fits, and does not fit, in an enterprise model lifecycle |
| **[Google ADK vs LangChain/LangGraph](https://github.com/byte-ish/google-adk-vs-langchain-langgraph)** | Standardising on one agent framework across teams |
| **[Argo Workflows vs Kubeflow Pipelines](https://github.com/byte-ish/argo-workflows-vs-kubeflow-pipelines)** | ML/MLOps orchestration on Kubernetes |
| **[Spring Boot vs FastAPI](https://github.com/byte-ish/spring-boot-vs-fastapi-ai-microservices)** | AI-enabled microservices in a regulated enterprise |
| **[Litestar vs FastAPI](https://github.com/byte-ish/litestar-vs-fastapi)** | Production services and agent backends |

A recurring theme across these: the open-source label and the neutral choice are not the same thing, and the interesting cost is rarely the sticker price.

## Background

Most of my career has been in regulated financial services, where the hard part is rarely the algorithm and almost always the blast radius: how a change reaches production, what evidence proves it is safe, and how quickly you can undo it. That constraint shapes everything below.

The technical core is JVM and distributed systems. Java and Spring for services, Kafka for event-driven integration, and test automation designed to run unattended against systems you don't fully control. Much of it was platform work that other engineering teams depended on rather than features an end user ever saw, which turns out to be useful grounding before designing anything agentic.

| | |
|---|---|
| **Languages** | Java, Python |
| **Services & integration** | Spring, Kafka, FastAPI, REST microservices, distributed systems |
| **Quality engineering** | Wiremock, Serenity, Mockito, CI-gated regression suites, SDET practice at scale |
| **AI engineering** | LangChain, LangGraph, multi-agent orchestration, RAG, LLM evaluation, MCP |
| **Delivery** | Docker, MLflow, CI/CD pipelines |

That foundation is why the AI work above leans toward evals, CI gates, and production concerns rather than notebooks and demos. The industry has no shortage of people who can get a model to do something impressive once. Rather less common is the discipline to prove it still works on the four hundredth run, in an environment where being wrong is expensive.

---
Open to connecting with people working on AI engineering, backend/platform systems, or enterprise automation. Views here are my own.
