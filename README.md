<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF9933,50:FFFFFF,100:128807&height=200&section=header&text=80%20Years%20of%20Freedom&fontSize=42&fontColor=0B1F6B&animation=fadeIn&fontAlignY=38&desc=A%20Liquid%20Glass%20Tribute%20to%20India&descAlignY=58&descSize=18" />

[![View Live](https://img.shields.io/badge/View-Live%20Demo-FFD54A?style=for-the-badge&logo=vercel&logoColor=black)](#)
[![Made with HTML CSS JS](https://img.shields.io/badge/Made%20with-HTML%20%7C%20CSS%20%7C%20JS-FF9933?style=for-the-badge)](#)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-128807?style=for-the-badge)](#)

</div>

---

## 🇮🇳 About

A single-page tribute site built for India's 80th year of independence — done up in a **liquid glass** aesthetic: molten SVG blobs that merge into each other, frosted glassmorphism cards, a spinning 24-spoke Ashoka Chakra, and a headline text that ripples like disturbed water. Everything is tricolor-themed, from the background ambience to the scroll-triggered timeline.

No frameworks, no build step, no image assets — every visual is CSS, SVG, and vanilla JavaScript in one file.

## ✨ Features

- **Hero** — spinning Ashoka Chakra, tricolor liquid-gradient headline with an SVG turbulence ripple filter
- **Timeline** — scroll-reveal history of 1857 → 1947, zigzag layout on desktop, single-rail on mobile
- **Heroes of the Nation** — flip cards (hover on desktop, tap on mobile) for freedom fighters
- **Achievements** — count-up stat counters that animate once they enter the viewport
- **Vision 2047** — parallax section on India's Amrit Kaal goals
- **Anthem toggle** — a play/pause button wired up for your own instrumental audio file
- **Liquid cursor** — a custom cursor blob on desktop that scales on hover (auto-disabled on touch)
- Fully responsive, `prefers-reduced-motion` aware, and tuned for mobile performance (lighter blur radius, fewer background blobs, throttled scroll handlers)

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, backdrop-filter, SVG filters) |
| Interactivity | Vanilla JavaScript (no libraries) |
| Fonts | [Cinzel](https://fonts.google.com/specimen/Cinzel), [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts |

## 📁 Project Structure

```
.
├── index.html          # everything — markup, styles, and script in one file
└── audio/
    └── anthem.mp3       # optional — drop your own instrumental track here
```

## 🚀 Running It Locally

No build tools needed — it's a static page.

```bash
git clone https://github.com/k4hav/<repo-name>.git
cd Independence

```

Then just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 5500
```

### Adding the anthem audio (optional)

Create an `audio` folder next to `index.html` and drop in a file named `anthem.mp3`. The play/pause button in the footer is already wired up — no code changes needed.

## 📱 Mobile Notes

- Custom cursor and hover effects are auto-disabled on touch devices via feature detection
- Flip cards respond to a single tap (not hover-then-tap)
- Blur intensity and background blob count are reduced under 640px for smoother scrolling

## 🙏 Credits

Built by **[@k4hav](https://github.com/k4hav)**

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:128807,50:FFFFFF,100:FF9933&height=100&section=footer" />
</div>
