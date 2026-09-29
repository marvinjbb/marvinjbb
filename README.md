<h1 align="center">Hi, I'm Marvin Joseph B 👋</h1>

<h3 align="center">Production SQL Server DBA building applied AI systems</h3>

<p align="center">
  <b>Python · FastAPI · LLM Applications · Bounded Agent Workflows · Production Reliability</b>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&pause=1100&color=2F81F7&center=true&vCenter=true&width=720&lines=Building+deployed+AI+applications;Designing+bounded+agent+workflows;Production+DBA+%E2%86%92+Applied+AI+Engineering;Evidence.+Validation.+Reliability." alt="Typing animation: building deployed AI applications, designing bounded agent workflows, and applying production engineering to AI" />
</p>

<p align="center">
  <a href="https://marvinjb.dev"><b>Portfolio</b></a>
  &nbsp;•&nbsp;
  <a href="https://www.linkedin.com/in/marvin-jbb"><b>LinkedIn</b></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/marvinjbb"><b>GitHub</b></a>
</p>

---

## Who I Am

I'm a **production SQL Server DBA transitioning into applied AI engineering**. My background includes incident response, performance troubleshooting, blocking and query analysis, HA/DR operations, backup and recovery, monitoring, automation, deployment support, and keeping production systems reliable.

I now apply that operating mindset to backend and AI systems built with Python, FastAPI, Pydantic, LLM APIs, structured outputs, tool calling, evaluation, Docker, PostgreSQL, REST APIs, and real production deployment.

> **I'm not leaving production engineering behind. I'm applying it to AI systems.**

---

## Featured AI Systems

### Incident Investigation Agent

A production-deployed controlled incident-response lab that investigates application and PostgreSQL failures through restricted diagnostics. It produces evidence-backed findings and requires human approval before any allowlisted remediation can run.

**Why it is technically interesting**

- Bounded model-selected diagnostic tools with no arbitrary SQL, shell, filesystem, PID, or deployment-version access
- Application-owned evidence IDs and strict citation/runbook validation
- Human approval, application-owned remediation policy, and TOCTOU revalidation
- Scenario-specific recovery verification and an auditable action lifecycle

**Built with:** Python · FastAPI · Pydantic · PostgreSQL · OpenAI Responses API · Docker · Nginx

**[Try Live Demo →](https://marvinjb.dev/demo/incident-investigation)** · **[View Repository →](https://github.com/marvinjbb/incident-investigation-agent)**

---

### Research Agent

A production-deployed bounded research system that decomposes one question into **2–5 focused assignments**, searches sources in parallel, preserves application-owned evidence, validates grounding relationships, and synthesizes a cited report.

**Why it is technically interesting**

- Planner-selected assignments and concurrent in-process workers
- Bounded Tavily search with stable source and evidence IDs
- Deterministic aggregation, explicit partial-worker failure, and provenance preservation
- Bounded synthesis that selects known claim, evidence, and uncertainty IDs

**Built with:** Python · FastAPI · Pydantic · asyncio · Tavily Search · OpenAI Responses API · Docker · Nginx

**[Try Live Demo →](https://marvinjb.dev/demo/research)** · **[View Repository →](https://github.com/marvinjbb/research-agent)**

---

### Extraction Agent

A production-deployed document extraction service that converts invoice PDFs and images into validated structured data, then supports stateless questions over the extracted invoice.

**Why it is technically interesting**

- PDF, JPEG, and PNG validation with a text-first PDF path and bounded vision fallback
- pypdf, PyMuPDF, and Pillow document processing
- OpenAI Structured Outputs through a provider DTO with deterministic `Decimal` conversion
- Application-owned Pydantic `Invoice` contract and bounded invoice Q&A

**Built with:** Python · FastAPI · Pydantic · OpenAI Structured Outputs · pypdf · PyMuPDF · Pillow · Docker

**[Try Live Demo →](https://marvinjb.dev/demo/extraction)** · **[View Repository →](https://github.com/marvinjbb/extraction-agent)**

---

## Engineering Stack

| Area | Demonstrated technologies and practices |
| --- | --- |
| **Core engineering** | Python, FastAPI, Pydantic, SQL Server, PostgreSQL, Docker, Linux, Git, GitHub, GitHub Actions |
| **AI applications** | OpenAI Responses API, Structured Outputs, Tool Calling, Agent Workflows, Evaluation, Evidence Grounding, Tavily Search, REST APIs |
| **Production & infrastructure** | Nginx, Docker Compose, Ubuntu VPS, HTTPS, CI/CD, Observability, Production Debugging |
| **Frontend** | React, TypeScript |

---

## What Connects These Systems

> **The model is only one component. The engineering is in the system around it.**

```text
User / System
      |
      v
API Boundary
      |
      v
Application Workflow
      |
   +--+-------------+
   |                |
   v                v
Model          Tools / Data
   |                |
   +-------+--------+
           |
           v
Validation / Policy
           |
           v
Human / Application Control
           |
           v
Final Result / Action
```

Across all three projects, application code owns the boundaries: inputs, tools, IDs, validation, policy, failure handling, and what the model is allowed to influence.

---

## Production Engineering Background

| Production database engineering | Applied AI engineering |
| --- | --- |
| Incident response and reproducible diagnosis | Bounded tool calling and explicit failure handling |
| Performance, blocking, and query analysis | Evidence grounding and traceable outputs |
| HA/DR operations, backup, and recovery | Human approval and recovery verification |
| Monitoring, automation, and deployment support | Evaluation, observability, and API reliability |
| Operational reliability | Production deployment and system design |

The common thread is disciplined engineering around failure: observe what happened, constrain what can act, validate results, and leave enough evidence for another engineer to understand the system.

---

## Engineering Questions I Care About

- What happens when the model is wrong or a tool fails?
- Can we trace where an answer came from and validate its output?
- Which actions require human approval?
- How should AI quality be evaluated?
- Can we reproduce a failure and verify recovery?
- Can another engineer understand and operate the system?

---

## Demonstrated vs. Currently Deepening

**Demonstrated in public projects**

Python · FastAPI · Pydantic · Structured Outputs · Tool Calling · Bounded Agent Workflows · Evidence Grounding · LLM Evaluation · PostgreSQL · Docker · Nginx · Production Deployment

**Currently deepening**

RAG and retrieval design · Embeddings · Model Context Protocol (MCP) · AI application security · Advanced observability and tracing · Larger-scale backend and system design

RAG, embeddings, vector search, and MCP are learning areas—not features of the three systems above.

---

## Credential

**Claude Certified Associate — Foundations**

---

## Career Journey

```text
Production SQL Server DBA
        ↓
Production Systems & Reliability
        ↓
Python / Backend / Automation
        ↓
LLM Applications
        ↓
Bounded Agent Workflows
        ↓
Applied AI Engineering
```

---

## Connect

**[Portfolio](https://marvinjb.dev)** · **[GitHub](https://github.com/marvinjbb)** · **[LinkedIn](https://www.linkedin.com/in/marvin-jbb)**

<p align="center">
  <b>Building AI systems with a production engineer's mindset.</b>
</p>
