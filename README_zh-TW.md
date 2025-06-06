# ServBay Windows 版本發佈

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![最新發佈版本](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](https://github.com/ServBay/ServBay-Windows-Release/releases/latest)
[![GitHub 下載總數](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](https://github.com/ServBay/ServBay-Windows-Release/releases)

歡迎來到 ServBay Windows 版的官方發佈倉庫。本倉庫用於存放 ServBay Windows 版的官方發佈安裝包與變更日誌。

## 🚀 ServBay：開發者的終極本機開發利器

ServBay 是一套專為開發者打造的**一站式、高效能、極易用**的本機 Web 開發環境整合方案。我們致力於消除繁複的環境配置步驟，讓你在短短幾分鐘內便能建立一個強大且高度自訂的開發環境，專注於編碼與創新。

ServBay 不僅僅是一組工具，而是一個**完整生態系統**，打造**無與倫比的開發體驗與超強能力**。無論你是網頁開發者、後端工程師、資料科學家，還是 AI 應用探索者，ServBay 都能滿足你多元的開發需求。

本倉庫專為分發 ServBay 的**Windows 版本**。

![ServBay Windows 版截圖：軟體管理](screenshots/softwares.png)

## ✨ ServBay 核心特色與超強功能

ServBay 為開發者提供了全面的工具組與強大的功能特性，顯著提升工作效率：

*   **全面語言支援，靈活切換版本**：
    *   **PHP**：支援從 PHP 5.6 到最新版 PHP 8.x，多版本一鍵切換，靈活對應不同專案需求。
    *   **Node.js**：內建支援從 Node.js 12 至 24 多版本，輕鬆管理專案依賴。
    *   **Python**：完整支援 Python 2.7 及 Python 3.5 ~ 3.14+，滿足 Web、資料科學與機器學習等開發場景。
    *   **Java**：集成多個 OpenJDK 7~24 版本，內建 Apache Maven，簡化 Java 專案建置與管理。
    *   **Go (Golang)**：支援 Go 1.11~1.24+，提供完整 Go 工具鏈，用於高效能應用開發。
    *   **Ruby**：支援 Ruby 2.4~3.4，特別適合 Ruby on Rails 等框架開發。
    *   **.NET**：廣泛支援 .NET SDK 2.0~10.0（Windows 版），滿足多元 .NET（Core/5+）專案建構與執行需求。
    *   **Rust**：集成高效能、安全性的 Rust 語言，方便進行本機開發與測試。
*   **強大資料庫支援，多實例能力**：
    *   **關聯式資料庫**：內建 MySQL、MariaDB、PostgreSQL，支援多版本同時運行。
    *   **NoSQL 資料庫**：內建常見 NoSQL 資料庫，如 Redis、Memcached、MongoDB，開箱即用。
    *   **資料庫管理工具**：整合 phpMyAdmin 與 Adminer，便於資料管理維護。
*   **高效能 Web 伺服器，彈性配置**：
    *   支援主流 Web 伺服器如 Caddy、Nginx、Apache，並具備視覺化設定介面。
*   **內建 ServBay CA，強大本地 PKI 能力**：
    *   ServBay 內含完整憑證簽發系統 **ServBay CA**，包含 **ServBay User CA**（使用者自訂根憑證）與 **ServBay Public CA**（公信預備 CA，用於簽發公開憑證）。
    *   用戶可輕鬆建立並管理自有根與中繼 CA，為本地所有網站及服務簽發專屬 SSL 憑證，實現真正的本地端 HTTPS 開發，徹底消除瀏覽器安全警告。
    *   提供憑證產生、撤銷、匯入與匯出等完整管理功能。
*   **AI 與大語言模型（LLM）支援**：
    *   **Ollama 整合**：一鍵安裝與管理 Ollama 服務，在本地輕鬆運行與調試多種開源大語言模型（如 DeepSeek、Llama 3、Qwen 等）。
    *   加速本地 AI 應用開發與整合。
*   **友善開發者特性**：
    *   **圖形化管理介面**：乾淨直覺的 UI，輕鬆管理所有服務與配置。
    *   **一鍵啟動/停止服務**：快速掌握整個開發環境的運行狀態。
    *   **公開 SSL 憑證申請**：內建支援 **ACME 協議**，一鍵申請 Let's Encrypt、ZeroSSL、Google Trust Services 等免費公開 SSL 憑證，方便公開展示或測試。
    *   **自訂開發域名**：輕鬆管理本地專案的域名指派。
    *   **命令列工具支援**：完備的命令列工具組，可於終端直接使用 `php`、`node`、`python`、`go`、`java`、`mysql` 等指令。
    *   **多站點管理**：輕鬆配置與運行多個網站專案，支援專案層級的執行環境設定。
    *   **反向代理支援**：方便以域名方式存取本地運行的應用（如 Docker、其他 Node.js 服務）。
    *   **日誌管理**：一站式查看並管理各項服務的運行日誌。
    *   **綠色安裝與備份**：ServBay 採用綠色安裝方式，完全不污染系統環境，易於備份、搬移與刪除。
    *   **開機自動啟動**：可設定隨系統開機自動執行，確保服務穩定在線。

*部分功能將依版本更新有所差異，請參閱官方文件以瞭解最新支援狀況。*

![ServBay Windows 版截圖：網站管理](screenshots/website.png)

## 📥 如何下載

你可以於本倉庫的 **[發佈頁面](https://github.com/ServBay/ServBay-Windows-Release/releases)** 下載所有可用的 ServBay Windows 版。

1.  造訪 [發佈頁面](https://github.com/ServBay/ServBay-Windows-Release/releases)。
2.  選擇所需版本（一般建議選最新穩定發佈版）。
3.  在該版本的「Assets」區塊中下載對應的安裝包（通常為 `.exe` 或 `.zip` 檔案）。
4.  下載完成後，請依安裝指南進行安裝。

## 💬 問題回報與社群支援

我們非常重視你的反饋！如果你在使用 ServBay Windows 版時遇到任何問題、有建議或發現 Bug，請透過下列方式聯繫我們：

*   **在本倉庫提交 Issue**：請詳述問題於 [ServBay-Windows-Release Issues 頁](https://github.com/ServBay/ServBay-Windows-Release/issues)。
*   **郵件反饋**：發送電子郵件至 [support@servbay.com](mailto:support@servbay.com)。
*   **社群支持**：加入我們的官方社群，與其他開發者互動、分享經驗、尋求協助：
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   微信交流群: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

回報問題時，請盡可能詳細說明問題描述、重現步驟、操作系統環境以及 ServBay 版本，這將有助於我們更快速定位並解決問題。

## 🔗 相關連結

*   **ServBay 官方網站**：[https://www.servbay.com](https://www.servbay.com)
*   **ServBay macOS 版下載／主倉庫**：[https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **ServBay 官方文件／支援中心**：[https://support.servbay.com/](https://support.servbay.com/)

感謝你選擇 ServBay！我們致力於帶給你最強大、最便利的本地開發體驗。