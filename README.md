[🇪🇸 Español](README.es.md)

<div align="center">
  <br/>

# Chidaruma

**錬金 · Alchemist of code.**

<br/>

*Independent and custom software development · Android · Linux · Latin America*

<br/>

[![Kotlin](https://img.shields.io/badge/kotlin-7f52ff?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/compose-4285f4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/compose)
[![Rust](https://img.shields.io/badge/rust-b7410e?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![TypeScript](https://img.shields.io/badge/typescript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Python](https://img.shields.io/badge/python-3776ab?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PHP](https://img.shields.io/badge/php-777bb4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![SQLite](https://img.shields.io/badge/sqlite-003b57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Arch Linux](https://img.shields.io/badge/arch%20linux-1793d1?style=for-the-badge&logo=archlinux&logoColor=white)](https://archlinux.org/)
[![XFCE](https://img.shields.io/badge/xfce-2284f2?style=for-the-badge&logo=xfce&logoColor=white)](https://xfce.org/)

</div>

---

I build software from Latin America on two fronts: custom systems for businesses that need to run their daily operations, and open-source projects born whenever the tool I want does not exist yet. Everything I publish here shares the same principles: code that can be read, documentation that can be followed, and applications that ship without ads, trackers or unnecessary dependencies.

<br/>

## ⚗️ Areas of work

| 🧭 Own projects | 🧾 Custom development |
| --- | --- |
| Open-source Android applications for Latin America: anime and manga with the sources compiled into the APK, with no external extensions or intermediary stores | Business management systems: points of sale, inventories and ERP, with verified business rules and immutable audit logs |
| Browser tools that work without a server: document generation, hardware integration through Web Serial | Corporate sites and portfolios in Next.js, with multilingual support and static deployment |
| Small, well-tested libraries for JavaScript and Python, ready to be published as packages | Process automation with Python, PHP and n8n: integration between services, data processing and internal tasks |
| Themes and desktop environments for Linux, with multi-distribution installers | Technical documentation written so the project can be maintained without depending on its author |

<br/>

## 📦 Published projects

| | Project | Description | Technology |
| --- | --- | --- | --- |
| 📺 | [**Watanuki**](https://github.com/Chidaruma696/Watanuki) | Anime viewer for Latin America: 59 Spanish-language sources compiled into the APK, libVLC player, parallel downloads and ten Touhou-inspired palettes | Kotlin · Compose · libVLC |
| 📖 | [**Yuko**](https://github.com/Chidaruma696/Yuko) | Manga reader, Watanuki's master: compiled Kotatsu parsers, chapters completed across sources and a right-to-left reader fitted to the page height | Kotlin · Compose |
| 📄 | [**Fumito**](https://github.com/Chidaruma696/Fumito) | Résumé generator built from GitHub repositories: a static page with no server and no artificial intelligence, three templates, export to PDF and Markdown · [demo](https://chidaruma696.github.io/Fumito/) | JavaScript · GitHub Pages |
| 🏪 | [**ToyPOS**](https://github.com/Chidaruma696/ToyPOS) | Core of a multi-branch point of sale: pure domain, local-first SQLite, scoped permissions, immutable audit log and end-to-end integer arithmetic | Rust · sqlx · OpenSpec |
| ⛩️ | [**Reimu**](https://github.com/Chidaruma696/Reimu) · *experimental* | Arch Linux installer in Bash: asks the right questions (filesystem, swap, encryption, bootloader, desktop) and finishes the job in one pass: LUKS2, btrfs snapshots, systemd-boot or GRUB, drivers, AUR, software bundles, replayable config files | Bash · Arch ISO |
| 🌿 | [**Sanae**](https://github.com/Chidaruma696/Sanae) · *experimental* | A software store for Arch Linux that lives in the terminal: shelves from AppStream with human names and popularity, repositories and AUR in one search, updates with the Arch news, a queue with preflight, and recipes that install and configure (Docker, QEMU, fonts, XFCE themes). Reimu offers to install it at the end | Rust · ratatui · pacman |
| 🧟 | [**Win2k Undead**](https://github.com/Chidaruma696/Win2k_undead) | The Windows 2000 desktop recreated for XFCE 4.18 and 4.20, with a native installer for Arch, Debian, Ubuntu, Fedora, Void and openSUSE | Bash · GTK · xfconf |
| ⚖️ | [**Kana**](https://github.com/Chidaruma696/Kana) | Torrey scales from the browser over Web Serial: polling, parser with stability flags, stabilizer tested at the counter, automatic reconnection and a simulator | JavaScript · npm |
| 🏷️ | [**Tohru**](https://github.com/Chidaruma696/Tohru) | Scale barcodes for Python: EAN-13, per-package identity, embedded weight and tolerance for readers that truncate digits | Python · pip |
| 🌐 | [**azazel-dev**](https://github.com/Chidaruma696/azazel-dev) | Portfolio site in four languages with animations, the studio's public presence | Next.js 15 · Tailwind v4 |

<br/>

## 🛠️ How I work

- **Architecture before speed.** Every application starts from a clear domain, separated from the interface; business rules are tested on their own, with no database or screen in between.
- **Local-first.** The systems I build work offline and synchronize when they can. An internet outage should never stop a register or a warehouse.
- **Minimal, auditable dependencies.** I would rather compile a source into the project than install a package I do not control. Whatever is included is understood.
- **Documentation as part of the product.** A README should let you install, understand and maintain the project in one sitting. If you have to ask the author, the documentation is incomplete.
- **Consistent visual identity.** A design system of my own, inspired by the manga page, with Touhou palettes in light and dark mode, shared across all applications.
- **Clear licenses.** Everything I publish carries an open license (Apache 2.0 or MIT) and explicit credit to the projects it depends on.

<br/>

## 🎌 Principles

- **Latin America first.** The anime and manga applications exist because the legal offering in the region arrives late or does not arrive at all. The day it does, they will stop being necessary, and that will be good news.
- **Open Android.** Everything I publish depends on each person being able to install whatever they choose on their own phone. I support the [Keep Android Open](https://keepandroidopen.org/) initiative.
- **No noise.** No project includes ads, tracking or packages that alter the system. It installs clean and uninstalls clean.
- **Anime, manga, Touhou and Linux.** They are the origin of most of these projects and of their aesthetics.

<br/>

## ✉️ Contact

Professional inquiries and work proposals: **jp@azazel.dev**

<br/>

<div align="center">

錬金 · れんきん

</div>
