# sankalpshetty.com

Minimal "Coming soon" landing page for **sankalpshetty.com**.

- Single static `index.html` — no build step.
- Typeface: **Aleo** (Google Font), ExtraLight (200), with **Noto Sans** ExtraLight as the fallback.
- Tracking: **-4%** (`letter-spacing: -0.04em`).
- Two left-aligned lines ("Coming" / "soon"), vertically centered on mobile and desktop.
- Graceful on-load ink fade: text emerges white → soft grey → black (honors `prefers-reduced-motion`).

## Deploy

Hosted on Vercel. Any push to `main` auto-deploys. The custom domain `sankalpshetty.com` is attached in the Vercel project's **Domains** settings.
