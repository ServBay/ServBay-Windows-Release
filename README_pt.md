# Lançamentos da Versão Windows do ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Último Lançamento](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](../../releases/latest)
[![Downloads do GitHub](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](../../releases)

Bem-vindo ao repositório oficial de lançamentos da versão Windows do ServBay. Aqui você encontra os pacotes oficiais e os registros de mudanças do ServBay para Windows.

## 🚀 ServBay: A Plataforma Definitiva de Desenvolvimento Local para Devs

O ServBay é uma solução **tudo-em-um, de alto desempenho e fácil de usar** para integração de ambientes de desenvolvimento web local, feita especialmente para desenvolvedores. Nosso objetivo é eliminar as etapas cansativas de configuração, permitindo que você configure um ambiente poderoso e altamente personalizável em minutos, focando apenas em programar e inovar.

O ServBay vai além de um simples conjunto de ferramentas; é um **ecossistema completo** projetado para oferecer **uma experiência de desenvolvimento sem igual e recursos avançados**. Seja você desenvolvedor web, engenheiro backend, cientista de dados ou explorador de aplicações de IA, o ServBay atende a todas as suas necessidades.

Este repositório é focado exclusivamente na **distribuição da versão Windows** do ServBay.

![Captura de tela da versão Windows do ServBay: Softwares](screenshots/softwares.png)

## ✨ Principais Recursos e Capacidades Avançadas do ServBay

O ServBay oferece um conjunto abrangente de ferramentas poderosas para turbinar a produtividade do desenvolvedor:

*   **Suporte Amplo a Linguagens com Troca Rápida de Versões**:
    *   **PHP**: Suporte a diversas versões do PHP, da 5.6 à mais recente 8.x; alterne com um clique para se adequar a diferentes projetos.
    *   **Node.js**: Suporte embutido a múltiplas versões, do Node.js 12 ao 24; gerencie facilmente as dependências do projeto.
    *   **Python**: Suporte completo ao Python 2.7 e do 3.5 até o 3.14+, facilitando projetos de web, ciência de dados e machine learning.
    *   **Java**: Integração de diversas versões do OpenJDK, do 7 ao 24, com Maven pré-instalado, simplificando o build e gerenciamento de projetos Java.
    *   **Go (Golang)**: Suporte do Go 1.11 ao 1.24+, fornecendo um toolchain completo para desenvolvimento de aplicativos de alta performance.
    *   **Ruby**: Suporte ao Ruby de 2.4 a 3.4, ideal para projetos com frameworks como Ruby on Rails.
    *   **.NET**: Suporte abrangente do .NET SDK de 2.0 a 10.0 (versão Windows), cobrindo build e execução de diversos projetos .NET (Core/5+).
    *   **Rust**: Linguagem Rust integrada, de alta performance e segurança, para desenvolvimento e testes locais.
*   **Suporte Robusto a Bancos de Dados com Multi-instâncias**:
    *   **Bancos de Dados Relacionais**: MySQL, MariaDB, PostgreSQL integrados, com possibilidade de rodar múltiplas versões simultaneamente.
    *   **Bancos NoSQL**: Redis, Memcached, MongoDB integrados e prontos para uso imediato.
    *   **Ferramentas de Administração**: phpMyAdmin e Adminer embutidos para facilitar a administração do banco de dados.
*   **Servidores Web de Alta Performance com Configuração Flexível**:
    *   Suporte aos principais servidores web como Caddy, Nginx, Apache, com interface visual amigável.
*   **CA Integrada do ServBay para Recursos Locais de PKI Avançados**:
    *   O ServBay possui uma Autoridade Certificadora própria, a **ServBay CA**, composta pela **ServBay User CA** (para certificados raiz definidos pelo usuário) e a **ServBay Public CA** (pre-CA para emissões amplamente confiáveis).
    *   Permite criar e gerenciar facilmente suas próprias CAs raiz e intermediárias para emitir certificados SSL personalizados para todos os seus sites e serviços locais — habilitando HTTPS local real e eliminando alertas de segurança do navegador.
    *   Oferece recursos completos de gerenciamento de certificados: geração, revogação, importação e exportação.
*   **Suporte a IA & LLM (Modelos de Linguagem de Grande Escala)**:
    *   **Integração com Ollama**: Instale e gerencie o serviço Ollama em um clique, execute e debuge diversos modelos de IA open-source localmente (ex: DeepSeek, Llama 3, Qwen).
    *   Estímulo ao desenvolvimento e integração de aplicações de IA em ambiente local.
*   **Funcionalidades Favoráveis ao Desenvolvedor**:
    *   **Interface de Gerenciamento Gráfica**: Interface limpa e intuitiva para gerenciar todos os serviços e configurações com facilidade.
    *   **Início/Parada de Serviços com Um Clique**: Controle rápido do status do ambiente de desenvolvimento por completo.
    *   **Emissão de Certificados SSL Públicos**: Solicite certificados públicos gratuitos da Let's Encrypt, ZeroSSL e Google Trust Services usando o **protocolo ACME**, facilitando demonstrações públicas e testes.
    *   **Domínios Personalizados**: Gerencie facilmente domínios de desenvolvimento locais.
    *   **Acesso via Linha de Comando**: Ferramentas CLI completas, permitindo uso direto de comandos como `php`, `node`, `python`, `go`, `java`, `mysql` no terminal.
    *   **Gerenciamento Multi-site**: Configure e rode diversos projetos de sites facilmente, com configuração de ambiente por projeto.
    *   **Suporte a Proxy Reverso**: Acesse aplicações locais (Docker, outros serviços Node.js, etc.) facilmente via nomes de domínio.
    *   **Gerenciamento de Logs**: Visualize e gerencie logs de todos os serviços de forma prática.
    *   **Sistema Limpo & Backup**: Instalação "verde", sem poluir o ambiente do sistema — facilitando backup, migração e exclusão.
    *   **Inicialização Automática**: O ServBay pode ser configurado para iniciar junto com o sistema, garantindo alta disponibilidade dos serviços.

*Alguns recursos podem variar conforme a versão. Consulte a documentação oficial para informações atualizadas.*

![Captura de tela da versão Windows do ServBay: Website](screenshots/website.png)

## 📥 Como Baixar

Todas as versões do ServBay para Windows estão disponíveis na **[Página de Lançamentos](../../releases)** deste repositório.

1.  Visite a [Página de Lançamentos](../../releases).
2.  Escolha a versão desejada (geralmente, é recomendado usar a versão estável mais recente).
3.  Na seção "Assets" do lançamento escolhido, faça o download do instalador correspondente (ex.: arquivo `.exe` ou `.zip`).
4.  Após o download, siga o respectivo guia de instalação.

## 💬 Relatar Problemas & Suporte da Comunidade

Sua opinião é muito importante para nós! Caso encontre algum problema usando o ServBay para Windows, tenha sugestões ou descubra um erro, entre em contato pelos canais abaixo:

*   **Informe um Problema Neste Repositório**: Descreva sua questão detalhadamente na [página de Issues do ServBay-Windows-Release](../../issues).
*   **Feedback por Email**: Envie um e-mail para [support@servbay.com](mailto:support@servbay.com).
*   **Suporte da Comunidade**: Participe de nossas comunidades oficiais para interagir com outros devs, compartilhar experiências e obter suporte:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   Grupo WeChat: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Ao relatar um problema, descreva o máximo possível: o erro, como reproduzir, o sistema operacional utilizado e a versão do ServBay. Assim você nos ajuda a localizar e resolver o problema mais rapidamente.

## 🔗 Links Relacionados

*   **Site Oficial do ServBay**: [https://www.servbay.com](https://www.servbay.com)
*   **Repositório Principal/Versão para macOS**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **Central de Ajuda & Documentação Oficial**: [https://support.servbay.com/](https://support.servbay.com/)

Obrigado por escolher o ServBay! Estamos comprometidos em proporcionar a você a experiência de desenvolvimento local mais poderosa e conveniente.