<div align="center">

# Arup Kumar Sarkar

### AI Platform & Solution Architect

**Intelligence to Adoption**

I help engineering teams adopt AI effectively. At GlobalLogic, I build custom
Claude/Codex development environments, AI-DLC utilities, context, skills, plugins
and tools that connect AI agents to customer problems and delivery workflows.

**Enterprise AI adoption · AI-native software engineering · Context engineering · Security, guardrails & evals**

**20 years in software · 10 years in architecture**

[LinkedIn](https://www.linkedin.com/in/arupmmi/) · [Email](mailto:arupus07@gmail.com) · [Skynet Harness](https://github.com/i-skynetai/skynet-harness) · [Skygraph](https://github.com/i-skynetai/skygraph)

</div>

---

## Enterprise AI adoption and developer enablement

I am a Solution Architect at GlobalLogic in Richardson, Texas. My current focus is
the engineering environment around AI: how teams give an agent the right context,
connect it to tools and workflows, control its actions and check its work.

I build AI-DLC utilities on our context engine with Claude as an agent, and skills,
plugins and tools for Claude/Codex. These custom development environments help
organisational and client teams use AI in their own systems to solve customer
problems. Faster software delivery and effective AI adoption are the purpose.

My context platforms connect enterprise knowledge and code through graph, keyword
and vector retrieval and repository structure over MCP. An AI-SDLC platform I built
is used by three enterprise clients of a European enterprise ITSM SaaS vendor.

Security, guardrails and evaluations are part of the solution. My agent tooling
includes identity, default-deny policies, tool-call audit records and human approval
of outward actions. Testing and review check generated code and agent outputs;
cost tracking and tracing help diagnose runs and failures.

## Full-stack engineering foundation

This work rests on 20 years in software, including ten in architecture. I remain
hands-on with Python/FastAPI, React/TypeScript, microservices and distributed systems.
Within a multi-tenant SaaS platform, my architecture and implementation contributions
cover the application shell, selected micro-frontends, shared libraries and AI work
within the wider platform design.

My agentic ITSM work connects shared context to ticket, incident and problem analysis,
impacted-service discovery and business-impact reasoning. This is distinct from the
AI-DLC work supporting engineering teams.

## What I work on

| Area | Engineering focus |
|---|---|
| **Enterprise AI enablement** | Custom Claude/Codex development environments, developer enablement and customer workflow integration |
| **AI-enabled software engineering** | AI-DLC utilities, agent skills and plugins, tool integration, context over MCP, testing and review |
| **Solution architecture** | Requirements analysis, solution design, architecture decisions, service boundaries, API contracts and enterprise integration |
| **Full-stack platforms** | Multi-tenant SaaS, Python/FastAPI microservices, React/TypeScript micro-frontends, Module Federation and shared libraries |
| **Delivery** | CI/CD, containerisation, observability, design reviews and technical guidance across distributed teams |
| **AI & retrieval** | RAG, knowledge graphs, hybrid graph/keyword/vector search, grounded agent workflows and context engineering |
| **Agentic business applications** | Shared context for ticket, incident and problem analysis, impacted-service discovery and business-impact reporting |
| **AI security** | Agent identity, role policies, tool-call audit trails, human approval, tenant isolation and access control |
| **Evaluation & operations** | LLM evaluation, output verification, cost tracking, timings, tracing and failure diagnosis |
| **Code intelligence** | Syntax trees, symbols, call graphs and incremental repository context |

## How I work

- **Start with the requirement.** Connect the business need to a design teams can build, operate and extend.
- **Make decisions explicit.** Define contracts, constraints and architecture decisions so teams can work independently.
- **Give AI useful context.** Supply the relevant files, decisions and constraints, then verify the result through tests and review.

## Intelligence to Adoption — projects you can inspect

These personal open-source projects demonstrate parts of the engineering environment
that makes AI useful: context, controlled tools, workflow coordination and evaluation.
They complement my enterprise experience; they are separate from employer and client systems.

| Adoption challenge | Project | What to inspect |
|---|---|---|
| Give coding agents useful repository context | [Skygraph](https://github.com/i-skynetai/skygraph) | Incremental code maps, read-only MCP tools and explicit unresolved relationships |
| Control what an agent may do | [Skynet Harness](https://github.com/i-skynetai/skynet-harness) | Default-deny roles, SDLC skills, readiness checks, audit records and human checkpoints |
| Connect requests to context and specialist tools | [Ethan](https://github.com/i-skynetai/ethan) | Knowledge-base routing, policy-governed launch, privacy checks and close-out records |
| Build an agent application with shared infrastructure | [Skynet+](https://github.com/i-skynetai/sky-plus) | Provider configuration, runtime, memory, guardrails, evaluation and tracing |
| Check when a smaller model can take over | [Praxis](https://github.com/i-skynetai/praxis) | Typed capabilities, traces, calibration, readiness gates and fallback |

### [Skygraph — context engineering for coding agents](https://github.com/i-skynetai/skygraph)

**Problem:** an agent spends each session rediscovering repository structure.

**Implemented:** an incremental index of files, symbols, calls and imports, exposed
through read-only MCP tools. Agents can query dependencies and change impact; unresolved
relationships are marked rather than guessed.

**Adoption value:** reusable repository context for Claude Code and Codex, with a
one-command setup and a sample-project demo.

**Evidence and limits:** the public repository includes a benchmark with hand-checked
answers. Call resolution remains partial; the agent still needs to inspect source where
the index cannot resolve a relationship.

[Try the demo](https://github.com/i-skynetai/skygraph#see-it-work-in-sixty-seconds) ·
[Architecture](https://github.com/i-skynetai/skygraph/blob/main/docs/architecture.md) ·
[Limits and roadmap](https://github.com/i-skynetai/skygraph/blob/main/ROADMAP.md)

### [Skynet Harness — governed AI development workflows](https://github.com/i-skynetai/skynet-harness)

**Problem:** agent settings drift, tool access is unclear, and outward actions need
human control.

**Implemented:** one written policy, agent roles, default-deny actions, knowledge-base
connections, SDLC skills, readiness checks and local audit records. Outward actions are
prepared for a person to execute.

**Adoption value:** explicit operating rules around the coding tools a team already uses.

**Evidence and limits:** the policy demo works without a model account. Claude Code
supports every managed role; Codex supports the reviewer role; Kimi currently supports
no managed role. A full run needs a supplied knowledge base. The harness is not a
security sandbox.

[Try the policy demo](https://github.com/i-skynetai/skynet-harness#see-it-work-in-sixty-seconds) ·
[Architecture](https://github.com/i-skynetai/skynet-harness/blob/main/docs/architecture.md) ·
[Policy](https://github.com/i-skynetai/skynet-harness/blob/main/docs/policy.md)

### [Ethan — context and workflow coordination](https://github.com/i-skynetai/ethan)

**Problem:** the operator repeatedly selects a knowledge base, picks an agent, writes
the brief and decides what to retain.

**Implemented:** hint-first knowledge-base routing, cited context, launch through the
harness, privacy checks on retained knowledge and a task ledger. Entry points include
a local console, CLI and Telegram.

**Adoption value:** connects a request to the appropriate context and specialist tool
while keeping the person responsible for decisions.

**Evidence and limits:** the published demo exercises routing, policy checks and
close-out with a stand-in agent. Real-agent end-to-end validation, status and inbox
workflows remain incomplete.

[Try the demo](https://github.com/i-skynetai/ethan#see-it-work-in-sixty-seconds) ·
[Architecture](https://github.com/i-skynetai/ethan/blob/main/docs/architecture.md) ·
[Roadmap](https://github.com/i-skynetai/ethan/blob/main/ROADMAP.md)

### [Skynet+ — an environment for agent applications](https://github.com/i-skynetai/sky-plus)

**Problem:** each agent application rebuilds runtime, model access, memory, safety,
evaluation and tracing.

**Implemented:** a Python SDK with configurable providers, readiness checks, tool
guardrails, per-run scores, tracing and a tamper-evident event log.

**Adoption value:** lets application developers concentrate on the customer workflow
while configuring shared agent infrastructure.

**Evidence and limits:** the local demo uses a fake model. LangGraph is the only real
runtime; human checkpoints cannot yet resume and streaming is unavailable.
Pattern-based tool-output screening does not establish complete prompt-injection
protection. Praxis integration is planned, not implemented.

[Try the demo](https://github.com/i-skynetai/sky-plus#see-it-work-in-sixty-seconds) ·
[Architecture](https://github.com/i-skynetai/sky-plus/blob/main/docs/architecture.md) ·
[Roadmap](https://github.com/i-skynetai/sky-plus/blob/main/ROADMAP.md)

### [Praxis — evaluation before model substitution](https://github.com/i-skynetai/praxis)

**Problem:** replacing repeated frontier-model calls with a smaller model requires
evidence that the smaller model is ready.

**Implemented:** typed capabilities, trace capture, calibration, readiness gates,
shadow/canary/serve stages and fallback when a student abstains or returns an invalid
answer.

**Adoption value:** makes model substitution a checked engineering decision.

**Evidence and limits:** the demo uses synthetic tickets and a rule-based teacher.
Dataset and paired-scorecard work remains on the roadmap. This is an evolving
implementation; production training, deployment and measured savings are not claimed.

[Try the demo](https://github.com/i-skynetai/praxis#see-it-work-in-sixty-seconds) ·
[Architecture and test guarantees](https://github.com/i-skynetai/praxis/blob/main/docs/architecture.md) ·
[Release plan](https://github.com/i-skynetai/praxis/blob/main/docs/release-plan-v1.0.md)

## Tools I use

**Applications:** Python · FastAPI · PostgreSQL · React · TypeScript · Module Federation  
**Delivery:** Docker · GitHub Actions · Azure Pipelines · OpenTelemetry  
**AI & knowledge:** RAG · GraphRAG · MCP · Neo4j · Elasticsearch/OpenSearch · LLM evaluation  
**Security:** role-based access control · tenant isolation · audit trails · agent identity · guardrails

## Let's connect

I welcome conversations about AI platform and solution architecture, context engineering,
enterprise AI enablement and secure agent workflows, with hands-on software delivery.
Available for international relocation; employer visa sponsorship required.

[Connect on LinkedIn](https://www.linkedin.com/in/arupmmi/) or
[email me](mailto:arupus07@gmail.com).