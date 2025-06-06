# ServBay Windows Sürüm Yayınları

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md) | [हिन्दी](/README_hi.md) | [Bahasa Indonesia](/README_id.md) | [Bahasa Melayu](/README_ms.md) | [Polski](/README_pl.md) | [Nederlands](/README_nl.md) | [Українська](/README_uk.md) | [ไทย](/README_th.md) | [한국어](/README_ko.md)

[![Son Sürüm](https://img.shields.io/github/v/release/ServBay/ServBay-Windows-Release?display_name=tag&sort=date&label=Latest%20Release)](https://github.com/ServBay/ServBay-Windows-Release/releases/latest)
[![GitHub Yayınları](https://img.shields.io/github/downloads/ServBay/ServBay-Windows-Release/total?label=Total%20Downloads)](https://github.com/ServBay/ServBay-Windows-Release/releases)

ServBay Windows sürümünün resmi yayın deposuna hoş geldiniz. Bu depo, Windows için ServBay’in resmi yayın paketlerini ve değişiklik kayıtlarını barındırır.

## 🚀 ServBay: Geliştiriciler için En Güçlü Yerel Geliştirme Platformu

ServBay, geliştiricilere özel olarak tasarlanmış, **her şey dahil, yüksek performanslı ve kullanıcı dostu** bir yerel web geliştirme ortamı entegre çözümüdür. Sıkıcı ortam yapılandırma adımlarını ortadan kaldırmaya kararlıyız; böylece dakikalar içinde güçlü ve son derece özelleştirilebilir bir geliştirme ortamını kurabilir, tüm odağınızı kodlamaya ve yeniliğe verebilirsiniz.

ServBay yalnızca bir araçlar topluluğu değildir; **benzersiz bir geliştirme deneyimi ve olağanüstü yetenekler** sunmak için geliştirilen eksiksiz bir **ekosistemdir**. İster web geliştiricisi, ister backend mühendisi, ister veri bilimcisi ya da Yapay Zeka uygulamalarını keşfeden biri olun, ServBay farklı ihtiyaçlarınıza cevap verebilir.

Bu depo, özel olarak **ServBay’in Windows sürümü** dağıtımı içindir.

![ServBay Windows sürüm ekran görüntüsü: Yazılımlar](screenshots/softwares.png)

## ✨ ServBay Temel Özellikleri & Üstün Yetenekleri

ServBay, geliştirici verimliliğini artıracak kapsamlı araçlar ve güçlü özelliklerle birlikte gelir:

*   **Geniş Dilde Destek ve Sorunsuz Sürüm Geçişi**:
    *   **PHP**: PHP 5.6’dan en yeni PHP 8.x’e kadar çoklu sürüm desteği, farklı proje gereksinimleri için tek tıkla geçiş.
    *   **Node.js**: Node.js 12’den 24’e kadar birden fazla sürüm yerleşik desteği ile proje bağımlılıklarını kolayca yönetin.
    *   **Python**: Python 2.7 ile 3.5’ten 3.14+’a kadar tam destek; web geliştirme, veri bilimi ve makine öğrenimi projelerini kolaylaştırır.
    *   **Java**: 7’den 24’e kadar birçok OpenJDK sürümünün entegrasyonu ve yerleşik Apache Maven desteği ile Java projeleri kolayca oluşturulabilir ve yönetilebilir.
    *   **Go (Golang)**: Go 1.11’den 1.24+’a kadar destek; yüksek performanslı uygulama geliştirmek için eksiksiz bir Go araç takımı sağlar.
    *   **Ruby**: Ruby 2.4’ten 3.4’e kadar destek; özellikle Ruby on Rails gibi frameworklerle geliştirme için uygundur.
    *   **.NET**: .NET SDK 2.0’dan 10.0’a (Windows sürümü) kadar geniş destek; çeşitli .NET (Core/5+) projelerinin derleme ve çalıştırma gereksinimlerini karşılar.
    *   **Rust**: Yüksek performanslı, güvenli Rust dili entegre edilmiş; kolay yerel geliştirme ve test imkânı sunar.
*   **Güçlü Veritabanı Desteği & Çoklu Örnek Yeteneği**:
    *   **İlişkisel Veritabanları**: Yerleşik MySQL, MariaDB, PostgreSQL; birden fazla sürümü aynı anda çalıştırabilirsiniz.
    *   **NoSQL Veritabanları**: Redis, Memcached, MongoDB gibi yaygın NoSQL veritabanları yerleşik ve kullanıma hazır.
    *   **Veritabanı Yönetim Araçları**: Kolay veritabanı yönetimi için yerleşik phpMyAdmin ve Adminer.
*   **Yüksek Performanslı Web Sunucuları & Esnek Yapılandırmalar**:
    *   Caddy, Nginx, Apache gibi popüler web sunucuları için destek; görsel yapılandırma arayüzü ile kolay yönetim.
*   **Yerleşik ServBay CA ile Güçlü Yerel PKI Yeteneği**:
    *   ServBay, eksiksiz bir Sertifika Yetkilisi (CA) içerir: **ServBay User CA** (kullanıcı tanımlı kök sertifikalar için) ve **ServBay Public CA** (genel olarak güvenilen sertifikaları vermek için bir ön CA).
    *   Kullanıcılar, yerel geliştirme ortamlarındaki tüm site ve servisler için özel SSL sertifikaları düzenleyecek kök ve ara CA’ları kolayca oluşturup yönetebilir; tam anlamıyla yerel HTTPS geliştirme sağlayarak tarayıcı güvenlik uyarılarını tamamen ortadan kaldırır.
    *   Sertifika oluşturma, iptal etme, içe/dışa aktarma dahil kapsamlı sertifika yönetimi özellikleri sunar.
*   **Yapay Zeka & Büyük Dil Modeli (LLM) Desteği**:
    *   **Ollama Entegrasyonu**: Ollama servisinin tek tıkla kurulumu ve yönetimi, farklı açık kaynak büyük dil modellerini (örn. DeepSeek, Llama 3, Qwen) yerel olarak kolayca çalıştırıp debug etme.
    *   Yerel AI uygulama geliştirme ve entegrasyonunu destekler.
*   **Geliştirici Dostu Özellikler**:
    *   **Grafiksel Yönetim Arayüzü**: Berrak ve sezgisel kullanıcı arayüzüyle tüm servis ve ayarları kolayca yönetme imkânı.
    *   **Tek Tıkla Servis Başlat/Durdur**: Geliştirme ortamınızın çalışma durumunu hızlıca kontrol edin.
    *   **Genel SSL Sertifikası Alma**: **ACME protokolü** ile Let's Encrypt, ZeroSSL ve Google Trust Services’ten ücretsiz genel SSL sertifikaları alın; topluluk demolarınız veya testleriniz için kolaylık sağlar.
    *   **Özel Alan Adları**: Yerel geliştirme alan adlarınızı kolayca yönetin.
    *   **Komut Satırı Desteği**: `php`, `node`, `python`, `go`, `java`, `mysql` gibi komutları terminalden doğrudan kullanabilmek için eksiksiz komut satırı araç seti.
    *   **Çoklu Site Yönetimi**: Birden fazla web sitesi projesini kolayca yapılandırın ve çalıştırın; proje düzeyinde çalışma zamanını özelleştirin.
    *   **Ters Proxy Desteği**: Yerelde çalışan uygulamalara (Docker, başka Node.js servisleri gibi) alan adı üzerinden kolay erişim.
    *   **Log Yönetimi**: Farklı servislerin loglarını kolayca izleyin ve yönetin.
    *   **Temiz Sistem & Yedekleme**: ServBay yeşil kurulum yöntemi ile sistemi kirletmeden kolayca yedeklenebilir, taşınabilir ya da silinebilir.
    *   **Sistemle Beraber Başlatma**: Sistem başlatıldığında otomatik olarak çalıştırılabilme desteği, böylece servisler her zaman erişilebilir olur.

*Belirli özellikler sürüm güncellemeleriyle değişiklik gösterebilir. Son durum için lütfen resmi dokümantasyonu inceleyin.*

![ServBay Windows sürüm ekran görüntüsü: Web Sitesi](screenshots/website.png)

## 📥 Nasıl İndirilir?

Tüm mevcut ServBay Windows sürümlerini bu deponun **[Yayınlar Sayfası](https://github.com/ServBay/ServBay-Windows-Release/releases)** üzerinden bulabilirsiniz.

1.  [Yayınlar Sayfası’na](https://github.com/ServBay/ServBay-Windows-Release/releases) gidin.
2.  Gerekli olan sürümü seçin (genellikle en son kararlı sürüm önerilir).
3.  Seçili sürümün "Assets" bölümünden uygun kurulum paketini (ör. `.exe` ya da `.zip` dosyası) indirin.
4.  İndirdikten sonra, ilgili kurulum kılavuzunu izleyerek yükleyin.

## 💬 Sorun Bildirimi & Topluluk Desteği

Geri bildiriminiz bizim için çok değerli! Windows için ServBay kullanırken bir sorunla karşılaşırsanız, önerileriniz varsa veya bir hata bulursanız, lütfen aşağıdaki kanallardan bize ulaşın:

*   **Bu Depoda Sorun Bildirimi**: [ServBay-Windows-Release Sorunlar Sayfası](https://github.com/ServBay/ServBay-Windows-Release/issues) üzerinden detaylı şekilde sorunuzu anlatın.
*   **E-posta ile Geri Bildirim**: [support@servbay.com](mailto:support@servbay.com) adresine e-posta gönderin.
*   **Topluluk Desteği**: Diğer geliştiricilerle buluşmak, deneyimler paylaşmak ve yardım almak için resmi topluluklarımıza katılın:
    *   Discord: [https://talk.servbay.com/](https://talk.servbay.com/)
    *   Telegram: [https://telegram.servbay.dev/](https://telegram.servbay.dev/)
    *   WeChat Grubu: [https://wechat-group.servbay.dev/](https://wechat-group.servbay.dev/)

Bir sorun bildirirken lütfen sorunu, yeniden üretme adımlarını, işletim sistemi ortamınızı ve kullandığınız ServBay sürümünü olabildiğince ayrıntılı şekilde belirtin. Bu, sorunun tespitini ve çözümünü hızlandıracaktır.

## 🔗 İlgili Bağlantılar

*   **ServBay Resmi Web Sitesi**: [https://www.servbay.com](https://www.servbay.com)
*   **ServBay macOS Sürümü İndir/Ana Depo**: [https://github.com/ServBay/ServBay](https://github.com/ServBay/ServBay)
*   **ServBay Resmi Dokümantasyon/Destek Merkezi**: [https://support.servbay.com/](https://support.servbay.com/)

ServBay’i tercih ettiğiniz için teşekkür ederiz! Size en güçlü ve en pratik yerel geliştirme deneyimini sunmaya kararlıyız.