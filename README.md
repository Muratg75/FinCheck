# FinCheck - Finansal Varlık Takip Uygulaması

## 📋 Proje Açıklaması
FinCheck, finansal varlıklarınızı takip etmek ve enflasyona karşı performanslarını analiz etmek için geliştirilmiş kapsamlı bir Windows Forms uygulamasıdır. Uygulama, çeşitli yatırım araçlarının değerlerini gerçek zamanlı olarak izlemenizi ve portföy performansınızı detaylı şekilde analiz etmenizi sağlar.

## 🛠️ Teknik Özellikler
- **Platform**: .NET 9.0 Windows Forms Uygulaması
- **Dil**: C# 
- **Veri Saklama**: AppData dizininde şifrelenmiş JSON formatında
- **Güvenlik**: SHA256 hash algoritması ile şifre koruması
- **API Entegrasyonu**: GenelPara.com ve Hürriyet BigPara API'leri

## 🔐 Güvenlik Özellikleri
- **Şifre Koruması**: Uygulama girişi için güçlü şifre sistemi
- **Veri Şifreleme**: Tüm veriler AES şifreleme ile korunur
- **Şifre Değiştirme**: Güvenli şifre değiştirme mekanizması
- **Deneme Sınırı**: 3 yanlış deneme sonrası kilit

## 💰 Desteklenen Varlık Türleri
- **Döviz**: USD, EUR, GBP
- **Değerli Madenler**: Altın (Gram, Ons), Gümüş, Platin, Palladyum, Rodiyum
- **Kripto Paralar**: Bitcoin (BTC), Ethereum (ETH)
- **Borsa**: BIST 100, Brent Petrol
- **Mevduat**: Banka mevduatları

## 📊 Ana Özellikler

### Varlık Yönetimi
- **Varlık Ekleme**: Detaylı varlık bilgileri girişi
- **Varlık Silme**: Güvenli varlık silme işlemi
- **Varlık Düzenleme**: Mevcut varlıkların güncellenmesi
- **Portföy Özeti**: Toplam değer ve kar/zarar analizi

### Gerçek Zamanlı Veri
- **Çoklu API Desteği**: GenelPara.com ve Hürriyet BigPara
- **Otomatik Güncelleme**: Döviz kurları ve altın fiyatları
- **Tarihsel Veri**: Geçmiş fiyat verilerini görüntüleme
- **Performans Analizi**: Kar/zarar hesaplamaları

### Enflasyon Analizi
- **Enflasyon Kaybı**: Enflasyona karşı performans analizi
- **Karşılaştırmalı Analiz**: Farklı varlık türlerinin performansı
- **Zaman Bazlı Analiz**: Tarihsel performans takibi

### Mevduat Yönetimi
- **Mevduat Takibi**: Banka mevduatlarının yönetimi
- **Faiz Hesaplama**: Otomatik faiz hesaplamaları
- **Vade Takibi**: Mevduat vade bilgileri

## 🎨 Kullanıcı Arayüzü
- **Modern Tasarım**: Kullanıcı dostu arayüz
- **Renk Kodlaması**: Varlık türlerine göre görsel ayrım
- **Responsive Layout**: Farklı ekran boyutlarına uyum
- **Kolay Navigasyon**: Sezgisel menü yapısı

## 📈 Raporlama ve Analiz
- **Portföy Özeti**: Toplam değer ve performans
- **Detaylı Raporlar**: Varlık bazında analiz
- **Grafik Görünümler**: Fiyat trendleri
- **Export Özelliği**: Veri dışa aktarma

## 🔧 Kurulum ve Kullanım
1. Uygulamayı çalıştırın
2. İlk kullanımda güvenli bir şifre belirleyin
3. Varlıklarınızı ekleyin
4. Gerçek zamanlı verileri güncelleyin
5. Portföy performansınızı analiz edin

## 📁 Veri Yapısı
```
AppData/
├── assets.jfn          # Şifrelenmiş varlık verileri
├── deposits.jfn        # Şifrelenmiş mevduat verileri  
├── currencies.jfn      # Şifrelenmiş döviz kuru verileri
└── inflation.json      # Enflasyon verileri
```

## 🚀 Gelecek Özellikler
- [ ] Grafik ve chart görünümleri
- [ ] Excel export/import
- [ ] Mobil uygulama desteği
- [ ] Cloud senkronizasyonu
- [ ] Gelişmiş raporlama

## 📞 Destek
Herhangi bir sorun veya öneri için lütfen iletişime geçin.

---
**FinCheck v1.0.0** - Finansal varlık takip uygulaması