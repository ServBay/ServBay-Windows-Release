# Serwery ServBay – Wydania dla Windows

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Najnowsze wydanie](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](./releases/latest)
[![Pobrania z GitHub](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](./releases)

Witamy w oficjalnym repozytorium wydań ServBay w wersji na Windows. To repozytorium zawiera oficjalne paczki instalacyjne oraz dzienniki zmian ServBay na Windows.

## 🚀 ServBay: Kompleksowa i wydajna platforma do lokalnego developmentu dla programistów

ServBay to **wszystko w jednym** – wysokowydajne, przyjazne w obsłudze środowisko integrujące narzędzia do lokalnego rozwoju stron i aplikacji, zaprojektowane specjalnie z myślą o programistach. Naszym celem jest wyeliminowanie żmudnych kroków konfiguracyjnych, byś mógł uruchomić potężne i w pełni dopasowane środowisko developerskie w kilka minut oraz skupić się na kodowaniu i innowacjach.

ServBay to znacznie więcej niż zbiór narzędzi – to **kompletny ekosystem**, który ma zapewnić **niezrównane doświadczenie developerskie i supermocne możliwości**. Niezależnie, czy jesteś web developerem, inżynierem backendu, data scientistą, czy eksploratorem AI – ServBay sprosta wszystkim Twoim wymaganiom.

To repozytorium przeznaczone jest wyłącznie do dystrybucji **wersji na Windows** ServBay.

![Zrzut ekranu ServBay dla Windows: Oprogramowanie](screenshots/softwares.png)

## ✨ Kluczowe funkcje i możliwości ServBay

ServBay oferuje kompleksowy zestaw narzędzi i funkcji, które maksymalizują produktywność programistów:

*   **Szerokie wsparcie języków programowania z płynnym przełączaniem wersji**:
    *   **PHP**: Obsługa wielu wersji od PHP 5.6 do najnowszego PHP 8.x – szybka zmiana wersji jednym kliknięciem, aby sprostać różnym wymaganiom projektowym.
    *   **Node.js**: Wbudowane wsparcie dla wielu wersji od Node.js 12 do 24 – łatwe zarządzanie zależnościami w Twoich projektach.
    *   **Python**: W pełni obsługiwane wersje od Python 2.7 i 3.5 do 3.14+, wspierając projekty webowe, data science i machine learning.
    *   **Java**: Integracja różnych wersji OpenJDK od 7 do 24 oraz wbudowany Apache Maven – uproszczone budowanie i zarządzanie projektami Java.
    *   **Go (Golang)**: Wsparcie od Go 1.11 do 1.24+, kompletny toolchain do tworzenia wydajnych aplikacji.
    *   **Ruby**: Obsługa Ruby 2.4–3.4, idealne dla frameworków takich jak Ruby on Rails.
    *   **.NET**: Szeroka obsługa SDK .NET 2.0–10.0 (na Windows), spełniająca wymagania budowy i uruchamiania projektów .NET (Core/5+).
    *   **Rust**: Zintegrowane środowisko wydajnego, bezpiecznego języka Rust – wygodny rozwój i testowanie lokalne.
*   **Wydajne bazy danych z obsługą wielu instancji**:
    *   **Relacyjne bazy danych**: Wbudowany MySQL, MariaDB, PostgreSQL – możliwość uruchamiania wielu wersji równocześnie.
    *   **Bazy NoSQL**: Zintegrowane popularne silniki NoSQL, takie jak Redis, Memcached, MongoDB – gotowe do użycia od razu po instalacji.
    *   **Narzędzia do zarządzania bazami**: Wbudowane phpMyAdmin i Adminer – łatwa administracja baz danych.
*   **Wysokowydajne serwery WWW z elastyczną konfiguracją**:
    *   Wsparcie dla popularnych serwerów – Caddy, Nginx, Apache – z intuicyjnym interfejsem do konfiguracji wizualnej.
*   **Wbudowany CA ServBay – potężne możliwości lokalnego PKI**:
    *   ServBay dysponuje kompletnym Urzędem Certyfikacji (CA) – **ServBay CA**, obejmującym **ServBay User CA** (dla własnych certyfikatów głównych) oraz **ServBay Public CA** (pre-CA do wydawania certyfikatów zaufanych publicznie).
    *   Użytkownicy mogą łatwo tworzyć i zarządzać własnymi urzędami głównymi i pośrednimi oraz wydawać indywidualne certyfikaty SSL dla wszystkich stron i usług w swoim środowisku deweloperskim – zyskujesz prawdziwy lokalny HTTPS i eliminujesz ostrzeżenia przeglądarki.
    *   Pełna funkcjonalność zarządzania certyfikatami: generowanie, unieważnianie, import, eksport.
*   **Wsparcie AI i dużych modeli językowych (LLM)**:
    *   **Integracja z Ollama**: Jedno kliknięcie by zainstalować i zarządzać usługą Ollama – lokalne uruchamianie i debugowanie otwartych modeli językowych (np. DeepSeek, Llama 3, Qwen).
    *   Możliwość nowoczesnego developmentu i integracji aplikacji AI w środowisku lokalnym.
*   **Funkcje przyjazne programistom**:
    *   **GRAFICZNY Panel Zarządzania**: Czysty i intuicyjny interfejs do zarządzania wszystkimi usługami oraz ustawieniami.
    *   **Jednoklikowe uruchamianie/zatrzymywanie usług**: Szybka kontrola statusu całego środowiska.
    *   **Publiczne certyfikaty SSL**: Prosty proces uzyskania darmowych certyfikatów od Let's Encrypt, ZeroSSL, Google Trust Services przez **protokół ACME** – idealne do publicznych demonstracji lub testów.
    *   **Własne domeny**: Łatwe zarządzanie domenami lokalnego środowiska programistycznego.
    *   **Obsługa linii komend**: Kompletny zestaw narzędzi CLI – możliwość użycia `php`, `node`, `python`, `go`, `java`, `mysql` bezpośrednio z terminala.
    *   **Wielostronowe zarządzanie projektami**: Prosta konfiguracja i obsługa wielu projektów www – wsparcie dla definiowania ustawień środowiska dla każdego z nich osobno.
    *   **Wsparcie reverse proxy**: Wygodny dostęp przez domenę do lokalnych usług (np. Docker, inne serwery Node.js).
    *   **Zarządzanie logami**: Łatwy wgląd i kontrola logów wszystkich usług.
    *   **Czystość systemu & backup**: Instalacja typu "green", nie zaśmieca środowiska, łatwa w archiwizacji, migracji i usuwaniu.
    *   **Autostart przy uruchomieniu systemu**: Możliwość konfiguracji startu wraz z systemem – Twoje usługi zawsze gotowe!

*Niektóre funkcje mogą się różnić w zależności od wersji. Najnowsze możliwości znajdziesz w oficjalnej dokumentacji.*

![Zrzut ekranu ServBay dla Windows: Strona www](screenshots/website.png)

## 📥 Jak pobrać

Wszystkie dostępne wersje ServBay dla Windows znajdziesz na stronie **[Wydania](./releases)** w tym repozytorium.

1.  Odwiedź [stronę wydań](./releases).
2.  Wybierz wersję, której potrzebujesz (zalecamy zwykle najnowsze stabilne wydanie).
3.  W sekcji "Assets" wybranej wersji pobierz odpowiednią paczkę instalacyjną (`.exe` lub `.zip`).
4.  Po pobraniu postępuj zgodnie z instrukcją instalacji.

## 💬 Zgłaszanie problemów i wsparcie społeczności

Twoja opinia jest dla nas bardzo cenna! Jeśli napotkasz kłopoty podczas korzystania z ServBay na Windows, masz sugestie lub odkryjesz błąd – skontaktuj się z nami przez poniższe kanały:

*   **Dodaj zgłoszenie w tym repozytorium**: Opisz szczegółowo swój problem na [stronie zgłoszeń ServBay-Windows-Release](./issues).
*   **E-mail**: Wyślij swoje uwagi na adres [support@servbay.com](mailto:support@servbay.com).
*   **Wsparcie społeczności**: Dołącz do naszych oficjalnych społeczności, aby dyskutować, dzielić się doświadczeniami i uzyskać pomoc:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   Grupa WeChat: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Zgłaszając problem, opisz dokładnie sytuację, kroki powielające problem, środowisko systemowe oraz numer wersji ServBay. Ułatwi to szybką diagnostykę i rozwiązanie Twojego zgłoszenia.

## 🔗 Przydatne linki

*   **Oficjalna strona ServBay**: [https://www.servbay.com](https://www.servbay.com)
*   **Wersja macOS/Repozytorium główne**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **Oficjalna dokumentacja / Centrum wsparcia**: [https://support.servbay.com/](https://support.servbay.com/)

Dziękujemy, że wybrałeś ServBay! Z pasją tworzymy dla Ciebie najbardziej wydajne i wygodne środowisko developerskie do pracy lokalnej.