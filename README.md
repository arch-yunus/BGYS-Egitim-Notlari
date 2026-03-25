# 🛡️ ISO 27001: Bilgi Güvenliği Yönetim Sistemi (BGYS) Eğitim Portalı

![ISO 27001 Banner](./assets/banner.png)

<p align="center">
  <img src="https://img.shields.io/badge/ISO/IEC-27001:2013/2022-blue.svg" alt="ISO 27001">
  <img src="https://img.shields.io/badge/Yazar-Yunus%20Emre-orange.svg" alt="Author">
  <img src="https://img.shields.io/badge/Sürüm-v2.0-blueviolet.svg" alt="Version">
  <img src="https://img.shields.io/badge/Türkçe-Eğitim-red.svg" alt="Language">
</p>

---

## 🌟 Giriş: Neden ISO 27001?
Modern dünyada **veriyi korumak, kaleyi korumaktan daha zordur.** Siber saldırıların, veri sızıntılarının ve regülasyonların (KVKK, GDPR) arttığı bu dönemde, bilgi güvenliği sadece teknik bir konu değil, bir **yönetim disiplini** haline gelmiştir. 

ISO/IEC 27001, bir kuruluşun bilgi güvenliğini sistematik olarak yönetmesine yardımcı olan, uluslararası düzeyde tanınan tek standarttır. Bu depo, bu karmaşık standartlar dizisini parçalara bölerek anlaşılır hale getirmeyi amaçlar.

---

## 🏛️ Temel Mimari ve Standart Dokusu
BGYS eğitimi, üç ana sütun üzerine inşa edilmiştir:

1.  **CIA Üçlüsü:** Gizlilik, Bütünlük ve Erişilebilirlik.
2.  **Risk Temelli Yaklaşım:** Sadece "her şeyi" korumak değil, "önemli ve riskli olanı" korumak.
3.  **PUKO Döngüsü:** Sürekli iyileştirme için Planla, Uygula, Kontrol Et ve Önlem Al (PDCA).

---

## 🗺️ Eğitim Yol Haritası (Müfredat)

| Modül | İçerik Özeti | Durum |
| :--- | :--- | :--- |
| **[01. Temel Kavramlar](./modules/01-temel-kavramlar.md)** | Bilgi Güvenliği, CIA Üçlüsü, PUKO Döngüsü (Görsel Şemalı) | ✅ Aktif |
| **[02. Risk Yönetimi](./modules/02-risk-yonetimi.md)** | Varlık Envanteri, Tehdit Analizi, Risk İşleme Akışı | ✅ Aktif |
| **[03. Ek-A Kontrolleri](./modules/03-ek-a-kontrolleri.md)** | 114 Kontrolün Domain Bazlı Analizi. ([Tam Liste Referansı](./modules/Annex-A-Tam-Liste.md)) | ✅ Aktif |
| **[04. Denetim & Yönetim](./modules/04-denetim-ve-yönetim.md)** | İç Denetim, YGG Toplantıları ve Düzeltici Faaliyetler | ✅ Aktif |
| **[05. Politika & Doküman](./modules/05-politika-ve-dokümantasyon.md)** | Zorunlu Dokümanlar ve Temel Politika Taslakları | ✅ Aktif |
| **[06. Sınava Hazırlık](./exam-prep/soru-bankasi.md)** | Sektörel Sınavlara Yönelik Soru-Cevap Setleri | ✅ Aktif |

---

## 🚧 Uygulamada Sık Yapılan Hatalar (Altın Kurallar)
ISO 27001 yolculuğunda projelerin başarısız olmasına neden olan 3 yaygın hata:

1.  **Kapsamı Çok Geniş Tutmak:** Tüm kurumu tek seferde dahil etmeye çalışmak yerine, kritik süreçlerle (örn: Bilgi İşlem veya Finans) başlamak daha sağlıklıdır.
2.  **Sadece Dokümantasyona Odaklanmak:** BGYS "kağıt üzerinde" değil, "uygulamada" başarılı olur. Kanıtlanamayan hiçbir kontrol denetçiden geçemez.
3.  **Üst Yönetim Desteğinin Eksikliği:** Üst yönetim kaynak (personel/bütçe) sağlamazsa sistem sürdürülebilir olmaz.

---

## 🔍 İç Denetim vs. Dış Denetim
Aradaki farkları anlamak, sertifikasyon başarısı için kritiktir:

| Özellik | İç Denetim (Madde 9.2) | Dış (Belgelendirme) Denetimi |
| :--- | :--- | :--- |
| **Kim Yapar?** | Şirket içi personel veya danışman. | Akredite belgelendirme kuruluşu (TÜRKAK vb.). |
| **Amacı nedir?** | Eksikleri bulup düzeltmek (Ön hazırlık). | Standart uygunluğunu onaylayıp belge vermek. |
| **Sonuç nedir?** | İç denetim raporu ve aksiyonlar. | ISO 27001 Sertifikası veya Takip Denetimi. |

---

## 🛣️ ISO 27001 Sertifikasyon Yol Haritası
1.  **Gap Analizi:** Mevcut durum tespiti. ([Risk Analizi Taslağı](./templates/risk-analizi-taslak.md)) 🧪
2.  **Kapsam ve Politika:** BGYS sınırlarının çizilmesi ve taahhüt.
3.  **Risk Analizi:** Varlık ve risk tespiti.
4.  **Uygulama:** Ek-A kontrollerinin hayata geçirilmesi.
5.  **İç Denetim & YGG:** Sistemin test edilmesi.
6.  **Belgelendirme Denetimi:** Resmi sertifika süreci.

---

## 👤 Hazırlayan ve İletişim
Bu eğitim portalı, bilgi güvenliği kültürünü yaygınlaştırmak amacıyla bizzat **Yunus Emre** tarafından tasarlanmış ve geliştirilmiştir. 

- **Yazar:** Yunus Emre (@arch-yunus)
- **Vizyon:** "Bilgi, sadece paylaşıldığında ve korunduğunda bir güçtür."
- **İletişim:** Yeni soru setleri veya kurumsal talepler için Pull Request açabilir veya Issue üzerinden iletişime geçebilirsiniz.

---

## ⭐️ Topluluk ve Destek
Eğer bu proje size faydalı olduysa, daha fazla kişinin faydalanabilmesi için:
- Repoyu **Star**layın. ⭐
- Meslektaşlarınızla **Paylaşın**. 🔗
- Gelişime katkı sağlamak için **Fork**layın. 🚜

---
**Lisans:** [MIT](./LICENSE)  
**Hazırlayan:** Yunus Emre
