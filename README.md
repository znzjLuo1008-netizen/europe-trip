# 🗺️ 探索欧罗巴：意法浪漫之约

[English](README.en.md) | [中文](README.md)

> **罗崽 × 超崽的欧洲之行** · 2026 年 4 月 · 意大利 + 法国 · 纯静态单页旅行规划器

🌐 **在线访问**：部署在 Vercel（域名见 `vercel.json`）

---

## ✨ 这是什么

一份做给自己看的欧洲行程单页网站，包含：

- 🗺️ **Leaflet 交互地图** — 行程每一站的坐标、路线动画
- 📅 **Day-by-day 日程** — 巴黎 · 罗马 · 米兰 · 佛罗伦萨 每日看点
- 🏛️ **景点清单** — 精选必去和小众打卡点
- 🍝 **美食攻略** — 当地特色餐厅与必吃
- 🛏️ **住宿 / 交通** — 酒店、机票、高铁等交通衔接
- 💰 **预算表** — 各项花销估算

**设计理念**：浅蓝配橙的温暖欧洲风 + 大字号轻量排版 + 玻璃拟态导航栏。

---

## 🚀 本地预览

```bash
# 1. 克隆
git clone https://github.com/znzjLuo1008-netizen/europe-trip.git
cd europe-trip

# 2. 起静态服务（任选）
python3 -m http.server 8080
# 或 npx serve .

# 3. 打开
open http://localhost:8080
```

---

## 🏗 文件结构

```
europe-trip/
├── index.html         ← 主页面（含 CSS + JS + 行程数据）
├── assets/            ← 图片资源（城市、地标、美食）
└── vercel.json        ← Vercel 部署配置（SPA 路由）
```

**技术栈**：
- HTML5 + Inline CSS + Vanilla JS
- Leaflet 1.9.4（地图）
- Noto Sans SC（中文字体）

---

## 🎨 设计语言

- **配色**：浅蓝 `#f3faff` → 白 `#ffffff` 渐变底，主色 `#2563eb`（蓝）+ `#f97316`（橙）
- **圆角**：18-22px
- **阴影**：柔光 `0 10px 30px rgba(15,23,42,.08)`
- **导航栏**：毛玻璃 `backdrop-filter: blur(10px)`

---

## 📌 更新记录

- 2026-04-04 初版上线
- 2026-05-07 README 双语化

---

## 💝 送给谁

送给同行的超崽，和未来还会再去欧洲的我们自己 ☀️

---

## 📜 License

MIT · © 2026 小罗
