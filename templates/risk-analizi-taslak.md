# ⚖️ Kurumsal Risk Analizi ve Değerlendirme Matrisi (Taslak)

Bu şablon, ISO/IEC 27001 gerekliliklerine uygun olarak temel düzeyde bir risk değerlendirme ve önceliklendirme çalışması yürütmek amacıyla tasarlanmıştır.

| Varlık Tanımı | Stratejik Değer (1-3) | Olası Tehdit | Yapısal Zafiyet | Olasılık (1-3) | Operasyonel Etki (1-3) | Risk Skoru (O x E) | Risk İşleme Stratejisi | Öngörülen Ek-A Kontrolü |
| :--- | :---: | :--- | :--- | :---: | :---: | :---: | :--- | :--- |
| **Müşteri Veritabanı** | 3 | Veri İhlali / Sızıntı | Güncel Olmayan Yama Seviyesi | 2 | 3 | 6 (Yüksek) | Azaltma | A.12.6.1, A.10.1.1 |
| **Sunucu Odası Erişimi** | 2 | Yetkisiz Giriş | Biyometrik Kilit Arızası | 1 | 3 | 3 (Orta) | Azaltma | A.11.1.2 |
| **Felaketten Kurtarma (DR) Yedekleri** | 3 | Kritik Veri Kaybı | Şifresiz Depolama Yapısı | 2 | 3 | 6 (Yüksek) | Azaltma | A.8.2.3, A.10.1.1 |
| **Kurumsal Uç Noktalar** | 2 | Zararlı Yazılım Enjeksiyonu | EDR/Antivirüs Yazılım Eksikliği | 3 | 2 | 6 (Yüksek) | Azaltma | A.12.2.1 |

---

## 📏 Metodolojik Skorlama Rehberi
- **Varlık Değeri:** 1 (Düşük/Destekleyici), 2 (Orta/Kritik Süreç), 3 (Yüksek/Hayati).
- **Olasılık (Probability):** 1 (Düşük/Nadir), 2 (Orta/Olası), 3 (Yüksek/Sık).
- **Etki (Impact):** 1 (Düşük/Operasyonel), 2 (Ciddi/Finansal-İtibar), 3 (Kritik/Yasal-Felaket).
- **Risk Önceliklendirme:** 
    - **1-2:** Düşük Risk (İzleme Modu)
    - **3-4:** Orta Risk (Planlı İyileştirme)
    - **6-9:** Yüksek Risk (İvedilikle Müdahale ve Kontrol Tahsisi)

---
**[Ana Sayfa - README](../README.md)**
