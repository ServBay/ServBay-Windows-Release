# Versions ServBay pour Windows

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Dernière version](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](../../releases/latest)
[![Téléchargements GitHub](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](../../releases)

Bienvenue dans le dépôt officiel des versions de ServBay pour Windows. Ce dépôt héberge les paquets d'installation officiels et les notes de version de ServBay sous Windows.

## 🚀 ServBay : La solution de développement local ultime pour les développeurs

ServBay est un environnement de développement web local **tout-en-un, performant et convivial** spécialement conçu pour les développeurs. Notre objectif : éliminer les fastidieuses étapes de configuration de l’environnement, afin que vous puissiez mettre en place un cadre de développement puissant et hautement personnalisable en quelques minutes… et vous concentrer sur l’essentiel : coder et innover.

ServBay n’est pas qu’une simple boîte à outils : c’est un **écosystème complet** pensé pour offrir une **expérience de développement inégalée et des performances exceptionnelles**. Que vous soyez développeur web, ingénieur back-end, data scientist ou explorateur d’applications IA, ServBay répond à tous vos besoins.

Ce dépôt est exclusivement destiné à la distribution de la **version Windows** de ServBay.

![Capture d'écran de ServBay version Windows : Logiciels](screenshots/softwares.png)

## ✨ Fonctionnalités clés & puissantes capacités de ServBay

ServBay propose une boîte à outils complète et des fonctionnalités puissantes pour maximiser votre productivité :

*   **Large prise en charge des langages avec changements de version faciles** :
    *   **PHP** : Prise en charge de plusieurs versions de PHP, de la 5.6 à la dernière 8.x ; changez de version en un clic pour répondre aux besoins de chaque projet.
    *   **Node.js** : Prise en charge intégrée de Node.js 12 à Node.js 24 ; gérez facilement les dépendances de vos projets.
    *   **Python** : Prise en charge complète des versions Python 2.7 et 3.5 à 3.14+ ; idéal pour le développement web, la data science et le machine learning.
    *   **Java** : Intègre plusieurs versions d’OpenJDK, de la 7 à la 24, avec Maven inclus pour simplifier la compilation et la gestion des projets Java.
    *   **Go (Golang)** : Prise en charge de Go 1.11 à 1.24+, offrant une chaîne d’outils complète pour concevoir des applications performantes.
    *   **Ruby** : Prise en charge de Ruby 2.4 à 3.4, particulièrement adaptée au développement avec Ruby on Rails.
    *   **.NET** : Large compatibilité avec .NET SDK de 2.0 à 10.0 (version Windows), pour compiler et exécuter tout projet .NET (Core/5+).
    *   **Rust** : Intégration du langage Rust, hautes performances et sécurité, pour un développement local efficace.
*   **Prise en charge avancée des bases de données avec gestion multi-instances** :
    *   **Bases de données relationnelles** : MySQL, MariaDB, PostgreSQL intégrés avec possibilité d’exécuter plusieurs versions simultanément.
    *   **Bases de données NoSQL** : Redis, Memcached, MongoDB intégrés et prêts à l’emploi.
    *   **Outils d’administration** : phpMyAdmin et Adminer intégrés pour une gestion simple des bases de données.
*   **Serveurs web performants à la configuration flexible** :
    *   Prise en charge des serveurs web majeurs comme Caddy, Nginx et Apache avec interface de configuration graphique.
*   **Autorité de Certification ServBay intégrée pour une gestion PKI locale avancée** :
    *   ServBay intègre une Autorité de Certification (CA) complète, **ServBay CA**, composée de la **ServBay User CA** (pour les certificats racines utilisateur) et de la **ServBay Public CA** (pré-CA pour la délivrance de certificats publics).
    *   Créez et gérez facilement vos propres autorités racines et intermédiaires pour délivrer des certificats SSL personnalisés à tous vos sites et services locaux : profitez ainsi du vrai HTTPS local et dites adieu aux avertissements de sécurité navigateur.
    *   Profitez d’une gestion complète des certificats : génération, révocation, importation et exportation.
*   **Support IA & grands modèles de langage (LLM)** :
    *   **Intégration d’Ollama** : Installation et gestion en un clic du service Ollama, pour exécuter et déboguer facilement divers LLM open source (DeepSeek, Llama 3, Qwen…) en local.
    *   Plateforme idéale pour le développement et l’intégration d’applications IA locales.
*   **Fonctionnalités pensées pour les développeurs** :
    *   **Interface graphique intuitive** : Gérez tous vos services et configurations en toute simplicité via une interface claire.
    *   **Démarrage/Arrêt en un clic** : Contrôlez rapidement l’état de l’environnement de développement.
    *   **Obtention de certificats SSL publics** : Demandez gratuitement des certificats SSL publics (Let's Encrypt, ZeroSSL, Google Trust Services) via le protocole **ACME** pour vos démonstrations ou vos tests publics.
    *   **Domaines personnalisés** : Gérez simplement vos domaines de développement locaux.
    *   **Support ligne de commande** : Utilisez directement `php`, `node`, `python`, `go`, `java`, `mysql` et d’autres outils en terminal.
    *   **Gestion multi-sites** : Configurez et exécutez facilement plusieurs projets web, avec gestion dédiée de l’environnement par projet.
    *   **Support du reverse proxy** : Accédez aisément à vos applications locales (Docker, services Node.js, etc.) via des noms de domaine.
    *   **Gestion centralisée des logs** : Consultez et gérez facilement les journaux de vos services.
    *   **Installation propre et sauvegarde** : Installation dite « verte » qui ne pollue pas votre système et facilite la sauvegarde, migration et suppression.
    *   **Lancement au démarrage** : Peut être configuré pour démarrer automatiquement avec Windows, assurant ainsi la disponibilité des services.

*Certaines fonctionnalités peuvent évoluer selon les versions. Veuillez consulter la documentation officielle pour les dernières nouveautés.*

![Capture d'écran de ServBay version Windows : Site web](screenshots/website.png)

## 📥 Comment télécharger

Vous trouverez toutes les versions disponibles de ServBay pour Windows sur la **[page des versions](../../releases)** de ce dépôt.

1.  Rendez-vous sur la [page des versions](../../releases).
2.  Sélectionnez la version désirée (nous recommandons généralement la dernière version stable).
3.  Dans la section "Assets" de la version choisie, téléchargez le fichier d’installation correspondant (`.exe` ou `.zip` par exemple).
4.  Une fois le téléchargement terminé, suivez le guide d’installation associé.

## 💬 Signaler un problème & obtenir du soutien

Nous accordons une grande importance à vos retours ! Si vous rencontrez un problème lors de l’utilisation de ServBay pour Windows, avez une suggestion ou repérez un bug, contactez-nous via les canaux suivants :

*   **Ouvrir un ticket sur ce dépôt** : Décrivez en détail votre problème sur la [page Issues ServBay-Windows-Release](../../issues).
*   **Envoyer un email** : Faites-nous part de vos retours à [support@servbay.com](mailto:support@servbay.com).
*   **Communauté** : Rejoignez nos communautés officielles pour échanger avec d'autres développeurs, partager vos expériences et obtenir de l'aide :
    *   Discord : [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram : [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   Groupe WeChat : [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Lors de la soumission d'un ticket, merci de décrire aussi précisément que possible le problème rencontré, les étapes pour le reproduire, votre système d’exploitation et la version de ServBay. Cela nous permettra de diagnostiquer et résoudre plus rapidement.

## 🔗 Liens utiles

*   **Site officiel ServBay** : [https://www.servbay.com](https://www.servbay.com)
*   **Téléchargement/version macOS de ServBay** : [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **Documentation & support ServBay** : [https://support.servbay.com/](https://support.servbay.com/)

Merci d’avoir choisi ServBay ! Nous nous engageons à vous offrir la meilleure expérience de développement local possible.