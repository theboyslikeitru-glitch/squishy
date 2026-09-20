<div align="center">

# 🎀 Squishy

**Compress photos, videos, PDFs & files — right in your browser.**

No servers. No sign-ups. No ads. No limits. Just you and your files.

[**🌐 Try it live →**](https://theboyslikeitru-glitch.github.io/squishy/)

---

**Made with 💚 by [Alisa](https://t.me/aliskamalyshkaa) · 2026**

</div>

---

## 🌸 What is Squishy?

**Squishy** is a tiny browser-based compressor with a big heart. Drop in a photo, a video, a PDF, or a whole bag of files — get them back smaller, instantly. Everything runs **100% locally** in your browser using Web APIs. Your files never touch a server, because there is no server.

Built by [**Alisa**](https://t.me/aliskamalyshkaa) — a 20-year-old who loves cute things, cozy vibes, and building tools that respect your privacy. Meet **Yumi**, the chibi helper who squeezes your files alongside you. 🎀

---

## ✨ Features

### 📷 Photos
- Compress **JPG, PNG, WebP, AVIF**
- Choose output format or keep the original
- Automatic transparency detection (PNG without alpha → JPEG for smaller size)
- Quality presets: **Maximum / Balanced / Quality** + fine-tune slider

### 🎬 Videos
- Compress **MP4, MOV, MKV, WebM**
- Multiple output formats (WebM VP9/VP8, MP4 H.264/H.265 — depending on your browser)
- Choose target resolution (up to 1920 px, 1280 px, 854 px, 640 px, or original)
- **Save a frame** as PNG in one click
- Real-time progress in the browser tab title

### 📄 PDFs
- Remove metadata and unused objects
- Typical savings: **5–30%**
- Works entirely offline (after the first load)

### 📦 Any other files
- **Pack multiple files into a ZIP** archive
- **Compress single files with GZIP**
- Smart compression level (automatically scales with file size)
- No memory crashes on large archives

### 🎁 Nice extras
- **Paste from clipboard** — `Ctrl+V` (or the 📋 button)
- **Rename file** before saving (✏️ icon next to filename)
- **Drag & drop** anywhere on the page
- **Statistics dashboard** — files compressed, data saved, favorite format (saved locally)
- **10 languages** with auto-detection: 🇷🇺 🇬🇧 🇺🇦 🇪🇸 🇧🇷 🇩🇪 🇫🇷 🇯🇵 🇨🇳
- **Dark & light themes**
- **PWA-ready** — install it on your phone, works offline
- **Hotkeys** — `Ctrl+O`, `Ctrl+S`, `Ctrl+V`, `Esc`

---

## 🛡️ Privacy first

Unlike most online compressors, Squishy **never uploads your files anywhere**:

| What other services do | What Squishy does |
|---|---|
| Upload your file to their server | Processes it in **your browser** |
| Store it for "analytics" | Nothing is stored anywhere |
| Require registration | No account, no email, no tracking |
| Show ads | No ads, ever |
| Limit file size | No limits from us (browser memory is the only limit) |

Close the tab — and it's like nothing ever happened. Because nothing did.

---

## 🧪 Honest limitations

We love transparency, so here's what to know before you use it:

- **Video compression runs in real time.** A 3-minute video takes about 3 minutes to process. This is a browser limitation, not ours.
- **Video output formats depend on your browser.** Chrome, Edge and Firefox can only produce **WebM**. Safari can produce **MP4**. MOV, AVI and H.265 can't be encoded in most browsers.
- **PDF compression** only removes metadata — images inside the PDF stay as they are.
- **Very large files (1 GB+)** may fail because of the browser's memory limit.
- **ZIP** only shrinks text, code, and CSV. Already-compressed files (JPG, PNG, MP4) won't get smaller — they're already tiny.

---

## 🚀 How to use it

### For users
1. Open **[the live site](https://theboyslikeitru-glitch.github.io/squishy/)**
2. Drag a file onto the page (or paste it with `Ctrl+V`)
3. Adjust quality settings if you want
4. Hit **Compress** → **Download**

That's it. No registration, no cookies, no nonsense.

### For developers (run locally)

```bash
git clone https://github.com/theboyslikeitru-glitch/squishy.git
cd squishy
open index.html
