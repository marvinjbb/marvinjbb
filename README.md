<h1 align="center">Hi, I'm Marvin Joseph B 👋</h1>

<h3 align="center">AI & Generative AI Engineer | Production SQL Server DBA Background</h3>

<p align="center">
  <b>LLM Applications · Agentic Workflows · AI APIs · Production Reliability</b>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=2F81F7&center=true&vCenter=true&width=760&lines=Building+production-grade+AI+applications;Designing+agentic+workflows+%26+LLM+systems;From+Production+DBA+to+AI+Engineer;Reliable.+Observable.+Controlled." alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://marvinjb.dev"><b>Portfolio</b></a>
  &nbsp;•&nbsp;
  <a href="https://www.linkedin.com/in/marvin-jbb"><b>LinkedIn</b></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/marvinjbb"><b>GitHub</b></a>
</p>

---

## ⚡ Who I Am

I'm a **production SQL Server DBA transitioning into AI and Generative AI engineering**.

My background is in production systems where failures matter: database incidents, performance troubleshooting, high availability, backup and recovery, monitoring, automation, deployments, and operational reliability.

Today I build **LLM applications and agentic AI systems** with Python, FastAPI, structured outputs, tool calling, retrieval, evaluation, Docker, and production-minded engineering practices.

> **I’m not leaving production engineering behind.
> I’m applying it to AI systems.**

---

## 🧰 Engineering Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,bash,docker,linux,git,github,aws,vscode&theme=dark" alt="tech icons"/>
</p>

<p align="center">

