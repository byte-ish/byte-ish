# Hi, I'm Ish

Vice President & Lead Software Engineer at a top global financial services firm. 12+ years building backend systems, microservices, and automation frameworks — the last year and a half of that increasingly spent on AI: wrapping models in production-grade services, and building the eval and testing infrastructure that makes agentic workflows safe to ship.

Background is Java and Python, distributed systems, and test automation at scale, so I still think like an SDET about anything I put into production — what breaks it, how you'd know, how you'd roll it back. That's the lens I bring to AI work too: less "look what the model can do," more "here's how you'd know if it stopped working."

## What I'm working on

- **[llm-eval-harness](https://github.com/byte-ish/llm-eval-harness)** — a versioned, CI-gated eval suite for LLM features. Treats a model or prompt change like a code change: regression-tested against a fixed dataset version before it ships.
- **[langgraph-sidekick](https://github.com/byte-ish/langgraph-sidekick)** — a multi-agent assistant (LangGraph + Playwright) that does a task, evaluates its own output against success criteria, and loops until it's actually done or needs clarification.
- **[smart-enterprise-ai-copilot](https://github.com/byte-ish/smart-enterprise-ai-copilot)** — a multi-agent orchestration platform for enterprise workflows (Jira, Outlook), with memory and tool integration.
- **[ai_agent_platform](https://github.com/byte-ish/ai-agents/tree/main/langchain/projects/ai_agent_platform)** — a code-review / test-generation agent built two different ways (plain LangChain vs. LangGraph) so I could compare them directly instead of taking anyone's word for it.

## Recent writing

I write up technology decisions as evidence-based comparisons instead of opinions — versions checked, sources cited, confidence level stated up front:

- **[Litestar vs FastAPI](https://github.com/byte-ish/litestar-vs-fastapi)** — for production services and agent backends
- **[Argo Workflows vs Kubeflow Pipelines](https://github.com/byte-ish/argo-workflows-vs-kubeflow-pipelines)** — for ML/MLOps orchestration on Kubernetes

## Background

Java, Spring, Kafka, and test automation (Wiremock, Serenity, Mockito) make up most of the rest of this profile — over a decade of it. That foundation is why the AI work above leans toward evals, CI gates, and production concerns rather than notebooks and demos.

---
Open to connecting with people working on AI engineering, backend/platform systems, or enterprise automation. Views here are my own.
