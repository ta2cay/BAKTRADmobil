# 📡 BAKTRAD Mobil v4.0

**Batı Karadeniz Telsiz ve Radyo Amatörleri Derneği**  
Resmi Mobil Uygulaması

[![PWA](https://img.shields.io/badge/PWA-Ready-blue?logo=googlechrome)](https://baktrad.org.tr/mobil/)
[![Version](https://img.shields.io/badge/Versiyon-4.0-orange)](https://baktrad.org.tr/mobil/)
[![License](https://img.shields.io/badge/Lisans-MIT-green)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web-lightgrey)](https://baktrad.org.tr/mobil/)

---

## 📸 Ekran Görüntüleri

<p align="center">
  <img src="https://github.com/ta2cay/BAKTRADmobil/blob/main/01.jpeg" width="18%" alt="Ana sayfa"/>
  <img src="https://github.com/ta2cay/BAKTRADmobil/blob/main/02.jpeg" width="18%" alt="Ana Sayfa-2"/>
  <img src="https://github.com/ta2cay/BAKTRADmobil/blob/main/03.jpeg" width="18%" alt="içerik"/>

</p>

---

## 📱 Uygulama Hakkında

BAKTRAD Mobil, ülkemizdeki amatör radyo ve telsiz istasyonlarının haftalık çevrim (net) kayıtlarını, istatistiklerini ve arşivini mobil cihazlardan yönetmek için geliştirilmiş bir **Progressive Web App (PWA)**'dır.

> 🌐 **Canlı Adres:** [baktrad.org.tr/mobil](https://baktrad.org.tr/mobil/)  
> 📻 **Çevrim Portalı:** [cevrim.baktrad.org.tr](https://cevrim.baktrad.org.tr)

---

## ✨ v4.0 Yenilikleri

| Özellik | Açıklama |
|---|---|
| 🎨 **Yeni Arayüz** | Tamamen yeniden tasarlanmış dark-mode öncelikli UI |
| 📊 **Gelişmiş İstatistikler** | Çevrim grafikleri, katılım analizleri, rekor takibi |
| 🔔 **Akıllı Bildirim** | Gelecek çevrim operatörü tek popup'ta, 5sn sonra kapanır |
| 🛰️ **ISS Canlı Takip** | Uluslararası Uzay İstasyonu radar görünümü |
| 🌦️ **Propagasyon** | Güneş aktivitesi ve HF bant durumu (SFI, A, K indeksi) |
| 🗺️ **QTH Bulucu** | GPS ile anlık Maidenhead locator hesaplama |
| 🔴 **Deprem Bandı** | Kandilli Rasathanesi canlı veri akışı |
| 🏆 **Lider Tablosu** | En aktif katılımcılar sıralaması |
| 📜 **Çevrim Arşivi** | Tüm geçmiş çevrimlerin kayıtları ve detayları |
| 🏅 **Sertifika** | Katılım sertifikası PDF oluşturma |

---

## 📋 Özellikler

### 🔴 Ana Sayfa
- Son çevrim raporu (tarih, operatör, katılım sayısı)
- Gelecek çevrim geri sayımı ve operatör bilgisi
- Son haberler (baktrad.org.tr RSS)
- Son depremler canlı bandı
- ISS canlı radar takibi
- QTH Locator
- Röle bilgileri ve kapsama haritaları
- Şube ve temsilcilik bilgileri

### 📡 Çevrim Modülü
- Haftalık çevrim kayıtları (`Her Perşembe 21:00`)
- Detaylı katılımcı listeleri
- Operatör istatistikleri
- Popüler çevrimler
- Çevrim arşivi (tarih bazlı)

### 🔬 Araçlar
- Propagasyon durumu
- CW (Mors) dersleri
- APRS kod üretici
- TA Röle haritası
- TA Callbook sorgulama
- Sınav hazırlık
- Echolink Web
- ISS Takip
- Yazılım arşivi
- Yarışma takvimi

### 👤 Üye Sistemi
- Giriş / kayıt
- Profil sayfası
- Kişisel çevrim istatistikleri

---

## 🛠️ Teknik Yapı

```
mobil/
├── index.php          # Ana sayfa (Dashboard)
├── header.php         # Sayfa başlığı ve navigasyon
├── footer.php         # Alt alan
├── backend_config.php # Veritabanı ve API yapılandırması
├── styles.css         # Ana stil dosyası
├── app.js             # Uygulama JavaScript motoru
├── sw.js              # Service Worker (offline destek)
├── manifest.json      # PWA manifest
├── splash.html        # Açılış ekranı
├── cevrim.php         # Çevrim listesi
├── detay.php          # Çevrim detay
├── analiz.php         # İstatistik analizi
├── arsiv.php          # Arşiv
├── propagasyon.php    # Propagasyon
├── iss.php            # ISS takip
├── sinav.php          # Sınav hazırlık
└── ...                # 60+ sayfa
```

**Kullanılan Teknolojiler:**
- PHP 8.x (Backend)
- MySQL (Veritabanı)
- Bootstrap Icons
- Chart.js
- Google Fonts (Inter, JetBrains Mono)
- Service Worker API
- Geolocation API
- Web Share API
- Vibration API

---

## 📲 Kurulum (APK / Telefona Yükleme)

### Yöntem 1: Tarayıcıdan Yükle (Önerilen)
1. Telefonunuzda Chrome ile [baktrad.org.tr/mobil](https://baktrad.org.tr/mobil/) adresini açın
2. Adres çubuğunda çıkan **"Uygulamayı Yükle"** butonuna dokunun
3. Onaylayın — uygulama ana ekranınıza eklenir

### Yöntem 2: APK ile Yükle
1. [Releases](https://github.com/ta2cay/BAKTRADmobil/releases/latest) sayfasından son APK'yı indirin
2. Telefonunuzda **"Bilinmeyen kaynaklardan yüklemeye izin ver"** açık olmalı
3. APK dosyasını çalıştırın ve yükleyin

---

## 🔗 Bağlantılar

| | |
|---|---|
| 🌐 Ana Site | [baktrad.org.tr](https://baktrad.org.tr) |
| 📡 Çevrim Portalı | [cevrim.baktrad.org.tr](https://cevrim.baktrad.org.tr) |
| 📱 Mobil Uygulama | [baktrad.org.tr/mobil](https://baktrad.org.tr/mobil) |
| 📘 Facebook | [BAKTRAD Grubu](https://www.facebook.com/groups/baktrad/) |
| 📸 Instagram | [@baktrad_genel_merkezi_ym2kv](https://www.instagram.com/baktrad_genel_merkezi_ym2kv/) |
| 📺 YouTube | [BAKTRAD Kanalı](https://www.youtube.com/@baktradbartin2389) |
| 📻 QRZ | [YM2KV](https://www.qrz.com/db/YM2KV) |

---

## 📻 Röle Bilgileri

| Lokasyon | Frekans | Ton | Tip |
|---|---|---|---|
| Bartın Merkez | 145.600 MHz | 88.5 | Röle |
| Çaycuma | 145.625 MHz | 88.5 | Röle |
| Safranbolu | 145.6125 MHz | 88.5 | Röle |
| Yenice | 145.675 MHz | 100.0 | Röle |
| Amasra | 433.475 MHz | 88.5 | Cross |
| İnkum | 433.450 MHz | 88.5 | Cross |
| Çankırı | 439.275 MHz | 88.5 | Röle |

---

## 👥 Şube ve Temsilcilikler

- **Merkez:** Bartın — YM2KV
- **Şube:** Zonguldak/Çaycuma — YM2KCY
- **Şube:** Karabük/Safranbolu — YM2KRB
- **Temsilcilik:** İstanbul — YM1KV
- **Temsilcilik:** Çankırı — YM6KV
- **Temsilcilik:** Karabük/Yenice — YM2KNZ
- **Temsilcilik:** Bartın/Amasra — YM2KAM
- **Temsilcilik:** Bartın/Ulus — YM2KUL
- **Temsilcilik:** Kastamonu/Cide — YM6KCD

---

## 📄 Lisans

MIT License — © 2026 BAKTRAD / TA2CAY

---

*73 de YM2KV — Batı Karadeniz'den selam!* 📡
