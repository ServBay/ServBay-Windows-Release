# ServBay Windows 버전 릴리즈

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Latest Release](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](https://github.com/ServBay/ServBay-Windows-Release/releases/latest)
[![GitHub Releases](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](https://github.com/ServBay/ServBay-Windows-Release/releases)

ServBay Windows 버전의 공식 릴리즈 저장소에 오신 것을 환영합니다. 이 저장소는 ServBay의 Windows용 공식 릴리즈 패키지와 변경 로그를 제공합니다.

## 🚀 ServBay: 개발자를 위한 궁극의 로컬 개발 환경

ServBay는 **원스톱, 고성능, 사용자 친화적인** 로컬 웹 개발 환경 통합 솔루션으로, 개발자를 위해 설계되었습니다. 지루한 환경 설정 과정을 없애고, 몇 분 만에 강력하고 높은 커스터마이즈가 가능한 개발 환경을 구축할 수 있도록 하여, 오직 코딩과 혁신에만 집중할 수 있게 돕습니다.

ServBay는 단순한 도구 모음이 아닙니다. **비교할 수 없는 개발 경험과 강력한 기능**을 제공하는 **완전한 생태계**입니다. 웹 개발자, 백엔드 엔지니어, 데이터 과학자, AI 애플리케이션을 탐구하는 분들 등, ServBay는 다양한 요구를 충족시킬 수 있습니다.

이 저장소는 ServBay의 **Windows 버전** 배포를 위한 공식 저장소입니다.

![ServBay Windows 버전 스크린샷: 소프트웨어](screenshots/softwares.png)

## ✨ ServBay의 주요 기능 및 강력한 지원

ServBay는 개발자의 생산성을 극대화할 수 있도록 다양한 도구들과 강력한 기능을 제공합니다:

*   **다양한 언어 지원 및 버전 전환을 한 번에**:
    *   **PHP**: PHP 5.6부터 최신 PHP 8.x까지 다양한 버전을 지원하며, 한 번의 클릭으로 전환하여 프로젝트별 요구사항을 만족할 수 있습니다.
    *   **Node.js**: Node.js 12부터 24까지 여러 버전을 내장 지원하여 프로젝트 의존성 관리가 쉽습니다.
    *   **Python**: Python 2.7과 3.5 ~ 3.14+ 광범위한 버전을 지원해 웹 개발, 데이터 과학, 머신러닝 프로젝트에 적합합니다.
    *   **Java**: OpenJDK 7~24의 다양한 버전 통합, Apache Maven 내장 지원으로 Java 프로젝트 빌드와 관리가 간편합니다.
    *   **Go (Golang)**: Go 1.11 ~ 1.24+ 지원, 고성능 애플리케이션 개발을 위한 완벽한 Go 툴체인 제공.
    *   **Ruby**: Ruby 2.4 ~ 3.4 지원으로 Ruby on Rails 등 프레임워크 기반 개발에 최적화됩니다.
    *   **.NET**: .NET SDK 2.0 ~ 10.0 (Windows 버전) 폭넓게 지원, 다양한 .NET(Core/5+) 프로젝트 빌드와 실행 요구를 충족합니다.
    *   **Rust**: 성능과 안정성이 뛰어난 Rust 언어를 통합해, 로컬 개발과 테스트가 편리합니다.
*   **강력한 데이터베이스 지원과 멀티 인스턴스 기능**:
    *   **관계형 데이터베이스**: MySQL, MariaDB, PostgreSQL 내장, 여러 버전을 동시에 실행 가능.
    *   **NoSQL 데이터베이스**: Redis, Memcached, MongoDB 등 주요 NoSQL 데이터베이스 내장 즉시 사용 가능.
    *   **데이터베이스 관리 툴**: phpMyAdmin, Adminer 내장으로 데이터베이스 관리를 쉽게 할 수 있습니다.
*   **유연한 설정이 가능한 고성능 웹 서버**:
    *   Caddy, Nginx, Apache 등 주요 웹 서버 지원, 시각적 설정 인터페이스 제공.
*   **강력한 로컬 PKI 기능의 내장 ServBay CA**:
    *   ServBay는 **ServBay User CA**(사용자 정의 루트 인증서)와 **ServBay Public CA**(공개 신뢰 인증서 발급용 사전 CA)로 구성된 자체 인증기관, **ServBay CA**를 내장하고 있습니다.
    *   사용자는 손쉽게 자체 루트 CA 및 중간 CA를 생성·관리하고, 로컬 개발 환경 내 모든 사이트와 서비스에 대한 맞춤형 SSL 인증서를 발급할 수 있어 진정한 로컬 HTTPS 개발을 구현하며, 브라우저 보안 경고를 완전히 제거합니다.
    *   인증서 생성, 폐기, 가져오기, 내보내기 등 포괄적인 인증서 관리 기능 제공.
*   **AI 및 대형 언어 모델(LLM) 지원**:
    *   **Ollama 연동**: Ollama 서비스를 원클릭 설치·관리, 다양한 오픈소스 LLM(예: DeepSeek, Llama 3, Qwen 등)을 손쉽게 로컬에서 실행 및 디버깅 가능.
    *   로컬 AI 애플리케이션 개발 및 통합 기능 강화.
*   **개발자를 위한 다양한 기능**:
    *   **그래픽 관리 인터페이스**: 직관적이고 깔끔한 UI로 모든 서비스와 설정을 손쉽게 관리.
    *   **원클릭 서비스 시작/중지**: 전체 개발 환경의 실행 상태를 빠르게 제어.
    *   **공개 SSL 인증서 발급**: **ACME 프로토콜**을 통해 Let's Encrypt, ZeroSSL, Google Trust Services에서 무료 공개 SSL 인증서를 신청·발급받아 퍼블릭 데모나 테스트에 활용 가능.
    *   **맞춤 도메인 관리**: 로컬 개발 도메인을 손쉽게 관리.
    *   **명령어 지원**: 터미널에서 `php`, `node`, `python`, `go`, `java`, `mysql` 등 각종 명령어를 바로 사용할 수 있는 포괄적 CLI 도구 제공.
    *   **멀티 사이트 관리**: 프로젝트 단위 런타임 환경 설정 지원으로 여러 웹사이트 프로젝트를 쉽게 구성 및 실행 가능.
    *   **리버스 프록시 지원**: 도메인으로 Docker, 기타 Node.js 서비스 등 로컬 실행 중인 앱에 간편하게 접속.
    *   **로그 관리**: 다양한 서비스의 로그를 쉽게 조회·관리.
    *   **클린 시스템 & 백업**: ServBay는 무설치(그린) 방식으로 시스템 환경을 오염시키지 않으며 백업, 마이그레이션, 삭제가 간편합니다.
    *   **자동 부팅 시 시작**: 시스템 기동 시 자동 시작 설정이 가능, 항상 가용성 보장.

*일부 기능은 버전 업데이트에 따라 달라질 수 있습니다. 최신 기능은 공식 문서를 참조하세요.*

![ServBay Windows 버전 스크린샷: 웹사이트](screenshots/website.png)

## 📥 다운로드 방법

모든 ServBay Windows 버전은 이 저장소의 **[Releases 페이지](https://github.com/ServBay/ServBay-Windows-Release/releases)** 에서 확인할 수 있습니다.

1.  [Releases 페이지](https://github.com/ServBay/ServBay-Windows-Release/releases)에 접속합니다.
2.  필요에 따라 버전을 선택하세요 (일반적으로 최신 안정화 버전을 권장합니다).
3.  선택한 릴리즈의 "Assets" 섹션에서 해당 인스톨러 패키지(예: `.exe` 또는 `.zip` 파일)를 다운로드합니다.
4.  다운로드 완료 후 안내에 따라 설치를 진행하세요.

## 💬 이슈 보고 및 커뮤니티 지원

여러분의 피드백은 매우 소중합니다! ServBay for Windows를 사용하시다가 문제가 발생하거나, 개선 제안 또는 버그가 있다면 아래 채널을 통해 문의해 주세요.

*   **이 저장소에 이슈 등록**: [ServBay-Windows-Release Issues 페이지](https://github.com/ServBay/ServBay-Windows-Release/issues)에 상세한 문제 상황을 남겨주세요.
*   **이메일 피드백**: [support@servbay.com](mailto:support@servbay.com) 으로 이메일을 보내주세요.
*   **커뮤니티 지원**: 공식 커뮤니티에 참여해 다른 개발자들과 소통하고 경험을 공유하거나 도움을 받을 수 있습니다:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   WeChat 그룹: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

이슈를 제출할 때는 문제 상황, 재현 방법, 사용 환경(OS), ServBay 버전 정보를 최대한 구체적으로 작성해 주세요. 그래야 더 빠른 문제 파악과 해결이 가능합니다.

## 🔗 관련 링크

*   **ServBay 공식 웹사이트**: [https://www.servbay.com](https://www.servbay.com)
*   **ServBay macOS 버전 다운로드/메인 저장소**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **ServBay 공식 문서/지원 센터**: [https://support.servbay.com/](https://support.servbay.com/)

ServBay를 선택해주셔서 감사합니다! 최강의 편리한 로컬 개발 환경을 제공하기 위해 최선을 다하겠습니다.