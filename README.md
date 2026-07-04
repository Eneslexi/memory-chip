# AIRCHIP 🖐️

**English** | [Türkçe](README.tr.md)

**Browse your photos like you're inside a sci-fi movie — with nothing but your hands.**

Your camera tracks 21 joints of your hand in real time. Grab photos with a pinch,
zoom them like you would on a phone screen, sweep the whole gallery through the air,
and file memories into albums — no mouse, no touchscreen.

> I didn't write a single line of this by hand — I described it to [Claude Code](https://claude.com/claude-code) and it built the whole thing.

🌐 **Live demo:** https://eneslexi.github.io/memory-chip/

## 🚀 Run it

**Easiest:** download `index.html`, open it in Chrome, allow camera access. That's it — no server, no install.

- Everything runs **on your device**: your photos never leave it, nothing is uploaded anywhere.
- On phones the camera requires HTTPS — use the live demo link or host it yourself.

## ✋ Gestures

| Gesture | What it does |
|---|---|
| 👌 Pinch thumb + index finger | Grab a photo |
| 🤏↔️ Spread / close fingers while holding | Zoom in / out (just like on a phone) |
| 🖐️ Open your hand fully | Release |
| ✋ Move your hand around | The whole gallery flows with you, with depth parallax |
| 🖐️⬆ Raise an open palm to the top | Toggle layout (grid ↔ scattered) |
| 📁 Hold a photo over a slot | It gets absorbed into that album |
| 👆 Point at a button + pinch | Press buttons in mid-air |

## 🔧 How it works

- **Hand tracking:** MediaPipe Hands — in-browser, on-device
- **Sound:** zero audio files; every sound is synthesized live with WebAudio
- **Storage:** IndexedDB — photos and albums persist on your device
- **Single file:** the entire app is one `index.html`

## 🧑‍🚀 Author

**Enes** — I build products with AI and share the whole journey:

- X: [@Eneslexi](https://x.com/Eneslexi) · Instagram: [@enesa.co](https://instagram.com/enesa.co) · TikTok: [@eneslexi](https://tiktok.com/@eneslexi)

Demo photos: Wikimedia Commons (CC). License: MIT — use it, learn from it, remix it.
