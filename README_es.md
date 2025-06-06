# Versiones de ServBay para Windows

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Última Versión](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](../../releases/latest)
[![Descargas de GitHub](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](../../releases)

Bienvenido al repositorio oficial de lanzamientos de ServBay para Windows. Este repositorio alberga los paquetes oficiales de lanzamiento y los registros de cambios de ServBay en Windows.

## 🚀 ServBay: El Entorno Definitivo de Desarrollo Local para Desarrolladores

ServBay es una solución integral, de alto rendimiento y fácil de usar, diseñada específicamente para proporcionar un entorno de desarrollo web local a desarrolladores. Nuestro compromiso es eliminar pasos tediosos de configuración, permitiéndote establecer un entorno potente y altamente personalizable en minutos, para que puedas enfocarte en programar e innovar.

ServBay es mucho más que un simple conjunto de herramientas; es un **ecosistema completo** creado para brindarte una **experiencia de desarrollo inigualable y capacidades avanzadas**. Ya seas desarrollador web, ingeniero backend, científico de datos o explorador de aplicaciones de IA, ServBay satisface todas tus necesidades.

Este repositorio está dedicado a la distribución de la **versión para Windows** de ServBay.

![Captura de pantalla de ServBay para Windows: Programas](screenshots/softwares.png)

## ✨ Funcionalidades Principales y Capacidades Avanzadas de ServBay

ServBay ofrece una completa gama de herramientas y potentes características para potenciar la productividad de los desarrolladores:

*   **Amplio soporte de lenguajes con cambio de versión sin interrupciones**:
    *   **PHP**: Compatibilidad con múltiples versiones desde PHP 5.6 hasta la última PHP 8.x. Cambia de versión con un solo clic para adaptarte a los distintos requisitos de tus proyectos.
    *   **Node.js**: Soporte integrado para varias versiones de Node.js, desde la 12 hasta la 24. Administrar dependencias será más fácil que nunca.
    *   **Python**: Soporte completo para Python 2.7 y desde la versión 3.5 a la 3.14+, ideal para desarrollo web, ciencia de datos y proyectos de aprendizaje automático.
    *   **Java**: Integración de varias versiones de OpenJDK, desde la 7 hasta la 24, con Apache Maven incorporado para simplificar la construcción y gestión de proyectos Java.
    *   **Go (Golang)**: Soporte de Go de la versión 1.11 hasta la 1.24+, proporcionando una herramienta robusta para el desarrollo de aplicaciones de alto rendimiento.
    *   **Ruby**: Compatibilidad con Ruby desde la 2.4 hasta la 3.4, ideal para frameworks como Ruby on Rails.
    *   **.NET**: Soporte amplio para el SDK de .NET desde la versión 2.0 hasta la 10.0 (para Windows), cubriendo los requisitos de ejecución y compilación de diversos proyectos .NET (Core/5+).
    *   **Rust**: Inclusión nativa del lenguaje Rust de alto rendimiento y seguridad para desarrollo y pruebas locales.
*   **Gestión robusta de bases de datos, con soporte multi-instancia**:
    *   **Bases de datos relacionales**: MySQL, MariaDB y PostgreSQL integrados, con la posibilidad de ejecutar varias versiones al mismo tiempo.
    *   **Bases de datos NoSQL**: Integración de bases de datos NoSQL populares como Redis, Memcached y MongoDB, listos para usar.
    *   **Herramientas de administración de bases de datos**: phpMyAdmin y Adminer incluidos para facilitar la administración.
*   **Servidores web de alto rendimiento con configuración flexible**:
    *   Soporte para los principales servidores web: Caddy, Nginx, Apache, con interfaz de configuración visual.
*   **Autoridad de Certificación integrada para capacidades avanzadas de PKI local**:
    *   ServBay incluye una Autoridad de Certificación completa, **ServBay CA**, compuesta por **ServBay User CA** (para certificados raíz definidos por el usuario) y **ServBay Public CA** (una pre-CA para emitir certificados confiables públicamente).
    *   Los usuarios pueden crear y gestionar fácilmente sus propias CAs raíz e intermedias para emitir certificados SSL personalizados para todos los sitios y servicios del entorno local, habilitando desarrollo HTTPS real y eliminando por completo las advertencias de seguridad del navegador.
    *   Proporciona funciones completas de gestión de certificados, incluyendo generación, revocación, importación y exportación.
*   **Soporte para IA y Modelos de Lenguaje de Gran Tamaño (LLM)**:
    *   **Integración con Ollama**: Instalación y gestión con un solo clic del servicio Ollama, permitiendo ejecutar y depurar fácilmente distintos modelos de lenguaje de código abierto (por ejemplo, DeepSeek, Llama 3, Qwen) en local.
    *   Potencia el desarrollo e integración de aplicaciones de IA locales.
*   **Funciones pensadas para desarrolladores**:
    *   **Interfaz gráfica de gestión**: Interfaz limpia e intuitiva para administrar servicios y configuraciones fácilmente.
    *   **Iniciar/Detener servicios con un solo clic**: Controla rápidamente el estado de todo tu entorno de desarrollo.
    *   **Obtención de certificados SSL públicos**: Permite solicitar certificados SSL públicos gratuitos de Let's Encrypt, ZeroSSL y Google Trust Services utilizando el **protocolo ACME**, facilitando demostraciones públicas o pruebas.
    *   **Dominios personalizados**: Administración sencilla de dominios de desarrollo locales.
    *   **Soporte para línea de comandos**: Completo conjunto de herramientas CLI para usar comandos como `php`, `node`, `python`, `go`, `java`, `mysql` directamente en la terminal.
    *   **Gestión multisite**: Configuraciones sencillas para administrar y ejecutar múltiples proyectos web, con soporte para configuración de entorno a nivel de proyecto.
    *   **Soporte de proxy inverso**: Acceso cómodo a aplicaciones que se ejecutan en local (por ejemplo, Docker, otros servicios Node.js) mediante nombres de dominio.
    *   **Gestión de logs**: Visualización y administración fácil de los registros de todos los servicios.
    *   **Sistema limpio y respaldo**: ServBay utiliza un método de instalación limpio que no contamina el entorno del sistema, facilitando la copia de seguridad, migración o desinstalación.
    *   **Inicio automático junto con el sistema**: Puede configurarse para arrancar junto al sistema operativo y así asegurar la disponibilidad continua de los servicios.

*Las características concretas pueden variar según las actualizaciones de versión. Consulta la documentación oficial para información actualizada.*

![Captura de pantalla de ServBay para Windows: Sitio Web](screenshots/website.png)

## 📥 Cómo Descargar

Todas las versiones disponibles de ServBay para Windows se encuentran en la **[Página de Lanzamientos](../../releases)** de este repositorio.

1.  Visita la [Página de Lanzamientos](../../releases).
2.  Elige la versión que necesitas (recomendamos seleccionar la versión estable más reciente).
3.  En la sección "Assets" de la versión seleccionada, descarga el paquete de instalación correspondiente (por ejemplo, un archivo `.exe` o `.zip`).
4.  Una vez descargado, sigue la guía de instalación para completar el proceso.

## 💬 Reporte de Problemas y Soporte Comunitario

¡Valoramos mucho tu opinión! Si tienes algún problema usando ServBay para Windows, sugerencias o encuentras algún error, contáctanos por los siguientes canales:

*   **Reporta un problema en este repositorio**: Describe tu problema en detalle en la [página de Incidencias de ServBay-Windows-Release](../../issues).
*   **Envíanos un correo electrónico**: Escribe a [support@servbay.com](mailto:support@servbay.com).
*   **Soporte comunitario**: Únete a nuestras comunidades oficiales para conectar con otros desarrolladores, compartir experiencias y recibir ayuda:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   Grupo de WeChat: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Al reportar un problema, por favor incluye una descripción detallada del inconveniente, los pasos para reproducirlo, tu sistema operativo y la versión de ServBay. Así podremos ayudarte de forma más rápida y eficiente.

## 🔗 Enlaces Relacionados

*   **Sitio web oficial de ServBay**: [https://www.servbay.com](https://www.servbay.com)
*   **Repositorio principal / Descarga para macOS**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **Documentación oficial y centro de soporte de ServBay**: [https://support.servbay.com/](https://support.servbay.com/)

¡Gracias por elegir ServBay! Nos esforzamos constantemente para ofrecerte la mejor experiencia local de desarrollo, potente y conveniente.