<div align="center">

# Shubham Prajapati

### AI Systems Builder · Forward Deployed Engineer · India

This repository hosts my personal portfolio. The best way to experience it is live, not as source files.

## → [View the live portfolio](https://my-portfolio-github-io-beta-five.vercel.app/) ←

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubham-prajapati086)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-14b8a6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Shubham.prajapati086@gmail.com)
[![Open to Work](https://img.shields.io/badge/Status-Open%20to%20FDE%20%2F%20TSE%20Roles-10b981?style=for-the-badge)](mailto:Shubham.prajapati086@gmail.com)

</div>

---

## The Story

For 5 years I worked enterprise IT operations: SAP and ServiceNow, strict SLAs, the receiving end of broken software at HCL Technologies and EvoraIT. I learned what production discipline actually means.

Then, about 2 years ago, I started experimenting with AI on my own. No bootcamp, no team, no roadmap. I began by building small AI apps, taught myself as I went, and kept pushing until the apps became full systems.

The further I went, the harder the real problems got. Not "how do I call an LLM" problems, but systems problems:

- **Memory.** My agents forgot everything between sessions. There was no continuity, no way to reuse what they had already learned.
- **Context.** Agents wasted thousands of tokens re-reading entire codebases. Context windows blew up and so did the cost.
- **Reliability.** A single-provider setup died the moment one API rate-limited or went down.
- **Consistency.** Multi-agent pipelines drifted, contradicted themselves, and repeated the same failures in loops.

I solved each one inside my own codebases, then optimized: multi-provider routing with failover, persistent reality-first memory, context graphs to cut token waste, response caching, and guardrails against prompt injection and repeat failures.

Once those patterns were stable, I extracted them out of my private systems and open-sourced them, so other self-taught builders do not have to learn it all the hard way. This site is the showcase of that work.

---

## The Journey

```
2019 - 2022   HCL Technologies, Noida
              L1 Agent to SME to Team Lead to Acting Floor Manager
              250+ agents trained, new support vertical live in 6 months, 4 promotions

2022 - 2024   EvoraIT Solution Pvt Ltd, Gurugram
              SAP L2 Support Specialist
              350 tickets/week, 98% SLA compliance, 95% MTTR improvement

2024 - Now    Self-taught AI engineering
              From first AI experiments to production systems and open-source patterns
```

I am open to **Forward Deployed Engineer**, **Technical Solutions Engineer**, and **Founding Engineer** roles at API-first AI startups.

---

## What I Built

**19 repositories · 261+ automated tests · 3 shipped products · 5+ years ops & SLA ownership**

Full case studies, architecture diagrams, and live demos on the [portfolio site](https://shubham0086.github.io/MyPortfolio.github.io/) — which itself runs a live RAG chatbot grounded on these repos (ask it anything).

### Products

| Product | Stack | Status |
|---------|-------|--------|
| **WellnessInYou + BODH** — Full-stack AI wellness platform | Next.js 15, Expo 54, CrewAI, Gemini, Razorpay/Stripe | Live |
| **Agentic SDLC** — 6-agent software development pipeline | Node.js, SQLite Blackboard, multi-LLM router, React+Vite | Private beta |
| **Agentic OS** — Multi-agent outreach + content system | FastAPI, Redis, LangChain, Instagram automation | Internal |
| **Adiyogi Books** — Independent publishing brand | Next.js, Prisma, Razorpay | Live |

### Open-Source: Learn Track

Foundations for anyone building agent systems from scratch.

| Repo | What it teaches |
|------|----------------|
| [AI-Systems-Evolution](https://github.com/shubham0086/AI-systems-evolution) | The same task at 6 levels of autonomy — code → single call → workflow → agent → team → swarm |
| [Agent-Anatomy](https://github.com/shubham0086/Agent-Anatomy) | One agent, four removable organs (brain/hands/memory/loop). Toggle one off, watch it break |

### Open-Source: Solve Track

Production patterns extracted from real systems. Each repo isolates one hard problem.

| Repo | Problem solved | Tests |
|------|---------------|-------|
| [Agent-Scars](https://github.com/shubham0086/Agent-Scars) | Failure memory — agents that learn from past mistakes | 7 |
| [Agent-Context](https://github.com/shubham0086/Agent-Context) | Dependency graphs to cut token waste on large codebases | 6 |
| [Agent-Recall](https://github.com/shubham0086/Agent-Recall) | Cross-session solution memory with similarity retrieval | 9 |
| [Agent-Routing](https://github.com/shubham0086/Agent-Routing) | Multi-provider LLM failover (NVIDIA → Groq → OpenRouter → Gemini) | 23 |
| [Research-Agent](https://github.com/shubham0086/research-agent) | Web research + multi-source summarization pipeline | 9 |
| [Content-Analyzer](https://github.com/shubham0086/content-analyzer) | URL → structured JSON extraction with AI analysis | 4 |
| [Video-Engine-Starter](https://github.com/shubham0086/video-engine-starter) | Text-to-video orchestration with Remotion + AI directors | — |
| [Agent-Constitution](https://github.com/shubham0086/agent-constitution) | Drift detection + anti-hallucination guardrails | 6 |
| [MCP-Agent-Toolkit](https://github.com/shubham0086/mcp-agent-toolkit) | MCP server with blackboard, SCAR, and cache tools (node:sqlite) | 13 |
| [RAG-Knowledge-Engine](https://github.com/shubham0086/rag-knowledge-engine) | Hybrid retrieval (BM25 + vector RRF) + cross-encoder rerank + RAGAS eval | 25 |

### Open-Source: Integrate Track

Complete systems and production templates.

| Repo | What it is | Tests |
|------|-----------|-------|
| [Agentic-Patterns](https://github.com/shubham0086/agentic-patterns) | 7 architectural guides with runnable starters | — |
| [Agentic-Systems](https://github.com/shubham0086/agentic-systems) | 5 complete standalone agent systems | — |
| [AgentKernel](https://github.com/shubham0086/agentkernel) | 6 production engines in Python + JavaScript | — |
| [Agentic-SaaS-Boilerplate](https://github.com/shubham0086/agentic-saas-boilerplate) | Billable multi-agent SaaS template — real WorkflowEngine, SSE queues, AgentRegistry | 22 |

---

## The Engineering Problems, and How I Solved Them

| Problem | What I built to solve it |
|---------|--------------------------|
| Agents forgetting across sessions | Reality-first persistent memory with cross-session reuse |
| Token waste from re-reading code | Dependency context graphs and layered RAG filtering |
| Single point of failure on LLM calls | Multi-provider router with circuit breakers and ordered failover |
| Brittle linear agent chains | DAG orchestration with Kahn's topological scheduling |
| Agents drifting and repeating failures | Anti-drift reality files and a repeat-failure guard (SCAR) |
| Prompt injection and secret leakage | Input and output guardrails, tested against real payloads |
| RAG returning irrelevant chunks | Hybrid BM25 + vector retrieval with RRF fusion + cross-encoder rerank |
| LLM provider downtime | 5-provider failover chain — any key missing is silently skipped |

---

## Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=github&logoColor=white)

Static site. No framework, no build step. Hand-written HTML, CSS, and vanilla JavaScript with inline animated SVG diagrams. Loads in under a second. The portfolio chatbot runs as a Vercel serverless function — Gemini embeddings over a prebuilt 118-chunk index, generation on a 5-provider failover chain.

---

## Contact

- **Email:** Shubham.prajapati086@gmail.com
- **LinkedIn:** [linkedin.com/in/shubham-prajapati086](https://linkedin.com/in/shubham-prajapati086)
- **Location:** Alwar, Rajasthan. Open to onsite Gurugram/NCR and remote globally
