# 🛡️ Modül 03: Ek-A Kontrolleri (Annex A)

ISO/IEC 27001:2013 standardı, **Ek-A** (Annex A) bölümünde 14 farklı grupta toplanmış 114 adet kontrol sunar. Bu kontroller, risk analizine göre seçilerek uygulanır.

## 📋 Kontrol Alanlarının Detaylı Analizi

Aşağıdaki tabloda her bir domain için kritik kontrol başlıkları ve uygulama önerileri yer almaktadır:

| Domain | Kritik Kontroller | Uygulama Önerisi |
| :--- | :--- | :--- |
| **A.5 / A.6** | Bilgi Güvenliği Politikaları & Organizasyon | Politikalar yılda bir kez veya majör değişikliklerde gözden geçirilmelidir. Üst yönetim onayı şarttır. |
| **A.7** | İnsan Kaynakları Güvenliği | İşe alımlarda adli sicil kaydı kontrol edilmeli, ayrılan personelin yetkileri anında iptal edilmelidir. |
| **A.8** | Varlık Yönetimi | Varlık envanteri güncel tutulmalı, gizlilik seviyelerine göre "Bilgi Sınıflandırması" yapılmalıdır. |
| **A.9 / A.10** | Erişim Kontrolü & Kriptografi | Parola politikaları (karmaşıklık, süre) uygulanmalı, hassas veriler (KVKK) şifrelenerek saklanmalıdır. |
| **A.11** | Fiziksel ve Çevresel Güvenlik | Sunucu odalarına biyometrik erişim, yangın söndürme ve kesintisiz güç kaynağı (UPS) sağlanmalıdır. |
| **A.12** | İşletim Güvenliği | Yedeklerin geri yüklenebilirliği test edilmeli (Restore Test), antivirüs merkezi yönetilmelidir. |
| **A.13** | Haberleşme Güvenliği | Ağ segmentasyonu (VLAN) yapılmalı, dış ağdan erişimler VPN/MFA ile korunmalıdır. |
| **A.14** | Sistem Edinimi ve Bakımı | Yazılım geliştirme için ayrı "Test" ve "Üretim" ortamları kullanılmalıdır. |
| **A.15** | Tedarikçi İlişkileri | Tedarikçi sözleşmelerine "Bilgi Güvenliği Ekleri" ve "Gizlilik Sözleşmeleri" (NDA) eklenmelidir. |
| **A.16** | Olay Yönetimi | Güvenlik ihlalleri için bir "Olay Müdahale Ekibi" (SOME/CERT) ve prosedürü olmalıdır. |
| **A.17** | İş Sürekliliği | İş Etki Analizi (İEA) yapılmalı ve Felaketten Kurtarma (DR) planları yılda en az bir kez test edilmelidir. |
| **A.18** | Uyum | Yasal mevzuat (KVKK, 5651 vb.) takibi yapılmalı ve lisanssız yazılım kullanılmamalıdır. |

---

## 🚀 Ek-A Uygulama İpuçları
- **Kontrol Seçimi:** Tüm 114 kontrolü uygulamak zorunda değilsiniz. Risk analizinizde "Düşük" çıkan alanlar için kontrol uygulamamayı seçebilir, bunu SOA'da gerekçelendirebilirsiniz.
- **Kanıt Toplama:** Denetçiler kontrolün "yapıldığını" değil, "yapıldığına dair kanıtı" (log, form, imza, ekran görüntüsü) görmek ister.

---
**[Geri Dön - README](../README.md)**
