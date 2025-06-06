# Rilis Versi Windows ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Rilis Terbaru](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](https://github.com/ServBay/ServBay-Windows-Release/releases/latest)
[![GitHub Releases](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](https://github.com/ServBay/ServBay-Windows-Release/releases)

Selamat datang di repository rilis resmi untuk ServBay versi Windows. Repository ini menyediakan paket rilis resmi dan catatan perubahan untuk ServBay di Windows.

## 🚀 ServBay: Solusi Pengembangan Lokal Terbaik untuk Developer

ServBay adalah solusi **terpadu, berkinerja tinggi, dan ramah pengguna** untuk lingkungan pengembangan web lokal yang dirancang khusus bagi para developer. Kami berkomitmen untuk menghilangkan langkah-langkah konfigurasi lingkungan yang merepotkan, sehingga Anda dapat membangun lingkungan pengembangan yang kuat dan sangat fleksibel hanya dalam hitungan menit, agar Anda dapat fokus pada pengkodean dan inovasi.

ServBay bukan sekadar kumpulan alat; ini adalah **ekosistem lengkap** yang dirancang untuk memberikan **pengalaman pengembangan tak tertandingi dan kemampuan supercharged**. Apakah Anda seorang pengembang web, engineer backend, ilmuwan data, atau penjelajah aplikasi AI, ServBay dapat memenuhi kebutuhan Anda yang beragam.

Repository ini khusus digunakan untuk distribusi **ServBay versi Windows**.

![Screenshot ServBay versi Windows: Perangkat Lunak](screenshots/softwares.png)

## ✨ Fitur Inti & Kemampuan Unggulan ServBay

ServBay menawarkan rangkaian lengkap alat dan fitur canggih untuk meningkatkan produktivitas developer:

*   **Dukungan Bahasa Pemrograman Lengkap dengan Pergantian Versi Mudah**:
    *   **PHP**: Mendukung banyak versi dari PHP 5.6 hingga PHP 8.x terbaru, ganti versi dengan satu klik untuk memenuhi persyaratan proyek yang berbeda.
    *   **Node.js**: Dukungan bawaan untuk berbagai versi dari Node.js 12 hingga Node.js 24, kelola dependensi proyek dengan mudah.
    *   **Python**: Dukungan penuh untuk Python 2.7 dan Python 3.5 hingga 3.14+, memudahkan proyek pengembangan web, data science, dan machine learning.
    *   **Java**: Integrasi berbagai versi OpenJDK dari 7 hingga 24, dengan dukungan Apache Maven, memudahkan pembangunan dan manajemen proyek Java.
    *   **Go (Golang)**: Dukungan untuk Go 1.11 hingga 1.24+, menyediakan toolchain Go lengkap untuk pengembangan aplikasi berkinerja tinggi.
    *   **Ruby**: Dukungan untuk Ruby 2.4 hingga 3.4, sangat cocok untuk pengembangan dengan framework seperti Ruby on Rails.
    *   **.NET**: Dukungan menyeluruh untuk .NET SDK 2.0 hingga 10.0 (versi Windows), memenuhi kebutuhan build dan eksekusi berbagai proyek .NET (Core/5+).
    *   **Rust**: Bahasa Rust terintegrasi dengan performa dan keamanan tinggi, memudahkan pengembangan dan pengujian secara lokal.
*   **Dukungan Basis Data Kuat dengan Kemampuan Multi-Instansi**:
    *   **Basis Data Relasional**: MySQL, MariaDB, dan PostgreSQL bawaan, mendukung operasi beberapa versi secara bersamaan.
    *   **Basis Data NoSQL**: Terintegrasi dengan database NoSQL populer seperti Redis, Memcached, MongoDB, siap digunakan langsung.
    *   **Alat Manajemen Database**: phpMyAdmin dan Adminer terintegrasi untuk mengelola database dengan mudah.
*   **Web Server Berkinerja Tinggi dengan Konfigurasi Fleksibel**:
    *   Mendukung web server utama seperti Caddy, Nginx, Apache, dilengkapi antarmuka konfigurasi visual.
*   **ServBay CA Bawaan untuk Kemampuan PKI Lokal Kuat**:
    *   ServBay menyertakan Certificate Authority lengkap, **ServBay CA**, terdiri dari **ServBay User CA** (untuk root certificate buatan pengguna) dan **ServBay Public CA** (pre-CA untuk penerbitan sertifikat tepercaya publik).
    *   Pengguna dapat dengan mudah membuat serta mengelola root CA dan intermediate CA mereka sendiri untuk menerbitkan sertifikat SSL khusus ke semua situs dan layanan di lingkungan pengembangan lokal mereka, memungkinkan pengembangan HTTPS lokal yang sesungguhnya dan sepenuhnya menghilangkan peringatan keamanan browser.
    *   Menyediakan fungsi manajemen sertifikat lengkap, mulai dari pembuatan, pencabutan, impor, hingga ekspor.
*   **Dukungan AI & Large Language Model (LLM)**:
    *   **Integrasi Ollama**: Instalasi dan manajemen layanan Ollama sekali klik, jalankan dan debug berbagai model bahasa terbuka (seperti DeepSeek, Llama 3, Qwen) secara lokal dengan mudah.
    *   Mendukung pengembangan dan integrasi aplikasi AI lokal Anda.
*   **Fitur Ramah Pengembang**:
    *   **Antarmuka Manajemen Grafis**: UI bersih dan intuitif untuk mengelola seluruh layanan dan konfigurasi dengan mudah.
    *   **Mulai/Hentikan Layanan Sekali Klik**: Atur status berjalan seluruh lingkungan pengembangan dengan cepat.
    *   **Perolehan Sertifikat SSL Publik**: Dapat mengajukan sertifikat SSL publik gratis dari Let's Encrypt, ZeroSSL, dan Google Trust Services lewat **protokol ACME**, memudahkan demo publik atau pengujian Anda.
    *   **Domain Kustom**: Mudah mengelola domain pengembangan lokal.
    *   **Dukungan Command-Line**: Rangkaian alat CLI lengkap, memungkinkan penggunaan perintah seperti `php`, `node`, `python`, `go`, `java`, `mysql` langsung di terminal.
    *   **Manajemen Multi-Situs**: Konfigurasi dan jalankan beberapa proyek website dengan mudah, dukungan konfigurasi lingkungan runtime pada tingkat proyek.
    *   **Dukungan Reverse Proxy**: Akses aplikasi lokal (seperti Docker, layanan Node.js lain) menggunakan nama domain dengan mudah.
    *   **Manajemen Log**: Melihat dan mengelola log beragam layanan secara nyaman.
    *   **Sistem Bersih & Backup Mudah**: ServBay menggunakan metode instalasi hijau, tidak mencemari lingkungan sistem dan mudah untuk backup, migrasi, maupun penghapusan.
    *   **Auto Start Saat Booting**: Dapat dikonfigurasi untuk berjalan otomatis saat sistem dinyalakan, memastikan layanan selalu aktif.

*Fitur tertentu dapat berbeda sesuai pembaruan versi. Silakan lihat dokumentasi resmi untuk informasi terbaru.*

![Screenshot ServBay versi Windows: Website](screenshots/website.png)

## 📥 Cara Mengunduh

Anda dapat menemukan semua versi ServBay Windows yang tersedia di **[Halaman Rilis](https://github.com/ServBay/ServBay-Windows-Release/releases)** repository ini.

1.  Kunjungi [Halaman Rilis](https://github.com/ServBay/ServBay-Windows-Release/releases).
2.  Pilih versi yang Anda butuhkan (umumnya direkomendasikan memilih rilis stabil terbaru).
3.  Pada bagian "Assets" dari rilis yang dipilih, unduh paket installer yang sesuai (misalnya file `.exe` atau `.zip`).
4.  Setelah terunduh, ikuti panduan instalasi untuk menginstal.

## 💬 Pelaporan Masalah & Dukungan Komunitas

Kami sangat menghargai masukan Anda! Jika Anda mengalami masalah saat menggunakan ServBay untuk Windows, memiliki saran, atau menemukan bug, silakan hubungi kami melalui saluran berikut:

*   **Laporkan Issue di Repository Ini**: Jelaskan masalah Anda secara detail di [Halaman Issues ServBay-Windows-Release](https://github.com/ServBay/ServBay-Windows-Release/issues).
*   **Kirim Email**: Kirimkan email ke [support@servbay.com](mailto:support@servbay.com).
*   **Dukungan Komunitas**: Bergabunglah dengan komunitas resmi kami untuk terhubung dengan developer lain, berbagi pengalaman, dan mendapatkan bantuan:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   WeChat Group: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Saat melaporkan masalah, mohon jelaskan masalahnya, langkah reproduksi, lingkungan sistem operasi yang digunakan, dan nomor versi ServBay secara detail. Ini akan membantu kami menemukan dan mengatasi masalah lebih cepat.

## 🔗 Tautan Terkait

*   **Situs Resmi ServBay**: [https://www.servbay.com](https://www.servbay.com)
*   **Unduh Versi macOS / Repository Utama ServBay**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **Dokumentasi Resmi / Pusat Dukungan ServBay**: [https://support.servbay.com/](https://support.servbay.com/)

Terima kasih telah memilih ServBay! Kami berkomitmen menghadirkan pengalaman pengembangan lokal yang paling kuat dan nyaman untuk Anda.