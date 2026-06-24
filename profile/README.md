<p align="center">
  <img src="https://raw.githubusercontent.com/venelouis/Rullst/main/Rullst.png" alt="Rullst Logo" width="300">
</p>

<h1 align="center">Rullst 📜🦀🌐🚀</h1>
<h3 align="center"><i>Rust for those who want to build, not suffer.</i></h3>

<p align="center">
  <img src="https://img.shields.io/crates/v/rullst?style=for-the-badge&color=10b981&logo=rust" alt="Crates.io">
  <a href="https://crates.io/crates/rullst"><img src="https://img.shields.io/crates/d/rullst?style=for-the-badge&color=blue" alt="Crates.io Downloads"></a>
  <a href="https://docs.rs/rullst"><img src="https://img.shields.io/docsrs/rullst?style=for-the-badge&logo=docsdotrs" alt="Docs.rs"></a>
  <a href="https://github.com/Rullst/Rullst/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/Rullst/Rullst/ci.yml?style=for-the-badge&label=Build" alt="Rust CI"></a>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License: MIT">
  <a href="https://discord.gg/2ntKFtsSjw"><img src="https://img.shields.io/badge/Discord-Join%20Community-5865F2?logo=discord&logoColor=white&style=for-the-badge" alt="Discord"></a>
  <a href="https://rullst.github.io"><img src="https://img.shields.io/badge/Website-Official%20Site-blue?logo=github&logoColor=white&style=for-the-badge" alt="Official Website"></a>
</p>

<br/>

**Rullst** is an opinionated, developer-first full-stack web framework for Rust, obsessively designed for **Emotional Productivity**. It solves the biggest problem in the Rust web ecosystem: the high barrier of entry. With Rullst, you spend your energy building your business, not fighting borrow checkers and manual routing setups.

<h3 align="center">🛡️ Enterprise-Grade Security</h3>

<p align="center">
  Rullst is built with a "Zero-Panic Policy" and tested against the most rigorous standards in the industry.<br/>
  Our continuous pipeline guarantees absolute safety for production edge infrastructure:
</p>

<div align="center">

