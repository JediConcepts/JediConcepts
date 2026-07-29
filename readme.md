# Jamie Easterman / Jedi Concepts

I build governed AI systems, orchestration layers, and production AI infrastructure for regulated and enterprise environments.

My work focuses on deterministic control layers around probabilistic AI systems, combining workflow orchestration, validation, auditability, evidence traceability, and operational reliability.

Most current work is private due to commercial, legal, and enterprise confidentiality requirements. The infrastructure layer is open source below. Consulting (AI cost and execution audits, architecture reviews, implementation) runs through [Super Web Guys](https://superwebguys.com) and [Jedi Concepts](https://jediconcepts.com).

## Current Focus

- AI execution and orchestration systems
- AI cost architecture and spend governance
- Multi model routing and provider abstraction
- Evidence intelligence pipelines
- Agent governance and validation layers
- Workflow integrated AI systems
- Structured reasoning and assertion analysis
- Reality Inference Evaluation

## Open Source

### [ai-execution-router](https://github.com/JediConcepts/ai-execution-router)

> The router executes. The controller decides.

A deterministic execution engine for LLM calls. One function, `complete()`: takes a fully resolved request, calls one provider once, returns one result with typed errors and usage telemetry. Policy, routing, fallback, cost guards, and audit live in a thin controller on the caller's side; the router itself never decides. Zero runtime dependencies, MIT.

```sh
npm install ai-execution-router
```

### [local-cli-bridge](https://github.com/JediConcepts/local-cli-bridge)

Makes locally authenticated CLI model tools look like an OpenAI compatible server, with an optional Cloudflare Tunnel launcher. A development and testing bridge, not a hosted model service. Zero dependencies, MIT.

```sh
npx local-cli-bridge
```

### [probantum-site](https://github.com/JediConcepts/probantum-site)

Public product and positioning layer for Probantum, a practitioner facing evidence intelligence platform.

## Engineering Themes

- TypeScript
- Next.js
- AI orchestration
- Multi provider routing
- Validation systems
- Structured extraction pipelines
- Human in the loop workflows
- Auditability and traceability
- Production AI operations

## Background

30+ years across SaaS, cloud, telecoms, infrastructure, enterprise systems, and AI driven platforms.

Selected work includes:
- KPMG
- Amazon Locker infrastructure
- NHS messaging and mobility systems
- DEC Tsunami Appeal platform
- Early ISP and SaaS infrastructure through London Web

## Philosophy

AI systems become commercially valuable when reliability, governance, workflow integration, and operational control are treated as first class architectural concerns.
