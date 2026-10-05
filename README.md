<div align="center">

# ⚡ OMARCHY
### *Beautiful, Fun & Agentic Linux by DHH*

[![Astro](https://img.shields.io/badge/Astro-7.3-FF5D01?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build)
[![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Arch Linux](https://img.shields.io/badge/Arch_Linux-Rolling-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)](https://archlinux.org)
[![Hyprland](https://img.shields.io/badge/Hyprland-Wayland-00FFFF?style=for-the-badge&logo=wayland&logoColor=black)](https://hypr.land)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br/>

**Omarchy** is an opinionated, *omakase* Linux distribution designed from the ground up for modern developers, hackers, and creators. Crafted by **David Heinemeier Hansson (DHH)**, Omarchy melds the bleeding-edge speed of **Arch Linux**, the buttery aesthetics of the **Hyprland** Wayland compositor, and a bespoke desktop shell powered by **Quickshell**—with first-class, pre-wired integration for the **autonomous AI agent revolution**.

[Website](https://omarchy.org) • [Manual](https://omarchy.org/manual/) • [Themes](https://omarchy.org/themes/) • [Radio](https://radio.omarchy.org) • [Workstations](https://omarchy.org/workstations/) • [Discord](https://discord.gg/omarchy)

</div>

---

## 📖 Daftar Isi / Table of Contents

- [✨ Mengapa Omarchy? (The Philosophy)](#-mengapa-omarchy-the-philosophy)
- [📜 The 10 Doctrines of Omarchy](#-the-10-doctrines-of-omarchy)
- [🧠 Jeroan & Arsitektur Sistem (The Guts)](#-jeroan--arsitektur-sistem-the-guts)
  - [1. Core OS & Engine](#1-core-os--engine)
  - [2. Window Manager & Compositor: Hyprland](#2-window-manager--compositor-hyprland)
  - [3. Desktop Shell & HUD: Quickshell](#3-desktop-shell--hud-quickshell)
  - [4. Modern Terminal & Shell Workflow](#4-modern-terminal--shell-workflow)
  - [5. The Ultimate TUI Suite](#5-the-ultimate-tui-suite)
- [🤖 Revolusi Agentic Linux (AI-First Experience)](#-revolusi-agentic-linux-ai-first-experience)
- [🎨 22 Curated Desktop Themes](#-22-curated-desktop-themes)
- [📻 Fun, Whimsy & Retro Soul](#-fun-whimsy--retro-soul)
- [💻 Jeroan Repositori Web Ini (Web Platform Stack)](#-jeroan-repositori-web-ini-web-platform-stack)
- [🚀 Quickstart & Instalasi](#-quickstart--instalasi)
- [🛠️ Panduan Pengembangan Lokal (Site Development)](#️-panduan-pengembangan-lokal-site-development)
- [🤝 Kontribusi & Komunitas](#-kontribusi--komunitas)

---

## ✨ Mengapa Omarchy? (The Philosophy)

> *"Because a beautiful system is a motivating system, and productivity has always been downstream from motivation."*  
> — **DHH**

Komputasi modern telah terjebak di antara dua kutub yang menjemukan: sistem operasi komersial yang penuh dengan *telemetry*, iklan tersembunyi, dan *walled-garden*, atau instalasi Linux tradisional yang membutuhkan waktu berhari-hari untuk melakukan *ricing* agar enak dipandang dan siap dipakai kerja.

**Omarchy hadir sebagai antitesis:**
- **Omakase Computing**: Bukan sekadar kumpulan paket acak, melainkan konfigurasi sistem yang dikurasi secara presisi oleh DHH untuk produktivitas maksimal tanpa bloatware.
- **Keyboard-Centric Flow**: Navigasi tuntas dengan shortcut keyboard cerdas, manajemen workspace dinamis, dan kontrol jendela instan.
- **Terminal as an Art Form**: Menghadirkan antarmuka berbasis teks (TUI) yang artistik, responsif, dan elegan.
- **Own Your Machine**: Bebas dari biaya langganan OS, bebas dari gatekeeper korporat, dan 100% kedaulatan atas mesin Anda sendiri.

---

## 📜 The 10 Doctrines of Omarchy

Filosofi Omarchy dirangkum dalam **10 Doktrin** resmi yang menjadi pilar pergerakan ini:

1. **Unite the nerds**  
   Menyatukan para hacker, programmer muda berbakat, hingga veteran UNIX dari ribuan faksi kecil untuk bersama-sama membuktikan bahwa Linux mampu memenangkan desktop.
2. **Hold the line**  
   Mengembalikan etos asli dunia hacker: fokus murni pada kualitas kode, karya, dan dedikasi teknis—menghapus birokrasi dan drama identitas. *Just be nice and sincere.*
3. **Have some fun**  
   Orang serius butuh bersenang-senang secara serius. Omarchy menyematkan easter eggs, screensaver retro, hingga siaran radio lagu parodi di terminal.
4. **Beauty is truth**  
   Alat kerja yang hebat haruslah indah. Setiap sudut radius jendela, garis pembatas TUI, dan palet warna dipoles dengan standar estetika tertinggi.
5. **Heritage is duty**  
   Menghormati sejarah komputasi: dari merilis `vi` 50 tahun setelah Bill Joy menulisnya, hingga tema khusus untuk menghormati John von Neumann.
6. **Command is service**  
   Keunggulan tidak lahir dari rapat komite yang bertele-tele. Omarchy dipimpin dengan visi *benevolent dictatorship* sebagaimana tradisi Linux dan Ruby on Rails.
7. **Welcome the agents**  
   Era AI Agent adalah lompatan paradigma terbesar sejak lahirnya mikroprosesor. Omarchy menyambut agen AI secara terbuka di terminal, issue, PR, dan sistem operasi.
8. **Perfect the computer**  
   Mengejar kesempurnaan tanpa kompromi. Menghilangkan setiap *paper cut*, membuat segala aspek lebih cepat, lebih stabil, dan lebih indah.
9. **Own the machine**  
   Komputer Anda adalah milik Anda sepenuhnya. Tanpa gerbang tol, tanpa pembaruan paksa, dan tanpa lisensi sepihak.
10. **You're somebody now**  
    Omarchy terbuka bagi siapa pun yang ingin belajar, berkontribusi, dan berkreasi.

---

## 🧠 Jeroan & Arsitektur Sistem (The Guts)

Di balik keindahannya, Omarchy ditenagai oleh fondasi teknis tingkat tinggi:

```
┌────────────────────────────────────────────────────────┐
│                      OMARCHY OS                        │
├────────────────────────────────────────────────────────┤
│  HUD & Bar      : Quickshell (QML / Wayland Native)    │
│  Compositor     : Hyprland (Smooth Animations & Tiling)│
│  Shell & Tools  : Fish / Zsh + Starship + Mise         │
│  Terminal       : Ghostty / Alacritty (GPU Accelerated)│
│  TUI Engine     : Neovim, Lazygit, Yazi, Btop, Spotify │
│  Agent Layer    : Claude, Codex, AGY, Grok, OpenCode   │
│  Base OS        : Arch Linux (Rolling, Pacman, Systemd)│
└────────────────────────────────────────────────────────┘
```

### 1. Core OS & Engine
- **Arch Linux Base**: Selalu mutakhir dengan model *rolling-release*, akses instan ke kernel Linux terkini, serta ribuan paket terpercaya melalui `pacman` dan AUR (*Arch User Repository*).
- **Automated Snapshots**: Dilengkapi sistem snapshot otomatis berbasis Btrfs / Timeshift sehingga sistem dapat di-*rollback* dalam hitungan detik jika terjadi kegagalan sistem.

### 2. Window Manager & Compositor: Hyprland
- **Wayland Native**: Performa bebas *screen-tearing*, konsumsi daya hemat, dan dukungan multi-monitor dengan refresh rate tinggi (144Hz+).
- **Fluid Physics & Animations**: Gerakan perpindahan jendela dan *workspace switching* yang halus dengan akselerasi perangkat keras.
- **Intelligent Auto-Tiling**: Penempatan jendela otomatis dengan layout master/dwindle yang dapat diatur sesuka hati.

### 3. Desktop Shell & HUD: Quickshell
- **Bespoke Top Bar**: Status bar elegan menampilkan resource monitor, jam dunia, koneksi jaringan, dan kontrol audio.
- **Unified Clipboard History**: Pengelola riwayat *clipboard* instan yang mendukung teks dan gambar (`Super + V`).
- **Interactive Control Center**: Pengaturan cepat untuk Wi-Fi, Bluetooth, Dark/Light mode, dan audio sink langsung dari desktop.
- **Screenshots & Instant OCR**: Tangkapan layar presisi dan ekstraksi teks instan (*optical character recognition*) dari layar langsung ke clipboard.

### 4. Modern Terminal & Shell Workflow
- **Terminal Emulator**: Menggunakan **Ghostty** atau **Alacritty** dengan akselerasi GPU, rendering font subpixel tajam, dan latensi input ultra-rendah.
- **Mise Toolchain Manager**: Manajemen versi runtime (Node, Ruby, Python, Go, Rust) terisolasi dan instan via [mise](https://mise.jdx.dev/).
- **Modern CLI Suite**:
  - `bat` — Pengganti `cat` dengan syntax highlighting dan git integration.
  - `eza` — Pengganti `ls` modern dengan icon, metadata, dan tree view.
  - `ripgrep` (`rg`) — Mesin pencari string secepat kilat.
  - `fd` — Alternatif cepat dan ramah pengguna untuk perintah `find`.
  - `fzf` & `zoxide` — Navigasi direktori fuzzy-jump kilat.

### 5. The Ultimate TUI Suite
Omarchy membuktikan bahwa antarmuka terminal tidak harus membosankan:
- **Neovim (btw)**: Konfigurasi artisanal out-of-the-box lengkap dengan Treesitter, LSP (*Language Server Protocol*), Mason package manager, fuzzy telescope, dan keymaps ergonomis.
- **Lazygit**: Manajemen Git visual di terminal—staging baris per baris, visual commit graph, dan merge conflict resolver.
- **Yazi**: File manager TUI asinkron secepat kilat yang mendukung preview gambar langsung di terminal via Kitty/Sixel graphics protocol.
- **Btop**: Monitor sumber daya CPU, memori, disk, jaringan, dan proses dengan grafik visual interaktif.
- **Lazydocker**: Monitoring kontainer Docker, log streaming, dan manajemen image dalam satu tampilan terpadu.

---

## 🤖 Revolusi Agentic Linux (AI-First Experience)

Omarchy adalah distribusi Linux pertama di dunia yang memperlakukan **AI Coding Agents** sebagai warga negara kelas satu (*first-class citizens*). 

Alih-alih memaksa Anda memakai satu model tertentu, Omarchy menyediakan ekosistem **lazy-loaded launcher** yang dikelola via `mise`: tidak membebani penyimpanan Anda sampai pertama kali Anda memanggilnya.

| Perintah Terminal | AI Coding Agent | Sumber / Pembuat |
|:---|:---|:---|
| `claude` | **Claude Code** | Anthropic |
| `codex` | **OpenAI Codex** | OpenAI |
| `agy` | **Google Antigravity CLI** | Google DeepMind |
| `opencode` | **OpenCode** | OpenCode Community |
| `copilot` | **GitHub Copilot CLI** | GitHub / Microsoft |
| `grok` | **Grok Build** | xAI |
| `crush` | **Crush** | Charmbracelet |
| `cursor-agent` | **Cursor CLI** | Anysphere / Cursor |
| `ori` | **Ori Harness** | OpenRouter (Jalankan agen apa pun di seluruh model catalog) |
| `hermes` | **Hermes Desktop** | Nous Research |
| `muse` | **Muse Code** | Meta AI |
| `pi` / `omp` | **Pi & Oh My Pi** | Mario Zechner / Open Source |

### Fitur AI Unggulan:
- **Default Agent Selector**: Atur agen utama Anda dengan perintah `omarchy default agent <name>` atau melalui menu `Super + Space`.
- **Terminal Piping**: Kirimkan output error kompilasi atau log secara instan ke agent:  
  `cargo build 2>&1 | claude -p "Perbaiki bug kompilasi ini"`
- **Zero Configuration**: Autentikasi otomatis tersimpan aman di secure keyring sistem.

---

## 🎨 22 Curated Desktop Themes

Omarchy menyertakan **22 tema visual terkurasi** yang menyelaraskan warna di seluruh lapisan desktop secara simultan—mulai dari bar Quickshell, terminal, Neovim, wallpaper, hingga dekorasi jendela:

<div align="center">

| | | |
|:---:|:---:|:---:|
| 🌌 **Tokyo Night** | ❄️ **Nord** | 🌲 **Everforest** |
| ☕ **Gruvbox** | 🌸 **Catppuccin Mocha** | 🌷 **Rose Pine** |
| 🧛 **Dracula** | ☀️ **Solarized Dark** | 🌊 **Kanagawa** |
| 🏛️ **Giants (von Neumann)** | 🏙️ **Cyberpunk** | 🍂 **Ayu Dark** |

*(...dan 10 tema artisanal lainnya!)*

</div>

Ganti tema secara instan tanpa perlu reboot hanya dengan satu shortcut atau ketik:
```bash
omarchy theme set tokyo-night
```

---

## 📻 Fun, Whimsy & Retro Soul

Omarchy memegang teguh doktrin **"Have Some Fun"**:
- **Radio Omarchy**: Pemutar audio terintegrasi yang menyiarkan lagu-lagu parodi coding dan alunan Lo-Fi retro ([radio.omarchy.org](https://radio.omarchy.org)).
- **Winamp Nostalgia**: Pemutar musik bergaya Winamp klasik dengan visualizer retro.
- **Built-in Screensavers**: Screensaver pipes, starfield, dan matrix ASCII yang hidup otomatis saat sistem idle.
- **Hacker Easter Eggs**: Temukan berbagai kejutan rahasia yang tersembunyi di dalam terminal CLI!

---

## 💻 Jeroan Repositori Web Ini (Web Platform Stack)

Repositori ini berisikan portal web resmi **omarchy.org** yang menampilkan seluruh dokumentasi, manual interaktif, showcase tema, peta meetup global, dan instalasi:

- **Framework**: [Astro 7.3](https://astro.build) (High-performance Content-driven Island Architecture)
- **UI Components**: [React 19](https://react.dev) + [@base-ui/react](https://base-ui.com) & [Shadcn UI](https://ui.shadcn.com)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com) (dengan engine `@tailwindcss/vite` super cepat)
- **Animations**: [Motion 13](https://motion.dev) (sebelumnya Framer Motion)
- **Data & Geography**: [D3 Geo](https://d3js.org/d3-geo) & TopoJSON untuk interactive global meetup maps
- **Deployment & Edge**: Cloudflare Workers via Wrangler & GitHub Pages
- **Internationalization (i18n)**: Sistem lokalisasi 32 bahasa dengan pipeline translasi terotomatisasi

---

## 🚀 Quickstart & Instalasi

### ⚡ Pasang Omarchy di Mesin Anda
Untuk menginstal Omarchy pada mesin Arch Linux baru (bare-metal atau VM):

```bash
eval "$(curl -fsSL https://omarchy.org/install)"
```

*Installer akan memandu partisi disk, menyiapkan driver grafis, mengonfigurasi Hyprland, mengunduh dotfiles, dan menyiapkan lingkungan AI agent secara otomatis.*

---

## 🛠️ Panduan Pengembangan Lokal (Site Development)

Ingin menjalankan atau mengedit portal web ini di komputer Anda?

### Prasyarat
- **Node.js** >= 24.0.0
- **Python** >= 3.13

### Langkah Menjalankan:
```bash
# 1. Kloning repositori ini
git clone https://github.com/vmubyt/omarchy.git
cd omarchy

# 2. Pasang dependensi
npm install

# 3. Jalankan development server Astro
npm run dev
```

Buka peramban Anda di `http://localhost:3113` untuk melihat tampilan web secara langsung!

### Perintah Bermanfaat Lainnya:
```bash
npm run build      # Melakukan kompilasi static site ke dist/client
npm run preview    # Meninjau hasil build lokal
npm run lint       # Menjalankan ESLint
npm run format     # Merapikan kode dengan Prettier & ESLint
npm run typecheck  # Memeriksa tipe TypeScript
npm run test       # Menjalankan unit test
```

---

## 🤝 Kontribusi & Komunitas

Ingin menambahkan tema karya Anda atau melengkapi manual?
1. **Submit Tema**: Kirimkan tangkapan layar 16:9 berukuran 1200x675 di `assets/themes/` dan daftarkan di `themes/index.html`.
2. **Terjemahan**: Bantu melokalisasi halaman ke dalam bahasa Anda melalui panduan di [docs/translations.md](docs/translations.md).
3. **Pamerkan Workstation**: Daftarkan *battlestation* Omarchy Anda untuk tampil di galeri resmi!

---

<div align="center">

Dibuat dengan ❤️ dan dedikasi tinggi untuk komunitas open-source dunia.  
**Long Live Linux on the Desktop.**

</div>
