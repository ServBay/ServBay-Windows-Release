# Versioni di ServBay per Windows

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Ultima versione](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](https://github.com/ServBay/ServBay-Windows-Release/releases/latest)
[![Download Totali](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](https://github.com/ServBay/ServBay-Windows-Release/releases)

Benvenuto nel repository ufficiale delle versioni di ServBay per Windows. Questo repository ospita i pacchetti ufficiali di rilascio e i changelog per ServBay su Windows.

## 🚀 ServBay: La Soluzione Definitiva per lo Sviluppo Locale dei Developer

ServBay è una soluzione **tutto-in-uno, ad alte prestazioni e facile da usare** per ambienti di sviluppo web locale, pensata appositamente per gli sviluppatori. Il nostro obiettivo è eliminare i noiosi passaggi di configurazione dell’ambiente, permettendoti di impostare in pochi minuti un ambiente di sviluppo potente e altamente personalizzabile, così che tu possa concentrarti sul codice e sull’innovazione.

ServBay non è solo un insieme di strumenti, ma un **ecosistema completo** studiato per offrirti **un’esperienza di sviluppo senza paragoni e funzionalità potenziate**. Che tu sia uno sviluppatore web, un ingegnere backend, un data scientist o un esploratore di applicazioni AI, ServBay soddisferà ogni tua esigenza.

Questo repository è dedicato esclusivamente alla distribuzione della versione **Windows** di ServBay.

![Screenshot della versione Windows di ServBay: Software](screenshots/softwares.png)

## ✨ Funzionalità Principali e Capacità Potenziate di ServBay

ServBay offre una suite completa di strumenti e funzionalità avanzate per aumentare la produttività degli sviluppatori:

*   **Ampio supporto ai linguaggi con cambio versione senza interruzioni**:
    *   **PHP**: Supporto per versioni multiple da PHP 5.6 fino all’ultima PHP 8.x, con cambio versione istantaneo per adattarsi alle esigenze di ogni progetto.
    *   **Node.js**: Supporto integrato per più versioni da Node.js 12 a Node.js 24, gestione facilitata delle dipendenze del progetto.
    *   **Python**: Compatibilità completa con Python 2.7 e da Python 3.5 fino a 3.14+, ideale per sviluppo web, data science e machine learning.
    *   **Java**: Integrazione di diverse versioni di OpenJDK dalla 7 alla 24 e supporto Apache Maven incorporato per semplificare la compilazione e gestione di progetti Java.
    *   **Go (Golang)**: Supporto da Go 1.11 a 1.24+, offrendo toolchain completi per lo sviluppo di applicazioni ad alte prestazioni.
    *   **Ruby**: Supporto da Ruby 2.4 a 3.4, specialmente indicato per lo sviluppo di applicazioni con framework come Ruby on Rails.
    *   **.NET**: Ampio supporto per .NET SDK dalla 2.0 alla 10.0 (versione Windows), soddisfa i requisiti di compilazione ed esecuzione per vari progetti .NET (Core/5+).
    *   **Rust**: Linguaggio Rust integrato, ad alte prestazioni e sicuro, per sviluppo e test locali pratici.
*   **Supporto robusto ai database con capacità multi-istanza**:
    *   **Database relazionali**: MySQL, MariaDB e PostgreSQL integrati, con possibilità di eseguire più versioni simultaneamente.
    *   **Database NoSQL**: Redis, Memcached, MongoDB integrati e pronti all’uso.
    *   **Strumenti di gestione database**: phpMyAdmin e Adminer integrati per un’amministrazione semplice dei database.
*   **Web server ad alte prestazioni con configurazione flessibile**:
    *   Supporto per i principali web server come Caddy, Nginx e Apache, con interfaccia di configurazione visuale.
*   **CA integrata per funzioni PKI locali avanzate**:
    *   ServBay include una intera Autorità di Certificazione, la **ServBay CA**, composta da **ServBay User CA** (per certificati root definiti dall’utente) e **ServBay Public CA** (pre-CA per l’emissione di certificati pubblicamente fidati).
    *   L’utente può facilmente creare e gestire root CA e CA intermedie proprie per rilasciare certificati SSL personalizzati utilizzabili in tutti i siti e servizi dell’ambiente di sviluppo locale, abilitando uno sviluppo HTTPS reale e senza avvisi di sicurezza nei browser.
    *   Offre funzionalità complete di gestione dei certificati: generazione, revoca, importazione ed esportazione.
*   **Supporto a AI e Large Language Model (LLM)**:
    *   **Integrazione con Ollama**: Installazione e gestione di Ollama con un click, esegui e testa facilmente localmente numerosi modelli LLM open source (ad es. DeepSeek, Llama 3, Qwen).
    *   Favorisce lo sviluppo e l’integrazione di applicazioni AI locali.
*   **Funzionalità progettate per gli sviluppatori**:
    *   **Interfaccia di gestione grafica**: UI pulita e intuitiva per la gestione semplice di tutti i servizi e configurazioni.
    *   **Avvio/arresto dei servizi con un click**: Controllo rapido dello stato dell’ambiente di sviluppo.
    *   **Acquisizione certificati SSL pubblici**: Richiedi certificati SSL pubblici gratuiti da Let's Encrypt, ZeroSSL e Google Trust Services tramite **protocollo ACME** per demo pubbliche o test.
    *   **Domini personalizzati**: Gestione facilitata dei domini locali di sviluppo.
    *   **Supporto alla linea di comando**: Set completo di strumenti CLI con comandi diretti come `php`, `node`, `python`, `go`, `java`, `mysql` nel terminale.
    *   **Gestione multi-sito**: Configura ed esegui più progetti web contemporaneamente, includendo configurazioni runtime a livello di progetto.
    *   **Supporto proxy inverso**: Accesso pratico ad applicazioni locali (come Docker e servizi Node.js) tramite domini.
    *   **Gestione dei log**: Visualizzazione e amministrazione dei log dei diversi servizi.
    *   **Sistema pulito & backup**: Installazione “verde” che non altera l’ambiente di sistema, facile da eseguire backup, migrare o rimuovere.
    *   **Avvio automatico all’accensione**: Può essere configurato per avviarsi insieme al sistema, mantenendo sempre disponibili i servizi.

*Le funzionalità disponibili possono variare in base alla versione. Consulta la documentazione ufficiale per conoscere le novità dell’ultima release.*

![Screenshot della versione Windows di ServBay: Sito Web](screenshots/website.png)

## 📥 Come scaricare

Puoi trovare tutte le versioni disponibili di ServBay per Windows nella **[Pagina dei Rilasci](https://github.com/ServBay/ServBay-Windows-Release/releases)** di questo repository.

1.  Vai alla [Pagina dei Rilasci](https://github.com/ServBay/ServBay-Windows-Release/releases).
2.  Scegli la versione di cui hai bisogno (in genere si consiglia l’ultima versione stabile).
3.  Nella sezione "Assets" del rilascio selezionato, scarica il pacchetto d’installazione corrispondente (ad es. file `.exe` o `.zip`).
4.  Una volta scaricato, segui la guida all’installazione appropriata.

## 💬 Segnalazione Problemi & Supporto Community

Il tuo feedback è estremamente prezioso! Se incontri problemi nell’utilizzo di ServBay per Windows, hai suggerimenti o trovi un bug, ti invitiamo a contattarci attraverso questi canali:

*   **Segnala un problema nel repository**: Descrivi il problema in dettaglio nella [pagina Issue di ServBay-Windows-Release](https://github.com/ServBay/ServBay-Windows-Release/issues).
*   **Feedback via email**: Scrivi a [support@servbay.com](mailto:support@servbay.com).
*   **Supporto Community**: Entra nelle nostre community ufficiali per entrare in contatto con altri sviluppatori, condividere esperienze e ottenere aiuto:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   Gruppo WeChat: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Quando segnali un problema, descrivi il problema, i passaggi per riprodurlo, il sistema operativo in uso e la versione di ServBay nel modo più dettagliato possibile. Questo aiuterà a identificare e risolvere l’errore più velocemente.

## 🔗 Link utili

*   **Sito ufficiale ServBay**: [https://www.servbay.com](https://www.servbay.com)
*   **Download/Repository principale ServBay per macOS**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **Documentazione/Supporto ufficiale ServBay**: [https://support.servbay.com/](https://support.servbay.com/)

Grazie per aver scelto ServBay! Siamo impegnati a offrirti la migliore esperienza di sviluppo locale: potente, semplice e sempre a portata di mano.