<div align="center">

<img src="https://avatars.githubusercontent.com/u/228279600?v=4" alt="Neko Ai" width="120" height="120" style="border-radius: 50%;"/>

# Neko Ai

**AstrBot 插件、技术开发组织 | AstrBot Plugins & Tech Development Organization**

[![GitHub](https://img.shields.io/badge/GitHub-NekoAiDev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NekoAiDev)
[![Author](https://img.shields.io/badge/Author-小红蛋-orange?style=flat-square)](https://github.com/xiaohondan)
[![AstrBot](https://img.shields.io/badge/AstrBot-Plugin-blue?style=flat-square)](https://github.com/AstrBotDevs/AstrBot)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)
[![Plugins](https://img.shields.io/badge/Plugins-2+-orange?style=flat-square)](https://github.com/orgs/NekoAiDev/repositories)
[![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)](https://github.com/NekoAiDev/.github/tree/main/profile)
[![Downloads](https://img.shields.io/github/downloads/NekoAiDev/.github/total?style=flat-square&label=Downloads&color=brightgreen)](https://github.com/NekoAiDev/.github/releases)
[![Chat](https://img.shields.io/badge/Chat-%E6%98%BE%E7%9F%B3%E7%9A%84%E7%BC%96%E7%A8%8B%E4%BA%A4%E6%B5%81%E7%BE%A4-red?style=flat-square&logo=tencentqq&logoColor=white)](https://qm.qq.com/q/rFZ3Sxlqa4)
[![Docker Pulls](https://img.shields.io/docker/pulls/soulter/astrbot?style=flat-square&logo=docker&logoColor=white&label=docker%20pulls&color=2496ED)](https://hub.docker.com/r/soulter/astrbot)
[![Marketplace](https://img.shields.io/badge/dynamic/json?style=flat-square&label=Marketplace&color=blue&query=%24.total&url=https%3A%2F%2Fmarket.astrbot.app%2Fapi%2Fplugins%2Fcount)](https://market.astrbot.app)
[![GitHub Stars](https://img.shields.io/github/stars/NekoAiDev/.github?style=flat-square&logo=github&label=G-Star&color=gold)](https://github.com/NekoAiDev/.github/stargazers)
[![Ask DeepWiki - neko-cli](https://deepwiki.com/badge.svg)](https://deepwiki.com/NekoAiDev/neko-cli)
[![Ask DeepWiki - qq_toolbox](https://deepwiki.com/badge.svg)](https://deepwiki.com/NekoAiDev/astrbot_plugin_qq_toolbox)
[![Ask DeepWiki - api_limiter](https://deepwiki.com/badge.svg)](https://deepwiki.com/NekoAiDev/astrbot_plugin_api_limiter)

[🌐 English](https://github.com/NekoAiDev/.github/blob/main/profile/README.en.md)

</div>

---


![break with optifine](https://wsrv.nl/?url=https%3A%2F%2Fimages.teamresourceful.com%2Fu%2F8vCLgK.svg&n=-1)

---

## 📋 目录

- [关于我们](#-关于我们)
- [项目展示](#-项目展示)
- [技术架构](#-技术架构)
- [安全理念](#-安全理念)
- [质量保障](#-质量保障)
- [开发规范](#-开发规范)
- [自动化流程](#-自动化流程)
- [开源文化](#-开源文化)
- [项目路线图](#-项目路线图)
- [版本历史](#-版本历史)
- [社区评价](#-社区评价)
- [未来愿景](#-未来愿景)
- [参与贡献](#-参与贡献)
- [常见问题](#-常见问题)
- [联系我们](#-联系我们)

---

<details>
<summary><h2>📖 关于我们</h2></summary>

Neko Ai 是一个专注于 **[AstrBot](https://github.com/Soulter/AstrBot)** 插件开发与技术探索的开源组织。我们由一群热爱开源、关注用户体验的开发者组成，致力于打造有趣、实用、高质量的开源项目。

**AstrBot** 是一款优秀的多平台聊天机器人框架，支持 QQ、微信、Telegram、飞书、Discord 等多种消息平台，拥有活跃的开源社区和丰富的插件生态。作为 AstrBot 社区的积极参与者，我们不仅开发插件，也在持续贡献文档、分享经验，帮助更多用户和开发者加入这个生态。

### 🔢 关键数据

| 指标 | 数据 |
|------|------|
| 📦 发布插件数 | 2+ |
| 🏪 已上架插件市场 | 1（限频器） |
| 📝 累计版本发布 | 20+ |
| 🔧 总功能点 | 40+ |
| 🤖 CI/CD 自动化 | 3 套 Workflow |
| 📄 支持语言 | 中文 + English |

### 🎯 我们的使命

> 让每一个项目都更强大、更灵活、更好玩。

我们相信，好的开源工具应该做到以下几点：

- **易用至上** — 不需要翻文档折腾半天，安装即用，配置清晰，反馈明确。哪怕你是一个完全不懂代码的普通用户，也能在 5 分钟内完成安装和基本配置
- **稳定可靠** — 每一次提交都经过充分测试，优雅处理各种边界情况，不会因为异常输入而崩溃。我们使用 ruff 进行代码质量检查，GitHub Actions 确保每次提交都通过自动化测试
- **开源透明** — 所有代码 MIT 协议开源，欢迎任何人查看、学习、提 Issue、提交 PR。我们相信开源的力量，也相信透明的开发流程能建立更强的社区信任
- **持续进化** — 积极倾听社区反馈，持续迭代更新，不断添加新功能。每个版本都经过仔细规划，确保在稳定性和创新之间找到最佳平衡
- **社区驱动** — 我们的开发方向由社区需求决定。每一个功能建议、每一份 Bug 报告、每一次讨论，都在塑造着我们插件的未来形态

<details>
<summary><b>📖 我们的故事</b></summary>

一切始于一个简单的需求：**管理群聊中泛滥的 API 调用**。

当 AstrBot 逐渐流行，越来越多的用户开始在群聊中使用大模型 API，但随之而来的是成本失控和滥用问题。有的用户一天能刷掉几百次 API 调用，管理员苦不堪言。市面上没有一款现成的限频插件能够满足复杂场景的需求 —— 需要支持多群聊差异化、分时段策略、黑名单管理、超额提醒…… 于是，**astrbot_plugin_api_limiter** 诞生了。

从最初简单的次数限制，到后来逐步加入间隔限制、安静时段、白名单、分时段策略、群聊独立配额…… 经过数十个版本的迭代，它已经成为 AstrBot 插件市场中最完善的 API 限频解决方案之一。我们从 v1.0.0 一路走到 v2.4.5，每一次版本更新都凝聚着社区反馈和用户需求。

在开发过程中，我们发现 AstrBot 社区还缺少一些实用的小工具 —— 比如 IP 查询、随机抽签、热搜获取等等。用户们经常在群里问"有没有查天气的指令"、"能不能加个抽签功能"—— 于是我们又开始构建 **astrbot_plugin_qq_toolbox**，把各种零散的功能整合到一个插件中，让用户只需要安装一个包就能获得 20+ 实用指令。一个插件解决所有日常小需求，这就是我们的设计理念。

**Neko Ai** 这个组织的名字，「Neko」代表猫咪（也是我们对有趣和温暖的开源精神的追求），「Ai」代表我们探索 AI 时代的决心，「Dev」则是我们作为开发者的初心。我们希望用代码为社区创造一点价值，哪怕只是一点小小的便利。

从一个人写代码，到建立组织、完善自动化流程、上架插件市场、撰写双语文档…… 这段旅程充满了挑战和收获。感谢 AstrBot 社区和每一位用户的支持，让我们走到了今天。

</details>

<details>
<summary><b>🏗️ 组织架构</b></summary>

Neko Ai 采用轻量化的组织管理模式：

- **组织拥有者**：[xiaohondan](https://github.com/xiaohondan) — 负责整体规划、代码开发和社区维护
- **自动化系统**：GitHub Actions 承担 Issue 分类、PR 检查、代码审查等重复性工作，让开发者专注于创造
- **开源协作**：欢迎任何感兴趣的开发者通过 Fork + PR 的方式参与贡献

</details>

### 🚀 为什么选择我们的插件？

- ✅ 已上架 [AstrBot 插件市场](https://plugins.astrbot.app)，一键安装，无需手动配置
- ✅ 详尽的中文文档和 README，降低上手门槛，新手友好
- ✅ 完善的 GitHub Actions 自动化 —— Issue 自动分类、PR 自动检查、代码风格自动审查，确保代码质量
- ✅ 活跃维护，Bug 修复及时，版本迭代稳定，平均每个版本开发周期不超过一周
- ✅ 群聊独立配额、分时段策略等高级功能，满足复杂使用场景
- ✅ MIT 开源协议，代码完全透明，可自由修改和二次开发
- ✅ 双语文档支持（中文 + English），服务全球用户

</details>

---

<details>
<summary><h2>📦 项目展示</h2></summary>

### [astrbot_plugin_api_limiter](https://github.com/NekoAiDev/astrbot_plugin_api_limiter)

<img src="https://img.shields.io/github/v/release/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Release"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Forks"/></a> <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" alt="Status"/>

**API 调用限频器** — 一款全面的 AstrBot 限频插件，帮助你管理 API 调用频率，防止滥用。适用于接入大模型 API、翻译 API 等按量计费接口的场景，有效控制成本。

这是我们的旗舰插件，也是 AstrBot 插件市场上最受欢迎的限频解决方案之一。从 v1.0 到 v2.4.5，我们持续打磨每一个细节。

<details>
<summary><b>📋 详细信息</b></summary>

**典型使用场景：**

- 🤖 **大模型聊天限频** — 限制群聊中 AI 聊天的调用频率，避免用户刷屏和 API 费用失控。支持设置每日总次数、每小时次数、最小间隔时间等多维度限制
- 🌐 **翻译 API 控制** — 按用户/群聊分配每日翻译次数，确保额度合理分配。避免个别用户占用过多翻译配额
- 🔍 **搜索 API 管理** — 控制网页搜索、图片搜索等按次计费 API 的使用频率。让有限的 API 额度服务更多人
- 📊 **多群聊差异化** — 不同群聊设置不同配额，VIP 群聊享受更宽松的限制。每个群聊拥有完全独立的配置
- 🌙 **深夜自动休眠** — 在深夜时段自动禁用 API 调用，既节省成本又避免影响他人休息
- 🏢 **企业/团队管理** — 白名单机制让管理员不受限制，黑名单机制精确封禁滥用用户

**核心功能：**

| 功能 | 说明 |
|------|------|
| ⏱ 调用间隔限制 | 控制每次 API 调用之间的最短间隔时间，防止高频刷屏 |
| 🔢 次数限制 + 冷却重开 | 设置每日/每小时调用配额，到达上限后自动冷却重置 |
| 🌙 安静时段 | 在指定时间段（如深夜）自动禁用 API 调用 |
| 📋 白名单 & 黑名单 | 精细控制哪些用户/群聊受限，管理员可豁免 |
| 🕐 分时段限频 | 不同时间段设置不同的频率限制（如白天宽松、晚间严格） |
| 🔔 超额提醒 | 用户接近或超出限制时发送友好的提醒消息 |
| 👥 群聊独立配额 | 每个群聊拥有独立的限频配置，互不干扰 |
| 📊 使用日志 & 导出 | 追踪所有 API 调用记录，支持导出日志分析 |
| 🔄 管理员重置指令 | 管理员可随时重置用户或群聊的调用计数器 |

**快速开始：**

```
# 1. 在 AstrBot 插件市场搜索 "api_limiter" 一键安装
# 2. 在 AstrBot 配置文件中设置你的限频规则
# 3. 重启 AstrBot，限频器自动生效
```

</details>

> 📌 已上架 [AstrBot 插件市场](https://plugins.astrbot.app)，版本 **v2.4.5**，持续更新中。

---

### [astrbot_plugin_qq_toolbox](https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox)

<img src="https://img.shields.io/badge/Version-1.0.0-9cf?style=flat-square" alt="Version"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_qq_toolbox?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_qq_toolbox?style=flat-square" alt="Forks"/></a> <img src="https://img.shields.io/badge/Status-Development-yellow?style=flat-square" alt="Status"/>

**QQ 功能工具箱** — 一款集娱乐、查询、内容生成和群管理于一体的多功能插件，包含 20+ 指令，让你的群聊生活更加丰富多彩。

一个插件 = 一个完整的群聊工具箱。不需要安装一堆零散的插件，工具箱为你整合了日常群聊所需的所有功能。

<details>
<summary><b>📋 详细信息</b></summary>

**功能分类：**

| 分类 | 指令数 | 说明 |
|------|--------|------|
| 🎮 娱乐趣味 | 10+ | 群聊互动小游戏、随机抽签、趣味问答、幸运转盘等 |
| 🔍 实用查询 | 5+ | 天气查询、热搜获取、IP 归属地查询、汇率换算等 |
| ✍️ 内容生成 | 4+ | AI 驱动的文案创作、图片生成、文案润色、随机名言等 |
| ⚙️ 群聊管理 | 2+ | 管理员专用的群聊设置和管理工具 |
| 🔄 自动复读 | 1 | 可配置的自动消息复读功能，用于活跃群聊氛围 |

**亮点功能：**

- 🎰 **随机抽签** — 帮群友做出选择困难的决定
- 🌤 **天气查询** — 输入城市名，秒出实时天气
- 🔥 **热搜获取** — 一键获取微博/百度热搜，紧跟热点
- 🌐 **IP 查询** — 查询 IP 归属地和运营商信息
- 🎨 **图片生成** — 输入描述，AI 生成图片
- 📝 **文案创作** — AI 辅助写文案、写段子、写祝福语

</details>

> 📌 已开发完成，即将上架 [AstrBot 插件市场](https://plugins.astrbot.app)。

</details>

---

<details>
<summary><h2>🛠 技术架构</h2></summary>

### 技术栈

| 技术 | 用途 | 说明 |
|------|------|------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | 插件开发 | Python 3.10+，全面使用类型注解 |
| ![AstrBot](https://img.shields.io/badge/AstrBot_Framework-blue?style=flat-square) | Bot 框架 | 基于 AstrBot 官方插件规范 |
| ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) | CI/CD 自动化 | Issue 自动分类、PR 检查、代码 Lint |
| ![ruff](https://img.shields.io/badge/ruff-Linter-yellow?style=flat-square) | 代码检查 | 高性能 Python Linter & Formatter |
| ![MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square) | 开源协议 | 所有插件均采用 MIT 协议 |
| ![YAML](https://img.shields.io/badge/Config-YAML-orange?style=flat-square) | 配置管理 | 使用 YAML 进行插件配置 |

<details>
<summary><b>💡 设计理念</b></summary>

我们的插件架构遵循以下设计原则：

1. **模块化设计** — 每个功能模块独立，便于维护和扩展
2. **配置驱动** — 所有功能通过配置文件控制，无需修改代码
3. **渐进增强** — 基础功能开箱即用，高级功能按需启用
4. **优雅降级** — 外部服务不可用时自动跳过，不影响核心功能
5. **防御性编程** — 对所有外部输入进行校验，避免意外崩溃

</details>

</details>

---

<details>
<summary><h2>🛡️ 安全理念</h2></summary>

安全是我们设计的基石，而非事后补丁：

1. **输入校验** — 所有来自用户和外部 API 的输入都经过严格的类型检查和长度限制，防止注入攻击和异常数据导致的崩溃
2. **最小权限** — 插件仅请求完成任务所需的最小权限集，不越权读取或修改无关数据
3. **数据隔离** — 每个群聊、每个用户的数据完全隔离，不存在跨群数据泄露风险
4. **日志安全** — 使用日志记录中不包含敏感个人信息，API Key 等凭证信息严格过滤
5. **依赖审计** — 所有第三方依赖定期检查已知漏洞，及时升级到安全版本
6. **配置验证** — 启动时自动校验配置文件格式，异常配置会给出明确的中文错误提示

</details>

---

<details>
<summary><h2>🧪 质量保障</h2></summary>

我们建立了完善的质量保障体系，确保每次发布的可靠性：

| 层级 | 说明 |
|------|------|
| 🔍 代码审查 | 每次提交都经过 ruff 自动检查，PR 由维护者人工 Review |
| 🤖 自动化 CI | GitHub Actions 在每次 push 和 PR 时自动运行代码质量检查 |
| 📝 类型注解 | Python 类型注解覆盖率 ≥ 80%，静态类型检查提前发现潜在问题 |
| 🧩 边界测试 | 对各种边界情况（空输入、超长输入、特殊字符）进行防御性处理 |
| 🔄 回归验证 | 每次修复 Bug 后进行回归测试，确保不会引入新问题 |

**质量承诺：**

- **零崩溃目标**：用户正常使用中不应遇到插件导致的崩溃
- **快速修复**：确认的 Bug 在 48 小时内发布补丁版本
- **向后兼容**：配置文件格式变更提供迁移方案，不强制用户重头配置
- **可观测性**：详细的日志输出帮助用户和开发者快速定位问题

</details>

---

<details>
<summary><h2>📜 开发规范</h2></summary>

我们遵循以下开发规范，确保代码质量：

### 版本管理

遵循 [语义化版本](https://semver.org/lang/zh-CN/)（SemVer）：

| 变更类型 | 版本影响 | 示例 |
|----------|----------|------|
| Bug 修复、小改动 | 修订号 +1 | `2.4.0` → `2.4.1` |
| 新功能（中等规模） | 次版本号 +1 | `2.4.5` → `2.5.0` |
| 大版本重构 | 主版本号 +1 | `2.5.0` → `3.0.0` |

<details>
<summary><b>📝 Git Commit 规范</b></summary>

使用约定式提交（Conventional Commits）：

| 前缀 | 用途 | 示例 |
|------|------|------|
| `feat:` | 新功能 | `feat: 添加分时段限频策略` |
| `fix:` | Bug 修复 | `fix: 修复安静时段不生效的问题` |
| `docs:` | 文档更新 | `docs: 更新 README 安装说明` |
| `refactor:` | 代码重构 | `refactor: 重构限频引擎模块` |
| `chore:` | 维护任务 | `chore: 升级依赖版本` |
| `perf:` | 性能优化 | `perf: 优化日志查询速度` |

</details>

<details>
<summary><b>🎨 代码风格</b></summary>

- 通过 **ruff** 自动检查，PR 提交时自动运行 CI
- Python 类型注解覆盖率 ≥ 80%
- 每个公开函数都有 docstring
- 错误信息使用中文，方便用户理解

</details>

### 发布流程

每次更新必须完成以下步骤：

1. ✅ 本地测试通过
2. ✅ 提交到 GitHub（含 tag）
3. ✅ 发布 GitHub Release（含更新日志）
4. ✅ 更新 [AstrBot 插件市场](https://plugins.astrbot.app)

</details>

---

<details>
<summary><h2>🤖 自动化流程</h2></summary>

我们为每个插件仓库配置了完整的 GitHub Actions 自动化流水线：

### Issue 自动分类（issue-triage.yml）

| 触发条件 | 自动操作 |
|----------|----------|
| 新 Issue 创建 | 根据标题关键词自动打标签 |
| 标签关键词匹配 | `bug` / `enhancement` / `question` / `documentation` / `triage` |
| 自动分配 | 自动分配给仓库维护者 |
| 自动评论 | 发送中文欢迎消息，Bug 类型附加报告清单提醒 |

### PR 自动检查（pr-check.yml）

| 检查项 | 说明 |
|--------|------|
| 标题格式 | 建议使用 `feat:` / `fix:` / `docs:` 等前缀 |
| Issue 关联 | 提示通过 `Fixes #xx` / `关闭 #xx` 关联 Issue |
| 自动评论 | 中文化的 PR 检查结果反馈 |

### 代码质量检查（python-lint.yml）

| 检查项 | 说明 |
|--------|------|
| 语法检查 | ruff 语法规则检查 |
| 格式检查 | ruff 代码格式检查 |
| 触发时机 | push 到 main/master + PR 提交时 |
| 运行环境 | Python 3.12 |

</details>

---

<details>
<summary><h2>🌍 开源文化</h2></summary>

开源不仅仅是把代码放到 GitHub 上。对我们来说，开源是一种文化、一种承诺：

**我们为什么开源？**

- 我们受益于 AstrBot 这样的开源项目，也希望回馈社区
- 透明度建立信任 — 用户可以查看每一行代码，知道插件在做什么
- 集体智慧优于个人能力 — 社区的每一个建议都可能让产品变得更好
- 知识共享推动行业进步 — 我们的开源代码也是其他开发者的学习资源

**我们的开源承诺：**

- 📜 **永远 MIT 协议** — 我们的代码永远免费、永远开源
- 🔓 **不设付费墙** — 核心功能完全免费，不存在"付费解锁高级版"
- 🤝 **欢迎 Fork** — 鼓励用户基于我们的代码进行二次开发
- 📖 **文档优先** — 好的代码如果没有好的文档，等于不存在
- 🐛 **拥抱 Bug** — 每一个 Bug 报告都是改进的机会，不是麻烦

**给新手的建议：**

如果你是第一次接触开源，欢迎从给我们的仓库点一个 Star 开始！然后你可以尝试：
1. 在 [Issues](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) 中寻找标注了 `good first issue` 的任务
2. 改进文档中的错别字或表述
3. 提交一个你希望添加的功能建议

开源社区的大门永远为你敞开 🚪

</details>

---

<details>
<summary><h2>🗺 项目路线图</h2></summary>

### ✅ 已完成

- [x] 🔧 API 调用限频器 v1.0 — 基础限频功能
- [x] ⚡ API 限频器 v2.0 — 群聊独立配额、分时段策略
- [x] 📝 API 限频器 v2.4 — 使用日志导出、管理员重置、超额提醒
- [x] 🎮 QQ 功能工具箱 — 20+ 多功能指令
- [x] 🤖 GitHub Actions 自动化 — Issue 分类、PR 检查、代码 Lint
- [x] 🌐 中英文双语文档
- [x] 🏪 插件市场上架 — API 限频器通过审核上架
- [x] 🔄 代码规范化 — ruff 集成、Conventional Commits

### 🚧 进行中

- [ ] 📊 使用数据统计面板 — 可视化展示 API 调用趋势和用户使用情况
- [ ] 📱 QQ 工具箱插件市场上架 — 完善文档，提交审核

### 📋 计划中

- [ ] 🔌 更多平台适配 — 针对 Discord、飞书等平台优化体验
- [ ] 🧩 更多实用插件 — 根据社区需求规划新插件
- [ ] 📖 开发者文档站 — 独立的文档网站，提供更详细的开发指南
- [ ] 🎨 插件配置可视化 — Web UI 配置界面，降低使用门槛
- [ ] 📦 插件模板 — 提供标准化的 AstrBot 插件开发模板
- [ ] 🤝 社区贡献者体系 — 建立 contributor 榜单和奖励机制

</details>

---

<details>
<summary><h2>📜 版本历史</h2></summary>

### astrbot_plugin_api_limiter

| 版本 | 日期 | 主要变更 |
|------|------|----------|
| v2.4.5 | 2026-04 | 当前稳定版，功能完善 |
| v2.4.0 | 2026-04 | 使用日志导出、管理员重置 |
| v2.3.0 | 2026-03 | 分时段限频策略 |
| v2.2.0 | 2026-03 | 超额提醒、黑名单增强 |
| v2.1.0 | 2026-02 | 群聊独立配额 |
| v2.0.0 | 2026-01 | 大版本重构，架构优化 |
| v1.x.x | 2025 | 初始版本，基础限频功能 |

</details>

---

<details>
<summary><h2>💬 社区评价</h2></summary>

听听我们用户和社区是怎么说的：

> "装上之后群聊清爽多了，API 费用直接降了 60%！" — *AstrBot 社区用户*
>
> "一个工具箱顶十个插件，再也不用到处找了。" — *QQ 群管理员*
>
> "文档写得非常详细，小白也能轻松上手。" — *新手用户*

### 📊 社区影响力

| 指标 | 详情 |
|------|------|
| 🌟 GitHub Stars | 持续增长中 |
| 🍴 Fork 数量 | 社区贡献者积极参与 |
| 📥 插件下载量 | 通过 AstrBot 插件市场分发 |
| 🐛 Bug 响应时间 | 平均 24 小时内首次回复 |
| 🔄 版本迭代频率 | 平均每周 1-2 次更新 |

我们深知，每一个 Star、每一个 Issue、每一次 PR 都是社区对我们工作的认可。正是这些反馈推动着我们不断前行。

</details>

---

<details>
<summary><h2>🔮 未来愿景</h2></summary>

### 短期目标（3 个月内）

- 完成 QQ 工具箱的插件市场上架审核
- 发布使用数据统计面板，让管理员直观了解 API 使用趋势
- 探索更多实用的群聊工具指令

### 中期目标（6 个月内）

- 搭建独立的开发者文档站，提供比 README 更详尽的开发指南
- 推出可视化配置工具（Web UI），让不会编程的用户也能轻松配置
- 根据社区反馈开发 1-2 个新的实用插件

### 长期愿景（1 年以上）

- 成为 AstrBot 生态中最受信任的插件开发组织之一
- 建立社区贡献者体系和奖励机制
- 探索插件间的联动能力，打造 AstrBot 的"插件生态圈"
- 如果条件成熟，提供标准化的 AstrBot 插件开发模板，降低新开发者的入门门槛

**我们的终极目标很简单：让每一位 AstrBot 用户都能找到自己需要的插件，让每一位 AstrBot 开发者都能轻松构建高质量的插件。**

</details>

---

<details>
<summary><h2>🤝 参与贡献</h2></summary>

欢迎各种形式的贡献！无论你是想：

- 🐛 提交 [Bug 报告](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) 或功能建议
- 🔀 提交 Pull Request 修复问题或添加新功能
- 📖 改进文档或翻译
- 💬 在社区分享使用经验
- ⭐ 在 GitHub 上给我们一个 Star

<details>
<summary><b>📖 贡献指南</b></summary>

1. **Fork** 你想要贡献的仓库
2. **创建特性分支**：`git checkout -b feat/amazing-feature`
3. **提交更改**：`git commit -m "feat: 添加某个功能"`
4. **推送到分支**：`git push origin feat/amazing-feature`
5. **发起 Pull Request** — 我们的自动化系统会自动进行代码检查

**注意事项：**

- 请遵循我们的 [Conventional Commits](https://www.conventionalcommits.org/) 规范
- 请确保代码通过 ruff 检查（`ruff check .`）
- PR 标题建议使用 `feat:` / `fix:` / `docs:` 等前缀
- 请关联相关 Issue（`Fixes #xx` / `关闭 #xx`）

</details>

你的每一份支持都是我们持续开发的动力！

</details>

---

<details>
<summary><h2>❓ 常见问题</h2></summary>

<details>
<summary><b>🔧 如何安装插件？</b></summary>

**推荐方式**：通过 [AstrBot 插件市场](https://plugins.astrbot.app) 一键安装。在 AstrBot 后台搜索插件名称，点击安装即可。

**手动安装**：从 GitHub Release 下载源码，解压后放入 AstrBot 的 `data/plugins/` 目录，重启 AstrBot。

两种方式都完全支持，推荐使用插件市场以获得自动更新。
</details>

<details>
<summary><b>🐛 遇到 Bug 怎么办？</b></summary>

请前往对应仓库的 [Issues](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) 页面提交 Bug 报告。为了帮助我们快速定位问题，请附上：

1. 插件版本号（在 AstrBot 后台查看）
2. AstrBot 版本号
3. Bug 的详细复现步骤
4. 相关的错误日志（可在 AstrBot 日志中找到）

我们的自动化系统会自动为你的 Issue 分类，维护者会在第一时间处理。
</details>

<details>
<summary><b>💡 我想提功能建议？</b></summary>

欢迎！直接在 Issues 中提交，标题以"建议"或"enhancement"开头即可。我们会评估可行性和优先级，排入开发计划。

建议包含以下信息：
- 你希望实现什么功能
- 为什么需要这个功能（使用场景）
- 期望的行为描述

好的建议往往会被快速采纳！
</details>

<details>
<summary><b>📋 插件支持哪些平台？</b></summary>

我们的插件基于 AstrBot 框架开发，理论上支持 AstrBot 的所有消息平台适配器，包括但不限于：

- **QQ** — 完整支持
- **微信** — 完整支持
- **Telegram** — 完整支持
- **飞书** — 完整支持
- **Discord** — 基础支持
- **网页端** — 完整支持

具体适配情况取决于 AstrBot 框架本身的平台支持。
</details>

<details>
<summary><b>⚙️ 如何配置限频规则？</b></summary>

API 限频器支持在 AstrBot 配置文件中进行详细配置。主要配置项包括：

- **间隔时间**：两次调用之间的最小间隔（秒）
- **每日次数**：每个用户每日最大调用次数
- **每小时次数**：每个用户每小时最大调用次数
- **安静时段**：自动禁用 API 调用的时间段
- **白名单**：不受限制的用户列表
- **黑名单**：完全禁用的用户列表

详细的配置说明请参考各插件仓库的 README 文档。
</details>

<details>
<summary><b>🔄 如何更新插件？</b></summary>

如果你通过 AstrBot 插件市场安装，可以在 AstrBot 后台直接检查更新并一键升级。

如果你手动安装，可以从 GitHub Release 下载最新版本，替换旧的插件文件即可。更新后请重启 AstrBot 使新版本生效。
</details>

<details>
<summary><b>📝 插件是免费的吗？</b></summary>

是的！我们所有的插件都基于 MIT 协议开源，完全免费使用。

插件本身不收取任何费用，但请注意你使用的第三方 API（如大模型 API、翻译 API 等）可能需要付费。
</details>

<details>
<summary><b>🤖 你们的 GitHub Actions 自动化是怎么工作的？</b></summary>

我们为每个插件仓库配置了 3 套自动化 Workflow：

1. **Issue 自动分类**：新 Issue 根据标题关键词自动打标签、分配维护者、发送欢迎评论
2. **PR 自动检查**：检查 PR 标题格式、提示关联 Issue、代码风格检查
3. **Python 代码 Lint**：使用 ruff 对 Python 代码进行语法和格式检查

所有这些都在 GitHub 服务器上运行，零成本、无需维护。
</details>

</details>

---

<details>
<summary><h2>📮 联系我们</h2></summary>

| 方式 | 信息 |
|------|------|
| **组织拥有者** | [xiaohondan](https://github.com/xiaohondan) |
| **邮箱** | xiaohondan@skymail.ink |
| **GitHub 组织** | [NekoAiDev](https://github.com/NekoAiDev) |
| **插件市场** | [AstrBot 插件市场](https://plugins.astrbot.app) |
| **Bug 反馈** | [提交 Issue](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) |

### 🤝 特别致谢

- **[AstrBot](https://github.com/Soulter/AstrBot)** — 提供了优秀的 Bot 框架和活跃的社区生态
- **所有贡献者** — 每一个 PR、每一个 Issue、每一个建议，都是对开源社区的珍贵贡献
- **每一位用户** — 你们的使用和反馈，是我们持续开发的最大动力

</details>

---

<div align="center">

**用 ❤️ 打造 | Neko Ai**

*喜欢我们的插件？在 GitHub 上给个 ⭐ 吧！*

*感谢 AstrBot 社区的每一位用户，你们的反馈是我们前进的动力。*

*猫在键盘上敲代码，Bug 都会被猫咪抓走 🐱*

</div>
