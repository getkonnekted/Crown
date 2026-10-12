<div align="center">

# 👑 CROWN & COUP

### Good food deserves a crown.

**A Lagos-first restaurant discovery experience — meet the contenders, crown your favourites, and share your food court.**

<br />

![PWA](https://img.shields.io/badge/PWA-installable-255B45?style=for-the-badge&logo=pwa)
![Status](https://img.shields.io/badge/status-MVP-CCF36B?style=for-the-badge&labelColor=18251D)
![Focus](https://img.shields.io/badge/launch-market-Lagos-F28C45?style=for-the-badge&labelColor=18251D)
![License](https://img.shields.io/badge/license-not%20specified-lightgrey?style=for-the-badge)

<br />

**[🚀 Open the homepage](https://crown-ivory-phi.vercel.app) · [🍽️ Enter the app](https://crown-ivory-phi.vercel.app/play/) · [🧑‍💻 Explore the repository](https://github.com/getkonnekted/Crown)**

</div>

---

## ✳️ The idea

Choosing where to eat shouldn't mean starting from zero every time.

**Crown & Coup** is a mobile-first progressive web app prototype for keeping a personal shortlist of favourite restaurants. Crown one pick per cuisine, revisit your choices, and share them with people who trust your taste.

> **The product principle:** your personal recommendations first; broader discovery can come next.

## 🟩 What works in this MVP

| Feature | What it does |
| --- | --- |
| 🔎 **Find a restaurant** | Search sample listings by name, cuisine, or neighbourhood. |
| 👑 **Crown a favourite** | Keep one crowned restaurant per cuisine; choosing another replaces the previous pick. |
| 💾 **Keep your court** | Your selections persist in this browser using local storage. |
| 📤 **Share your taste** | Share your court or open a dedicated restaurant page with its own Open Graph title, description, and image. |
| 🗺️ **Continue in Maps** | Open a restaurant search in Google Maps. |
| 📱 **Installable shell** | A shared design system, PWA manifest and service worker support installation on compatible browsers. |

## 🎨 Shared design system

The landing page, restaurant discovery app, and every restaurant profile share `assets/crown.css` and the Crown & Coup favicon in `assets/crown-icon.svg`. The palette uses deep plum, warm cream, crown gold, and tomato coral; restaurant imagery is varied by cuisine and remains clearly marked as illustrative.

## 🎨 Product feel

<div align="center">

| 🍇 Deep plum | 🌼 Crown gold | 🥛 Warm cream | 🍅 Tomato coral |
|:---:|:---:|:---:|:---:|
| `#2B1D35` | `#F4C95D` | `#FAF5EE` | `#F36B4F` |

*An editorial, food-forward visual direction built to feel at home on mobile.*

</div>

## ⚙️ Run locally

You only need a browser and Python for a quick local preview.

```bash
git clone https://github.com/getkonnekted/Crown.git
cd Crown
python -m http.server 4173
```

Then open **http://localhost:4173** for the landing page. Choose **Enter Crown & Coup** to open the app at `/play/`.

> Service workers and installable PWA features require localhost or HTTPS.

## 🧭 Current scope — and what's not here yet

This is an **early MVP**, not a live restaurant database.

- Restaurant listings are sample/demo data; they are not verified live Google Places results.
- Restaurant card and link-preview images are illustrative Unsplash food photography, not verified photos of the named venues. The app does not scrape Google Maps or call Google Places.
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

**👑 Meet the contenders. Crown the winner.**

<sub>Built for a Lagos-first restaurant discovery experience.</sub>

</div>
