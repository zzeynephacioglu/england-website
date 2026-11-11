# Londra Rehberi 

> İngiltere'nin kültürünü, ikonik simgelerini ve seyahat rotalarını tanıtan, modern, performans odaklı ve tam duyarlı (responsive) bir web uygulaması.

---

## Teknik Özellikler ve Mimari Yapı

Projenin teknik altyapısı, hız, sürdürülebilirlik ve modern web standartları gözetilerek saf web teknolojileriyle geliştirilmiştir:

* **HTML5 :** SEO uyumluluğu ve ekran okuyucu erişilebilirliği göz önünde bulundurularak `header`, `main`, `section` gibi anlamsal etiketlerle oluşturulmuştur.
* **Modern CSS3:** 
  * Yerleşimler için **CSS Grid** ve **Flexbox** kullanılarak esnek ve akışkan bir yapı elde edilmiştir.
  * Tema ve renk yönetimini standartlaştırmak için **CSS Custom Properties (Değişkenler)** entegre edilmiştir.
  * Cihazlar arası sorunsuz geçişler için optimize edilmiş geçiş efektleri ve **Media Queries** ile mobil öncelikli duyarlı tasarım uygulanmıştır.
* **Saf (Vanilla) JavaScript (ES6+):** 
  * Harici framework veya ağır kütüphane bağımlılığı bulunmamaktadır; bu sayede minimum dosya boyutu ve maksimum çalışma zamanı performansı sağlanır.
* **Performans ve Varlık Yönetimi:** Görseller ve statik varlıklar web performans standartlarına uygun olarak optimize edilmiştir.

---

## Web Sitesi Ekran Görüntüleri
**1. Keşfet**
   
   <img width="1600" height="698" alt="WhatsApp Image 2026-11-11 at 23 18 36" src="https://github.com/user-attachments/assets/249a3b35-c191-4734-859f-c4b15cace3d1" />


**2. Deneyimle**
 
   <img width="1600" height="673" alt="WhatsApp Image 2026-11-11 at 23 18 37" src="https://github.com/user-attachments/assets/d21d4fa2-f0fb-48c1-92ea-806c66d1ea05" />


**3. Pratik Bilgiler**
   
   <img width="1600" height="694" alt="WhatsApp Image 2026-11-11 at 23 18 36 (1)" src="https://github.com/user-attachments/assets/091398f3-139c-49d5-95d8-cfd72b4abc4d" />

---

##  Proje Yapısı

```text
england-website/
│
├── index.html          # Ana sayfa ve sayfa iskeleti
├── assets/             # Görseller ve medya dosyaları
├── css/                # Stil dosyaları
│   └── style.css       # Ana tasarım, grid ve duyarlı görünüm kuralları
└── js/                 # JavaScript betikleri
    └── main.js         # Etkileşim, olay yönetimi ve dinamik öğeler
