# Sai Teja Kusireddy

Backend / AI Infrastructure Engineer focused on distributed systems, reliability, observability, and LLM infrastructure.

M.S. Computer Science student at Pace University. Previously Software Engineer at Tata Consultancy Services. Currently building production-grade AI agent infrastructure at GetOnStack.

[Portfolio](YOUR_PORTFOLIO_LINK) · [LinkedIn](https://www.linkedin.com/in/sai-teja-kusireddy/) · [Medium](https://medium.com/@tejakusireddy) · [Email](mailto:saiteja.kusireddy@gmail.com)

---

## Open Source Contributions

Contributed 6 test-backed fixes across AWS CDK and Microsoft AI/cloud OSS, including Semantic Kernel, Agent Framework, ai4s-jobq, and Multicloud DB SDK.

| Area | Contribution Focus |
|---|---|
| AWS CDK | CloudFormation token handling |
| Semantic Kernel | Agent orchestration reliability |
| Agent Framework | YAML / parser correctness |
| ai4s-jobq | Distributed queue workflow reliability |
| Multicloud DB SDK | Parser safety limits and cloud database error semantics |

Focus areas: cloud infrastructure, AI agent orchestration, distributed workflows, parser correctness, and production reliability.

---

## Featured Engineering Work

### [ForgeAI](https://github.com/tejakusireddy/forgeai) — AI Inference Gateway

OpenAI-compatible inference gateway for model routing, retrieval-augmented generation, and AI cost optimization.

**Tech:** Python, FastAPI, gRPC, vLLM, Qdrant, Redis, PostgreSQL, Kubernetes

**Highlights**
- Built contextual-bandit routing for model selection
- Added RAG support with vector retrieval
- Added semantic caching and request optimization
- Achieved 72.9% lower inference cost at 94ms p50 latency on NVIDIA H100

---

### [FalconQ](https://github.com/tejakusireddy/FalconQ-distributed-message-queue) — Distributed Messaging Queue

Distributed messaging queue built in Go with partitioned topics, consistent hashing, replication, and observability.

**Tech:** Go, AWS EKS, Raft, Terraform, Prometheus, Grafana

**Highlights**
- Handles hot-key skew using partitioned topics and consistent hashing
- Preserves write correctness during load balancing and failover
- Validated at 1.5M messages/min with p99 latency under 12ms
- Includes observability for broker and queue behavior

---

### [Copilot Plugin API](https://github.com/tejakusireddy/copilot-plugin-api) — Copilot-Style LLM API Platform

C#/.NET API platform for LLM workflows with streaming, memory, plugin execution, and production-style request handling.

**Tech:** C#, .NET 8, Azure OpenAI, Redis, SQL, SSE, xUnit

**Highlights**
- Built SSE streaming for real-time LLM responses
- Added Redis-backed memory for workflow state
- Built plugin execution support for tool-based workflows
- Added rate limits, idempotency, semantic caching, and xUnit test coverage

---

### [OpenGPU Lab](https://github.com/tejakusireddy/gpu-systems-compiler-runtime-rtl) — CPU/CUDA/RTL GPU Execution Stack

End-to-end GPU systems lab with CPU, CUDA, and RTL backends, plus a GPU optimization CLI for roofline-guided kernel analysis.

**Tech:** C++, CUDA, Verilog, SystemVerilog, Verilator, Icarus Verilog, CMake, Python

**Highlights**
- Built a unified C++ runtime across CPU, CUDA, and RTL backends
- Achieved 0.0 max-error parity across backend outputs
- Built `gpuopt`, a CLI for roofline modeling and memory-access analysis
- Improved arithmetic intensity from 10.67 to 16.00 FLOPS/byte by adjusting tiling from 48 to 64 and adding shared-memory staging
- Validated RTL behavior with clock/reset-safe simulation

---

### [Structured Extraction Pipeline](https://github.com/tejakusireddy/structured-extraction-pipeline) — Legal Document Intelligence

Vector retrieval and structured extraction pipeline for semantic search across large legal document collections.

**Tech:** Python, FastAPI, PostgreSQL, Qdrant, OpenAI, Terraform, GCP

**Highlights**
- Built semantic search over 10M+ legal documents
- Added FastAPI service layer for retrieval and extraction
- Added strict typing and CI/CD ingestion gates
- Designed a retrieval-first architecture for reliable document intelligence

---

### [Trade Settlement Commentary Engine](https://github.com/tejakusireddy/trade-settlement-commentary-engine) — Event-Driven Settlement Analysis

Event-driven trade settlement system with idempotent consumers, DLQ retries, and AI-assisted commentary generation.

**Tech:** Java 21, Spring Boot, Kafka, PostgreSQL, Redis, Claude API

**Highlights**
- Built Kafka-based settlement processing workflow
- Added idempotent consumers for repeat-safe event handling
- Added DLQ retries for failure isolation and recovery
- Reduced analysis time from ~20 min to under 10 sec

---

## Experience Snapshot

**Founding Engineer — GetOnStack**  
Building AI agent infrastructure focused on observability, cost control, loop detection, and production reliability.

**Software Engineer — Tata Consultancy Services**  
Built backend services, cloud automation, observability systems, RAG workflows, and reliability tooling across production environments.

**M.S. Computer Science — Pace University**  
Coursework: Distributed Systems, Cloud Infrastructure, Operating Systems, Machine Learning, Systems Security, Algorithms.

**Certification**  
AWS Certified Solutions Architect – Associate

---

## Technical Writing

Selected technical writing on AI infrastructure, agent reliability, and production LLM systems.

- “We Spent $47,000 Running AI Agents in Production” — 92K+ views
- Essays on AI runtime reliability, agent observability, LLM infrastructure, and production failure modes

[Read on Medium](https://medium.com/@tejakusireddy)

---

## Tech Stack

**Languages:** Java, Python, Go, TypeScript, C#, C++, SQL, Bash  
**Backend:** REST, gRPC, Kafka, Redis, Spring Boot, FastAPI, .NET, PostgreSQL  
**Cloud / Infra:** AWS, Azure, GCP, Kubernetes, Docker, Terraform, Helm, GitHub Actions  
**Observability:** Prometheus, OpenTelemetry, Grafana, Splunk  
**AI / LLM:** Azure OpenAI, LangChain, vLLM, Qdrant, RAG, semantic caching  
**Testing:** JUnit, PyTest, xUnit, Postman  

---

## Contact

- LinkedIn: [linkedin.com/in/sai-teja-kusireddy](https://www.linkedin.com/in/sai-teja-kusireddy/)
- GitHub: [github.com/tejakusireddy](https://github.com/tejakusireddy)
- Medium: [medium.com/@tejakusireddy](https://medium.com/@tejakusireddy)
- Email: [saiteja.kusireddy@gmail.com](mailto:saiteja.kusireddy@gmail.com)
