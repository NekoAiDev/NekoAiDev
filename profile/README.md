<div align="center">

<img src="https://avatars.githubusercontent.com/u/228279600?v=4" alt="Neko Ai" width="120" height="120" style="border-radius: 50%;"/>

# 🐱 Neko Ai Dev

**AstrBot 插件开发组织**

[![GitHub](https://img.shields.io/badge/GitHub-NekoAiDev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NekoAiDev)
[![AstrBot](https://img.shields.io/badge/AstrBot-Plugin-blue?style=flat-square)](https://github.com/Soulter/AstrBot)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)
[![Plugins](https://img.shields.io/badge/Plugins-2+-orange?style=flat-square)](https://github.com/orgs/NekoAiDev/repositories)

[🌐 English](./README.en.md)

</div>

---

## 关于我们

Neko Ai Dev 是一个专注于为 **[AstrBot](https://github.com/Soulter/AstrBot)** 框架开发高质量插件的开源组织。

**AstrBot** 是一款优秀的多平台聊天机器人框架，支持 QQ、微信、Telegram 等多种消息平台，拥有活跃的开源社区和丰富的插件生态。我们致力于为这个生态贡献实用、有趣的插件，让每一位 AstrBot 用户都能享受到更好的机器人体验。

### 🎯 我们的使命

> 让 AstrBot 更强大、更灵活、更好玩。

我们相信，好的开源工具应该做到以下几点：

- **易用至上** — 不需要翻文档折腾半天，安装即用，配置清晰，反馈明确
- **稳定可靠** — 每一次提交都经过充分测试，优雅处理各种边界情况，不会因为异常输入而崩溃
- **开源透明** — 所有代码 MIT 协议开源，欢迎任何人查看、学习、提 Issue、提交 PR
- **持续进化** — 积极倾听社区反馈，持续迭代更新，不断添加新功能

### 📖 我们的故事

一切始于一个简单的需求：**管理群聊中泛滥的 API 调用**。

当 AstrBot 逐渐流行，越来越多的用户开始在群聊中使用大模型 API，但随之而来的是成本失控和滥用问题。市面上没有一款现成的限频插件能够满足复杂场景的需求 —— 于是，**astrbot_plugin_api_limiter** 诞生了。

从最初简单的次数限制，到后来逐步加入间隔限制、安静时段、白名单、分时段策略、群聊独立配额…… 经过数十个版本的迭代，它已经成为 AstrBot 插件市场中最完善的 API 限频解决方案之一。

在开发过程中，我们发现 AstrBot 社区还缺少一些实用的小工具 —— 比如 IP 查询、随机抽签、热搜获取等等。于是我们又开始构建 **astrbot_plugin_qq_toolbox**，把各种零散的功能整合到一个插件中，让用户只需要安装一个包就能获得 20+ 实用指令。

**Neko Ai Dev** 这个组织的名字，「Neko」代表猫咪（也是我们对有趣和温暖的开源精神的追求），「Ai」代表我们探索 AI 时代的决心，「Dev」则是我们作为开发者的初心。我们希望用代码为社区创造一点价值，哪怕只是一点小小的便利。

### 🚀 为什么选择我们的插件？

- ✅ 已上架 [AstrBot 插件市场](https://plugins.astrbot.app)，一键安装，无需手动配置
- ✅ 详尽的中文文档和 README，降低上手门槛
- ✅ 完善的 GitHub Actions 自动化 —— Issue 自动分类、PR 自动检查、代码风格自动审查
- ✅ 活跃维护，Bug 修复及时，版本迭代稳定
- ✅ 群聊独立配额、分时段策略等高级功能，满足复杂使用场景

---

## 📦 项目展示

### [astrbot_plugin_api_limiter](https://github.com/NekoAiDev/astrbot_plugin_api_limiter)

<img src="https://img.shields.io/github/v/release/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Release"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Forks"/></a>

**API 调用限频器** — 一款全面的 AstrBot 限频插件，帮助你管理 API 调用频率，防止滥用。适用于接入大模型 API、翻译 API 等按量计费接口的场景，有效控制成本。

**典型使用场景：**

- 🤖 **大模型聊天限频** — 限制群聊中 AI 聊天的调用频率，避免用户刷屏和 API 费用失控
- 🌐 **翻译 API 控制** — 按用户/群聊分配每日翻译次数，确保额度合理分配
- 🔍 **搜索 API 管理** — 控制网页搜索、图片搜索等按次计费 API 的使用频率
- 📊 **多群聊差异化** — 不同群聊设置不同配额，VIP 群聊享受更宽松的限制

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
- **发布流程** — 每次更新必须：提交 GitHub + 发布 GitHub Release + 更新插件市场

---

## 🗺 项目路线图

我们正在积极规划和开发以下内容：

- [x] 🔧 API 调用限频器 v1.0 — 基础限频功能
- [x] ⚡ API 限频器 v2.0 — 群聊独立配额、分时段策略
- [x] 🎮 QQ 功能工具箱 — 20+ 多功能指令
- [x] 🤖 GitHub Actions 自动化 — Issue 分类、PR 检查、代码 Lint
- [x] 🌐 中英文双语文档
- [ ] 📊 使用数据统计面板（计划中）
- [ ] 🔌 更多平台适配（计划中）
- [ ] 🧩 更多实用插件（持续规划中）

---

## 🤝 参与贡献

欢迎各种形式的贡献！无论你是想：

- 🐛 提交 [Bug 报告](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) 或功能建议
- 🔀 提交 Pull Request 修复问题或添加新功能
- 📖 改进文档或翻译
- ⭐ 在 GitHub 上给我们一个 Star

**贡献指南：**

1. Fork 你想要贡献的仓库
2. 创建特性分支：`git checkout -b feat/amazing-feature`
3. 提交更改：`git commit -m "feat: 添加某个功能"`
4. 推送到分支：`git push origin feat/amazing-feature`
5. 发起 Pull Request

你的每一份支持都是我们持续开发的动力！

---

## ❓ 常见问题

<details>
<summary><b>🔧 如何安装插件？</b></summary>

推荐通过 [AstrBot 插件市场](https://plugins.astrbot.app) 一键安装。也可以从 GitHub Release 下载源码后手动放入 AstrBot 插件目录。
</details>

<details>
<summary><b>🐛 遇到 Bug 怎么办？</b></summary>

请前往对应仓库的 [Issues](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) 页面提交 Bug 报告，附上插件版本、AstrBot 版本、复现步骤和相关日志。我们的自动化系统会自动分类和处理。
</details>

<details>
<summary><b>💡 我想提功能建议？</b></summary>

欢迎！直接在 Issues 中提交，标题以"建议"或"enhancement"开头即可。我们会评估并排入开发计划。
</details>

<details>
<summary><b>📋 插件支持哪些平台？</b></summary>

我们的插件基于 AstrBot 框架开发，理论上支持 AstrBot 的所有消息平台适配器，包括但不限于 QQ、微信、Telegram 等。
</details>

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
