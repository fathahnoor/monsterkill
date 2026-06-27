# ⚔️ MONSTERKILL: Dota 2 Item Browser

<div align="center">

![MONSTERKILL Banner](https://img.shields.io/badge/DOTA%202-Item%20Browser-f7931e?style=for-the-badge&logo=valve&logoColor=white)
![Patch](https://img.shields.io/badge/Patch-7.41d-f5c542?style=for-the-badge)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-4fc3a1?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-brightgreen?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-blueviolet?style=for-the-badge)

**_Learn Smart. Win Hard._**

[🌐 Web](https://fathahnoor.github.io/monsterkill) · [🐛 Report Bug](../../issues/new?labels=bug) · [💡 Request Feature](../../issues/new?labels=enhancement) · [🤝 Contribute](#-contributing)

</div>

---

## 🎮 Apa Itu MONSTERKILL?

Pernah nggak lagi **draft phase**, panik mikir _"item apa yang bisa counter Spectre?"_ atau _"item mana yang kasih lifesteal tertinggi?"_ dan kamu harus buka 5 tab berbeda buat nemuin jawabannya?

**MONSTERKILL** adalah browser item Dota 2 yang ringan, cepat, dan bisa jalan **langsung di browser tanpa install apapun**. Semua data item patch **7.41d** ada di sini, bisa kamu filter, sort, dan bandingkan dalam hitungan detik.

> No ads. No login. No backend. Pure Dota knowledge. ⚡

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
|---|---|
| 🔍 **Smart Search** | Cari item by nama secara real-time |
| 🏷️ **Filter by Effect** | Filter berdasarkan tag: lifesteal, evasion, slow, invisibility, dll |
| 💰 **Cost Range Filter** | Filter item berdasarkan rentang harga gold |
| 📊 **Multi-Sort** | Sort by damage, armor, mana, move speed, attack speed, dan banyak lagi |
| 📋 **Detail Panel** | Klik item, lihat semua stats, tags, dan deskripsi lengkap |
| 📱 **Fully Responsive** | Nyaman di desktop, tablet, maupun mobile |
| ⚡ **Zero Dependencies** | Satu file HTML, tidak butuh Node.js, server, atau framework apapun |

---

## 🚀 Cara Pakai

### Option 1: Buka via Web (Paling Gampang)
Kunjungi langsung: **[fathahnoor.github.io/monsterkill](https://fathahnoor.github.io/monsterkill)**

### Option 2: Download & Buka Lokal
Download file `index.html`, lalu buka di browser. Selesai. Tidak ada proses install.

### Option 3: Clone & Run
```bash
git clone https://github.com/fathahnoor/monsterkill.git
cd monsterkill
```
Lalu buka `index.html` di browser favorit kamu.

### Option 4: Windows Batch Server (Local Dev)
```bash
# Double-click run.bat atau jalankan di terminal:
run.bat
```
Script ini akan menjalankan local server sederhana agar kamu bisa develop dengan lebih nyaman.

---

## 🗺️ Preview Layout

```
┌──────────────────┬──────────────────────┬───────────────────────┐
│  🔍 SEARCH       │  📦 ITEM LIST         │  📋 ITEM DETAIL       │
│                  │                      │                       │
│  Filter Effect:  │  Black King Bar      │  Black King Bar       │
│  ☑ damage        │  ─────────────       │  Cost: 4050g          │
│  ☑ magic_resist  │  Butterfly           │                       │
│  ☐ lifesteal     │  ─────────────       │  Damage:    +24       │
│                  │  Heart of Tarrasque  │  Str:       +10       │
│  Cost Range:     │  ─────────────       │  Active: Avatar       │
│  Min: 3000       │  Linken's Sphere     │  (Magic Immunity)     │
│  Max: 5000       │  ─────────────       │                       │
│                  │  ...                 │  Tags: magic_resist   │
│  Sort: Cost ↓    │                      │        strength       │
└──────────────────┴──────────────────────┴───────────────────────┘
```

---

## 🧠 Untuk Siapa Tool Ini?

- 🆕 **Pemain Baru**: masih belajar fungsi tiap item
- 📈 **Player Climbing MMR**: butuh referensi cepat pas draft atau laning
- 🎓 **Coach & Analyst**: research item build untuk spesifik hero/situasi
- 🛠️ **Developer**: yang mau extend tool ini jadi sesuatu yang lebih keren

---

## 🛠️ Tech Stack

```
📁 monsterkill/
├── index.html     <- Seluruh app (HTML + CSS + JS in one file)
└── run.bat        <- Local server launcher (Windows)
```

- **Pure Vanilla HTML/CSS/JS**: no React, no Vue, no bundler
- **Embedded Item Database**: data patch 7.41d sudah hardcoded di JS
- **CSS Grid + Flexbox**: responsive layout tanpa library
- **Zero External Dependencies**: bisa jalan offline sepenuhnya

---

## 🤝 Contributing

**Ini adalah proyek komunitas. Kamu bisa bantu bikin ini jadi tool terbaik untuk player Dota 2 Indonesia (dan dunia)!**

### 💡 Ada ide fitur keren? Request di sini!

👉 [**Buka Feature Request Issue**](../../issues/new?labels=enhancement)

Beberapa ide yang **sangat dibutuhkan** dan belum ada. Siapa yang mau mulai?

- [ ] 🦸 **Hero Builder**: simulasi item build per hero + total stats
- [ ] ⚔️ **Item Comparison Mode**: compare 2 item side by side
- [ ] 🔄 **Build Path Viewer**: lihat komponen penyusun item (recipe tree)
- [ ] 🌙 **Item Recommender**: suggest item berdasarkan hero + situasi game
- [ ] 📊 **Stats Chart**: visualisasi bar chart perbandingan stat item
- [ ] 🌐 **Multi-Language**: support Bahasa Indonesia & bahasa lainnya
- [ ] 🔔 **Patch Tracker**: highlight item yang berubah tiap patch baru
- [ ] 🎯 **Counter-Item Finder**: cari item yang counter hero X
- [ ] ⏰ **Patch Auto-Update**: data item update otomatis saat patch baru rilis

### 🐛 Nemu Bug atau Data Item yang Salah?

👉 [**Laporkan di sini**](../../issues/new?labels=bug)

### 👨‍💻 Cara Kontribusi Kode

1. **Fork** repo ini
2. **Buat branch** baru: `git checkout -b feature/nama-fiturmu`
3. **Commit** perubahanmu: `git commit -m 'feat: tambah fitur XYZ'`
4. **Push** ke branch: `git push origin feature/nama-fiturmu`
5. **Buka Pull Request**: describe apa yang kamu tambahkan dan kenapa

### ✅ Guidelines Kontribusi

- Pertahankan pendekatan **zero-dependency** (vanilla JS/HTML/CSS only, kecuali ada alasan kuat)
- Data item harus akurat sesuai patch terbaru Dota 2
- Kode harus readable, tambahkan komentar singkat jika logika kompleks
- Test di Chrome, Firefox, dan mobile browser sebelum submit PR
- Commit message mengikuti format: `feat:`, `fix:`, `data:`, `docs:`

---

## 📋 Issue Labels

Saat membuka issue, gunakan label yang sesuai agar lebih mudah dikelola:

| Label | Kapan Digunakan |
|---|---|
| `bug` | Sesuatu yang tidak berjalan sesuai harapan |
| `enhancement` | Request fitur baru |
| `data` | Item data yang salah atau kurang akurat |
| `patch-update` | Update data ke patch Dota 2 terbaru |
| `good first issue` | Cocok untuk kontributor pertama kali |
| `help wanted` | Butuh bantuan dari komunitas |

---

## 🗺️ Roadmap

- [x] Item browser dasar (search, filter by effect, sort, detail panel)
- [x] Responsive mobile layout
- [x] Data lengkap patch 7.41d (consumables, attributes, weapons, armor, dll)
- [ ] Update data ke patch terbaru
- [ ] Hero item build database
- [ ] Item comparison mode
- [ ] Build path / recipe tree viewer
- [ ] Bahasa Indonesia support
- [ ] PWA (Progressive Web App) untuk offline access
- [ ] Dark/Light theme toggle

---

## 📜 License

Proyek ini open source di bawah lisensi **[MIT](LICENSE)**.
Data item Dota 2 adalah milik © Valve Corporation, digunakan untuk keperluan edukasi dan komunitas non-komersial.

---

## 🙏 Kredit & Dukungan

Dibuat dengan ❤️ oleh **[@fathahnoor](https://github.com/fathahnoor)** untuk komunitas Dota 2.

Kalau tool ini membantu kamu menang game atau naik MMR, **kasih ⭐ star** di repo ini!
Itu adalah motivasi terbesar untuk terus update dan ngembangkan fitur baru.

```
                   GG WP! 🎮
        "The battle is won before it's fought."
              -- Sun Tzu (dan Ancient kamu)
```

<div align="center">

[![Star this repo](https://img.shields.io/github/stars/fathahnoor/monsterkill?style=social)](../../stargazers)
[![Fork this repo](https://img.shields.io/github/forks/fathahnoor/monsterkill?style=social)](../../network/members)
[![Open Issues](https://img.shields.io/github/issues/fathahnoor/monsterkill?color=f7931e)](../../issues)

**⭐ Star · 🍴 Fork · 💬 Open Issue · 🤝 Pull Request**

</div>
