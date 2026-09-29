# Lumen Clinic — Awwwards-style Clinic Template

A single-page, award-calibre website template for a modern medical clinic.
Built with hand-written HTML/CSS/JS — no framework, no build step. English copy.

**Live demo:** https://mohammedguejjim-hash.github.io/lumen-clinic/

## ✨ Signature effects

- **Preloader** — counter 0→100 with curtain reveal
- **Ink cursor** — dot + trailing ring with `mix-blend-mode: difference`; morphs into a "VIEW" badge on interactive elements
- **Hero** — giant display typography reveal over a parallax image
- **ECG pulse** — a heartbeat line that *draws itself* as you scroll (SVG stroke animation, scroll-scrubbed)
- **Services** — editorial list where the department image follows your cursor on hover
- **Philosophy** — word-by-word text reveal on scroll
- **Stats** — animated counters
- **Lenis** buttery smooth scrolling + GSAP ScrollTrigger throughout
- Strict **black & white** palette, film-grain overlay, marquee strip, hide-on-scroll nav

## 📁 Structure

```
lumen-clinic/
├── index.html          # the whole site (markup + styles + scripts)
├── README.md
└── assets/
    └── img/
        ├── hero.jpg
        ├── service-dental.jpg
        ├── service-derma.jpg
        ├── service-cardio.jpg
        ├── service-pediatrie.jpg
        └── clinic.jpg
```

## 🛠 Customize

| What | Where |
|---|---|
| Texts (English) | `index.html` — search the section comments |
| Images | replace files in `assets/img/` (keep the same names) |
| Colors | CSS `:root` in `index.html` — `--paper`, `--ink` |
| Contact email/phone | search `hello@lumen-clinic.ma` in `index.html` |
| Services | duplicate an `<a class="service">` block, change `data-img`, title, meta |

Libraries load from CDN (GSAP 3.12, ScrollTrigger, Lenis 1.1, Google Fonts). If they fail to load, the site gracefully degrades to a fully readable static page.

## 🚀 Deploy

Any static host works. For GitHub Pages: repo Settings → Pages → Deploy from branch → `main` / root.

---
*Original template. All copy and imagery are AI-generated originals.*
