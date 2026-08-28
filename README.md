Markdown

# Dörtlük Yazma Programı

Türk halk şiiri ve hece ölçülü şiir yazarlarının mısra hece sayılarını, kafiye şemalarını ve ölçü uyumunu anlık olarak takip etmelerini sağlayan web tabanlı bir yardımcı araçtır.

![Dörtlük Yazma Programı - Mihriban Şiiri Örneği](https://raw.githubusercontent.com/Akhenaton41/Dortluk-Yazma-Programi/refs/heads/main/mihriban.png)

## 🚀 Canlı Önizleme & Kullanım
Uygulamayı doğrudan tarayıcınızda kullanmak için:  
👉 **[Dörtlük Yazma Programı Canlı İzle](https://akhenaton41.github.io/Dortluk-Yazma-Programi/)**

---

## ✨ Özellikler

* 📐 **Otomatik Hece Sayacı & Ölçü Doğrulama:**
  * Seçilen hece ölçüsüne (7'li, 8'li, 10'lu, 11'li, 12'li vb.) göre mısradaki sesli harfleri anlık hesaplar.
  * Mısra hece sayısı seçilen ölçüyle tam eşleştiğinde yeşil (`valid`), eksik ya da fazla olduğunda kırmızı (`invalid`) renk ile geliştiriciyi görsel olarak uyarır.

* 🏷️ **Dinamik Kafiye Şeması Etiketleme:**
  * Mısra sonlarındaki kelimelerin sesli/sessiz harf yapılarını analiz ederek sayfa genelinde **A, B, C, D...** şeklinde otomatik kafiye rozetleri (badges) üretir.

* 🔍 **Entegre Türkçe Kafiye Arama Motoru:**
  * Kelime veritabanı (`turkceKelimeler.js`) üzerinden aranan kelimenin son ses uyumuna göre kafiye eşleşmelerini listeleyen ayrı bir arama penceresi sunar.

* 📋 **Toplu Şiir Yapıştırma & Otomatik Dörtlük/Ölçü Tespiti:**
  * Yapıştırılan ham şiir metinlerini otomatik olarak 4'erli dörtlük gruplarına ayırır.
  * Şiirin genelinde en sık kullanılan hece sayısını tespit ederek hece ölçüsü seçim kutusunu otomatik ayarlar.

* 💾 **Yerel Arşiv & Şiir Depolama (`localStorage`):**
  * Şiirleri başlıkları ile tarayıcı hafızasına kaydetme, arşivden geri yükleme, silme ve son çalışılan şiiri otomatik açma desteği sağlar.

* 📤 **Derleme & Panoya Kopyalama:**
  * Tamamlanan şiirleri başlığıyla birlikte düzgün biçimlendirilmiş metin formatında derler ve panoya kolayca kopyalama imkanı verir.

---

## 🛠️ Kurulum ve Çalıştırma

Proje herhangi bir derleme aracı, Node.js veya sunucu kurulumu gerektirmez (Sunucusuz / Pure JavaScript & HTML5).

1. Repoyu bilgisayarınıza indirin veya klonlayın:
   ```bash
   git clone [https://github.com/Akhenaton41/Dortluk-Yazma-Programi.git](https://github.com/Akhenaton41/Dortluk-Yazma-Programi.git)
