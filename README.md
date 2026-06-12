# KKU-COCAI 2040 🎓

> **AI as a horizontal capability — built by the College of Computing, for every domain, every discipline.**

A strategic roadmap website for the **College of Computing & Artificial Intelligence, Khon Kaen University** — presenting a 15-year vision (2026–2040) to become Southeast Asia's premier AI research and education hub.

---

## 📋 What's Inside

A single-file HTML website covering the full KKU-COCAI2040 strategic roadmap:

| Section | Description |
|---|---|
| **Hero** | Animated dark hero with wordmark, stats strip, and CTAs |
| **Vision & Philosophy** | Core philosophy and 4 strategic pillars |
| **AI as Horizontal Layer** | Domain × Phase capability matrix |
| **Three Strategic Phases** | Foundation → Expansion → Leadership (2026–2040) |
| **Six Research Domains** | GeoAI, Medicine, Quantum, HCAI, Education, Agentic AI |
| **Teaching · Research · Impact** | Stanford HAI 3-Pillar strategy table |
| **2040 Targets** | 7 measurable success metrics |
| **References & Credits** | Stanford HAI, MIT CSAIL, Google DeepMind, MIT CISR, Georgia Tech, NAIRR |

---

## 📱 Mobile-First Design

Fully responsive across **iPhone, Samsung, and all modern devices**:

- **Hamburger drawer navigation** — smooth slide-in panel with backdrop dismiss, ESC key, and swipe-to-close
- **Safe area insets** — `env(safe-area-inset-*)` for iPhone notch, Dynamic Island, and Samsung punch-hole cameras
- **`100svh` hero** — avoids iOS Safari toolbar clipping on full-screen hero sections
- **Fluid typography** — `clamp()` everywhere; text scales beautifully from 375px to 1440px+
- **Horizontal scroll tables** — capability matrix and strategy pillars scroll smoothly with `-webkit-overflow-scrolling: touch`
- **44px minimum tap targets** — all buttons and links meet Apple/Google accessibility guidelines
- **Responsive grids** — 3-col → 2-col → 1-col at appropriate breakpoints

### Breakpoints

| Breakpoint | Layout |
|---|---|
| `> 960px` | Full desktop — 3-column grids, side-by-side philosophy |
| `680px – 960px` | Tablet — 2-column grids, stacked phases |
| `< 680px` | Mobile — single column, hamburger nav, full-width buttons |
| `< 400px` | Small mobile — condensed typography and single-column targets |

---

## 🗂 File Structure

```
cocai-2040-mobile.html   # Complete website (HTML + CSS + JS, single file)
README.md                # This file
```

Everything is self-contained. Fonts load from Google Fonts CDN. No frameworks, no build tools, no package.json.

---

## 🎨 Design System

### Color Palette

| Token | Hex | Usage |
|---|---|---|
| `--navy` | `#0A1628` | Primary background, headings |
| `--crimson` | `#8B1A2F` | Brand accent, eyebrows, CTAs |
| `--teal` | `#0E7C6E` | Phase I / Foundation |
| `--purple` | `#5C3D99` | Phase II / Expansion |
| `--amber` | `#C97B1A` | Phase III / Leadership |
| `--slate` | `#F7F8FA` | Alternate section background |

### Typography

| Role | Font | Weight |
|---|---|---|
| Wordmark / Hero | DM Sans | 200 (ultralight) |
| Section titles | Inter | 700 |
| Pull quotes | Playfair Display | 700 italic |
| Body / UI | Inter | 400, 500, 600 |

### Animations

- **Hero grid drift** — subtle perspective movement on the dot grid background
- **Radial glow pulses** — soft color orbs that breathe on the hero
- **Scroll reveals** — `IntersectionObserver`-driven `fadeUp` with staggered delays
- **Nav transition** — transparent → frosted glass on scroll (`backdrop-filter: blur(20px)`)
- **Scroll indicator** — animated drop-line guides first-time visitors

All animations respect `prefers-reduced-motion`.

---

## 🏛 Strategic Framework

KKU-COCAI 2040 is organized around three interlocking ideas:

### Three Phases

```
2026 ──────────── 2030 ──────────── 2035 ──────────── 2040
   [ Foundation ]      [ Expansion ]      [ Leadership ]
   Infra · Talent      Centers · Degrees  Top 3 ASEAN
```

### Six Research Domains

1. 🌍 **GeoAI & Geoscience** — Remote sensing, climate AI, smart agriculture
2. 🩺 **AI + Medicine & Health** — Medical imaging, drug discovery, clinical AI
3. ⚛️ **Quantum Computing** — Quantum ML, post-quantum cryptography
4. 🧑‍💻 **Human-Centered AI** — Ethics, explainability, ASEAN AI governance
5. 📚 **AI for Education & Society** — Intelligent tutoring, adaptive learning, smart city
6. 🤖 **Agentic AI & Foundation Models** — Thai/ASEAN LLMs, multi-agent systems, robotics

### Three Pillars (Stanford HAI Framework)

Every domain operates across **Teaching**, **Research**, and **Impact** — simultaneously and at every phase.

---

## 📚 References & Inspiration

| Institution | Framework Borrowed |
|---|---|
| [Stanford HAI](https://hai.stanford.edu) | 3-Pillar Framework (Research · Education · Impact) |
| [MIT CSAIL](https://csail.mit.edu) | Research priority areas (physics-guided DL, liquid networks, robotics) |
| [Google DeepMind](https://deepmind.google) | "AI in 2030" long-term capability projections |
| [MIT CISR](https://cisr.mit.edu) | 4-Stage AI Maturity Model → COCAI's three phases |
| [Georgia Tech](https://gatech.edu) | Jill Watson ITS, AI-Powered Learning framework |
| NAIRR | Open compute & dataset infrastructure model |

Frameworks were adapted — not copied — for the unique context of **Khon Kaen University** and Northeast Thailand.

---

## 🌏 Context

**Khon Kaen University (KKU)** is Thailand's leading university in the Northeast (Isan) region. The College of Computing & AI sits at the intersection of:

- A world-class KKU Medical Faculty and Hospital (AI + Medicine partnership)
- Isan's agricultural heartland (GeoAI, smart farming, flood prediction)
- ASEAN's emerging AI governance needs (Human-Centered AI, ethics policy)
- Thailand's national AI strategy and digital economy agenda

KKU-COCAI's mission: embed AI not as a silo, but as a **horizontal capability** across every school, every faculty, every discipline at KKU — and beyond.

---

## 📄 License

This project is an academic strategic planning document produced by the College of Computing & Artificial Intelligence, Khon Kaen University. Referenced frameworks belong to their respective institutions (Stanford HAI, MIT, Google DeepMind, etc.).

---

*College of Computing & Artificial Intelligence · Khon Kaen University*  
*123 Mitraphap Road, Khon Kaen 40002, Thailand*  
*[kku.ac.th](https://kku.ac.th)*

---

## 📖 Citation

If you use this project, please cite it as:

```bibtex
@misc{panboonyuen2026kkucocai2040,
  author       = {Teerapong Panboonyuen},
  title        = {KKU-COCAI2040: Strategic Roadmap for the College of Computing, Khon Kaen University},
  year         = {2026},
  institution  = {College of Computing, Khon Kaen University},
  address      = {Khon Kaen, Thailand},
  note         = {Strategic vision document and interactive web publication},
  url          = {https://github.com/<username>/kku-cocai-2040}
}
```

---