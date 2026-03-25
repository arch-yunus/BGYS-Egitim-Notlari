# 🛡️ Modül 03: Ek-A Referans Kontrolleri (Annex A) Analizi

ISO/IEC 27001 standardı, **Ek-A** (Annex A) kapsamında 14 farklı kontrol alanına (Domain) yayılmış 114 adet kontrol maddesi sunar. Bu kontroller, kurumsal risk analizinin somut karşılıklarıdır.

## 📋 Kontrol Domainlerinin Analiz Matrisi

Aşağıdaki matris, her bir disiplin için kritik kontrol odaklarını ve implementasyon standartlarını içermektedir:

| Domain Disiplini | Kritik Kontrol Odağı | Uygulama Standartları |
| :--- | :--- | :--- |
| **A.5 / A.6** | Politika Setleri & Organizasyonel Yapı | Kurumsal politikaların yılda en az bir kez ve majör altyapı değişikliklerinde revize edilmesi, üst yönetim onaylı hiyerarşi. |
| **A.7** | İnsan Kaynakları Güvenliği | İşe alım öncesi güvenlik taramaları, gizlilik sözleşmeleri (NDA) ve işten ayrılma süreçlerinde yetki deprizasyonu. |
| **A.8** | Varlık Yönetimi | Varlıkların mülkiyet ataması ve "Hassasiyet Derecelerine" (Gizli, Hizmete Özel vb.) göre sınıflandırma protokolü. |
| **A.9 / A.10** | Erişim Kontrolü & Kriptografi | "Least Privilege" (En Az Yetki) prensibi, MFA sistemleri ve uçtan uca veri şifreleme (Encryption) standartları. |
| **A.11** | Fiziksel ve Çevresel Güvenlik | Güvenli alanların (Veri Merkezi/Sistem Odası) biyometrik erişim ve çevresel izleme (Yangın/Isı) ile korunması. |
| **A.12** | İşletim Güvenliği | Yedekleme stratejileri (Restore Test), log yönetimi (SIEM entegrasyonu) ve antimalware merkezi yönetimi. |
| **A.13** | Haberleşme Güvenliği | Ağ segmentasyonu (VLAN/DMZ) ve dış ağ güvenliği için VPN/Güvenli tünelleme mimarileri. |
| **A.14** | Sistem Edinimi ve Bakımı | Güvenli SDLC süreçleri, Geliştirme (DEV) ve Üretim (PROD) ortamlarının fiziksel/mantıksal ayrımı. |
| **A.15** | Tedarikçi Güvenliği | Üçüncü taraf hizmet sağlayıcıları ile yapılan sözleşmelerde "Bilgi Güvenliği Şartnameleri" (SLA). |
| **A.16** | Olay Yönetimi | Güvenlik ihlallerine yönelik Olay Müdahale Planı (IRP) ve SOME/CERT ekiplerinin koordinasyonu. |
| **A.17** | İş Sürekliliği | Olağanüstü Durum Merkezi (ODM) planlaması ve İş Etki Analizi (İEA) çıktılı DR testleri. |
| **A.18** | Uyum (Compliance) | Yasal regülasyonların (KVKK, 5651, GDPR vb.) ve fikri mülkiyet haklarının takibi. |

---

## 🚀 Implementasyon ve Denetim İpuçları
- **Bağlamsal Seçim:** Tüm 114 kontrol zorunlu değildir; uygulanacak kontroller kurumun "Kapsamı" ve "Risk Analizi" sonucuna göre belirlenmelidir.
- **Evidence Management (Kanıt Yönetimi):** Denetim aşamasında kontrolün varlığı sadece politika ile değil; loglar, tutanaklar, ekran görüntüleri ve konfigürasyon kayıtları ile ispatlanmalıdır.

---
**[Ana Sayfa - README](../README.md)**
