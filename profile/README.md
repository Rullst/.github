<p align="center">
  <img src="https://github.com/venelouis/Rullst/blob/main/Rullst.png" alt="Rullst Logo" width="400">
</p>

# Rullst - 📜🦀🌐🤖🚀
### *"Rust for those who want to build, not suffer."*

> 📖 **[See all the changes in our Changelog!](./CHANGELOG.md)**  
> 📚 **[Read the Official Documentation!](https://venelouis.github.io/Rullst/)**  
> 📦 **[View on Crates.io!](https://crates.io/crates/rullst)**

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Built with: Axum & Rust Eloquent](https://img.shields.io/badge/Stack-Axum%20%7C%20Rust%20Eloquent-blue)

**Rullst** (Rust + Fullstack) is an opinionated, developer-first full-stack web framework for Rust, obsessively designed for **Emotional Productivity**. 

It was created to solve the biggest problem in the Rust web ecosystem: the high barrier of entry that turns web programming into a PhD research on compiler design. We believe you should spend your energy building your business, not fighting borrow checkers and manual routing setups.

---

## 💡 The Rullst Manifesto

> *"Most Rust frameworks treat the web developer like a compiler engineer. Rullst treats the developer like someone who wants to build awesome products at lightning speed."*

In the current ecosystem, to write a simple CRUD, you are forced to glue dozens of crates together, manually map nested routing trees, write verbose ORMs requiring multiple structs, and continuously clone variables inside dynamic HTML templates just to satisfy the borrow checker.

Rullst redefines this experience. We offer an integrated, cohesive developer experience that brings the sweetness and iteration speed of **Laravel and Next.js** together with the Formula 1 performance and military-grade safety of **Rust, Axum, and Hyper**:

* **No More Frankenstein setups:** A single cohesive framework managing your server (Axum), your database (`rust-eloquent`), and your HTML rendering.
* **No More Borrow Checker fights in UI:** Our compile-time JSX-like `html!` macro processes pure elements on the server (SSR). It generates optimized string-builders directly at compile time. It's blazing fast, safe, and SEO-friendly by default.
* **First-Class Active Record ORM:** Native integration with your **`rust-eloquent`** package. Interacting with databases is as intuitive as `user.save()`.
* **AI-Native Engineering & AI-Friendly:** Designed from the ground up for modern pair-programming. Strict type-safety, zero dynamic runtime magic, automatic `.ai-rules` scaffolding, and structured schemas prevent AI agent hallucinations and allow instant compiler self-correction.


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
