<div align="center">

```
  ██████╗  ██████╗  ██████╗  ██████╗ ██╗     ███████╗
 ██╔════╝ ██╔═══██╗██╔═══██╗██╔════╝ ██║     ██╔════╝
 ██║  ███╗██║   ██║██║   ██║██║  ███╗██║     █████╗  
 ██║   ██║██║   ██║██║   ██║██║   ██║██║     ██╔══╝  
 ╚██████╔╝╚██████╔╝╚██████╔╝╚██████╔╝███████╗███████╗
  ╚═════╝  ╚═════╝  ╚═════╝  ╚═════╝ ╚══════╝╚══════╝
         AI AGENTS · INTENSIVE · 2026
```

**Yash Surve** · 5-Day Vibe Coding Intensive · Google × Kaggle · June 15–19, 2026

[![Course](https://img.shields.io/badge/Google%20×%20Kaggle-AI%20Agents%20Intensive-4285F4?style=flat-square&logo=google&logoColor=white)](https://kaggle.com)
[![Status](https://img.shields.io/badge/Status-Day%202%20of%205-brightgreen?style=flat-square)](.)
[![Badges](https://img.shields.io/badge/Badges%20Earned-3-FFD700?style=flat-square&logo=google-developers&logoColor=white)](.)
[![Apps Built](https://img.shields.io/badge/Apps%20Shipped-2-orange?style=flat-square)](.)
[![LinkedIn](https://img.shields.io/badge/Follow%20Journey-LinkedIn-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/yashsurve)

</div>

---

## What is this?

This repo documents my hands-on journey through Google's **5-Day AI Agents: Intensive Vibe Coding Course** — a free, production-focused program by Google researchers & engineers, hosted on Kaggle.

The course covers the full arc of modern agent development: from understanding why vibe coding is reshaping the SDLC, all the way to deploying governed, observable, production-grade agent fleets on Cloud Run.

Every day = a whitepaper + podcast + codelabs + live AMA with Google engineers. This repo captures everything: notes, shipped projects, key takeaways, and honest reflections.

---

## Progress

| # | Day | Topic | Status | App Built | Badge |
|---|-----|-------|--------|-----------|-------|
| 1 | Jun 15 | Introduction to Agents & Vibe Coding | ✅ Done | Web App → Cloud Run | 🏅 ×2 |
| 2 | Jun 16 | Agent Tools & Interoperability | ✅ Done | BigQuery Release Notes + Tweet App | 🏅 ×1 |
| 3 | Jun 17 | Agent Skills | 🔄 In Progress | — | — |
| 4 | Jun 18 | Agent Security & Evaluation | ⬜ Upcoming | — | — |
| 5 | Jun 19 | Spec-Driven Production Development | ⬜ Upcoming | — | — |

---

## Daily Logs

### Day 1 — Introduction to Agents & Vibe Coding
> *"Stop writing syntax. Start describing intent."*

**Core Insight:** The SDLC is being compressed. Developers are transitioning from writing code line-by-line to becoming **system orchestrators** — designing the evaluation, constraint, and context harnesses that guide autonomous AI execution. The whitepaper *"The New SDLC with Vibe Coding"* frames this shift clearly.

**What I Built:**
- 🎈 **Snowflakes & Balloons Web App** — built using Google AI Studio via natural language prompt, deployed live to **Cloud Run**
- Explored **Antigravity 2.0 IDE** for the first time

**Key Concepts:**
- Intent-driven development over syntax-driven
- AI as a compression layer on traditional SDLC
- Developer as orchestrator, not implementer

**Resources:** [`/daily/day1/`](./daily/day1/) · [Notes](./daily/day1/notes.md) · [Whitepaper Reflection](./daily/day1/whitepaper.md)

---

### Day 2 — Agent Tools & Interoperability
> *"Open protocols. Unlimited capabilities."*

**Core Insight:** The agent ecosystem is converging on a plug-and-play protocol stack. MCP standardizes tool connectivity, A2A enables agent-to-agent collaboration, A2UI generates UI on the fly, and AP2/UCP handle machine-to-machine commerce — all eliminating the brittle custom integrations of the past.

**What I Built:**
- 📰 **BigQuery Release Notes Dashboard** — Python Flask app built entirely via **Antigravity CLI** using natural language. Fetches live release notes from Google's public XML feed and includes a one-click Tweet button for any update.

**Key Concepts:**
- MCP (Model Context Protocol) — connects agents to data sources
- A2A (Agent2Agent) — structured multi-agent collaboration
- A2UI — runtime-generated user interfaces
- AP2 & UCP — secure machine-to-machine commerce protocols

**Resources:** [`/daily/day2/`](./daily/day2/) · [Notes](./daily/day2/notes.md) · [App Code](./daily/day2/bigquery-release-notes/)

---

### Day 3 — Agent Skills *(In Progress)*

**What's Coming:**
- Long-term memory & persistent state in agents
- Optimal token use strategies
- Integrating modular skills into agentic frameworks

**Resources:** [`/daily/day3/`](./daily/day3/) *(updating live)*

---

### Day 4 — Agent Security & Evaluation *(Upcoming)*

**What's Coming:**
- Implementing rigorous testing & guardrails
- Defending against prompt injection & new threat vectors
- Building quality evaluation frameworks

---

### Day 5 — Spec-Driven Production Development *(Upcoming)*

**What's Coming:**
- Graduating local agents into governed, observable production fleets
- Cloud deployment, debugging, and observability at scale

---

## Repo Structure

```
google-ai-agents-intensive/
│
├── README.md                  ← You are here
├── JOURNAL.md                 ← Raw daily stream-of-consciousness notes
│
├── daily/
│   ├── day1/
│   │   ├── notes.md           ← Whitepaper & podcast notes
│   │   ├── whitepaper.md      ← "The New SDLC with Vibe Coding" reflection
│   │   └── snowflakes-app/    ← Shipped web app code
│   ├── day2/
│   │   ├── notes.md
│   │   ├── whitepaper.md      ← "Agent Tools & Interoperability" reflection
│   │   └── bigquery-release-notes/  ← Flask app + CLI prompt log
│   ├── day3/
│   ├── day4/
│   └── day5/
│
├── projects/
│   └── capstone/              ← Final capstone project (Day 5)
│
└── resources/
    ├── whitepapers.md         ← Links to all 5 whitepapers
    ├── podcasts.md            ← YouTube episode links
    └── tools.md               ← Tools & platforms used
```

---

## What I'm Learning to Build

By the end of Day 5, I'll have shipped agents that can:

- **Remember** — persistent memory across sessions
- **Act** — call external APIs and execute code
- **Collaborate** — talk to other agents via A2A
- **Evaluate themselves** — built-in quality guardrails
- **Scale** — deploy to Cloud Run as production-grade fleets

---

## Tools & Stack

| Tool | Used For |
|------|----------|
| Google AI Studio | Rapid prototyping & vibe coding |
| Antigravity 2.0 IDE | Agent development environment |
| Antigravity CLI | Terminal-based vibe coding |
| Google Cloud Run | Deploying apps to production |
| MCP Servers | Connecting agents to live data |
| Python Flask | Backend for Day 2 app |

---

## My LinkedIn Posts

Documenting the journey publicly — follow along for daily updates.

- [📝 Day 1 + Day 2 Combined Post](https://linkedin.com/in/yashsurve) *(posted Jun 16)*
- Day 3 post — *coming Jun 17*
- Day 4 post — *coming Jun 18*
- Day 5 + Capstone — *coming Jun 19*

---

## Prompts That Worked

One of the most practical things I'm collecting: the exact natural language prompts I used to build real apps.

```
# Day 1 — Google AI Studio
"Create a formal looking frontend application that has two buttons:
'Snowflakes' and 'Balloons'. If the user clicks Snowflakes, snowflakes
of medium size should start falling from top to bottom for 5 seconds.
If the user clicks Balloons, balloons of medium size should start
floating from the bottom for 5 seconds."
```

```
# Day 2 — Antigravity CLI
"Please build a web application for me using Python Flask and plain
vanilla HTML, JavaScript and CSS that fetches the BigQuery Release
Notes from https://docs.cloud.google.com/feeds/bigquery-release-notes.xml
and shows them to me. A simple refresh button with a spinner is good
enough. I would also like the ability to select any specific update
and tweet about it."
```

> See [`/daily/`](./daily/) for more prompt logs as the course progresses.

---

## Capstone

At the end of Day 5, I'll participate in the course capstone — a real-world agent project competing for:
- 🥇 Kaggle Certificates
- 🎁 Google Swag
- 📣 Recognition on Google & Kaggle social channels

Follow this repo to see what I build.

---

<div align="center">

**Yash Surve** · Pune, India · Building in public · June 2026

[LinkedIn](https://linkedin.com/in/yashsurve) · [Google Developer Profile](https://g.dev/yashsurve)

*Started with a prompt. Ended with production agents.*

</div>
