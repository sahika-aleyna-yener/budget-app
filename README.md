# 💜 BirikimAsistanı

> Yargılamayan, motive eden — Türkiye'ye özel kişisel finans asistanı.

Tek dosya HTML uygulaması. Kurulum yok, sunucu yok, hesap yok. Tarayıcıda aç, kullan.

---

## 🚀 Nasıl Kullanılır?

`BirikimAsistaniV3_1.html` dosyasını indirip herhangi bir tarayıcıda aç. Hepsi bu.

Tüm veriler **localStorage**'a kaydedilir — cihazında, güvende.

---

## ✨ Özellikler

| Özellik | Açıklama |
|---|---|
| 🎯 Hedef Takibi | Birikim hedefi, yüzde ilerlemesi, tahmini ulaşma tarihi |
| 📊 50/30/20 Analizi | İhtiyaç / İstek / Birikim bütçe dağılımı |
| 📈 Simülasyon | Aylık bileşik faizli birikim projeksiyonu, senaryo karşılaştırması |
| 💳 Kart Takipçisi | Kesim gününe göre günlük harcama limiti |
| 🛒 24 Saat İstek Sepeti | Anlık alışveriş dürtüsünü 24 saat beklet |
| 🥇 Altın Portföyü | Gram/çeyrek/tam altın takibi, kâr/zarar hesabı |
| 🏦 Mevduat Hesabı | Banka faiz karşılaştırması, TMSF uyarısı |
| 🎓 KYK / Burs | KYK bitiş tarihi ve tutarına göre plan ayarı |
| 🏅 12 Rozet | Kullanım alışkanlıklarına göre kazanılan başarımlar |
| 🤖 AI Koç | Claude API ile kişisel finans analizi (opsiyonel) |
| 📚 Finansal Rehber | Kakeibo, 50/30/20, davranışsal finans blog yazıları |

---

## 🗂 Versiyon Geçmişi

### V3.1 _(Kasım 2026)_
- `dailyLimit()` tarih hesabı bug'ı düzeltildi
- `simule()` saf nesne döndürüyor (`{adimlar, hedefAy}`)
- `sifir_gun` rozeti aktif hale getirildi
- Altın tutarı otomatik hesaplanıyor (gram ağırlığı × adet × güncel fiyat)
- 50/30/20 birikim barı gerçek planlı tasarrufa göre
- XSS koruması eklendi (`escHTML()`)
- 6 sekme → 5 sekme (Rozet "Daha Fazla" altına taşındı)
- Ayarlar accordion bölümlere ayrıldı
- Yaz aylarına Mayıs eklendi
- Streak + Blog tek kartta birleştirildi

### V3 _(Kasım 2026)_
- Çok özellikli tek dosya mimarisi
- NLP tabanlı hızlı harcama girişi
- SVG grafik motoru (donut, çizgi, halka)
- Karakter / maskot sistemi
- Abonelik mikro-sızıntı takibi
- Blog bölümü

---

## 🛠 Teknik Notlar

- **Tek dosya:** Inline CSS + JS, harici bağımlılık yok
- **Depolama:** `localStorage` (`ba_v3` anahtarı)
- **Grafik:** Özel SVG (kütüphane yok)
- **Mobil öncelikli:** `max-width: 480px`
- **AI:** Claude API (Anthropic) — opsiyonel, anahtar kullanıcıdan alınır

---

## 📌 Katkı

Bu proje şu an tek-geliştirici aşamasında. Önerilerin için [Issue](../../issues) aç.

---

<p align="center">Made with 💜 in İzmir</p>
