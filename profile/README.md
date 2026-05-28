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
