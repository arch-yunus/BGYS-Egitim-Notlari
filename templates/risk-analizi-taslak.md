# 🧪 Risk Analizi ve Değerlendirme Tablosu (Taslak)

Bu şablon, basit bir risk analizi çalışması için başlangıç noktası olarak kullanılabilir.

| Varlık Adı | Varlık Değeri (1-3) | Tehdit | Zafiyet | Olasılık (1-3) | Etki (1-3) | Risk Skoru (O x E) | Risk İşleme Seçeneği | Uygulanacak Ek-A Kontrolü |
| :--- | :---: | :--- | :--- | :---: | :---: | :---: | :--- | :--- |
| Müşteri Veritabanı | 3 | Veri Sızıntısı | Güncellenmemiş DB | 2 | 3 | 6 (Yüksek) | Azaltma | A.12.6.1, A.10.1.1 |
| Sunucu Odası Kapısı | 2 | Yetkisiz Giriş | Kilit Arızası | 1 | 3 | 3 (Orta) | Azaltma | A.11.1.2 |
| Yedek Harddiskler | 3 | Veri Kaybı | Şifresiz Depolama | 2 | 3 | 6 (Yüksek) | Azaltma | A.8.2.3, A.10.1.1 |
| Ofis Bilgisayarları | 2 | Malware / Virüs | Antivirüs Eksikliği | 3 | 2 | 6 (Yüksek) | Azaltma | A.12.2.1 |

---

## 📏 Skorlama Rehberi
- **Varlık Değeri:** 1 (Düşük), 2 (Orta), 3 (Kritik).
- **Olasılık:** 1 (Nadir), 2 (Olası), 3 (Sık).
- **Etki:** 1 (Düşük), 2 (Ciddi), 3 (Felaket).
- **Risk Skoru:** 
    - 1-2: Düşük (Kabul Edilebilir)
    - 3-4: Orta (İzlenmeli)
    - 6-9: Yüksek (Derhal Aksiyon Alınmalı)

---
**[Geri Dön - README](../README.md)**
