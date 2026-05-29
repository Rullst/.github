<p align="center">
  <img src="https://github.com/venelouis/Rullst/blob/main/Rullst.png" alt="Rullst Logo" width="400">
</p>

# Rullst - 📜🦀🌐🤖🚀
### *"Rust for those who want to build, not suffer."*

> 📖 **[See all the changes in our Changelog!](https://github.com/venelouis/Rullst/blob/main/CHANGELOG.md)**  
> 📚 **[Read the Official Documentation!](https://venelouis.github.io/Rullst/)**  
> 📦 **[View on Crates.io!](https://crates.io/crates/rullst)**

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Built with: Axum & Rust Eloquent](https://img.shields.io/badge/Stack-Axum%20%7C%20Rust%20Eloquent-blue)

**Rullst** (Rust + Fullstack) is an opinionated, developer-first full-stack web framework for Rust, obsessively designed for **Emotional Productivity**. 

## 🏆 Everything You Need, Built-In

Rullst ships with **8 completed milestones** covering every layer of modern web development:

| Category | Features |
|---|---|
| 🛠️ **CLI & DX** | `cargo rullst new` wizard, `make:controller`, `make:model -m`, `make:middleware`, `make:worker`, `generate:openapi`, `cargo rullst upgrade` (self-healing) |
| 🗄️ **Database** | Active Record ORM, Migrations (`db:migrate`, `db:rollback`, `db:status`), Seeders & Factories, HasMany / BelongsTo / BelongsToMany, Eager Loading |
| 🔒 **Auth & Security** | Argon2 hashing, JWT & Cookie sessions, CSRF protection, Social OAuth (Google, GitHub, Facebook, Twitter via `rust-socialite`), `cargo rullst auth` scaffolding |
| ⚡ **Frontend** | HTMX first-class support, TailwindCSS auto-integration, partial template rendering, **Rullst Live** (Phoenix LiveView-inspired server-driven UI), **Wasm Islands** (`#[client_component]`) |
| 📦 **Production** | Queue (SQLite/Redis), Cache (Memory/Redis), Task Scheduler (Cron), Docker multi-stage builds, **Rullst Horizon** dashboard |
| 🏢 **Enterprise** | Declarative Validation, Mailer (SMTP/Resend/SendGrid), Storage (Local/S3/R2), WebSockets, Multi-Tenancy, Feature Flags, E2E Testing |
| 🚀 **Unfair Advantage** | **AI Core** (`rullst::ai` — OpenAI/Gemini/Anthropic/Ollama + RAG), **Rullst Studio** (visual DB GUI), **Self-Healing Error Console** (AI auto-fix), **Hot Reloading via `dylib`** |
| 🌍 **Edge & Data** | Edge Runtime (Cloudflare Workers, Fastly, AWS Lambda@Edge), Zero-Config Distributed SQLite Replication (Turso/D1), Autonomous Upgrades |

---


## ⚡ Get Started in 10 Seconds

Scaffold a fully operational application with our interactive CLI wizard!

```bash
# 1. Run the interactive CLI scaffolding tool
cargo rullst new

# The wizard will prompt you:
# 🚀 App name? (no spaces allowed) -> my-app
# 🏗️ What would you like to build? -> Full-Stack Web App (SaaS, Portfolio, Blog) / REST API
# 🔥 Enable Hot Reloading by default? -> Yes / No
# 🗄️ Will your project need a Data Base? -> Yes / No
# 💾 Select a DB Provider -> Sqlite / Postgres / MySQL/MariaDB

# 2. Enter the project folder
cd my-app

# 3. Start your high-performance full-stack app immediately!
cargo run

# 🔥 Or enable instant Hot Reloading (no server restart!):
HOT_RELOAD=1 cargo run
```


## 🔥 Hot Reloading (Zero Downtime Dev Loop)

Rullst supports **Hot Reloading via Dynamic Linking** — change your routes, handlers, and templates, and see the changes reflected **instantly** without restarting the server or losing connections:

```bash
# Start your app in hot-reload mode
HOT_RELOAD=1 cargo run

# ⚡ Edit any handler in src/ → Rullst detects the change
# 🔄 Background recompilation of the cdylib
# 🚀 Router hot-swapped atomically — zero downtime!
```

## 📝 License

Distributed under the MIT License. See `LICENSE` for more details.
