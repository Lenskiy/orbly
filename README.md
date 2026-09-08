# Orbly — landing site

Marketing site for **Orbly**: any message becomes a circular glyph — a key
only a scan can open. Print it on a tee, a wall, a tote, a card.

A single static page, no build step. Open `index.html` or serve the folder.

```
index.html      one scrolling page: hero · how it works · gallery · footer
assets/         glyph images (g1–g6, ps, pm)
```

The hero glyph is rendered live on a `<canvas>` (192-dimensional signed
tendril encoding of *"Creativity is contagious, pass it on"*). Everything
else is plain HTML/CSS — IBM Plex Sans, ink-blue ground, orange accent.

## Deploy

Served via GitHub Pages from `main` / root. To use the custom domain,
add a `CNAME` file containing `orbly.to` and point the domain's DNS at
GitHub Pages.
