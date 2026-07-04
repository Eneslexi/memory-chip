# MEMORY CHIP 🖐️

**Fotoğraflarını bir bilim kurgu filmindeymiş gibi, ellerinle havada yönet.**

Kamera elinin 21 eklem noktasını gerçek zamanlı takip eder. Fotoğrafları parmaklarınla tutar,
büyütür, havada savurur ve albümlere ayırırsın — mouse yok, dokunmatik yok.

> Bu uygulamanın tek satırını elle yazmadım — tamamını [Claude Code](https://claude.com/claude-code)'a tarif ederek yaptırdım.

## 🚀 Çalıştırma

**En kolay:** `index.html` dosyasını indir, Chrome'da aç, kamera iznini ver. Hepsi bu — sunucu yok, kurulum yok.

- Tüm işlem **kendi cihazında** çalışır: fotoğrafların hiçbir sunucuya gitmez.
- Telefonda kamera için HTTPS gerekir (canlı linkten aç ya da kendi hostinginde yayınla).

## ✋ Jestler

| Hareket | Ne yapar |
|---|---|
| 👌 Baş parmak + işaret parmağını kıstır | Fotoğrafı tut |
| 🤏↔️ Tutarken parmak arasını aç/kapat | Büyüt / küçült (telefondaki gibi) |
| 🖐️ Avucunu tamamen aç | Bırak |
| ✋ Açık avuçla süpür | Tüm galeri akar (momentum korunur, yakalayana kadar) |
| 🖐️⬆ Avucu yukarı kaldır | Diziliş değişir (ızgara ↔ serbest) |
| 📁 Fotoğrafı sol yuvaya götürüp beklet | Albüme kaydolur |
| 👆 Parmağı butona getir + kıstır | Havadan buton basma |

## 🔧 Nasıl çalışıyor?

- **El takibi:** MediaPipe Hands — tarayıcı içinde, cihaz üstünde
- **Sesler:** Dosya yok; tüm sesler WebAudio ile anlık sentezlenir
- **Depolama:** IndexedDB — fotoğraflar ve albümler cihazında kalıcı
- **Tek dosya:** Uygulamanın tamamı `index.html`

## 🧑‍🚀 Yapan

**Enes** — ürünlerimi yapay zekâyla inşa ediyorum ve süreci paylaşıyorum:

- Instagram: [@enesa.co](https://instagram.com/enesa.co) · TikTok: [@eneslexi](https://tiktok.com/@eneslexi) · X: [@Eneslexi](https://x.com/Eneslexi)

Fotoğraflar: Wikimedia Commons (CC). Lisans: MIT — istediğin gibi kullan, öğren, değiştir.
