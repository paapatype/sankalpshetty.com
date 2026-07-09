# sankalpshetty.com

**STEEL BREATH** — the coming-soon landing page for **sankalpshetty.com**.

A full-bleed sheet of brushed, fogged stainless steel. A slow press (or touch) wicks the
condensation away in a watery bloom to reveal **COMING SOON** debossed into the metal —
etched from behind, catching a thread of light along each groove. Release, and after a held
breath the surface slowly re-fogs. On load the words breathe in and out on their own so the
message always lands and the gesture is taught.

- Single self-contained `index.html` — no build step. **Canvas 2D** rendering engine; **GSAP**
  (CDN, with an inline rAF-lerp fallback) drives the slow-press reveal, pointer inertia, and the
  exhale re-fog.
- Typeface: **Aleo** ExtraLight (200), uppercase — baked into the etched wordmark, so the hero is
  font-independent after load.
- Desktop (pointer) + mobile (touch); the render loop sleeps when idle to save battery.
- Robust: honors `prefers-reduced-motion` (static frame), a `<noscript>` steel fallback, an
  always-present semantic `<h1>` for SEO/accessibility, and a DPR/pixel guard for large displays.

## Deploy

Hosted on Vercel — pushes to `main` auto-deploy. The custom domain `sankalpshetty.com` is
attached in the Vercel project and pointed there via GoDaddy DNS (`A @ → 76.76.21.21`).
