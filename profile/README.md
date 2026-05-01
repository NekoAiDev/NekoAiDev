<div align="center">

<img src="https://avatars.githubusercontent.com/u/228279600?v=4" alt="Neko Ai" width="120" height="120" style="border-radius: 50%;"/>

# 🐱 Neko Ai Dev

**AstrBot Plugin Development Organization**

[![GitHub](https://img.shields.io/badge/GitHub-NekoAiDev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NekoAiDev)
[![AstrBot](https://img.shields.io/badge/AstrBot-Plugin-blue?style=flat-square)](https://github.com/Soulter/AstrBot)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)
[![Plugins](https://img.shields.io/badge/Plugins-2+-orange?style=flat-square)](https://github.com/orgs/NekoAiDev/repositories)

</div>

---

<a name="zh"></a>

| 🌐 语言 | [中文](#zh) | [English](#en) |
|:---:|:---:|:---:|

## 关于我们

Neko Ai Dev 是一个专注于为 [AstrBot](https://github.com/Soulter/AstrBot) 框架开发高质量插件的开源组织。

**AstrBot** 是一款优秀的多平台聊天机器人框架，支持 QQ、微信、Telegram 等多种消息平台。我们致力于为这个生态贡献实用、有趣的插件，让每一位 AstrBot 用户都能享受到更好的机器人体验。

### 🎯 我们的使命

> 让 AstrBot 更强大、更灵活、更好玩。

我们相信，好的开源工具应该做到以下几点：

- **易用至上** — 不需要翻文档折腾半天，安装即用，配置清晰，反馈明确
- **稳定可靠** — 每一次提交都经过充分测试，优雅处理各种边界情况，不会因为异常输入而崩溃
- **开源透明** — 所有代码 MIT 协议开源，欢迎任何人查看、学习、提 Issue、提交 PR
- **持续进化** — 积极倾听社区反馈，持续迭代更新，不断添加新功能

### 🚀 为什么选择我们的插件？

- ✅ 已上架 [AstrBot 插件市场](https://plugins.astrbot.app)，一键安装，无需手动配置
- ✅ 详尽的中文文档和 README，降低上手门槛
- ✅ 完善的 GitHub Actions 自动化 —— Issue 自动分类、PR 自动检查、代码风格自动审查
- ✅ 活跃维护，Bug 修复及时，版本迭代稳定
- ✅ 群聊独立配额、分时段策略等高级功能，满足复杂使用场景

---

## 📦 项目

### [astrbot_plugin_api_limiter](https://github.com/NekoAiDev/astrbot_plugin_api_limiter)

<img src="https://img.shields.io/github/v/release/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Release"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Forks"/></a>

**API 调用限频器** — 一款全面的 AstrBot 限频插件，帮助你管理 API 调用频率，防止滥用。适用于接入大模型 API、翻译 API 等按量计费接口的场景，有效控制成本。

**核心功能：**

| 功能 | 说明 |
|------|------|
| ⏱ 调用间隔限制 | 控制每次 API 调用之间的最短间隔时间 |
| 🔢 次数限制 + 冷却重开 | 设置每日/每小时调用配额，到达上限后自动冷却重置 |
| 🌙 安静时段 | 在指定时间段（如深夜）自动禁用 API 调用 |
| 📋 白名单 & 黑名单 | 精细控制哪些用户/群聊受限，管理员可豁免 |
| 🕐 分时段限频 | 不同时间段设置不同的频率限制（如白天宽松、晚间严格） |
| 🔔 超额提醒 | 用户接近或超出限制时发送友好的提醒消息 |
| 👥 群聊独立配额 | 每个群聊拥有独立的限频配置，互不干扰 |
| 📊 使用日志 & 导出 | 追踪所有 API 调用记录，支持导出日志分析 |
| 🔄 管理员重置指令 | 管理员可随时重置用户或群聊的调用计数器 |

> 📌 已上架 [AstrBot 插件市场](https://plugins.astrbot.app)，版本 **v2.4.5**，持续更新中。

---

### [astrbot_plugin_qq_toolbox](https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox)

<img src="https://img.shields.io/badge/Version-1.0.0-9cf?style=flat-square" alt="Version"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_qq_toolbox?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_qq_toolbox?style=flat-square" alt="Forks"/></a>

**QQ 功能工具箱** — 一款集娱乐、查询、内容生成和群管理于一体的多功能插件，包含 20+ 指令，让你的群聊生活更加丰富多彩。

**功能分类：**

| 分类 | 指令数 | 说明 |
|------|--------|------|
| 🎮 娱乐趣味 | 10+ | 群聊互动小游戏、随机抽签、趣味问答等 |
| 🔍 实用查询 | 5+ | 天气、热搜、IP 查询等实用工具 |
| ✍️ 内容生成 | 4+ | AI 驱动的文案创作、图片生成等 |
| ⚙️ 群聊管理 | 2+ | 管理员专用群聊设置工具 |
| 🔄 自动复读 | 1 | 可配置的自动消息复读功能 |

> 📌 已开发完成，即将上架 [AstrBot 插件市场](https://plugins.astrbot.app)。

---

## 🛠 技术栈

| 技术 | 用途 | 说明 |
|------|------|------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | 插件开发 | Python 3.10+，类型注解 |
| ![AstrBot](https://img.shields.io/badge/AstrBot_Framework-blue?style=flat-square) | Bot 框架 | 基于 AstrBot 官方插件规范 |
| ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) | CI/CD 自动化 | Issue 自动分类、PR 检查、代码 Lint |
| ![ruff](https://img.shields.io/badge/ruff-Linter-yellow?style=flat-square) | 代码检查 | 高性能 Python Linter & Formatter |
| ![MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square) | 开源协议 | 所有插件均采用 MIT 协议 |

---

## 📜 开发规范

我们遵循以下开发规范，确保代码质量：

- **版本管理** — 遵循 [语义化版本](https://semver.org/lang/zh-CN/)（SemVer）
  - `主版本.次版本.修订号`（如 `2.4.5`）
  - Bug 修复 → 修订号 +1
  - 新功能 → 次版本 +1
  - 大重构 → 主版本 +1
- **Git Commit** — 使用约定式提交（Conventional Commits）
  - `feat:` 新功能 / `fix:` Bug 修复 / `docs:` 文档 / `refactor:` 重构 / `chore:` 维护
- **代码风格** — 通过 ruff 自动检查，PR 提交时自动运行 CI
- **Issue 管理** — 自动标签分类（bug / enhancement / question / documentation / triage）

---

## 🤝 参与贡献

欢迎各种形式的贡献！无论你是想：

- 🐛 提交 [Bug 报告](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) 或功能建议
- 🔀 提交 Pull Request 修复问题或添加新功能
- 📖 改进文档或翻译
- ⭐ 在 GitHub 上给我们一个 Star

你的每一份支持都是我们持续开发的动力！

---

## 📮 联系我们

| 方式 | 信息 |
|------|------|
| **组织拥有者** | [xiaohondan](https://github.com/xiaohondan) |
| **邮箱** | xiaohondan@skymail.ink |
| **GitHub** | [NekoAiDev](https://github.com/NekoAiDev) |
| **插件市场** | [AstrBot 插件市场](https://plugins.astrbot.app) |

---

<div align="center">

**用 ❤️ 打造 | Neko Ai Dev**

*喜欢我们的插件？在 GitHub 上给个 ⭐ 吧！*

</div>

---
---
---

<a name="en"></a>

| 🌐 Language | [中文](#zh) | [English](#en) |
|:---:|:---:|:---:|

## About Us

Neko Ai Dev is an open-source development organization dedicated to building high-quality plugins for the **[AstrBot](https://github.com/Soulter/AstrBot)** framework.

**AstrBot** is an excellent multi-platform chatbot framework supporting QQ, WeChat, Telegram, and more. We're committed to contributing practical and fun plugins to this ecosystem, making every AstrBot user's experience better.

### 🎯 Our Mission

> Make AstrBot more powerful, more flexible, and more fun.

We believe great open-source tools should:

- **Be User-Friendly** — No need to spend hours reading docs. Install and go, with clear configs and explicit feedback.
- **Be Rock-Solid** — Every commit is thoroughly tested. Edge cases are handled gracefully. No crashes from unexpected input.
- **Be Open & Transparent** — All code is MIT licensed. Everyone is welcome to read, learn, open issues, and submit PRs.
- **Keep Evolving** — We actively listen to community feedback, iterate continuously, and keep adding new features.

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

---

## 🤝 Contributing

We welcome contributions in any form! Whether you want to:

- 🐛 Submit a [bug report](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) or feature request
- 🔀 Open a Pull Request to fix issues or add features
- 📖 Improve documentation or translations
- ⭐ Give us a Star on GitHub

Every bit of support motivates us to keep building!

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
