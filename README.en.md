# 🗺️ Exploring Europe · A Romantic Italy + France Trip

[English](README.en.md) | [中文](README.md)

> **Luo & Chao's Europe Trip** · April 2026 · Italy + France · A static single-page travel planner

🌐 **Live site**: Deployed on Vercel (see `vercel.json`)

---

## ✨ What's this

A single-page Europe travel planner made for us, including:

- 🗺️ **Leaflet interactive map** — every stop's coordinates and animated routes
- 📅 **Day-by-day itinerary** — Paris · Rome · Milan · Florence, highlights per day
- 🏛️ **Places to see** — must-visits and hidden gems
- 🍝 **Food guide** — local specialties and must-try restaurants
- 🛏️ **Lodging & transport** — hotels, flights, trains
- 💰 **Budget sheet** — estimated spending per category

**Design vibe**: warm European palette (light blue + orange) + large, airy typography + glassmorphism nav.

---

## 🚀 Run locally

```bash
# 1. Clone
git clone https://github.com/znzjLuo1008-netizen/europe-trip.git
cd europe-trip

# 2. Start a static server (pick one)
python3 -m http.server 8080
# or: npx serve .

# 3. Open in browser
open http://localhost:8080
```

---

## 🏗 Structure

```
europe-trip/
├── index.html         ← Main page (CSS + JS + data inline)
├── assets/            ← Images (cities, landmarks, food)
└── vercel.json        ← Vercel deployment config (SPA routing)
```

**Tech stack**:
- HTML5 + inline CSS + Vanilla JS
- Leaflet 1.9.4 (maps)
- Noto Sans SC (Chinese font)

---

## 🎨 Design Language

- **Palette**: light-blue `#f3faff` → white `#ffffff` gradient bg, accent `#2563eb` (blue) + `#f97316` (orange)
- **Radius**: 18–22px
- **Shadow**: soft `0 10px 30px rgba(15,23,42,.08)`
- **Nav**: glassmorphism with `backdrop-filter: blur(10px)`

---

## 📌 Changelog

- 2026-04-04 First release
- 2026-05-07 Added bilingual README

---

## 💝 Made for

For Chao who traveled with me, and for a future us who'll go again ☀️

---

## 📜 License

MIT · © 2026 Luo Luo
