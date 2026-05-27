# Trending AI projects list

A curated overview of the top open-source AI repositories, organised by category. Each section covers a distinct layer of the modern AI stack — from orchestration frameworks and RAG pipelines to coding agents, evaluation tooling, and model serving infrastructure.
This list is subject to change and will be updated regularly.

*Maintained at [bobpage0451/ai-trending-repos](https://github.com/bobpage0451/ai-trending-repos) • Last updated: 2026-05-27 (refreshed bi-weekly)*

![banner_grah](banner_graph.png)
- [App orchestration layer](#app-orchestration-layer)
- [RAG, memory, and knowledge layer](#rag-memory-and-knowledge-layer)
- [Language models and foundation model layer](#language-models-and-foundation-model-layer)
- [Agent and workflow layer](#agent-and-workflow-layer)
- [Tools, MCP, and integration layer](#tools-mcp-and-integration-layer)
- [UI and generative interface layer](#ui-and-generative-interface-layer)
- [AI coding agents and developer experience](#ai-coding-agents-and-developer-experience)
- [Evaluation and testing layer](#evaluation-and-testing-layer)
- [Observability, tracing, and prompt management](#observability-tracing-and-prompt-management)
- [Guardrails, safety, governance, and policy layer](#guardrails-safety-governance-and-policy-layer)
- [Model training, fine-tuning, and adaptation](#model-training-fine-tuning-and-adaptation)
- [Deployment, local inference, and model serving layer](#deployment-local-inference-and-model-serving-layer)

---

## App orchestration layer

This is the core application framework layer for building AI apps. It helps structure LLM calls, chains, workflows, tool use, retrieval, memory, callbacks, and agent execution.

Connect prompts, models, tools, memory, retrieval, agents, and workflows.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 137.8k | 22821 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [appsmithorg/appsmith](https://github.com/appsmithorg/appsmith) | 39.9k | 4580 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | 33.1k | 5594 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 25.4k | 2810 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | MDX |
| [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents) | 23.4k | 3310 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [google/adk-python](https://github.com/google/adk-python) | 19.9k | 3465 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [Chainlit/chainlit](https://github.com/Chainlit/chainlit) | 12.1k | 1712 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/agent-framework](https://github.com/microsoft/agent-framework) | 10.8k | 1786 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [InternLM/lagent](https://github.com/InternLM/lagent) | 2.3k | 231 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [run-llama/llama-agents](https://github.com/run-llama/llama-agents) | 381 | 66 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## RAG, memory, and knowledge layer

This layer includes retrieval-augmented generation, semantic search, embeddings, vector storage, hybrid search, reranking, citations, document permissions, and short-term or long-term memory.

Give the model external, project, user, or company knowledge.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 81.4k | 9329 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | 56.9k | 6486 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [MemPalace/mempalace](https://github.com/MemPalace/mempalace) | 52.9k | 6980 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | 49.7k | 7468 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [milvus-io/milvus](https://github.com/milvus-io/milvus) | 44.5k | 4026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [VectifyAI/PageIndex](https://github.com/VectifyAI/PageIndex) | 32.2k | 2776 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [qdrant/qdrant](https://github.com/qdrant/qdrant) | 31.6k | 2298 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [chroma-core/chroma](https://github.com/chroma-core/chroma) | 28.1k | 2274 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [weaviate/weaviate](https://github.com/weaviate/weaviate) | 16.2k | 1298 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [memvid/memvid](https://github.com/memvid/memvid) | 15.6k | 1344 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |

## Language models and foundation model layer

This layer includes proprietary, open-weight, and local language models used for chat, reasoning, coding, embeddings, multimodal tasks, and agentic workflows. It covers model families such as OpenAI GPT, Anthropic Claude, Google Gemini and Gemma, Meta Llama, Mistral, DeepSeek, Qwen, Cohere, GitHub Models, and other foundation models.

Choose, compare, and use the underlying language models that power AI applications.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) | 103.6k | 16744 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [deepseek-ai/DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) | 92k | 11728 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | N/A |
| [google-deepmind/gemma](https://github.com/google-deepmind/gemma) | 5.3k | 937 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Agent and workflow layer

This layer covers tool-using agents, graph-based workflows, planner-executor patterns, multi-agent collaboration, human approval steps, state management, retries, and long-running task execution.

Build systems that can plan, call tools, perform multi-step tasks, and coordinate agents.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | 375k | 78185 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [langflow-ai/langflow](https://github.com/langflow-ai/langflow) | 148.8k | 9128 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | 69.8k | 9400 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [FoundationAgents/MetaGPT](https://github.com/FoundationAgents/MetaGPT) | 68.3k | 8705 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | 52.3k | 7264 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [agno-agi/agno](https://github.com/agno-agi/agno) | 40.4k | 5429 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) | 33.2k | 4122 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [huggingface/smolagents](https://github.com/huggingface/smolagents) | 27.5k | 2618 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [openai/openai-agents-python](https://github.com/openai/openai-agents-python) | 26.7k | 4108 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [letta-ai/letta](https://github.com/letta-ai/letta) | 23k | 2450 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Tools, MCP, and integration layer

This layer includes Model Context Protocol servers and clients, tool schemas, function calling, API connectors, filesystem access, browser access, database access, and integrations with services like GitHub, Slack, Google Drive, and internal tools.

Let models and agents interact with external systems, APIs, databases, files, and tools.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | 104.7k | 13895 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | 95.8k | 10784 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | 33.1k | 2717 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [ComposioHQ/composio](https://github.com/ComposioHQ/composio) | 28.5k | 4589 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) | 25.3k | 2034 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) | 16.2k | 5299 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Jupyter Notebook](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) |
| [Netflix/metaflow](https://github.com/Netflix/metaflow) | 10.1k | 1279 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) | 10k | 1303 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [steel-dev/steel-browser](https://github.com/steel-dev/steel-browser) | 7.1k | 933 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) | 6.4k | 733 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) |

## UI and generative interface layer

This layer is more than normal frontend. It includes chat UIs, streaming responses, agent dashboards, tool-call displays, generated UI, copilot components, diff viewers, file attachments, code previews, and human approval interfaces.

Build the user-facing interface for AI applications.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 115.1k | 8926 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [streamlit/streamlit](https://github.com/streamlit/streamlit) | 44.7k | 4262 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [gradio-app/gradio](https://github.com/gradio-app/gradio) | 42.7k | 3481 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) | 31.8k | 4109 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | 28k | 4608 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C#](https://img.shields.io/badge/-C%23-239120?logo=csharp&logoColor=white) |
| [tambo-ai/tambo](https://github.com/tambo-ai/tambo) | 11.1k | 568 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [huggingface/chat-ui](https://github.com/huggingface/chat-ui) | 10.7k | 1647 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [richardgill/llm-ui](https://github.com/richardgill/llm-ui) | 1.7k | 89 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |

## AI coding agents and developer experience

This category includes AI coding assistants, autonomous coding agents, repo-editing agents, terminal agents, IDE extensions, pair programmers, code review tools, and systems that inspect, modify, test, and explain codebases.

Help developers write, edit, review, understand, and run code with AI.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 169.8k | 28331 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | 166.1k | 19744 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [openai/codex](https://github.com/openai/codex) | 86.3k | 12614 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 65.5k | 3695 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [cline/cline](https://github.com/cline/cline) | 62.4k | 6550 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [Aider-AI/aider](https://github.com/Aider-AI/aider) | 45.4k | 4494 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [continuedev/continue](https://github.com/continuedev/continue) | 33.4k | 4568 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) | 19.3k | 2102 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Evaluation and testing layer

This layer includes prompt tests, regression tests, model comparisons, RAG evaluation, hallucination checks, LLM-as-judge metrics, agent task success evaluation, red-team tests, and CI/CD quality gates.

Measure whether an AI app, prompt, RAG pipeline, model, or agent is improving or getting worse.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | 26.1k | 5787 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | 21.7k | 1904 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [vibrantlabsai/ragas](https://github.com/vibrantlabsai/ragas) | 14.1k | 1446 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | 12.7k | 3294 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | 7.9k | 970 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [truera/trulens](https://github.com/truera/trulens) | 3.3k | 281 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [huggingface/lighteval](https://github.com/huggingface/lighteval) | 2.4k | 473 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [msoedov/agentic_security](https://github.com/msoedov/agentic_security) | 1.9k | 258 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Observability, tracing, and prompt management

This layer gives visibility into what happened inside an AI system. It includes tracing, span trees, prompt logs, completion logs, token usage, cost monitoring, feedback capture, prompt versioning, and evaluation dashboards.

Track prompts, completions, costs, latency, errors, tool calls, traces, retrieved context, and feedback.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [evidentlyai/evidently](https://github.com/evidentlyai/evidently) | 7.5k | 853 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Jupyter Notebook](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) |
| [traceloop/openllmetry](https://github.com/traceloop/openllmetry) | 7.1k | 978 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [Helicone/helicone](https://github.com/Helicone/helicone) | 5.7k | 590 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |

## Guardrails, safety, governance, and policy layer

This layer includes input and output filters, PII detection, jailbreak and prompt-injection defenses, safe tool calling, policy engines, human approvals, governance, compliance, audit logs, and red-team testing.

Prevent harmful outputs, unsafe tool calls, prompt injection, data leakage, and uncontrolled agent behavior.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [microsoft/presidio](https://github.com/microsoft/presidio) | 8.3k | 1077 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [guardrails-ai/guardrails](https://github.com/guardrails-ai/guardrails) | 6.9k | 613 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [superagent-ai/superagent](https://github.com/superagent-ai/superagent) | 6.6k | 958 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) | 2.9k | 460 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [agentcontrol/agent-control](https://github.com/agentcontrol/agent-control) | 252 | 36 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Model training, fine-tuning, and adaptation

For most app builders, this is not the first layer to learn, but it is part of the full picture. It includes supervised fine-tuning, LoRA, QLoRA, PEFT, DPO, RLHF, instruction tuning, adapter training, dataset formatting, and model export.

Customize models when prompting, RAG, and tool use are not enough.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [huggingface/transformers](https://github.com/huggingface/transformers) | 161k | 33337 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | 65.2k | 5796 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI) | 41.4k | 4504 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [lm-sys/FastChat](https://github.com/lm-sys/FastChat) | 39.5k | 4788 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/onnxruntime](https://github.com/microsoft/onnxruntime) | 20.7k | 3943 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white) |

## Deployment, local inference, and model serving layer

This layer includes local model runners, inference servers, OpenAI-compatible local APIs, high-throughput serving, GPU inference, batching, quantization, autoscaling, Kubernetes deployment, and model-serving infrastructure.

Run models and AI services reliably in local, cloud, or production environments.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [ollama/ollama](https://github.com/ollama/ollama) | 172.4k | 16308 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) | 113.3k | 18834 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white) |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | 81.2k | 17306 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all) | 77.4k | 8325 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white) |
| [hiyouga/LlamaFactory](https://github.com/hiyouga/LlamaFactory) | 71.7k | 8753 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [mudler/LocalAI](https://github.com/mudler/LocalAI) | 46.5k | 4105 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [ray-project/ray](https://github.com/ray-project/ray) | 42.7k | 7618 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | 42.4k | 4839 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | 28.3k | 6166 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

