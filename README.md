<div align="center">

![SteamToolsApp GameList & Manifest Hub](og-home.png)

# 🎮 SteamToolsApp GameList & Manifest Directory

**Official curated Steam games database, metadata catalog, and instant manifest generator for SteamTools (Watt Toolkit).**

[![Official Website](https://img.shields.io/badge/Website-steamtoolsapp.com-00d2ff?style=for-the-badge&logo=google-chrome&logoColor=white)](https://steamtoolsapp.com)
[![Curated Games](https://img.shields.io/badge/Catalog-99%2B%20Curated%20Games-10b981?style=for-the-badge&logo=steam)](https://steamtoolsapp.com/games)
[![Client Download](https://img.shields.io/badge/Client-Win%20%7C%20Mac%20%7C%20Linux-8b5cf6?style=for-the-badge&logo=windows)](https://steamtoolsapp.com/download)
[![License](https://img.shields.io/badge/License-MIT-amber?style=for-the-badge)](LICENSE)

<p align="center">
  <a href="https://steamtoolsapp.com">🌐 Web Generator</a> •
  <a href="https://steamtoolsapp.com/games">🎮 99+ Games Catalog</a> •
  <a href="https://steamtoolsapp.com/download">💻 Desktop Client</a> •
  <a href="https://steamtoolsapp.com/how-to-use">📖 Tutorial</a> •
  <a href="https://steamtoolsapp.com/faq">❓ FAQ</a>
</p>

</div>

---

### 🌐 Read this in your language:
**[English](README.md)** | **[简体中文](README_zh.md)** | **[Русский](README_ru.md)** | **[Türkçe](README_tr.md)** | **[Español](README_es.md)** | **[Français](README_fr.md)** | **[Português (Brasil)](README_pt-BR.md)**

---

## 📖 Overview

**GameList** is the canonical Steam game metadata repository powering **[SteamToolsApp.com](https://steamtoolsapp.com)**. It contains structured game indexes (`games.json`), Steam AppIDs, cover assets, and localized metadata.

Pairing with **[ManifestHub](https://github.com/steamtoolsapp/ManifestHub)**, it enables one-click generation of verified `.lua` hook scripts, `key.vdf` depot keys, and full game manifest archives in seconds.

---

## 🌟 Quick Links

* 🌐 **Live Web Generator**: [https://steamtoolsapp.com](https://steamtoolsapp.com)
* 🎮 **Curated 99+ Games Catalog**: [https://steamtoolsapp.com/games](https://steamtoolsapp.com/games)
* 💻 **Client Setup (Windows / macOS / Linux)**: [https://steamtoolsapp.com/download](https://steamtoolsapp.com/download)
* 📖 **How It Works & Setup Guide**: [https://steamtoolsapp.com/how-to-use](https://steamtoolsapp.com/how-to-use)
* ❓ **Frequently Asked Questions**: [https://steamtoolsapp.com/faq](https://steamtoolsapp.com/faq)

---

## 🚀 How to Use

1. **Find your Game**: Search by game title or Steam App ID on **[SteamToolsApp.com](https://steamtoolsapp.com)**.
2. **Download Package**: Click **Download ZIP Package** to get `{appId}_public.lua`, `key.vdf`, and setup guide.
3. **Place Files**: Copy `.lua` and `key.vdf` into your SteamTools installation root directory.
4. **Restart & Play**: Launch SteamTools / Steam — your game manifests will synchronize immediately.

---

## 🔥 Featured Popular Games (Quick Downloads)

| App ID | Game Name | Direct Manifest Link |
| :--- | :--- | :--- |
| `2358720` | **Black Myth: Wukong (黑神话：悟空)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/2358720) |
| `1245620` | **ELDEN RING (艾尔登法环)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/1245620) |
| `271590` | **Grand Theft Auto V (GTA 5)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/271590) |
| `730` | **Counter-Strike 2 (CS2)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/730) |
| `1623730` | **Palworld (幻兽帕鲁)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/1623730) |
| `1091500` | **Cyberpunk 2077 (赛博朋克 2077)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/1091500) |
| `1174180` | **Red Dead Redemption 2 (荒野大镖客 2)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/1174180) |
| `105600` | **Terraria (泰拉瑞亚)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/105600) |
| `413150` | **Stardew Valley (星露谷物语)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/413150) |
| `892970` | **Valheim (英灵神殿)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/892970) |
| `400` | **Portal (传送门)** | [Download Manifest & Lua](https://steamtoolsapp.com/app/400) |

👉 **[Browse Full 99+ Games Catalog on SteamToolsApp.com →](https://steamtoolsapp.com/games)**

---

## 🔌 Free REST API & Automation

Query game metadata and generate manifest packages programmatically with no authentication required:

### 1. Search Games Catalog
```bash
curl -s "https://steamtoolsapp.com/api/search?q=wukong" | jq
```

### 2. Generate Manifest Package
```bash
curl -s "https://steamtoolsapp.com/api/generate?appId=2358720" | jq
```

---

## 🛡️ Security & Privacy

- **100% Virus-Free**: All manifests and binary packages are verified against cryptographic SHA-256 signatures.
- **Zero Account Credentials Required**: No Steam login, passwords, or personal credentials are ever requested.

---

## 📄 License

MIT License © 2026 [SteamToolsApp.com](https://steamtoolsapp.com)
