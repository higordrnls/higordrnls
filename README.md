# 👋 Hi, I'm Higor Dornelas

**Backend Development • Distributed Systems • Automation • Data • Product Engineering**

I build practical software with a focus on backend engineering, data integrity, automation, and thoughtful product experiences. My background in operations and data helps me connect technical decisions to real workflows.

Currently deepening my work with **TypeScript, NestJS, PostgreSQL, transactional consistency, and distributed messaging**, while shipping small, usable products end to end.

---

## 📊 GitHub Stats

<a href="https://github.com/higordrnls">
  <picture>
    <source srcset="https://github-readme-stats-diogofrr.vercel.app/api?username=higordrnls&show_icons=true&theme=radical" media="(prefers-color-scheme: dark)" />
    <source srcset="https://github-readme-stats-diogofrr.vercel.app/api?username=higordrnls&show_icons=true&theme=light" media="(prefers-color-scheme: light)" />
    <img height="185em" src="https://github-readme-stats-diogofrr.vercel.app/api?username=higordrnls&show_icons=true" />
  </picture>

  <picture>
    <source srcset="https://github-readme-stats-diogofrr.vercel.app/api/top-langs/?username=higordrnls&layout=compact&theme=radical" media="(prefers-color-scheme: dark)" />
    <source srcset="https://github-readme-stats-diogofrr.vercel.app/api/top-langs/?username=higordrnls&layout=compact" media="(prefers-color-scheme: light)" />
    <img height="185em" src="https://github-readme-stats-diogofrr.vercel.app/api/top-langs/?username=higordrnls&layout=compact" />
  </picture>
</a>

---

# 🎮 Live Project — Tigrinho de Mentirinha

**[▶ Play the game](https://distributed-wagering-processor.pages.dev/)** · **[View the source code](https://github.com/higordrnls/distributed-wagering-processor)**

A playful, mobile-first slot-machine **simulation using fictional coins only**. Built as a portfolio extension of a distributed transaction-processing study.

- **Frontend:** HTML, CSS, and JavaScript, with responsive UI and animated reels
- **Game backend:** Cloudflare Pages Functions, with server-authoritative spin outcomes
- **Persistence:** Neon PostgreSQL for anonymous player wallets, balances, and round history
- **Consistency:** atomic SQL updates and idempotent spin requests
- **Deployment:** GitHub → Cloudflare Pages

**Architecture note:** the live game runs on its own serverless backend. It is **not connected** to the separate NestJS/SQS transaction processor described below.

---

# 🚀 Tech Stack

<p align="left">

<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angular/angular-original.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg"/>
<img height="36" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-original.svg"/>

</p>

---

# 🧠 About Me

I'm developing my career in **backend software engineering**, drawing on hands-on experience in **operations, data analysis, automation, and digital products**.

My projects usually begin with a problem or idea and evolve into structured software systems. Depending on the problem, that can involve backend development, browser automation, APIs, data analysis, frontend applications, AI integrations, or system architecture.

I'm especially interested in:

* Backend Engineering & APIs
* PostgreSQL, Transactions & Data Modeling
* Distributed Systems & Messaging
* Automation & Data Engineering
* Full Stack Product Development
* System Architecture

I also care about documenting the reasoning behind technical decisions, not just the code itself.

---

# ⭐ Featured Projects

## ⚙️ Distributed Wagering Processor — Backend Engineering

A transaction-processing backend built to explore **financial consistency, idempotency, concurrency, and failure recovery** in distributed systems.

**Highlights**

* BET, WIN, LOSS, REFUND, and ROLLBACK operations
* PostgreSQL transactions, wallet-level locking, and immutable ledger
* Persistent idempotency, inbox/outbox patterns, and SQS FIFO messaging
* Integration tests covering concurrent processing and recovery scenarios
* Architecture documentation, trade-offs, and load-test notes

**Stack**

Bun • TypeScript • NestJS • PostgreSQL • SQS • Docker

**[Repository and architecture](https://github.com/higordrnls/distributed-wagering-processor)** · **[Case study](https://github.com/higordrnls/distributed-wagering-processor/blob/main/docs/PORTFOLIO_CASE_STUDY.md)**

---

## 🕶️ Agadê — Digital Eyewear Platform

A conceptual Brazilian eyewear brand and digital product exploring **digital manufacturing, contemporary design, e-commerce, and circular economy**.

Agadê is currently being developed as a portfolio project, with the goal of exploring the construction of a complete digital product — from brand and product definition to frontend architecture, data modeling, and future commerce infrastructure.

**Highlights**

* Product & UX design
* React / TypeScript prototype
* Product catalog architecture
* Conceptual e-commerce experience
* Architecture Decision Records
* Product Requirements Documentation
* Planned Supabase / PostgreSQL architecture
* Digital manufacturing & circular economy concepts

**Stack**

React • TypeScript • Vite • Tailwind CSS • Motion

👉 https://github.com/higordrnls/agade

---

## 🏋️ Hevy AI Automator

Browser automation engine capable of transforming structured workout data into fully configured Hevy routines.

**Highlights**

* Browser Automation
* Structured JSON workout schema
* Multi-provider architecture
* AI-ready architecture
* Automatic workout creation
* Intelligent exercise mapping

**Stack**

TypeScript • Playwright • Zod • Node.js

👉 https://github.com/higordrnls/hevy-ai-automator

---

## 💰 Kanban Financeiro

Interactive personal finance application inspired by Trello.

**Highlights**

* Drag-and-drop transactions
* Cash flow tracking
* Local persistence
* Dark / Light mode

**Stack**

JavaScript • HTML • CSS

👉 https://github.com/higordrnls/Kanban-Financeiro

---

## 📊 Sales Performance Dashboard

Business Intelligence dashboard built for retail sales analysis.

**Highlights**

* R$214K revenue analyzed
* 7,924 products tracked
* KPI dashboard
* DAX measures
* Data modeling

**Stack**

Power BI • DAX • Excel

👉 https://github.com/higordrnls/dashboard-vendas-powerbi

---

## 🎮 Procedural Rust Engine

Experimental 2D game engine focused on ECS architecture and procedural generation.

**Highlights**

* Infinite procedural terrain
* ECS architecture
* State machine
* Collision system
* XP & level system

**Stack**

Rust • Bevy

👉 https://github.com/higordrnls/retro-game-2000

---

## 🔄 ArchDaily Pipeline Creator

Serverless data pipeline that collects architecture news and exposes structured information through APIs.

**Stack**

Angular • Python • BeautifulSoup • Serverless Functions

👉 https://github.com/higordrnls/ArchDaily-Pipeline-Creator

---

# 🔭 What I'm Building Toward

I'm interested in building software that goes beyond isolated features and evolves into **complete, well-structured systems**.

Some of the product ecosystems I'm exploring include:

* 🕶️ **Agadê** — Sustainable Eyewear Platform
* 📐 **Lumear** — Vedic Architecture Platform
* 🥟 **Dornelas ERP** — Business Management System

Across these projects, I'm exploring the same broader idea:

> **Build software that connects product thinking, automation, data, and intelligent systems.**

---

# 📚 Engineering Approach

I believe good software is not only about writing code.

My approach increasingly involves:

**Problem → Product → Architecture → Implementation → Data → Iteration**

That means documenting requirements, making explicit architectural decisions, modeling data carefully, validating interfaces through prototypes, and evolving the system incrementally.

---

# 📫 Contact

* **LinkedIn**
  https://linkedin.com/in/hdornelas

* **GitHub**
  https://github.com/higordrnls

---

> **Building software that turns ideas and real-world problems into structured, intelligent systems.**
