# Diwash Koirala — Portfolio

A production-ready personal portfolio website built with pure HTML, CSS, and JavaScript.

## Files

```
portfolio/
├── index.html    ← Main HTML structure
├── style.css     ← All styles (dark editorial aesthetic)
├── main.js       ← Interactions, animations, scroll effects
└── README.md
```

## Features

- Dark editorial aesthetic with grain overlay
- Custom cursor with trailing animation
- Smooth scroll + active nav highlighting
- Intersection Observer scroll reveals
- Animated skill bars
- Staggered project card animations
- Light/dark mode toggle (persisted via localStorage)
- Hero parallax grid on mouse move
- Fully responsive (mobile hamburger menu)
- Zero dependencies — no frameworks, no build tools

## Run Locally

Just open `index.html` in any browser. No build step needed.

Or use a local server for best results:
```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Then open: `http://localhost:8080`

## Deploy to GitHub Pages

1. Push all files to a GitHub repo
2. Go to **Settings → Pages**
3. Source: **Deploy from branch → main → / (root)**
4. Your site will be live at: `https://yourusername.github.io/repo-name`

## Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel

# Follow prompts — site goes live instantly
```

## Customization

- Update GitHub/email/LinkedIn links in `index.html`
- Adjust accent color: change `--accent` in `:root` in `style.css`
- Add/remove projects in the `.projects-grid` section

## Fonts Used

- **Syne** — Display / headings (Google Fonts)
- **DM Mono** — Body / code labels (Google Fonts)  
- **Instrument Serif** — Italic accent in hero name (Google Fonts)
