<div align="center">

<img src="https://avatars.githubusercontent.com/u/228279600?v=4" alt="Neko Ai" width="120" height="120" style="border-radius: 50%;"/>

# 🐱 Neko Ai Dev

**AstrBot Plugin Development Organization**

[![GitHub](https://img.shields.io/badge/GitHub-NekoAiDev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NekoAiDev)
[![AstrBot](https://img.shields.io/badge/AstrBot-Plugin-blue?style=flat-square)](https://github.com/Soulter/AstrBot)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)
[![Plugins](https://img.shields.io/badge/Plugins-2+-orange?style=flat-square)](https://github.com/orgs/NekoAiDev/repositories)

[🌐 中文](./README.md)

</div>

---

## About Us

Neko Ai Dev is an open-source development organization dedicated to building high-quality plugins for the **[AstrBot](https://github.com/Soulter/AstrBot)** framework.

**AstrBot** is an excellent multi-platform chatbot framework supporting QQ, WeChat, Telegram, and more, with an active open-source community and a rich plugin ecosystem. We're committed to contributing practical and fun plugins to this ecosystem, making every AstrBot user's experience better.

### 🎯 Our Mission

> Make AstrBot more powerful, more flexible, and more fun.

We believe great open-source tools should:

- **Be User-Friendly** — No need to spend hours reading docs. Install and go, with clear configs and explicit feedback.
- **Be Rock-Solid** — Every commit is thoroughly tested. Edge cases are handled gracefully. No crashes from unexpected input.
- **Be Open & Transparent** — All code is MIT licensed. Everyone is welcome to read, learn, open issues, and submit PRs.
- **Keep Evolving** — We actively listen to community feedback, iterate continuously, and keep adding new features.

### 📖 Our Story

It all started with a simple need: **managing runaway API calls in group chats**.

As AstrBot grew in popularity, more and more users started using LLM APIs in group chats. But with that came unchecked costs and abuse. No existing rate-limiting plugin could handle complex real-world scenarios — so **astrbot_plugin_api_limiter** was born.

From a simple call counter, it evolved through dozens of versions to include interval limiting, quiet hours, whitelists, time-based policies, per-group quotas, and more. Today, it's one of the most comprehensive API rate limiting solutions on the AstrBot Plugin Marketplace.

Along the way, we noticed the AstrBot community was missing handy utility tools — IP lookups, random draws, trending topic searches, and more. That led us to build **astrbot_plugin_qq_toolbox**, bundling 20+ useful commands into a single plugin so users only need one install for a full toolkit.

The name **Neko Ai Dev** reflects our values: "Neko" (cat) represents the fun and warmth we bring to open source, "Ai" stands for our commitment to the AI era, and "Dev" is our developer roots. We aim to create value for the community — even if it's just a small convenience.

### 🚀 Why Choose Our Plugins?

- ✅ Published on the [AstrBot Plugin Marketplace](https://plugins.astrbot.app) — one-click install, no manual setup
- ✅ Comprehensive documentation and README in both Chinese and English
- ✅ Full GitHub Actions automation — auto issue triage, PR checks, and code linting
- ✅ Actively maintained with timely bug fixes and stable version iterations
- ✅ Advanced features like per-group quotas and time-based policies for complex use cases

---

## 📦 Projects

### [astrbot_plugin_api_limiter](https://github.com/NekoAiDev/astrbot_plugin_api_limiter)

<img src="https://img.shields.io/github/v/release/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Release"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Forks"/></a>

**API Rate Limiter** — A comprehensive rate limiting plugin for AstrBot that helps you manage API call frequency and prevent abuse. Perfect for metered APIs like LLMs, translation services, and more.

**Typical Use Cases:**

- 🤖 **LLM Chat Rate Limiting** — Prevent users from spamming AI chat in groups and keep API costs under control
- 🌐 **Translation API Control** — Allocate daily translation quotas per user/group for fair distribution
- 🔍 **Search API Management** — Manage rate-limited APIs like web search and image search
- 📊 **Multi-Group Differentiation** — Different quotas for different groups; VIP groups get more relaxed limits

**Core Features:**

| Feature | Description |
|---------|-------------|
| ⏱ Interval Limiting | Control the minimum time between consecutive API calls |
| 🔢 Count Limiting + Cooldown Reset | Set daily/hourly quotas that automatically reset after cooldown |
| 🌙 Quiet Hours | Automatically disable API calls during specified time periods |
| 📋 Whitelist & Blacklist | Fine-grained control over which users/groups are affected, admin exempt |
| 🕐 Time-Based Policies | Apply different rate limits for different time periods |
| 🔔 Over-Limit Reminders | Send friendly notifications when users approach or exceed limits |
| 👥 Per-Group Quotas | Each group chat has its own independent rate limit config |
| 📊 Usage Logging & Export | Track all API calls with exportable logs for analysis |
| 🔄 Admin Reset Commands | Reset user or group counters at any time |

> 📌 Available on the [AstrBot Plugin Marketplace](https://plugins.astrbot.app). Current version: **v2.4.5**. Continuously updated.

---

### [astrbot_plugin_qq_toolbox](https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox)

<img src="https://img.shields.io/badge/Version-1.0.0-9cf?style=flat-square" alt="Version"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_qq_toolbox?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_qq_toolbox?style=flat-square" alt="Forks"/></a>

**QQ Toolbox** — An all-in-one utility plugin packed with 20+ commands across entertainment, queries, content generation, and group management. Spice up your group chat experience!

**Feature Categories:**

| Category | Commands | Description |
|----------|----------|-------------|
| 🎮 Entertainment | 10+ | Fun group chat mini-games, random draws, quizzes, and more |
| 🔍 Utility Queries | 5+ | Weather, trending topics, IP lookup, and practical tools |
| ✍️ Content Generation | 4+ | AI-powered copywriting, image generation, and more |
| ⚙️ Group Management | 2+ | Admin tools for managing group chat settings |
| 🔄 Auto-Reply | 1 | Configurable automatic message repetition |

> 📌 Development complete. Coming soon to the [AstrBot Plugin Marketplace](https://plugins.astrbot.app).

---

## 🛠 Tech Stack

| Technology | Usage | Details |
|------------|-------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Plugin Development | Python 3.10+, type annotations |
| ![AstrBot](https://img.shields.io/badge/AstrBot_Framework-blue?style=flat-square) | Bot Framework | Based on official AstrBot plugin spec |
| ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) | CI/CD Automation | Auto issue triage, PR checks, code lint |
| ![ruff](https://img.shields.io/badge/ruff-Linter-yellow?style=flat-square) | Code Quality | High-performance Python linter & formatter |
| ![MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square) | License | All plugins under MIT license |

---

## 📜 Development Standards

We follow these standards to ensure code quality:

- **Versioning** — [Semantic Versioning](https://semver.org/) (SemVer)
  - `MAJOR.MINOR.PATCH` (e.g., `2.4.5`)
  - Bug fix → PATCH +1
  - New feature → MINOR +1
  - Major rewrite → MAJOR +1
- **Git Commits** — [Conventional Commits](https://www.conventionalcommits.org/)
  - `feat:` new feature / `fix:` bug fix / `docs:` documentation / `refactor:` refactoring / `chore:` maintenance
- **Code Style** — Automatically checked with ruff, CI runs on every PR
- **Issue Management** — Auto-labeled (bug / enhancement / question / documentation / triage)
- **Release Process** — Every update must: push to GitHub + publish GitHub Release + update plugin marketplace

---

## 🗺 Roadmap

We're actively planning and developing the following:

- [x] 🔧 API Rate Limiter v1.0 — Basic rate limiting features
- [x] ⚡ API Limiter v2.0 — Per-group quotas, time-based policies
- [x] 🎮 QQ Toolbox — 20+ multi-function commands
- [x] 🤖 GitHub Actions Automation — Issue triage, PR checks, code lint
- [x] 🌐 Bilingual Documentation (Chinese & English)
- [ ] 📊 Usage Statistics Dashboard (planned)
- [ ] 🔌 More Platform Adapters (planned)
- [ ] 🧩 More Utility Plugins (continuously planning)

---

## 🤝 Contributing

We welcome contributions in any form! Whether you want to:

- 🐛 Submit a [bug report](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) or feature request
- 🔀 Open a Pull Request to fix issues or add features
- 📖 Improve documentation or translations
- ⭐ Give us a Star on GitHub

**How to Contribute:**

1. Fork the repository you want to contribute to
2. Create a feature branch: `git checkout -b feat/amazing-feature`
3. Commit your changes: `git commit -m "feat: add some amazing feature"`
4. Push to the branch: `git push origin feat/amazing-feature`
5. Open a Pull Request

Every bit of support motivates us to keep building!

---

## ❓ FAQ

<details>
<summary><b>🔧 How do I install the plugins?</b></summary>

We recommend installing via the [AstrBot Plugin Marketplace](https://plugins.astrbot.app) with one click. You can also download the source code from GitHub Releases and manually place it in the AstrBot plugin directory.
</details>

<details>
<summary><b>🐛 What should I do if I find a bug?</b></summary>

Please submit a bug report on the [Issues](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) page of the corresponding repository. Include the plugin version, AstrBot version, steps to reproduce, and relevant logs. Our automation system will automatically categorize and process it.
</details>

<details>
<summary><b>💡 Can I suggest a new feature?</b></summary>

Absolutely! Open an Issue with a title starting with "feature" or "enhancement". We'll evaluate it and add it to our development roadmap if it aligns with our goals.
</details>

<details>
<summary><b>📋 Which platforms are supported?</b></summary>

Our plugins are built on the AstrBot framework and theoretically support all of AstrBot's message platform adapters, including but not limited to QQ, WeChat, and Telegram.
</details>

---

## 📮 Contact

| Method | Info |
|--------|------|
| **Organization Owner** | [xiaohondan](https://github.com/xiaohondan) |
| **Email** | xiaohondan@skymail.ink |
| **GitHub** | [NekoAiDev](https://github.com/NekoAiDev) |
| **Plugin Marketplace** | [AstrBot Plugin Marketplace](https://plugins.astrbot.app) |

---

<div align="center">

**Made with ❤️ by Neko Ai Dev**

*If you like our plugins, give them a ⭐ on GitHub!*

</div>
