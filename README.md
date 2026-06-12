# Task1-Kavali-Ajay-Kumar
# 🎮 R-Force Games — Ultra 3D Gaming Platform

<div align="center">

![R-Force Games Banner](https://img.shields.io/badge/R--FORCE-GAMES-00FFFF?style=for-the-badge&labelColor=050816&color=00FFFF)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Canvas API](https://img.shields.io/badge/Canvas_API-FF00FF?style=for-the-badge&labelColor=050816&color=8B5CF6)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A next-generation futuristic 3D gaming platform — 100% free, no downloads, no frameworks.**

[🚀 Live Demo](#) · [📦 Download](#) · [🐛 Report Bug](../../issues) · [✨ Request Feature](../../issues)

</div>

---

## 📸 Preview

> A cyberpunk-themed, fully animated gaming universe built entirely with vanilla HTML, CSS, and Canvas API — no external JS frameworks required.

```
┌─────────────────────────────────────────────────────┐
│  🎮  PLAY GAMES WITHOUT LIMITS                       │
│      Live 3D controller · Particle system            │
│      Orbiting rings · Mouse-reactive parallax        │
├─────────────────────────────────────────────────────┤
│  📊 Stats  │  🔍 Search  │  🃏 Games  │  🌐 Categories │
├─────────────────────────────────────────────────────┤
│  🔥 Trending Carousel  │  ✨ Features  │  💬 Testimonials │
└─────────────────────────────────────────────────────┘
```

---

## ✨ Features

### 🌌 Hero Experience
- **Live Canvas Animation** — real-time 3D glowing controller drawn with Canvas API
- **Mouse Parallax** — controller, stars, and grid all shift with cursor movement
- **Particle System** — 80 floating neon particles + 200 twinkling star field
- **Orbiting Rings** — 3 elliptical orbit rings with a live orbiting dot
- **Animated Geometry** — 12 floating hexagons, diamonds, and triangles
- **Perspective Grid** — neon grid that follows mouse movement

### 🧭 Navigation
- Glassmorphism navbar with `backdrop-filter: blur`
- Neon underline hover animations
- Sticky floating position with frosted glass background
- Cyberpunk clipped-corner CTA button

### 🃏 Featured Games
- **6 holographic game cards** (Cyber Warriors, Racing Legends, Battle Arena, Zombie Survival, Football Champions, Space Explorer)
- **3D Tilt Effect** — `perspective()` transform tracks mouse in real time on each card
- Holographic shimmer sweep on hover
- Animated badge labels (HOT / NEW / TOP / LIVE)
- Genre tags, star ratings, and neon Play buttons

### 🌐 Categories Universe
- **8 floating category cubes** — Action, Racing, Adventure, Sports, Puzzle, Strategy, Shooting, Multiplayer
- Animated floating icons with `drop-shadow` glow
- Alternating cyan / purple / magenta color themes per category

### 📡 Trending Carousel
- **Infinite auto-scroll** with CSS `@keyframes`
- Pauses on hover
- Seamlessly duplicated track for endless loop
- 12 game cards with emoji previews

### 🔍 AI-Powered Search
- Animated neon search bar with `clip-path` geometry
- 6 filter toggle buttons — All, Action, Sports, Multiplayer, New Releases, Most Popular
- Futuristic input glow on focus

### 📊 Statistics Dashboard
- **Animated counters** triggered by `IntersectionObserver` on scroll
- 10M+ Players · 500+ Games · 100+ Tournaments · 50+ Categories
- Glassmorphism stat cards with top-border glow on hover

### 💡 Why R-Force Section
- 6 feature cards with animated bottom-border reveal
- 100% Free · Instant Play · No Downloads · Multiplayer · Cloud Gaming · Mobile Friendly

### 💬 Testimonials
- 3 floating glassmorphism cards with CSS float animation
- Gradient avatar initials, neon purple borders
- Pause-on-hover animation control

### 🦶 Footer
- 4-column grid layout (Brand · Community · Support · Company)
- Social link icons with neon hover glow
- Radial gradient particle background
- Privacy Policy, Terms, Cookies links

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure, single-file architecture |
| **CSS3** | Glassmorphism, `clip-path`, `backdrop-filter`, animations |
| **Vanilla JavaScript** | Interactivity, scroll observers, counters |
| **Canvas 2D API** | Hero animation — controller, particles, stars, geometry |
| **Google Fonts** | Orbitron (display) + Rajdhani (body) |
| **IntersectionObserver API** | Scroll-triggered stat counters and reveal animations |

> **Zero external JS libraries.** No React, no Three.js, no GSAP, no jQuery — pure browser APIs only.

---

## 🚀 Getting Started

### Option 1 — Open directly
```bash
# Just open the file in any modern browser
open rforce-games.html
```

### Option 2 — Serve locally
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# VS Code
# Use the Live Server extension
```

Then visit `http://localhost:8000/rforce-games.html`

### Requirements
- Any modern browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- No build tools, no npm install, no dependencies

---

## 📁 Project Structure

```
rforce-games/
│
├── rforce-games.html       # Complete platform — all HTML, CSS, JS in one file
└── README.md               # This file
```

The entire project ships as a **single self-contained HTML file** (~18KB gzipped). All styles and scripts are inlined for maximum portability.

---

## 🎨 Color System

| Role | Name | Hex |
|---|---|---|
| Primary | Electric Cyan | `#00FFFF` |
| Secondary | Neon Purple | `#8B5CF6` |
| Accent | Magenta | `#FF00FF` |
| Background | Deep Space Black | `#050816` |
| Surface | Dark Navy | `#0a0f2e` |
| Text | White | `#FFFFFF` |

**Typography**
- Display / Headings — [Orbitron](https://fonts.google.com/specimen/Orbitron) (400, 700, 900)
- Body / UI — [Rajdhani](https://fonts.google.com/specimen/Rajdhani) (300, 400, 600, 700)

---

## 🧩 Sections Overview

| # | Section | Description |
|---|---|---|
| 1 | **Hero** | Full-screen live canvas with 3D controller and parallax |
| 2 | **Stats** | Animated scroll-triggered counters |
| 3 | **Search** | AI-styled search bar with genre filters |
| 4 | **Featured Games** | 6 holographic tilt cards |
| 5 | **Categories** | 8 floating neon category cubes |
| 6 | **Trending** | Infinite auto-scrolling carousel |
| 7 | **Features** | 6 glassmorphism feature cards |
| 8 | **Testimonials** | 3 floating animated review cards |
| 9 | **Footer** | 4-column cyberpunk footer |

---

## ⚙️ Customization

### Add a new game card
Copy any `.game-card` block inside `#games` and update the emoji, title, genre, and rating.

### Change colors
Edit the CSS variables at the top of `<style>`:
```css
:root {
  --cyan: #00FFFF;
  --purple: #8B5CF6;
  --magenta: #FF00FF;
  --bg: #050816;
}
```

### Add carousel items
Push a new object to `trendingData` in the `<script>`:
```js
{ emoji: '🗡️', title: 'Shadow Blade', genre: 'Action' }
```

### Adjust particle count
Change the loop limits in the script section:
```js
for (let i = 0; i < 80; i++) { ... }   // particles
for (let i = 0; i < 200; i++) { ... }  // stars
for (let i = 0; i < 12; i++) { ... }   // geo shapes
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout Changes |
|---|---|
| `> 900px` | Full desktop layout, all columns visible |
| `≤ 900px` | Nav links hidden, 2-col games/categories grid |
| `≤ 540px` | Single column games, 2-col stats, compact hero text |

---

## 🌐 Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile (iOS/Android) | ✅ Responsive |

---

## Author
KAVALI AJAY KUMAR

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

```
MIT License — Copyright (c) 2026 R-Force Games
Permission is granted to use, copy, modify, and distribute this software freely.
```

---


