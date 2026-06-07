# C# Windows Forms Çalışma Sayfası

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Görsel Programlama I Dersi · Final Çalışma Materyali**

<sub>Hazırlayan: **DEVNANOTEK — İslam ERGÜN**</sub>

</div>

---

## Bilgi

| | |
|---|---|
| **Üniversite** | Mardin Artuklu Üniversitesi |
| **Bölüm** | Bilgisayar Programcılığı |
| **Sınıf** | 1. Sınıf |
| **Ders** | Görsel Programlama I |
| **Öğretim Görevlisi** | Öğr.Gör.Dr. Muhammed Fatih Ağalda |

---

## Proje Hakkında

Bu proje, **Görsel Programlama I** dersi kapsamında işlenen **C# Windows Forms** konularını öğrenmeyi ve pekiştirmeyi amaçlayan interaktif bir web çalışma sayfasıdır. 33 farklı konu; kod örnekleri, sade Türkçe açıklamalar ve beklenen çıktılarıyla birlikte sunulmuştur. Ayrıca kapsamlı bir **öğrenme rehberi** ve **25 soruluk bilgi testi** içermektedir.

### Özellikler

- **33 Konu** — Buton tıklamasından MessageBox'a, Timer'dan Random'a kadar tüm temel Windows Forms konuları
- **Kod Görüntüleyici** — C# syntax highlighting (Highlight.js) ile renklendirilmiş kod blokları
- **Tek Tıkla Kopyala** — Her kod bloğunu tek butonla panoya kopyalama
- **Beklenen Çıktı** — Her konu için kodun çalıştığında ne üreteceğini gösteren çıktı bölümü
- **Sidebar Navigasyon** — Konular arası hızlı gezinme, aktif konu takibi
- **Öğrenme Rehberi** — Sıfırdan başlayanlar için "5 yaşındaki birine anlatır gibi" detaylı açıklamalar
- **Bilgi Testi** — 25 soruluk çoktan seçmeli sınav, anlık sonuç ve istatistik
- **Responsive Tasarım** — Mobil, tablet ve masaüstünde eksiksiz çalışır
- **Dark Theme** — Göz yormayan koyu tema

---

## Sayfalar

### `index.html` — Ana Çalışma Sayfası
33 konunun tamamını içerir. Her konu kartında:
- Konu numarası ve kategorisi
- Başlık
- Sade Türkçe açıklama
- Renklendirilmiş C# kodu (kopyalanabilir)
- Beklenen çıktı

### `ogren.html` — Sıfırdan Öğrenme Rehberi
Hiç bilmeyenler için hazırlanmış kapsamlı ders notu:
- Değişkenler, kontroller, özellikler, olaylar
- `if-else`, `for` döngüsü, diziler
- `MessageBox`, `Timer`, `Random`
- Operatörler, form geçişi, dinamik kontroller
- Her konu için günlük hayattan benzetmeler ve hap bilgiler
- Hızlı özet tablosu

### `test.html` — Bilgi Testi
25 çoktan seçmeli soru ile kendini sına:
- Doğru / Yanlış / Boş istatistikleri
- Her soru için doğru cevabı ve açıklamasını görme
- Yüzdelik başarı puanı ve seviyeye göre geri bildirim
- İlerleme çubuğu
- Testi sıfırlayıp tekrar çözme

---

## Kullanılan Teknolojiler

| Teknoloji | Sürüm | Kullanım Amacı |
|---|---|---|
| HTML5 | — | Sayfa yapısı |
| CSS3 | — | Stil ve responsive tasarım |
| JavaScript (ES6) | — | Dinamik içerik, test mantığı |
| jQuery | 3.7.1 | DOM manipülasyonu, animasyonlar |
| Bootstrap 5 | 5.3.3 | Grid sistemi, responsive altyapı |
| Bootstrap Icons | 1.11.3 | İkonlar |
| Highlight.js | 11.9.0 | C# kod sözdizimi renklendirme |

