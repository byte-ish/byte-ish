# Hi, I'm Ish

I spent several years working mostly in Java — Spring, Kafka, test automation — and over the last year and a half that's shifted almost entirely to Python, LLMs, and the tooling around running them: agents, evals, RAG pipelines, and the infrastructure decisions that come with putting any of that in production.

## What I'm working on

- **[llm-eval-harness](https://github.com/byte-ish/llm-eval-harness)** — a versioned, CI-gated eval suite for LLM features. Treats a model or prompt change like a code change: regression-tested against a fixed dataset version before it ships.
- **[langgraph-sidekick](https://github.com/byte-ish/langgraph-sidekick)** — a multi-agent assistant (LangGraph + Playwright) that does a task, evaluates its own output against success criteria, and loops until it's actually done or needs clarification.
- **[smart-enterprise-ai-copilot](https://github.com/byte-ish/smart-enterprise-ai-copilot)** — a multi-agent orchestration platform for enterprise workflows (Jira, Outlook), with memory and tool integration.
- **[ai_agent_platform](https://github.com/byte-ish/ai-agents/tree/main/langchain/projects/ai_agent_platform)** — a code-review / test-generation agent built two different ways (plain LangChain vs. LangGraph) so I could compare them directly instead of taking anyone's word for it.

## Recent writing

I write up technology decisions as evidence-based comparisons instead of opinions — versions checked, sources cited, confidence level stated up front:

- **[Litestar vs FastAPI](https://github.com/byte-ish/litestar-vs-fastapi)** — for production services and agent backends
- **[Argo Workflows vs Kubeflow Pipelines](https://github.com/byte-ish/argo-workflows-vs-kubeflow-pipelines)** — for ML/MLOps orchestration on Kubernetes

## Elsewhere

The rest of this profile is mostly older Java and test-automation work (Spring, Kafka, Wiremock, Serenity) from before the shift. Still here, just not where my time goes now.
