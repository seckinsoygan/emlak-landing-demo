<div align="center">

# 🏛️ DEMO Gayrimenkul — Dark Luxury Emlak

**İstanbul'un en prestijli adresleri için tasarlanmış, tek dosyalık lüks gayrimenkul landing page demosu.**

Sıfır bağımlılık · Kurulum yok · Herhangi bir tarayıcıda açılır

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?logo=javascript&logoColor=black)](#)
[![No Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)](#)

</div>

---

## ✨ Hakkında

Bu proje, emlak ve gayrimenkul firmalarına yönelik **kurumsal web sitesi + portföy listeleme** demosudur. Amaç; potansiyel müşteriye "profesyonel, güvenilir, modern" hissi vermek ve firmayı rakiplerinden görsel olarak bir adım öne çıkarmaktır.

Tüm HTML, CSS ve JavaScript **tek bir `index.html` dosyasında** yer alır — derleme adımı, paket yöneticisi veya sunucu gerektirmez.

## 🎨 Tasarım

**"Dark Luxury Real Estate"** estetiği:

| | |
|---|---|
| **Palet** | `#0D0D0D` derin siyah · `#FFFFFF` saf beyaz · `#B8975A` altın |
| **Başlık fontu** | Cormorant Garamond (zarafet, güven) |
| **Gövde fontu** | Outfit (modern, temiz) |
| **Doku** | İnce grain overlay + subtle gold gradient vurgular |
| **Animasyon** | Yavaş, sinematik `cubic-bezier` geçişler |
| **Layout** | Asimetrik grid — sol ağır, sağ havadar |

## 🚀 Özellikler

- 🖥️ **Tam ekran sinematik hero** — clip-path kesimli görsel, animasyonlu scroll indicator
- 📊 **CountUp istatistikler** — IntersectionObserver ile viewport'a girince tetiklenir
- 🏆 **Öne çıkan portföy** — asimetrik kart grid'i, Tümü / Satılık / Kiralık / Proje tab filtresi
- 🔍 **Akıllı arama paneli** — glassmorphism tasarım, JS array filter ile çalışan sonuç sayacı
- 🗂️ **Dinamik ilan listeleme** — ilanlar JS array'inden render edilir, "Daha Fazla" ile stagger fade-in
- 👔 **Hizmetler, ekip & referanslar** — Lucide ikonlarla zenginleştirilmiş bölümler
- 📬 **İletişim formu** — gerçek zamanlı validation + başarı mesajı (gönderim simülasyonu)
- 📱 **Mobile-first responsive** — 375px → 1440px sorunsuz, hamburger drawer menü
- ⚡ **Performans odaklı** — yalnızca `transform` & `opacity` animasyonları, `prefers-reduced-motion` desteği

## 📑 Sayfa Bölümleri

1. Hero (tam ekran)
2. İstatistik / Güven bölümü
3. Öne çıkan portföy (filtrelenebilir)
4. Arama / Filtre paneli
5. Tüm ilanlar grid'i
6. Hizmetlerimiz
7. Neden Biz / USP
8. Danışmanlar / Ekip
9. Referanslar / Yorumlar
10. İletişim & Ofis (harita ile)
11. Footer

## 🛠️ Teknolojiler

- **Vanilla HTML5 / CSS3 / JavaScript** — framework yok
- **Google Fonts** (Cormorant Garamond + Outfit) — CDN
- **Lucide Icons** — CDN
- **Unsplash** — placeholder görseller
- **Google Maps Embed** — ofis konumu

## ▶️ Çalıştırma

Kurulum gerektirmez. `index.html` dosyasını çift tıklayarak tarayıcıda açın:

```bash
# veya bir yerel sunucu ile (opsiyonel)
npx serve .
```

> 💡 Görseller ve harita canlı internet üzerinden yüklenir; çevrimdışıyken görsel alanları boş kalabilir.

## ⚙️ Özelleştirme

Gerçek bir firmaya teslim için güncellenecek noktalar:

- **Firma kimliği** — `index.html` içinde marka adı, logo ve renkler (`:root` CSS değişkenleri)
- **İlan verileri** — `<script>` içindeki `listings` array'i firmanın gerçek portföyüyle değiştirilir
- **Görseller** — Unsplash URL'leri firmanın gerçek ilan fotoğraflarıyla güncellenir
- **Harita** — iletişim bölümündeki Google Maps embed ofis koordinatına ayarlanır
- **Form** — backend veya [Formspree](https://formspree.io) gibi bir servise bağlanır
- **SEO** — `og:title`, `description`, `canonical` meta etiketleri firmaya göre düzenlenir

## 📁 Proje Yapısı

```
.
├── index.html        # Tüm proje (HTML + CSS + JS)
└── README.md
```

## 📄 Lisans

Bu proje demo amaçlıdır. Görseller [Unsplash](https://unsplash.com) lisansı kapsamındadır.

---

<div align="center">
<sub>Tek dosya. Sıfır bağımlılık. Saf zanaat.</sub>
</div>
