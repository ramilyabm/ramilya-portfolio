# Ramilya Bakiyeva — Portfolio Website

Professional portfolio built with **Astro 5**, **Tailwind CSS**, and deployed on **Vercel**.

## Pages

- `/` — Home (hero, highlight cards, value prop)
- `/experience` — Professional timeline (P&G, AIESEC, teaching)
- `/projects` — Technical portfolio (4 deployed projects)
- `/education` — Degrees, exchange programs, certifications
- `/about` — Personal story, Clifton Strengths, music
- `/contact` — Email, LinkedIn, phone, contact form

## Local Development

```bash
npm install
npm run dev        # starts at http://localhost:4321
npm run build      # outputs to ./dist
npm run preview    # preview production build
```

Requires Node.js 18+.

## Deploy to Vercel (Free)

1. Push this repo to GitHub (public or private).
2. Go to [vercel.com](https://vercel.com) → sign in with GitHub.
3. Click **"New Project"** → import this repo.
4. Vercel auto-detects Astro. Click **Deploy**.
5. Done. Every push to `main` auto-deploys.

## TODOs Before Going Live

- [ ] Replace placeholder GitHub URL in `Footer.astro` with your actual GitHub profile.
- [ ] Replace `YOUR_FORM_ID` in `contact.astro` with a real [Formspree](https://formspree.io) form ID (free).
- [ ] Add YouTube embed URLs in `about.astro` for music/singing videos.
- [ ] Add project screenshots to `/public/` and reference in `projects.astro`.
- [ ] Add professional photo to `/public/` and add to home page hero.
- [ ] Add resume PDF to `/public/resume.pdf` and link from home page.
- [ ] Update live URLs for AI Strategy Analyzer and AI Startup ROI Mapping in `projects.astro`.
- [ ] Optional: Buy a custom domain (e.g., ramilya.dev) and connect in Vercel dashboard.
- [ ] Update `site` in `astro.config.mjs` to match your final domain.
