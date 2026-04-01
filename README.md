# Advokat Olivera Kantar — Website

Trilingual law office website for Olivera Kantar, Kikinda, Serbia.

**Live:** https://advokat-olivera-kantar.pages.dev

## Languages
- Serbian (Latin)
- Serbian (Cyrillic)
- English (US)

## Stack
- Pure HTML/CSS/JS — no build step, no dependencies
- Deployed via Cloudflare Pages

## Structure
```
/
└── index.html        # Full website (single file)
└── README.md
└── .gitignore
```

## Deployment
Connected to Cloudflare Pages. Every `git push` to `main` triggers an automatic redeploy.

## To update content
Replace all placeholder values in `index.html`:
- `+381 XX XXX-XXX` → real phone number
- `office@advokat-kantar.rs` → real email address
- `po dogovoru` → real working hours
- Photographer image → replace the SVG placeholder with `<img src="photo.jpg" alt="Olivera Kantar, advokat">`
- Hero stats (15+, 500+) → real figures
- Domain in `<link rel="canonical">` and Schema.org `url` field
