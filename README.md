# gitmyphotos-site

Landing page for [GitMyPhotos](https://github.com/SiddarthAA/gitmyphotos) — a self-hosted, GitHub-native photo storage pipeline. No cloud dependency, no subscription, no lock-in.

Built with plain HTML, Tailwind CSS (CDN), and vanilla JS.

---

## Deploy on Vercel

### One-click

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/SiddarthAA/gitmyphotos-site)

### Manual

```bash
# 1. Install Vercel CLI
npm i -g vercel

# 2. Clone the repo
git clone https://github.com/SiddarthAA/gitmyphotos-site
cd gitmyphotos-site

# 3. Deploy
vercel
```

Vercel will detect a static site automatically — no build step, no configuration needed.

**Production deploy:**
```bash
vercel --prod
```

---

## Local preview

```bash
# Any static file server works
npx serve .
# → http://localhost:3000
```

Or just open `index.html` directly in a browser.

---

## Project structure

```
gitmyphotos-site/
└── index.html   # entire site — single self-contained file
```

---

## Stack

| Thing | What |
|---|---|
| Markup | HTML5 |
| Styles | Tailwind CSS via CDN |
| Fonts | Bebas Neue, DM Mono, Inter (Google Fonts) |
| Scroll | Lenis smooth scroll |
| Icons | Iconify |
| Hosting | Vercel (static) |

---

## License

MIT — see the [main repo](https://github.com/SiddarthAA/gitmyphotos) for full details.
