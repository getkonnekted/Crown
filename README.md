<div align="center">

# 👑 CROWN

### Your taste. Your picks. Your restaurant crown.

**A Lagos-first restaurant discovery companion — crown your favourites, build your personal court, and share your taste.**

<br />

![PWA](https://img.shields.io/badge/PWA-installable-255B45?style=for-the-badge&logo=pwa)
![Status](https://img.shields.io/badge/status-MVP-CCF36B?style=for-the-badge&labelColor=18251D)
![Focus](https://img.shields.io/badge/launch-market-Lagos-F28C45?style=for-the-badge&labelColor=18251D)
![License](https://img.shields.io/badge/license-not%20specified-lightgrey?style=for-the-badge)

<br />

**[🚀 Open Crown](https://crown-ivory-phi.vercel.app) · [🧑‍💻 Explore the repository](https://github.com/getkonnekted/Crown)**

</div>

---

## ✳️ The idea

Choosing where to eat shouldn't mean starting from zero every time.

**Crown** is a mobile-first progressive web app prototype for keeping a personal shortlist of favourite restaurants. Crown one pick per cuisine, revisit your choices, and share them with people who trust your taste.

> **The product principle:** your personal recommendations first; broader discovery can come next.

## 🟩 What works in this MVP

| Feature | What it does |
| --- | --- |
| 🔎 **Find a restaurant** | Search sample listings by name, cuisine, or neighbourhood. |
| 👑 **Crown a favourite** | Keep one crowned restaurant per cuisine; choosing another replaces the previous pick. |
| 💾 **Keep your court** | Your selections persist in this browser using local storage. |
| 📤 **Share your taste** | Share your court or a crowned restaurant, with a clipboard fallback. |
| 🗺️ **Continue in Maps** | Open a restaurant search in Google Maps. |
| 📱 **Installable shell** | A basic PWA manifest and service worker support installation on compatible browsers. |

## 🎨 Product feel

<div align="center">

| 🌲 Deep green | 🍋 Crown lime | 🥛 Warm cream | 🍊 Citrus |
|:---:|:---:|:---:|:---:|
| `#255B45` | `#CCF36B` | `#F7F4EA` | `#F28C45` |

*An editorial, food-forward visual direction built to feel at home on mobile.*

</div>

## ⚙️ Run locally

You only need a browser and Python for a quick local preview.

```bash
git clone https://github.com/getkonnekted/Crown.git
cd Crown
python -m http.server 4173
```

Then open **http://localhost:4173**.

> Service workers and installable PWA features require localhost or HTTPS.

## 🧭 Current scope — and what's not here yet

This is an **early MVP**, not a live restaurant database.

- Restaurant listings are sample/demo data; they are not verified live Google Places results.
- There are no accounts, public profiles, friend graph, backend, or cloud sync yet.
- Restaurant crowns are stored in the current browser, so they do not follow you across devices.
- Google Maps handoff uses Maps URLs; no Google API key is required for this prototype.

## 🛠️ Build next

1. Validate whether people find the personal-court concept useful.
2. Add accounts and shareable public courts if the MVP earns that complexity.
3. Evaluate live Places data only after checking cost, attribution, and Google Maps Platform terms.

## 🤝 Contributing

The project is in its early prototype stage. Issues and focused suggestions are welcome; please keep proposals grounded in the current MVP.

---

<div align="center">

**👑 Crown your favourites. Share your taste.**

<sub>Built for a Lagos-first restaurant discovery experience.</sub>

</div>
