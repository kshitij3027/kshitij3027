## What I'm building

Software engineer focused on AI infrastructure and developer tools. MS in Computer Software Engineering from Carnegie Mellon (Dec 2025), two years prior at Siemens Digital Industries Software. Mostly Python + FastAPI, deployed on AWS.

**Portfolio →** [v0-simple-spa-deployment.vercel.app](https://v0-simple-spa-deployment.vercel.app)

## Current focus

- LLM serving infrastructure — caching, routing, rate limiting
- Retrieval systems — hybrid search, reranking, agentic tool use
- Developer tooling for AI workflows

## Projects

### [inference-gateway](https://github.com/kshitij3027/inference-gateway)
Multi-instance LLM reverse proxy. Two-tier semantic caching (L1 LRU + L2 Redis embeddings, 15–73% hit rate), consistent-hash routing, circuit breakers, atomic rate limiting, request coalescing. Deployed on AWS via Terraform (ECS, ElastiCache, ALB) with OpenTelemetry tracing.

### [agentic-chat-and-document-ingestion](https://github.com/kshitij3027/agentic-chat-and-document-ingestion)
Full-stack RAG pipeline, no LangChain. Hybrid retrieval (pgvector + Postgres FTS + Cohere reranking via Reciprocal Rank Fusion), structural-aware chunking across 6 document formats, agentic tool calling, SSE streaming.

### [codagent](https://github.com/kshitij3027/codagent)
CLI coding agent built with Pydantic AI, Rich, and prompt-toolkit. Token-by-token streaming, runtime model switching across 3 providers, slash commands with tab completion, persistent history, 3-tier safety model.

### [backend-labs](https://github.com/kshitij3027/backend-labs)
Distributed systems learning lab — 40+ projects working through caches, message queues, write-ahead logging, circuit breakers, P99 latency tracking, and related primitives.

## Stack

**Languages:** Python, TypeScript, SQL
**Backend:** FastAPI, Pydantic, Pydantic AI
**AI/ML:** OpenAI, Cohere, pgvector, sentence-transformers
**Infra:** Docker, Redis, PostgreSQL, Terraform (AWS ECS / ElastiCache / ALB), Prometheus, Grafana, OpenTelemetry

## Reach me

- LinkedIn — [kshitijkakade307](https://www.linkedin.com/in/kshitijkakade307)
- Email — kshitijskakade307@gmail.com
- Mountain View, CA
