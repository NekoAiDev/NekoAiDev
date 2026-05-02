<div align="center">

<img src="https://avatars.githubusercontent.com/u/228279600?v=4" alt="Neko Ai" width="120" height="120" style="border-radius: 50%;"/>

# Neko Ai

**AstrBot Plugins & Tech Development Organization**

[![GitHub](https://img.shields.io/badge/GitHub-NekoAiDev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NekoAiDev)
[![Author](https://img.shields.io/badge/Author-%E5%B0%8F%E7%BA%A2%E8%9B%8B-orange?style=flat-square)](https://github.com/xiaohondan)
[![AstrBot](https://img.shields.io/badge/AstrBot-Plugin-blue?style=flat-square)](https://github.com/Soulter/AstrBot)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)
[![Plugins](https://img.shields.io/badge/Plugins-2+-orange?style=flat-square)](https://github.com/orgs/NekoAiDev/repositories)
[![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)](https://github.com/NekoAiDev/.github/tree/main/profile)

[🌐 中文](https://github.com/NekoAiDev)

</div>

---



## 📋 Table of Contents

- [About Us](#-about-us)
- [Project](#-projects)
- [Technical Architecture](#-technical-architecture)
- [Security Philosophy](#-security-philosophy)
- [Quality Assurance](#-quality-assurance)
- [Development Standards](#-development-standards)
- [Automation Pipeline](#-automation-pipeline)
- [Open Source Culture](#-open-source-culture)
- [Roadmap](#-roadmap)
- [Version History](#-version-history)
- [Community Feedback](#-community-feedback)
- [Future Vision](#-future-vision)
- [Contributing](#-contributing)
- [FAQ](#-faq)
- [Contact](#-contact)

---

<details>
<summary><h2>📖 About Us</h2></summary>

Neko Ai is an open-source development organization focused on **[AstrBot](https://github.com/Soulter/AstrBot)** plugin development and broader tech exploration. We are a group of developers passionate about open source and user experience, committed to building fun, practical, and high-quality open-source projects.

**AstrBot** is an excellent multi-platform chatbot framework supporting QQ, WeChat, Telegram, Feishu (Lark), Discord, and more, with an active open-source community and a rich plugin ecosystem. As active participants in the AstrBot community, we don't just build plugins — we also contribute documentation, share experiences, and help more users and developers join the ecosystem.

### 🔢 Key Stats

| Metric | Value |
|--------|-------|
| 📦 Published Plugins | 2+ |
| 🏪 Marketplace Listings | 1 (Rate Limiter) |
| 📝 Total Releases | 20+ |
| 🔧 Total Features | 40+ |
| 🤖 CI/CD Workflows | 3 automated pipelines |
| 📄 Languages Supported | 中文 + English |

### 🎯 Our Mission

> Make every project more powerful, more flexible, and more fun.

We believe great open-source tools should:

- **Be User-Friendly** — No need to spend hours reading docs. Install and go, with clear configs and explicit feedback. Even if you're a complete beginner with zero coding experience, you can set up and configure our plugins in under 5 minutes
- **Be Rock-Solid** — Every commit is thoroughly tested. Edge cases are handled gracefully. No crashes from unexpected input. We use ruff for code quality checks and GitHub Actions to ensure every commit passes automated tests
- **Be Open & Transparent** — All code is MIT licensed. Everyone is welcome to read, learn, open issues, and submit PRs. We believe in the power of open source and that transparent development processes build stronger community trust
- **Keep Evolving** — We actively listen to community feedback, iterate continuously, and keep adding new features. Every version is carefully planned to find the right balance between stability and innovation
- **Be Community-Driven** — Our development direction is shaped by community needs. Every feature request, every bug report, and every discussion helps shape the future of our plugins

<details>
<summary><b>📖 Our Story</b></summary>

It all started with a simple need: **managing runaway API calls in group chats**.

As AstrBot grew in popularity, more and more users started using LLM APIs in group chats. But with that came unchecked costs and abuse. Some users would burn through hundreds of API calls in a single day, leaving admins frustrated. No existing rate-limiting plugin could handle complex real-world scenarios — multi-group differentiation, time-based policies, blacklist management, over-limit notifications... So **astrbot_plugin_api_limiter** was born.

From a simple call counter, it evolved through dozens of versions to include interval limiting, quiet hours, whitelists, time-based policies, per-group quotas, and more. Today, it's one of the most comprehensive API rate limiting solutions on the AstrBot Plugin Marketplace. We've journeyed from v1.0.0 to v2.4.5, with every release shaped by community feedback and user needs.

Along the way, we noticed the AstrBot community was missing handy utility tools — IP lookups, random draws, trending topic searches, and more. Users would frequently ask in group chats, "Is there a weather command?" or "Can you add a lucky draw feature?" — That led us to build **astrbot_plugin_qq_toolbox**, bundling 20+ useful commands into a single plugin so users only need one install for a full toolkit. One plugin to solve all daily needs — that's our design philosophy.

The name **Neko Ai** reflects our values: "Neko" (cat) represents the fun and warmth we bring to open source, "Ai" stands for our commitment to the AI era, and "Dev" is our developer roots. We aim to create value for the community — even if it's just a small convenience.

From one person writing code to building an organization, establishing automated workflows, listing on the plugin marketplace, and publishing bilingual documentation... this journey has been full of challenges and rewards. We're grateful to the AstrBot community and every user who has supported us along the way.

</details>

<details>
<summary><b>🏗️ Organization Structure</b></summary>

Neko Ai uses a lean organizational model:

- **Organization Owner**: [xiaohondan](https://github.com/xiaohondan) — Responsible for overall planning, development, and community maintenance
- **Automation System**: GitHub Actions handles repetitive tasks like issue triage, PR checks, and code review, allowing developers to focus on creation
- **Open Collaboration**: Any interested developer can contribute via the Fork + PR workflow

</details>

### 🚀 Why Choose Our Plugins?

- ✅ Published on the [AstrBot Plugin Marketplace](https://plugins.astrbot.app) — one-click install, no manual setup
- ✅ Comprehensive documentation and README in both Chinese and English, beginner-friendly
- ✅ Full GitHub Actions automation — auto issue triage, PR checks, and code linting for guaranteed code quality
- ✅ Actively maintained with timely bug fixes and stable version iterations, average release cycle under one week
- ✅ Advanced features like per-group quotas and time-based policies for complex use cases
- ✅ MIT open-source license — fully transparent code, free to modify and redistribute
- ✅ Bilingual documentation (中文 + English), serving users worldwide

</details>

---

<details>
<summary><h2>📦 Projects</h2></summary>

### [astrbot_plugin_api_limiter](https://github.com/NekoAiDev/astrbot_plugin_api_limiter)

<img src="https://img.shields.io/github/v/release/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Release"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_api_limiter/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_api_limiter?style=flat-square" alt="Forks"/></a> <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" alt="Status"/>

**API Rate Limiter** — A comprehensive rate limiting plugin for AstrBot that helps you manage API call frequency and prevent abuse. Perfect for metered APIs like LLMs, translation services, and more.

This is our flagship plugin and one of the most popular rate limiting solutions on the AstrBot Plugin Marketplace. From v1.0 to v2.4.5, we've continuously refined every detail.

<details>
<summary><b>📋 Details</b></summary>

**Typical Use Cases:**

- 🤖 **LLM Chat Rate Limiting** — Prevent users from spamming AI chat in groups and keep API costs under control. Supports multi-dimensional limits including daily totals, hourly caps, and minimum intervals
- 🌐 **Translation API Control** — Allocate daily translation quotas per user/group for fair distribution. Prevent individual users from monopolizing translation capacity
- 🔍 **Search API Management** — Manage rate-limited APIs like web search and image search. Make limited API quotas serve more users
- 📊 **Multi-Group Differentiation** — Different quotas for different groups; VIP groups get more relaxed limits. Each group has completely independent configuration
- 🌙 **Automatic Night Mode** — Automatically disable API calls during late night hours, saving costs and avoiding disruptions
- 🏢 **Enterprise/Team Management** — Whitelist mechanism exempts admins, blacklist mechanism precisely blocks abusive users

**Core Features:**

| Feature |描述|
|---------|-------------|
| ⏱ Interval Limiting | Control the minimum time between consecutive API calls to prevent spamming |
| 🔢 Count Limiting + Cooldown Reset | Set daily/hourly quotas that automatically reset after cooldown |
| 🌙 Quiet Hours | Automatically disable API calls during specified time periods |
| 📋 Whitelist & Blacklist | Fine-grained control over which users/groups are affected, admin exempt |
| 🕐 Time-Based Policies | Apply different rate limits for different time periods |
| 🔔 Over-Limit Reminders | Send friendly notifications when users approach or exceed limits |
| 👥 Per-Group Quotas | Each group chat has its own independent rate limit config |
| 📊 Usage Logging & Export | Track all API calls with exportable logs for analysis |
| 🔄 Admin Reset Commands | Reset user or group counters at any time |

**Quick Start:**

```
# 1. Search "api_limiter" in the AstrBot Plugin Marketplace and install with one click
# 2. Configure your rate limiting rules in the AstrBot config file
# 3. Restart AstrBot — the rate limiter activates automatically
```

</details>

> 📌 Available on the [AstrBot Plugin Marketplace](https://plugins.astrbot.app). Current version: **v2.4.5**. Continuously updated.

---

### [astrbot_plugin_qq_toolbox](https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox)

<img src="https://img.shields.io/badge/Version-1.0.0-9cf?style=flat-square" alt="Version"/> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"/> <a href="https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox/stargazers"><img src="https://img.shields.io/github/stars/NekoAiDev/astrbot_plugin_qq_toolbox?style=flat-square" alt="Stars"/></a> <a href="https://github.com/NekoAiDev/astrbot_plugin_qq_toolbox/forks"><img src="https://img.shields.io/github/forks/NekoAiDev/astrbot_plugin_qq_toolbox?style=flat-square" alt="Forks"/></a> <img src="https://img.shields.io/badge/Status-Development-yellow?style=flat-square" alt="Status"/>

**QQ Toolbox** — An all-in-one utility plugin packed with 20+ commands across entertainment, queries, content generation, and group management. Spice up your group chat experience!

One plugin = a complete group chat toolkit. No need to install a bunch of scattered plugins — Toolbox gives you everything you need for daily group chat in a single install.

<details>
<summary><b>📋 Details</b></summary>

**Feature Categories:**

| Category | Commands |描述|
|----------|----------|-------------|
| 🎮 Entertainment | 10+ | Fun group chat mini-games, random draws, quizzes, lucky wheels, and more |
| 🔍 Utility Queries | 5+ | Weather lookup, trending topics, IP geolocation, currency exchange, and more |
| ✍️ Content Generation | 4+ | AI-powered copywriting, image generation, text polishing, random quotes, and more |
| ⚙️ Group Management | 2+ | Admin tools for managing group chat settings |
| 🔄 Auto-Reply | 1 | Configurable automatic message repetition to keep groups active |

**Highlight Features:**

- 🎰 **Random Draw** — Help group members make decisions when they can't choose
- 🌤 **Weather Query** — Enter a city name, get real-time weather instantly
- 🔥 **Trending Topics** — Get the latest hot searches from Weibo/Baidu with one command
- 🌐 **IP Lookup** — Query IP geolocation and ISP information
- 🎨 **Image Generation** — Enter a description, AI generates an image
- 📝 **Copywriting** — AI-assisted writing for posts, jokes, greetings, and more

</details>

> 📌 Development complete. Coming soon to the [AstrBot Plugin Marketplace](https://plugins.astrbot.app).

</details>

---

<details>
<summary><h2>🛠 Technical Architecture</h2></summary>

### Tech Stack

| Technology | Usage | Details |
|------------|-------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Plugin Development | Python 3.10+, comprehensive type annotations |
| ![AstrBot](https://img.shields.io/badge/AstrBot_Framework-blue?style=flat-square) | Bot Framework | Based on official AstrBot plugin spec |
| ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) | CI/CD Automation | Auto issue triage, PR checks, code lint |
| ![ruff](https://img.shields.io/badge/ruff-Linter-yellow?style=flat-square) | Code Quality | High-performance Python linter & formatter |
| ![MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square) | License | All plugins under MIT license |
| ![YAML](https://img.shields.io/badge/Config-YAML-orange?style=flat-square) | Configuration | YAML-based plugin configuration |

<details>
<summary><b>💡 Design Principles</b></summary>

Our plugin architecture follows these design principles:

1. **Modular Design** — Each feature module is independent for easy maintenance and extension
2. **Configuration-Driven** — All features controlled via config files, no code modification needed
3. **Progressive Enhancement** — Core features work out of the box, advanced features opt-in
4. **Graceful Degradation** — External service failures are silently skipped without affecting core functionality
5. **Defensive Programming** — All external inputs are validated to prevent unexpected crashes

</details>

</details>

---

<details>
<summary><h2>🛡️ Security Philosophy</h2></summary>

Security is the foundation of our design, not an afterthought:

1. **Input Validation** — All input from users and external APIs undergoes strict type checking and length limits to prevent injection attacks and crashes from abnormal data
2. **Least Privilege** — Plugins only request the minimum permissions needed to accomplish their tasks. No reading or modifying unrelated data
3. **Data Isolation** — Each group chat and each user's data is completely isolated. No cross-group data leakage risk
4. **Log Security** — No sensitive personal information is recorded in logs. API keys and credentials are strictly filtered out
5. **Dependency Auditing** — All third-party dependencies are regularly checked for known vulnerabilities and upgraded promptly
6. **Configuration Validation** — Automatic config file format validation on startup with clear error messages for invalid configurations

</details>

---

<details>
<summary><h2>🧪 Quality Assurance</h2></summary>

We've established a comprehensive quality assurance system to ensure the reliability of every release:

| Layer |描述|
|-------|-------------|
| 🔍 Code Review | Every commit is automatically checked by ruff; PRs are manually reviewed by maintainers |
| 🤖 Automated CI | GitHub Actions runs code quality checks on every push and PR |
| 📝 Type Annotations | Python type annotation coverage ≥ 80%, catching potential issues early via static type checking |
| 🧩 Edge Case Testing | Defensive handling of edge cases including empty input, extra-long input, and special characters |
| 🔄 Regression Verification | Regression testing after every bug fix to ensure no new issues are introduced |

**Quality Commitments:**

- **Zero Crash Goal**: Users should never encounter plugin-caused crashes during normal usage
- **Fast Fixes**: Confirmed bugs receive patch releases within 48 hours
- **Backward Compatibility**: Config file format changes include migration paths — users never have to start from scratch
- **Observability**: Detailed logging output helps both users and developers quickly pinpoint issues

</details>

---

<details>
<summary><h2>📜 Development Standards</h2></summary>

We follow these standards to ensure code quality:

### Version Management

Following [Semantic Versioning](https://semver.org/) (SemVer):

| Change Type | Version Impact | Example |
|-------------|---------------|---------|
| Bug fixes, minor changes | PATCH +1 | `2.4.0` → `2.4.1` |
| New features (medium scope) | MINOR +1 | `2.4.5` → `2.5.0` |
| Major rewrites | MAJOR +1 | `2.5.0` → `3.0.0` |

<details>
<summary><b>📝 Git Commit Convention</b></summary>

Using [Conventional Commits](https://www.conventionalcommits.org/):

| Prefix | Purpose | Example |
|--------|---------|---------|
| `feat:` | New feature | `feat: add time-based rate limiting policy` |
| `fix:` | Bug fix | `fix: resolve quiet hours not working` |
| `docs:` | Documentation | `docs: update README installation guide` |
| `refactor:` | Refactoring | `refactor: restructure rate limiting engine` |
| `chore:` | Maintenance | `chore: upgrade dependencies` |
| `perf:` | Performance | `perf: optimize log query speed` |

</details>

<details>
<summary><b>🎨 Code Style</b></summary>

- Automatically checked with **ruff**, CI runs on every PR
- Python type annotation coverage ≥ 80%
- Every public function has a docstring
- Error messages in Chinese for better user understanding

</details>

### Release Process

Every update must complete these steps:

1. ✅ Local testing passed
2. ✅ Push to GitHub (with tag)
3. ✅ Publish GitHub Release (with changelog)
4. ✅ Update [AstrBot Plugin Marketplace](https://plugins.astrbot.app)

</details>

---

<details>
<summary><h2>🤖 Automation Pipeline</h2></summary>

We've configured a complete GitHub Actions automation pipeline for each plugin repository:

### Auto Issue Triage (issue-triage.yml)

| Trigger | Automatic Action |
|---------|-----------------|
| New issue created | Auto-label based on title keywords |
| Keyword matching | `bug` / `enhancement` / `question` / `documentation` / `triage` |
| Auto-assign | Automatically assigned to repository maintainer |
| Auto-comment | Welcome message; bug-type issues get a report checklist reminder |

### Auto PR Check (pr-check.yml)

| Check | Description |
|-------|-------------|
| Title format | Suggests using `feat:` / `fix:` / `docs:` prefixes |
| Issue linking | Prompts to link issues via `Fixes #xx` / `Closes #xx` |
| Auto-comment | Feedback on PR check results |

### Code Quality (python-lint.yml)

| Check | Description |
|-------|-------------|
| Syntax check | ruff syntax rule checking |
| Format check | ruff code format checking |
| Trigger | Push to main/master + PR submission |
| Runtime | Python 3.12 |

</details>

---

<details>
<summary><h2>🌍 Open Source Culture</h2></summary>

Open source is more than just putting code on GitHub. For us, it's a culture and a commitment:

**Why We Open Source?**

- We benefit from open-source projects like AstrBot, and we want to give back to the community
- Transparency builds trust — users can inspect every line of code and know exactly what our plugins do
- Collective wisdom beats individual ability — every community suggestion can make our products better
- Knowledge sharing drives industry progress — our open-source code is also a learning resource for other developers

**Our Open Source Commitments:**

- 📜 **Forever MIT Licensed** — Our code will always be free and always be open source
- 🔓 **No Paywalls** — All core features are completely free. No "premium unlocks"
- 🤝 **Fork-Friendly** — We encourage users to build upon our code for secondary development
- 📖 **Docs First** — Great code without great documentation might as well not exist
- 🐛 **Bug-Friendly** — Every bug report is an opportunity to improve, not a nuisance

**Advice for Open Source Beginners:**

If you're new to open source, start by giving our repos a Star! Then you can try:
1. Look for issues labeled `good first issue` in our [Issues](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) page
2. Fix typos or improve wording in documentation
3. Submit a feature request for something you'd like to see

The doors of the open-source community are always open for you 🚪

</details>

---

<details>
<summary><h2>🗺 Roadmap</h2></summary>

### ✅ Completed

- [x] 🔧 API Rate Limiter v1.0 — Basic rate limiting features
- [x] ⚡ API Limiter v2.0 — Per-group quotas, time-based policies
- [x] 📝 API Limiter v2.4 — Usage log export, admin reset, over-limit reminders
- [x] 🎮 QQ Toolbox — 20+ multi-function commands
- [x] 🤖 GitHub Actions Automation — Issue triage, PR checks, code lint
- [x] 🌐 Bilingual Documentation (Chinese & English)
- [x] 🏪 Plugin Marketplace Listing — Rate limiter approved and listed
- [x] 🔄 Code Standardization — ruff integration, Conventional Commits

### 🚧 In Progress

- [ ] 📊 Usage Statistics Dashboard — Visualize API call trends and user usage patterns
- [ ] 📱 QQ Toolbox Marketplace Listing — Complete documentation and submit for review

### 📋 Planned

- [ ] 🔌 More Platform Adapters — Optimize experience for Discord, Feishu, and more
- [ ] 🧩 More Utility Plugins — Plan new plugins based on community demand
- [ ] 📖 Developer Documentation Site — Standalone docs site with detailed development guides
- [ ] 🎨 Visual Plugin Configuration — Web UI config interface to lower the barrier to entry
- [ ] 📦 Plugin Template — Standardized AstrBot plugin development template
- [ ] 🤝 Community Contributor System — Contributor leaderboard and reward mechanism

</details>

---

<details>
<summary><h2>📜 Version History</h2></summary>

### astrbot_plugin_api_limiter

| Version | Date | Key Changes |
|---------|------|-------------|
| v2.4.5 | 2026-04 | Current stable release, fully featured |
| v2.4.0 | 2026-04 | Usage log export, admin reset commands |
| v2.3.0 | 2026-03 | Time-based rate limiting policies |
| v2.2.0 | 2026-03 | Over-limit reminders, blacklist enhancements |
| v2.1.0 | 2026-02 | Per-group independent quotas |
| v2.0.0 | 2026-01 | Major rewrite, architecture optimization |
| v1.x.x | 2025 | Initial versions, basic rate limiting |

</details>

---

<details>
<summary><h2>💬 Community Feedback</h2></summary>

Here's what our users and community are saying:

> "After installing this, my group chat is so much cleaner. API costs dropped by 60%!" — *AstrBot Community User*
>
> "One toolbox replaces ten plugins. No more hunting around for features." — *QQ Group Admin*
>
> "The documentation is incredibly detailed — even a complete beginner can get started easily." — *New User*

### 📊 Community Impact

| Metric | Details |
|--------|---------|
| 🌟 GitHub Stars | Growing steadily |
| 🍴 Forks | Community contributors actively participating |
| 📥 Downloads | Distributed via AstrBot Plugin Marketplace |
| 🐛 Bug Response Time | First response within 24 hours on average |
| 🔄 Release Frequency | 1-2 updates per week on average |

We know that every Star, every Issue, and every PR is the community's recognition of our work. It's these interactions that keep us moving forward.

</details>

---

<details>
<summary><h2>🔮 Future Vision</h2></summary>

### Short-Term Goals (3 months)

- Complete the QQ Toolbox plugin marketplace listing review
- Release a usage statistics dashboard for admins to visualize API usage trends
- Explore more practical group chat utility commands

### Mid-Term Goals (6 months)

- Build a standalone developer documentation site with more detailed guides than the README
- Launch a visual configuration tool (Web UI) so non-programmers can easily configure plugins
- Develop 1-2 new utility plugins based on community feedback

### Long-Term Vision (1 year+)

- Become one of the most trusted plugin development organizations in the AstrBot ecosystem
- Establish a community contributor system with recognition and rewards
- Explore cross-plugin integration capabilities to create an "AstrBot plugin ecosystem"
- If conditions are right, provide a standardized AstrBot plugin development template to lower the barrier for new developers

**Our ultimate goal is simple: ensure every AstrBot user can find the plugins they need, and every AstrBot developer can easily build high-quality plugins.**

</details>

---

<details>
<summary><h2>🤝 Contributing</h2></summary>

We welcome contributions in any form! Whether you want to:

- 🐛 Submit a [bug report](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) or feature request
- 🔀 Open a Pull Request to fix issues or add features
- 📖 Improve documentation or translations
- 💬 Share your experience in the community
- ⭐ Give us a Star on GitHub

<details>
<summary><b>📖 Contribution Guide</b></summary>

1. **Fork** the repository you want to contribute to
2. **Create a feature branch**: `git checkout -b feat/amazing-feature`
3. **Commit your changes**: `git commit -m "feat: add some amazing feature"`
4. **Push to the branch**: `git push origin feat/amazing-feature`
5. **Open a Pull Request** — Our automation system will automatically run code checks

**Guidelines:**

- Please follow our [Conventional Commits](https://www.conventionalcommits.org/) convention
- Ensure your code passes ruff checks (`ruff check .`)
- PR titles should use `feat:` / `fix:` / `docs:` prefixes
- Link related issues when applicable (`Fixes #xx` / `Closes #xx`)

</details>

Every bit of support motivates us to keep building!

</details>

---

<details>
<summary><h2>❓ FAQ</h2></summary>

<details>
<summary><b>🔧 How do I install the plugins?</b></summary>

**Recommended**: Install via the [AstrBot Plugin Marketplace](https://plugins.astrbot.app) with one click. Search for the plugin name in the AstrBot dashboard and click install.

**Manual**: Download the source code from GitHub Releases, extract it into AstrBot's `data/plugins/` directory, and restart AstrBot.

Both methods are fully supported. We recommend the marketplace for automatic updates.
</details>

<details>
<summary><b>🐛 What should I do if I find a bug?</b></summary>

Please submit a bug report on the [Issues](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) page of the corresponding repository. To help us fix it quickly, please include:

1. Plugin version number (visible in the AstrBot dashboard)
2. AstrBot version number
3. Detailed steps to reproduce the bug
4. Relevant error logs (available in AstrBot's log files)

Our automation system will automatically categorize your issue, and maintainers will handle it as soon as possible.
</details>

<details>
<summary><b>💡 Can I suggest a new feature?</b></summary>

Absolutely! Open an Issue with a title starting with "feature" or "enhancement". We'll evaluate feasibility and priority, and add it to our development roadmap if it aligns with our goals.

For the best chance of adoption, include:
- What feature you'd like
- Why you need it (use case scenario)
- Expected behavior description

Good suggestions are often adopted quickly!
</details>

<details>
<summary><b>📋 Which platforms are supported?</b></summary>

Our plugins are built on the AstrBot framework and theoretically support all of AstrBot's message platform adapters, including but not limited to:

- **QQ** — Full support
- **WeChat** — Full support
- **Telegram** — Full support
- **Feishu (Lark)** — Full support
- **Discord** — Basic support
- **Web** — Full support

Actual compatibility depends on the AstrBot framework's platform support.
</details>

<details>
<summary><b>⚙️ How do I configure rate limiting rules?</b></summary>

The API Rate Limiter supports detailed configuration in the AstrBot config file. Main configuration options include:

- **Interval Time**: Minimum seconds between consecutive API calls
- **Daily Limit**: Maximum calls per user per day
- **Hourly Limit**: Maximum calls per user per hour
- **Quiet Hours**: Time periods when API calls are automatically disabled
- **Whitelist**: Users exempt from all limits
- **Blacklist**: Users completely blocked from API access

For detailed configuration instructions, please refer to the README documentation in each plugin repository.
</details>

<details>
<summary><b>🔄 How do I update the plugins?</b></summary>

If you installed via the AstrBot Plugin Marketplace, you can check for updates and upgrade with one click directly from the AstrBot dashboard.

For manual installations, download the latest version from GitHub Releases, replace the old plugin files, and restart AstrBot for the new version to take effect.
</details>

<details>
<summary><b>📝 Are the plugins free?</b></summary>

Yes! All our plugins are MIT-licensed open source and completely free to use.

Note that third-party APIs you use with the plugins (such as LLM APIs, translation APIs, etc.) may have their own costs.
</details>

<details>
<summary><b>🤖 How does your GitHub Actions automation work?</b></summary>

We configure 3 automated Workflow pipelines for each plugin repository:

1. **Auto Issue Triage**: New issues are auto-labeled by title keywords, auto-assigned to maintainers, and receive a welcome comment
2. **Auto PR Check**: Checks PR title format, suggests issue linking, and runs code style checks
3. **Python Code Lint**: Uses ruff for Python syntax and format checking

All of this runs on GitHub's servers at zero cost with no maintenance required.
</details>

</details>

---

<details>
<summary><h2>📮 Contact</h2></summary>

| Method | Info |
|--------|------|
| **Organization Owner** | [xiaohondan](https://github.com/xiaohondan) |
| **Email** | xiaohondan@skymail.ink |
| **GitHub Org** | [NekoAiDev](https://github.com/NekoAiDev) |
| **Plugin Marketplace** | [AstrBot Plugin Marketplace](https://plugins.astrbot.app) |
| **Bug Reports** | [Submit an Issue](https://github.com/NekoAiDev/astrbot_plugin_api_limiter/issues) |

### 🤝 Special Thanks

- **[AstrBot](https://github.com/Soulter/AstrBot)** — For providing an excellent Bot framework and an active community ecosystem
- **All Contributors** — Every PR, every Issue, every suggestion is a precious contribution to the open-source community
- **Every User** — Your usage and feedback are our greatest motivation to keep building

</details>

---

<div align="center">

**Made with ❤️ by Neko Ai**

*If you like our plugins, give them a ⭐ on GitHub!*

*Thanks to every user in the AstrBot community — your feedback drives us forward.*

*Coding with cats on the keyboard — they catch all the bugs 🐱*

</div>