| Security Audit | Status | Description |
| :--- | :---: | :--- |
| **OSSF Scorecard** | [![OSSF Scorecard](https://img.shields.io/ossf-scorecard/github.com/Rullst/Rullst?label=&style=flat-square)](https://github.com/Rullst/Rullst/actions/workflows/scorecards.yml) | Supply-chain security & best practices |
| **Codecov** | [![Codecov](https://img.shields.io/codecov/c/github/Rullst/Rullst?style=flat-square&label=)](https://codecov.io/gh/Rullst/Rullst) | Strict code coverage enforcement |
| **OpenSSF** | [![OpenSSF](https://img.shields.io/badge/status-Gold-gold?style=flat-square&label=)](https://www.bestpractices.dev/projects/13321) | Open source security standards |
| **Continuous Fuzzing** | [![Continuous Fuzzing](https://img.shields.io/github/actions/workflow/status/Rullst/Rullst/fuzzing.yml?style=flat-square&label=)](https://github.com/Rullst/Rullst/actions/workflows/fuzzing.yml) | Fuzzing against edge cases & panics |
| **CodeQL SAST** | [![CodeQL SAST](https://img.shields.io/github/actions/workflow/status/Rullst/Rullst/codeql.yml?style=flat-square&label=)](https://github.com/Rullst/Rullst/actions/workflows/codeql.yml) | Advanced semantic code analysis |
| **OWASP ZAP DAST** | [![OWASP ZAP DAST](https://img.shields.io/github/actions/workflow/status/Rullst/Rullst/dast-zap.yml?style=flat-square&label=)](https://github.com/Rullst/Rullst/actions/workflows/dast-zap.yml) | Dynamic vulnerability scanning |
| **Cargo Deny** | [![Cargo Deny](https://img.shields.io/github/actions/workflow/status/Rullst/Rullst/cargo-deny.yml?style=flat-square&label=)](https://github.com/Rullst/Rullst/actions/workflows/cargo-deny.yml) | Banning unmaintained/vulnerable crates |
| **LLVM Coverage** | [![LLVM Coverage](https://img.shields.io/github/actions/workflow/status/Rullst/Rullst/coverage.yml?style=flat-square&label=)](https://github.com/Rullst/Rullst/actions/workflows/coverage.yml) | Strict code coverage enforcement |

</div>

<!--
| **Mutation Testing** | [![Mutation Testing](https://img.shields.io/github/actions/workflow/status/Rullst/Rullst/mutants.yml?style=flat-square&label=)](https://github.com/Rullst/Rullst/actions/workflows/mutants.yml) | Validating test suite exhaustiveness |
-->

<br/>

**Rullst** (Rust + Fullstack) is an opinionated, developer-first full-stack web framework for Rust, obsessively designed for **Emotional Productivity**. 

It was created to solve the biggest problem in the Rust web ecosystem: the high barrier of entry that turns web programming into a PhD research on compiler design. We believe you should spend your energy building your business, not fighting borrow checkers and manual routing setups.

<h2 align="center">How to build a SaaS Blueprint with Rullst </h2>
<p align="center">
<a href="https://www.youtube.com/watch?v=nDXLeNM327g">
  <img src="https://img.youtube.com/vi/nDXLeNM327g/hqdefault.jpg" alt="How to build a SaaS with Rullst" width="430" />
</a>
</p>


## 💡 The Rullst Manifesto

> *"Most Rust frameworks treat the web developer like a compiler engineer. Rullst treats the developer like someone who wants to build awesome products at lightning speed."*

In the current ecosystem, to write a simple CRUD, you are forced to glue dozens of crates together, manually map nested routing trees, write verbose ORMs requiring multiple structs, and continuously clone variables inside dynamic HTML templates just to satisfy the borrow checker.

Rullst redefines this experience. We offer an integrated, cohesive developer experience that brings the sweetness and iteration speed of **Laravel and Next.js** together with the Formula 1 performance and military-grade safety of **Rust, Axum, and Hyper**:

* **No More Frankenstein setups:** A single cohesive framework managing your server (Axum), your database (`rullst-orm`), and your HTML rendering.
* **No More Borrow Checker fights in UI:** Our compile-time JSX-like `html!` macro processes pure elements on the server (SSR). It generates optimized string-builders directly at compile time. It's blazing fast, safe, and SEO-friendly by default.
* **First-Class Active Record ORM:** Native integration with your **`rullst-orm`** package. Interacting with databases is as intuitive as `user.save()`.
* **AI-Native Engineering & AI-Friendly:** Designed from the ground up for modern pair-programming. Strict type-safety, zero dynamic runtime magic, automatic `.ai-rules` scaffolding, and structured schemas prevent AI agent hallucinations and allow instant compiler self-correction.

---

## 🏆 Everything You Need, Built-In

Rullst ships with **10 completed milestones** covering every layer of modern web development:

| Category | Features |
|---|---|
| 🛠️ **CLI & DX** | `cargo rullst new` wizard (interactive blueprints: Blank, LMS, SaaS, Blog, ERP, Uptime), `make:controller`, `make:model -m`, `make:middleware`, `make:worker`, `generate:openapi`, `cargo rullst upgrade` (self-healing) |
| 🗄️ **Database** | Active Record ORM, Migrations (`db:migrate`, `db:rollback`, `db:status`), Seeders & Factories, HasMany / BelongsTo / BelongsToMany, Eager Loading |
| 🔒 **Auth & Security** | Argon2 hashing, JWT & Cookie sessions, CSRF protection, Social OAuth (Google, GitHub, Facebook, Twitter via `rullst-connect`), `cargo rullst auth` scaffolding |
| ⚡ **Frontend** | HTMX first-class support, TailwindCSS auto-integration, partial template rendering, **Rullst Live** (Phoenix LiveView-inspired server-driven UI), **Wasm Islands** (`#[client_component]`) |
| 📦 **Production** | Queue (SQLite/Redis), Cache (Memory/Redis), Task Scheduler (Cron), Docker multi-stage builds, **Rullst Horizon** dashboard |
| 🏢 **Enterprise** | Declarative Validation, Mailer (SMTP/Resend/SendGrid), Storage (Local/S3/R2), WebSockets, Multi-Tenancy, Feature Flags, E2E Testing |
| 🚀 **Unfair Advantage** | **AI Core** (`rullst::ai` — OpenAI/Gemini/Anthropic/Ollama + RAG), **Rullst Studio** (visual DB GUI), **Self-Healing Error Console** (AI auto-fix), **Hot Reloading via `dylib`** |
| 🌍 **Edge & Data** | Edge Runtime (Cloudflare Workers, Fastly, AWS Lambda@Edge), Zero-Config Distributed SQLite Replication (Turso/D1), Autonomous Upgrades |
| 🆓 **Free Enterprise** | **Rullst Nexus** (visual auto-CMS & AI Chat assistant), **Rullst Capital** (Stripe/LemonSqueezy subscriptions boilerplate), **Dual-Engine Frontend** (Hyper Desktop + Omni Multi-Platform Signal Apps), **Rullst Shield** (Wasm WAF & PII masking), **Rullst Foundry** (1-click Cloud Devops Deploy) |
| ⚡ **Linker Hacking** | **Mold/Cranelift Deep Integration** (sub-100ms incremental hot loops), compiler-driven auto-link optimization |

