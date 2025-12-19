# Limova clone (Astro)

This project was generated from the provided `code.pdf` and aims to reproduce the same page structure/styles.

## Run locally
```bash
npm install
npm run dev
```

## Deploy to Vercel
- Import this repo in Vercel (GitHub).
- Framework preset: Astro
- Build command: `npm run build`
- Output: `dist/`

Notes:
- The page references external Webflow assets (CSS/JS/images) hosted on `cdn.prod.website-files.com`.
- If you want a fully self-hosted version, we can mirror those assets into `/public` and update links.
