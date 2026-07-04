# AIRCHIP 🖐️

[English](README.md) | **Türkçe**

**Fotoğraflarını bir bilim kurgu filmindeymiş gibi, sadece ellerinle yönet.**

Kamera, elinin 21 eklem noktasını gerçek zamanlı takip eder. Fotoğrafları parmaklarını
kıstırarak tutar, telefondaki gibi parmak açarak büyütür, tüm galeriyi havada gezdirir
ve anılarını albümlere ayırırsın — mouse yok, dokunmatik yok.

> Bu uygulamanın tek satırını elle yazmadım — tamamını [Claude Code](https://claude.com/claude-code)'a tarif ederek yaptırdım.

🌐 **Canlı demo:** https://eneslexi.github.io/memory-chip/

## 🚀 Çalıştırma

**En kolay:** `index.html` dosyasını indir, Chrome'da aç, kamera iznini ver. Hepsi bu — sunucu yok, kurulum yok.

- Her şey **kendi cihazında** çalışır: fotoğrafların cihazından çıkmaz, hiçbir yere yüklenmez.
- Telefonda kamera için HTTPS gerekir — canlı demo linkini kullan ya da kendin yayınla.

## ✋ Jestler

| Hareket | Ne yapar |
|---|---|
| 👌 Baş parmak + işaret parmağını kıstır | Fotoğrafı tut |
| 🤏↔️ Tutarken parmak arasını aç/kapat | Büyüt / küçült (telefondaki gibi) |
| 🖐️ Avucunu tamamen aç | Bırak |
| ✋ Elini ekranda gezdir | Tüm galeri derinlik hissiyle seninle akar |
| 🖐️⬆ Açık avucu en üste kaldır | Diziliş değişir (ızgara ↔ serbest) |
| 📁 Fotoğrafı yuvanın üstünde beklet | O albüme kaydolur |
| 👆 Parmağı butona getir + kıstır | Havadan buton basma |

## 🔧 Nasıl çalışıyor?

- **El takibi:** MediaPipe Hands — tarayıcı içinde, cihaz üstünde
- **Sesler:** Ses dosyası yok; tüm sesler WebAudio ile anlık sentezlenir
- **Depolama:** IndexedDB — fotoğraflar ve albümler cihazında kalıcı
- **Tek dosya:** Uygulamanın tamamı `index.html`

## 🧑‍🚀 Yapan

**Enes** — ürünlerimi yapay zekâyla inşa ediyorum ve süreci paylaşıyorum:

- X: [@Eneslexi](https://x.com/Eneslexi) · Instagram: [@enesa.co](https://instagram.com/enesa.co) · TikTok: [@eneslexi](https://tiktok.com/@eneslexi)

Demo fotoğrafları: Wikimedia Commons (CC). Lisans: MIT — istediğin gibi kullan, öğren, değiştir.
