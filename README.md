# Awesome AI Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Built by Groovy Web](https://img.shields.io/badge/Built%20by-Groovy%20Web-0f3460?logo=github&logoColor=white)](https://www.groovyweb.co/?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-agents)

> A curated list of AI agent frameworks, tools, platforms, and resources for building autonomous and semi-autonomous AI systems.

AI agents are systems that use LLMs to reason, plan, and take actions autonomously. This list covers everything from frameworks to production deployment tools.

**Contributions welcome!** Read the [contribution guidelines](CONTRIBUTING.md) first.

## Contents

- [Frameworks](#frameworks)
- [Orchestration](#orchestration)
- [Agent Platforms](#agent-platforms)
- [Tool Use & Function Calling](#tool-use--function-calling)
- [Memory & State](#memory--state)
- [RAG (Retrieval-Augmented Generation)](#rag-retrieval-augmented-generation)
- [Testing & Evaluation](#testing--evaluation)
- [Monitoring & Observability](#monitoring--observability)
- [Deployment](#deployment)
- [Research Papers](#research-papers)
- [Tutorials & Courses](#tutorials--courses)
- [Community](#community)

## Frameworks

Multi-agent and single-agent frameworks for building AI systems.

### Multi-Agent

- [LangGraph](https://github.com/langchain-ai/langgraph) - Build stateful, multi-actor applications with LLMs. By LangChain.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing AI agents.
- [AutoGen](https://github.com/microsoft/autogen) - Multi-agent conversation framework by Microsoft.
- [Swarm](https://github.com/openai/swarm) - Lightweight multi-agent orchestration by OpenAI.
- [Camel](https://github.com/camel-ai/camel) - Communicative agents for large-scale exploration.
- [MetaGPT](https://github.com/geekan/MetaGPT) - Multi-agent framework that mimics a software company.
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) - Agent orchestration framework with customizable agent roles.
- [Magentic-One](https://github.com/microsoft/autogen/tree/main/python/packages/autogen-magentic-one) - Generalist multi-agent system by Microsoft Research.

### Single-Agent

- [LangChain](https://github.com/langchain-ai/langchain) - Framework for developing LLM-powered applications.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for LLM applications with RAG.
- [Haystack](https://github.com/deepset-ai/haystack) - End-to-end NLP framework for building LLM applications.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - SDK for integrating LLMs into applications. By Microsoft.
- [Instructor](https://github.com/jxnl/instructor) - Structured outputs from LLMs with validation.
- [Marvin](https://github.com/PrefectHQ/marvin) - AI engineering toolkit for building reliable AI interfaces.

### Agent SDKs

- [Claude Agent SDK](https://github.com/anthropics/anthropic-sdk-python) - Build agents with Claude by Anthropic.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - Lightweight Python framework for agent workflows.
- [Google ADK](https://github.com/google/adk-python) - Agent Development Kit by Google.
- [Vercel AI SDK](https://github.com/vercel/ai) - Build AI-powered apps with React, Next.js, and more.

## Orchestration

Tools for managing agent workflows and pipelines.

- [Temporal](https://github.com/temporalio/temporal) - Durable execution for microservices and agents.
- [Prefect](https://github.com/PrefectHQ/prefect) - Workflow orchestration for data and ML pipelines.
- [Airflow](https://github.com/apache/airflow) - Platform for programmatically authoring and scheduling workflows.
- [Dagster](https://github.com/dagster-io/dagster) - Data orchestration platform with built-in asset management.
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation with AI capabilities.
- [Windmill](https://github.com/windmill-labs/windmill) - Developer platform for building internal tools and workflows.

## Agent Platforms

Hosted platforms for building, deploying, and managing AI agents.

- [OpenAI Assistants API](https://platform.openai.com/docs/assistants/overview) - Build AI assistants with tools, knowledge, and actions.
- [Claude MCP](https://modelcontextprotocol.io/) - Model Context Protocol for connecting AI to tools and data.
- [Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder) - Build conversational AI agents on Google Cloud.
- [Amazon Bedrock Agents](https://aws.amazon.com/bedrock/agents/) - Build and deploy AI agents on AWS.
- [Relevance AI](https://relevanceai.com/) - Platform for building AI agents and workflows.
- [Voiceflow](https://www.voiceflow.com/) - Build and deploy conversational AI agents.
- [Botpress](https://github.com/botpress/botpress) - Open-source platform for building AI agents and chatbots.

## Tool Use & Function Calling

Libraries for giving agents the ability to use tools and APIs.

- [Agent Payment Node](https://github.com/nuanu-ai/agent-payment-node) - Local CLI and stdio MCP payment tools with owner-set limits and command-specific foreground approval for AI-agent workflows on macOS Apple Silicon.
- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) - Open standard for connecting LLMs to tools and data.
- [Composio](https://github.com/ComposioHQ/composio) - Integration platform for AI agents with 150+ tools.
- [Toolhouse](https://toolhouse.ai/) - Tool infrastructure for LLM applications.
- [Arcade AI](https://github.com/ArcadeAI/arcade-ai) - Tool use infrastructure with auth and execution.
- [LangChain Tools](https://python.langchain.com/docs/integrations/tools/) - Extensive tool integrations for LangChain agents.

## Memory & State

Solutions for agent memory, context, and state management.

- [Mem0](https://github.com/mem0ai/mem0) - Memory layer for AI agents and assistants.
- [Zep](https://github.com/getzep/zep) - Long-term memory for AI assistants and agents.
- [Letta (MemGPT)](https://github.com/letta-ai/letta) - Agents with long-term memory and self-editing capabilities.
- [Chromem-go](https://github.com/philippgille/chromem-go) - Embeddable vector database for Go.
- [MotherDuck](https://motherduck.com/) - Serverless analytics for agent state management.

## RAG (Retrieval-Augmented Generation)

Tools and frameworks for building RAG systems that power agent knowledge.

- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for building RAG applications.
- [Unstructured](https://github.com/Unstructured-IO/unstructured) - Document parsing for RAG pipelines.
- [LangChain RAG](https://python.langchain.com/docs/tutorials/rag/) - RAG tutorials and implementations.
- [RAGFlow](https://github.com/infiniflow/ragflow) - Open-source RAG engine with deep document understanding.
- [Cognita](https://github.com/truefoundry/cognita) - Open-source RAG framework for production.
- [R2R](https://github.com/SciPhi-AI/R2R) - Production-ready RAG system.
- **[rag-system-pgvector](https://github.com/groovy-web/rag-system-pgvector)** - Production RAG with PostgreSQL + pgvector. By Groovy Web.
- **[rag-systems-production](https://github.com/groovy-web/rag-systems-production)** - Enterprise-grade RAG systems. By Groovy Web.

### Vector Databases

- [pgvector](https://github.com/pgvector/pgvector) - Open-source vector similarity search for PostgreSQL.
- [Pinecone](https://www.pinecone.io/) - Managed vector database for AI applications.
- [Weaviate](https://github.com/weaviate/weaviate) - Open-source vector database with hybrid search.
- [ChromaDB](https://github.com/chroma-core/chroma) - Open-source embedding database.
- [Qdrant](https://github.com/qdrant/qdrant) - High-performance vector search engine.
- [Milvus](https://github.com/milvus-io/milvus) - Open-source vector database for scalable similarity search.

## Testing & Evaluation

Tools for testing, evaluating, and benchmarking AI agents.

- [DeepEval](https://github.com/confident-ai/deepeval) - LLM evaluation framework for RAG and agents.
- [RAGAS](https://github.com/explodinggradients/ragas) - Evaluation framework for RAG pipelines.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - Test and evaluate LLM outputs.
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) - Framework for evaluating LLMs by UK AISI.
- [Giskard](https://github.com/Giskard-AI/giskard) - Testing framework for ML models and LLMs.
- **[ai-testing-mcp](https://github.com/groovy-web/ai-testing-mcp)** - MCP server for AI testing and QA. By Groovy Web.

## Monitoring & Observability

Track agent performance, costs, and behavior in production.

- [LangSmith](https://smith.langchain.com/) - Debugging, testing, and monitoring for LLM applications.
- [LangFuse](https://github.com/langfuse/langfuse) - Open-source LLM engineering platform.
- [Helicone](https://github.com/Helicone/helicone) - Open-source LLM observability platform.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - ML observability for LLMs, agents, and RAG.
- [Weights & Biases](https://wandb.ai/) - ML experiment tracking with LLM support.
- [Braintrust](https://www.braintrust.dev/) - Evaluation, logging, and prompt management.

## Deployment

Tools for deploying AI agents to production.

- [Modal](https://modal.com/) - Serverless cloud for AI and ML workloads.
- [Replicate](https://replicate.com/) - Run and deploy ML models with an API.
- [BentoML](https://github.com/bentoml/BentoML) - Build and deploy ML services.
- [Ray Serve](https://docs.ray.io/en/latest/serve/) - Scalable model serving on Ray.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput LLM serving engine.
- [Ollama](https://github.com/ollama/ollama) - Run LLMs locally.

## Research Papers

Key papers on AI agents and multi-agent systems.

- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) - Foundation paper for tool-using agents.
- [Toolformer](https://arxiv.org/abs/2302.04761) - LMs that teach themselves to use tools.
- [Generative Agents](https://arxiv.org/abs/2304.03442) - Simulacra of human behavior using LLMs.
- [Chain-of-Thought Prompting](https://arxiv.org/abs/2201.11903) - Eliciting reasoning in LLMs.
- [Tree of Thoughts](https://arxiv.org/abs/2305.10601) - Deliberate problem-solving with LLMs.
- [Reflexion](https://arxiv.org/abs/2303.11366) - Language agents with verbal reinforcement learning.
- [LATS](https://arxiv.org/abs/2310.04406) - Language Agent Tree Search for reasoning and planning.

## Tutorials & Courses

- [LangChain Academy](https://academy.langchain.com/) - Free courses on building with LangChain and LangGraph.
- [DeepLearning.AI - Building Agentic RAG](https://www.deeplearning.ai/short-courses/) - Short courses on agent patterns.
- **[langchain-multi-agent-example](https://github.com/groovy-web/langchain-multi-agent-example)** - Complete multi-agent tutorial. By Groovy Web.
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) - Code samples for the Anthropic API.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Examples and guides for using the OpenAI API.

## Community

- [LangChain Discord](https://discord.gg/langchain) - LangChain community chat.
- [r/LangChain](https://www.reddit.com/r/LangChain/) - LangChain subreddit.
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) - Local LLM community.
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning/) - ML research community.
- [Hugging Face Forums](https://discuss.huggingface.co/) - ML community discussions.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. If you find this list useful, give it a star.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

Curated with care by **[Groovy Web](https://www.groovyweb.co/?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-agents)** -- AI-First Engineering Agency
