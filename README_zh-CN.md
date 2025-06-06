# ServBay Windows 版本发布

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![最新版本](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](../../releases/latest)
[![GitHub 下载量](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](../../releases)

欢迎来到 ServBay Windows 版本的官方发布仓库。本仓库存储 ServBay 在 Windows 平台的官方发布包及更新日志。

## 🚀 ServBay：开发者本地开发的终极利器

ServBay 是为开发者量身打造的一体化、高性能、易用的本地 Web 开发环境集成解决方案。我们致力于让繁琐的环境配置过程不再成为负担，让你几分钟内即可搭建功能强大、可高度自定义的开发环境，把更多时间留给代码和创新。

ServBay 不仅仅是工具的简单聚合，它是一个**完整生态系统**，旨在为开发者带来**无与伦比的开发体验和超级能力**。无论你是 Web 开发者、后端工程师、数据科学家，还是 AI 应用的探索者，ServBay 都能满足你多样化的开发需求。

本仓库专为 ServBay 的 **Windows 版本** 发布与下载。

![ServBay Windows 版本界面截图：软件](screenshots/softwares.png)

## ✨ ServBay 核心特点与超强功能

ServBay 提供全套开发工具和丰富功能，助力开发者效率提升：

*   **多语言环境及一键切换**：
    *   **PHP**：支持 PHP 5.6 至最新 8.x 多版本，一键切换满足不同项目需求。
    *   **Node.js**：集成 Node.js 12 到 24 多版本，便捷管理项目依赖。
    *   **Python**：全面支持 Python 2.7 及 3.5-3.14+，适用于 Web 开发、数据科学与机器学习项目。
    *   **Java**：集成 OpenJDK 7-24 多版本，内置 Apache Maven，Java 项目构建与管理更简单。
    *   **Go (Golang)**：支持 Go 1.11-1.24+，为高性能应用开发提供完整 Go 工具链。
    *   **Ruby**：支持 Ruby 2.4-3.4，尤其适合 Ruby on Rails 等框架开发。
    *   **.NET**：支持 .NET SDK 2.0-10.0 诸多版本（Windows 专属），全面满足 .NET (Core/5+) 项目的编译与运行。
    *   **Rust**：集成高性能高安全 Rust 语言，轻松本地开发与调试。
*   **强大数据库支持及多实例能力**：
    *   **关系型数据库**：内置 MySQL、MariaDB、PostgreSQL，支持多版本同时运行。
    *   **NoSQL 数据库**：集成 Redis、Memcached、MongoDB 等主流 NoSQL 数据库，开箱即用。
    *   **数据库管理工具**：内置 phpMyAdmin 和 Adminer，数据库管理更便捷。
*   **高性能 Web 服务器及灵活配置**：
    *   支持 Caddy、Nginx、Apache 等主流 Web 服务器，并配备可视化配置界面。
*   **内置 ServBay CA，实现专业本地 PKI 能力**：
    *   ServBay 内建完整证书颁发机构（CA），包含 **ServBay 用户 CA**（自定义根证书）和 **ServBay 公共 CA**（可签发被公网信任证书的中间 CA）。
    *   用户可轻松创建和管理自有根 CA 及中间 CA，为本地开发环境所有站点和服务颁发自定义 SSL 证书，实现真正的本地 HTTPS 开发，彻底消除浏览器安全警告。
    *   提供完善的证书管理功能，包括证书生成、吊销、导入与导出。
*   **AI 与大模型（LLM）支持**：
    *   **Ollama 集成**：一键安装及管理 Ollama 服务，本地运行和调试各类开源大语言模型（如 DeepSeek、Llama 3、Qwen）轻而易举。
    *   赋能本地 AI 应用开发与集成。
*   **开发者友好功能**：
    *   **图形化管理界面**：简洁直观 UI 一键管理全部服务与配置。
    *   **一键启动/停止服务**：快速启停整个开发环境。
    *   **公网 SSL 证书申请**：通过 **ACME 协议**，支持 Let's Encrypt、ZeroSSL、Google Trust Services 免费申请域名证书，助力项目演示或测试上线。
    *   **自定义域名**：本地开发域名统一管理。
    *   **命令行支持**：内置全套命令行工具，`php`、`node`、`python`、`go`、`java`、`mysql` 等命令即开即用。
    *   **多站点管理**：便捷配置和切换多个网站项目，支持项目级运行环境定制。
    *   **反向代理**：通过域名轻松访问本地运行的应用（例如 Docker、其他 Node.js 服务）。
    *   **日志管理**：统一查看与管理各类服务日志。
    *   **绿色安装与备份**：ServBay 采用绿色安装方式，不污染系统环境，便于备份、迁移与卸载。
    *   **开机自启动**：可设为随系统自动启动，确保服务始终在线。

*部分功能随版本更新有所变化，具体请以官方文档为准。*

![ServBay Windows 版本界面截图：网站管理](screenshots/website.png)

## 📥 如何下载

你可以在本仓库的 **[发布页面](../../releases)** 获取全部 ServBay Windows 版本。

1.  访问 [Releases 发布页面](../../releases)。
2.  选择你需要的版本（一般建议选择最新稳定版本）。
3.  在所选版本的 “Assets” 区域下载相应的安装包（如 `.exe` 或 `.zip` 文件）。
4.  下载完成后，按照相应文档进行安装。

## 💬 问题反馈与社区支持

我们非常重视你的反馈！如果你在使用 ServBay for Windows 过程中遇到任何问题、有建议或发现 Bug，欢迎通过以下渠道联系我们：

*   **仓库提 Issue**：请在 [ServBay-Windows-Release Issues 页面](../../issues)详细描述遇到的问题。
*   **邮件反馈**：发送邮件至 [support@servbay.com](mailto:support@servbay.com)。
*   **社区支持**：加入我们的官方社群，与其他开发者交流经验、获取帮助：
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   微信群: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

提 Issue 时，请尽量详细描述问题、复现步骤、操作系统环境及 ServBay 版本号等，这将帮助我们更快定位和解决问题。

## 🔗 相关链接

*   **ServBay 官方网站**：[https://www.servbay.com](https://www.servbay.com)
*   **ServBay macOS 版本下载/主仓库**：[https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **ServBay 官方文档/支持中心**：[https://support.servbay.com/](https://support.servbay.com/)

感谢你选择 ServBay！我们将始终致力于为你带来最强大、最高效的本地开发体验。