Tüm bağımlılıklar **CDN** üzerinden yüklenir, ek kurulum gerektirmez.

---

## Kurulum & Çalıştırma

1. Repoyu klonlayın:
   ```bash
   git clone https://github.com/kullaniciadi/csharp-windowsforms-calisma.git
   ```

2. `www` klasöründeki `index.html` dosyasını tarayıcıda açın.

> Ek bir kurulum veya sunucu gerekmez. Tüm dosyalar statik HTML'dir.

---

## Klasör Yapısı

```
www/
├── index.html      # Ana çalışma sayfası (33 konu)
├── ogren.html      # Sıfırdan öğrenme rehberi
└── test.html       # 25 soruluk bilgi testi
```

---

## Konu Listesi

| # | Kategori | Başlık |
|---|---|---|
| 01 | Temel İşlem | Butona Basınca Yazı Değiştirme |
| 02 | Temel İşlem | TextBox'taki Yazıyı Label'a Yazdırma |
| 03 | Değişkenler | Değişken ile Veri Taşıma |
| 04 | Değişkenler | İki Sayıyı Toplama |
| 05 | Döngüler | For Döngüsü ile Üs Alma |
| 06 | Döngüler | Faktöriyel Hesaplama |
| 07 | Hesaplama | Restoran Menü Fiyat Hesaplama |
| 08 | MessageBox | MessageBox ile Bilgi Penceresi Açma |
| 09 | MessageBox | MessageBox'ta Değişken Kullanma |
| 10 | Hesaplama | İki Sayının Dört İşlemi |
| 11 | Text İşlemleri | İki TextBox'taki Yazıyı Yer Değiştirme |
| 12 | Temel İşlem | Programı Kapatma |
| 13 | Hesaplama | Öğrenci Not Ortalaması Hesaplama |
| 14 | ComboBox | ComboBox'a Şehir Ekleme |
| 15 | Hesaplama | Sinema Sipariş Hesaplama |
| 16 | Karar Yapıları | Vize ve Final Notundan Geçme/Kalma |
| 17 | Karar Yapıları | Adete Göre İndirimli Fiyat Hesaplama |
| 18 | Quiz Uygulaması | Doğru/Yanlış Quiz Uygulaması |
| 19 | Döngüler | Sayının Bölenlerini Bulma |
| 20 | Timer | Timer ile Arka Plan Rengi Değiştirme |
| 21 | Timer | Dijital Saat Yapımı |
| 22 | ProgressBar | ProgressBar Artırma ve Azaltma |
| 23 | Random | Rastgele Sayı Üretme |
| 24 | Random | Rastgele Sayıları Karşılaştırma |
| 25 | Random | Rastgele Şifre Üretme |
| 26 | Form İşlemleri | Bir Formdan Diğerine Veri Gönderme |
| 27 | Form İşlemleri | Projeye Yeni Form Ekleme |
| 28 | Form İşlemleri | PictureBox ile Farklı Formları Açma |
| 29 | Dinamik Kontroller | Kod ile Araç Ekleme |
| 30 | Dinamik Kontroller | For Döngüsü ile Dinamik Buton Oluşturma |
| 31 | Text İşlemleri | RichTextBox Karakter Sayacı |
| 32 | CheckBox | CheckBox ile Butonu Aktif/Pasif Yapma |
| 33 | RadioButton | RadioButton ile Cinsiyet Seçimi |

---

## Ekran Görüntüleri

*Projeyi klonlayıp tarayıcıda `www/index.html` dosyasını açarak tüm sayfaları görüntüleyebilirsiniz.*

---

## Lisans

Bu proje eğitim amaçlı hazırlanmıştır. Dilediğiniz gibi kullanabilir, paylaşabilir ve geliştirebilirsiniz.

---

<div align="center">

**Mardin Artuklu Üniversitesi · Bilgisayar Programcılığı · 2024-2025**

*Başarılar!*

</div>
