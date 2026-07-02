# AiNbox — AI Assistant App
**by DoNat** · Powered by Google Gemini (Gratis)

## Fitur
- 💬 Chat AI dengan Gemini
- 🔍 Web Search AI
- 📄 Baca & Analisis Dokumen (PDF, foto)
- 📱 UI mirip uNbox — biru navy, pill buttons

---

## Cara Build .IPA (Gratis via GitHub Actions)

### Langkah 1 — Upload ke GitHub
1. Buat akun di **github.com** (gratis)
2. Klik **New Repository** → nama: `ainbox`
3. Upload semua file project ini
4. Pastikan struktur:
```
ainbox/
├── src/
│   └── index.html
├── .github/
│   └── workflows/
│       └── build-ios.yml
├── package.json
├── capacitor.config.json
└── vite.config.js
```

### Langkah 2 — Jalankan Build
1. Masuk ke tab **Actions** di GitHub
2. Klik **Build IPA (AiNbox)**
3. Klik **Run workflow** → **Run workflow**
4. Tunggu ±10-15 menit

### Langkah 3 — Download .IPA
1. Setelah selesai (✅), klik nama workflow
2. Scroll ke bawah → **Artifacts**
3. Download **AiNbox-IPA**
4. Extract → dapat file `AiNbox.ipa`

### Langkah 4 — Install ke iPhone (Jailbreak)
Karena iPhone sudah jailbreak, install via:

**Opsi A — Filza File Manager:**
1. Transfer `AiNbox.ipa` ke iPhone via iTunes/iMazing
2. Buka Filza → cari file .ipa
3. Tap → Install

**Opsi B — AppSync + iGameGuardian:**
```
Cydia → cari "AppSync Unified" → install
```
Lalu install .ipa via AFC2 atau Filza

**Opsi C — Sideloadly (PC Windows):**
1. Download Sideloadly dari sideloadly.io
2. Hubungkan iPhone via USB
3. Drag & drop AiNbox.ipa ke Sideloadly
4. Login Apple ID gratis
5. Klik Start

---

## Setup API Key Gemini (Gratis)
1. Buka **aistudio.google.com**
2. Login dengan Google
3. Klik **Get API key** → **Create API key**
4. Copy key (dimulai dengan `AIza...`)
5. Paste di app AiNbox saat pertama buka

---

## Teknologi
- **UI**: HTML + CSS + Vanilla JS (kompatibel iOS 12+)
- **Framework**: Ionic Capacitor 6
- **AI**: Google Gemini API (gratis)
- **Build**: GitHub Actions (macOS runner gratis)
