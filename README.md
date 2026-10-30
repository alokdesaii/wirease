<p align="center">
  <a href="https://wirease.vercel.app">
    <img src="assets/wirease-logo-horizontal.svg" alt="Wirease" width="320">
  </a>
</p>

<h3 align="center">Send money from Hong Kong to 100+ countries — faster, easier and cheaper.</h3>

<p align="center">
  <a href="https://wirease.vercel.app"><strong>Live site →</strong></a>
</p>

<p align="center">
  <img alt="Static" src="https://img.shields.io/badge/build-none-21262b?style=flat-square">
  <img alt="GSAP" src="https://img.shields.io/badge/motion-GSAP-14bdb7?style=flat-square">
  <img alt="D3" src="https://img.shields.io/badge/globe-d3%20%2B%20canvas-0d61a6?style=flat-square">
  <img alt="Vercel" src="https://img.shields.io/badge/hosted%20on-Vercel-21262b?style=flat-square&logo=vercel">
</p>

---

## About

The marketing homepage for **Wirease**, a Hong Kong–based cross-border payments company regulated by the Customs and Excise Department (C&ED), serving 100+ countries in 50+ currencies.

It covers the four lines of business:

| | |
|---|---|
| **Home remittance** | Send to family abroad at competitive rates |
| **Business payments** | Multi-currency payments for companies |
| **Wholesale banknotes** | 50+ currencies of physical banknotes |
| **IMTS platform** | Remittance infrastructure for partner brands |

## Highlights

- **Live calculator**: indicative HKD rates from [open.er-api.com](https://open.er-api.com) across 21 corridors, with static fallbacks.
- **Rotating globe**: a canvas orthographic projection with animated payment arcs, drag to spin.
- **Isometric Hong Kong**: a generated SVG city with traffic, a ferry and a payment route.
- **Scroll motion**: GSAP + ScrollTrigger reveals, odometer stats and a sticky solutions section.
- **No build step**: one `index.html`, CDN libraries, nothing to install.

## Brand

| Token | Hex | |
|---|---|---|
| Blue | `#0d61a6` | ![](https://img.shields.io/badge/-%20-0d61a6?style=flat-square) |
| Teal | `#14bdb7` | ![](https://img.shields.io/badge/-%20-14bdb7?style=flat-square) |
| Ink | `#21262b` | ![](https://img.shields.io/badge/-%20-21262b?style=flat-square) |
| Mist | `#d2d6dc` | ![](https://img.shields.io/badge/-%20-d2d6dc?style=flat-square) |
| Paper | `#f9fafb` | ![](https://img.shields.io/badge/-%20-f9fafb?style=flat-square) |

Typeface: [Archivo](https://fonts.google.com/specimen/Archivo).

## Run locally

```bash
python3 -m http.server 5173
```

Then open <http://localhost:5173>.

## Deploy

```bash
vercel deploy --prod
```

`vercel.json` tells Vercel to serve the files as a static site, with no build.

## Structure

```
index.html              the homepage (markup, styles, scripts)
assets/
  favicon.svg
  wirease-logo-horizontal.svg
  wirease-wordmark.svg
  hk-skyline.svg
vercel.json
```

---

<p align="center"><sub>© Wirease Limited · Hong Kong</sub></p>
