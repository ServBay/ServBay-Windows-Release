# ServBay Windows-Version Veröffentlichungen

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Neueste Version](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](../../releases/latest)
[![GitHub Downloads](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](../../releases)

Willkommen im offiziellen Release-Repository der ServBay Windows-Version. In diesem Repository finden Sie die offiziellen Bereitstellungspakete und Changelogs von ServBay für Windows.

## 🚀 ServBay: Die ultimative lokale Entwicklungsplattform für Entwickler

ServBay ist eine **All-in-One-, leistungsstarke und benutzerfreundliche** Integrationslösung für lokale Webentwicklungsumgebungen, die speziell für Entwickler entwickelt wurde. Unser Ziel ist es, lästige Konfigurationsschritte zu eliminieren, sodass Sie in Minuten eine leistungsstarke und hochgradig anpassbare Entwicklungsumgebung einrichten können – damit Sie sich voll und ganz auf das Programmieren und Ihre Ideen konzentrieren können.

ServBay ist weit mehr als nur eine Ansammlung von Tools; es ist ein **vollständiges Ökosystem**, das eine **unvergleichliche Entwicklungserfahrung und enorme Leistungsfähigkeit** bietet. Ob Sie Webentwickler, Backend-Engineer, Data Scientist oder AI-Enthusiast sind – ServBay erfüllt vielseitige Anforderungen.

Dieses Repository dient ausschließlich zur Bereitstellung der **Windows-Version** von ServBay.

![Screenshot der ServBay Windows-Version: Softwares](screenshots/softwares.png)

## ✨ ServBay – Kernfunktionen & Leistungsstarke Features

ServBay bietet eine umfassende Sammlung von Tools und leistungsstarken Funktionen, um Ihre Produktivität als Entwickler zu steigern:

*   **Umfangreicher Sprachensupport mit nahtlosem Versionswechsel:**
    *   **PHP**: Unterstützung mehrerer Versionen von PHP 5.6 bis zum neuesten PHP 8.x – der Wechsel erfolgt mit nur einem Klick, um unterschiedliche Projektanforderungen zu erfüllen.
    *   **Node.js**: Integrierte Unterstützung mehrerer Versionen von Node.js 12 bis Node.js 24 – einfaches Verwalten von Projekt-Abhängigkeiten.
    *   **Python**: Vollständige Unterstützung für Python 2.7 sowie Python 3.5 bis 3.14+, perfekt für Webentwicklung, Data Science und Machine Learning-Projekte.
    *   **Java**: Integration mehrerer OpenJDK-Versionen (7 bis 24) und eingebauter Apache Maven-Support – erleichtert das Build- und Management von Java-Projekten.
    *   **Go (Golang)**: Support von Go 1.11 bis 1.24+ – eine vollständige Go-Toolchain für hochleistungsfähige Anwendungen.
    *   **Ruby**: Unterstützung für Ruby 2.4 bis 3.4 – ideal für Frameworks wie Ruby on Rails.
    *   **.NET**: Umfassender Support von .NET SDK 2.0 bis 10.0 (Windows-Version), erfüllt alle Anforderungen für Build und Betrieb verschiedenster .NET (Core/5+)-Projekte.
    *   **Rust**: Integrierte Hochleistungs- und Sicherheits-Programmiersprache Rust für komfortable lokale Entwicklung und Testen.
*   **Starke Datenbankunterstützung mit Multi-Instanz-Fähigkeit:**
    *   **Relationale Datenbanken**: Integrierte Versionen von MySQL, MariaDB und PostgreSQL – gleichzeitiger Betrieb mehrerer Versionen möglich.
    *   **NoSQL-Datenbanken**: Integrierte, sofort einsatzbereite NoSQL-Datenbanken wie Redis, Memcached und MongoDB.
    *   **Datenbank-Verwaltungstools**: Eingebaute Tools wie phpMyAdmin und Adminer für eine einfache Datenbankverwaltung.
*   **Leistungsstarke Webserver mit flexibler Konfiguration:**
    *   Support für gängige Webserver wie Caddy, Nginx und Apache – inklusive visueller Konfigurationsoberfläche.
*   **Integrierte ServBay CA für leistungsfähige lokale PKI-Funktionen:**
    *   ServBay beinhaltet eine vollständige Certificate Authority, **ServBay CA**, bestehend aus **ServBay User CA** (für benutzerdefinierte Root-Zertifikate) und **ServBay Public CA** (eine Pre-CA für Ausstellung öffentlich vertrauenswürdiger Zertifikate).
    *   Sie können ganz einfach eigene Root- und Zwischen-CAs erstellen und verwalten, um benutzerdefinierte SSL-Zertifikate für alle lokalen Sites und Services auszustellen – für echtes lokales HTTPS und ohne Sicherheitswarnungen im Browser.
    *   Umfassende Zertifikatverwaltung inklusive Erzeugung, Widerruf, Import und Export.
*   **AI- und LLM-Integration:**
    *   **Ollama-Integration**: Ein-Klick-Installation und -Verwaltung des Ollama-Dienstes – Sie können einfach unterschiedliche Open-Source-Large-Language-Models (z. B. DeepSeek, Llama 3, Qwen) lokal ausführen und debuggen.
    *   Ermöglicht die nahtlose Entwicklung und Integration eigener KI-Anwendungen.
*   **Entwicklerfreundliche Funktionen:**
    *   **Grafische Verwaltungsoberfläche**: Aufgeräumte und intuitive UI zur einfachen Verwaltung aller Dienste und Konfigurationen.
    *   **Services schnell starten/stoppen**: Mit einem Klick kann der Ausführungsstatus der gesamten Umgebung gesteuert werden.
    *   **Öffentliche SSL-Zertifikate beantragen**: Unterstützung der Beantragung kostenloser öffentlicher SSL-Zertifikate von Let's Encrypt, ZeroSSL und Google Trust Services über das **ACME-Protokoll** – ideal für öffentliche Demos oder Tests.
    *   **Eigene Domains**: Einfache Verwaltung lokaler Entwicklungsdomains.
    *   **Kommandozeilen-Support**: Umfassende CLI-Werkzeuge, direkter Zugriff auf Befehle wie `php`, `node`, `python`, `go`, `java`, `mysql` im Terminal.
    *   **Multi-Site-Management**: Mehrere Website-Projekte komfortabel konfigurieren und betreiben – inklusive projektbezogenem Runtime-Setup.
    *   **Reverse Proxy-Unterstützung**: Einfache Erreichbarkeit von lokal laufenden Anwendungen (wie Docker oder andere Node.js-Services) über Domains.
    *   **Log-Management**: Bequeme Ansicht und Verwaltung von Logs aller Dienste.
    *   **Sauberes System & Backup**: ServBay verwendet eine portable Installation – es werden keine Systemdateien verändert; einfaches Backup, Migration und Löschen.
    *   **Autostart**: Kann so eingerichtet werden, dass ServBay beim Systemstart automatisch startet und die Services sofort verfügbar sind.

*Einzelne Funktionen können sich mit Versionen ändern. Bitte schauen Sie in der offiziellen Dokumentation für den aktuellsten Stand nach.*


![Screenshot der ServBay Windows-Version: Website](screenshots/website.png)


## 📥 Download-Anleitung

Alle verfügbaren Windows-Versionen von ServBay finden Sie auf der **[Releases-Seite](../../releases)** dieses Repositories.

1.  Besuchen Sie die [Releases-Seite](../../releases).
2.  Wählen Sie die gewünschte Version aus (empfohlen wird in der Regel die neueste stabile Version).
3.  Im Abschnitt „Assets“ des jeweiligen Releases laden Sie das entsprechende Installationspaket herunter (z. B. `.exe`- oder `.zip`-Datei).
4.  Folgen Sie nach dem Download den Installationsanweisungen.

## 💬 Fehler melden & Community-Support

Ihr Feedback ist uns sehr wichtig! Sollten Sie bei der Nutzung der ServBay Windows-Version auf ein Problem stoßen, Anregungen haben oder einen Bug melden wollen, kontaktieren Sie uns bitte über einen der folgenden Wege:

*   **Issue im Repository erstellen**: Beschreiben Sie Ihr Problem ausführlich auf der [ServBay-Windows-Release-Issues-Seite](../../issues).
*   **Feedback per E-Mail**: Schreiben Sie uns an [support@servbay.com](mailto:support@servbay.com).
*   **Community-Support**: Treten Sie unseren offiziellen Communities bei, tauschen Sie sich mit anderen Entwicklern aus, teilen Sie Ihre Erfahrungen und erhalten Sie Hilfe:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   WeChat-Gruppe: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Bitte geben Sie bei einem Issue so detailliert wie möglich an: das aufgetretene Problem, die Schritte zur Reproduktion, Ihr Betriebssystem und die ServBay-Version. Das hilft uns, Ihr Anliegen schnellstmöglich zu lösen.

## 🔗 Weiterführende Links

*   **Offizielle Website von ServBay**: [https://www.servbay.com](https://www.servbay.com)
*   **ServBay macOS-Version Download/Haupt-Repository**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **Offizielle Dokumentation/Support Center von ServBay**: [https://support.servbay.com/](https://support.servbay.com/)

Vielen Dank, dass Sie sich für ServBay entschieden haben! Wir geben unser Bestes, um Ihnen das leistungsfähigste und komfortabelste lokale Entwicklungserlebnis zu bieten.