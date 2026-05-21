# ashokg.dev

Personal portfolio site for Ashok Gudivada — Full Stack Engineer (AI/ML) at Verizon.

**Live:** [ashokg.dev](https://ashokg.dev)

## Stack

Single-file static site — no build step, no framework, no dependencies.

- `index.html` — markup, CSS, and JS in one file
- `robots.txt` + `sitemap.xml` — SEO
- `CNAME` — custom domain (GitHub Pages)

## Features

- Dark / light theme with system preference + localStorage persistence
- Animated hero with HW × SW PCB-trace canvas
- RF signal-wave canvas strip
- `Cmd+K` terminal with whoami / skills / experience / projects commands
- Scroll-reveal animations + IntersectionObserver-driven section nav
- Honors `prefers-reduced-motion`; pauses canvas work when off-screen

## Local development

```sh
# any static server works
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

Pushed to `main` → GitHub Pages serves from the root → resolves at `ashokg.dev` via the `CNAME` record.
