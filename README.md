<div align="center">

# Shubham Prajapati

### AI Systems Builder · Forward Deployed Engineer · India

This repository hosts my personal portfolio. The best way to experience it is live, not as source files.

## → [View the live portfolio](https://shubham0086.github.io/MyPortfolio.github.io/) ←

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

Four products and three open-source tracks. Full case studies, architecture diagrams, and live demos are on the [website](https://shubham0086.github.io/MyPortfolio.github.io/).

**Products**
- **WellnessInYou + BODH** : full-stack wellness platform (Next.js 15, Expo 54, CrewAI)
- **Agentic SDLC** : 6-agent software development pipeline (private beta)
- **Agentic OS** : outreach CRM with Instagram automation
- **Adiyogi Books** : independent publishing brand (live)

**Open-source tracks** *(separate repositories, sharing the patterns with the community)*
- **AI Systems Evolution** : the entry point. The same task solved at six levels of autonomy — code → single call → workflow → agent → team → swarm
- **Agent Anatomy** : the atom. One agent, four removable organs (brain/hands/memory/loop). Toggle one off and watch it break
- **Agentic Patterns** : the theory. Architectural guides for the problems above, with runnable Node and Python starters
- **Agentic Systems** : the practice. 5 standalone runnable agent systems
- **AgentKernel** : the infrastructure. 6 production engines, written in both Python and JavaScript

---

## The Engineering Problems, and How I Solved Them

These are the lessons that came out of building real systems alone, now documented and open-sourced:

| Problem | What I built to solve it |
|---------|--------------------------|
| Agents forgetting across sessions | Reality-first persistent memory with cross-session reuse |
| Token waste from re-reading code | Dependency context graphs and layered RAG filtering |
| Single point of failure on LLM calls | Multi-provider router with circuit breakers and ordered failover |
| Brittle linear agent chains | DAG orchestration with Kahn's topological scheduling |
| Agents drifting and repeating failures | Anti-drift reality files and a repeat-failure guard (SCAR) |
| Prompt injection and secret leakage | Input and output guardrails, tested against real payloads |

---

## Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=github&logoColor=white)

Static site. No framework, no build step. Hand-written HTML, CSS, and vanilla JavaScript with inline animated SVG diagrams. Loads in under a second.

---

## Contact

- **Email:** Shubham.prajapati086@gmail.com
- **LinkedIn:** [linkedin.com/in/shubham-prajapati086](https://linkedin.com/in/shubham-prajapati086)
- **Location:** Alwar, Rajasthan. Open to onsite Gurugram/NCR and remote globally
