# ServBay Windows Versie Releases

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Nieuwste Release](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](https://github.com/ServBay/ServBay-Windows-Release/releases/latest)
[![GitHub Releases](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](https://github.com/ServBay/ServBay-Windows-Release/releases)

Welkom bij de officiële release repository van de Windows-versie van ServBay. In deze repository vind je de officiële releasepakketten en changelogs voor ServBay op Windows.

## 🚀 ServBay: Dé Ultieme Lokale Ontwikkelomgeving voor Developers

ServBay is een **alles-in-één, krachtige en gebruiksvriendelijke** lokale webontwikkelomgeving, speciaal ontworpen voor ontwikkelaars. Wij nemen het ingewikkelde configureren van de omgeving volledig uit handen, zodat jij in enkele minuten een krachtige en hoogst aanpasbare ontwikkelomgeving gereed hebt. Zo kun je je volledig richten op het programmeren en innoveren.

ServBay is niet zomaar een verzameling tools; het is een **volledig ecosysteem** dat je een **ongeëvenaarde ontwikkelervaring en ongekende mogelijkheden** biedt. Of je nu een webontwikkelaar, backend-engineer, data scientist of AI-ontwikkelaar bent, ServBay ondersteunt jouw uiteenlopende ontwikkelbehoeftes.

Deze repository is speciaal voor de distributie van de **Windows-versie** van ServBay.

![ServBay Windows versie screenshot: Softwarepakketten](screenshots/softwares.png)

## ✨ ServBay Kernfuncties & Supersnelle Mogelijkheden

ServBay biedt een uitgebreide toolset en krachtige functies om de productiviteit van ontwikkelaars te maximaliseren:

*   **Uitgebreide Taalondersteuning en Naadloos Wisselen van Versies**:
    *   **PHP**: Ondersteunt meerdere versies van PHP 5.6 tot en met de nieuwste PHP 8.x; met één klik wisselen tussen versies voor diverse projecten.
    *   **Node.js**: Ingebouwde ondersteuning voor versies van Node.js 12 tot en met Node.js 24; eenvoudig projectafhankelijkheden beheren.
    *   **Python**: Volledige ondersteuning voor Python 2.7 en Python 3.5 t/m 3.14+; ideaal voor webontwikkeling, data science en machine learning projecten.
    *   **Java**: Integreert verschillende versies van OpenJDK (7 t/m 24) plus ingebouwde Apache Maven, voor eenvoudig bouwen en beheren van Java-projecten.
    *   **Go (Golang)**: Ondersteuning voor Go 1.11 t/m 1.24+; volledige Go-toolchain voor high-performance applicatieontwikkeling.
    *   **Ruby**: Ondersteunt Ruby 2.4 t/m 3.4; ideaal voor het ontwikkelen met frameworks zoals Ruby on Rails.
    *   **.NET**: Brede ondersteuning voor .NET SDK 2.0 t/m 10.0 (Windows-versie); geschikt voor het bouwen en uitvoeren van uiteenlopende .NET (Core/5+) projecten.
    *   **Rust**: Geïntegreerde, krachtige en veilige Rust-ondersteuning voor lokaal ontwikkelen en testen.
*   **Robuuste Databaseondersteuning met Multi-Instance Mogelijkheid**:
    *   **Relationele databases**: Ingebouwde MySQL, MariaDB, PostgreSQL, ondersteunt meerdere versies tegelijkertijd.
    *   **NoSQL-databases**: Direct bruikbare integraties van Redis, Memcached en MongoDB.
    *   **Databasebeheer Tools**: Ingebouwde phpMyAdmin en Adminer voor gemakkelijke database-administratie.
*   **High-performance Webservers met Flexibel Beheer**:
    *   Ondersteuning voor gangbare webservers zoals Caddy, Nginx en Apache, met visuele configuratie-interface.
*   **Ingebouwde ServBay CA voor Krachtig Lokaal PKI Beheer**:
    *   ServBay bevat een complete certificaatautoriteit, **ServBay CA**, bestaande uit **ServBay User CA** (voor gebruikers gedefinieerde rootcertificaten) en **ServBay Public CA** (pre-CA voor uitgifte van publiek vertrouwde certificaten).
    *   Gebruikers kunnen eenvoudig zelf root- en intermediate CAs aanmaken en beheren, en eigen SSL-certificaten uitgeven voor alle lokale sites en services. Hiermee kun je echt lokaal via HTTPS ontwikkelen en behoren browserbeveiligingswaarschuwingen tot het verleden.
    *   Biedt uitgebreide certificaatbeheer-functies zoals genereren, intrekken, importeren en exporteren van certificaten.
*   **AI- & Large Language Model (LLM) Ondersteuning**:
    *   **Ollama-integratie**: Installeer en beheer de Ollama-service met één klik en draai eenvoudig open-source large language models (zoals DeepSeek, Llama 3, Qwen) op jouw eigen pc.
    *   Versterk lokale AI-applicatieontwikkeling en integratie.
*   **Ontwikkelaarvriendelijke Functies**:
    *   **Grafische Beheerinterface**: Strakke, intuïtieve UI voor eenvoudig beheer van alle services en instellingen.
    *   **Één Klik Start/Stop Services**: Snel beheer over de status van je hele ontwikkelomgeving.
    *   **Publieke SSL-certificaten aanvragen**: Ondersteunt gratis publieke SSL-certificaten van Let's Encrypt, ZeroSSL en Google Trust Services via het **ACME-protocol**; ideaal voor publieke demo’s of testen.
    *   **Eigen Doeminen**: Beheer eenvoudig lokale ontwikkeldomeinen.
    *   **Command-line Ondersteuning**: Uitgebreide command-line tools; gebruik commando’s als `php`, `node`, `python`, `go`, `java`, `mysql` direct in de terminal.
    *   **Multi-site Beheer**: Configureer en beheer eenvoudig meerdere websiteprojecten met per-project runtime specifieke omgevingen.
    *   **Reverse Proxy Ondersteuning**: Benader lokaal draaiende applicaties (zoals Docker of andere Node.js services) gemakkelijk via domeinnamen.
    *   **Logbeheer**: Eenvoudig logs van verschillende services bekijken en beheren.
    *   **Schoon Systeem & Back-up**: ServBay gebruikt een ‘schone installatie’, waardoor je systeem niet vervuild wordt en eenvoudig te back-uppen, migreren of verwijderen is.
    *   **Opstarten bij Systeemstart**: Kan zo ingesteld worden dat ServBay automatisch met Windows start en je diensten dus altijd direct beschikbaar zijn.

*Specifieke functies kunnen verschillen per versie. Raadpleeg de officiële documentatie voor de laatste informatie.*

![ServBay Windows versie screenshot: Website](screenshots/website.png)

## 📥 Hoe Downloaden

Alle beschikbare Windows-versies van ServBay vind je op de **[Releases-pagina](https://github.com/ServBay/ServBay-Windows-Release/releases)** van deze repository.

1.  Ga naar de [Releases-pagina](https://github.com/ServBay/ServBay-Windows-Release/releases).
2.  Kies de gewenste versie (het wordt aangeraden om de nieuwste stabiele release te kiezen).
3.  Download bij de geselecteerde release onder "Assets" het juiste installatiepakket (zoals een `.exe` of `.zip` bestand).
4.  Volg na het downloaden de installatiegids voor de installatie.

## 💬 Problemen Melden & Community Support

Jouw feedback is erg belangrijk voor ons! Ervaar je problemen met ServBay voor Windows, heb je suggesties of ontdek je een bug? Neem dan contact met ons op via de volgende kanalen:

*   **Open een Issue in deze Repository**: Omschrijf je probleem in detail op de [ServBay-Windows-Release Issues-pagina](https://github.com/ServBay/ServBay-Windows-Release/issues).
*   **E-mailfeedback**: Stuur een e-mail naar [support@servbay.com](mailto:support@servbay.com).
*   **Community Support**: Word lid van onze officiële communities om andere ontwikkelaars te ontmoeten, ervaringen te delen en hulp te krijgen:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   WeChat-groep: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Vermeld bij het melden van een issue zo uitgebreid mogelijk het probleem, de stappen om het te reproduceren, je besturingssysteem en het ServBay versienummer. Zo kunnen we je sneller en beter helpen.

## 🔗 Gerelateerde Links

*   **Officiële website ServBay**: [https://www.servbay.com](https://www.servbay.com)
*   **ServBay macOS Versie Download/Hoofdrepo**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **Officiële documentatie / Support Center**: [https://support.servbay.com/](https://support.servbay.com/)

Bedankt dat je voor ServBay kiest! Wij zetten ons in om jou de meest krachtige en gebruiksvriendelijke lokale ontwikkelervaring te bieden.