![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FASTAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)
![Pydantic](https://img.shields.io/badge/PYDANTIC-E92063?style=for-the-badge\&logo=pydantic\&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_SERVER-CC2927?style=for-the-badge\&logo=microsoftsqlserver\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/POSTGRESQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Docker](https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Linux](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GITHUB_ACTIONS-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)

</p>

<p align="center">

`LLM APIs` · `Structured Outputs` · `Tool Calling` · `AI Agents` · `RAG` · `Embeddings` · `Evaluation` · `MCP` · `REST APIs`

</p>

---

# 🚀 Featured AI Systems

<p align="center">
  These projects represent the direction of my work: <b>AI systems that can retrieve evidence, use tools, make bounded decisions, and operate reliably inside real workflows.</b>
</p>

<table>
<tr>

<td width="33%" valign="top">

### 🚨 Incident Investigation Agent

An AI investigation system inspired by real production incident-response workflows.

The agent gathers evidence from:

* application logs
* database diagnostics
* recent changes
* operational runbooks

It reconstructs an incident, evaluates evidence, identifies likely causes, and recommends next actions.

**Key engineering ideas**

`Agent orchestration`
`Tool calling`
`Evidence gathering`
`Human approval`
`Safety boundaries`
`Auditability`

<br>

<a href="YOUR-INCIDENT-REPO-URL">
<b>View Repository →</b>
</a>

</td>

<td width="33%" valign="top">

### 🔎 Research Agent

A multi-step research system designed to investigate a question rather than simply ask one model for an answer.

A planner breaks the problem into subproblems, specialized workers gather evidence, and the system synthesizes the findings into a grounded report.

**Key engineering ideas**

`Planning`
`Worker agents`
`Source grounding`
`Citations`
`Conflict detection`
`Uncertainty handling`

<br>

<a href="YOUR-RESEARCH-REPO-URL">
<b>View Repository →</b>
</a>

</td>

<td width="33%" valign="top">

### 📄 Extraction Agent

A document intelligence API that converts uploaded invoices into validated structured data.

The pipeline validates files, extracts document content, requests schema-constrained output from an LLM, validates the result with Pydantic, and returns predictable JSON.

**Key engineering ideas**

`Structured outputs`
`Pydantic validation`
`File validation`
`FastAPI`
`Testing`
`Failure handling`

<br>

<a href="https://github.com/marvinjbb/extraction-agent">
<b>View Repository →</b>
</a>

</td>

</tr>
</table>

---

## 🧠 What Connects These Projects

The projects look different, but they are teaching me the same deeper engineering problem:

```text
                    ┌──────────────────┐
                    │   User / System  │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │     FastAPI      │
                    │    API Layer     │
                    └────────┬─────────┘
                             │
                             ▼
                 ┌──────────────────────┐
                 │ AI Workflow / Agent  │
                 └──────────┬───────────┘
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
          ┌──────┐     ┌──────────┐    ┌─────────┐
          │ LLM  │     │Retrieval │    │  Tools  │
          └──┬───┘     └────┬─────┘    └────┬────┘
             │              │               │
             └──────────────┼───────────────┘
                            │
                            ▼
                  ┌───────────────────┐
                  │ Validation / Eval │
                  └─────────┬─────────┘
                            │
                            ▼
                  ┌───────────────────┐
                  │ Human / Policy    │
                  │ Approval Boundary │
                  └─────────┬─────────┘
                            │
                            ▼
                  ┌───────────────────┐
                  │   Final Result    │
                  └───────────────────┘
```

<p align="center">
<b>The model is only one component.<br>
The engineering is in the system around it.</b>
</p>

---

## 🗄️ Production Engineering Background

Before AI engineering, I spent years supporting **Microsoft SQL Server in production environments**.

That experience shaped how I think about software.

<table>

<tr>

<td width="50%" valign="top">

### Production DBA

`Incident response`

`Performance troubleshooting`

`Blocking & query analysis`

`High availability`

`Backup & recovery`

`Monitoring`

`Automation`

`Deployment support`

`Operational reliability`

</td>

<td width="50%" valign="top">

### AI Engineering

`Agent observability`

`Failure handling`

`Evidence gathering`

`Safe tool execution`

`Human approval`

`Evaluation`

`API reliability`

`Production deployment`

`System design`

</td>

</tr>

</table>

---

## 🔍 Questions I Care About

```text
What happens when the model is wrong?

What happens when a tool fails?

Can we trace where the answer came from?

Can the output be validated?

What actions should require human approval?

How do we measure whether retrieval actually works?

Can we reproduce a failure?

Can another engineer understand and operate the system?
```

That is where AI engineering becomes more interesting than simply calling a model API.

---

## 🎯 Current Focus

<table>

<tr>

<td width="50%">

```text
01  Agentic workflows
02  Tool / function calling
03  Structured outputs
04  RAG & retrieval
05  LLM evaluation
```

</td>

<td width="50%">

```text
06  MCP
07  AI system design
08  AI security
09  Observability
10  Production deployment
```

</td>

</tr>

</table>

---

## 🧭 My Engineering Journey

```text
Production SQL Server DBA
            │
            ▼
Production Systems & Reliability
            │
            ▼
Python + APIs + Backend Engineering
            │
            ▼
LLM Applications
            │
            ▼
Agentic AI Systems
            │
            ▼
AI / Generative AI Engineering
```

---

## 🎓 Credentials & Learning

### Claude Certified Associate — Foundations

Currently deepening my understanding of:

`LLM architecture` · `context windows` · `tokenization` · `embeddings` · `RAG` · `tool calling` · `agents` · `MCP` · `evaluation` · `AI security` · `system design`

---

## 🌐 Explore

<table>

<tr>

<td width="33%" align="center">

### 🌍 Portfolio

Live demos, architecture, project stories, and technical writing.

**[marvinjb.dev →](https://marvinjb.dev)**

</td>

<td width="33%" align="center">

### 💻 Projects

Production-minded AI systems and engineering experiments.

**[GitHub →](https://github.com/marvinjbb)**

</td>

<td width="33%" align="center">

### 💼 LinkedIn

My transition from production database engineering into AI.

**[Connect →](https://www.linkedin.com/in/marvin-jbb)**

</td>

</tr>

</table>

---

<p align="center">
  <b>Building AI systems with a production engineer's mindset.</b>
</p>

<p align="center">
  Python · FastAPI · LLMs · Agents · RAG · APIs · Docker · Production Systems
</p>
