# Thrust Dynamics — pre-launch site

Static marketing site for Thrust Dynamics (compact micro gas-turbine propulsion for
high-speed UAVs). Single self-contained `index.html` (inline CSS + JS) plus `assets/`.
No build step.

## Deploy (Cloudflare Pages)

- **Framework preset:** None
- **Build command:** *(leave empty)*
- **Build output directory:** `/`

Cloudflare Pages serves the repo root as-is and redeploys on every push to `main`.

## Local preview

```bash
npx serve -p 3901 .
# then open http://localhost:3901
```

## Notes

- The large raw DaVinci source clips (`assets/video/hero/`, `assets/video/sequence/`,
  `hero-loop.mp4`) are intentionally git-ignored — the site only serves
  `assets/video/hero-master.mp4`, `hero-master-720.mp4`, and `turbine-cinematic-loop.mp4`.
