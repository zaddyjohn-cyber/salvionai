# Salvion AI — Marketing Site

A design-forward, single-file marketing site for **Salvion AI** — *Human Signal Intelligence*. Salvion turns any smartphone or laptop camera into a clinical-grade health-screening platform: 50+ health markers from a single 30-second face scan, no wearables required.

## ✨ Highlights

- **Single self-contained file** — `index.html` with embedded CSS + JS. No build step.
- **Real 3D (Three.js / WebGL)** — particle "signal sphere" hero, a rotating neural-lattice, and a drifting particle CTA field.
- **Animated hero video** — a framed, 3D-tilted "Live Scan" screen with floating vital-sign cards, a scanline sweep and glow frame.
- **Live data feel** — animated ECG sparklines, eight signal waveforms, count-up stats and per-section canvas visualizations.
- **Glassmorphism + neon** design system, scroll-reveal animations, 3D card tilt, fully responsive.
- Sections: Hero · Executive Summary · Problem · Why Now · How It Works · Capabilities · Deep Technology · Signal Coverage · Deployment · Solutions · Competitive Comparison · Developers (SDK/API) · Pricing · FAQ · Medical Disclaimer.

## 🚀 Run locally

It's a static site — just open `index.html` in a modern browser, or serve the folder with any static server:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

> The 3D scenes (Three.js) and fonts load from CDNs, so an internet connection is needed for the full experience. The page degrades gracefully offline — all content and animations still render.

## 📁 Structure

```
index.html      # the entire site
assets/
  hero.mp4      # hero "live scan" demo clip
```

## ⚠️ Notes

- Pricing figures, FAQ answers and the example API snippet are **illustrative placeholders**, not official Salvion data.
- The site is for demonstration/marketing purposes. See the in-page medical disclaimer.
